## Getting Started

### Prerequisites

Make sure you have Python installed on your system. It's recommended to use a virtual environment.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis.git
   cd sentiment-analysis

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

### Running the project

1. Start the web server:
   ```bash
   python server.py

3. Open your web browser and go to http://localhost:5000 to use the sentiment analysis tool.

### Usage
1. Enter text into the web application to see the sentiment classification.
2. The model will classify the input as positive, negative, or neutral.

### Deployment
To deploy the project, you can use the provided deploy.sh script. Make sure to modify the script according to your server's configuration.
