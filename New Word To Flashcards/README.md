# New Word to Flashcards Shortcut

**Link**: https://www.icloud.com/shortcuts/1368c38c576340c1b2ed8753bc3535a8

This shortcut allows you to easily add new vocabulary words to your flashcards in **Obsidian**, with built-in translation capabilities between two languages of your choice. It automates the process of adding flashcards with hints and translations directly into an Obsidian note.

> Shortcut:

![IMG_4024](https://github.com/user-attachments/assets/becb1875-414d-4a20-aa75-366964153715)

> Result:

![Screenshot 2024-10-12 at 2 20 41 PM](https://github.com/user-attachments/assets/4b0f07a6-04b4-4be0-9ab5-b0f81c1dccfe)

## Prerequisites

### Required:
1. **Obsidian**: The shortcut integrates with your Obsidian vault, so you need to have Obsidian installed.
2. **Obsidian Flashcards Plugin**: This plugin is necessary to manage and review your flashcards efficiently inside Obsidian. You can install it from Obsidian's plugin market.

For more information on Obsidian and the Flashcards plugin, visit:
- [Obsidian Official Website](https://obsidian.md)
- [Flashcards Plugin for Obsidian](https://github.com/mgmeyers/obsidian-spaced-repetition)

### Optional Alternatives:
If you don’t want to set up Obsidian or the Flashcards plugin, you can modify the shortcut to save the flashcards in other text-based apps like **Apple Notes** or **Notion**. However, the translation and spaced repetition features will need to be adjusted according to the app's capabilities.

## Setup Instructions

1. **Vault Path**: The shortcut will ask you for the path of your Obsidian vault. Make sure you know where your vault is stored on your device so you can provide the correct path.
   
2. **Flashcards Note Path**: You will also need to provide the path where the flashcards will be stored. This should be the full path within your Obsidian vault, for example, `/Flashcards/Language/` or `/Inbox/`.

3. **Set Translation Languages**: The shortcut will prompt you to set two languages for translation. During the setup, you can choose the languages you want to translate between. In the demo setup, it's configured as Japanese to Spanish, but you can modify this to any pair of languages that Google Translate supports.

## How It Works

1. The shortcut asks you for the **word** you want to translate.
2. It then translates the word from the **source language** (e.g., Japanese) to the **target language** (e.g., Spanish).
3. If the word includes hints or contextual notes in parentheses, the shortcut strips these out during the translation but preserves them in the flashcard hint.
4. The shortcut generates a flashcard in the format required by the Obsidian Flashcards plugin, saving the card in the specified Obsidian note.

## Example Use Case

- **Word**: Chao (informal)
- **Translation**: The shortcut will create a card with "Chao" in the question and "Bye" as the translation, with "informal" as a hint in the flashcard.

## Customization

- You can customize the file paths, languages, and the format of the flashcards according to your needs. The default configuration uses double colons (`::`) to separate the question and answer in the Obsidian flashcard format, but this can be changed if necessary.

![IMG_0935E46C1F6F-1](https://github.com/user-attachments/assets/e2e9ba0a-8d2a-4f6d-aa6e-89661d871014)


