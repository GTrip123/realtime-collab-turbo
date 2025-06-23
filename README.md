# turbowarp realtime collab
a script that can do a turbowarp realtime collab...

# INSTRUCTIONS:
# 1: download both files (collab and server.js)

# 2: open your console
(For Windows, press the Win key and type cmd. For Mac, press Command key and
the Space key and then type "Terminal". Terminal will appear and click it so it opens.)

# 3: 
Type "node server.js" in your console/terminal. It will start on "ws://localhost:8080".

# 4:
Open "collab.js". Go to line 23/24. You should see "URL: { type: Scratch.ArgumentType.STRING, defaultValue: 'wss://yourserver.com' }"
Edit the defaultValue to say "ws//localhost:8080".

# 5:
IF you wanted to collab with your friends, then you are going to have to go into your router's settings (usually 192.168.0.1) and go to Port Forwarding. If you don't know how to do that, google how to do it with [insert router brand]. Make a new port forwarder and set it to 8080. If you know your public ip, then replace the "defaultValue" from collab.js with your public ip with ':8080" at the end. Then, go to
