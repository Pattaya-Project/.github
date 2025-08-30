![Welcome to Pattaya :)](https://github.com/Pattaya-Project/.github/blob/main/profile/pattaya_banner.png)

## Pattaya RAT is an experimental real-time based Remote Administrator Tool (RAT). <br>

Now Pattaya RAT is already release in Development version you can download using this <a href="https://drive.google.com/file/d/1S6eEFPZWZcPqyZywDhrsjZtgZ6HGJ0pC/view?usp=sharing" target="_blank">link</a> // password is: <b>welcometopattaya</b>
## Demo
<a href="https://youtu.be/Ht4GMrWczVo" target="_blank">https://youtu.be/Ht4GMrWczVo</a>

# Features
### Server
- <b>Real-time connection</b> because Pattaya RAT using socket.io for tramsmitting message
- <b>Multiple team player</b>. Pattaya RAT server support multiple user
- <b>Command permission</b>. This feature useful when provide Pattaya RAT as Trojan-As-A-Service
- <b>Multiple DB support</b>. Currently Pattaya RAT support 2 databases, SQLite and MongoDB but if you need to migrate to another DB, just modify the Prisma schema
- <b>Zero log</b>. If you being arrested, no information leak
- <b>Cross platform</b>. Pattaya server using Javascript. It supprot all OS

### Panel
- <b>Qt UI based</b> Cross platform GUI, Say no to HTML
- <b>Multiple themes</b>
- <b>Old-School RAT style</b> if you miss DarkComet

### Client
- <b>C#</b> can using <a href="https://github.com/TheWover/donut" target="_blank">Donut</a> to convert it to shellcode and do what you want
- <b>Builder support</b>


### All command right now
<pre>
+------------------+--------------------------------------------------+
|     Command      |                   Description                    |
+------------------+--------------------------------------------------+
|       help       |            Get Pattaya help terminal             |
+------------------+--------------------------------------------------+
|     pingbot      |            Handshake with current bot            |
+------------------+--------------------------------------------------+
|     killbot      |            Shutdown/Kill current bot             |
+------------------+--------------------------------------------------+
|        cd        |               Change bot directory               |
+------------------+--------------------------------------------------+
|      mkdir       |                 Create directory                 |
+------------------+--------------------------------------------------+
|      rmdir       |                 Delete directory                 |
+------------------+--------------------------------------------------+
|        ls        |                  List directory                  |
+------------------+--------------------------------------------------+
|       cat        |                View file content                 |
+------------------+--------------------------------------------------+
|        rm        |                   Delete file                    |
+------------------+--------------------------------------------------+
|       pwd        |         Print current working directory          |
+------------------+--------------------------------------------------+
|        ps        |                List all processes                |
+------------------+--------------------------------------------------+
|      whoami      |               Get current username               |
+------------------+--------------------------------------------------+
|      shell       |              Execute shell command               |
+------------------+--------------------------------------------------+
|      upload      |   Upload file to bot (limit file size to 10MB)   |
+------------------+--------------------------------------------------+
|     download     | Download file from bot (limit file size to 10MB) |
+------------------+--------------------------------------------------+
|   url-download   |            Drop file from url to bot             |
+------------------+--------------------------------------------------+
| execute-assembly |              Execute .Net assembly               |
+------------------+--------------------------------------------------+
|    screenshot    |                Capture bot screen                |
+------------------+--------------------------------------------------+
|    openloots     |            Open bot loots collection             |
+------------------+--------------------------------------------------+
|      clear       |                  Clear terminal                  |
+------------------+--------------------------------------------------+
</pre>
#### If bugs occurs, feel free to open issue







