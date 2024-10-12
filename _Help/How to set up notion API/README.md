# How to Set Up Notion API for Linking a Database

This guide will walk you through how to set up Notion's API, generate an API key, and link a database for use in automations like the **Apple Pay to Notion** shortcut. If you feel stuck search for a YouTube video explaining this, there are tons.

## Step 1: Create an Integration in Notion

1. Go to the [Notion Developers Page](https://www.notion.so/my-integrations).
2. Click **New Integration**.
3. Give your integration a name, such as "Apple Pay Integration."
4. Select the workspace where you want this integration to have access.
5. Copy the **API Key** from the integration page.

### Step 2: Obtain Your Database ID

1. Open the database where you want to log your Apple Pay transactions.
2. In the database view, click the **Share** button in the top right corner.
3. Choose **Copy Link**.
4. The database ID is the part of the link between the `https://www.notion.so/` and the `?v=` parameters. For example:

> https://www.notion.so/yourworkspace/1234567890abcdef1234567890abcdef?v=123abc456

Here, `1234567890abcdef1234567890abcdef` is your **Database ID**.

### Step 3: Add the Database to Your Integration

1. Go to your Notion database.
2. Click on the **Share** button at the top right of the database.
3. Search for your integration name (e.g., "Apple Pay Integration") and invite it to the database.
4. This grants the integration permission to access and update the data in your database.

That's it! Now your shortcut is ready to be set up to send the data to a notion database.

---

## Useful Links

- [Notion API Documentation](https://developers.notion.com)
