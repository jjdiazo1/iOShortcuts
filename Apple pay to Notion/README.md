# Apple Pay to Notion

**Link**: https://www.icloud.com/shortcuts/e7f278a62d7145ff8e28feab22f86841
<img width="886" alt="Screenshot 2024-10-12 at 1 30 01 PM" src="https://github.com/user-attachments/assets/ffca6675-f426-46fc-9106-24b9aaf8b3b8">

This shortcut allows you to log your Apple Pay transactions directly into a Notion database. It's a seamless way to track your expenses with a quick tap.

## How It Works
- When you tap your card using Apple Pay, the transaction details are logged into a Notion database.
- The shortcut fetches your transaction data and sends it to the Notion API, which records it in a specific Notion database.

## Prerequisites

1. **Notion API Key**: You need to generate a Notion API key to allow this shortcut to send data to your Notion workspace.
2. **Database ID**: The ID of the database where the transactions will be logged.

[Help/How to set up notion API/README.md](https://github.com/jjdiazo1/iOShortcuts/tree/33d7ac06377a56fc4c6d9c18cf0ee99ee1dd6bb7/_Help/How%20to%20set%20up%20notion%20API)

### How to Configure the Shortcut

1. Clone the [expenses template](https://lyrical-surprise-739.notion.site/11d07d2edf3580eebce6f2acf458591c?v=11d07d2edf358183899a000c41f19b61&pvs=4) or modify the text in the shortcut to match the fields of your own database, refer to the [Notion API documentation](https://developers.notion.com/reference/intro)
2. Download the shortcut via the iCloud link given.
3. Open the shortcut in the **Shortcuts** app.
4. Replace the variables in the 5th and 6th line of the shortcut with the Api Key and the Database Id respectively

![IMG_0F2ABDD3D1BF-1](https://github.com/user-attachments/assets/e2e02ee2-ed67-4792-83a9-8e7797cabb2f)

6. Make sure you have set up the shortcut as an automation.

Refer to the following 
[../Help/How to set up a transaction automation](https://github.com/jjdiazo1/iOShortcuts/tree/33d7ac06377a56fc4c6d9c18cf0ee99ee1dd6bb7/_Help/How%20to%20set%20up%20a%20transaction%20automation)


