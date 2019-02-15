fips_begin_lib(clipper)
fips_files(clipper.cpp clipper.hpp)
fips_end_lib()

set_target_properties(clipper PROPERTIES COMPILE_FLAGS "-fexceptions")