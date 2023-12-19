# Topics Abbrandregelung V0.60
|Aktuelle Topics|Datentyp|Wertebereich|Beschreibung
|---------------|--------|------------|------------
|/tele/ZeitStartRegelung|Int||
|/tele/StartCheckNachlegen|Int||
|/tele/COSekunde|int||
|/tele/CODiffProzNachlegen|float||
|/cmnd/MindestDauerStufe3|int||
|/tele/MindestDauerStufe3|int||
|/cmnd/TempOfenAus|int||
|/tele/TempOfenAus|int||
|/cmnd/MindestDauerStufe4|int||
|/tele/MindestDauerStufe4|int||
|/cmnd/MindestDauerStufe5|int||
|/tele/MindestDauerStufe5|int||
|/cmnd/SystemTemperaturMax|int||
|/tele/SystemTemperaturMax|int||
|/cmnd/ZeitFaktorTempProz|float||
|/tele/ZeitFaktorTempProz|float||
|/cmnd/MaxDauerStufe2|int||
|/tele/MaxDauerStufe2|int||
|/cmnd/MaxDauerStufe3|int||
|/tele/MaxDauerStufe3|int||
|/cmnd/MaxDauerStufe4|int||
|/tele/MaxDauerStufe4|int||
|/cmnd/MaxDauerStufe5|int||
|/tele/MaxDauerStufe5|int||
|/tele/Abfrage|float||
|/cmnd/COSekundeZeit|int||
|/tele/COSekundeZeit|int||
|/tele/FWVersion|String|Vx.x|Firmwareversion
|/tele/Online|String|"Online", "Offline"|Verbindungsstatus zu MQTT-Broker
|/tele/IP|String||IP-Adresse
|/cmnd/ServoUeberfahren|Int|0-3000|Wie weit der Servo die Position überfahren soll [µs]
|/tele/ServoUeberfahren|Int|0-3000|Rückmeldung zu /cmnd/ServoUeberfahren
|/cmnd/CoVonExtern|||nicht implementiert
|/cmnd/CoExternAktiv|||nicht implementiert
|/cmnd/TempVonExtern|||nicht implementiert
|/cmnd/TempExternAktiv|||nicht implementiert
|/cmnd/StellgrVonExtern|int|400-3000|Stellgröße externe Vorgabe [µs]
|/cmnd/StellgrExternAktiv|int|0/1|Stellgröße Vorgabe Aus/Ein
|/cmnd/Quittieren|int|1|Meldung Quittieren/löschen
|/cmnd/ServoMin|int|300-3000|Minimalposition Servo [µs]
|/cmnd/ServoMax|int|300-3000|Maximalposition Servo [µs]
|/cmnd/ServoSpeed|int|10-1000|Position um [ServoSpeed*25]µs pro s verändern
|/cmnd/ServoStromLimit|||nicht implementiert
|/tele/co|int|0-200000|	CO-Wert [Ohm]
|/tele/temp|int|0-1000|	Temperaturwert [°C]
|/tele/stellgr| int|0-3000|	Servoposition [µs]
|/tele/modus|int|0-5|Entspricht Ofenstatus
|/tele/Uptime|int|0- |Laufzeit [s]
|/tele/CoVonExtern|||nicht implementiert
|/tele/CoExternAktiv|||nicht implementiert
|/tele/TempVonExtern|||nicht implementiert
|/tele/TempExternAktiv|||nicht implementiert
|/tele/StellgrVonExtern|int|300-3000|Rückmeldung von "/cmnd/StellgrVonExtern"
|/tele/StellgrExternAktiv|int|0/1|Rückmeldung von "/cmnd/StellgrExternAktiv"
|/tele/Meldungen|String||(Fehler-)Meldungen
|/tele/ServoMin|int|300-3000|Rückmeldung von "/cmnd/ServoMin"
|/tele/ServoMax|int|300-3000|Rückmeldung von "/cmnd/ServoMax"
|/tele/ServoSpeed/tele/ServoStromLimit|||nicht implementiert
|/tele/ServoUeberstrom |||nicht implementiert
|/tele/Empfang|int|-100-0|W-Lan Empfangsstärke (RSSI)
|/tele/ServoTemp|float|-55-125| Temperatursensor am Servo [°C]
|/tele/ESPTemp|int|-40-125|Kerntemperatur Microcontroller [°C]
|/tele/GehaeuseTemp|float|-55-125| Temperatursensor in Gehäuse der Steuerung [°C]
|/tele/COStabil|int|0-200000| COStabil
|/tele/COMinute|int|0-200000| COMinute
|/tele/CODiffProz|float||CODiffProz
|/tele/COMinimum|float||COMinimum
|/tele/TempStabil|int||TempStabil
|/tele/TempMinute|int||TempMinute
|/tele/Klappenstellung|int|0-100|Klappenstellung [%]
|/tele/KlappeProzent|int|0-100|Klappenstellung [%]
|/tele/Status|int|0-5|Ofenstatus
|/tele/CheckStufe3auf|bool|0-1|CheckStufe3auf
|/tele/CheckStufe3zu|bool|0-1|CheckStufe3zu
|/tele/ZeitOfenstart|String|"tag.monat.jahr hh:mm:ss"|ZeitOfenstart
|/tele/ZeitSeitOfenstart|int||Zeit seit Ofenstart [s]
|/tele/COSteigung|float||COSteigung
|/tele/TempSteigung|float||TempSteigung
|/tele/COSteigungLang|float||COSteigungLang
|/tele/TempSteigungKurz|float||TempSteigungKurz
|/tele/COSteigungSehrLang|float||COSteigungSehrLang
|/tele/TempSteigungLang|float||TempSteigungLang
|/tele/ZeitFaktor|float||ZeitFaktor
|/tele/CheckStufe3KlappeZu|bool|0-1|CheckStufe3KlappeZu
|/tele/ZeitSeitCheckStufe3KlappeZu|int||ZeitSeitCheckStufe3KlappeZu
|/tele/COCheckStufe3KlappeZu|int||COCheckStufe3KlappeZu
|/tele/BegrenzeStufe2|bool|0-1|BegrenzeStufe2
|/cmnd/KlappenstellungNachlegen|
|/tele/KlappenstellungNachlegen|
|/cmnd/COStabilStufe2Proz|
|/tele/COStabilStufe2Proz|
|/cmnd/COStabilStufe3Proz|
|/tele/COStabilStufe3Proz|
|/cmnd/COStabilStufe5Proz|
|/tele/COStabilStufe5Proz|
|/cmnd/KlappenstellungStartStufe1|
|/tele/KlappenstellungStartStufe1|
|/cmnd/KlappenstellungMinStufe2|
|/tele/KlappenstellungMinStufe2|
|/cmnd/KlappeOffnenStufe2|
|/tele/KlappeOffnenStufe2|
|/cmnd/KlappeSchliessenStufe2|
|/tele/KlappeSchliessenStufe2|
|/cmnd/KlappeSchliessenStufe3|
|/tele/KlappeSchliessenStufe3|
|/cmnd/KlappenstellungAbsturzStufe2|
|/tele/KlappenstellungAbsturzStufe2|
|/cmnd/KlappenstellungMinStufe3|
|/tele/KlappenstellungMinStufe3|
|/cmnd/KlappenstellungMaxStufe3|
|/tele/KlappenstellungMaxStufe3|
|/cmnd/KlappenstellungCheckStufe3|
|/tele/KlappenstellungCheckStufe3|
|/cmnd/KlappenstellungWechselStufe3|
|/tele/KlappenstellungWechselStufe3|
|/cmnd/KlappenstellungMinStufe4|
|/tele/KlappenstellungMinStufe4|
|/cmnd/MindestdauerStufe2|
|/tele/MindestdauerStufe2|
|/cmnd/ZeitZwischenAbfrageStufe2|
|/tele/ZeitZwischenAbfrageStufe2|
|/cmnd/ZeitZwischenAbfrageStufe3|
|/tele/ZeitZwischenAbfrageStufe3|
|/cmnd/WertNotKlappenOeffnung|
|/tele/WertNotKlappenOeffnung|
|/cmnd/COProzAbsturz|
|/tele/COProzAbsturz|
|/cmnd/WertAbsturzKlappenOeffnung|
|/tele/WertAbsturzKlappenOeffnung|
|/cmnd/COProzAbsturzStufe3|
|/tele/COProzAbsturzStufe3|
|/cmnd/DauerCheckStufe3KlappeZu|
|/tele/DauerCheckStufe3KlappeZu|
|/cmnd/OeffneKlappeCheckStufe3KlappeZu|
|/tele/OeffneKlappeCheckStufe3KlappeZu|
|/cmnd/SystemTemperaturMaxFaktor|
|/tele/SystemTemperaturMaxFaktor|
|/cmnd/SystemTemperaturMaxFaktor1|
|/tele/SystemTemperaturMaxFaktor1|
|/cmnd/SystemTemperaturMaxFaktor2|
|/tele/SystemTemperaturMaxFaktor2|
|/cmnd/CODiffOfenStartProz|
|/tele/CODiffOfenStartProz|
|/cmnd/OfenFehlstartTemperatur|
|/tele/OfenFehlstartTemperatur|
|/cmnd/OfenFehlstartZeit|
|/tele/OfenFehlstartZeit|
|/cmnd/MinDiffTemperaturWechselStufe2|
|/tele/MinDiffTemperaturWechselStufe2|
|/cmnd/MinDiffZeitWechselStufe2|
|/tele/MinDiffZeitWechselStufe2|
|/cmnd/MittlereKlappenstellung|
|/tele/MittlereKlappenstellung|
|/cmnd/ZeitFaktorMax|
|/tele/ZeitFaktorMax|
|/cmnd/COimKellerFaktor|
|/tele/COimKellerFaktor|
|/cmnd/ZeitspanneNotklappenoeffnung|
|/tele/ZeitspanneNotklappenoeffnung|
|/cmnd/COWertWechsel5nach0Faktor|
|/tele/COWertWechsel5nach0Faktor|
|/cmnd/COStabilZeit|
|/tele/COStabilZeit|
|/cmnd/COMinuteZeit|
|/tele/COMinuteZeit|
|/cmnd/COSteigungZeit|
|/tele/COSteigungZeit|
|/cmnd/COSteigungLangZeit|
|/tele/COSteigungLangZeit|
|/cmnd/COSteigungSehrLangZeit|
|/tele/COSteigungSehrLangZeit|
|/cmnd/TempStabilZeit|
|/tele/TempStabilZeit|
|/cmnd/TempMinuteZeit|
|/tele/TempMinuteZeit|
|/cmnd/TempSteigungZeit|
|/tele/TempSteigungZeit|
|/cmnd/TempSteigungKurzZeit|
|/tele/TempSteigungKurzZeit|
|/cmnd/TempSteigungLangZeit|
|/tele/TempSteigungLangZeit|
