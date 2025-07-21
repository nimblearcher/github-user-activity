# GitHub User Activity CLI Tool

## Project Overview
This project provides a simple command-line interface (CLI) tool to fetch and display the recent public activity of any given GitHub user. It directly interacts with the GitHub API to retrieve event data, demonstrating basic API interaction and command-line scripting without external libraries or frameworks.

## Features
* **CLI Interface**: Runs directly from your terminal.
* **Username Argument**: Accepts a GitHub username as a command-line argument.
* **GitHub API Integration**: Fetches recent public events for the specified user using the official GitHub API.
* **Raw Output**: Displays the raw JSON response of the user's activity directly in the terminal.

## Requirements
* A Unix-like environment (e.g., Git Bash on Windows, Linux, macOS).
* `curl` command-line tool installed (usually pre-installed on most systems).

## Usage

### How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/nimblearcher/github-user-activity.git](https://github.com/nimblearcher/github-user-activity.git)
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd github-user-activity
    ```
3.  **Make the script executable (if it isn't already):**
    ```bash
    chmod +x github-activity
    ```
4.  **Run the tool:**
    Provide the GitHub username as an argument.
    ```bash
    ./github-activity <github-username>
    ```
    **Example:** To fetch activity for the GitHub user `octocat`:
    ```bash
    ./github-activity octocat
    ```
    **You can try using your own username and see the result!**

### Expected Output
The tool will output the raw JSON data representing the user's recent public activity directly to your terminal. This data includes various event types (e.g., PushEvent, CreateEvent, PullRequestEvent) and their details.

## Project URL
https://github.com/nimblearcher/github-user-activity
