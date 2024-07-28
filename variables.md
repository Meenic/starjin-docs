## Variables

To use these variables in your message templates, enclose the variable name within curly braces `{}`.

**Here is an example for `giveawayEntryMessage`:**

```
{memberMention}, you're entered! (**{totalEntries}** entries)
```

### Giveaway Entry Message

**Used for:** Announcing a new giveaway entry.

* **memberId**: The unique ID of the user who entered the giveaway.
* **memberName**: The display name of the user who entered.
* **memberMention**: A mention of the user (e.g., `@username`).
* **totalEntries**: The total number of people who have entered the giveaway so far.

### Giveaway Winner Announcement

**Used for:** Declaring the winners of a giveaway.

* **winners**: A list of the winning users (formatted as needed for the platform).
* **winnerCount**: The total number of winners.

### Giveaway Winner Notification

**Used for:** Sending a private message to the giveaway winners.

* **prize**: The prize that the winners have won.
* **channelName**: The name of the channel where the giveaway took place.
* **channelMention**: A mention of the giveaway channel (e.g., #giveaway-channel).
* **guildName**: The name of the server where the giveaway happened.

### Giveaway Reroll Announcement

**Used for:** Announcing that a giveaway has been rerolled.

* **executorMention**: A mention of the user who rerolled the giveaway (e.g., @admin).
* **executorUsername**: The username of the user who rerolled the giveaway.
* **winners**: A list of the new winners (formatted as needed for the platform).
* **winnerCount**: The total number of new winners.
