# Faculty Assistant Downloads

This public repository contains approved Windows installers for
[Faculty Assistant](https://facultyassistant.org). The application source code
is maintained separately in a private repository.

`latest.json` is a machine-readable pointer to the newest approved installer.
It lets the product website resolve downloads without depending on GitHub's
anonymous API rate limit. The release workflow updates it after publication.

## Download safely

1. Use the latest release linked from
   [facultyassistant.org/download](https://facultyassistant.org/download).
2. Download the Windows installer and `SHA256SUMS.txt` from the same release.
3. Verify the installer checksum before running it.

```powershell
Get-FileHash ".\Faculty.Assistant.Setup.exe" -Algorithm SHA256
```

The hash shown by PowerShell must match the installer entry in
`SHA256SUMS.txt`. Do not install files received through email attachments or
unofficial file-sharing links.

## Beta releases

Pre-release versions are clearly marked as beta. Keep original academic files
and review all calculations, question keys, exports, and Moodle publishing
actions before treating them as official.

## Support and terms

- Product information: <https://facultyassistant.org>
- Privacy: <https://facultyassistant.org/privacy.html>
- Terms: <https://facultyassistant.org/terms.html>

Do not submit student records, examination papers, passwords, licence keys, or
Moodle service tokens in a public GitHub issue.
