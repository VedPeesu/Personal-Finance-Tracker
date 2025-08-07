# Automated Personal Finance Tracker
A personal finance and budgeting tool designed to help users manage finances, visualize spending, and automate all transaction records.


### Features
- A detailed budgeting system that allows users to input an expense under a certain category
- Ability to create new budgets and split them across different areas and to see spending in each category
- Visualization of spending with charts and graphs
- Automated monthly backups of transactions to Google Drive accounts using a Google Drive API and cron jobs.


### Installation
#### **Steps**


1. Install the required libraries by running the following:
   ```bash
   pip install pydrive google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client matplotlib
   ```


2. Clone the repository
   ```bash
   git clone https://github.com/VedPeesu/AutomatedPersonalFinanceTracker.git
   ```


3. Set up Google Drive API
   - Go to the Google Developers Console
   - Create a project or select an existing one.
   - Enable the Google Drive API for your project.
   - Create OAuth 2.0 credentials and download the credentials JSON file.
   - Rename the downloaded file to credentials.json and place it in the project directory.


4. Run the application
   ```bash
   python tracker.py
   ```
