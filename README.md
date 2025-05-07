# An-AI-based-personalized-learning-assistance for enhanced learning


# NoteFusion

 This project is an AI-powered educational assistant that helps students by:
-  Converting images or screenshots into structured notes
-  Summarizing textbook content
-  Generating personalized study roadmaps in PDF format
-  Creating custom books on user-specified topics

Built with **Streamlit** and powered by **Google Gemini API**, NoteFusion streamlines learning through intelligent content processing.

---

##  Features

- **Image to Notes**: Upload an image or screenshot of handwritten or printed content and get structured notes.
- **Summarize Textbook**: Upload a textbook PDF or an image to get a concise summary using AI.
- **Generate Roadmap PDF**: Type in subjects and get a week-wise roadmap in a downloadable PDF format.
- **Create Your Own Book**: Give a book title and let the AI generate HTML-formatted content, saved as a PDF.

---

## 🛠 Installation

1. **Clone the repository**  
```bash
git clone https://github.com/Srinivasteja8763/An-AI-based-personalized-learning-assistance.git
cd NoteFusion
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Set up environment variables**  
Create a `.env` file in the root directory and add your Gemini API key:
```
GOOGLE_API_KEY="AIzaSyBa4VymN-MR5vV-lWRIcZVwRxZa8SLAVf4"
```

---

##  Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

Then open the URL provided in your terminal (usually `http://localhost:8501`) in a web browser.

---

## Dependencies

- streamlit
- google-generativeai
- beautifulsoup4
- python-dotenv
- fpdf2
- PyPDF2
- Pillow

---


- Ensure your `.env` file is not uploaded to public repositories.
- The app uses Google's `gemini-1.5-flash-latest` model for all content generation.
- PDF generation requires valid HTML — avoid using Markdown formatting.

---
