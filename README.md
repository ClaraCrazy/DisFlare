# DisFlare
Cloudflare-like "protection" for your Discord DMs.
![disflare](https://github.com/ClaraCrazy/DisFlare/assets/55334727/b4086f95-b596-4257-8074-f42e7d82b6ff)

-----

### This project is currently in the concept phase. Feel free to contact me if you might be interested in helping:

- Python application
- Should run on Linux (primary) and Windows (secondary goal)
- Run as service, for linux maybe auto-install systemd service?
- Uses provided Token
- Waits for new DMs or "Message requests" and acts:
  - First thing thats done is muting the DM, to not bother the user
  - Instantly replies based on your settings with a captcha. Also setting to instantly decline & block based on account age, default profile pics or message parameters
  - Captcha is a simple image captcha, just send image, ask for text. Little intro to disflare ofc so the user knows whats going on
  - Upon successful captcha DM is marked as unread to put the little (1) back on the client and let the user know they got a legit human being
  - Failed captcha results in retry, block or other, based on config
- Config via json file, far future plans would involve a betterdiscord / aliu / whatever- client mod with a settings tab.

### This idea is almost 2yrs old at this point, and I finally want to tackle it, but since I already maintain 7 projects full-time its getting hard to add more. Feel free to help <3
