# Power BI Resources

A curated list of Power BI resources: blogs, software, demos, templates, AI and more, organized by category.

**Legend:** 🆓 free · 💰 paid · 🔀 freemium (free tier + paid features) · 🇳🇱 🇧🇪 Dutch / Belgian creator or event · ⭐ good starting point

Contributions are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Official Microsoft](#official-microsoft)
- [Learning & Courses](#learning--courses)
- [Certifications](#certifications)
- [Reference & Documentation](#reference--documentation)
- [Blogs](#blogs)
- [YouTube Channels](#youtube-channels)
- [Podcasts & Newsletters](#podcasts--newsletters)
- [Books](#books)
- [Software & Tools](#software--tools)
  - [Microsoft Tools](#microsoft-tools)
  - [External Tools](#external-tools)
  - [Source Control, CI/CD & DevOps](#source-control-cicd--devops)
  - [Administration, Monitoring & Governance](#administration-monitoring--governance)
  - [Developer, Embedding & APIs](#developer-embedding--apis)
- [Custom Visuals](#custom-visuals)
- [Templates, Themes & Design](#templates-themes--design)
- [Demos, Samples & Datasets](#demos-samples--datasets)
- [AI](#ai)
  - [AI Built Into Power BI & Fabric](#ai-built-into-power-bi--fabric)
  - [MCP Servers](#mcp-servers)
  - [Agent Skills & Plugins](#agent-skills--plugins)
  - [Reading on AI & Power BI](#reading-on-ai--power-bi)
- [Community & Events](#community--events)
- [Dutch & Belgian Community](#dutch--belgian-community)

---

## Official Microsoft

- ⭐ [Power BI documentation](https://learn.microsoft.com/power-bi/) - The official docs for Desktop, the service, mobile, embedding and administration.
- ⭐ [Power BI Blog](https://powerbi.microsoft.com/blog/) - Product announcements and the monthly feature summary. Now hosted on the Fabric Community site.
- [Microsoft Fabric Blog](https://blog.fabric.microsoft.com/) - Updates for Fabric, the platform Power BI is now part of.
- [What's new in Power BI](https://learn.microsoft.com/power-bi/fundamentals/whats-new) - Monthly overview of new features.
- [Fabric Roadmap](https://roadmap.fabric.microsoft.com/) - Planned and shipped features for Power BI and Fabric.
- [Fabric Ideas](https://ideas.fabric.microsoft.com/) - Submit and vote on feature requests.
- [Power BI guidance](https://learn.microsoft.com/power-bi/guidance/) - Microsoft's best-practice articles on modeling, DAX, reports and deployment.
- [Power BI implementation planning](https://learn.microsoft.com/power-bi/guidance/powerbi-implementation-planning-introduction) - In-depth series on planning an enterprise rollout.
- [Microsoft Fabric adoption roadmap](https://learn.microsoft.com/power-bi/guidance/fabric-adoption-roadmap) - Framework for data culture, governance, Center of Excellence and mentoring.
- [Fabric known issues](https://learn.microsoft.com/fabric/known-issues/fabric-known-issues) - Currently active bugs in Power BI and Fabric, with workarounds.
- [Fabric support & status](https://support.fabric.microsoft.com/) - Service health and support portal.

## Learning & Courses

- ⭐ [Microsoft Learn: Power BI training](https://learn.microsoft.com/training/powerplatform/power-bi) 🆓 - Free learning paths from beginner to advanced.
- [Microsoft Learn: Fabric training](https://learn.microsoft.com/training/fabric/) 🆓 - Learning paths for Fabric (lakehouse, warehouse, Direct Lake, real-time).
- ⭐ [SQLBI training](https://www.sqlbi.com/training/) 💰 - Mastering DAX, Optimizing DAX and Data Modeling courses by Marco Russo and Alberto Ferrari. Several introductory courses are free.
- [Enterprise DNA](https://enterprisedna.co/) 💰 - Large course library and community, with an increasing AI focus.
- [Maven Analytics](https://mavenanalytics.io/) 🔀 - Hands-on Power BI courses, guided projects and free datasets.
- [Microsoft Power BI Data Analyst Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/microsoft-power-bi-data-analyst) 💰 - Microsoft's own course track, prepares for PL-300.
- [Pragmatic Works](https://pragmaticworks.com/) 🔀 - On-demand training and free "Learn with the Nerds" sessions.
- [Excelerator BI](https://exceleratorbi.com.au/) 💰 - Matt Allington's Power BI and DAX training.
- [RADACAD](https://radacad.com/) 💰 - Reza Rad and Leila Etaati's training, books and articles.
- [DataCamp: Power BI](https://www.datacamp.com/category/power-bi) 💰 - Interactive browser-based courses.

## Certifications

- ⭐ [PL-300: Power BI Data Analyst Associate](https://learn.microsoft.com/credentials/certifications/data-analyst-associate/) - The core Power BI certification.
- [DP-600: Fabric Analytics Engineer Associate](https://learn.microsoft.com/credentials/certifications/fabric-analytics-engineer-associate/) - Semantic models, lakehouses and warehouses in Fabric.
- [DP-700: Fabric Data Engineer Associate](https://learn.microsoft.com/credentials/certifications/fabric-data-engineer-associate/) - Data engineering in Fabric.
- [Microsoft Learn exam sandbox](https://aka.ms/examdemo) - Try the exam interface before you take an exam.

## Reference & Documentation

**DAX**

- ⭐ [DAX Guide](https://dax.guide/) 🆓 - The best DAX function reference, with examples and compatibility notes.
- ⭐ [DAX Patterns](https://www.daxpatterns.com/) 🆓 - Ready-to-use solutions for common problems (time intelligence, ABC classification, budget, and more).
- [DAX.do](https://dax.do/) 🆓 - Run DAX queries against a sample model in your browser.
- [DAX function reference (Microsoft)](https://learn.microsoft.com/dax/) - Official DAX docs.
- [SQLBI articles](https://www.sqlbi.com/articles/) 🆓 - Hundreds of in-depth articles on DAX and data modeling.
- [DAX Formatter](https://www.daxformatter.com/) 🆓 - Formats DAX code according to the SQLBI style.
- [DAX.tips](https://dax.tips/) 🆓 - Phil Seamark's advanced DAX and performance articles.

**Power Query / M**

- [Power Query M reference (Microsoft)](https://learn.microsoft.com/powerquery-m/) - Official M language and function docs.
- [powerquery.how](https://powerquery.how/) 🆓 🇳🇱 - Rick de Groot's complete, example-based M function reference.
- [Power Query M Primer](https://bengribaudo.com/power-query-m-primer) 🆓 - Ben Gribaudo's deep series on the M language.
- [Power Query Formatter](https://www.powerqueryformatter.com/) 🆓 - Formats M code.

**Modeling, file formats & visuals**

- [Star schema guidance](https://learn.microsoft.com/power-bi/guidance/star-schema) - Why and how to build star schemas for Power BI.
- [Power BI Project (PBIP)](https://learn.microsoft.com/power-bi/developer/projects/projects-overview) - Save reports and models as folders of text files for source control.
- [TMDL](https://learn.microsoft.com/analysis-services/tmdl/tmdl-overview) - Tabular Model Definition Language, the text format for semantic models.
- [PBIR report format](https://learn.microsoft.com/power-bi/developer/projects/projects-report) - The text-based, documented report format.
- [Power BI Visuals Reference](https://www.sqlbi.com/ref/power-bi-visuals-reference/) 🆓 - SQLBI/OKVIZ poster that helps you choose the right visual.
- [Financial Times Visual Vocabulary](https://github.com/Financial-Times/chart-doctor/tree/main/visual-vocabulary) 🆓 - Choose a chart type based on what you want to show.
- [Tabular Editor documentation](https://docs.tabulareditor.com/) - Docs for TE2/TE3, C# scripting and the Best Practice Analyzer.

## Blogs

- ⭐ [SQLBI](https://www.sqlbi.com/) - Marco Russo and Alberto Ferrari: the authority on DAX and tabular modeling.
- ⭐ [Chris Webb's BI Blog](https://blog.crossjoin.co.uk/) - Deep dives on Power Query, performance, Direct Lake and the service, by a member of the Fabric CAT team.
- ⭐ [Data Goblins](https://data-goblins.com/) - Kurt Buhler on report design, Tabular Editor and agentic development.
- [Tabular Editor Blog](https://tabulareditor.com/blog) - Modeling, C# scripts, DevOps and AI agents for semantic models.
- [PowerBI.tips](https://powerbi.tips/) - Tutorials, tools, layouts and the Explicit Measures podcast.
- [RADACAD](https://radacad.com/blog) - Reza Rad's large catalog of how-to articles.
- [The BIccountant](https://www.thebiccountant.com/) - Imke Feldmann's advanced Power Query and finance solutions.
- [Kasper On BI](https://www.kasperonbi.com/) 🇳🇱 - Kasper de Jonge, Principal PM at Microsoft, on modeling and security.
- [Data Mozart](https://data-mozart.com/) - Nikola Ilic on Power BI and Fabric, explained in plain language.
- [BI Polar](https://ssbipolar.com/) - Matthew Roche on data culture, Power BI adoption and Fabric.
- [Fourmoo](https://www.fourmoo.com/blog/) - Gilbert Quevauvilliers on Power BI and Fabric administration and performance.
- [Paul Turley's Blog](https://sqlserverbi.blog/) - Enterprise BI design and best practices.
- [Excelerator BI Blog](https://exceleratorbi.com.au/blogs/) - Matt Allington on DAX and Power BI for business users.
- [P3 Adaptive Blog](https://p3adaptive.com/blog/) - Practical Power BI and DAX articles.
- [Havens Consulting](https://www.havensconsulting.net/) - Reid Havens on report design and UX.
- [Fabric.guru](https://fabric.guru/) - Sandeep Pawar on Semantic Link, notebooks and Fabric automation.
- [Data Monkey](https://datamonkeysite.com/) - Mim Djouallah on Fabric, Direct Lake and Python.
- [Gerhard Brueckl](https://blog.gbrueckl.at/) - Power BI, Fabric and the VS Code extensions he maintains.
- [Brunner BI](https://www.brunner.bi/blog) - Model cleanup, governance and Measure Killer.
- [Kerry Kolosko](https://kerrykolosko.com/) - Data visualization, Deneb templates and design.
- [Power BI Docs](https://powerbidocs.com/) - Beginner-friendly tutorials and DAX examples.
- [BI Gorilla](https://gorilla.bi/) 🇳🇱 - Rick de Groot on Power Query and DAX.
- [Data-Marc](https://data-marc.com/) 🇳🇱 - Marc Lelijveld on enterprise Power BI, governance and Fabric.

## YouTube Channels

- ⭐ [Guy in a Cube](https://www.youtube.com/@GuyInACube) - Adam Saxton and Patrick LeBlanc: Power BI and Fabric news and how-tos, plus weekly livestreams.
- ⭐ [SQLBI](https://www.youtube.com/@SQLBI) - DAX and modeling explained by Marco Russo and Alberto Ferrari.
- [Microsoft Power BI](https://www.youtube.com/@MicrosoftPowerBI) - Official channel with the monthly feature updates.
- [Curbal](https://www.youtube.com/@CurbalEN) - Ruth Pozuelo: tutorials and DAX fridays.
- [How to Power BI](https://www.youtube.com/@HowtoPowerBI) 🇳🇱 - Bas Dohmen: practical, clear tutorials and report design.
- [BI Gorilla](https://www.youtube.com/@BIGorilla) 🇳🇱 - Rick de Groot: Power Query and DAX.
- [Havens Consulting](https://www.youtube.com/@HavensConsulting) - Report design, UX and tips.
- [PowerBI.tips](https://www.youtube.com/@PowerBItips) - Tutorials and the Explicit Measures podcast.
- [Goodly](https://www.youtube.com/@GoodlyChandeep) - Chandeep Chhabra: Power Query and DAX.
- [Solutions Abroad](https://www.youtube.com/@SolutionsAbroad) - Practical DAX and visualization.
- [Enterprise DNA](https://www.youtube.com/@EnterpriseDNA) - Tutorials and showcases.
- [Access Analytic](https://www.youtube.com/@AccessAnalytic) - Wyn Hopkins on Power BI and Excel.
- [Pragmatic Works](https://www.youtube.com/@PragmaticWorks) - Long-form training sessions.
- [RADACAD](https://www.youtube.com/@RADACAD) - Reza Rad and Leila Etaati.
- [BI Elite](https://www.youtube.com/@BIElite) - Tips, tricks and Power Apps integration.
- [Maven Analytics](https://www.youtube.com/@MavenAnalytics) - Data skills and Power BI tutorials.

## Podcasts & Newsletters

- [Explicit Measures](https://powerbi.tips/podcast/) - Live podcast by Mike Carlo and Tommy Puglia on the "why" of Power BI and Fabric.
- [Raw Data with Rob Collie](https://p3adaptive.com/rawdatapodcast/) - P3 Adaptive's podcast on data, AI and the business side of BI.
- ⭐ [Power BI Weekly](https://endjin.com/microsoft-partner/newsletter/powerbi-weekly/) 🆓 - Weekly selection of the best Power BI content, by endjin. Sister newsletter: Fabric Weekly.
- [SQLBI Newsletter](https://www.sqlbi.com/newsletter/) 🆓 - New articles, videos and tools from SQLBI.

## Books

- ⭐ [The Definitive Guide to DAX (2nd ed.)](https://www.sqlbi.com/books/the-definitive-guide-to-dax-2nd-edition/) - Marco Russo & Alberto Ferrari. The DAX bible.
- [Analyzing Data with Power BI and Power Pivot for Excel](https://www.sqlbi.com/books/analyzing-data-with-microsoft-power-bi-and-power-pivot-for-excel/) - Russo & Ferrari. Data modeling for analysts.
- [Data Modeling with Microsoft Power BI](https://www.oreilly.com/library/view/data-modeling-with/9781098148546/) - Markus Ehrenmueller-Jensen (O'Reilly).
- [Microsoft Power BI Cookbook (3rd ed.)](https://www.packtpub.com/en-us/product/microsoft-power-bi-cookbook-9781835464663) - Greg Deckler & Brett Powell (Packt).
- [Expert Data Modeling with Power BI (2nd ed.)](https://www.oreilly.com/library/view/expert-data-modeling/9781803246246/) - Soheil Bakhshi (Packt).
- [Supercharge Power BI](https://excel.bookstore.ipgbook.com/supercharge-power-bi-products-9781615470693.php) - Matt Allington. Learn DAX step by step.
- [The Data Warehouse Toolkit](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books/data-warehouse-dw-toolkit/) - Ralph Kimball. The foundation of dimensional modeling and star schemas.
- [Storytelling with Data](https://www.storytellingwithdata.com/books) - Cole Nussbaumer Knaflic. Tool-agnostic data visualization.

## Software & Tools

### Microsoft Tools

- ⭐ [Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop) 🆓 - The authoring tool for models and reports (Windows).
- [Power BI Report Builder](https://learn.microsoft.com/power-bi/paginated-reports/report-builder-power-bi) 🆓 - Authoring tool for paginated (pixel-perfect) reports.
- [Power BI Report Server](https://www.microsoft.com/power-platform/products/power-bi/report-server) 💰 - On-premises report portal.
- [On-premises data gateway](https://learn.microsoft.com/data-integration/gateway/service-gateway-onprem) 🆓 - Connects the service to on-premises sources.
- [Power BI mobile apps](https://learn.microsoft.com/power-bi/explore-reports/mobile/mobile-apps-for-mobile-devices) 🆓 - iOS, Android and Windows apps.
- [Analyze in Excel](https://learn.microsoft.com/power-bi/collaborate-share/office-integration/service-analyze-in-excel) - Use semantic models in Excel PivotTables.
- [SQL Server Management Studio](https://learn.microsoft.com/ssms/sql-server-management-studio-ssms) 🆓 - Connect to models through the XMLA endpoint.
- [TMDL extension for VS Code](https://marketplace.visualstudio.com/items?itemName=analysis-services.TMDL) 🆓 - Syntax highlighting and IntelliSense for TMDL files.
- [Power Query SDK for VS Code](https://github.com/microsoft/vscode-powerquery-sdk) 🆓 - Build custom connectors.

### External Tools

> [External tools](https://learn.microsoft.com/power-bi/transform-model/desktop-external-tools) integrate with the External Tools ribbon in Power BI Desktop.

- ⭐ [Tabular Editor 2](https://github.com/TabularEditor/TabularEditor) 🆓 - Open-source model editor: bulk edits, C# scripts, Best Practice Analyzer.
- ⭐ [Tabular Editor 3](https://tabulareditor.com/) 💰 - The commercial successor, with a DAX editor, debugger, diagrams and more.
- ⭐ [DAX Studio](https://daxstudio.org/) 🆓 - Write, run and profile DAX queries. Includes server timings and VertiPaq Analyzer.
- ⭐ [Bravo for Power BI](https://bravo.bi/) 🆓 - SQLBI's tool to analyze model size, format DAX, create date tables and export data.
- [ALM Toolkit](https://alm-toolkit.com/) 🆓 - Compare and merge semantic models, and deploy partial changes.
- [VertiPaq Analyzer](https://www.sqlbi.com/tools/vertipaq-analyzer/) 🆓 - Analyze the memory footprint of models per table and column.
- [Measure Killer](https://measurekiller.com/) 🔀 - Find unused measures and columns, lineage and governance across reports.
- [Power BI Helper](https://powerbihelper.org/) 🔀 - Documentation, cleanup and model analysis by RADACAD.
- [Business Ops](https://github.com/MikeCarlo/BusinessOps) 🆓 - PowerBI.tips installer that bundles many external tools.
- [PBI Explorer](https://pbiexplorer.com/) 🆓 - Code-first view of PBIX/PBIP reports and diffs between versions.
- [DAX Optimizer](https://www.daxoptimizer.com/) 💰 - Automated analysis of DAX performance issues, by SQLBI and Tabular Tools.
- [Best Practice Rules](https://github.com/TabularEditor/BestPracticeRules) 🆓 - Rule sets for Tabular Editor's Best Practice Analyzer.
- [Power BI Studio for VS Code](https://github.com/gbrueckl/PowerBI-VSCode) 🆓 - Manage workspaces and run DAX from VS Code, by Gerhard Brueckl.

### Source Control, CI/CD & DevOps

- [Fabric Git integration](https://learn.microsoft.com/fabric/cicd/git-integration/intro-to-git-integration) - Connect workspaces to Azure DevOps or GitHub.
- [Deployment pipelines](https://learn.microsoft.com/fabric/cicd/deployment-pipelines/intro-to-deployment-pipelines) - Promote content from Dev to Test to Prod.
- [fabric-cicd](https://github.com/microsoft/fabric-cicd) 🆓 - Python library for code-first deployment of Fabric and Power BI items.
- [Fabric CLI](https://github.com/microsoft/fabric-cli) 🆓 - Command-line interface for Fabric and Power BI.
- [pbi-tools](https://pbi.tools/) 🆓 - Extract PBIX files to source control and build them back.
- [Fab Inspector](https://github.com/NatVanG/fab-inspector) 🆓 - Formerly PBI Inspector. Rule-based tests for report definitions and other Fabric items, locally or in CI pipelines.
- [Semantic Link Labs](https://github.com/microsoft/semantic-link-labs) 🆓 - Python library with hundreds of functions to automate models, reports and administration from Fabric notebooks.

### Administration, Monitoring & Governance

- [Fabric administration](https://learn.microsoft.com/fabric/admin/admin-overview) - Admin portal, tenant settings, capacities and workspaces.
- [Tenant settings index](https://learn.microsoft.com/fabric/admin/tenant-settings-index) - All tenant settings explained.
- [Track user activities](https://learn.microsoft.com/fabric/admin/track-user-activities) - Activity log and audit events.
- [Metadata scanning (Scanner API)](https://learn.microsoft.com/fabric/governance/metadata-scanning-overview) - Inventory all workspaces, datasets and lineage.
- [Fabric Capacity Metrics app](https://learn.microsoft.com/fabric/enterprise/metrics-app) - Monitor capacity usage and throttling.
- [Fabric Toolbox](https://github.com/microsoft/fabric-toolbox) 🆓 - Microsoft's collection of accelerators, including FUAM (Fabric Unified Admin Monitoring).
- [pbimonitor](https://github.com/RuiRomano/pbimonitor) 🆓 - Rui Romano's tenant monitoring solution based on the REST APIs.
- [Power BI Sentinel](https://www.powerbisentinel.com/) 💰 - Backups, change tracking, lineage and documentation.

### Developer, Embedding & APIs

- [Power BI REST API reference](https://learn.microsoft.com/rest/api/power-bi/) - Automate workspaces, refreshes, deployments and more.
- [Fabric REST API reference](https://learn.microsoft.com/rest/api/fabric/articles/) - APIs for all Fabric items.
- [Power BI Embedded analytics](https://learn.microsoft.com/power-bi/developer/embedded/) - Embed reports in your own applications.
- ⭐ [Power BI Embedded Analytics Playground](https://playground.powerbi.com/) 🆓 - Try out the embedding APIs live, with showcases and sample code.
- [PowerBI-JavaScript](https://github.com/microsoft/PowerBI-JavaScript) 🆓 - JavaScript client for embedding.
- [powerbi-client-react](https://github.com/microsoft/powerbi-client-react) 🆓 - React component for embedding.
- [PowerBI-Developer-Samples](https://github.com/microsoft/PowerBI-Developer-Samples) 🆓 - Sample code for embedding and APIs.
- [Power BI PowerShell cmdlets](https://learn.microsoft.com/powershell/power-bi/overview) 🆓 - MicrosoftPowerBIMgmt module for administration.
- [Semantic Link](https://learn.microsoft.com/fabric/data-science/semantic-link-overview) - Use semantic models in Python (Fabric notebooks).
- [Custom visuals development](https://learn.microsoft.com/power-bi/developer/visuals/develop-power-bi-visuals) - Build your own visual with the pbiviz tools.
- [PBIXRay](https://github.com/Hugoberry/pbixray) 🆓 - Python library to read the model, DAX and M from PBIX files.

## Custom Visuals

- [Microsoft Marketplace: Power BI visuals](https://marketplace.microsoft.com/search/products?product=power-bi-visuals) - The official marketplace for custom visuals (formerly AppSource).
- ⭐ [Deneb](https://deneb.guide/) 🆓 - Build any visual with Vega or Vega-Lite, certified by Microsoft.
- [HTML Content](https://html-content.com/) 🆓 - Render HTML from measures, by the creator of Deneb.
- [Zebra BI](https://zebrabi.com/) 💰 - IBCS-style tables and charts for financial reporting.
- [Inforiver](https://inforiver.com/) 💰 - Matrix reporting, write-back and planning.
- [ZoomCharts](https://zoomcharts.com/) 💰 - Interactive drill-down visuals.
- [OKVIZ](https://okviz.com/) 🔀 - Synoptic Panel, Smart Filter Pro, Bullet Chart and others.
- [Icon Map](https://icon-map.com/) 🔀 - Flexible maps with custom shapes and layers.
- [Python visuals](https://learn.microsoft.com/power-bi/connect-data/desktop-python-visuals) and [R visuals](https://learn.microsoft.com/power-bi/create-reports/desktop-r-visuals) - Use code for visualizations.

## Templates, Themes & Design

**Themes**

- [Report themes documentation](https://learn.microsoft.com/power-bi/create-reports/desktop-report-themes) - How JSON themes work.
- [Report theme JSON schema](https://github.com/microsoft/powerbi-desktop-samples/tree/main/Report%20Theme%20JSON%20Schema) 🆓 - Official schema for writing themes by hand.
- ⭐ [PowerBI.tips Theme Generator](https://themes.powerbi.tips/) 🔀 - Visual editor for themes.
- [BIBB Theme Generator](https://bibb.pro/apps/theme-generator/) 🔀 - Theme generator, plus UI templates on [bibb.pro](https://bibb.pro/).

**Report templates & layouts**

- [PowerBI.tips Power Designer](https://powerbi.tips/power-designer/) 🔀 - Design report layouts and backgrounds (the successor of PowerBI.tips Layouts).
- [Numerro](https://numerro.io/) 💰 - Report templates and design kits.
- [Template apps](https://learn.microsoft.com/power-bi/collaborate-share/service-template-apps-overview) - Prebuilt apps for services such as Salesforce and Dynamics.
- [Bravo date table templates](https://github.com/sql-bi/DaxDateTemplate) 🆓 - SQLBI's DAX date table template, also used by Bravo.

**Design resources**

- [IBCS standards](https://www.ibcs.com/) 🆓 - International Business Communication Standards for business reporting.
- [Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons) 🆓 - Microsoft's icon set, works well in reports.
- [Material Symbols](https://fonts.google.com/icons) 🆓 - Google icon set, downloadable as SVG.
- [ColorBrewer](https://colorbrewer2.org/) 🆓 - Colorblind-safe palettes.
- [Coolors](https://coolors.co/) 🔀 - Color palette generator.
- [Viz Palette](https://projects.susielu.com/viz-palette) 🆓 - Test palettes for accessibility.

## Demos, Samples & Datasets

**Sample reports & models**

- ⭐ [Power BI sample reports and models](https://learn.microsoft.com/power-bi/create-reports/sample-datasets) 🆓 - Official samples (Retail Analysis, Sales & Returns, Store Sales, and more).
- [powerbi-desktop-samples](https://github.com/microsoft/powerbi-desktop-samples) 🆓 - Sample PBIX files, including the ones from the monthly feature summaries.
- [Contoso Data Generator](https://github.com/sql-bi/Contoso-Data-Generator-V2) 🆓 - Generate realistic Contoso datasets of any size, by SQLBI.
- [AdventureWorks sample databases](https://learn.microsoft.com/sql/samples/adventureworks-install-configure) 🆓 - Classic sample data warehouse.
- [Fabric end-to-end tutorials](https://learn.microsoft.com/fabric/fundamentals/end-to-end-tutorials) 🆓 - Complete scenarios from ingestion to report.

**Inspiration & showcases**

- ⭐ [Data Stories Gallery](https://community.fabric.microsoft.com/t5/Data-Stories-Gallery/bd-p/DataStoriesGallery) 🆓 - Community reports for inspiration.
- [Enterprise DNA Showcase](https://enterprisedna.co/showcase) 🆓 - Example reports from challenges.
- [Embedded Playground Showcases](https://playground.powerbi.com/en-us/showcases) 🆓 - Interactive demos of embedded scenarios.

**Challenges**

- [Workout Wednesday for Power BI](https://www.workout-wednesday.com/power-bi-challenges/) 🆓 - Weekly exercises.
- [Onyx Data DataDNA](https://datadna.onyxdata.co.uk/) 🆓 - Monthly dataset challenge.
- [FP20 Analytics Challenges](https://fp20analytics.com/) 🆓 - Community challenges with feedback.
- [Makeover Monday](https://makeovermonday.co.uk/) 🆓 - Weekly dataset to visualize (any tool).

**Datasets**

- [Maven Analytics Data Playground](https://mavenanalytics.io/data-playground) 🆓 - Clean datasets for practice.
- [Kaggle Datasets](https://www.kaggle.com/datasets) 🆓 - Thousands of public datasets.
- [Our World in Data](https://ourworldindata.org/) 🆓 - Global statistics with downloads.
- [CBS Open Data](https://opendata.cbs.nl/) 🆓 🇳🇱 - Statistics Netherlands, with an OData feed that works directly in Power BI.
- [data.overheid.nl](https://data.overheid.nl/) 🆓 🇳🇱 - Dutch government open data portal.

## AI

### AI Built Into Power BI & Fabric

- ⭐ [Copilot in Power BI](https://learn.microsoft.com/power-bi/create-reports/copilot-introduction) - Generate report pages, summaries and DAX, and ask questions about your data.
- [Prepare your data for AI](https://learn.microsoft.com/power-bi/create-reports/copilot-prepare-data-ai) - AI data schemas, verified answers and AI instructions to make models Copilot-ready.
- [Copilot in DAX query view](https://learn.microsoft.com/dax/dax-copilot) - Write and explain DAX queries with Copilot.
- [Copilot in Fabric](https://learn.microsoft.com/fabric/fundamentals/copilot-fabric-overview) - Overview of Copilot across all Fabric workloads.
- [Fabric Copilot capacity](https://learn.microsoft.com/fabric/enterprise/fabric-copilot-capacity) - Licensing and capacity for Copilot.
- [Fabric data agent](https://learn.microsoft.com/fabric/data-science/concept-data-agent) - Build conversational Q&A agents on semantic models, lakehouses and warehouses.
- [Fabric IQ MCP](https://learn.microsoft.com/fabric/iq/connectors/fabric-iq-mcp) - Answer natural-language questions over governed Power BI data, for Microsoft 365 Copilot, Copilot Studio and custom agents.
- [Fabric AI functions](https://learn.microsoft.com/fabric/data-science/ai-functions/overview) - Classification, sentiment, extraction and more with one line of code.
- [Q&A](https://learn.microsoft.com/power-bi/natural-language/q-and-a-intro) - The classic natural-language visual.
- AI visuals: [Key influencers](https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-influencers), [Decomposition tree](https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-decomposition-tree), [Smart narrative](https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-smart-narrative), [Anomaly detection](https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-anomaly-detection).

### MCP Servers

> The [Model Context Protocol](https://modelcontextprotocol.io/) lets AI agents (GitHub Copilot, Claude, Cursor, and others) use tools such as Power BI.

- ⭐ [Power BI MCP servers overview](https://learn.microsoft.com/power-bi/developer/mcp/mcp-servers-overview) - Microsoft's guide to which server fits which scenario.
- ⭐ [Power BI Authoring MCP server](https://learn.microsoft.com/power-bi/developer/mcp/power-bi-authoring-mcp) 🆓 - Microsoft's server for building and changing semantic models: tables, measures, relationships, bulk refactoring, DAX validation, TMDL/PBIP. Local version (GA) and hosted version (preview).
- [microsoft/powerbi-modeling-mcp](https://github.com/microsoft/powerbi-modeling-mcp) 🆓 - GitHub repo of the local server.
- [Power BI Desktop Bridge](https://learn.microsoft.com/power-bi/developer/agentic/power-bi-desktop-bridge-overview) - Local server inside Power BI Desktop that lets external tools and agents control a running Desktop instance.
- [Microsoft Learn MCP server](https://learn.microsoft.com/training/support/mcp) 🆓 - Gives agents up-to-date Microsoft docs, including Power BI and DAX.
- [sulaiman013/powerbi-mcp](https://github.com/sulaiman013/powerbi-mcp) 🆓 - Community MCP server (Python) for Desktop and the service.
- [SemanticOps MCP](https://github.com/maxanatsko/mcp-engine-public) - Formerly MCP Engine, by Maxim Anatsko. Read, query and change models in Power BI Desktop from an AI assistant. Proprietary license.

### Agent Skills & Plugins

- ⭐ [Power BI Agentic](https://learn.microsoft.com/power-bi/developer/agentic/power-bi-agentic-overview) - Microsoft's bundle of skills and tools for developing Power BI with AI coding agents.
- [microsoft/skills-for-fabric](https://github.com/microsoft/skills-for-fabric) 🆓 - Marketplace with the `powerbi-authoring` plugin (semantic model and PBIR report skills plus the Authoring MCP server). Works with GitHub Copilot CLI, VS Code, Claude Code, Cursor and others.
- [data-goblin/power-bi-agentic-development](https://github.com/data-goblin/power-bi-agentic-development) 🆓 - Kurt Buhler's plugins for Claude Code and others: PBIP/TMDL/PBIR, Power BI Desktop, Tabular Editor, Fabric CLI and BPA rules.

### Reading on AI & Power BI

- [Agentic development of semantic models in simple terms](https://tabulareditor.com/blog/agentic-development-of-semantic-models-in-simple-terms) - Tabular Editor: the three ways agents can work with models.
- [AI agents that work with Power BI semantic model MCP servers](https://tabulareditor.com/blog/ai-agents-that-work-with-power-bi-semantic-model-mcp-servers) - Tabular Editor: possibilities, limitations and risks.
- [AI agents that work with TMDL files](https://tabulareditor.com/blog/ai-agents-that-work-with-tmdl-files) - Tabular Editor: let agents edit model metadata directly.
- [The dark side of LLMs: security risks in semantic model development](https://tabulareditor.com/blog/the-dark-side-of-llms-security-risks-in-semantic-model-development) - Tabular Editor: what to watch for.

## Community & Events

**Forums & Q&A**

- ⭐ [Fabric Community (Power BI forums)](https://community.fabric.microsoft.com/) - The official forum, with active Super Users.
- [r/PowerBI](https://www.reddit.com/r/PowerBI/) - Reddit community.
- [r/MicrosoftFabric](https://www.reddit.com/r/MicrosoftFabric/) - Reddit community, frequently visited by Microsoft product team members.
- [Stack Overflow: powerbi](https://stackoverflow.com/questions/tagged/powerbi) - Technical Q&A.
- [Microsoft MVPs](https://mvp.microsoft.com/) - Find experts by region and topic.

**Conferences**

- [FabCon](https://fabriccon.com/) - The Microsoft Fabric Community Conference (US and Europe).
- [SQLBits](https://sqlbits.com/) - Large data platform conference in the UK, with a lot of free content.
- [PASS Data Community Summit](https://passdatacommunitysummit.com/) - Data platform conference in Seattle.
- [Data Saturdays](https://datasaturdays.com/) - Free community events worldwide.

## Dutch & Belgian Community

- ⭐ [Power BI Gebruikersdagen (PBIG)](https://www.pbig.nl/) 🇳🇱 - Big three-day Power BI and Fabric event in Utrecht (Jaarbeurs), every March.
- [dataMinds](https://dataminds.be/) 🇧🇪 - Belgian data platform community, organizer of dataMinds Connect.
- [How to Power BI](https://www.youtube.com/@HowtoPowerBI) 🇳🇱 - Bas Dohmen's YouTube channel.
- [BI Gorilla](https://gorilla.bi/) and [powerquery.how](https://powerquery.how/) 🇳🇱 - Rick de Groot.
- [Kasper On BI](https://www.kasperonbi.com/) 🇳🇱 - Kasper de Jonge.
- [Data-Marc](https://data-marc.com/) 🇳🇱 - Marc Lelijveld.
- [Dutch Data Dude](https://www.dutchdatadude.com/) 🇳🇱 - Jeroen ter Heerdt.
- [SQL Kover](https://sqlkover.com/) 🇧🇪 - Koen Verbeeck on SQL Server, Power BI and Fabric.
- [CBS Open Data](https://opendata.cbs.nl/) and [data.overheid.nl](https://data.overheid.nl/) 🇳🇱 - Dutch datasets to practice with.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work. See [LICENSE](LICENSE).
