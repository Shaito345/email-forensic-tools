# Free vs Paid Email Forensics Tools, a Decision Table

Free tools cover many email forensics jobs and paid tools cover the rest. This table matches the job to the kind of tool. Every tool named here sits in the [tool list](../README.md), where prices were checked on 17 October 2026.

*Last reviewed 20 November 2026.*

> We are the team behind MailXaminer at SysTools. The list marks it and so does this page.

## Decision Table

| Your job | Free options in the list | Paid options in the list |
|---|---|---|
| Check the header of one message | Google Admin Toolbox Messageheader, emlAnalyzer | None in our list |
| Convert email files to another format | readpst (PST to MBOX or EML) | Aid4Mail |
| Scan a drive for email evidence | Autopsy, The Sleuth Kit | FTK, EnCase Forensic |
| Search email files by keyword | Autopsy | Intella, MailXaminer (we make it) |
| Handle a large case from review to production | None in our list | Relativity, Nuix |
| Collect email from a cloud account | None in our list | Forensic Email Collector, Aid4Mail |

Find the vendor links in the [Free](../README.md#free) and [Paid](../README.md#paid) sections of the list. Our list is not complete, so "None in our list" means we have not listed a tool for that job.

## Five Rules for Choosing

1. **Start free for one file or a few messages.** The free tools in the list show headers, convert PST files and check attachment metadata with ExifTool.
2. **Start free when you work in a command line.** emlAnalyzer and The Sleuth Kit are command line tools.
3. **Look at paid tools when the evidence sits in a live cloud account.** The paid list names Forensic Email Collector for cloud providers and Aid4Mail for email collection and conversion.
4. **Look at paid tools when a case needs review at scale.** Intella, Nuix and Relativity are built for search and review of large volumes.
5. **Test any tool before it touches real evidence.** Keep the original file and its hash values. Ask your lawyer which standards your court expects.

## What NIST Tests

NIST operates the Computer Forensics Tool Testing Program to establish a methodology for testing forensic software. Its test areas include disk imaging, deleted file recovery and forensic string search. That page does not name email among its test areas, so check for a report that matches your task before you rely on a tool.

## Sources

- [Email Forensics Tools list](../README.md)
- [NIST: Computer Forensics Tool Testing Program](https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-program-cftt)
- [DHS: NIST CFTT reports](https://www.dhs.gov/science-and-technology/nist-cftt-reports)

Nothing here is legal advice.

## Related Guides

- [Email Header Cheat Sheet](https://github.com/Shaito345/email-header-cheatsheet)
