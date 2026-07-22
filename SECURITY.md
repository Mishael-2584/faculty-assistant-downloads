# Security

## Supported releases

Only installers listed on the repository's Releases page are official public
downloads. Beta builds may be replaced as defects are resolved.

## Verify a download

Every release includes `SHA256SUMS.txt`. Compare its installer hash with the
result from Windows PowerShell:

```powershell
Get-FileHash ".\Faculty.Assistant.Setup.exe" -Algorithm SHA256
```

## Report a concern

Use the contact form at <https://facultyassistant.org/#contact> for a security
or installer-integrity concern. Do not include credentials, student data,
assessment content, or institution service tokens.
