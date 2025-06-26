# How to make a Bootable USB


A bootable usb contains files needed in order to install an operating system such as Windows or Linux on your computer

there are *3 things* you need to make a bootable usb.

- A usb flashdrive of at least 8gb
- An .iso file containing the files and processes needed to install the operating system.
- and and install tool such as Rufus or Window Media Creation Tool

## Here are the steps to creating a bootable usb with Rufus

1. Download Rufus: Get the latest version from the Rufus website. 
2. Insert USB Drive: Plug the USB drive into your computer. 
3. Open Rufus: Launch the application. 
4. Select USB Drive: Rufus will automatically detect the USB drive. Choose it from the "Device" dropdown. 
5. Select ISO Image: Click "Select" and browse to the location of your ISO file. 
6. Configure Settings: Choose the appropriate partition scheme and target system. For most modern systems, you'll want GPT and UEFI. 
7. Start: Click "Start" to begin writing the ISO image to the USB drive. This will format the drive, so back up any important data. 
8. Wait: Rufus will create the bootable USB drive

9. ## Can you have Multiple Boots on one Bootable USB?

10. yes! you can use tools such as YUMI, Ventoy, or Easy2Boot than can multiboot a usb, also you can use the usb to simply store multiple .iso files. The Boot menu can also help ypu choose exactly which .iso file you'd like to boot from the drive.
