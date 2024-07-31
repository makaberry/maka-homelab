# makablab
Makaberry's Homelab Dump

<img src="https://github.com/user-attachments/assets/456dedf1-89f2-435d-a817-e1500f6d1711" height="500"> <img src="https://github.com/user-attachments/assets/521dd89f-bcdf-4212-b7cd-35de0e95a3ae" height="500">

Network:
  1. unifi express
  2. unifi switch lite 16 poe

Compute:
  1. raspberry pi 5 [yamper]
     - pi os lite x64 (debian 12 bookworm)
       - glances
       - docker
           - portainer
           - tailscale (subnet router)
           - homepage
           - pihole
           - uptime-kuma
  2. raspberry pi 5 [nickit]
      - pi os lite x64 (debian 12 bookworm)
        - glances
        - docker
            - portainer agent
            - pihole
            - gluetun
            - qbittorrent
            - sonarr
            - radarr
  3. lattepanda mu [mantine]
       - proxmox ve
         - glances
         - proxmox backup server lxc
         - syncthing lxc
         - home assistant lxc
         - scrypted lxc (igpu + tpu map)
         - jellyfin lxc (igpu map)
  4. itx nas [corsola]
       - truenas scale
         - glances

IoT:
  1. 4 x tp-link tapo c110 wifi camera
  2. tp-link kasa hs100 wifi 6-outlet surge protector
  3. 4 x thirdreality zigbee smart plug
  4. thirdreality zigbee temp + humidity sensor
  5. apple homepod mini (homekit / thread hub)
  6. apple tv 4k (homekit / thread hub)

Rack:
  1. deskpi rackmate t1
       - patch panel
       - sbc shelf
       - itx shelf
       - lots of standard shelves
       - lots of 1u spacers
       - 3 x noctua nf-a12x15 + linkup 4-pin pwm to usb cable
       - lots of velcro tape
       - lots of zip ties
