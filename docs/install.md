# Installation guide
<div style="text-align: justify;">
The CMAP library is available from the link <a href="https://github.com/YauheniTalochkaN/CMAP_Library"  target="_blank" rel="noopener">https://github.com/YauheniTalochkaN/CMAP_Library</a>. 
You can use this <a href="https://github.com/YauheniTalochkaN/CMAP_LYSO_Example"  target="_blank" rel="noopener">CMAP-powered LYSO example</a> compiling it with the libCMAP.a library to see how it works. 
Before compiling the example code, the <a href="https://root.cern/"  target="_blank" rel="noopener">CERN ROOT toolkit</a> and the <a href="https://www.openmp.org/"  target="_blank" rel="noopener">OpenMP library</a> must be installed in your system.
Then, please check the <code>CMAP_LIB_DIR</code> and <code>CMAP_INCLUDE_DIR</code> variables in the <code>CMakeLists.txt</code> file to set them right for your system. 
After that, the example code can be compiled and run as following
```
cd CMAP_LYSO_Example
mkdir build
cd build
cmake ../
make -jN
./LYSO run.param
```
</div>