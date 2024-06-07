Dieses Repository wurde erstellt, um das Paket CK-Editor für Redmine an unsere Bedürfnisse anzupassen.
Details sind im Ticket https://csc.atrivio.net/issues/30416 zu finden.  

## JPG-Handling
Für die korrekte Verarbeitung von JPG-Files wurden die Dateien `rich/app/controllers/rich/files_controller.rb` und `assets/javascripts/browser.js` bearbeitet.
Es wurde dafür gesorgt, dass Leerzeichen automatisch bei der Verarbeitung und Speicherung der Dateien automatischb durch Unterstrich ersetzt werden.