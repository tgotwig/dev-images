# dev-images

A collection of minimal, ready-to-use Docker images with essential CLI tools for developers.

<img src="https://github.com/user-attachments/assets/16c25a38-4b6f-47ac-8fc5-5faa28ce573e" width="300">

<details>
  <summary>📃 [WiP] List of commands which should be everywhere, but currently not (click me)</summary>

  | Command | Note | Sample |
  | :-- | :-- | :-- |
  | asdf | For installing programming languages. |  |
  | curl |  |  |
  | fish | Replacement for bash with lots of auto-completions.  |  |
  | ip | For getting host IPs. | `ip a` |
  | nc | For chatting or to check if port is open. | `nc -zv <host> <port>` |
  | nmap |  |  |
  | nslookup | For getting IPs from dns name. | `nslookup github.com <alt-dns-server>` |
  | ping |  |  |
  | starship |  For making the terminal prompt pretty 😊 |  |
  | z | For jumping into previously visited folders. | `z <part-of-folders-path>` |
</details>

| Image                                               | OS  | Additions | CMD |
| :--                                                 | :-- | :--       | --- |
| [alpine](https://github.com/tgotwig/alpine)         | alpine 3.21 | curl, fish, starship, zoxide | docker run -it --rm tgotwig/alpine |
| [node](https://github.com/tgotwig/node) 23.5.0      | alpine 3.21 | fish, starship, zoxide | docker run -it --rm tgotwig/node fish |
| [ubuntu](https://github.com/tgotwig/ubuntu)         | ubuntu 24.04 | curl, dnsutils (delv, dig, host, nslookup), fish, iproute2 (bridge, ctstat, ip, lnstat, nstat, rtmon, ss, tc), nc, nmap, ping, starship, z | docker run -it --rm tgotwig/ubuntu |
