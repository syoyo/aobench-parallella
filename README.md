# aobench on Parallella

aobench on Parallella.

![aobench](https://github.com/syoyo/aobench-parallella/blob/master/img/aobench_parallella.png?raw=true)

Youtube

http://www.youtube.com/watch?v=_t4p4Is0Z3E

Based on Shodruky's mandelbrot example

https://github.com/parallella/parallella-examples/tree/master/mandelbrot

## How to build and run

    $ make

Go to framebuffer mode(CTRL + ALT + F2)

    $ ./run.sh

Will render animation of aobench. 
After execution, you can go back to GUI by CTRL + ALT + F7

## Note

-O3 option doesn't work(seems causing stack overrun).

epiphany core doesn't have division, sqrt, etc units in HW. So we have to provide (approximate) functions of these for better performance.

## Author

Syoyo Fujita(syoyo@lighttransport.com)

## License

BSD license
