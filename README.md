# base2tone-tilix

[Base2Tone](https://base2t.one/) color schemes for the [Tilix](https://gnunn1.github.io/tilix-web/) terminal.

## Installation

Clone this repo and then copy the color scheme files to `~/.config/tilix/schemes`:

```
git clone https://gitlab.com/drkrynstrng/base2tone-tilix
cd base2tone-tilix/schemes
mkdir -p ~/.config/tilix/schemes
cp *.json ~/.config/tilix/schemes
```

## Usage

First, if needed, restart Tilix after installing the color scheme files.

Then, within Tilix, go to `Preferences` and create a new profile or modify an existing profile. On the `Color` tab for the profile, use the `Color scheme` drop down menu to select a Base2Tone theme:

```
Preferences > Profile > Color > Color scheme
```

Finally, switch your terminal to this profile by using the drop down menu from the terminal title:

```
Terminal title > Profiles
```

You can also set this profile as the default profile in `Preferences`.

## License

[0BSD](LICENSE)
