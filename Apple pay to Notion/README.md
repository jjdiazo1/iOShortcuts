# Apple Pay to Notion

**Link**: 

This shortcut allows you to log your Apple Pay transactions directly into a Notion database. It's a seamless way to track your expenses with a quick tap.

## How It Works
- When you tap your card using Apple Pay, the transaction details are logged into a Notion database.
- The shortcut fetches your transaction data and sends it to the Notion API, which records it in a specific Notion database.

## Prerequisites

1. **Notion API Key**: You need to generate a Notion API key to allow this shortcut to send data to your Notion workspace.
2. **Database ID**: The ID of the database where the transactions will be logged.

Both of these need to be configured in the shortcut for it to work properly.

### How to Configure the Shortcut

1. Open the shortcut in the **Shortcuts** app.
2. Replace the placeholder text for `database_id` and `Authorization` with your Notion API key and the ID of your Notion database.
3. For **Authorization**, use the format: `Bearer YOUR_API_KEY` Replace `YOUR_API_KEY` with your actual Notion API key.
4. Make sure you have set up the Notion API and granted access to your database (see the next section for instructions).

For further help setting up the Notion API and getting your database ready, refer to the 


