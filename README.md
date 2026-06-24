# Marathon Starship Theme
A Starship configuration inspired by **Marathon** by Bungie.
<img width="473" height="52" alt="image" src="https://github.com/user-attachments/assets/dae01508-863c-4e0d-af0b-ffde5954e262" />

---

## Features

- os, root, path, git, devenv/direnv, status, dotnet, rust, go, python, time

---

## VARIANTS

<details>
<summary>Arachne</summary>
<br>
<img width="277" height="59" alt="image" src="https://github.com/user-attachments/assets/8938df5e-3918-4cff-bddb-9a24cf12ccfa" />
</details>
<details>
<summary>CyberAcme</summary>
<br>
<img width="277" height="51" alt="image" src="https://github.com/user-attachments/assets/730182f7-7820-4e1f-a14d-1aeb096c7f1e" />
</details>
<details>
<summary>NuCaLoric</summary>
<br>
<img width="275" height="51" alt="image" src="https://github.com/user-attachments/assets/a38255b9-6aa0-4439-b464-51bf28a25bc2" />
</details>
<details>
<summary>Sekiguchi</summary>
<br>
<img width="278" height="51" alt="image" src="https://github.com/user-attachments/assets/4f89145b-05cf-430c-a832-4b70544917a6" />
</details>
<details>
<summary>Traxus</summary>
<br>
<img width="284" height="53" alt="image" src="https://github.com/user-attachments/assets/95ae2354-3878-415c-909b-f13c44af223d" />
</details>
<details>
<summary>MIDA</summary>
<br>
<img width="278" height="54" alt="image" src="https://github.com/user-attachments/assets/ed048e56-917d-4e1a-a85d-611b301ab096" />
</details>

## Requirements

Before using this theme, make sure you have:

* [Oh My Posh](https://ohmypo.sh/) installed
* [A Nerd Font](https://www.nerdfonts.com/font-downloads) installed and configured in your terminal (or fonts that that support for Nerdfont's icons)

---

## Installation

Replace `starship.toml` in `~/.config` or if you don't want to override the default, place it anywhere and
do `export STARSHIP_CONFIG=~/example/non/default/path/marathon.toml` or your reguinal equivalent.

If everything went correctly, the prompt should show after your next command.

---

## Preview

SOON

--- 

## Customization

You can switch between the main `marathon` theme and the 6 faction themese by setting `palette` to:
- `marathon`
- `arachne`
- `cybercane`
- `mida`
- `nucaloric`
- `sekiguchi`
- `traxus`

Changes should take effect immediately.

---

## Notes

This theme was originally created at [valkyrieglasc/marathon-ohmyposh-config](https://github.com/valkyrieglasc/marathon-ohmyposh-config).
I liked it so i just blatantly ported it to Starship. There are a few differences from theirs due to needs and support (eg: no direnv support in omp)
