This is a canadian compiled GCC compiler. It can build 32 bit windows programs on 64 bits windows. Sure you can use g++ -m32, but i find that sometimes it does not work, for example, windows 95 for unknown reasons. Built by the fast_io library's author

Unix Timestamp:1677215354.249777505
UTC:2023-02-24T05:09:14.249777505Z

fast_io:
https://github.com/cppfastio/fast_io

build	:	x86_64-linux-gnu
host	:	x86_64-w64-mingw32
target	:	i686-w64-mingw32

i686-w64-mingw32-g++ -v
Using built-in specs.
COLLECT_GCC=i686-w64-mingw32-g++
COLLECT_LTO_WRAPPER=D:/toolchains/gnu/x86_64-w64-mingw32/i686-w64-mingw32/bin/../libexec/gcc/i686-w64-mingw32/13.0.1/lto-wrapper.exe
Target: i686-w64-mingw32
Configured with: /home/cqwrteur/toolchains_build/gcc/configure --with-gxx-libcxx-include-dir=/home/cqwrteur/toolchains/x86_64-w64-mingw32/i686-w64-mingw32/i686-w64-mingw32/include/c++/v1 --prefix=/home/cqwrteur/toolchains/x86_64-w64-mingw32/i686-w64-mingw32 --build=x86_64-pc-linux-gnu --host=x86_64-w64-mingw32 --target=i686-w64-mingw32 --disable-nls --disable-werror --enable-languages=c,c++ --disable-multilib --disable-bootstrap --disable-libstdcxx-verbose --with-libstdcxx-eh-pool-obj-count=0 --disable-sjlj-exceptions --enable-libstdcxx-threads --enable-libstdcxx-backtrace
Thread model: win32
Supported LTO compression algorithms: zlib
gcc version 13.0.1 20230224 (experimental) (GCC)
