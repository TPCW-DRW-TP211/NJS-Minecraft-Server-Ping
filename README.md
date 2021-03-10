# NJS-Minecraft-Server-Ping
Ping Minecraft Server, Get Server Information. (Motd, Players Online Amount, Favicon etc.)


Hello? This should be my 8th project that I will continue to develop.

Time flies so fast. I have been open source for many years, But there are few practically useful projects.

Get to know me again, My name is TP211, Hello

# =====Project Introduction=====
This project is a *command line* tool designed to quickly obtain the basic information of the Minecraft Server.
It allows you to get the basic information of the Minecraft Server.
### SRV Resolution support is not currently provided!

The current version supports the obtained information:
- Server Host Address
- Server Port
- Server Version
- Server Version Code (E.g. 47)
- Number Of Online Players
- Maximum Number Of Players
- Hidden Small Motd (The content displayed by the mouse pointer on the server delay icon. *Some servers do not exist.*)
- Server Motd
- Server Favicon
- Mods Information (List Of Mod)
- Extra Information (if it exists? *I cannot guarantee what the content is*)

Developed based on Node.JS module *[minecraft-server-util](https://www.npmjs.com/package/minecraft-server-util)*

# =====Instructions=====
For the compiled binary package:
- Only need to be executed in the *Command Prompt*
- mcsrvping.exe &lt;host&gt; [port]
- ./mcsrvping &lt;host&gt; [port]
- Not compatible with MacOS temporarily.
- The host is MUST REQUIRED, If you don't fill it, The program will refuse to run.
- The port is optional, If omitted, The default port will be used for communication. (Default Port: *25565*)

For Node.JS Script source code:
- You can use the 'node' command to test the code.
- node main.js &lt;host&gt; [port]
- The precautions are the same as for the binary package.
- &lt;&gt; is Required, [] is Optional.

# ===== About Issues=====
I'm Sorry, Because I don't visit github often, It may take a long time for the submitted Issue to get a response.
You can try to send me an email: 1242410592@qq.com
