[🇫🇷 Français](README.md) · **🇬🇧 English**

# Hi there 👋

I'm **Éric**. I like building things that work.

After a long road through databases and Windows infrastructure, what still gives me
the most pleasure is **building my own tools**, usually in PowerShell, self-contained,
no install, with a small web UI in the browser. That makes them usable anywhere,
including locked-down or air-gapped environments. When they're useful to others,
I publish them here under the MIT license.

## 🛠️ My tools

### [PS-MRTG](https://github.com/vietnamix/ps-mrtg) · network bandwidth monitoring
A modern take on the venerable MRTG, rebuilt for the Windows world. It collects a
server's network traffic (SNMP, performance counters) and renders it as readable,
exportable graphs straight in the browser. Built to run even on pure Windows and
disconnected setups.

### [PS-PING](https://github.com/vietnamix/ps-ping) · in-depth ping analysis
Much more than `ping -t`: a fine-grained latency analysis with smart zoom that
surfaces network inconsistencies the usual tools (ping, SmokePing) miss. Automatic
anomaly detection via sliding-window heuristics, with an interactive web UI to
explore the measurements.

### [PS-NCDU](https://github.com/vietnamix/ps-ncdu) · disk usage analyzer
In the spirit of NCDU (Linux) and TreeSize (Windows), but in native PowerShell with
a dynamic web UI. Shows in real time what's filling a disk, with nothing to install.
Ideal for regulated environments (banking, pharma) where deploying external tools
isn't allowed.

### [PS-ZIM](https://github.com/vietnamix/ps-zim) · offline documentation reader
Reads documentation archives (Wikipedia dumps, static bases, exported wikis) in the
browser, locally and fully offline. Built-in HTTP server and wiki-format parsing.
Handy when you work cut off from the network.

> Common thread: 100% PowerShell, zero install, runs on any Windows. All
> co-built with LLMs, which has become a big part of how I code today.

---

`PowerShell` · `SQL` · `C#` · `Python` · Windows/Linux infra & automation
[LinkedIn](https://linkedin.com/in/eric-guiffault) · eric@guiffault.com · https://eric.guiffault.com(https://eric.guiffault.com)
