# Hi, I'm Rofi

**Workflow automation and internal tools, Indonesia.**

I automate the admin work teams still do by hand, like the monthly spreadsheet someone rebuilds from scratch or the invoice someone retypes into another system. Where a wrong value would cost money, I keep a person in the loop to check it. I also keep the setup simple, so the team can run it without me.

I started in HR operations, so most of my automation so far handles people data and Indonesian business admin.

<!-- TODO(Rofi): add one or two real, anonymised results, e.g.
     "Automated the monthly attendance-to-payroll recap: about X hours down to Y minutes."
     Use numbers you can defend if someone asks. If you can't, delete this comment and the line below. -->
<!-- **Results:** … -->

## What I automate

- Pulling fields out of PDFs and scans into rows someone can review before export
- Google Sheets and Apps Script systems, and XLSX files generated from code
- Recurring recaps and exports that move data from one tool into another
- LLM steps inside a pipeline, with a person approving the output

Most of this runs on private employee and company data, so the repos are closed. Things I've built there include a master-data system on Google Sheets and Apps Script, an attendance-to-payroll recap, a job-description generator, and a CV screener that parses PDFs, removes personal data before the LLM sees it, scores each CV and writes the results to CSV.

## Public projects

**[DokumenAI](https://github.com/Reckbeg/dokumenai)**: a self-hostable prototype for Indonesian business documents (invoices, faktur pajak, transfer proofs, POs). It extracts the fields, you check them, and you export to CSV, XLSX or JSON. You pick the model endpoint, and it can be a local one.
`Next.js` `TypeScript` `SQLite` `Docker`

**[PeopleSheet](https://github.com/Reckbeg/PeopleSheet)**: generates nine XLSX workbooks with working formulas for Indonesian HR admin, including PPh21, THR, BPJS, attendance and leave. No login, and it stores nothing. → [peoplesheet.biz.id](https://peoplesheet.biz.id)
`ExcelJS` `Vitest` `GitHub Actions`

## Open source

- [FMLibreEditor](https://github.com/tozmoz/FMLibreEditor) (Rust): I added [club export to CSV and JSON](https://github.com/tozmoz/FMLibreEditor/pull/135), read live from the running game, and an [Indonesian interface](https://github.com/tozmoz/FMLibreEditor/pull/138). Both merged.
- [HyperFormula](https://github.com/handsontable/hyperformula): I added [Indonesian spreadsheet function names](https://github.com/handsontable/hyperformula/pull/1674) and [fixed wide tables in the docs on phones](https://github.com/handsontable/hyperformula/pull/1675). Both merged.
- Meta AI Hackathon 2026, team project NextStep: I wrote the [ASP.NET Core client for the model API](https://github.com/NOOROWAISSI/meta-ai-hackathon-2026/pull/10) and fixes that flag preparation plans the user can't actually carry out.

## Work with me

Send me the task your team keeps doing by hand, and I'll tell you whether it's worth automating.

[rofiibnu.com](https://rofiibnu.com) · [LinkedIn](https://www.linkedin.com/in/rofiibnu) · [hi@rofiibnu.com](mailto:hi@rofiibnu.com)
