from building import *
import rtconfig
Import('RTT_ROOT')

# get current directory
cwd = GetCurrentDir()
src = []
path = [cwd + '/Core/Include']

group = DefineGroup('Libraries', src, depend=[''], CPPPATH=path)
Return('group')
