# daqpi
Aufzeichnung aller Betriebsdaten einer Hargassner-Heizanlage wie Kesseltemperatur, Vorlauftemperaturen, Pumpen, Rauchgastemperaturen und Pufferwerte. Die Daten werden in einer InfluxDB gespeichert und können mit Grafana visualisiert werden.

Das Raspberry Pi Image enthält alle für den Betrieb notwendigen Programme. Es muss lediglich die IP Adresse der Steuerung und ein Name für die Aufzeichnung hinterlegt werden, und die Aufzeichnung beginnt automatisch. Auch das gleichzeitige Aufzeichnen mehrerer Kessel ist möglich.
