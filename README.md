# Awesome-Cloud-PDF-Tools

## Top Cloud PDF Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Browser-Based PDF Editing, Free Web Utilities & Self-Hosted PDF Toolkits*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud PDF Tools**. These are browser-based utilities that let users merge, split, compress, convert, and edit PDFs without installing desktop software—ranging from generous free tiers with privacy-preserving local processing to subscription editors with advanced AI features.



**Examples** include Adobe Acrobat Web, Smallpdf, iLovePDF, PDF24, Sejda, PDF Candy, and Stirling-PDF (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-task limits, and keeping documents entirely on your own infrastructure. The open-source landscape is anchored by **Stirling-PDF** (the comprehensive self-hosted web UI), **pdf-lib** (the JavaScript creation/manipulation library), and **Sejda SDK** (the AGPLv3 core behind Sejda's web tools), with **PDF.js** providing the rendering foundation for browser-based viewers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global PDF software and cloud document editing market is valued between **$2.5B and $4.5B**, expanding at an estimated 8–15% CAGR toward double-digit billions over the coming decade. The sector exhibits a barbell market structure: **moderately concentrated at the enterprise peak** (dominated by Adobe and a select few enterprise suites capturing >50–60% of commercial market revenues) yet **highly fragmented across the consumer, SMB, and web-utility landscape**, where dozens of freemium and bootstrapped cloud SaaS platforms compete vigorously on accessibility, tool-breadth, and browser-first simplicity.



## SaaS/Hosted Platforms



| Product | Company Scale (Revenue / Valuation) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Acrobat Web](https://www.adobe.com/acrobat/online.html)** | **~$24B+ revenue** (~$100B+ market cap) | Adobe's browser-based PDF tools plus Acrobat Standard/Pro subscription for full document workflows. | **Standard**: **$14.99/mo** (annual commitment) or $24.99/mo (monthly). **Pro**: **$19.99/mo** (annual commitment) or $29.99/mo (monthly). | **Free plan limits**: Free tools permit **1 free transaction** without sign-in; signed-in free accounts get **1 free premium transaction every 30 days**. Unlimited basic viewing, form filling, and commenting. Max 100MB per file (up to 2GB for Compress; 1,500 pages max). |
| **[PDFescape](https://www.pdfescape.com/)** | **~$100M+ revenue** (parent Claranova / Avanquest) | Online PDF editor, form filler, and annotation suite with companion desktop software. | **Premium**: **$2.99/mo** (billed annually at $35.88/yr) or $5.99/mo month-to-month. **Ultimate**: $5.99/mo (annual) or $8.99/mo month-to-month. | **Free forever plan**: Web editor is free with strict file caps of **max 10 MB per file** and **max 100 pages per document**; basic form filler and annotations included (desktop app offers 7-day trial). |
| **[iLovePDF](https://www.ilovepdf.com/)** | **~$20M–$40M ARR** (bootstrapped) | High-volume PDF toolkit providing browser-based conversion, compression, merge, OCR, and e-signatures. | **Premium**: **$4.00/mo** (billed annually at $48/yr) or **$7.00/mo** month-to-month. Custom enterprise tiers available. | **Free forever plan**: Access to web tools with processing throttles: max **100MB per task** for most operations, **15MB** for OCR/complex conversions, non-batch processing (limited files per task). |
| **[Smallpdf](https://smallpdf.com/)** | **~$8M–$11M ARR** (bootstrapped, ~$5M raised) | Swiss-engineered document suite offering 30+ browser tools, AI summarization, and integrated e-signing. | **Pro**: **$9.00/mo** (billed annually at $108/yr) or $12.00/mo month-to-month. **Team**: $7.00/seat/mo (annual). | **Free forever plan**: Access to 30+ web tools with daily download caps; eSign capped at **2 signature requests/month**. Paid Pro plan offers a **7-day free trial** with full features. |
| **[DocHub](https://dochub.com/)** | **~$6M+ ARR** (subsidiary of airSlate, $1.25B unicorn) | Document editor and workflow tool deeply integrated with Google Workspace and cloud drives. | **Basic**: **$8.00/user/mo** (billed annually) or **$11.00/mo** monthly. **Pro**: **$12.00/user/mo** (annual) or **$16.00/mo** monthly. | **Free forever plan**: Capped at a **shared limit of 3 documents/actions per month**; up to 3 signature requests/mo; max 2 collaborators per document. |
| **[Lumin PDF](https://www.luminpdf.com/)** | **~$4.6M ARR** (bootstrapped / private) | Collaborative PDF editor and workflow platform featuring Google Drive sync and e-signatures. | **Pro**: **$19.00/mo** (billed annually) or **$30.00/mo** month-to-month. Paid workspace seats available. | **Free forever plan**: Limited to **3 completed document exports/shares per month**; unlimited drafts and free unlimited Viewer seats. Also offers a **7-day free trial** for Pro workspace features. |
| **[Sejda](https://www.sejda.com/)** | **Private / Bootstrapped** (~$2M–$5M estimated) | Browser-based PDF manipulation tools and cross-platform desktop application. | **Web Week Pass**: **$5.00 one-time** (7 days). **Desktop+Web Annual**: **$63.00/yr** ($5.25/mo equivalent) or **$7.50/mo** monthly. | **Free forever plan**: Limited to **3 tasks per hour**, max **200 pages or 50 MB** per document; OCR capped at **10 pages**; combining capped at **30 files and 50 pages**; 1 document at a time. |
| **[PDF Candy](https://pdfcandy.com/)** | **Private / Bootstrapped** (Icecream Apps) | All-in-one web utility suite covering 47+ PDF conversion, security, and editing tools. | **Web Monthly**: **$6.00/mo**. **Desktop + Web Annual**: **$4.00/mo** (billed annually at $48/yr). **Lifetime**: $99.00 one-time. | **Free forever plan**: Capped strictly at **1 task every 60 minutes (1 task/hour)** across all web tools; no batch operations; max file size capped at 10–20MB depending on operation. |
| **[PDF24](https://tools.pdf24.org/)** | **Private / Bootstrapped** (Geek Software GmbH) | Comprehensive suite of 122+ online PDF and image utilities powered by client-side browser processing. | **Free** ($0.00 for individuals & commercial use; ad-supported; commercial REST API licenses available). | **Free forever plan**: **100% free with unlimited tasks, unlimited file sizes, and no daily/hourly caps**. No account or registration needed; processing occurs client-side in browser without server upload. |



## Open-Source GitHub Projects



- **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** [![GitHub Stars](https://img.shields.io/github/stars/Stirling-Tools/Stirling-PDF?style=social&color=white)](https://github.com/Stirling-Tools/Stirling-PDF/stargazers)  

  **The self-hosted PDF manipulation suite.** A locally hosted web application for merging, splitting, converting, OCR, and signing PDFs—all processing stays on your infrastructure. **Strengths**: comprehensive tool coverage in a single Docker-deployable package; no per-task limits or file uploads to third parties. Best for teams and individuals wanting a private, web-based PDF toolkit without subscription costs.



- **[pdf-lib](https://github.com/Hopding/pdf-lib)** [![GitHub Stars](https://img.shields.io/github/stars/Hopding/pdf-lib?style=social&color=white)](https://github.com/Hopding/pdf-lib/stargazers)  

  **The JavaScript PDF creation and manipulation library.** MIT licensed. Create and modify PDFs programmatically in Node.js or the browser—embed text, images, and form fields, split/merge documents, and fill forms. Best for JavaScript/TypeScript applications needing embedded PDF generation without an external API.



- **[Sejda SDK](https://github.com/sejda-pdf/sejda-sdk)** [![GitHub Stars](https://img.shields.io/github/stars/sejda-pdf/sejda-sdk?style=social&color=white)](https://github.com/sejda-pdf/sejda-sdk/stargazers)  

  **The open-source core behind Sejda's web tools.** AGPLv3 licensed for open-source use—unlimited tasks and executions. **Capabilities**: merge, split, compress, extract text, encrypt/decrypt, image-to-PDF, watermark. **Commercial caveat**: closed-source use requires a PRO license at **$2,000/year** . Best for open-source projects or teams willing to license commercially.



- **[PDF.js](https://github.com/mozilla/pdf.js)** [![GitHub Stars](https://img.shields.io/github/stars/mozilla/pdf.js?style=social&color=white)](https://github.com/mozilla/pdf.js/stargazers)  

  **The browser-based PDF rendering standard.** Apache 2.0 licensed. Mozilla's PDF viewer that renders documents in HTML5 canvas without plugins—the foundation for many web PDF viewers. Best for displaying PDFs in web applications; not a manipulation API.



### Additional Strong Open-Source Options



- **qpdf** — Command-line PDF transformation tool for encryption, linearization, and structural repair. Best for scripted batch operations.

- **PyMuPDF** — High-performance Python PDF library (AGPL or commercial). Best for Python data pipelines.

- **Docling (IBM)** — Document conversion library with PDF parsing and structure extraction. Best for AI/RAG pipelines needing PDF-to-structured-text.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Free tiers vary dramatically in usefulness**: PDF24 is genuinely free with no signup, no watermarks, and local processing ; Adobe limits signed-in users to one premium transaction every 30 days ; Smallpdf's free tier caps downloads and Sign.com at 2 documents/month ; DocHub's free tier is extremely limited at 3 shared uses/month .

- **Privacy matters with cloud PDF tools**: Most SaaS tools upload files to their servers. PDF24 processes most files locally in your browser ; self-hosted Stirling-PDF keeps everything on your infrastructure. Review privacy policies before uploading sensitive documents.

- **"Free" often means limited**: Sejda and PDF Candy offer free tiers with page/hourly restrictions. Adobe's free online tools are functional but tightly capped. If you process documents regularly, a paid tier or self-hosted tool is usually necessary.

- **Self-hosted toolkits require infrastructure**: Stirling-PDF and pdf-lib need servers or application integration—free software is not free operations.



---



**Made for individuals, teams, and organizations needing reliable PDF processing without desktop software.**  

Let's make cloud PDF tools more open, privacy-respecting, and self-hostable.
