## ✨ Features

When a user sends a message to the support chat it will create a ticket which will be forwarded to the staff group. Any admin in the staff group may answer that ticket by just replying to it. Salutation is added automatically. Photos will be forwared too.

- [x] File forwarding from and to user
- [x] Database for handling open and closed tickets
- [x] Restrict users
- [x] Simple anti spam system
- [x] Send tickets to different staff groups
- [x] Private reply to user
- [x] Anonymize users
- [x] Auto reply based on keywords [beta]
- [x] Web chat [beta]]  

## 📜 Commands

Currently the support chat offers these commands (staff commands):

- `/open` - lists all open tickets (messages where noone has replied yet)
- `/reopen` - reopen a closed ticket
- `/close` - close a ticket manually (in case someone writes 'thank you')
- `/ban` - ban a person from writing to your chat

User commands:

- `/start` - tells the user how to use this bot
- `/help` - an overview over the commands or some explanation for the user
- `/faq` - shows the FAQ
- `/id` - returns your telegram id and the group chat id (1234567 -1234567890)

## 📦 Install

```bash
mv config/config-sample.yaml config.yaml
docker-compose up -d
```