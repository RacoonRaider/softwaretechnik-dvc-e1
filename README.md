Einsendeaufgabe DVC-E1 – Versionsverwaltung mit Git

Repository:
https://github.com/RacoonRaider/softwaretechnik-dvc-e1

1. Repository erstellen

1.1 Repository erstellt und Git initialisiert

 Ich habe auf GitHub ein öffentliches Repository erstellt und mein lokales Projekt mit Git initialisiert.

 Verwendeter Befehl:
 <img width="635" height="36" alt="Screenshot 2026-05-09 190550" src="https://github.com/user-attachments/assets/999b2ce6-24fb-4974-a0a6-105b90cad295" />
 Anschließend habe ich mit git status überprüft, welche Dateien noch nicht von Git verfolgt werden. Dabei wurden folgende Dateien erkannt:
 <img width="544" height="175" alt="Screenshot 2026-05-09 191422" src="https://github.com/user-attachments/assets/0c59fd36-c23b-45e9-9060-d01366878cfb" />

2. Dateien hinzugefügt und erster Commit erstellt 

Ich habe alle Dateien mit git add . vorgemerkt.
Danach habe ich erneut den Status überprüft: <img width="333" height="150" alt="Screenshot 2026-05-09 191739" src="https://github.com/user-attachments/assets/cf173f1d-95df-4a8b-ad6d-1464520f5b5c" />
Anschließend habe ich meinen ersten Commit erstellt: <img width="497" height="268" alt="Screenshot 2026-05-09 191846" src="https://github.com/user-attachments/assets/c0e086d5-4bba-47ed-b50d-f4746dcf02e8" />

1.2 Git-Konfiguration angepasst

Nach dem ersten Commit wurde angezeigt, dass mein echter Name und meine Arbeits-E-Mail verwendet wurden und nicht die Daten von meinem Git account.
Deshalb habe ich meine Git-Konfiguration angepasst. Erst den Namen dann die Mail.
Zuerst habe ich versehentlich den Befehl falsch geschrieben: <img width="376" height="79" alt="Screenshot 2026-05-09 192438" src="https://github.com/user-attachments/assets/10df8623-0bcc-4756-b97a-fd6d6b020c2d" />
Danach habe ich es noch mal mit der korrekten Schreibweise versucht und seltsamerweise hat es funktioniert: <img width="331" height="24" alt="Screenshot 2026-05-09 192725" src="https://github.com/user-attachments/assets/e94dc984-56f7-4063-a71c-fc176b1573e5" />
Dann noch die die "noreplay" mail: <img width="580" height="21" alt="Screenshot 2026-05-09 193056" src="https://github.com/user-attachments/assets/3da87481-98a1-4f03-90b1-073b38c48b7d" />
Anschließend habe ich überprüft, ob die neuen Daten übernommen wurden: 
<img width="164" height="33" alt="Screenshot 2026-05-09 193211" src="https://github.com/user-attachments/assets/630322d5-4ccb-408b-9f42-9216efdedeb2" />
<img width="343" height="34" alt="Screenshot 2026-05-09 193320" src="https://github.com/user-attachments/assets/4c82f21d-1970-4b6a-85d5-422a83176ef1" />
Danach habe ich den ersten Commit mit den neuen Autor-Daten überschrieben: <img width="352" height="90" alt="Screenshot 2026-05-09 193524" src="https://github.com/user-attachments/assets/443d2e1d-16a2-45dc-afab-3a0c671ebf0e" />
Mit git log habe ich kontrolliert, ob der Commit jetzt den richtigen GitHub-Namen verwendet: <img width="496" height="94" alt="Screenshot 2026-05-09 193643" src="https://github.com/user-attachments/assets/522d69ec-5a99-485a-bf65-43e669e1fabc" />

1.3 Branch von master zu main umbenannt

Ich habe den Standard-Branch von master zu main umbenannt: <img width="149" height="21" alt="Screenshot 2026-05-09 193805" src="https://github.com/user-attachments/assets/e79dceb1-a85a-4bfb-bb7d-2135b5c34c23" />

1.4 Verbindung mit GitHub hergestellt

Ich habe mein lokales Projekt mit meinem GitHub-Repository verbunden: <img width="582" height="21" alt="Screenshot 2026-05-09 195413" src="https://github.com/user-attachments/assets/fcc7f75d-471d-4b7f-831c-348c213a948e" />
Danach habe ich das Projekt zu GitHub hochgeladen: <img width="437" height="146" alt="Screenshot 2026-05-09 195511" src="https://github.com/user-attachments/assets/6a4fbcd1-00fb-4b8c-a5a8-afbccb31ec8e" />

3. Alle relevanten Methoden anwenden

3.1 Änderungen mit git status und git diff untersucht

