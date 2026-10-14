### Võ Lê Anh Tuấn · `vlat273`

Cybersecurity student at Swinburne University of Technology, currently interning in IT
operations. I came up through network operations and SIEM before moving toward
offensive security — which means I read an attack path from both sides.

Working through the HTB Certified Penetration Testing Specialist (CPTS) track, and
building case files from authorised lab and internship work.

---

**Things I have actually done**

- **Authorised web application assessment** — during my network internship I proposed
  and received approval to assess an internal web application, then reproduced,
  root-caused and remediated three vulnerabilities in a production PHP CMS:
  SQL injection leading to admin authentication bypass, HTTP verb tampering leading to
  privilege escalation, and a reflected XSS issue I found myself. I fixed the code,
  deployed to production and re-tested to verify.

- **Distributed Splunk Enterprise lab** — onboarded five log families (Windows Event,
  Sysmon, Linux syslog, web application, firewall), validated ingestion and field
  extraction, normalised time, and shipped dashboards, alerts and POC documentation.

- **Network operations** — multi-VLAN production segments and the training lab behind
  them: Cisco routing and switching, firewalls, VPN, VMware ESXi and EVE-NG, plus the
  runbooks and backups that keep it recoverable.

- **[Event Payment Registration](https://github.com/tuankhongbietcode/Transactions)** —
  event ticketing with payOS payment integration, HMAC-SHA256 verified webhooks, QR
  check-in with duplicate-entry prevention, Supabase storage and Excel reconciliation
  export. Hardened with an admin token gate, CORS allowlist, rate limiting, helmet,
  CI and API smoke tests.

---

**How I work**

Method first, evidence always, no inflated claims. Nothing goes public that I cannot
reproduce from an authorised environment — and nothing that has not been sanitised
first. A case file with a credential or a flag in it is worth less than no case file
at all.

**Interests** — web application security · Active Directory · detection engineering ·
network security
