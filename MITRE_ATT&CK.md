# MITRE ATT&CK

MITRE Corporation · 2015

A globally accessible knowledge base of adversary tactics, techniques, and procedures (TTPs) based on real-world observations. Not linear — techniques map to any tactic at any stage.
Key matrices

    Enterprise (Windows, macOS, Linux, Cloud)
    Mobile
    ICS (Industrial Control Systems)

![Uploading image.png…]()

What ATT&CK actually is
ATT&CK is a globally accessible knowledge base of adversary tactics and techniques based on real-world observations EC-Council, and it's completely free. The framework documents 196 individual techniques and 411 sub-techniques, covering Windows, Linux, macOS, and mobile platforms. IJRASET The key distinction from the Cyber Kill Chain is that ATT&CK is non-linear — an adversary can apply techniques from multiple tactics simultaneously or in any order.
How it's used in a SOC day-to-day
The power of ATT&CK lies in its ability to create a collective operational map across an entire security program. When a SIEM fires "Suspicious LSASS Access", mapping it to T1003.001 instantly tells every analyst what is happening — credential dumping via direct memory access to the Local Security Authority Subsystem Service. Medium
For detection engineering specifically, detection rules can be tagged with ATT&CK IDs, allowing you to detect coverage gaps. If you have 50 detections for T1059 (Command and Scripting Interpreter) but zero for T1574 (Hijack Execution Flow), you know exactly where to deploy effort. Medium
For threat intelligence, listing attacker TTPs in a structured and usable way enables threat-informed cyber defense — the assumption being that it is possible to predict an attacker's future behavior based on past observed TTPs. IEEE Xplore
Measuring SOC maturity
Coverage percentage by tactic can be tracked over time. If Q1 shows 45% coverage and Q3 reaches 68%, that is a quantifiable security improvement that can be shared with leadership to demonstrate SOC maturity and justify security investments. Medium
How red and blue teams use it together
ATT&CK-based red team exercises simulate specific threat actors' TTPs to test defensive measures against real-world attack scenarios PYnomial, rather than generic vulnerability scanning. Instead of "try to compromise us", you can request specific technique validation: "Execute T1003.001, T1021.002, and T1048.003 — verify your detections work." Medium
For your career path specifically — as a future SOC analyst or detection engineer, the Enterprise Matrix tab and the Career tab are your most immediately relevant views. Every senior analyst you'll work alongside thinks in ATT&CK IDs. Starting to recognize techniques by their T-numbers (T1059 for scripting, T1003 for credential dumping, T1021 for lateral movement) will give you a strong head start in interviews and on the job.

# Sources 

## Websites

Visited on 18/03/2026 ~ 17:55

https://attack.mitre.org/


## LLM

claude.ai

Prompted on 18/03/2026 around 17:45:

I would like to see similair framework for Cybersecurity like: the Diamond Model and the Cyber Kill Chain.

Make sure the source is correct and make no mistakes.
