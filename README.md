## RedPitaya-Generate-Acquire
Simple Python scripts and programs in C to illustrate the use of the fast ADCs and the DACs on the RedPitaya board.

The Python scripts were tested on 

- Version: 1.04
- Build: 18 

of the Red Pitaya GNU/Linux Ecosystem using Python 3.5.

These Python scripts use the *periphery module* which is already installed in the latest releases of the RedPytaya ecosystem and the official memory map of the STEMLab 125-14 board.  

### Hardware Configuration

Connect IN1 to OUT1 on your RedPitaya board and the range jumper on IN1 to LV. 


#### The memory map is documented here: https://redpitaya.readthedocs.io/en/latest/developerGuide/software/build/fpga/regset/in_dev/v0.94.html


### Installation


The simplest way to install the code is to clone the repository in the directory /home/jupyter on the RedPitaya 

Then you can open the jupyter notebooks using the *Jupyter Python Programming* page from the *Development* page of the RedPitaya web page menu.

An alternative way is to use an ssh-tunnel.

On the latest ecosystems Jupyter Notebook is already installed. Otherwise you need to install it.
*In order to catch the signal generated it is necesary to use both jupyter notebooks:*
use the *Generate notebook* to generate a signal in burst mode and the *Acquire notebook* to acquire the signal. Do not use the *Oscilloscope App* at the same time as it may interfere the execution of the Python scripts.

#### See https://github.com/lvillasen/RedPitaya-Signal-Generator-Python for a tutorial on the use of the *Periphery Module* to control the ASG module of the RedPitaya.

### License

[MIT](LICENSE)
