### Introduction

A Slack bot that is built with Flask, a Python web framework, which helps you manage your daily tasks directly within your Slack workspace. The bot integrates with Slack using the Slack API and provides various functionalities to streamline task management and enhance productivity. Hope this will make your workday more active and positive.

### Features
- Task Creation: Easily create tasks by using slash commands or direct messages to the bot. Specify the task details such as title, due date, priority, and assignees.
- Task Listing: View a list of your tasks with important details like status, due date, and assignees. Sort and filter tasks based on different criteria to stay organized.
- Task Updates: Update task details, such as changing the due date, marking tasks as complete, or assigning tasks to different team members.
- Reminders: Receive reminders for upcoming task deadlines, ensuring you never miss an important deadline again.
- Notifications: Get notified about task assignments, updates, and mentions, allowing for seamless communication and collaboration.

### Installation and Setup
- Clone the repository:
`git clone https://github.com/quangnguyen3499/slack-reminder-bot.git`

- Install the required dependencies:
`pip install -r requirements.txt`

- Set up a Slack app and obtain the necessary API credentials. Refer to the Slack API documentation for detailed instructions.

- Create a .env file that contains your not configuration environment with an example from .env.example file.

- Distribute your bot by sharing your app URL or publishing it on Slack App Directory.

- Set up the necessary Slack app permissions and slash commands according to your desired functionality. Make sure to enable event subscriptions to receive events from Slack.

- Install the Slack app to your workspace and authorize it with the required permissions.

- Start using the bot in your Slack workspace by interacting with it using slash commands or through direct messages.

### Usage
Once the bot is set up and installed in your Slack workspace, you can start managing your daily tasks effortlessly. Here are some example commands you can use:

- /create-task: Create a new task and specify the task details such as title, due date, priority, and assignees.
- /list-tasks: View a list of your tasks with important details like status, due date, and assignees.
- /update-task: Update task details such as changing the due date, marking tasks as complete, or assigning tasks to different team members.
- /remind-me: Set reminders for upcoming task deadlines.

For a complete list of available commands and their usage, refer to the bot's documentation or type /help to get a list of supported commands directly within Slack.

### Contributing
- Contributions to this project are welcome! If you find any issues, have suggestions, or would like to add new features, feel free to submit a pull request.

Please make sure to follow the contribution guidelines outlined in the CONTRIBUTING.md file.

Feel free to customize this README.md file based on your specific project requirements and provide more detailed instructions if necessary.
