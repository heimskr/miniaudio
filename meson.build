project('miniaudio', 'cpp', meson_version: '>= 0.62.0', default_options: ['warning_level=2', 'werror=false', 'cpp_std=c++23'])

miniaudio_includes = include_directories('include')
miniaudio = declare_dependency(include_directories: [miniaudio_includes], dependencies: [dependency('opusfile'), dependency('vorbisfile')])
