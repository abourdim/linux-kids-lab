<p align="center">
  <img src="logo.svg" alt="Workshop DIY" width="120"><br>
  <strong style="font-size:2rem">LINUX KIDS LAB</strong><br>
  <em>Type • Hack • Play</em><br><br>
  <img src="https://img.shields.io/badge/Linux-Kids%20Lab-22c55e?style=for-the-badge&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/Commands-200%2B-f97316?style=for-the-badge" alt="200+ Commands">
  <img src="https://img.shields.io/badge/Terminal-Simulator-3b82f6?style=for-the-badge" alt="Terminal Simulator">
  <img src="https://img.shields.io/badge/Cost-%240-22c55e?style=for-the-badge" alt="Free">
  <img src="https://img.shields.io/badge/version-1.0-9ca3af?style=for-the-badge" alt="v1.0">
</p>

---

## 🔥 What is this?

**208 terminal commands** that make you look like a hacker, play games, break things (safely), and actually learn Linux — all from a web app with a **built-in terminal simulator**.

No installs needed to start. Open the web app, type commands, see output. When you're ready, run them for real on your machine.

```
  ┌──────────────────────────────────────────────────────────┐
  │ kid@linux:~$ cmatrix                                     │
  │                                                          │
  │  ╔╦╗┌─┐┌┬┐┬─┐┬─┐ ─┐ ╦  ┌─┐┌─┐┌┬┐┌─┐┌┬┐                │
  │  ║║║├─┤ │ ├┬┘│┌┘  │ ║  │ │├─┤ ││├┤  ││                 │
  │  ╩ ╩┴ ┴ ┴ ┴└─┴└─ ─┘ ╩═╝└─┘┴ ┴─┴┘└─┘─┴┘                │
  │                                                          │
  │  Wake up, Neo...                                         │
  │  The Matrix has you...                                   │
  │  Follow the white rabbit.                                │
  │                                                          │
  │ kid@linux:~$ fortune | cowsay | lolcat                   │
  │  ________________________________________                │
  │ / You will be awarded some great honor. \                │
  │ \ — fortune cookie                      /                │
  │  ----------------------------------------                │
  │         \   ^__^                                         │
  │          \  (oo)\_______                                 │
  │             (__)\       )\/\                              │
  │                 ||----w |                                 │
  │                 ||     ||                                 │
  │                                                          │
  │ kid@linux:~$ █                                           │
  └──────────────────────────────────────────────────────────┘
```

Works on **Linux**, **macOS**, **Windows (MSYS2)**, and **Git Bash**.

---

## ⚡ Quick Start

### Option A — Just explore (zero install)

Open `index.html` → type commands in the built-in terminal simulator → see realistic output. Offline. Free. No setup.

### Option B — Run commands for real

Pick your OS, run one command:

**🐧 Linux**
```bash
curl -sL workshop-diy.github.io/linux-lab/setup.sh | bash
```

**🍎 macOS**
```bash
curl -sL workshop-diy.github.io/linux-lab/setup-mac.sh | bash
```

**🪟 Windows (MSYS2)**
```bash
curl -sL workshop-diy.github.io/linux-lab/setup-msys2.sh | bash
```

**🪟 Git Bash** — Already have Git for Windows? Basics work out of the box (`ls`, `cat`, `grep`, `curl`, `ssh`, `find`). For the fun stuff, upgrade to MSYS2.

The setup script scans your system, shows what's missing, asks permission, installs everything, then celebrates:

```
  🔍 Scanning your system...

    ✅ 42 commands found
    ❌ 47 missing

  📦 Install 47 packages? [y/N] y
  Installing... ████████████████████ 100%

  🎉 89/89 commands available.
  Try: figlet "HACK THE PLANET" | lolcat
```

---

## 🎮 What can you do?

