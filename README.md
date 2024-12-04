# ResearchBuilder 📚

A powerful desktop application that leverages Google's Gemini AI to automatically generate structured academic research papers.

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![CustomTkinter](https://img.shields.io/badge/CustomTkinter-5.2.0-green.svg)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-1.5-orange.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Features

- **Automated Paper Generation**: Generate complete research papers with all standard academic sections
- **Structured Output**: Creates papers with Abstract, Introduction, Methodology, Results, Discussion, and Conclusion
- **Context-Aware**: Each section is generated with awareness of previous sections for coherent flow
- **Citation Management**: Automatically extracts and manages citations across sections
- **Flexible Export**: Save output as both Word (.docx) and Markdown (.md) formats
- **Progress Tracking**: Real-time progress bars for each section generation
- **User-Friendly Interface**: Clean and modern UI built with CustomTkinter

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- Google Gemini API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Chungus1310/ResearchBuilder.git
cd ResearchBuilder
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python main.py
```

## 📝 Usage

1. Launch the application
2. Enter your Google Gemini API key
3. Fill in the required fields:
   - Research Topic
   - Methodology
   - Key Results
4. (Optional) Check "Save as Markdown" for additional .md output
5. Click "Generate Paper" and monitor progress
6. Find your generated paper in the application directory

## 🛠️ Technical Details

### Core Components

- **CustomTkinter**: Modern GUI framework for a clean interface
- **Google Generative AI**: Leverages Gemini 1.5 Flash for content generation
- **python-docx**: Handles Word document generation
- **asyncio**: Manages asynchronous paper generation
- **threading**: Ensures responsive UI during generation

### Key Features Implementation

- **Context Building**: Maintains coherence across sections using previous content
- **Citation Management**: Automatically extracts and tracks citations
- **Progress Monitoring**: Real-time updates for each section
- **Error Handling**: Comprehensive error catching and user feedback
- **Multi-format Export**: Supports both .docx and .md output formats

## 🔧 Configuration

The application uses the following default configurations:

- Model: `gemini-1.5-flash`
- Temperature: 0.001 (for consistent output)
- Maximum Output Tokens: 8192
- Optimized for academic writing style

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Google Generative AI team for the Gemini API
- CustomTkinter for the modern UI framework
- The academic community for input on paper structure

## ⚠️ Disclaimer

This tool is designed to assist in research paper writing and should not be used to generate papers for academic submission without proper review and modification. Always ensure compliance with academic integrity policies.

## 📞 Contact

GitHub: [@Chungus1310](https://github.com/Chungus1310)

---

Made with ❤️ by Chun
