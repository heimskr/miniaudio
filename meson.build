project('miniaudio', 'cpp', meson_version: '>= 0.62.0', default_options: ['warning_level=2', 'werror=false', 'cpp_std=c++20'])

miniaudio = declare_dependency(include_directories: ['include'], dependencies: [dependency('opusfile'), dependency('vorbisfile')])