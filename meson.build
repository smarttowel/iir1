project('iir', 'cpp',
         version: '1.9.0',
         default_options: ['cpp_std=c++17',
                           'warning_level=2'])

iir_lib = static_library('iir',
                         'iir/Biquad.cpp',
                         'iir/Butterworth.cpp',
                         'iir/Cascade.cpp',
                         'iir/ChebyshevI.cpp',
                         'iir/ChebyshevII.cpp',
                         'iir/Custom.cpp',
                         'iir/PoleFilter.cpp',
                         'iir/RBJ.cpp',
                          include_directories: include_directories('iir'))
iir_dep = declare_dependency(link_with: iir_lib,
                             include_directories: include_directories('.'))

