# GitHub Automation with Multi-Agent Group Chat

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

This project demonstrates a **multi-agent group chat system** that automates GitHub operations such as creating issues and committing code. The system uses a collaborative workflow between agents to collect user input, validate parameters, and execute GitHub API requests.

---

## Features

- **Multi-Agent Collaboration**: Three agents (User Proxy, Coordinator, GitHub Expert) work together to handle user requests.
- **GitHub Operations**:
  - Create GitHub issues.
  - Commit code to a repository.
- **Error Handling**: Robust validation and error handling for GitHub API requests.
- **Termination Control**: Conversations end with a `TERMINATE` message for clarity.

---

## Try It Out in Google Colab

You can try the system directly in your browser using the Google Colab notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mrmaverick9119/learningwithGithub/blob/main/GitHub_Automation.ipynb)

---

## Installation

### Prerequisites
- Python 3.8 or higher.
- A GitHub account with a personal access token (PAT).
- OpenAI API key (for GPT-4 integration).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/mrmaverick9119/learningwithGithub.git
   cd learningwithGithub
   ```
 2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
 3. Set up environment variables:
    
    Create a .env file and add your API keys:
    ```bash
    OPENAI_API_KEY=your_openai_api_key
    GITHUB_ACCESS_TOKEN=your_github_personal_access_token
    ```
4. Run the script:
    ```bash
    python main.py
    ```

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
       
