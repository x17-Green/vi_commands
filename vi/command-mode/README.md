# :keyboard: [Command Mode](vi/command-mode/README.md)
> Commands which cause an action to be taken on a file.

The following commands cause an action to be taken on a file.

Characters typed acts as a command to the file being edited when in command mode.

## command mode commands
1. start of line (0)
1. end of the line ($)
1. copy line (yy)
1. delete line (dd)
1. paste (p)
1. copy word (yw)
1. delete word (dw)
1. delete character (x)
1. undo/redo toggle (u)

## Moving the cursor
> `vi` was designed with the QWERTY Keyboard (with no arrow keys) in mind, so using the arrow keys (:arrow_up_down:, :left_right_arrow:) to navigate `vi` might sometimes act strangely, they should be avoided at all cost.
The key commands listed bellow will help you navigate `vi` effectly in **[Command Mode.](/vi/command-mode/README.md)**
> - Take them as your modern D-PAD

1. **:arrow_up: [Move line up](/vi/command-mode/move_line-up)**
    - Move the cursor up to the next line from the current position.
1. **:arrow_right: [Move character right](/vi/command-mode/move_char-right)**
    - This command moves the cusor to the right one character forward from current cursor position.
1. **:arrow_down: [Move line down](/vi/command-mode/move_line-down)**
    - This command moves the cursor down to the next line from the current position.
1. **:arrow_left: [Move character left](/vi/command-mode/move_char-left)**
    - This command moves the cusor to the left one character backwards.
1. **:fast_forward: [Move from word to right](/vi/command-mode/move_word-right)**
    - This command moves cursor to beginning of next word to the right
1. **:rewind: [Move from word to left](/vi/command-mode/move_word-left)**
    - This command moves the cursor back to beginning of preceding word on the left

## Thank you
Feel free to recommed more new commands as they come to new, you can reach me on [Discord.](https://discord.com/users/982980024950997073)

These are just the basics, but there is more to this commands and can be found [here](https://www.cs.colostate.edu/helpdocs/vi.html)