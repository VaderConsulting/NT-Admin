# NT Admin

Chips, Bits and Bytes VB6 ActiveX DLL (project Admin, exposed class `NT`) for Windows NT domain account administration over NetAPI32. Resolves a PDC with `NetGetDCName`, then adds/deletes users, adds/removes global group membership, and enumerates users or groups. Higher-level helpers (`GetPDC`, `GetAllUsers`, `GetUserGroupList`, `UserInGroup`, `GetDomainName`) wrap the LanMan buffer calls for callers. Based on Microsoft KB Q159498 LanMan patterns (Planet Source Code sample noted in the class header).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Admin` (`NT Admin.vbp`) | VB6 | ActiveX DLL | NetAPI32 NT user/group add/delete/enum and PDC lookup |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `NT Admin.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Windows NT/2000+ with NetAPI32 privileges for domain user and group changes

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/NT Admin`.
Company names in project files: Chips, Bits and Bytes.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
