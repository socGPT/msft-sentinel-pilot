`©️ 2024 zerohat Consulting` \
`Hinweis: kein Anspruch auf Vollständigkeit, selber mitdenken - Copy & Innovate!`

---

# SENTINEL (SOC) Operator

## WEEKLY Checks

```mermaid
mindmap
  root((weekly-checks))
    Health
      Nutzung Workbook<br />"Analytics Health & Audit"
        Kontrolle "Overview"
        Kontrolle "Health"
    Incidents
      Nutzung "Security Operations Efficiency" <br />Workbook
    Content Hub
      1.Kontrolle auf Updates
        Release Notes beachten
    Data Connector
      1.Kontrolle der connected Quellen
          Nutzung Workbook "Workspace Usage Report"
            Prüfung Nutzen & Kosten (Tab: Cost Analysis)
            Prüfung "Latency" pro Quelle
            Prüfung Tab "Regular Checks"
    SOC optimization
      Prüfung der Vorschläge <br/>In-Progress oder Completed
    Threat Intelligence
      TI Alerts vorhanden?
      Neue Custom IOC's aufnehmen?
        Watchlist Referenzen nutzen 
      Nutzung "Workbook Threat Intelligence"
        Prüfung Indikators
      MITRE Att&CK
        Prüfung der Detections <br />Sortieren nach Top
          Prüfung woher Alarme kommen <br />Quelle & Rules
    UEBA
      Customize Widgets
        Je nach Umgebung relevante <br />Widgets einblenden
        Aktivierung "Enrichment Widget"
          Erfordert API-Keys <br />Empfehlenswert!
    Workspace Manager
      Repo Status okay?
```

---

## Online References

- https://learn.microsoft.com/en-us/azure/security/fundamentals/operational-checklist
- https://learn.microsoft.com/en-us/azure/sentinel/whats-new
- https://danielchronlund.com/wp-content/uploads/2022/09/microsoft-sentinel-soc-activities.pdf
