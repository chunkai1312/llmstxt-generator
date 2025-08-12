# llms.txt Generator 🚀

Generate consolidated text files from websites for LLM training and inference. Powered by [@firecrawl_dev](https://twitter.com/firecrawl_dev) for web crawling and GPT-4-mini for text processing.

## Features
- Crawls websites and combines content into a single text file
- Generates both standard (`llms.txt`) and full (`llms-full.txt`) versions
- Web interface and API access available
- No API key required for basic usage

## Usage

### Web Interface
Visit [llmstxt.firecrawl.dev](https://llmstxt.firecrawl.dev) to generate files through the browser.

### API Endpoint
```
GET https://llmstxt.firecrawl.dev/[YOUR_URL_HERE]
```

Note: Processing may take several minutes due to crawling and LLM operations.

## Local Development

### Prerequisites
Create a `.env` file with the following variables:
```
FIRECRAWL_API_KEY=
```

### Installation
```bash
npm install
npm run dev
```
