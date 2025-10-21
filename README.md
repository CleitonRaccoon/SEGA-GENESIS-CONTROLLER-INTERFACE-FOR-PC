# SEGA-GENESIS-CONTROLLER-INTERFACE-FOR-PC
Arduino UNO interface for sega genesis controller

Hi I made this proyect originaly to let my girlfriend play sonic on real hardware on my sega trough parsec but found it has a  lot more uses than that, this little bundle lets you use any controller on your sega genesis as long as windows recognizes it as a xbox 360 controller

ARDUINO SET UP

The first thing you need to do is connect this Digital pins on your Arduino to the sega genesis controller port

IMPORTANT NOTE NEVER CONNECT THE FIVE VOLTS PIN OF YOUR SEGA GENESIS INTO THE ARDUINO

Follow the next schematic

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/c6e4ddd5-c97f-4958-b462-7b8137069e59" 

Next you need to upload the code in realeases to your arduino

So once you have the Arduino side set up, you have to make sure that your computer recognizes your controller as a xbox 360 one, this is important because the python script that sends the input to the arduino uses xinput and wont work if windows doesnt think your controller is a xbox 360 one, you can use programs like ds4 if you have a ps3, ps4 or ps5 controller or x360ce for any generic one

Once your genesis is turn on, the arduino is setup and your controller is conected to your pc, you have tu run the python script (You have to make sure that you have the libraries the script uses installed)

If everything works you should be able to use your controller on the genesis!

