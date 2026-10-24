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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Adobe Acrobat Web](https://www.adobe.com/acrobat/online.html)** | Adobe's browser-based PDF tools plus Acrobat Pro subscription for full editing. | **Acrobat Pro**: **£19.97/mo** (incl. VAT) for individuals; **£20.22/mo** per licence for teams (excl. VAT) . | **Free online tools**: Most tools allow **one free transaction** without sign-in. Signed-in users get **one free premium transaction every 30 days**; basic fill/sign/comment is free. File limits: 100MB standard, 2GB for Compress, 1,500 pages max . |

| **[Smallpdf](https://smallpdf.com/)** | Swiss-made PDF suite with 30+ tools, AI features, and eSign integration. | **Pro**: **$9.00/month** (billed annually at $108/year); **Team**: $7/seat/month (2–19 seats) . | **Free tier**: Access to 30+ tools with **limited document downloads** and restricted mobile app access. Sign.com free accounts capped at **2 documents/month** . 7-day free trial for Pro . |

| **[iLovePDF](https://www.ilovepdf.com/)** | Popular PDF toolkit with merge, split, compress, convert, and OCR tools. | **Premium**: **$4/month** (billed annually at $48/year) or **$7/month** monthly . Enterprise pricing custom. | **Free tier**: Core tools with **limited file processing**. Max file size **100MB** for most tasks; 15MB for some conversions . |

| **[PDF24](https://tools.pdf24.org/)** | 122 free browser-based PDF and image tools, with privacy-preserving local processing. | **Free** (ad-supported). Desktop PDF24 Creator also free for commercial use . | **Fully free**: All 122 tools, no signup, no watermarks, no daily limits. Most tools process files **locally in your browser**—files never leave your device . |

| **[Sejda](https://www.sejda.com/)** | Browser-based PDF tools plus a downloadable desktop app. | **Web Week Pass**: **$5 one-time** (7 days). **Desktop+Web Annual**: **$63/year** . | **Free tier**: Limited pages/hourly usage, restricted file uploads, tool-specific limits. **No signup required** . |

| **[PDF Candy](https://pdfcandy.com/)** | Browser-based PDF toolkit with desktop app option. | **Desktop + Web Annual**: **$4/month** (billed annually). **Web Monthly**: $6/month. **Lifetime**: $99 one-time . | **Free tier**: Access to most tools with **page and hourly limits**, no batch processing, file size restrictions. No account required . |

| **[Lumin PDF](https://www.luminpdf.com/)** | Collaborative PDF editor with eSign and real-time annotation. | **Paid plans** start around **$9/month** (per SourceForge listing) . Seat-based pricing rolling out (Collab/Full seats) . | **Viewer seats are free** on every plan. **7-day free trial** with Full seats for workspaces that haven't had a paid plan . |

| **[DocHub](https://dochub.com/)** | PDF editor with eSign, Google Workspace integration, and AI assistant. | Pricing not published in search results; paid tiers (Basic, Pro, Site License) available. | **Free tier**: **Shared limit of 3 uses/month** for core tools. Page tools (merge, rotate, reorder, delete) are available. Document collaboration limited to 2 people . |

| **[PDFescape](https://www.pdfescape.com/)** | Online PDF editor and form filler with desktop app. | **Premium**: **$2.99/month** (billed yearly) or $5.99/monthly. **Ultimate**: $5.99/month (yearly) or $8.99/monthly . | **Free tier** available with feature restrictions (not detailed in search results). **15-day money-back guarantee** on paid plans . |



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
