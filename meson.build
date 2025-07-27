project('getopt', 'c')

getopt = static_library('getopt',
    files('getopt.c', 'getopt1.c', 'getopt_core.h', 'getopt_ext.h', 'getopt_int.h', 'getopt.h'),
    pic: true,
)
getopt_dep = declare_dependency(include_directories: include_directories('.'), link_with: getopt)
