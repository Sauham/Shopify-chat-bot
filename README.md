# Shopify Updates in Chat

This project fetches Shopify data and sends it via email using a scheduled function. The project is implemented in a Jupyter Notebook and a Python script.

## Setup

1. Clone the repository and navigate to the project directory.
2. Install the required Python packages:
    ```sh
    pip install requests google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client functions-framework schedule
    ```

3. Upload your  file to the project directory.

4. Set up your environment variables for Shopify API credentials and email recipient:
    ```sh
    export SHOPIFY_API_KEY="your_shopify_api_key"
    export SHOPIFY_API_PASSWORD="your_shopify_api_password"
    export SHOPIFY_STORE="your_shopify_store"
    export EMAIL_RECIPIENT="recipient_email"
    ```

## Usage

1. Run the Jupyter Notebook  or the Python script .

2. The function  will fetch Shopify orders and send a report via email.

3. The report will be sent every day at 9 AM.

## Files

- : Jupyter Notebook containing the code to fetch Shopify data and send it via email.
- : Python script containing the same functionality as the Jupyter Notebook.
- : Service account JSON file for Google API authentication.
- : This README file.

## License

This project is licensed under the MIT License.