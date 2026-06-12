# Linux Quiz

Browser-based learning tools for ITSC 1301 and ITSC 2325 students. Two files, no installation required.

| File | What it is |
|---|---|
| `linux-quiz.html` | Multiple-choice quiz — 248 questions across 7 categories |
| `terminal-invaders.html` | Arcade game — type Linux commands to destroy invaders |

## Getting started

1. Click the green **Code** button on this page, then click **Download ZIP**
2. Unzip the downloaded file
3. Open either HTML file in any web browser (Chrome, Firefox, Edge)

That's it — no installation required.

## How to use

Answer 10 questions per set, then review your results and start the next set. Use the category buttons to focus on a specific topic. Use the **Light / Navy / Dark** buttons in the top right to switch themes.

## Question bank

~248 questions across 7 categories:

| Category | Questions | Topics |
|---|---|---|
| Files & Filesystem | 116 | BASH shell, vi/vim, grep/sed/awk, piping & redirection, echo/cat/touch/mkdir, mount/umount, ext4, fdisk, /etc/ /var/ /dev/ /home/ /proc/, man pages, shell variables ($PATH, $USER, $0, $1), case sensitivity, history, env, alias, tee, diff, lsblk, rsync, gzip, unzip |
| Processes & Services | 44 | systemctl, journalctl, ps, PIDs, kill, run levels, systemd targets, GUIs, desktop environments, rsyslog, cron, uptime, date, uname |
| Security & Hardening | 30 | PAM, firewalls, VPNs, encryption, SSH hardening, fail2ban, least privilege, iptables, ACLs, hashing, digital signatures |
| Networking & Firewall | 21 | SSH, sshd, scp, UFW, ping, netstat, ip addr, ports, ssh-copy-id, /etc/services, shutdown |
| Users & Permissions | 14 | useradd, adduser, usermod, userdel, passwd, whoami, id, groups, sudo, su, /etc/passwd, /etc/shadow, /etc/sudoers |
| File Permissions | 13 | chmod, chown, chgrp, reading permission strings (rwxr-x---), numeric permissions (755, 644) |
| Package Management | 10 | apt, dpkg |

## Features

- Randomized question order each set
- Category filter to drill a specific topic
- Avoid-recent window (10/20/30/Off) to prevent seeing the same question too soon
- Wrong answers re-queued for retry in the same session
- Go back to any question in the current set to review or re-answer it
- End-of-set review showing correct answers for missed questions
- Set history table tracking score and accuracy across rounds
- Light, Navy, and Dark themes

---

## Terminal Invaders

An arcade game in the style of Space Invaders. Rows of enemies descend toward your terminal — each one shows a hint describing a Linux command. Type the correct command and press Enter to fire. Miss too many, and it's game over.

### How to play

1. Open `terminal-invaders.html` in a browser
2. Choose a difficulty: **Easy**, **Medium**, or **Hard**
3. Read the hint on each enemy (e.g. *list files*) and type the matching Linux command (`ls`) in the prompt at the bottom
4. Press **Enter** to fire — a correct command destroys the matching enemy and scores points
5. Wrong command? You get an error message and nothing fires — try again
6. Clear all 6 enemies to advance to the next wave. There are 5 waves per game.

### Scoring

Points per kill depend on command difficulty tier:

| Tier | Color | Commands | Points |
|---|---|---|---|
| Basic | Green | ls, pwd, cd, clear, date, echo | 10 |
| Files | Cyan | cat, cp, mv, rm, mkdir, touch, head, tail, less | 20 |
| System | Orange | ps, top, free, df, who, whoami, kill, grep, man | 30 |
| Advanced | Red | chmod, chown, ssh, wget, find, diff | 40 |

### Lives and enemies

You start with **3 lives**. You lose a life when:
- An enemy wave descends past the ground line
- A bomb dropped by an enemy hits your terminal

### Hint system

Press **Ctrl+H** during a wave to reveal the answer for the leftmost un-hinted enemy. A confirmation prompt appears — press **Y** or **Enter** to confirm, **N** or **Esc** to cancel. Each hint costs 1 life.

### High scores

After each game, if your score ranks in the top 10, you are prompted to enter 3 initials. Scores persist in your browser (localStorage) and appear on the title screen.

### Difficulty comparison

| | Easy | Medium | Hard |
|---|---|---|---|
| Formation speed | Slow | Moderate | Fast |
| Bomb frequency | Rare | Occasional | Frequent |
| Speed on kills | +40% | +60% | +80% |

### Command reference (all 30 commands)

`ls` `pwd` `cd` `clear` `date` `echo` `cat` `cp` `mv` `rm` `mkdir` `touch` `head` `tail` `less` `ps` `top` `free` `df` `who` `whoami` `kill` `grep` `man` `chmod` `chown` `ssh` `wget` `find` `diff`

Each game shuffles all 30 commands and deals 6 per wave — no command repeats within a game.

---

## Linux Quiz

Covers beginner-level Linux topics including the BASH shell, vi, file management, piping and redirection, user administration, package management, networking, SSH, services, logging, run levels, GUIs, and Linux security fundamentals.
