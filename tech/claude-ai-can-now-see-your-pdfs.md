# Claude AI can now see your PDFs

**Author:** Katie Hignett
**Date:** November 4, 2024
**Source:** https://www.indiehackers.com/post/EwkQ0zXKNT4mhodom3mA

---

Anthropic recently upgraded Claude's capabilities to process PDFs visually rather than extracting only text. Previously, the system converted PDFs to text for analysis, missing graphic elements like tables and charts. Now, the model receives both text and visual components, enabling analysis of financial reports, charts, and legal documents.

Users can drag-and-drop PDFs into Claude's web interface after enabling Visual PDFs in feature preview. Developers can utilize the API with the "anthropic-beta: pdfs-2024-09-25" header for the latest 3.5 Sonnet model. The feature supports documents up to 32MB with maximum 100-page size and works with prompt caching and batch processing.

Competitors like ChatGPT and Google's Pinpoint service offer similar functionality. Some indie developers express concern that integrated AI capabilities threaten standalone PDF-focused startups, requiring them to differentiate through specialized features.

**Key Lessons:**
- Indie businesses providing specialized services must develop comprehensive offerings to compete with major AI firms
- API accessibility reduces barriers for developers to integrate advanced capabilities

**Tech Stack Mentioned:**
- Claude AI model (3.5 Sonnet)
- Anthropic API
- Amazon Bedrock
- Google Vertex AI
- ChatGPT
- Tabula (OCR software)
