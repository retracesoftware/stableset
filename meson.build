# meson.build
project('retracesoftware.stableset', 'cpp', default_options: ['cpp_std=c++20'])

# Bind to the interpreter Meson/meson-python wants us to use.
py = import('python').find_installation()

py.extension_module(
  'stableset',
  'module.cpp',
  install: true,
  subdir: 'retracesoftware',

  # If you want extra flags:
  # cpp_args: ['-O3', '-fvisibility=hidden'],
  #include_directories: include_directories('.'),
)