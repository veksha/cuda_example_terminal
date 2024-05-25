# ExTerminal

Advantages over Terminal+ plugin:

- `ExTerminal` tries to mimic real interactive terminal behaviour.
 That means that you can use apps like nano/vim/htop/python inside it.

# Commands in "Plugins / ExTerminal" menu:

- New terminal
- Close all terminals
- Run selection from editor
- Run current file
- Toggle focus terminal/editor
- CD to current file's directory

# Configuration file

Menu item "Options / Settings-plugins / ExTerminal / Config" opens file "plugins.ini" with `[exterminal]` section.

Setting               | Possible values            | Description
----------------------|----------------------------|----------------------------
shell_*               | string                     | shell to execute, for example - "bash" or "cmd.exe"
colors                | 0,1                        | enable terminal colors. (slows down terminal. will be optimized in the future.)
esc_focuses_editor    | 0,1                        | focus editor by pressing ESC key instead of sending it to terminal. Disabled by default. <br> Hint: Ctrl+[ key sends ESC code to the terminal, you can use it instead of ESC key
show_caption          | 0,1                        | show terminal header (title)
themed                | 0,1                        | use theme colors
ctrl_c                | 0,1                        | enable Ctrl+C (copy) in terminal
ctrl_x                | 0,1                        | enable Ctrl+X (cut) in terminal
ctrl_v                | 0,1                        | enable Ctrl+V (paste) in terminal
