# Starjin

Starjin allows you to easily create and manage giveaways in your Discord server.

## Features

-  Create giveaways with various options like prize, duration, winner count, entry methods and much more.
-  Use text commands or a future interactive interface to create giveaways.
-  Customize giveaway messages with various customizations.

## How to Use

-  Use the `/giveaway` command to create, edit, or cancel giveaways.

## Creating Giveaways

This section explains how to use the `/giveaway create` command to set up a giveaway in your server.

### Subcommands:

-  **create:** This subcommand is used to create a giveaway through text-based options.
-  **create_interactive:** This subcommand will allow creating giveaways through an interactive modal interface.

### Text-based Giveaway Creation (`/giveaway create`):

This method involves providing various options through text commands. Here's a breakdown of the available options:

**Required Options:**

-  **prize:** A clear and concise description of the prize being offered. This will be displayed in the giveaway message and should entice users to participate.

   -  **Example:** "Nitro Classic ($5)"

-  **duration:** The amount of time the giveaway will be active before a winner is chosen. Specify the duration value followed by a time unit.

   -  **Example:** "1h", "30m", "2d", "5w", "1y"

-  **winner_count:** The number of winners you want to randomly choose from the participants.

   -  **Example:** "1" (one winner), "3" (three winners)

-  **channel:** The specific text channel where the giveaway message will be posted. This channel should be accessible to users who want to enter the giveaway.

   -  **Example:** "#giveaways" (assuming you have a channel named giveaways)

**Optional Options:**

-  **reaction_emoji:** The emoji users must react with to enter the giveaway. It's recommended to use an emoji relevant to the prize or giveaway theme.

   -  **Example:** "🎉" (party popper), "<:giveaway:123456789012345678>" (custom emoji)

-  **button_label:** The text displayed on the button users click to enter the giveaway. Keep it clear and concise.

   -  **Example:** "Enter Giveaway", "Participate"

-  **button_emoji:** The emoji displayed on the entry button (optional).

   -  **Example:** "🥳" (partying face), "<:gift:123456789012345678>" (custom emoji)

-  **required_roles:** Comma-separated list of role IDs that users must have to enter the giveaway. This can be used to restrict participation to specific groups within your server.

   -  **Example:** "123456,789012"

-  **excluded_roles:** Comma-separated list of role IDs that exclude users from entering the giveaway. This can be helpful if you want to prevent certain groups from participating.

   -  **Example:** "123456,789012"

-  **bonus_entries:** The maximum number of additional entries a user can get beyond the default one. This can be used to reward users for specific actions, like having certain roles or inviting friends. Requires `bonus_roles` to be set.

   -  **Example:** "5" (users can get up to maximum of 5 bonus entries)

-  **bonus_roles:** Comma-separated list of role IDs with the corresponding number of bonus entries assigned to each role. Requires `bonus_entries` to be set.

   -  **Example:** "roleID1:3,roleID2:2" (users with roleID1 get 3 bonus entries, roleID2 gets 2)

-  **embed_custom_fields:** Comma-separated list of key-value pairs to add custom fields to the giveaway embed message. Each pair should be formatted as "key:value". To add multiple pairs, simply add a comma between each pair like this: "key:value,key1:value1". This allows you to provide additional information about the giveaway beyond the prize and duration.

   -  **Example:** `"Sponsored By:Acme Inc.", "Website:https://www.example.com"` (specifies a sponsor and website link) (only premium users can inlcude links)

-  **embed_footer:** Text displayed at the bottom of the giveaway embed message. Use this to add a short message or disclaimer.

   -  **Example:** "Good luck everyone!", "This giveaway is not sponsored by Discord."

-  **private_message_on_win:** Whether to send the winners a private message after they are chosen. This can be useful to congratulate them and provide instructions on how to claim their prize.

   -  **Example:** "true" (send private messages), "false" (don't send messages)

-  **show_options:** Whether to show details about the giveaway options (requirements, excluded roles, bonus roles, etc.) in the giveaway message.

   -  **Example:** "false" (hide options), "true" (show options) (defaults to true)

**Remember:**

-  Replace the placeholders in the examples with your specific information.
-  Double-check the role IDs and emoji codes for accuracy to avoid errors.

## Additional Information

-  This bot is under active development. More features and functionalities may be added in the future.
-  For any bugs or suggestions, feel free to [create an issue](https://github.com/Meenic/starjin/issues).
