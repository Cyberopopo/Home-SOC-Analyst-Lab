---

# 03_EDR_Lab/README.md

```markdown
# 03_EDR_Lab
**Project:** Endpoint visibility & detection using Elastic Agent or Defender evaluation + Sysmon  
**Objective:** Configure endpoint telemetry (Sysmon + Wazuh agent) and show how endpoint events create detections in SIEM.

---

## Tools used
- Sysmon (Windows)
- Wazuh Agent (already installed)
- Elastic Agent or Microsoft Defender (optional for richer detection)
- Process monitoring utilities (Process Explorer)

---

## Steps: Sysmon + Wazuh integration

### 1) Install Sysmon on Windows
```powershell
# Transfer the sysmon64.exe file to the VM
.\sysmon64.exe -accepteula -i -n
# -i install, use a config later to tune
