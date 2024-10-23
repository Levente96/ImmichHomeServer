# ImmichHomeServer
Guide on setting up a cost and energy efficient self hosted Immich server.

## Building the server
### Hardware
1. Raspberry Pi 4 (4Gb+)
2. 2.5" HDD (2 of the same capacity)
3. External HDD cases (2)
4. USB Y cable (2)
5. Power supply
6. 3D Printed case (*optional*)
7. Fan (*optional but recommended*)
### Software
1. OS
2. Log2Ram
3. MDADM
4. Docker(compose)
5. Immich
6. Management scripts
7. Exposing to internet - NGINX Proxy Manager
8. Exposing to internet - Fail2ban

---

#### OS
For ease of use I went with Ubuntu server. It is really easy to set it up on an SD card with a multitude of tools for raspberry.

#### Log2Ram
One of the most important tool for increasing the lifetime of the memory card. It is an opensource project with a good description on [how to set it up](https://github.com/azlux/log2ram).

#### MDADM
// TODO

Mount the raid to `/mnt/md0`

#### Immich
Managing the photo backup [Immich](https://github.com/immich-app/immich)
//TODO
