# Flask HTOP Application

This is a simple Flask application that displays system information and top output on a web page (For Online Test Submission).

## Features

- Displays user's full name
- Shows system username
- Provides server time in IST (Indian Standard Time)
- Displays output similar to the Linux 'top' command

## Requirements

- Python 3.x
- Flask
- pytz

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required packages:
   ```
   pip install flask pytz
   ```

## Running the Application

1. In the root directory of the project, run:
   ```
   python app.py
   ```

2. The application will start and be available at `http://localhost:5000/htop`

## Accessing the Application in GitHub Codespaces

If you're running this application in a GitHub Codespace:

1. Make sure the application is running.
2. Go to the "Ports" tab in the Codespace.
3. Find port 5000 and make it public.
4. Use the provided URL to access the application, adding `/htop` to the end.

## Repository Structure

- `app.py`: The main Flask application file
- `README.md`: This file, containing project information and instructions
