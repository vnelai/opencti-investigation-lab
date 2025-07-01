# 🗺️ MITRE ATT&CK Technique Mapping Summary

## 🔍 Objective
Summarize all MITRE ATT&CK techniques and kill chain phases identified during this OpenCTI investigation lab.

## 🧾 Technique Overview
| Tactic              | Technique Name               | Technique ID | Associated With         | Kill Chain Phase     |
|---------------------|-------------------------------|--------------|--------------------------|-----------------------|
| Execution (ICS)     | Command-Line Interface        | T0807        | CaddyWiper              | Execution-ICS         |
| Execution           | Native API                    | (custom)     | CaddyWiper              | Execution             |
| Initial Access      | Drive-by Compromise           | T1189        | APT37                   | Initial Access        |
| Initial Access      | Phishing                      | T1566        | APT37                   | Initial Access        |
| Discovery           | File and Directory Discovery  | T1083        | APT37 / Others (mapped) | Discovery             |
| Discovery           | Process Discovery             | T1057        | APT37 / Others (mapped) | Discovery             |
| Discovery           | System Information Discovery  | T1082        | APT37 / Others (mapped) | Discovery             |
| Discovery           | Permission Groups Discovery   | T1069        | APT37 / Others (mapped) | Discovery             |

## 📈 What This Shows
- Wide coverage of MITRE ATT&CK tactics: Execution, Initial Access, and Discovery
- Accurate linking of techniques to threat actors, malware, and tools
- Use of ATT&CK IDs in context of both Enterprise and ICS matrices

## 🔗 Sources Referenced
- OpenCTI’s embedded MITRE ATT&CK matrix and technique relationship graphs
- Entity-specific timelines and knowledge tabs throughout the lab

---

*Maintaining MITRE mapping documentation helps analysts align detections, enrich threat reports, and communicate findings across security teams.*
