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

<br><br>

## ❤️ Support me

<!--
Pwease support me >.<
-->  

<p>Since I work full-time on open-source projects spread across my organizations, my only source of income is donations from people like you that use & appreciate my stuff. So, if you can spare a dollar or two, I would really appreciate that. All the money goes towards paying rent, essentials like food, drinks etc, and most importantly it will be used to fuel my cookie addiction🍪<br></p>

- **[Patreon](<https://patreon.com/crazyco>) (Fee: 8%\*)**: ❤️ Account needed, subscription with perks.<br>
- **[Instant transfer (bunq)](<https://bunq.me/ClaraK>) (Fee: 0%\*)**: No account needed, one-time, directly to my bank<br>
- **[Paypal](<https://paypal.me/ClaraCrazy>)\*\* (Fee: 2%\*)**: Account needed, one-time<br>
- **[ko-fi](<https://ko-fi.com/cynthialabs>) (Fee: 2%\*)**: No account needed, one-time<br>
- **Monero (Fee: ~2.5%\*)**: `41kyWeeoVdK4quzQ4M9ikVGs6tCQCLfdx8jLExTNsAu2SF1QAyDqRdjfGM6EL8L9NpXwt89HJeAoGf1aoArk7nDr4AMMV4T`<br>

\* Fee is calculated by how much I will lose when cashing out<br>
\*\* Please make sure to select *Friends and Family*<br><br>
**Thanks for all your support <3**
