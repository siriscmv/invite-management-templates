### Description

A 2 embed leave message template with cool emojis

### Emoji Credits

- Original Source: [Icons](https://discord.gg/gpkNkYKr8G)
- Emojis stored in [Invite Management](https://discord.gg/EdT6KNmxSD)

### Template Credits

[Siris#1337](https://discord.com/users/581451736305106985)

### Showcase

![showcase](showcase.png 'Showcase')

### Template

JSON template

```json{
	"embeds": [
		{
			"color": 3092790,
			"fields": [
				{
					"value": "・${user_mention}\n・`​${user_tag}`​\n・Account created ${user_created_date}",
					"name": "<:leaves:906931999908966420> User left",
					"inline": false
				}
			],
			"thumbnail": { "url": "https://cdn.discordapp.com/avatars/user" }
		},
		{
			"color": 3092790,
			"fields": [
				{
					"value": "・${inviter_mention}\n・`​${inviter_tag}`​\n・`​${inviter_invites_leaves}`​ leaves\n・`​${inviter_invites_total}`​ invites",
					"name": "<:Invite:906259354624327700> Invited by",
					"inline": false
				}
			],
			"thumbnail": { "url": "https://cdn.discordapp.com/avatars/inviter" },
			"footer": {
				"text": "We now have ${guild_membercount} members!",
				"icon_url": "https://cdn.discordapp.com/avatars/server"
			}
		}
	]
}
```
