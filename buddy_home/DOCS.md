# Buddy Home Agent

Lets you control your home by chatting with Buddy at **https://buddy.bengom.co.uk**.

## Set-up (2 minutes)

1. Open the **Configuration** tab of this add-on.
2. Paste the **enrolment code** from your Buddy welcome sheet and press **Save**.
3. Press **Start** on the **Info** tab and switch on **Start on boot** and **Watchdog**.
4. Open the **Log** tab. You should see `Enrolled with the Buddy portal`.
5. Go to https://buddy.bengom.co.uk and sign in with the details on your welcome sheet.

## Good to know

- Buddy only makes **outbound** connections. No ports are opened and no router changes are needed.
- Home Assistant is reached through the built-in Supervisor connection. You do not need to create a token.
- The code works once and expires after 24 hours. If it is refused, ask for a new one.
- To move Buddy to a different device or re-connect after the home was reset, paste a **new** code and restart the add-on.
