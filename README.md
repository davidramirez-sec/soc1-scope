# SOC 1 Scope Tool

A straightforward decision tool for companies trying to figure out whether they actually need a SOC 1 report.

**Live:** https://davidramirez-sec.github.io/soc1-scope

---

## Why I built this

The same question comes up constantly. "Do we need a SOC 1?" Most of the time the person asking has just been approached by a client or a procurement team and has no idea what they're getting into.

I wanted something that could walk through the right questions and give a straight answer without requiring someone to already understand SSAE 18.

8 questions, one at a time. Takes about 3 minutes.

## How it works

Questions cover the things that actually determine SOC 1 applicability. What service you provide, whether your clients' auditors care about your controls, how directly your service connects to client financial reporting, how mature your controls are, and whether your timeline supports a Type I or Type II engagement.

At the end you get a verdict on whether SOC 1 applies, which report type makes sense given your situation, and which control domains would likely be in scope.

The scoring logic is based on SSAE 18 applicability criteria. It is directional not definitive, and the disclaimer at the end of every result makes that clear.

## Four possible results

SOC 1 is strongly indicated. SOC 1 is worth exploring. SOC 1 may apply but controls are not ready yet. SOC 1 is likely not required.

Each result explains the reasoning behind it.

## Stack

Vanilla HTML, CSS, and JavaScript. No frameworks, no backend.

```
git clone https://github.com/davidramirez-sec/soc1-scope.git
open index.html
```

## What I'd add next

Industry specific guidance since the SOC 1 threshold is different for a payroll processor versus a cloud hosting provider. A side by side comparison against SOC 2 for companies trying to figure out which one they need. A printable version of the result for internal discussions.

## About

Built by David Ramirez — SSCP · CCSP · CySA+ · Security+ · ITIL v4

davidramirez.tech@gmail.com

Directional assessment only. Not a substitute for advice from a licensed CPA firm or service auditor.
