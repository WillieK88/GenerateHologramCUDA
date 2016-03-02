# GenerateHologramCUDA
CUDA script to generate SLM phase masks. From Martin Persson's [HOTlab](https://github.com/MartinPersson/HOTlab).


To compile (on Mac, for Mac)
```
nvcc --shared -o GenerateHologramCUDA.dylib GenerateHologramCUDA.cu -lcufft
```
