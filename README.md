### Install-ViciDial-using-ViciBox

#### Download ViciBox: 
https://download.vicidial.com/iso/vicibox/server/ViciBox_v11.x86_64-11.0.1.iso

#### Note: 
Make sure you have already configured static ip for your server. if not, then follow this: https://docs.vicibox.com/en/latest/installation/phase1_5/static-ip.html

#### vicibox-express:
1. If not already, login as the `root` user to get to the # command prompt.

2. Type `vicibox-express` and press `ENTER`.

3. Type `Y` and press `ENTER` to start the installation.

4. Once you are back at the # command prompt, the installation is complete. Type reboot and press `ENTER`.

5. Once the reboot is complete, log back in as root to get to the # command prompt.

6. Type `screen -ls` and press `ENTER`. While it might take upwards of 5 minutes, eventually there should be 11 Sockets in /run/screens/S-root shown before returning to the # command prompt

7. In a web browser, type in the `servers IP address`, I.E. 192.168.50.4, and press `ENTER`

8. Click on Administration and login. The default Username is `6666` with Password `1234`. Upon login you should see the ViciDial Initial Setup screen.

#### References:
`https://docs.vicibox.com/en/latest/installation/phase2/express.html`




