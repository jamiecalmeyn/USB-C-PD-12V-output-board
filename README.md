# USB-C PD 12V output board
Powered by the IP2721_MAX12
## PCB
![Rendered Image](https://github.com/user-attachments/assets/8842366a-6b86-44ba-ac8b-c6bae3676933)

Upgrade your legacy gear with modern USB-C power. This compact board delivers a 12V output using the IP2721_MAX12 USB-C Power Delivery controller.

Whether you're retrofitting old tech or building something new, this board offers a simple, reliable way to tap into USB-C PD at 12V. It uses the HRO_TYPE-C-31-M-17 USB connector.
It should be able to handle 1.5A of current based on PCB track width.

![Untitled](https://github.com/user-attachments/assets/575aa0ea-1c83-43e4-a5bb-28cfa8e6c2b1)

*Board tested with 1.5A of current*

![image](https://github.com/user-attachments/assets/4cd3a3b1-1cd2-40a9-8a86-e42035d8078b)

*Ripple under a 1.5A load, ripple can vary based on the USB-C charger. Test conducted with the **65W USB-C GaN iFixit Fast Charger***
## IP2721_MAX12

⚠️ Important: Use the Correct Chip

Be sure to use the **IP2721_MAX12** chip.

Using the standard **IP2721** (without the _MAX12 suffix) will result in 20V output, which could damage 12V devices. Double-check your part number!
Do note that the 12V is an optional voltage output in the USB-C PD standard, not every charger has a 12V output mode. 
## Schematic
 ![Schematic](https://github.com/user-attachments/assets/61299f8f-1654-4bf5-9e82-5d1d85b611e5)
