<h1>SDGs Extractor</h1>
<p>
  <strong>SDGs Indicator Early Detection System</strong><br>
  An intelligent web-based system that identifies and classifies research publications by their relevance to the United Nations Sustainable Development Goals (SDGs).Built using <b>FastAPI</b>, <b>MySQL</b>, <b>PyMuPDF</b>, and <b>Sentence-BERT</b> for semantic text analysis.
</p>

<h2> Features </h2>
1. PDF Extraction — Automatically extracts Title, Abstract, and Keywords using PyMuPDF.
2. Rule-Based Matching — Detects SDG indicators with curated inclusion/exclusion patterns.
3. Semantic Similarity — Computes document-to-indicator similarity using Sentence-BERT embeddings.
4. Top-3 SDG Detection — Displays the top three most relevant SDGs with similarity scores.
5. Explainable Output — Highlights missing and matched keywords, inclusion scopes, and confidence levels.
6 Web Interface — FastAPI backend + modern, responsive frontend for seamless user interaction.

<h3> Homepage </h3>
Landing page introducing SDGs and the system overview.
<img width="1584" height="865" alt="image" src="https://github.com/user-attachments/assets/edbab743-6c66-4325-a956-51c7cdda0fe4" />

<h3> Login Page </h3>
Secure login interface integrated with UNAIR branding.
<img width="1583" height="859" alt="image" src="https://github.com/user-attachments/assets/4ac77ca0-43b5-4873-8a09-f108bca432e3" />

<h3> User Guide Modal</h3>
Step-by-step instructions before detection begins.
<img width="1602" height="846" alt="image" src="https://github.com/user-attachments/assets/538704cd-e565-4812-b61f-3113e705933a" />

<h3>Detection Result </h3>
Top-3 SDG detection results with inclusion rules and explanations.
<img width="1577" height="848" alt="image" src="https://github.com/user-attachments/assets/67f44549-321d-4cb5-bb5a-f63e41121701" />
