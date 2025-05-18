# Lecture 10: Semantic Web and RDF Quiz

This project is an interactive quiz web page for Lecture 10 of a university course on Semantic Web and RDF, created by **Eng: XE Ahmed Refat – EELU Student Sohag branch**. The quiz tests understanding of key concepts such as the Semantic Web, RDF triples, RDF formats (N-Triples, Turtle, RDF/XML, JSON-LD), Ontologies, OWL, SPARQL, and Linked Data, based on the lecture content. It features a responsive design, engaging animations, and bilingual support (English questions with Egyptian Arabic explanations).

## Features

- **35 Questions**:
  - 20 Multiple-Choice Questions (MCQs) with 4 options each, covering major topics from the lecture.
  - 15 True/False questions to test foundational knowledge.
  - Questions have varying difficulty levels (Easy, Medium, Hard).
  - Correct answers are evenly distributed (5 A, 5 B, 5 C, 5 D for MCQs; 8 True, 7 False for True/False) to ensure fairness and challenge.
- **Bilingual Support**:
  - Questions and options in English (LTR).
  - Explanations in Egyptian Arabic (RTL) with technical terms in English for clarity.
- **Responsive Design**:
  - Optimized for phones (≤480px), tablets (≤768px), laptops, and desktops using CSS media queries.
  - Clean layout with gradient backgrounds, rounded corners, and box shadows.
- **Interactive Elements**:
  - Progress bar showing quiz completion percentage.
  - Fade-in animation for questions and bounce effect on the submit button.
  - Feedback system: Green for correct answers, red for incorrect, with detailed explanations.
  - Final score page with percentage and motivational feedback in Egyptian Arabic (e.g., "ممتاز! عملت شغل عالي جداً").
- **Dark Mode**:
  - Toggle button to switch between light and dark themes for better accessibility.
- **Lightweight**:
  - Single HTML file (`quiz_lecture10.html`) with inline CSS and vanilla JavaScript, no external dependencies.
- **Robust Handling**:
  - Special characters (e.g., `<rdf:RDF>`) are escaped to prevent rendering issues.
  - Error handling for unsubmitted answers with a warning message.

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge, Safari).
- Optional: A local server (e.g., VS Code Live Server) or hosting platform (e.g., GitHub Pages, Netlify) for deployment.

## Installation

1. **Clone or Download the Repository**:

   ```bash
   git clone https://github.com/Xeahmed/Semantic-Web-RDF-lecture10-quiz.git
   ```

   Alternatively, download the ZIP file and extract it.

2. **Navigate to the Project Folder**:

   ```bash
   cd lecture10-quiz
   ```

3. **Open the Quiz**:

   - Double-click `quiz_lecture10.html` to open it in your browser (works offline).
   - For a better experience, use a local server:

     ```bash
     npx live-server
     ```

     Or open via VS Code’s Live Server extension.

## Deployment

To host the quiz online:

1. **GitHub Pages**:
   - Push the repository to GitHub.
   - Go to the repository settings, enable GitHub Pages, and select the `main` branch.
   - Access the quiz at `https://Xeahmed.github.io/Semantic-Web-RDF-lecture10-quiz`.

2. **Netlify**:
   - Upload the folder to Netlify or link the GitHub repository.
   - Deploy and access the quiz via the provided URL.

## Usage

1. Open `quiz_lecture10.html` in a browser.
2. Start the quiz:
   - Questions are displayed one at a time with a progress bar.
   - Select an answer (radio button) and click **Submit**.
   - View feedback (correct or incorrect) with an explanation in Egyptian Arabic.
   - Click **Next** to proceed to the next question.
3. Toggle **Dark Mode** for a different visual experience.
4. At the end, view your final score, percentage, and feedback based on performance.

## File Structure

```
lecture10-quiz/
├── quiz_lecture10.html  # Main quiz page with inline CSS and JavaScript
├── README.md            # Project documentation
└── LICENSE              # MIT License file
```

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code, provided you include the license and credit the original author. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a description of your changes.

Please ensure your changes align with the project’s goals (e.g., maintaining responsiveness, bilingual support, and lightweight design).

## Acknowledgments

- **Eng: XE Ahmed Refat**: Creator and designer of the quiz, EELU Student Sohag branch.
- Egyptian E-Learning University (EELU) for the educational content.
- Inspired by Semantic Web and RDF concepts from Lecture 10.

## Contact

For questions, suggestions, or issues, contact Eng: XE Ahmed Refat via:

- Email: [your-email@example.com] (replace with your email)
- GitHub: [your-username] (replace with your GitHub profile)

© 2025 Eng: XE Ahmed Refat – EELU Sohag
