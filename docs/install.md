# Installation guide
<div style="text-align: justify;">
The CMAP libraryr is available from the link <a href="https://github.com/YauheniTalochkaN/CMAP_Library"  target="_blank" rel="noopener">https://github.com/YauheniTalochkaN/CMAP_Library</a>. 
You can use this <a href="https://github.com/YauheniTalochkaN/CMAP_LYSO_Example"  target="_blank" rel="noopener">LYSO example</a> compiling it with the libCMAP.a to see how it works. 
Before compiling the CMAP_LYSO_Example code, the <a href="https://root.cern/"  target="_blank" rel="noopener">CERN ROOT toolkit</a> and <a href="https://www.openmp.org/"  target="_blank" rel="noopener">OpenMP library</a> must be installed in your system.
Then, please check the CMAP CMAP_LIB_DIR and CMAP_INCLUDE_DIR variables in the CMakeLists.txt to connect them right in your system. 
After that, the CMAP_LYSO_Example code can be compiled as 
```
cd CMAP_LYSO_Example
mkdir build
cd build
cmake ../
make -jN
make install
```
</div>