CXX_EXTENSIONS
--------------

Boolean specifying whether compiler specific extensions are requested.

This property specifies whether compiler specific extensions should be
used.  For some compilers, this results in adding a flag such
as ``-std=gnu++11`` instead of ``-std=c++11`` to the compile line.  This
property is ``ON`` by default.

See the :manual:`cmake-compile-features(7)` manual for information on
compile features.

This property is initialized by the value of
the :variable:`CMAKE_CXX_EXTENSIONS` variable if it is set when a target
is created.
