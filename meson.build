project(
    'com.github.pongloongyeat.elementary-template-app',
    'vala',
    'c'
)

i18n = import('i18n')

add_project_arguments(
    '-DGETTEXT_PACKAGE="@0@"'.format(meson.project_name()),
    language: 'c'
)

executable(
    meson.project_name(),
    'src/Application.vala',
    'src/MainWindow.vala',
    dependencies: [
        dependency('gtk+-3.0'),
        dependency('granite'),
    ],
    install: true
)

subdir('data')
subdir('po')