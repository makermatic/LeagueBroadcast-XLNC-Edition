# <u>LeagueBroadcast XLNC Edition</u>

This is a fork of LeagueBroadcast by Lars Eble. The front end and configs have been heavily modified to work with the new XLNC League Layout.

## <u>First Time Setup</u>

1. Download the app by clicking the green code button and click "Download Zip."
2. Extract the folder to a reasonable location (ex. `documents/xlnc`).
4. Open `LeagueBroadcast.exe` and you're all set!

## <u>Match Setup</u>

1. Before doing anything, make sure you prep your Team Logos to be **squared** (ex. 512 x 512 pixels).
2. Open the League of Legends client, the circle on the top right should change to `Client Connected`.
3. In the `Pick Ban` section, type in the Four Fields.
   1. `Team Name`
   2. `Tag` (This must be exactly the same as `Team Name`)
   3. `Coach`
   4. `Logo`
4. In the `Ingame` section, click on the downwards arrow at the top of the screen.
5. Change the `Series Game Count` to the designated number (ex. `B01, Bo3`, `Bo5`).

## <u>FAQs</u>

- If the browser sources have empty links, what should I do?

  - Here you go: 
    - In Game: http://localhost:9001/frontend?backend=localhost
    
    - Pick Ban: http://localhost:9001/?backend=ws://localhost:9001/api
    
    - Just make sure that your sources are set to 1920x1080
    
      

- The app crashes every time I load into game. What did I do?

  - Just relaunch the app. If you have a stream deck, it's handy to make a button for the exe.
  - You didn't do anything wrong it's okay! :)

- I've downloaded Net Framework trillions of times and it's still not letting me open the app
  - Download .NET Core 3.1 [here](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-3.1.413-windows-x64-installer)

- The links are `localhost`, what does that even mean?

  - In a nutshell, the app hosts two webpages on your computer rather than on a server far far away.
