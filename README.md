# KeePass
Mirror of https://sourceforge.net/projects/keepass

To fix the error message "Severity	Code	Description	Project	File	Line	Suppression State Error Cannot import the following key file: KeePassLib.pfx. The key file may be password protected. To correct this, try to import the certificate again or manually install the certificate to the Strong Name CSP with the following key container name: VS_KEY_FD2BEC84A0382FBD	KeePassLib".

C:\> sn -i KeePass.pfx VS_KEY_27A70973F3FC3787

Password is 123123.
