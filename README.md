# Chat-Data-Summarization-and-Extraction
**Task 1: Chat Summarization:**
- Implements conversation history management.
- Supports abstractive and extractive summarization.
- Includes multiple test cases with varying conversation lengths.
- Abstractive summary output example:
```
------------------------------------------------------------
ABSTRACTIVE SUMMARY: The user asked for help with Python installation. The assistant suggested downloading the installer from python.org and running it on Windows. The user then asked which version to choose, and the assistant recommended the latest stable version, usually 3.x.
------------------------------------------------------------
```

**Task 2: Chat Information Extraction:**
- Defines JSON schema for structured outputs.
- Uses function calling for tool-based extraction.
- Validates extracted data against the schema.
- Runs on sample chat scenarios (complete, partial, varied formatting).
- Structured json output example:
```
{
  "name": "Alex Thompson",
  "email": "alex@example.com",
  "phone": "555-987-6543",
  "age": 35,
  "location": "Boston, MA"

}
```

**Requirements:**
- Python 3.8+
- OpenAI API (or equivalent LLM API)
- Libraries: json, typing, requests

**Setup API Key:**\
Get your API key from [GROQAI](https://console.groq.com/keys) and Insert it in the placeholder.
```
GROQ_API_KEY = "insert_API_key"
```

