install_data(
   [
     '50_budgie-desktop.conf',
   ],
   install_dir: join_paths(confdir, 'lightdm', 'lightdm.conf.d'),
 )

install_data(
   [
     'defaults.list',
   ],
   install_dir: join_paths(confdir, 'budgie-desktop'),
 )

install_symlink(['defaults.list'],
	pointing_to: join_paths(confdir, 'budgie-desktop'),
	install_dir: join_paths(datadir, 'budgie-desktop', 'applications')
)

install_data(
   [
     '25_budgie-desktop-environment.gschema.override',
   ],
   install_dir: join_paths(datadir, 'glib-2.0', 'schemas'),
 )

