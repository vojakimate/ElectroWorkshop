# Known limitations in 1.0.1

- The interface, exercise descriptions and help have English and Hungarian
  versions. Some live status fragments can still remain in Hungarian; for
  example, the bottom status may show `bekapcsolva` (on) while a lamp is active.
  The published measurement screenshot shows the actual application state.
- Numeric readouts can use a decimal comma, such as `233,1 V`, depending on
  the formatting used by the application. This is not a different voltage unit.
- The packaged application was tested on Windows with Chrome. A clean-machine
  Windows VM and a full matrix of Windows/browser versions were not tested.
- The executable is not digitally signed. SHA256 checksums verify file identity,
  not a publisher signature.
- The simulation uses ideal contacts and simplified educational load/protection
  models. It does not certify an actual installation, conductor sizing, loop
  impedance, real trip time or absence of voltage. See the in-app help.

For data-storage behaviour, supported settings and excluded edition features,
see [Saves](SAVES.md), [Settings](SETTINGS.md) and [FAQ](FAQ.md).
