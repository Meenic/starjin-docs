## Starjin Giveaway Options

This file lists all options available for creating and customizing giveaways using the Starjin bot.

**Required Options:**

| Option        | Description                                                  | Example               |
|----------------|------------------------------------------------------------|------------------------|
| prize          | A clear and concise description of the prize being offered.   | "Nitro Classic ($5)"    |
| duration       | The amount of time the giveaway will be active before a winner is chosen. | "1h", "30m", "2d", "5w", "1y" |
| winner_count   | The number of winners you want to randomly choose from the participants. | "1" (one winner), "3" (three winners) |
| channel       | The specific text channel where the giveaway message will be posted. | "#giveaways"          |

**Optional Options:**

| Option        | Description                                                  | Example                                 |
|----------------|------------------------------------------------------------|------------------------------------------|
| reaction_emoji | The emoji users must react with to enter the giveaway.          | "🎉", "<:giveaway:123456789012345678>"    |
| button_label   | The text displayed on the button users click to enter the giveaway. | "Enter Giveaway", "Participate"          |
| button_emoji   | The emoji displayed on the entry button (optional).             | "🥳", "<:gift:123456789012345678>"        |
| required_roles | Comma-separated list of role IDs that users must have to enter the giveaway. | "123456,789012"                         |
| excluded_roles | Comma-separated list of role IDs that exclude users from entering the giveaway. | "123456,789012"                         |
| bonus_entries  | The maximum number of additional entries a user can get beyond the default one. | "5"                                    |
| bonus_roles    | Comma-separated list of role IDs with the corresponding number of bonus entries assigned to each role. | "roleID1:3,roleID2:2"                     |
| embed_custom_fields | Comma-separated list of key-value pairs to add custom fields to the giveaway embed message. | "Sponsored By:Acme Inc., Website:[https://www.example.com](https://www.example.com)" (premium only) |
| embed_footer   | Text displayed at the bottom of the giveaway embed message.        | "Good luck everyone!", "This giveaway is not sponsored by Discord." |
| private_message_on_win | Whether to send the winners a private message after they are chosen. | "true" (send messages), "false" (don't send messages) |
| show_options    | Whether to show details about the giveaway options (requirements, excluded roles, bonus roles, etc.) in the giveaway message. | "false" (hide options), "true" (show options) |

**Note:**

* This file only contains options and their descriptions. Refer to the main documentation for detailed explanations and usage instructions.
