import os
import shutil
from building import * 

# get current dir path
cwd = GetCurrentDir()

# traversal subscript
objs = []
list = os.listdir(cwd)
for d in list:
    path = os.path.join(cwd, d)
    if os.path.isfile(os.path.join(path, 'SConscript')):
        objs = objs + SConscript(os.path.join(d, 'SConscript'))

#delate non-used files
try:
    shutil.rmtree(os.path.join(cwd,'rt-thread-3.1.3'))
except:
    pass
    
Return('objs')
