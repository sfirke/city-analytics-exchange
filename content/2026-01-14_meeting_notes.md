+++
title = "January 2026 CAE Meeting Recap"
date = 2026-01-14
description = "Recap of Jan 2026 meeting"

[taxonomies]
categories = ["Meetings"]
tags = ["meeting_recap"]

[extra]
author = "Sam Firke"
+++

Our first meeting of 2026 was on January 14th. We had a show-and-tell meeting featuring demos of three tools/products mentioned at our November meeting.

<!-- more -->

### Logic Models
**Andy Viren, City of Philadelphia**

Andy taught us the basics of logic models, when you would apply them, and showed a case study of using one to evaluate impact of summer parks programs.

*I took a screenshot of a great slide that defined terms we throw around without thinking about, like "metrics" and "analytics" - now I need to find it.*

One takeaway for me was that this requires a good understanding of the program. One can't just drop in as an outsider and create a logic model.

### Deepnote
**Shuyan Zhan, City of Pittsburgh**

Shuyan showed off Deepnote, a data analysis and exploration workbench. I was excited that in addition to a conventional SaaS offering, there are the options to self-host and to use a free cloud tier.

There's a VSCode extension, which would make it easy for me to bolt on to my current workflow.

My notes say "Jupyter Notebook heir, but shareable, enterprise, AI."

### R {targets} package
**Eli Pousson, City of Balitmore**

Eli does some beautiful reporting with R. "Reporting" doesn't quite capture it, maybe I should say he "publishes beautiful static documents."

These are official report PDFs on the department website. Some have charts that are very computationally-intensive and it's prohibitive to naively run the pipeline from start to finish each time a small change is made.

The maps alone in one report take six minutes to generate, tying up all the RAM on the machine. {targets} keeps track of which components of the analysis & document production pipeline have changed, so that only those need to be re-run.

It's a similar idea to an orchestration platform like Airflow, but focused on the generation of static files within a repository and performing reproducible research. 