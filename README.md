# DATUMM Desktop releases

Public distribution repository for unsigned Windows x64 DATUMM installers and the optional bundled Revit bridge. Application source and user data are not published here.

The [1.0.0-rc.2 unsigned candidate](https://github.com/RAJ-IITROORKEE/datumm-desktop-releases/releases/tag/v1.0.0-rc.2) repairs existing-profile startup migration and includes the combined desktop installer, optional Revit alpha.29 installation, checksum, payload manifest and verification results. The repaired workspace opened on the owner's system. Web users can download the unchanged separate Revit installer from the [RC1 release](https://github.com/RAJ-IITROORKEE/datumm-desktop-releases/releases/tag/v1.0.0-rc.1). No stable release is published yet; the stable update feed remains empty.

Download [DATUMM for Windows x64](https://github.com/RAJ-IITROORKEE/datumm-desktop-releases/releases/download/v1.0.0-rc.2/DATUMM-1.0.0-rc.2-unsigned-win-x64.exe). Its SHA-256 is `eb327601b46b3c5254795297b6d9f4bd8912a1b045ea019d407e7a9f7489cbee`. The candidate uses the separate DATUMM Local Test identity and profile. Production Clerk configuration, clean-PC installation/upgrade and live Revit acceptance remain open.

Close DATUMM and Revit before running an upgrade. Installed user profiles are retained; local test and stable desktop profiles are separate. An unsigned installer may show Windows publisher warnings.
