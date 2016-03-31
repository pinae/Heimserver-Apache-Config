# Konfigurationsdateien für den heimischen Webserver

Diese Konfigurationsdateien definieren einen virtuellen Host für Owncloud. Platzieren Sie die Konfiguration in `/etc/apache2/sites-available/` und aktivieren sie mit `a2ensite`. Wenn Sie Let's Encrypt einsetzen, können Sie `002-owncloud.conf` verwenden, da Let's Encrypt die Verschlüsselung automatisch konfiguriert. Ansonsten verwenden Sie `002-owncloud-SSL.conf` und tragen dort Ihr Zertifikat ein.
