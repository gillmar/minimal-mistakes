C7 SDE Meeting                                                                Di 22.05.2018
RHO, MG, DHD, MBK, WIS, ML, TG, TS
===========================================================================================
     
- Änderung der Liefernamen:                                                19.06.2018 [MBK]
  + Entscheidung: nächste Lieferungen: RC-3.142, RC-4.143, RC-4.144, 145-RC
    SIRe: Fixed in configuration wird entsprechend gefüllt
  + SCM-Jenkins Jobs anpassen
  - CM-Approach anpassen
 
- SCILA / CIL mails erstellen                                         29.05.2018 [WIS, RHO]
  - Versionsnummer in Sourcen soll ausgewertet werden. 
    -> Bei Änderung: Files per Email an einen Verteiler
  - Erstellung von CIL-Artefakten bei der Migration
    + Für Java und Python sollen die CIL-Artefakte bei der CIL-Migration
      direkt erstellt werden und in Artifactory gespeichert werden. 
    + RHO schickt Vorschlag rum
    + Reminder für Feedback versandt
    - Eingabe von Stories oder SIRs ongoing
    + Umsetzung beginnt: SIRs für static, common im QA Review;
      eurex und c7core folgen noch
    + Anlegen von RC-Job und Migrations-Job
    - SIRs für weitere Komponenten ab 24.4.2018 eingeben

- SIRe/Jira- Umstellung                                                    29.05.2018 [MBK]
  - SIR, Container, DCCR-Ablösung 2018
    Rechtevergabe noch nicht geklärt
  + T7-Workflow 

- C7 OSS Requests (z.B. Payment Services, ARP)                             19.06.2018 [ABU]
  - Hanno Klein erstellt Foliensatz zu 'OSS Prozess' ; Status: ongoing 
  - Neues Jira als Ersatz für SIRE ... oder Implementierung in bestehendes JIRA?
  - Was passiert mit derzeit offenen Requests? (RHO schickt Liste an Arno, Hanno)
    - derzeit ca. 140 offene Issues, die meisten davon Clearing betreffend
  - Prüfen ob alle derzeit genutzen Komponenten auf der Whitelist stehen
    Wo steht die Whitelist?
  - Wie wollen/sollen wir weiter vorgehen?
    - OSS-Check mit Blackduck?
    - automatisches Erstellen einer Liste aller verwendeten Komponenten?
    - alles was einen Lizenztyp hat, der auf der Whitelist steht, ist erlaubt 
      -> kein OSS-Request mehr
    - Architekten informieren über neuen Prozess    

- Alle Test Ergebnisse für alle C7 Komponenten sichern              19.06.2018 [MBK,WIS,JH]
  + Statusabfrage an die Teams verschickt
  + Feedback von Processcontroller fehlt noch
  - Mapping von Testergebnissen zu RC-Builds noch unklar
  - Feedback von Celia Holbach an Jörg Heroth erwartet
  - Ziel: 
    (a) Alle Tests und Sonar-Scans werden 3-6 Monate (t.b.d.) aufbewahrt
    (b) Jedem RC-Build müssen alle Tests und der Sonar-Scan eindeutig zuzuordnen sein.
    (c) Tests und Sonar-Scan für RC-Build werden 2-10 Jahre (t.b.d.) aufbewahrt.  
  
- RH7.3 für GUI Webservices                                           05.06.2018 [ABU, ABE]
  - Apache 2.4 + AJP + Tomcat 8 
  - Einführung für Simu+Prod (Termin noch offen)
  - 2 VMs für ACT bestellt
  - Zuständigkeit: Mario Jäger 

- Sonar Regelsatz für Java bearbeiten                                      29.05.2018 [MBK]
  + Project-feedback 
  + Zusammenstellung und Abstimmung des Feedbacks
  + Email-Zusammenfassung verschickt
  + Feedback ist da - wird zusammengestellt
  - Neuer Regelsatz wurde angelegt -> Scans für alle C7 Projekte werden durchgeführt

- Updates in 2018                                                          29.05.2018 [all]
  + PostgreSQL 9.6 mit 174-RC (9.4-Treiber richtig und zu 9.6 kompatibel)
  - RHEL 7 in Q3
  - RedHat JBOSS EAP 7.1 in Q3 (JBOSS 6.4 und 7.1 können parallel auf gleicher HW genutzt
    werden)
  - Java 9 (... da Java 8 im September 2018 aus Wartung läuft) 

- Ansible Prototype                                                    05.06.2018 [ML, RHO]
  + Erstellung eines Prototypen für das Gui zunächst für DEV und Test
  + Andreas Benk wird am 27.02.2018 präsentieren
  + Warten auf VMs
  + github DEV/C7-Deployment ist dafür gedacht
  - momentan noch in github benkand/ansible-egs
  - Freitags Meeting ... Andreas Präsentation hat stattgefunden
    ongoing - Synergien zweier Meetings sollen geschaffen warden
    Anforderungen von XEOps und SysOps harmonisieren

- Umstellung auf Java Broker für die Verbindung zum OPM                 29.05.2018 [MG,RHO]
  für alle C7 Komponenten voraussichtlich mit 1??-RC?
  + Umstellung auf Jenkins-Build (vieleicht zuerst nur 2 der 3 Projekte)
  - Hardware für Development bei Mario Jäger in Auftrag gegeben
  - NCA SIR der Installation beschreibt und triggert ist jetzt vergübar

- Evtl Anlegen eines Github Repositories für fixml-Dokumente (Word)         05.06.2018 [MG]
  - hier wird noch überlegt...

- Kritische Fortify Issues sollen bis Ende des Jahres behoben werden.      29.05.2018 [WIS]
  + neue Scans werden angestoßen und Ergebnisse verteilt
  - Ziel: Scan alle 4 Wochen
  - Ziel ist es, CRITICAL Issues bis Ende 2018 zu eliminieren
  - evtl automatisierte Übersicht erstellen 

- Test Coverage in Sonar im Jacoco einführen                               19.06.2018 [MG]

===========================================================================================
