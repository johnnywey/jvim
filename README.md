## jVIM Config ##

**Shamelessly copied from <https://github.com/wolandark/wim>**

- Install macvim: `brew install macvim`
- Install .vim_rc: Rename `vimrc` to `.vimrc` and move into home directory
- Install vim_plug: `curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`
- Install JetBrains Mono from <https://www.nerdfonts.com/font-downloads>
- `brew install vifm`
- `brew install ranger`
- iTerm Config:
    - Set Font to `JetBrains Mono NerdFont` `BOLD` at font size `15` (Settings->Profiles->Text)
    - Set `Report Terminal Type` to `xterm-256color` (Settings->Profiles->Terminal)
    - Load Color Preset `jVIM` (Settings->Profiles->Colors)
- Launch vim and run `:PluginInstall`

#### Keybindings ####
_`leader` is `space`_

|Keys              |Function               |
| --               | --                    |
| leader n         | NERDTree              |
| leader v         | Vifm Floating         |
| leader r         | Ranger Floating       |
| leader e         | Netrw On The Left Side |
| leader t         | Terminal              |
| leader i          |  Pop Start Menu   |
| leader T         | NewTab                |
| leader d         | Duplicate Cleaner     |
| leader m         | File History          |
| leader cc        | Comment Out           |
| leader 1-9       | Go To Tab             |
| leader tm        | Move Tab              |
| leader x         | Close Tab             |
| leader c         | Fuzzy Colorschemes    |
| leader b         | Fuzzy Buffers         |
| leader s         | Fuzzy File Search     |
| leader W         | Fuzzy Windows         |
| leader H         | Fuzzy History         |
| leader M         | Fuzzy Mappings        |
| leader w         | Quick Save w!         |
| leader op        | Source Current File   |
| leader z          | Fix Spelling For 1 word |
| leader l          | Fix Spelling On 1 Line |
| Alt Arrows       | Go Tabs Right Or Left |
| Shift Arrows     | Resize Splits         |
| Ctrl hjkl/Arrows | Focus Between Splits  |
| F2               | Start Live Webserver  |
| F3               | Reload Live Webserver |
| F4               | Stop Live Webserver   |
| F6               | SpellCheck            |
| F8               | Markdown Live Server  |
| END              | Trigger Snippets       |
|Ctrl j k          | Move Within Triggered Snippet |
|Ctrl PGDNN        | List Available Snippets  |
|V mode c-p | Copies To Shared Clipboard |
|V mode c-v | Pastes From Shared Clipboard | 
