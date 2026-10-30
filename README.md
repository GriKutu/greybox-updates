# GreyBox updates

The site packages of the GreyBox fault recorder PC programs (ASLI OTOMASYON). Each release carries one setup file,
its sha256 checksum, the release notes and a MANIFEST.txt that the GreyBox Data Server reads to update itself.

Nothing in this repository is source code. The Data Server of a site asks
`releases/latest/download/MANIFEST.txt` every few hours, downloads a newer setup, checks its sha256 and installs
it at the site's quiet hour. The setup keeps the site's project and all its records.
