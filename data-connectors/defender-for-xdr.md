`connector:` `Microsoft Defender XDR`

Reference:
- https://github.com/MicrosoftDocs/azure-docs/blob/main/articles/sentinel/connect-microsoft-365-defender.md
- https://github.com/MicrosoftDocs/azure-docs/blob/main/articles/sentinel/microsoft-365-defender-sentinel-integration.md

---

## Implementation Mindmap

```mermaid
mindmap
  root((defender-xdr))
    Docs
      Read GH Connector<br/>reference
    Activate
      1.Microsoft Defender XDR
        Activates whole XDR<br/>suite
      2.Connect Events
         Carefully evaluate per<br />connector
         Depends on Sentinel Rules<br />you wanna use
      3.Validate Defender Settings
         Forward Incidents via Stream API
    Blades
      security.microsoft.com
    Tools
      xx
      yy
```

## Special Hints
