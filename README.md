# aobench on Parallella

aobench on Parallella.

Based on Shodruky's mandelbrot example

https://github.com/parallella/parallella-examples/tree/master/mandelbrot

## Note

-O3 option doesn't work(seems causing stack overrun).

epiphany core doesn't have division, sqrt, etc units in HW. So we have to provide (approximate) functions of these for better performance.

## Author

Syoyo Fujita(syoyo@lighttransport.com)

## License

BSD license
