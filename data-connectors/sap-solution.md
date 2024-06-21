`Connector:` `Microsoft Sentinel solution for SAP®`

![image](https://github.com/socGPT/msft-sentinel-pilot/assets/73879930/7a7194cd-ca54-4a36-88bc-a6467cd38d4e)

## Log Quellen

- ABAP Security Audit Log
- ABAP Change Documents Log
- ABAP Spool Log
- ABAP Spool Output Log
- ABAP Job Log
- ABAP Workflow Log
- ABAP DB Table Data
- SAP User Master Data
- ABAP CR Log
- ICM Logs
- JAVA Webdispacher Logs
- Syslog

## Kostenaufstellung

**Folgendener Datenfluss findet statt:**

- Logdaten von den einzelnen Systemen, über den Syslog-Server an den ARC-Monitoring Agent (Syslog/CEF, System Insights)
- ARC-Agent schreibt alle Daten zum Sentinel Log Analytics Workspace
- Sentinel (SIEM/SOAR) analysiert & korreliert die Daten

**Wo enstehen Kosten?**

- Daten-Ingest bei Log Analytics
- Daten-Verarbeitung in Microsoft Sentinel
- Sentinel SAP Solution: pro SID €1.88/Stunde
  - Bsp.: 1 SID's: €1.380 / Monat

---

## Implementierung

1. **Prüfung der Vorraussetzungen:**
   - https://learn.microsoft.com/en-us/azure/sentinel/sap/prerequisites-for-deploying-sap-continuous-threat-monitoring#sap-prerequisites
3. xx