| Feature | What it means |
|---|---|
| **208 commands** | Organized in 17 categories from beginner to geek |
| **Terminal simulator** | Fake bash shell in the browser. Type anything |
| **Command cards** | Name, description, install, example, simulated output |
| **"Try it" buttons** | Opens simulator, auto-types the command |
| **Pipe combos** | `fortune \| cowsay \| lolcat` — chain commands together |
| **4 OS support** | 🐧 Linux · 🍎 macOS · 🪟 MSYS2 · 🪟 Git Bash |
| **Install tabs** | `apt` / `brew` / `pacman` / Git Bash per command |
| **One-click setup** | One script installs everything for your OS |
| **Surprise Me** | Random command from the catalog |
| **Quest system** | 8 missions + 8 badges to earn |
| **4 themes** | 🌙 Stealth · ⚡ Neon · ☁️ Arctic · 🔥 Blaze |
| **3 languages** | 🇬🇧 English · 🇫🇷 Français · 🇸🇦 العربية (RTL) |
| **Offline** | No internet. No API. Everything in one HTML file |

---

## 🖥️ Terminal Simulator

The built-in terminal is not a real shell — it's a safe simulation in the browser.

**Real logic (computed in JS):**
`cal`, `date`, `factor`, `cowsay` (renders bubble), `history`, `clear`, `cd`/`ls`/`mkdir`/`touch` (fake filesystem), `echo`, `rev`, `wc`, arrow key history

**Animated:**
`cmatrix` (falling characters), `pipes.sh` (growing pipes), `sl` (train crosses screen), `aafire` (ASCII flames), `asciiquarium` (fish tank)

**Randomized:**
`fortune` (pool of 30 quotes), `neofetch` (random uptime/RAM), `cbonsai` (different tree shapes), `shuf`, `rig` (fake identities)

**Everything else:** realistic pre-recorded output. Pipes chain outputs. Unknown commands → `bash: xyz: command not found`.

---

## 📦 208 Commands — 17 Categories

### 🖥️ Terminal 101 (10)

The basics every terminal user needs. `cd`, `ls`, `pwd`, `mkdir`, `cp`, `mv`, `rm`, `man`, `clear`, `echo`.

### 🎭 ASCII Arsenal (18)

Text art and decorations. `figlet`, `toilet`, `cowsay`, `cowthink`, `ponysay`, `fortune`, `boxes`, `cbonsai`, `lolcat`, `banner`, `aview`, `jp2a`, `aafire`, `caca-utils`, isometric figlet, metallic toilet, dragon cowsay, parchment boxes.

### 🔥 Hacker Mode (12)

Make your screen look like a movie. `cmatrix`, `hollywood`, `no-more-secrets`, `pipes.sh`, `genact`, `asciiquarium`, `tty-clock`, `rain`, `bb`, `nyancat`, `xeyes`, color cmatrix.

### 🕵️ System Spy (10)

What's inside your machine. `neofetch`, `htop`, `free`, `df`, `uptime`, `whoami`, `uname`, `lscpu`, `sensors`, `w`.

### 📁 File Ninja (11)

Find anything, search inside files. `tree`, `find`, `grep`, `ls -la`, `du`, `wc`, `stat`, `diff`, `file`, `head`, `tail`.

### 🎮 Games (16)

Real games in the terminal. `bastet` (Tetris), `ninvaders` (Space Invaders), `nsnake`, `2048`, `moon-buggy`, `nudoku` (Sudoku), `greed`, `nethack`, `pacman4console`, `tron`, `bsdgames` (30+ classics), `chess`, `ttysolitaire`, `adventure` (1977 original), `zork`, `robots`.

### 🌐 Network Ops (13)

Ping, trace, fetch. `ping`, `traceroute`, `curl wttr.in`, `curl ifconfig.me`, `dig`, `ss`, `wget`, `ssh`, `mtr`, `nmap`, `arp`, `host`, `whois`.

### ✏️ Text Weapons (10)

Slice, dice, transform. `sed`, `awk`, `sort`, `rev`, `tac`, `shuf`, `cut`, `uniq`, `tr`, `xargs`.

### 🧪 Weird Science (14)

Numbers, math, computation. `factor`, `bc`, `pi`, `seq`, `numfmt`, `units`, `primes`, `dc`, `numaverage`, `datamash`, `gnuplot`, `octave`, `maxima`, `calc`.

### 🔊 Sound & Speech (6)

Make noise. `espeak`, `say`, `beep`, `aplay`, `sox`, `spd-say`.

### 🧬 Cursed & Obscure (12)

Things you didn't know existed. `ddate` (Discordian calendar), `rig` (fake identities), `pv` (pipe progress bar), `oneko` (cat chases cursor), `xdotool` (ghost mouse), `expect` (auto-answer prompts), `look` (dictionary lookup), `flock` (file locking), `inotifywait` (file surveillance), `figlet -f banner3-D`, `cacademo`, `3D figlet`.

