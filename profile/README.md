# DatLab

Small public-data tools on Apify Store. Mostly the boring ingest jobs nobody wants to write twice.

- [Website to Markdown Crawler](https://apify.com/datlab/site-to-markdown-crawler): crawl a docs site into clean Markdown for RAG. HTTP first, headless browser only when a page is a JS shell. $0.10 per 1,000 HTTP pages.
- [Web Page to Markdown](https://apify.com/datlab/web-page-to-markdown): same thing for a plain list of URLs.
- [Sitemap Extractor & Change Monitor](https://apify.com/datlab/sitemap-change-monitor): pull every URL from a sitemap and get new, removed and updated URLs on each run.
- [Bulk Website Screenshot](https://apify.com/datlab/bulk-website-screenshot): full page or mobile screenshots of a URL list, PNG, JPEG or PDF.
- [ATS Job Listings](https://apify.com/datlab/ats-job-listings): public job posts from Personio, Teamtailor, Workable and Recruitee boards.
- [SAM.gov Contract Opportunities](https://apify.com/datlab/sam-gov-contract-opportunities): US federal opportunities from the official daily extract, no API key needed.

Pricing is pay per result, and failed or robots-blocked pages aren't billed. We respect robots.txt and don't touch logins, paywalls or captchas.

Walkthrough with JS and Python code: [docs site to Markdown for RAG on dev.to](https://dev.to/datlab/turning-a-docs-site-into-clean-markdown-for-rag-for-about-10-cents-per-1000-pages-1nfp)

Using an MCP client? You can pin an actor on Apify's hosted server: `https://mcp.apify.com/?tools=fetch-actor-details,datlab/site-to-markdown-crawler`

Found a page that converts badly? Open an issue here with the public URL.
