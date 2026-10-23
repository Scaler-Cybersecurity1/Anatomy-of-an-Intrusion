# Anatomy-of-an-Intrusion

**Topic:** Attack reconstruction (MITRE ATT&CK) · **Time:** 25–35 min

**Scenario.** A finance workstation, WKS-FIN-07, was compromised last week.
Forensics pulled **8 artifacts** off it — a document, process events, registry keys,
network beacons, a cleared log, a data upload.

**Your task.**
1. **Map the column:** for each artifact, choose the MITRE ATT&CK tactic it
   represents from the dropdown. One tactic in the list is a decoy and is never
   used; no tactic repeats.
2. **Order the kill chain:** once all 8 are mapped correctly, put the artifacts in
   the order the attack actually happened, from how they got in to what they did last.
3. **Recover the facts** below.

**You must find:**
1. The command-and-control (C2) domain.
2. The name of the autorun value used for persistence.
3. The process that was dumped to steal credentials.
