# Job Application Email Processor

The Job Application Email Processor is a Python tool designed to parse and process job-related emails from mailbox files (`.mbox`). It extracts relevant information and uses a chatbot powered by OpenAI's GPT-4 to determine the state of job applications, such as interviews or offers, and exports the data to a CSV file for easy review and analysis.

## Features

- **Email Parsing**: Efficiently processes `.mbox` files to extract email content.
- **Job Application Detection**: Utilizes keyword matching to identify emails related to job applications.
- **GPT-4 Integration**: Leverages the power of OpenAI's GPT-4 to interpret the content of emails and provide structured data.
- **Data Export**: Allows for the easy export of processed email data to a CSV file.

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed:

- Python 3.8 or higher
- `pip` for installing Python packages

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/job-application-email-processor.git
   
2. Install the required Python packages:

    pip install -r requirements.txt
    
How it Works

Process Emails: The EmailMessage class in utils.py is responsible for parsing the .mbox file and extracting email content after cleaning it up and checking for job application-related keywords.

Chatbot Interaction: The ChatGPT class in chatbot.py uses OpenAI's GPT-4 to further process the content and classify the state of the job application.

Export to CSV: The main.py script orchestrates the process and exports the results to a CSV file.

Usage
Run the script with the following command:

python main.py --path path_to_your_email_file.mbox --output output_filename.csv
Replace path_to_your_email_file.mbox with the path to your mbox file and output_filename.csv with your desired output file name.

Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - @your_twitter

Project Link: https://github.com/your-username/job-application-email-processor


Remember to replace placeholders like `your-username`, `your_twitter`, and any other specific details with your actual information. You may also want to add a `LICENSE` file to your repository if you haven't already.