Ich habe die Datei main.py bearbeitet und zusätzlichen Python-Code ergänzt: <img width="191" height="41" alt="Screenshot 2026-05-09 195924" src="https://github.com/user-attachments/assets/60014845-9c60-4bf7-afc5-13cc5411f8b8" />
Danach habe ich überprüft, welche Datei verändert wurde: <img width="508" height="146" alt="Screenshot 2026-05-09 200041" src="https://github.com/user-attachments/assets/5e3eeb31-0505-4fa4-b130-87d8570f691a" />
Mit git diff habe ich mir die Unterschiede anzeigen lassen: <img width="225" height="133" alt="Screenshot 2026-05-09 200209" src="https://github.com/user-attachments/assets/184d1232-8bdb-4c42-8c0d-7cc3b6ae855f" />
Git zeigte dabei die neu hinzugefügten Zeilen mit + an.

3.2 Änderungen gespeichert und hochgeladen

Ich habe die Datei mit git add vorgemerkt: <img width="130" height="19" alt="Screenshot 2026-05-09 200344" src="https://github.com/user-attachments/assets/03bbe3ba-c7e8-40d8-b79d-5790518697ae" />
Danach erneut den Status geprüft: <img width="368" height="106" alt="Screenshot 2026-05-09 200430" src="https://github.com/user-attachments/assets/7a25f07d-b326-4d6a-a0f6-e245ba2351e6" />
Anschließend habe ich die Änderung committed: <img width="246" height="46" alt="Screenshot 2026-05-09 200552" src="https://github.com/user-attachments/assets/7e3d275c-5a29-465a-90df-4dfc4bc660a0" />
und danach zu GitHub hochgeladen: <img width="440" height="133" alt="Screenshot 2026-05-09 200638" src="https://github.com/user-attachments/assets/d1ca200a-490a-4adf-831c-e6d9c4010a3e" />

3.3 Datei mit git mv umbenannt

Ich habe die Datei main.py in app.py umbenannt: <img width="173" height="23" alt="Screenshot 2026-05-09 200732" src="https://github.com/user-attachments/assets/189e181d-dce0-4b97-ac16-e317afbbb6aa" />
Danach habe ich den Status geprüft und Git erkannte die Änderung automatisch als Umbenennung: <img width="365" height="110" alt="Screenshot 2026-05-09 200854" src="https://github.com/user-attachments/assets/83aa3baa-76d7-4ae4-9495-5b6fc0a7f0de" />
Änderung committed: <img width="343" height="63" alt="Screenshot 2026-05-09 201059" src="https://github.com/user-attachments/assets/a0823431-5aa9-4278-b9aa-caa0fdbc3209" />
und zu GitHub hochgeladen: <img width="481" height="142" alt="Screenshot 2026-05-09 201134" src="https://github.com/user-attachments/assets/b56a28dd-d868-4e23-911c-9cdd42d73523" />

3.4 Datei mit git rm gelöscht

Ich habe die Datei notes.txt aus dem Repository entfernt: <img width="137" height="31" alt="Screenshot 2026-05-09 201223" src="https://github.com/user-attachments/assets/a8ea8947-2c5e-466b-b4d7-6c0323dd5ebb" />
Danach habe ich den Status kontrolliert - Git erkannte die Datei als gelöscht: <img width="369" height="111" alt="Screenshot 2026-05-09 201254" src="https://github.com/user-attachments/assets/b6f9ea60-b5fd-458c-843b-0cd01ae2d876" />
Dann die Änderung committed: <img width="350" height="59" alt="Screenshot 2026-05-09 201708" src="https://github.com/user-attachments/assets/9f0f9a6f-73b7-45c1-923b-0f72fc4f562d" />
und in GitHub hochgeladen: <img width="479" height="144" alt="Screenshot 2026-05-09 201830" src="https://github.com/user-attachments/assets/e61ca3e2-f82f-4fa4-b539-5ba725944705" />

5. Erstellung von zwei unterschiedlichen Branches + Merge

5.1 Ersten Branch erstellt

Ich habe einen neuen Branch namens neue-ausgabe erstellt: <img width="280" height="32" alt="Screenshot 2026-05-09 202217" src="https://github.com/user-attachments/assets/37774694-33ba-4d82-9fd1-3e8bba307ecd" />
In diesem Branch habe ich zusätzlichen Python-Code ergänzt: <img width="183" height="23" alt="Screenshot 2026-05-09 202329" src="https://github.com/user-attachments/assets/0dd66729-bfbc-475c-b784-4bfed026af3a" />
Danach habe ich die Änderung gespeichert: <img width="542" height="91" alt="Screenshot 2026-05-09 202422" src="https://github.com/user-attachments/assets/0ee0d169-fa4c-4a43-a6fc-67b7fba82100" />
und den Branch in GitHub hochgeladen: <img width="632" height="201" alt="Screenshot 2026-05-09 202736" src="https://github.com/user-attachments/assets/feef06ef-d28b-4fb3-92e0-fed9a0857fbc" />

5.2 Zweiten Branch erstellt

