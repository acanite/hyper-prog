HyperCalc Logo
HyperCalc - High precision command line styled calculator
HyperCalc is a console styled calculator, which is similar to linux "bc".

Webpage and windows binaries: http://hyperprog.com/hypercalc/index.html
It designed to be simple, easy to use and fast. The calculations evaluated with correct precedence, using decimal based numbers with high precision to avoid floating point errors. (The base mathematical functions built on boost c++) You can use hexadecimal, octal and binary numbers as input or output. Available operators/sings:

+ - * / % ^ ( )
The program has many internal functions and loadable functions and you can define new ones (See screenshots for examples)

HyperCalc screenshot 1

HyperCalc screenshot 1

Compile / Install
Require Qt (https://www.qt.io/) and gSAFE (Qt based opensource lib) and Boost C++ (https://www.boost.org/).

Check the paths of these libraries in HyperCalc.pro file the run:

$qmake
$make
#make install
Author
Péter Deák (hyper80@gmail.com)

License
GPLv2
