# Linux Quiz

A browser-based multiple choice quiz for ITSC 1301 and ITSC 2325 students learning Linux fundamentals. No server required — open `linux-quiz.html` directly in any browser.

## How to use

Open `linux-quiz.html` in a browser. Answer 10 questions per set, review your results, then start the next set. Use the category buttons to focus on a specific topic.

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

## Course context

Covers beginner-level Linux topics including the BASH shell, vi, file management, piping and redirection, user administration, package management, networking, SSH, services, logging, run levels, GUIs, and Linux security fundamentals.
