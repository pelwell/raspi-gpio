# raspi-gpio
Tool to help debug / hack at the BCM283x GPIO. 
You can dump the state of a GPIO or (all GPIOs).
You can change a GPIO mode and pulls (and level if set as an output).
Beware this tool writes directly to the BCM283x GPIO reisters, ignoring anything else that may be using them (like Linux drivers).
