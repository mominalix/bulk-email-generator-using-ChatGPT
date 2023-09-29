# Bulk Sales Email Generator

This Python script uses the OpenAI API to generate bulk sales emails customized based on clients' use cases. It extracts client information from a CSV file, scrapes website data, and uses the OpenAI API to create personalized emails for each client. The results are saved to a CSV file.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Required Python packages (install via `pip install package_name`):
  - `csv`
  - `requests`
  - `beautifulsoup4`
  - `openai`

## Getting Started

1. Clone this repository or download the provided Python script (`bulk_sales_email_generator.py`) to your local machine.

2. Obtain an OpenAI API key:
   - Visit the [OpenAI website](https://beta.openai.com/signup/) to sign up for an account if you don't have one.
   - Once you have an account, generate an API key.

3. Replace `YOUR_API_KEY` in the script with your actual OpenAI API key.

4. Prepare the client data:
   - Create a CSV file named `client_data.csv` with two columns: "Name" and "Email Address." Add your client data to this file.

## Running the Script

To run the script, open a terminal or command prompt, navigate to the directory containing the script, and execute the following command:

```bash
python bulk_sales_email_generator.py
```

The script will process the client data, generate customized emails using the OpenAI API, and save the results to a CSV file named `customized_emails.csv`.

## Script Functionality

1. The script reads client data (name and email address) from `client_data.csv`.

2. It scrapes website data from the client's email address (assumes that the website URL can be derived from the email address). You may need to adjust this logic if necessary.

3. The script uses the OpenAI API to generate customized emails based on a predefined prompt. The prompt includes client-specific information, sender information, and instructions.

4. The generated customized emails are saved to `customized_emails.csv` with three columns: "Name," "Email Address," and "Customized Email."

## Customizing the Email Template

You can customize the email template by modifying the `generate_customized_email` function in the script. Adjust the `prompt` variable to include the specific content and structure you want in the emails.

## Output

The script will generate customized emails for each client and save them in the `customized_emails.csv` file. You can use this CSV file for your email marketing campaigns.

That's it! You've successfully generated bulk sales emails customized for your clients using the OpenAI API.

For any questions or issues, please feel free to reach out through [Email](mailto:mominalichannar@gmail.com) or visit my profile on [LinkedIn](https://www.linkedin.com/in/mominalix)


