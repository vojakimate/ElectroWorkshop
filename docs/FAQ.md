# Frequently asked questions

**Is it free?**  
Yes, for private use and non-commercial education under [Terms of Use](../LICENSE.txt).
Commercial/professional business use and use as part of paid training require
separate permission. No such permission is granted by downloading the program.

**Is this open source?**  
No. This repository distributes the Windows program and documentation. The
development source is not published. Browser-side JavaScript is technically
inspectable; that does not grant unrestricted reuse rights.

**Do I need Python, Docker or an account?**  
No. The launcher uses Windows system components and a browser. No account or
internet connection is needed to use the program after downloading.

**Why does it open in a browser?**  
The EXE starts a local, loopback-only static server. The browser is the user
interface; the app is not being run on a remote website.

**Can I access it from another computer?**  
This portable edition listens only on `127.0.0.1`. It is not a LAN hosting edition.
Run a separate local copy on the other supported Windows computer.

**Does it control real smart-home equipment?**  
No. This Basic edition has no MQTT, Home Assistant, smart-device or 3D floorplan
features. It simulates conventional electrical circuits.

**Can I use it to certify a real installation?**  
No. It is an educational model, not an installation inspection, absence-of-voltage
test or electrical sizing tool. Read the simulation limits in the app's help.

**Can I switch between English and Hungarian?**  
Yes. The header offers both. First use defaults to English. The INI can change
the default and whether a previous selection is remembered.

**Does changing the INI require a new EXE?**  
No. Close the launcher, edit the INI and restart it. See [Settings](SETTINGS.md).

**Where are my circuits?**  
Autosaves are in the current browser/profile. Export important work to JSON.
They are not stored inside the EXE. See [Saves](SAVES.md).

**Is the Windows executable signed?**  
No. Published SHA256 checksums help compare file identity; they are not a
digital publisher signature.

**Is support guaranteed?**  
No response time or individual support commitment is promised. Reproducible
reports are welcome through this repository's Issues.
