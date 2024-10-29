# Personal Keyboard Remapping For Productivity

The containing `json` file is a configuration file to be used with a Linux
software called [Input Remapper](https://github.com/sezanzeb/input-remapper).

Carefully designed to enhance personal productivity. The configuration is
designed to use `CapsLock` key as the super key to run the recorded key
mapping. It also provides multiple mode, which enable same keys to play
different recorded keys-auto-play.

I also use `Lazyvim` and most of the key configurations are specific for `Lazyvim`
only.

- `CapsLock` = `Super` key
- `Super + 7` = Switch to `Default Mode`
- `Super + 8` = Switch to `Alacritty Mode`
- `Super + 9` = Switch to `Lazyvim Window Mode`
- `Super + f` = Toggle recent mode

## Default Mode `Super + 7`

| Mapping     | Description                                   |
| ----------- | --------------------------------------------- |
| `Super + j` | Toggle first workspace and second workspace   |
| `Super + ;` | Toggle third workspace and recent workspace   |
| `Super + k` | Fix format issue caused by flutter-tools.nvim |
| `Super + l` | Show current file fullname with path          |
| `Super + u` | Trigger `Ctrl + n`                            |
| `Super + p` | Trigger `Ctrl + p`                            |
| `Super + i` | Navigate forward                              |
| `Super + o` | Navigate backward                             |
| `Super + y` | Scroll up lazyvim by half                     |
| `Super + h` | Scroll down lazyvim by half                   |
| `Super + n` | Restart flutter                               |
| `Super + m` | Reload flutter                                |
| `Super + ,` | Save current buffer                           |
| `Super + .` | Trigger backtick `                            |

## Alacritty Mode `Super + 8`

| Mapping     | Description                          |
| ----------- | ------------------------------------ |
| `Super + u` | Toggle alacritty `Lock` mode         |
| `Super + n` | Create new tab                       |
| `Super + m` | Rename current tab                   |
| `Super + p` | Toggle Alacritty's floating terminal |
| `Super + i` | Open new pane in horizontal split    |
| `Super + o` | Open new pane in vertical split      |
| `Super + h` | Jump to the left pane or tab         |
| `Super + l` | Jump to the right pane or tab        |
| `Super + k` | Jump to the down pane                |
| `Super + j` | Jump to the top pane                 |

## Lazyvim Window Mode `Super + 9`

| Mapping     | Description                          |
| ----------- | ------------------------------------ |
| `Super + j` | Shrink current window horizontally   |
| `Super + k` | Expend current window horizontally   |
| `Super + ,` | Shrink currnet window vertically     |
| `Super + .` | Expend current window vertically     |
| `Super + i` | Create a new horizontal split window |
| `Super + o` | Create a new vertical split window   |
