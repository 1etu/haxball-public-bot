NOTE: My first attempt at creating anything for HaxBall in my life. This is nowhere near ready for production and probably have shit tons of security issues.

Head to the https://haxball.com/headlesstoken and grab your token

Go to the script and find the ROOM_CONFIG  ```(Line 8) ```
```
const ROOM_CONFIG = {
    roomName: "🎐 etu | Futsal - Sniper - Power | 24/7",
    maxPlayers: 12,
    public: true,
    noPlayer: true, 
    token: "" 
};
```

Replace the ```token: ""``` part with your actual token

Go to the https://html5.haxball.com/headless

Open the developer console ```(F12)``` and paste the bot code there

Get the URL to join your server
