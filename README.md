# Interfacing-Pinguino-Matplotlib
Interface to graph analog signal in python with Matplotlib library and the PinguinoVe4550 board

# Instructions

Pinguino example to graph analog signal read on pin 13 of the penguin
with the matplotlib library through serial communication using the
pynguino communication library and CDC_8bit.pde from yeison cardona
to be seen in AnalogReadSerialMatplotlib.py

1) Clone the repository

2) Install libraries 
  a) # apt-get install python-matplotlib.
  b) # pip install pynguino.
  c) # pip install numpy.
  
3) Load the .pde in the Pinguino pic, CDC_8bit.pde from Yeison Cardona, https://bitbucket.org/yeisoneng/pynguino-2.0/raw/tip/pinguino/CDC/cdc_8bit.pde.

4) Use a potentiometer and place the 5 V input in pin 'A', the 'B' pin which is the middle one, connect the input pin in the pic pinguino (in this case it would be pin 13) and pin 'C' 'of the potentiometer connected to ground.

5) Pinguino board pic18f4550 connected via usb to pc.


# How to Start the Example?
 1) Pinguino board pic18f4550 connected via usb to pc.
 2) Open the terminal.
 3) Placed in the folder where your AnalogReadSerialMatplotlib.py file is located. execute $ cd /home/usuario/folder where is your file.
 4) As administrator execute # python AnalogReadSerialMatplotlib.py and will open the window with the real-time graph.
