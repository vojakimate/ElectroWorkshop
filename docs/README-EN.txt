ElectroWorkshop Basic 1.0.1 / Villanyműhely – Windows

START
1. Extract the complete ZIP into a folder of your choice.
2. Run ElectroWorkshop.exe.
3. The workshop opens in your default browser.
4. Use the Magyar / English selector in the header to change language.
5. When finished, close the small launcher window or press Stop.
   Closing the browser tab alone does not stop the local server.

SETTINGS – ElectroWorkshop.ini
Edit the file next to the EXE using a text editor. Close the launcher
first and restart it after saving. No rebuild or repackaging is required.
- default_language=en: English on first use; use hu for Hungarian.
- remember_language=true: a previously selected language takes priority.
  With false, each new opening uses default_language.
- open_browser=true: automatically open the browser at startup.
  With false, use the launcher's Open button instead.
Missing file defaults: en / true / true. Invalid values produce an error
message. Changing these settings does not change your saved circuits.
To always start in English even after previously selecting Hungarian,
use default_language=en and remember_language=false.

Requirements: Windows 10/11 and a current Edge, Chrome or Firefox browser.
The launcher uses the system .NET Framework 4.5 or later, normally already
available on Windows 10/11. No separate Python, Docker, administrator
installation or internet connection is required.
Local address: http://127.0.0.1:18743/ . The app does not listen on the LAN.
If the port is occupied, close the other ElectroWorkshop Basic instance.

FEATURES
Conventional lighting and motor-control exercises, device placement,
wiring, physical and schematic views, simulation, measuring instruments,
connection tracing, exercise checks and local JSON save/open.
No MQTT, Home Assistant, smart devices, 3D floorplans or school accounts.
Conventional educational circuit exercises remain available.
Separate photographic reference material is not included in this edition.

SAVES
Work is stored per exercise in the selected browser's local storage.
Both languages share that storage. Your own device labels are preserved,
not automatically translated. Different browsers have separate storage.
Export important work to a JSON file using Save: clearing browser data may
remove automatic saves. This edition uses a separate local address and
does not overwrite the full/NAS edition's browser storage.
Files containing smart devices or floorplans are rejected, not converted.

This is a teaching simulator, not an installation certification tool,
absence-of-voltage test or electrical sizing tool. Model limitations are
explained in the in-app help.

USE AND DISTRIBUTION
Free for private use and non-commercial education under the included
Terms of Use. No permission for commercial use is granted.
The development source package is not included. Browser-side JavaScript
remains technically inspectable; packing it into an EXE is not encryption.
The executable is not digitally signed. A SHA256 checksum is supplied.

No personal saves, passwords, databases or HA/MQTT settings are included.