### 🧲 Hardware Whisperer (10)

Talk to your hardware. `lsusb`, `lspci`, `lsblk`, `dmidecode`, `hdparm`, `smartctl`, `acpi`, `xrandr`, `hwinfo`, `inxi`.

### 🎪 Party Tricks (10)

Show-off commands. `curl wttr.in/Moon` (moon phase), `cal 9 1752` (missing days!), `telnet mapscii.me` (world map in ASCII), `curl rate.sx`, `curl cheat.sh/tar`, random useless facts piped to cowsay, `ponysay`, `toilet --gay` (chromatic mode), `rig | cowsay`.

### 🔬 Forensics & Snooping (10)

Who did what and when. `last`, `lastlog`, `w`, `finger`, `strace`, `ltrace`, `lsof`, `tcpdump`, `strings`, `auditd`.

### 🕹️ Retro & Nostalgia (8)

Easter eggs and hidden gems. `emacs -batch -l dunnet` (hidden game), `vim :help 42` (Easter egg), `apt moo` → `aptitude -vvv moo` (keep going...), `dmesg`, `journalctl`, `screenfetch`, `linuxlogo`, `cowsay -l` (30+ secret characters).

### 🎨 Pimp My Terminal (6)

Customize everything. PS1 prompt hacks, `alias`, `.bashrc` editing, ANSI escape color codes, `oh-my-bash`, `starship` prompt.

### 💣 Danger Zone (8)

Commands that DESTROY your system. **Read-only. Giant warnings. Never run these.**

`rm -rf /` (delete everything), `:(){ :|:& };:` (fork bomb), `dd if=/dev/zero of=/dev/sda` (overwrite disk), `chmod -R 000 /` (remove all permissions), `mkfs.ext4 /dev/sda` (format drive), `mv /home/* /dev/null` (files into void), piping unknown URLs to shell, `sudo rm -rf --no-preserve-root /`.

### 🧰 Tricks & One-Liners (18)

Weird, fun, useful. `yes`, `sl` (train for mistyping ls), `watch`, `time`, `alias`, `history`, `!!` (repeat with sudo), `curl parrot.live` (dancing parrot), `curl ascii.live/forrest`, `telnet towel.blinkenlights.nl` (Star Wars in ASCII), `rev`, `tac`, `shuf`, `fold`, `column`, metallic toilet, slanted figlet, colored cmatrix.

---

## 🌍 Platform Compatibility

| | 🐧 Linux | 🍎 macOS | 🪟 MSYS2 | 🪟 Git Bash |
|---|---|---|---|---|
| **Package manager** | `apt` | `brew` | `pacman` | — |
| **Terminal 101** | ✅ all | ✅ all | ✅ all | ✅ all |
| **ASCII Arsenal** | ✅ all | ✅ all | ✅ most | ⚠️ limited |
| **Hacker Mode** | ✅ all | ✅ most | ✅ most | ❌ |
| **System Spy** | ✅ all | ✅ most | ⚠️ some | ⚠️ basic |
| **File Ninja** | ✅ all | ✅ all | ✅ all | ✅ most |
| **Games** | ✅ all | ✅ most | ✅ most | ❌ |
| **Network Ops** | ✅ all | ✅ all | ✅ most | ✅ most |
| **Text Weapons** | ✅ all | ✅ all | ✅ all | ✅ all |
| **Hardware** | ✅ all | ⚠️ some | ⚠️ limited | ❌ |
| **Danger Zone** | 🔒 read-only | 🔒 read-only | 🔒 read-only | 🔒 read-only |
| **Overall** | 100% | ~90% | ~75% | ~40% |

Each command card shows install tabs for all 4 platforms. If unavailable: "Linux only" or "Install MSYS2 for this one."

---

## 🏆 Quest System

**8 missions:**

1. ⚡ **Deploy** — Run the setup script on your real machine
2. 🖥️ **First Login** — Open a real terminal (Ctrl+Alt+T)
3. 🎭 **ASCII Art** — Create art with figlet, cowsay, or toilet
4. 🔥 **Matrix** — Enter the Matrix with cmatrix
5. 🕵️ **Spy** — Run neofetch and see your system info
6. 🎮 **Gamer** — Play a terminal game
7. 🌐 **Net Ops** — Curl something from the internet
8. 🎨 **Custom** — Customize your prompt (PS1)

