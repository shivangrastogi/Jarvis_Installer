**🧠 JARVIS: Your Personal Python Assistant (Console Version)**

JARVIS (Just A Rather Very Intelligent System) is a console-based personal assistant developed in Python. It can respond to voice commands, execute various automation tasks, control YouTube and browser operations, report system status, and more.

-----
**🧪 Features**

**✅ Function Commands**

**General Features**

- "check internet speed"
- "check speed test"
- "speed test"
- "are you there"
- "hello there"
- "check temperature"
- "temperature"
- "find my ip"
- "ip address"
- "what is the time"
- "time"
- "what time is"
- "start clap with music system"
- "start smart music system"
-----
**✅ Common Automation Commands**

**Open Applications**

- "open [app name]"

**Close Applications**

- "close this"
- "close window"
- "close application"
- "close app"
- "band kar do"
- "band karo"
- "close the program"
- "close"
-----
**✅ Battery Commands**

- "check battery percentage"
- "battery percentage"
- "check plug"
- "check battery plug"
- "give me the battery alert"
- "battery alert"
-----
**✅ Google Browser Commands**

**Tabs & Navigation**

- "refresh page"
- "close tab"
- "open new tab"
- "open browser menu"
- "zoom in"
- "zoom out"
- "switch to next tab"
- "switch to previous tab"
- "open history"
- "open bookmarks"
- "go back"
- "go forward"
- "open dev tools"
- "toggle full screen"
- "open private window"

**Google Search**

- "search [query] in google"
- "search [query] on google"

**Website Access**

- "open website [site name]"
- "open site [site name]"

**Scrolling**

- "scroll up"
- "scroll down"
- "scroll to top"
- "scroll to bottom"
-----
**✅ YouTube Commands**

**Music Playback**

- "play music" → triggers listening and plays
- "stop"
- "play"
- "toggle play/pause"
- "toggle mute/unmute"

**Volume**

- "increase volume"
- "decrease volume"

**Seek Controls**

- "seek forward"
- "seek backward"
- "seek forward 10 seconds"
- "seek backward 10 seconds"
- "seek backward frame"
- "seek forward frame"
- "seek to beginning"
- "seek to end"
- "seek to previous chapter"
- "seek to next chapter"

**Playback Speed**

- "increase playback speed"
- "decrease playback speed"

**Video Navigation**

- "move to next video"
- "move to previous video"

**Subtitles**

- "toggle subtitles"

**Text & UI Styling**

- "increase font size"
- "decrease font size"
- "rotate text opacity"
- "rotate window opacity"

**Pan**

- "pan up"
- "pan down"
- "pan left"
- "pan right"

**Zoom**

- "zoom in"
- "zoom out"

**Window Control**

- "go to search box"
- "toggle full screen"
- "exit full screen"
- "toggle theater mode"
- "toggle miniplayer mode"
- "toggle party mode"

**Navigation**

- "navigate forward"
- "navigate backward"

**Search**

- "search [query] in youtube"
- "search [query] on youtube"
- "search in current youtube window"
- "search on current youtube window"
- "search current youtube window"
- "search [query]"
-----
**🧑‍💻 Installation**

1. **Clone the repository**

bash

CopyEdit

git clone https://github.com/yourusername/jarvis-assistant.git

cd jarvis-assistant

1. **Install dependencies**
   1. Create virtual environment (optional but recommended)

bash

CopyEdit

python -m venv venv

venv\Scripts\activate

1. Install required packages:

bash

CopyEdit

pip install -r requirements.txt

1. **Set environment**\
   Create a .env file in the root:

env

CopyEdit

Assistantname=JARVIS

1. **Check directories**\
   Ensure these folders exist:

kotlin

CopyEdit

├── Files

│   ├── Mic.data

│   └── Status.data

├── Graphics

│   └── Jarvis.gif

1. **Run JARVIS**

bash

CopyEdit

python main.py

-----
**🎙️ Usage**

You can say:

- "check internet speed"
- "find my IP"
- "open Chrome"
- "search Python tips on Google"
- "play songs on YouTube"
- "toggle full screen"
- "give me the battery alert"

Or many more natural phrases thanks to modular command parsing.

-----
**📂 Project Structure**

arduino

CopyEdit

├── FUNCTION

│   └── MAIN\_FUNCTION\_INTEGRATION

│       └── function\_integration.py

├── AUTOMATION

│   ├── MAIN\_INTEGRATION

│   │   └── \_integration\_automation.py

│   └── COMMON\_AUTOMATION

│       ├── open.py

│       └── close.py

├── BRAIN / DATA / USER\_INTERFACE ...

├── main.py

└── README.md

-----
**💡 Notes**

- You must have ChromeDriver installed for web automation.
- Mic permissions should be allowed.
- Works best on Windows with admin privileges for certain operations.
-----
**📦 Build Executable (Optional)**

To create a .exe:

bash

CopyEdit

pyinstaller --onefile --noconsole main.py

Or for full folder build:

bash

CopyEdit

pyinstaller --noconsole --add-data "Graphics;Graphics" --add-data "Files;Files" main.py

-----
**🙋‍♂️ License & Support**

MIT License. For issues, raise one on [GitHub](https://github.com/yourusername/jarvis-assistant/issues).

