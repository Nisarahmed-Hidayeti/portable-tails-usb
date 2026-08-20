# Portable tails USB

Today i finished the tails and i just wanna say that this thing is actually Revolutionary this is amazing 

# I mean what in the world u can carry your entire operating system in your pocket this is amazing 

- Fully anonymous
- Forgets who you are every session
- Tor is built in directly
- built in persistent storage system

This is how how you do it

## Creating a Tails USB

> [!NOTE]
> The installation process depends on your operating system. Choose the section that matches the computer you're currently using to create the Tails USB.

### Windows

1. **Download the Tails USB image:** [Tails USB Image](https://tails.net/install/download/)
2. **Download Rufus:** [Rufus](https://rufus.ie/)
3. Insert your USB drive into your computer.
4. Open **Rufus** and select your USB drive under **Device**.
5. Under **Boot selection**, select the Tails image you downloaded.
6. Click **Start** and confirm that you want to erase the USB drive.
7. Wait for Rufus to finish writing Tails to the USB.
8. Safely eject the USB drive when finished.

> [!WARNING]
> Flashing Tails will erase the contents of the selected USB drive. **Double-check that you selected the correct USB drive before starting.**

---

### 🐧 Linux

1. **Download the Tails USB image:** [Tails USB Image](https://tails.net/install/download/)
2. Insert your USB drive.
3. Open **GNOME Disks**. It is commonly installed by default on GNOME-based Linux systems.
4. Select your USB drive from the list.
5. Open the disk menu and choose **Restore Disk Image**.
6. Select the Tails image you downloaded.
7. Confirm that the correct USB drive is selected.
8. Start the process and wait for the image to finish writing.
9. Safely eject the USB drive.

> [!WARNING]
> Be extremely careful when selecting the destination drive. Choosing the wrong disk can overwrite another drive.

---

### macOS

1. **Download the Tails USB image:** [Tails USB Image](https://tails.net/install/download/)
2. **Download balenaEtcher:** [balenaEtcher](https://etcher.balena.io/)
3. Insert your USB drive.
4. Open **balenaEtcher**.
5. Select **Flash from file** and choose the Tails image.
6. Select your USB drive as the destination.
7. Click **Flash** and wait for the process to finish.
8. Safely eject the USB drive.

Tails' documentation also provides a macOS method using balenaEtcher.

> [!WARNING]
> Writing the Tails image will erase the selected USB drive. Make sure you have backed up anything important before continuing.

---

### Booting Tails

Once the USB has been created:

1. Insert the Tails USB into the computer you want to use.
2. Restart the computer.
3. Open the computer's **boot menu** during startup. The key varies by manufacturer and may be `F12`, `F9`, `Esc`, `F8`, or another key.
4. Select the USB drive from the boot menu.
5. Tails should start from the USB instead of the computer's internal drive.

> [!TIP]
> If the USB does not appear in the boot menu, check that the USB was created correctly and check your computer manufacturer's documentation for the correct boot-menu key.