**8 badges:**
🖥️ First Login · 🎭 ASCII Artist · 🔥 Matrix Agent · 🕵️ System Spy · 📁 File Ninja · 🎮 Gamer · 🌐 Net Ops · 🧙 Terminal Wizard

---

## 🔥 Best Combos

Commands get better when you pipe them together:

| Combo | What happens |
|---|---|
| `fortune \| cowsay` | Random quote said by a cow |
| `fortune \| cowsay -f tux \| lolcat` | Tux the penguin says a colorful quote |
| `figlet "HACK" \| lolcat` | Giant gradient text |
| `ls -la \| lolcat` | Colorful file listing |
| `curl wttr.in \| head -7` | Weather forecast, compact |
| `cal \| boxes -d dog` | Calendar inside a dog-shaped box |
| `uptime \| figlet` | Giant uptime display |
| `echo "DANGER" \| toilet --metal` | Metallic warning text |
| `rig \| cowsay -f stegosaurus` | Fake identity delivered by a dinosaur |
| `date +%H:%M \| figlet -f big` | Giant clock |

---

## 🆚 Already did the ESP32 labs?

Same design. Third lab in the Workshop-DIY series.

| | ESPHome Lab | WLED Lab | Linux Lab |
|---|---|---|---|
| **Focus** | Sensors, GPIO, micro:bit | LEDs, effects, audio | Terminal, commands, games |
| **Hardware** | ESP32-C3 + sensors | ESP32-C3 + LED strip | Any computer |
| **Install** | `esphome run` | install.wled.me | `curl setup.sh` |
| **Cost** | ~$15 in parts | ~$8 in parts | $0 |
| **Connection** | "You already typed in a terminal..." | "Same board, just reflash" | "Now master the terminal itself" |

> 💡 Kids who did the ESP32 labs already used the terminal for `esphome run`. This lab blows the door wide open on what else it can do.

---

## 🔧 Setup Script Details

The setup scripts do 5 things:

1. **Detect OS** — prints your system info
2. **Scan** — checks all 208 commands with `which`
3. **Scorecard** — shows ✅ installed / ❌ missing
4. **Ask** — "Install N missing packages? [y/N]"
5. **Install** — `apt` / `brew` / `pacman` depending on OS
6. **Celebrate** — `figlet "READY!" | lolcat`

Scripts never run without asking. You can also install commands individually — every command card shows its install command.

---

## 📁 Files

```
linux-kids-lab/
├── index.html          ← The web app (just open it)
├── logo.svg            ← Workshop-DIY logo
├── setup.sh            ← Linux installer
├── setup-mac.sh        ← macOS installer
├── setup-msys2.sh      ← MSYS2 installer
└── README.md           ← You are here
```

One HTML file. No build. No dependencies. No API calls. Just open `index.html`.

---

## 🔗 Links

| | Link |
|---|---|
| 📖 Linux Command Reference | [man7.org](https://man7.org/linux/man-pages/) |
| 🎮 Terminal Games List | [ttygames.wordpress.com](https://ttygames.wordpress.com) |
| 🐮 Cowsay Files | [cowsay.diamonds](https://cowsay.diamonds) |
| 🎨 Starship Prompt | [starship.rs](https://starship.rs) |
| 📝 Cheat Sheets | [cheat.sh](https://cheat.sh) |
| 🗺️ ASCII World Map | [mapscii.me](https://mapscii.me) |
| 🔬 ESPHome Kids Lab | [github.com/abourdim/esp32-c3-kids-lab](https://github.com/abourdim/esp32-c3-kids-lab) |
| 💡 WLED Kids Lab | [github.com/abourdim/wled-kids-lab](https://github.com/abourdim/wled-kids-lab) |

---

## 🙏 Credits

Built on top of hundreds of open-source tools by incredible developers worldwide.

Web app built for the [Workshop-DIY](https://github.com/abourdim) kids electronics program.

---

<p align="center">
  <strong>Built for kids who like to build things.</strong><br>
  <em>Workshop-DIY · 2026</em>
</p>
