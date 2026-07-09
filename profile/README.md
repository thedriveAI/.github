<a href="https://thedrive.ai">
  <img src="https://dev.thedrive.ai/thedrive.ai" alt="The Drive AI" width="100%">
</a>

<p align="center">
  <a href="https://thedrive.ai">Website</a> &nbsp;|&nbsp;
  <a href="https://docs.thedrive.ai">Docs</a> &nbsp;|&nbsp;
  <a href="https://dev.thedrive.ai">Developer API</a> &nbsp;|&nbsp;
  <a href="https://dev.thedrive.ai/blog">Blog</a> &nbsp;|&nbsp;
  <a href="https://pypi.org/project/thedriveai/">PyPI</a> &nbsp;|&nbsp;
  <a href="https://www.npmjs.com/package/@thedriveai/sdk">npm</a>
</p>

---

## About The Drive AI

We built The Drive AI because managing files is broken. People spend hours every week renaming, sorting, and searching for documents — work that adds zero value. We believe AI should handle all of it.

**The Drive AI is an agentic workspace that manages your files for you.** It reads the content of every document — not just the filename — and automatically renames, tags, and organizes it. But it goes beyond organization: AI file agents can create, share, move, delete, transform, and analyze your documents through plain English commands. Ask it to summarize a contract, merge three PDFs, send a file for e-signature, or cross-reference an invoice against a purchase order — and it just does it.

We started with a simple idea: what if your file system understood what was inside your files, and could act on them?

That led to two products:

<table>
<tr>
<td width="50%" valign="top">

### [The Drive AI](https://thedrive.ai)

**AI-powered document workspace**

<picture>
  <img src="https://dev.thedrive.ai/thedrive.ai" alt="The Drive AI — AI-powered document workspace" width="100%">
</picture>

An AI workspace with file agents that can create, organize, search, share, transform, and analyze your documents — all through plain English. It works across PDFs, spreadsheets, images, scanned files, audio, and video.

- **File agents** — create, move, rename, merge, delete, and share files via natural language
- **Auto-organization** that reads content and learns your patterns
- **Semantic search** — ask questions across all your files, get cited answers
- **Document actions** — summarize, extract data, compare, transform
- **E-signatures** (ESIGN Act compliant) and file request links
- **Integrations** — Gmail, Outlook, Google Drive, OneDrive, Dropbox, Slack
- **Everywhere** — web, macOS, iOS, and Android

**For:** Teams in real estate, law, accounting, HR, and education who are drowning in documents.

<a href="https://thedrive.ai">Try The Drive AI &rarr;</a>

</td>
<td width="50%" valign="top">

### [Developer API](https://dev.thedrive.ai)

**File intelligence endpoints for developers**

<picture>
  <img src="https://dev.thedrive.ai/dev.thedrive.ai" alt="The Drive AI Developer API" width="100%">
</picture>

The file intelligence layer that powers our workspace — now available as public API endpoints. Extract structured data, analyze documents, cross-reference files, convert to markdown, and generate thumbnails from any file or URL.

- Extract and Analyze endpoints with schema-based output
- Cross-document analysis (reason across 2-5 files)
- 107+ file formats, websites, and URLs
- Python and TypeScript SDKs
- Async processing, batch jobs, webhooks
- 100 free credits/month

**For:** Developers building document processing into their own apps, AI agents, and RAG pipelines.

<a href="https://dev.thedrive.ai">Explore the API &rarr;</a>

</td>
</tr>
</table>

---

## Our Vision

Every business runs on documents — contracts, invoices, reports, forms, records. Today, working with these documents is still manual: open, read, re-type, rename, file away. We're building the infrastructure to make documents self-organizing and machine-readable by default.

The workspace is for teams who want to stop managing files. The API is for developers who want to build on top of that same intelligence.

---

## Getting Started

**Use the workspace:**
1. Sign up at [thedrive.ai](https://thedrive.ai)
2. Upload your files — they'll be organized automatically
3. Start searching and asking questions in plain English

**Use the developer API:**
1. Get an API key at [dev.thedrive.ai/login](https://dev.thedrive.ai/login)
2. Install the SDK: `pip install thedriveai` or `npm install @thedriveai/sdk`
3. Start extracting data from files and URLs

```python
from thedriveai import TheDriveAI

client = TheDriveAI(api_key="tda_live_...")

result = client.extract(
    file="invoice.pdf",
    schema={
        "vendor": {"type": "string", "description": "Company name"},
        "total": {"type": "number", "description": "Total amount due"},
    },
)
print(result.data)  # {"vendor": "Acme Corp", "total": 4250.00}
```

---

## Documentation

| Resource | Link |
|----------|------|
| Workspace docs | [docs.thedrive.ai](https://docs.thedrive.ai) |
| API reference | [dev.thedrive.ai/docs](https://dev.thedrive.ai/docs) |
| Blog | [dev.thedrive.ai/blog](https://dev.thedrive.ai/blog) |
| Python SDK | [pypi.org/project/thedriveai](https://pypi.org/project/thedriveai/) |
| TypeScript SDK | [npmjs.com/package/@thedriveai/sdk](https://www.npmjs.com/package/@thedriveai/sdk) |

---

## Contact

- **Support:** support@thedrive.ai
- **Website:** [thedrive.ai](https://thedrive.ai)
- **Developer API:** [dev.thedrive.ai](https://dev.thedrive.ai)
