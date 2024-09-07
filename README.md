# laptopt_check_methods
# Laptop Testing Guide for HP Elitebook, Lenovo Thinkpad, Dell Latitude

## Table of Contents
1. [Manufacturing Date](#manufacturing-date)
2. [Battery Check](#battery-check)
3. [Battery Health](#battery-health)
4. [Display Test](#display-test)
5. [Hard Disk Check](#hard-disk-check)
6. [Keyboard Check](#keyboard-check)
7. [Webcam Check](#webcam-check)
8. [Speaker Test](#speaker-test)
9. [Additional Tests](#additional-tests)

---

## Manufacturing Date
To check the laptop manufacturing date using BIOS version:
1. Press `Win + R`, type `cmd` and press Enter.
2. In the command prompt, type `systeminfo.exe`.
3. Look for the **BIOS Version** for the manufacturing date.

## Battery Check
1. Open the command prompt: `Win + R` -> `cmd`.
2. Type `powercfg /batteryreport` and hit Enter.
3. A link will be generated. Copy the link and paste it into a browser to view the battery report.

## Battery Health
1. Check battery health using the formula: Full Charge Capacity * 100 / Design Capacity
2. 10,687 * 100 / 32,120 = 33.27% [The acceptable rate is >= 80%.]

## Display Test
1. Search for "online display test" on Google and choose any site for testing.
2. Alternatively, use this link: [EIZO Monitor Test](https://www.eizo.be/monitor-test/).

## Hard Disk Check
1. Press `Ctrl + Shift + Esc` to open the Task Manager.
2. Go to the **Performance** tab and check the hard disk status.

To check hard disk health:
1. Search for "HDD health check" on Google and go to [HDD Sentinel](https://www.hdsentinel.com/).
2. Download and install the software, then run it to check the hard disk health.

## Keyboard Check
1. Visit this [online keyboard checker](https://en.key-test.ru/).
2. Press each key to verify functionality.

## Webcam Check
1. Visit this [online webcam check](https://webcamtests.com/check).
2. Test your webcam by following the instructions on the website.

## Speaker Test
1. Go to Windows search and type "Change sound system".
2. Select your playback device and click **Configure**.
3. Click **Test** to ensure the speakers are working properly.

## Additional Tests
Test additional components:
- **Fingerprint sensor**: Check for functionality using Windows Hello or the device's fingerprint software.
- **Bluetooth**: Go to `Settings -> Devices -> Bluetooth` to check connectivity.
- **Wi-Fi**: Ensure Wi-Fi is working by connecting to a network.
- **LAN port**: Test the LAN port by connecting a cable and checking network access.
- **HDMI and other ports**: Connect external devices to check if ports are functioning properly.
