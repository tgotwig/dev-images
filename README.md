# dev-images

A collection of minimal, ready-to-use Docker images with essential CLI tools for developers (amd64 and arm64).

<img src="https://github.com/user-attachments/assets/16c25a38-4b6f-47ac-8fc5-5faa28ce573e" width="300">

| Image                                               | OS  | CMD |
| :--                                                 | :-- | --- |
| [alpine](https://github.com/tgotwig/alpine)         | alpine 3.21 | docker run -it --rm tgotwig/alpine |
| [node](https://github.com/tgotwig/node) 23.5.0      | alpine 3.21 | docker run -it --rm tgotwig/node fish |
| [ubuntu](https://github.com/tgotwig/ubuntu)         | ubuntu 24.04 | docker run -it --rm tgotwig/ubuntu |

<details>
  <summary>📃 List of commands which should be everywhere (click me)</summary>

  | Command | Note | Sample |
  | :-- | :-- | :-- |
  | asdf | For installing programming languages. |  |
  | cc | For compiling C code. |  |
  | curl |  |  |
  | fish | Bash replacement with lots of auto-completions.  |  |
  | git |  |  |
  | ip | For getting host IPs. | `ip a` |
  | jq |  |  |
  | less |  |  |
  | mediainfo |  |  |
  | micro |  |  |
  | nc | For chatting or to check if port is open. | `nc -zv <host> <port>` |
  | nmap |  |  |
  | nslookup | For getting IPs from dns name. | `nslookup github.com <alt-dns-server>` |
  | ping |  |  |
  | starship |  For making the terminal prompt pretty 😊 |  |
  | task | For having a task runner. |  |
  | tree |  | `tree <folder>` |
  | wget | For downloading files. | `wget <url>` |
  | z | For jumping into previously visited folders. | `z <part-of-folders-path>` |
</details>

## Implementation status

| Command | Alpine | Node | Ubuntu |
| :-- | :--: | :--: | :--: |
| asdf | ❌ | ❌ | ✅ |
| cc | ❌ | ❌ | ❌ |
| curl | ✅ | ✅ | ✅ |
| fish | ✅ | ✅ | ✅ |
| git | ❌ | ❌ | ✅ |
| ip | ✅ | ✅ | ✅ |
| jq | ❌ | ❌ | ❌ |
| less | ❌ | ❌ | ❌ |
| mediainfo | ❌ | ❌ | ❌ |
| micro | ❌ | ❌ | ❌ |
| nc | ✅ | ✅ | ✅ |
| nmap | ❌ | ❌ | ✅ |
| nslookup | ✅ | ✅ | ✅ |
| ping | ✅ | ✅ | ✅ |
| starship | ✅ | ✅ | ✅ |
| task | ❌ | ❌ | ✅ |
| tree | ❌ | ❌ | ❌ |
| wget | ✅ | ✅ | ✅ |
| z | ✅ | ✅ | ✅ |

Commands which look different:

- nc
- nslookup
- ping
- wget
