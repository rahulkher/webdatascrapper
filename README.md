
# Twitter Scraping and Prompt Generation Tool

## Overview
This repository provides a toolset for scraping Twitter data and generating prompts using OpenAI and Hugging Face models. It includes user authentication, license verification, and customizable prompt generation.

## Features
- **Twitter Scraping:** Scrapes Twitter data based on user-provided queries.
- **Prompt Generation:** Generates search prompts using OpenAI and Hugging Face models.
- **License Verification:** Ensures valid licenses for accessing premium and standard features.
- **User Authentication:** Secure login and registration system.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Configuration
1. Create a `.env` file in the root directory and add your environment variables:
   ```sh
   TWITTER_USERNAME=your_twitter_username
   TWITTER_PASSWORD=your_twitter_password
   OPENAI_API_KEY=your_openai_api_key
   HUGGINGFACE_API_KEY=your_huggingface_api_key
   ```

## Usage
### Running the Application
1. Navigate to the project directory:
   ```sh
   cd your-repo
   ```
2. Run the main application script:
   ```sh
   python app.py
   ```

### Web Interface
1. Start the Flask application:
   ```sh
   python app_run.py
   ```
2. Open your web browser and navigate to `http://127.0.0.1:5000/`.

## File Structure
```
__pycache__
app
   __pycache__
   __init__.py
   models.py
   routes.py
instance
   site.db
scrappers
   __pycache__
   helpers
      __init__.py
      checklicense.py
      generate_license.py
   prompts.py
   scrappers.py
templates
   base.html
   index.html
   login.html
   prompt.html
   register.html
LICENSE
README.md
app.py
app_run.py
license.lic
requirements.txt
twitter_scrapper.ipynb
```

## Version Information

### Version v1.0.0
**Release Date:** [Insert Date]

- **Initial Release:** This version includes the core features such as Twitter scraping, prompt generation using OpenAI and Hugging Face, license verification, and user authentication.

**Tagging Suggestions:**
- Prefix your version names with the letter `v`. For example: `v1.0.0` or `v2.3.4`.
- For pre-release versions, add a pre-release label. For example: `v0.2.0-alpha` or `v5.9-beta.3`.

**Semantic Versioning:**
- Follow [semantic versioning](https://semver.org/) principles to ensure clear and predictable version management.

## Contributing
Contributions are welcome! Please create a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License.
