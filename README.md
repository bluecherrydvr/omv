omv
===

Bluecherry GPL changes to OpenMediaVault (Ubuntu port and changes)

## Changes to packaging ##
### Dependencies ###
#### jsl ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)

#### libjs-extjs ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)

#### php5-pam ####
+ Built for Ubuntu 12.04 (Precise)
+ Built using dh-make-pecl for debhelper >= 7

#### php-json-schema ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Used patches from OMV changes

#### xmlstarlet ####
+ Rebuilt 1.3.1 from Debian Sid for Ubuntu 12.04 (Precise)

### OpenMediaVault ###
#### openmediavault ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ Fixed debian/postinst for samba to smbd daemon name changes
+ debian/patches/ubuntu_01_samba_to_smbd.diff - fixes scripts in source code to use smbd instead of samba

#### openmediavault-clamav ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-forkeddaapd ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-iscsitarget ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-keyring ####
+ Not ported over or rebuilt as we won't be using the upstream keyring for
packages

#### openmediavault-ldap ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-lvm2 ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-netatalk ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-nut ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-route ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#

#### openmediavault-transmissionbt ####
+ Built using debhelper >= 8
+ Built for Ubuntu 12.04 (Precise)
+ Fixed debian/copyright to be as close to Debian copyright guidelines as possible
+ debian/postinst, postrm, prerm fixed to include #DEBHELPER#
