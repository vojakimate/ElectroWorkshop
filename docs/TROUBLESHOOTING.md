# Troubleshooting

## I cannot find the EXE

Download **ElectroWorkshop-Basic-1.0.1-Windows.zip** from the release Assets,
then extract it. **ElectroWorkshop.exe** is in its extracted top-level folder.

If you downloaded the maintainer's GitHub-upload kit instead, the program is
inside a second ZIP under `release-assets/`. Normal users need only the Windows
program ZIP. GitHub's automatic **Source code** downloads are documentation.

## It starts in Hungarian

A previous language choice may have been remembered. Choose **English** in
the header. To always start in English, close the launcher and set
`default_language=en` and `remember_language=false` in **ElectroWorkshop.ini**.
Then restart it. The EXE does not need rebuilding.

## The browser does not open

Check that the launcher is still running. Press its **Open / Megnyitás** button,
or open `http://127.0.0.1:18743/` in a modern browser.
If `open_browser=false`, manual opening is intentional.

## Startup reports that the port is in use

Check for another ElectroWorkshop Basic launcher and close the duplicate after
saving its work. This version uses port 18743. If another program owns that
port, identify it before making changes; the workshop does not reconfigure it.

## An INI error appears

Use the three supported settings and exact value forms shown in
[Settings](SETTINGS.md). Avoid rich-text formatting or a hidden `.txt` extension.
Close and restart the launcher after editing. No program rebuild is required.

## A control is missing or wiring cannot be changed

On smaller windows, controls move into the compact menu. Check the top-left
menu or choose **Normal** interface size. Turn the supply off before editing.
Put away measuring tools or leave connection tracing if a terminal click is
being used by one of those modes. Press Escape to cancel an active operation.

## My saved circuit is missing

Use the same browser and profile as before. Browser-data deletion, private
browsing and switching browser profiles can affect local saves. Open an exported
JSON backup. See [Saves](SAVES.md).

## Windows or security software flags the file

The EXE is unsigned. Confirm that the file came from the intended release and
compare its checksum with the release's published `.sha256` file. Report the
exact message and program version if you need help. A checksum verifies file
identity, not publisher identity or a guarantee of safety.

PowerShell example for checking the downloaded ZIP:

```powershell
Get-FileHash -Algorithm SHA256 .\ElectroWorkshop-Basic-1.0.1-Windows.zip
```

Compare the returned hash with the text in the `.zip.sha256` asset.

## Still reproducible?

Open a **Bug report** in this repository's Issues. Include app version,
Windows/browser version, steps, expected/actual result and an optional sanitised
screenshot. See [Support](../SUPPORT.md).
