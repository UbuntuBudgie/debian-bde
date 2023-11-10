project(
  'budgie-desktop-environment',
  version: '0.1.1',
  license: 'GPLv2+',
  meson_version: '>= 0.61.0',
  default_options: ['prefix=/usr'],
)

# Globals that we need
prefix = get_option('prefix')
libdir = join_paths(prefix, get_option('libdir'))
confdir = join_paths(prefix, get_option('sysconfdir'))
datadir = join_paths(prefix, get_option('datadir'))
 
subdir('data')
