Newsletter Export Script für OS-Commerce
========================================
    Digineo GmbH 2009 | www.digineo.de
    Author: Tim Kretschmer
    Version 1.0
    Lizenz: GNU 3


1. Installation
---------------
Führen Sie die Dateien mit Ihrer OS-Commerce Installation zusammen.
Die Datei export.php muss in den Ordner /newsletter_export/ kopiert werden.

2. Bedienung
------------
Ändern Sie als allererstes die Zugangsdaten für den Aufruf des Skriptes ($user und $password).
Entscheiden Sie sich, ob Sie nur die Kunden exportieren wollen, die sich für den Newsletter 
angemeldet haben ($all = false;), oder ob Sie alle Kunden exportieren wollen ($all = true;).

Der Aufruf des Exportes erfolgt  über http://USER:PASSWORT@ihr-shop.de/newsletter_export/export.php 	 
