# MCQ Generator

This project is a web application that generates multiple-choice questions (MCQs) from uploaded text documents using the DeepSeek API.

## Features
- Upload PDF, DOCX, or TXT files
- Extract text from uploaded files
- Generate MCQs using the DeepSeek API
- Download generated MCQs as TXT or PDF files

## Setup

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd MCQ Generator
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file and add your DeepSeek API key:
   ```
   DEEPSEEK_API_KEY=your_api_key_here
   ```

## Usage
1. Run the application:
   ```bash
   python app.py
   ```
2. Open your web browser and go to `http://localhost:5000`
3. Upload a file and specify the number of MCQs to generate
4. Download the generated MCQs in TXT or PDF format

## Project Structure
- `app.py`: Main application file
- `templates/`: HTML templates for the web interface
- `uploads/`: Directory for uploaded files
- `results/`: Directory for generated MCQ files

## License
This project is licensed under the MIT License.
        
