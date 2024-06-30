

# ATS Scan Tool

Welcome to the ATS Scan Tool! This project leverages cutting-edge technology to help job seekers optimize their resumes to better match job descriptions and improve their chances of passing through Applicant Tracking Systems (ATS).

## Features

- **Resume Analysis:** Upload your resume and a job description to receive a detailed analysis.
- **ATS Score:** Get a score indicating how well your resume matches the job description.
- **Strengths & Weaknesses Report:** Identify strong points and areas of improvement in your resume.
- **User-Friendly Interface:** Easy-to-use interface built with Streamlit.
- **Detailed Explanation:** Understand the reasoning behind your score and how you can improve it.

## Getting Started

### Prerequisites

- **Python 3.8+**: Ensure Python is installed on your system.
- **Streamlit**: For the front-end user interface.
- **Google Gemini Pro**: For advanced natural language processing capabilities.


### Usage

1. **Upload Resume & Job Description:**
   - Use the file upload widgets to upload your resume and the job description file.

2. **View Results:**
   - After processing, view the ATS score and detailed feedback on how your resume aligns with the job description.

3. **Improve Your Resume:**
   - Use the provided suggestions to enhance your resume and increase your ATS score.

## How It Works

### Front-End

- **Streamlit**: The entire user interface is built using Streamlit, providing a fast and interactive way to create web apps in Python.

### Back-End

- **Python**: Handles the core logic for parsing and analyzing resumes and job descriptions.
- **Google Gemini Pro**: Utilized for its advanced natural language understanding to compare the resume with the job description and extract key insights.

### Analysis Process

1. **Text Extraction**: Extracts text from the uploaded documents using Google Gemini Pro.
2. **Keyword Matching**: Utilizes NLP to compare keywords and phrases in the resume with those in the job description.
3. **Scoring**: Calculates an ATS score based on the relevance and frequency of key terms.
4. **Feedback Generation**: Provides insights into strengths and areas for improvement.

## Roadmap

- [ ] **Enhance Keyword Matching**: Improve the NLP algorithms for better accuracy using Google Gemini Pro.
- [ ] **Add Support for Multiple Languages**: Expand the tool to support resumes and job descriptions in various languages.
- [ ] **Integrate with Job Platforms**: Allow users to pull job descriptions directly from job listing websites.
- [ ] **Advanced Analytics**: Incorporate more sophisticated metrics and visualizations.

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to get involved.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Google Gemini Pro**: For its powerful language processing capabilities.
- **Streamlit**: For the user-friendly interface framework.
- **OpenAI**: For providing the language model assistance.