Danach bin ich zurück zu main gewechselt: <img width="321" height="49" alt="Screenshot 2026-05-09 202834" src="https://github.com/user-attachments/assets/e1d65af7-c0b0-4f83-a0de-17a424bb5e76" />
Anschließend habe ich einen zweiten Branch erstellt: <img width="291" height="34" alt="Screenshot 2026-05-09 203012" src="https://github.com/user-attachments/assets/f1d8f534-8e06-45e8-ac18-78009135da0a" />
In diesem Branch habe ich zusätzlichen Python-Code ergänzt: <img width="182" height="22" alt="Screenshot 2026-05-09 203048" src="https://github.com/user-attachments/assets/ffd7f944-d12f-4cc5-a9c1-755c79caf901" />
Dann habe ich die Änderung gespeichert: <img width="643" height="258" alt="Screenshot 2026-05-09 203157" src="https://github.com/user-attachments/assets/db245a34-bd3f-421c-a34b-8845012823b6" />

5.3 Branches gemerged

Zuerst bin ich zurück zu main gewechselt: <img width="324" height="54" alt="Screenshot 2026-05-09 203336" src="https://github.com/user-attachments/assets/1aeb1a2d-dc94-49f9-8ccc-551c63099f8e" />
Danach habe ich den ersten Branch gemerged: <img width="339" height="79" alt="Screenshot 2026-05-09 203505" src="https://github.com/user-attachments/assets/e0c2c9c5-b663-4c44-9bd6-69dc65a67181" />
Dieser Merge funktionierte automatisch.

Beim Merge des zweiten Branches entstand ein Merge-Konflikt: <img width="464" height="63" alt="Screenshot 2026-05-09 205243" src="https://github.com/user-attachments/assets/1c30798b-d9db-4f14-ae41-4a1d510ff6c5" />
Ich habe den Konflikt manuell in app.py gelöst (leider Screenshot vergessen) und danach die Datei erneut vorgemerkt: <img width="126" height="19" alt="Screenshot 2026-05-09 205404" src="https://github.com/user-attachments/assets/1fdd1bd8-cb7a-4ba5-956e-440543b64e2c" />
Anschließend habe ich den Merge abgeschlossen: <img width="411" height="32" alt="Screenshot 2026-05-09 205614" src="https://github.com/user-attachments/assets/18558541-2110-4428-8bf6-6e2fcd13810d" />
Danach habe ich alles in GitHub hochgeladen: <img width="433" height="133" alt="Screenshot 2026-05-09 205831" src="https://github.com/user-attachments/assets/373b9529-541d-484b-9d7e-e66b20a70fb5" />

4. Experiment Zeitreise

4.1 Zeitreisen mit Git
Ich habe mit git log --oneline die Commit-Historie untersucht: <img width="558" height="116" alt="Screenshot 2026-05-09 210439" src="https://github.com/user-attachments/assets/480f685f-52eb-428f-adf6-55851da9e949" />

4.2 Älteren Commit geöffnet:
<img width="546" height="271" alt="Screenshot 2026-05-09 210558" src="https://github.com/user-attachments/assets/14266177-6a67-48a5-b96f-8f51c1abb293" />
Dabei befand ich mich im „detached HEAD“-Zustand.
Danach bin ich wieder zum aktuellen Branch zurückgekehrt: <img width="441" height="58" alt="Screenshot 2026-05-09 210657" src="https://github.com/user-attachments/assets/6415be76-5639-4375-8a29-e9c45eb84e5f" />

4.3 Noch ältere Version untersucht:
Ich habe zusätzlich den Commit b5a8077 geöffnet und Dort habe ich versucht, die Datei app.py anzuzeigen Git meldete "cat: app.py: No such file or directory" Der Grund dafür war, dass die Datei zu diesem Zeitpunkt noch main.py hieß: <img width="542" height="275" alt="Screenshot 2026-05-09 211909" src="https://github.com/user-attachments/assets/cfbc9b27-9867-4194-a496-3c956f223b7c" />
Danach habe ich die alte Datei erfolgreich angezeigt: <img width="157" height="46" alt="Screenshot 2026-05-09 212146" src="https://github.com/user-attachments/assets/28d4ee84-389c-442b-9fc5-1c6faa7149e5" />
Zum Abschluss bin ich wieder zurück zu main gewechselt: <img width="368" height="62" alt="Screenshot 2026-05-09 212234" src="https://github.com/user-attachments/assets/c8b72cba-8383-4516-8628-9962987e0739" />

6. Pull Request bei edlich/education

Ich habe direkt über die GitHub-Weboberfläche (nicht über die Shell) einen Pull Request erstellt.
Da der direkte Versuch auf einen Fehler lief, habe ich einen Fork des Repositories erstellt: RacoonRaider/education
Im Ordner students habe ich folgende Datei erstellt: <img width="224" height="60" alt="Screenshot 2026-05-09 213244" src="https://github.com/user-attachments/assets/b417b971-6483-4e74-987e-7bdf66f52fde" />
Da ich beim Erledigen der Aufgaben einen Merge-Konflikt hatte dachte das wäre passend zum Thema: <img width="575" height="351" alt="Screenshot 2026-05-09 213401" src="https://github.com/user-attachments/assets/a8d9d39d-7fd3-4c22-bc25-a9a3eddde940" />
Danach habe ich einen Pull Request an das Original-Repository erstellt:

Pull Request: https://github.com/edlich/education/pull/606
Pull-Request-Nummer: #606

