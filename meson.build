# meson.build
project('retracesoftware.stableset', 'cpp', default_options: ['cpp_std=c++20'])

# Bind to the interpreter Meson/meson-python wants us to use.
py = import('python').find_installation()

py.extension_module(
  'retracesoftware.stableset',            # import name: `import retrace_software.stableset`
  'module.cpp',        # your single source file
  install: true
  # If you want extra flags:
  # cpp_args: ['-O3', '-fvisibility=hidden'],
  #include_directories: include_directories('.'),
)