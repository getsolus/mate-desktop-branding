mate_schemas = [
    'com.solus-project.brisk-menu.gschema.override',
    'org.gnome.desktop.interface.gschema.override',
    'org.mate.Marco.general.gschema.override',
    'org.mate.NotificationDaemon.gschema.override',
    'org.mate.SettingsDaemon.plugins.media-keys.gschema.override',
    'org.mate.background.gschema.override',
    'org.mate.font-rendering.gschema.override',
    'org.mate.interface.gschema.override',
    'org.mate.panel.applet.clock.gschema.override',
    'org.mate.panel.gschema.override',
    'org.mate.panel.menubar.gschema.override',
    'org.mate.peripherals-mouse.gschema.override',
    'org.mate.peripherals-touchpad.gschema.override',
    'org.mate.power-manager.gschema.override',
    'org.mate.panel.toplevel.gschema.override',
    'x.dm.slick-greeter.gschema.override',
]

custom_target('10_mate_settings.gschema.override',
    output: '10_mate_settings.gschema.override',
    capture: true,
    input: mate_schemas,
    command: ['cat', '@INPUT@'],
    install: true,
    install_dir: path_schemadir,
)

subdir('livecd')
