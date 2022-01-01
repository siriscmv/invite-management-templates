### Description

A 2 embed join message template with cool emojis

### Emoji Credits

- Original Source: [Icons](https://discord.gg/gpkNkYKr8G)
- Emojis stored in [Invite Management](https://discord.gg/EdT6KNmxSD)

### Template Credits

[Siris#1337](https://discord.com/users/581451736305106985)

### Showcase

![showcase](assets/2embeds.png 'Showcase')

### Template

JSON template

```json
{
	"embeds": [
		{
			"color": 6746969,
			"fields": [
				{
					"value": "・${user_mention}\n・`​${user_tag}`​\n・Account created ${user_created_date}",
					"name": "<:Join:906259324911882281> User joined",
					"inline": true
				}
			],
			"thumbnail": { "url": "https://cdn.discordapp.com/avatars/user" }
		},
		{
			"color": 3092790,
			"fields": [
				{
					"value": "・${inviter_mention}\n・`​${inviter_tag}`​\n・`​${inviter_invites_joins}`​ joins\n・`​${inviter_invites_total}`​ invites",
					"name": "<:Invite:906259354624327700> Invited by",
					"inline": true
				},
				{
					"value": "・[`​${invite_code}`​](https://discord.gg/invite/${invite_code})\n・`​${invite_uses}`​ uses",
					"name": "<:Linkadd:906259338526601246> Invite code used",
					"inline": true
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
