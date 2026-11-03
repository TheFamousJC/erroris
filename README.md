# Erroris — computer and internet help

Live: https://thefamousjc.github.io/erroris/
Repository: https://github.com/TheFamousJC/erroris

Static lookup with 217 troubleshooting guides and 2,451 code references (2,668 entries total). Coverage includes browsers, internet connections, HTTP, Windows, macOS, apps, email, developer tools and explicitly labelled legacy hardware.

Guides contain practical checks and escalation advice; they do not diagnose a device. References contain identifiers and context-gathering advice, not a reviewed fix. 2,461 Win32 identifier pairs discovered through Lifewire were cross-checked against Microsoft's official decimal/symbol definitions; 32 have contextual troubleshooting advice. 92 unmatched identifiers were held out. No bulk secondary article descriptions were copied. The HP manual is version 1.0 from July 1997. Secondary beep-code tables require exact-model verification.

Browse defaults to guides, with reference/all filters and 20 entries per page. Lookup searches both kinds and shows up to 50 matches. Source labels distinguish official documentation from secondary references. Audience-specific steps, checklists and source tabs remain available. Always seek the help and advice of a professional.

Edit data/catalogue.json, then run:

    node scripts/build-catalogue.cjs
    node scripts/test-catalogue.cjs

The deployed repository root contains dist files. Erroris-source.zip contains the full source tree with data and scripts. Local provenance reports are in outputs/lifewire-crosscheck-report.json and outputs/digital-expansion-report.json.

No AI, live search API, automatic device/network tests, video ranking or live outage checks are connected. Google/YouTube links are external searches, not reviewed results. Version notes do not verify compatibility. Recent IDs are saved only in the browser. Earlier appliance research is archived separately.

Resolution expansion: 20 existing Windows Installer references now have four-step workflows, applicability restrictions, outcome checks and official Microsoft sources. This includes source files, logs, language/platform mismatches, invalid patches, policy escalation, Safe Mode and successful restart-required status 3010. See outputs/installer-resolution-report.json locally. These workflows combine official code definitions with editorial sequencing and do not guarantee a repair.

