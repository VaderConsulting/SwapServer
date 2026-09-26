# SwapServer

VB6 SwapServer (`SwapServer.exe`) that remaps mapped network drives from old file servers to new ones using `SwapServer.ini` (old,new pairs), WMI and Scripting Runtime helpers, and reconnect logic. Open `SwapServer.vbp` in the VB6 IDE.

**Source last updated:** 2003-04-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SwapServer` (`SwapServer.vbp`) | VB6 | WinForms exe | Remap drive shares to replacement servers from INI |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `SwapServer.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft Scripting Runtime (scrrun.dll)
- Microsoft WMI Scripting V1.2 Library
- `SwapServer.ini` beside the exe (sample included)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/SwapServer`. Notes in `Documentation.xml`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
