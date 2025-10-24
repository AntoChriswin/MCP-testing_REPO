# Firecrawl MCP Tools

## 1. firecrawl_scrape
**Purpose**: Scrape content from a single URL with advanced options

**Best for**: Single page content extraction when you know exactly which page contains the information

**Features**: 
- Multiple format support (markdown, html, rawHtml, screenshot, links, summary, JSON extraction)
- Cache support with maxAge parameter for 500% faster scrapes
- Screenshot capabilities with custom viewport and quality settings
- PDF parsing support
- Actions support (wait, scroll, click, write, press, executeJavascript, generatePDF)

## 2. firecrawl_map
**Purpose**: Map a website to discover all indexed URLs

**Best for**: Discovering URLs on a website before deciding what to scrape; finding specific sections

**Features**: 
- Sitemap inclusion/exclusion options
- Search within mapped URLs
- Subdomain inclusion
- Query parameter handling
- URL limit controls

## 3. firecrawl_search
**Purpose**: Search the web and optionally extract content from search results

**Best for**: Finding specific information across multiple websites when you don't know which website has it

**Features**: 
- Multiple source types: web, images, news
- Search operators support (quotes, minus, site:, inurl:, intitle:, etc.)
- Optional scraping of search results
- Language and country filtering
- Location-based search

## 4. firecrawl_crawl
**Purpose**: Start a crawl job on a website and extract content from all pages

**Best for**: Extracting content from multiple related pages with comprehensive coverage

**Features**: 
- Configurable depth (maxDiscoveryDepth)
- URL limit controls
- Include/exclude path patterns
- External link handling
- Similar URL deduplication
- Webhook support for async processing
- Delay and concurrency controls

## 5. firecrawl_check_crawl_status
**Purpose**: Check the status of a crawl job

**Returns**: Status and progress of the crawl job, including results if available

**Input**: Crawl job ID

## 6. firecrawl_extract
**Purpose**: Extract structured information from web pages using LLM capabilities

**Best for**: Extracting specific structured data like prices, names, details from web pages

**Features**: 
- Custom prompt for LLM extraction
- JSON schema support for structured output
- Multiple URL processing
- Web search enhancement option
- Subdomain inclusion
- Works with both cloud AI and self-hosted LLM