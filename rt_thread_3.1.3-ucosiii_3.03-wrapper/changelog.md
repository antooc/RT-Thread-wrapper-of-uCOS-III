# ά����־

### 2020-6-29 

- ��������
- ����ź�������
- ���os_time.cϵͳ��ʱ�йؼ���


### 2020-6-30 

- ���������ʱ������


### 2020-7-1  

- ʵ�ֻ���������


### 2020-7-2  

- ʵ����Ϣ���м���


### 2020-7-3  

- ʵ���źű�־�����

- ʵ�������ڽ��Ĵ�������

- ʵ�������ڽ���Ϣ���м���

### 2020-7-4  

- ʵ�������ڽ��ź�������
- ʵ��uCOS-III��ȫ��֤�����ؼ���
- �Խ�os_cfg.h�궨��
- ����os_cfg_app.h����֮�Խ�
- ���os_sem.c os_q.c�ļ��궨�����Լ����̵�ȷ��

### 2020-7-5  

- ���os_flag.c os_mutex.c os_tmr.c os_task.c os_time.c os_core.c�ļ��궨�����Լ����̵�ȷ��
- �Ż�os_cfg_app.h��os_cfg.h

### 2020-7-6  

- ��ʵreadme.md
- ʵ��`OSSemSet`��`OSTaskSemSet`����
- �Ż�`OSTaskSuspend`��`OSTaskResume`������ʹ��߱�Ƕ�׹���/�������
- ʵ�ֹ��Ӻ���

### 2020-7-7  

- ��ֲos_mem.c�ļ�
- �Ż����ں˶���Ľṹ��

### 2020-7-8  

- ʵ��`OSTmrStateGet`����
- ����ͳ��������
- �޸�OSTaskDel����û��ɾ�������ڽ��ź����������ڽ����е�bug
- ��ֲ`OS_TaskDbgListAdd`��`OS_TaskDbgListRemove`����
- ʵ��`OS_TaskInitTCB`����
- ʵ��Idle����ʵ��ΪRTT Idle����Ļص�������
- ʵ��Idle�����Ӻ���`OSIdleTaskHook()`

### 2020-7-9

- ʵ��uCOS-III�ڲ����񡪡�ͳ�����񣬿�����ȷ����CPUʹ���ʡ�ÿ�������ʹ�ö�ջ

### 2020-7-10

- ʵ��`OSTimeDlyResume`����
- �޸�`OSSemDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ�������
- �޸�`OSMutexDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ�������
- �޸�`OSQDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ�������
- �޸�`OSFlagDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ�������

### 2020-7-11

- ���Ӽ���ԭ��OS_TCB�ṹ���Ա����
- ʵ��`OSSemPendAbort`������`OSSemPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ���

### 2020-7-12

- ����os_rtwrap.c�ļ��������RT-Thread�ͦ�COS-III��ת���ṩ֧�֡�����os.h�ļ�ĩβ����os_rtwrap.c�ں���������
- ʵ��`OSTaskSemPendAbort`����
- ʵ��`OSTaskQPendAbort`����
- ʵ��`OSSemPendAbort`������`OSSemPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ���
- ʵ��`OSSemMutexAbort`������`OSMutexPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ���
- ʵ��`OSSFlagPendAbort`������`OSFlagPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ���
- ʵ��`OSQPendAbort`������`OSQPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ���




# Release

## v0.1.0

�����ں˶�������Ѿ�ȫ��ʵ�֣��������������ļ������󡣱��汾��δʵ�֦�COS-III��ͳ�����񣬸ù��ܽ��ں����汾�з�����



## v0.2.0 

**[bug fix]** �޸�`OSTaskDel`����û��ɾ�������ڽ��ź����������ڽ����е�bug

**[add]** ʵ��`OSTmrStateGet`������Ŀǰ����13��uCOS-III API�޷����ݣ�

**[add]** ʵ��Idle����ʵ��ΪRTT Idle����Ļص�������

**[add]** ʵ��Idle�����Ӻ���`OSIdleTaskHook()`

**[add]** ʵ��uCOS-III�ڲ����񡪡�ͳ������



## v0.3.0����δ������

**[bug fix]** �޸�`OSSemDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ������⣨��֪��

**[bug fix]** �޸�`OSMutexDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ������⣨��֪��

**[bug fix]** �޸�`OSQDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ������⣨��֪��

**[bug fix]** �޸�`OSFlagDel`�����޷����ص�ǰ�ȴ��ź����������޷�ʹ��`OS_OPT_DEL_NO_PEND`ѡ������⣨��֪��

**[bug fix]** `OSSemPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ��ܣ���֪��

**[bug fix]** `OSMutexPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ��ܣ���֪��

**[bug fix]** `OSQPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ��ܣ���֪��

**[bug fix]** `OSFlagPend`���������˴���`OS_ERR_PEND_ABORT`�Ĺ��ܣ���֪��

**[add]** ���Ӽ���ԭ��OS_TCB�ṹ���Ա����

**[add]** ʵ��`OSTimeDlyResume`������Ŀǰ����12��uCOS-III API�޷����ݣ�

**[add]** ʵ��`OSSemPendAbort`������Ŀǰ����11��uCOS-III API�޷����ݣ�

**[add]** ʵ��`OSTaskSemPendAbort`������Ŀǰ����10��uCOS-III API�޷����ݣ�

**[add]** ʵ��`OSMutexPendAbort`������Ŀǰ����9��uCOS-III API�޷����ݣ�

**[add]** ʵ��`OSQPendAbort`������Ŀǰ����8��uCOS-III API�޷����ݣ�

**[add]** ʵ��`OSTaskQPendAbort`������Ŀǰ����7��uCOS-III API�޷����ݣ�

**[add]** ʵ��`OSFlagPendAbort`������Ŀǰ����6��uCOS-III API�޷����ݣ�



# TODO

- [ ] ��������ͳ�����������ͳ����
- [ ] ����Ŭ��ʵ��������opts
- [ ] ����Ŭ��ʵ��ʣ��δ���ݵ�API
- [ ] uCOS-IIIʱ��Ƭʱ��תRTTʱ��Ƭʱ��
- [ ] `OSQPendAbort`��`OSTaskQPendAbort`��δ����
- [ ] `OSQFlagAbort`��δ����