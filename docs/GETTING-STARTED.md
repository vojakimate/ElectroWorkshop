# Getting started

## Download the program

Open the repository's **Releases**, select **v1.0.1**, and download
**ElectroWorkshop-Basic-1.0.1-Windows.zip** from **Assets**.
The automatically generated **Source code** archives contain repository
documentation, not the Windows application.

Extract the complete ZIP. Inside the extracted folder you should see:

```text
ElectroWorkshop.exe
ElectroWorkshop.ini
README-EN.txt
README-HU.txt
TERMS-OF-USE.txt
FELHASZNALASI-FELTETELEK.txt
THIRD-PARTY-NOTICES.txt
SHA256SUMS.txt
licenses/
```

Keep these files together. No Python, Docker or application installer is needed.
The launcher uses the Windows system .NET Framework 4.5 or later and a modern
browser. The tested combination is Windows with Chrome; other combinations
have not all been independently tested. The EXE is not digitally signed.

## Start and stop

Run **ElectroWorkshop.exe**. It opens the workshop in your default browser at
`http://127.0.0.1:18743/`. Keep the small launcher window running. If the browser
does not open automatically, press **Open / Megnyitás** in that window.

To finish, close the launcher or press **Stop / Leállítás**. Closing the browser
tab alone does not stop the local server. Save important work to a JSON file
before closing or clearing browser data.

## First exercise

1. Select a conventional example from **Example circuits**. The one-way circuit
   is a suitable starting point.
2. Use **Physical** or **Schematic** to choose a view of the same circuit.
3. Press **Supply on** and click the switch rocker to operate the lamp.
4. Press **Supply off** before changing wiring.
5. Drag a wire between terminals, or click a start terminal and a target terminal.
   Use a free terminal position or a WAGO connector for branches.
6. Select **Measurement** to access the two-pole tester and clamp meter.
7. Use **Trace connections**, then select a terminal to highlight its current
   conducting component. Press Escape to stop tracing.
8. Use **Save** to export the circuit to JSON.

**Connection tracing is not an indication of current flow or proof of absence
of voltage.** Wire crossings alone do not create connections. The model's
limitations are explained in the in-app help.

## Language and smaller windows

The first launch defaults to English. Select **Magyar** or **English** in the
header; that browser remembers the choice unless disabled in the INI.
Labels you assign to devices are your own data and are not translated.

Automatic compact mode moves some controls into menus on smaller windows.
Open the top-left menu to find controls such as connection tracing. Choose
**Normal** in the interface-size selector if you prefer the full layout.

See [Settings](SETTINGS.md), [Saves](SAVES.md),
[Troubleshooting](TROUBLESHOOTING.md) and [FAQ](FAQ.md).
