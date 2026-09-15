Created with the help of Gemini AI

Purpose:
Cinnamon Desktop applet to connect/disconnect from a Wireguard tunnel.

Language:
Python

Use:
Create wg-tray.desktop in ~/.config/autostart/

[Desktop Entry]
Type=Application
Exec=python <full path to app>/wg-tray
NoDisplay=false
Hidden=false
Name=WireGuard Status
X-GNOME-Autostart-Delay=3

Notes:
* It lists all .conf files from /etc/wireguard
* You will need to give your user permissions to /etc/wireguard.  visudo?

Issues:
* The applet should turn red when no tunnel is activated.

20260915:
* Repository created.

