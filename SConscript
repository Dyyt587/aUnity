Import('rtconfig')
from building import *
import os

cwd = GetCurrentDir()
src = Glob('*.c') + Glob('*.cpp')
inc = [cwd]


CXXFLAGS = ''


group = DefineGroup('perf_counter', src, depend = ['PKG_USING_AUNITY'], CPPPATH = inc, CXXFLAGS = CXXFLAGS)

Return('group')
