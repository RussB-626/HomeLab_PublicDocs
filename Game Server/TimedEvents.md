# Timed Events

---

### Synch Backup Files [ MON - SUN ]

- 08:10:00 UTC
    - Send Messages To:
        - Players Discord
    - Synch Files

---

### Restart / Backup [ MON - SAT ]

##### ATM9 Instance

- 07:(50/55/59):00 UTC
    - Send Messages To:
        - ATM9 Instance
        - Players Discord

- 08:00:00 UTC
    - Send Messages To:
        - ATM9 Instance
        - Players Discord
    - Wait 10s ( **Roughly 08:00:10 UTC** )
    - Stop Minecraft Server
    - Wait 60s ( **Roughly 08:01:10 UTC** )
    - Send Messages To:
        - Players Discord
    - Take a Backup
    - Wait 120s ( **Roughly 08:04:00 UTC** )
    - Send Messages To:
        - Players Discord
    - Start Minecraft Server

---

### Weekly Server Maintenance [ SUN ]

##### ATM9 Instance Scheduler

- 07:(50/55/59):00 UTC
    - Send Messages To:
        - ATM9 Instance
        - Players Discord

- 08:00:00 UTC
    - Send Messages To:
        - ATM9 Instance
        - Players Discord
    - Wait 10s ( **Roughly 08:00:10 UTC** )
    - Stop Minecraft Server
    - Wait 60s ( **Roughly 08:01:10 UTC** )
    - Send Messages To:
        - Players Discord
    - Take a Backup
    - Wait 120s ( **Roughly 08:04:00 UTC** )
    - Send Messages To:
        - Players Discord

##### AMP Application Scheduler

- 08:30:00 UTC
    - Send messages To:
        - Players Discord
    - Take A Backup
    - Update the application and restart it if it was previously running

##### Ansible Scheduler

- 09:00:00 UTC
    - Send Messages To:
        - Players Discord
    - Perform Dist. Upgrade
    - Remove dependencies
    - Send Messages To:
        - Players Discord
    - Restart Game Server

##### ATM9 Instance Scheduler

- 09:30:00 UTC
    - Send Messages To:
        - Players Discord
    - Start Minecraft Server

---

# Triggered Events

### ATM9 Instance Triggered Events

##### A backup finished archiving

- Send Messages To:
    - Players Discord

##### The Minecraft Server Repeatedly Fails To Start

- Send Messages To:
    - Players Discord
    - HomeLab Discord

##### The Minecraft Server Stop Unexpectedly

- Send Messages To:
    - Players Discord
    - HomeLab Discord