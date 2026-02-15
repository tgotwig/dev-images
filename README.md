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
  | atuin | For shell history. | `atuin search git` |
  | bat | For syntax-highlighted cat. | `bat file.txt` |
  | cc | For compiling C code. | `cc main.c -o main` |
  | curl |  |  |
  | docker | For container CLI. | `docker ps` |
  | dust | For disk usage. | `dust .` |
  | fd | For fast file search. | `fd "*.md"` |
  | fish | Bash replacement with lots of auto-completions.  |  |
  | git |  |  |
  | gnupg | For managing GPG keys. | `gpg --list-keys` |
  | ip | For getting host IPs. | `ip a` |
  | jq | For querying JSON. | `jq . file.json` |
  | less | For paging long output. | `less file.txt` |
  | lsd | For modern ls. | `lsd -la` |
  | mediainfo | For inspecting media metadata. | `mediainfo file.mp4` |
  | micro | Lightweight terminal editor. | `micro file.txt` |
  | nc | For chatting or to check if port is open. | `nc -zv <host> <port>` |
  | nmap |  |  |
  | nslookup | For getting IPs from dns name. | `nslookup github.com <alt-dns-server>` |
  | ping |  |  |
  | rg | For fast text search. | `rg "todo"` |
  | sd | For modern sed. | `sd "foo" "bar" file.txt` |
  | ssh | For remote access. | `ssh user@host` |
  | starship |  For making the terminal prompt pretty 😊 |  |
  | task | For having a task runner. |  |
  | tree |  | `tree <folder>` |
  | unzip | For extracting zip files. | `unzip archive.zip` |
  | wget | For downloading files. | `wget <url>` |
  | z | For jumping into previously visited folders. | `z <part-of-folders-path>` |
</details>

## Implementation status

| Command | Alpine | Node | Ubuntu |
| :-- | :--: | :--: | :--: |
| asdf | ❌ | ❌ | ✅ |
| atuin | ❌ | ❌ | ✅ |
| bat | ❌ | ❌ | ✅ |
| cc | ❌ | ❌ | ✅ |
| curl | ✅ | ✅ | ✅ |
| docker | ❌ | ❌ | ✅ |
| dust | ❌ | ❌ | ✅ |
| fd | ❌ | ❌ | ✅ |
| fish | ✅ | ✅ | ✅ |
| git | ❌ | ❌ | ✅ |
| gnupg | ❌ | ❌ | ✅ |
| ip | ✅ | ✅ | ✅ |
| jq | ❌ | ❌ | ✅ |
| less | ❌ | ❌ | ✅ |
| lsd | ❌ | ❌ | ✅ |
| mediainfo | ❌ | ❌ | ✅ |
| micro | ❌ | ❌ | ✅ |
| nc | ✅ | ✅ | ✅ |
| nmap | ❌ | ❌ | ✅ |
| nslookup | ✅ | ✅ | ✅ |
| ping | ✅ | ✅ | ✅ |
| rg | ❌ | ❌ | ✅ |
| sd | ❌ | ❌ | ✅ |
| ssh | ❌ | ❌ | ✅ |
| starship | ✅ | ✅ | ✅ |
| task | ❌ | ❌ | ✅ |
| tree | ❌ | ❌ | ✅ |
| unzip | ❌ | ❌ | ✅ |
| wget | ✅ | ✅ | ✅ |
| z | ✅ | ✅ | ✅ |

Commands which look different:

- nc
- nslookup
- ping
- wget
