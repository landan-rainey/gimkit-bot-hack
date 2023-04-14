# gimkit-bot-hack
gimkit bot hack working april 13
READ BEFORE USING
To use this exploit, you have to make it a bookmarklet since gimkit patched it. To make it into a bookmarklet:

1: Create a bookmark of a random page.
2: Right click on the bookmark, select Edit.
3: Type javascript: and paste the exploit.
4: Click on the bookmarklet BEFORE the page loads (IMPORTANT).
5: If the dialog box says Started. you can continue using as normal, if it says Refresh and try again. Continue to step 6.
6: Refresh the page and click the bookmarklet as fast as possible. Continue to step 5.

For exploit.js
1: Run the script.
2: Answer a question, then press ; (Make sure its right or you lose money).
3: Press u to simulate answering a question.

For exploit-auto.js
1: Run the script
2: Answer a question, then press ; (Make sure its right or you lose money)
3: Press u to toggle on or off

You might get kicked if you answer too fast.
I am not responsible for you getting kicked or getting in trouble for using these.

How it works
nerd Gimkit uses websockets to transfer data between the client and the server. Think of websockets as a tunnel, data can go from the client to the server or the server to the client.
What this hack does is intercept the data being transferred, records it, and lets it continue to the server.
When you press u, the client sends the saved data directly to the server via the websocket. If the saved data is a correct answer, it will trick the server into giving you money.

