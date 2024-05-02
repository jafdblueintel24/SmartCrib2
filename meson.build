dbus_cflags = get_pkgconfig_variable('dbus-1', 'cflags')

executable('my_program',
           'source.c',
           dependencies : dbus_dependency,
           include_directories : dbus_cflags.split())
