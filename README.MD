# fftw3.3.10
FFTw3.3.10自编译双精度静态链接库
FFTW3.3.10 self-compiled double-precision static link library
## 配置参数
### Linux
```
./configure --with-our-malloc16 --with-windows-f77-mangling --enable-threads --enable-sse2 --with-incoming-stack-boundary=2 --enable-openmp --with-g77-wrappers --enable-avx2 --enable-avx512 --enable-avx --enable-mpi
```
### Windows
见config.h

## Authors
FFTW was developed by Matteo Frigo and Steven G. Johnson. The latest version of FFTW, benchmarks, links, and other information can be found at the FFTW home page (http://www.fftw.org).
