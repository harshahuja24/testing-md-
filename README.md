# AutoSlides Project Flowchart

```mermaid
graph TD
    A[Input] --> B[Text Extraction using PyMuPDF]
    B --> C[Image Extraction]
    C --> D[Text Analysis]
    D --> D1[Paragraph Analysis]
    D --> D2[Section Identification]
    D1 --> E[Summarization using NLP models]
    D2 --> E
    E --> E1[Key Phrase Extraction]
    E --> E2[Short Summary Generation]
    E1 --> F[Slide Content Generation]
    E2 --> F
    F --> F1[Content Structuring]
    F --> F2[Relevance-based Content Allocation]
    F1 --> G[Slide Design]
    F2 --> G
    G --> G1[Visual Formatting]
    G --> G2[Image Placement]
    G1 --> H[Final Presentation Slides]
    G2 --> H
