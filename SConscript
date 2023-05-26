from building import *
import os

cwd = GetCurrentDir()

src = Split('''
platform/rtthread/pf_task_adapter.c
platform/rtthread/pf_mutex_adapter.c
platform/rtthread/pf_sem_adapter.c
platform/rtthread/pf_event_adapter.c
''')

CPPPATH = [cwd + '/platform']

group = DefineGroup('rplatform', src, depend = [''], CPPPATH = CPPPATH)
Return('group')
