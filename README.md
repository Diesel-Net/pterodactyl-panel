[![Build Status](https://drone.kiwi-labs.net/api/badges/Diesel-Net/pterodactyl-panel/status.svg)](https://drone.kiwi-labs.net/Diesel-Net/pterodactyl-panel)

# pterodactyl-panel

[pterodactyl.io](https://pterodactyl.io/) Panel on Docker Swarm. Deployed and used in-conjunction with the [Wings](https://github.com/Diesel-Net/pterodactyl-wings) agents.

[Official Docker Image](https://github.com/pterodactyl/panel/pkgs/container/panel)


Run this comman inside the panel container to set up the first admin user credentials.

```bash
php artisan p:user:make
```
