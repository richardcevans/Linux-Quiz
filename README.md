# Linux Quiz

A browser-based multiple choice quiz for ITSC 1301 and ITSC 2325 students learning Linux fundamentals. No server required — open `linux-quiz.html` directly in any browser.

## How to use

Open `linux-quiz.html` in a browser. Answer 10 questions per set, review your results, then start the next set. Use the category buttons to focus on a specific topic.

## Question bank

~200 questions across 6 categories:

| Category | Questions | Topics |
|---|---|---|
| Files & Filesystem | 74 | BASH shell, vi/vim, grep/sed/awk, piping & redirection, echo/cat/touch/mkdir, mount/umount, ext4, fdisk, /etc/ /var/ /dev/ /home/ /proc/, man pages |
| Processes & Services | 39 | systemctl, journalctl, ps, PIDs, run levels, systemd targets, GUIs, desktop environments, rsyslog |
| Security & Hardening | 30 | PAM, firewalls, VPNs, encryption, SSH hardening, fail2ban, least privilege |
| Users & Permissions | 20 | useradd, usermod, chown, chgrp, chmod, /etc/shadow, groups |
| Networking & Firewall | 27 | SSH, sshd, ssh-keygen, scp, UFW, ping, netstat, ip addr, ports |
| Package Management | 8 | apt, dpkg |

## Features

- Randomized question order each set
- Category filter to drill a specific topic
- End-of-set review showing correct answers for missed questions
- Set history table tracking score and accuracy across rounds

## Course context

Covers beginner-level Linux topics including the BASH shell, vi, file management, piping and redirection, user administration, package management, networking, SSH, services, logging, run levels, GUIs, and Linux security fundamentals.
