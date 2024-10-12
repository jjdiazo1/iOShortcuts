# Create Task in Notion

**Link**: https://www.icloud.com/shortcuts/23724c68e77a4162977c8a5c86d1b420

This shortcut allows you to create a new task directly in a Notion database using the template provided. It simplifies task management by integrating with the Notion API and automatically logging tasks into the specified database.

## How It Works

- The shortcut will prompt you for a task name and log it into a Notion database as a new task.
- It connects to the Notion API and sends the task data to the database defined by your **Database ID**.
- You can modify the task's class directly inside the shortcut to categorize it properly.

## Prerequisites

1. **Notion API Key**: You need to generate a Notion API key to allow this shortcut to send data to your Notion workspace.
2. **Database ID**: The ID of the database where the tasks will be logged.

[Help/How to set up notion API/README.md](https://github.com/jjdiazo1/iOShortcuts/tree/33d7ac06377a56fc4c6d9c18cf0ee99ee1dd6bb7/_Help/How%20to%20set%20up%20notion%20API)

## Setup Instructions

### Before Installing the Shortcut:

1. **Install the Database Template**: First duplicate the template via
     - [Task Database Template](https://lyrical-surprise-739.notion.site/11d07d2edf358001b565fceb52871546?v=11d07d2edf358110a280000cd7b1c2c2&pvs=4) 
2. **Get Your API Key and Database ID**:
   - Follow the instructions in the [How to Set Up Notion API Guide](https://developers.notion.com/reference/intro) to generate your API key and notion database ID.

### Installing the Shortcut:

1. Download the shortcut via the iCloud link provided.
2. Open the shortcut in the **Shortcuts** app.
3. During the setup, you will be asked to input:
   - Your **Notion API Key**.
   - The **Database ID** of your Notion database where the tasks will be logged.
4. Modify the **class** for your tasks manually by editing the shortcut. You can see the list of classes that need to be defined, as shown in the image below:

![IMG_2643ABBDC1A6-1](https://github.com/user-attachments/assets/7fe507da-686e-413f-b0e8-556758ffa3e7)

To add or edit the class names, you need to manually enter your classes in the list as shown in the screenshot.

## Important Notes

- Once you have completed the setup, the shortcut will automatically prompt you to add new tasks to your Notion database, categorized by class.
- The **class** selection is the only part that you need to configure manually inside the shortcut. Everything else, such as API Key and Database ID, will be handled during the installation.

## Automation

Make sure to configure this shortcut as an automation, so that you can trigger task creation seamlessly.

---

For more details on setting up automations, check the following:
[../Help/How to set up a transaction automation](https://github.com/jjdiazo1/iOShortcuts/tree/33d7ac06377a56fc4c6d9c18cf0ee99ee1dd6bb7/_Help/How%20to%20set%20up%20a%20transaction%20automation)

