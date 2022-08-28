# RedPitaya-Generate-Acquire
Simple Python scripts to illustrate the use of the ASG and triggered signal acquisition on the RedPitaya board.

The scripts were tested on 

- Version: 1.04
- Build: 18 

of the Red Pitaya GNU/Linux Ecosystem using Python 3.5.

These scripts use the *periphery module* which is already installed in the latest releases of the RedPytaya ecosystem.  



## Installation

The simplest way to install the code is to clone the repository and copy the jupyter notebooks to the directory /home/jupyter on the RedPitaya 

Then you can open them through the *Jupyter Python Programming* page from the *Development* page of the RedPitaya web page menu.

An alternative is to use an ssh-tunnel.

On the latest ecosystems Jupyter Notebook is already installed. Otherwise you need to install it.

Use the *Generate notebook* to generate a signal in burst mode and the *Acquire notebook* to acquire the signal. Do not use the *Oscilloscope App* at the same time as it may interfere the execution of the Python scripts.

### See https://github.com/lvillasen/RedPitaya-Python-Elephant for a tutorial on the use of the *Periphery Module* to control the ASG module of the RedPitaya.

## License

[MIT](LICENSE)
