# :keyboard: [Command Mode](command_mode)
> Commands which cause an action to be taken on a file.

The following commands cause an action to be taken on a file.

Characters typed acts as a command to the file being edited when in command mode.

## Navigating the `vi` CLI
> `vi` was designed with the QWERTY Keyboard (with no arrow keys) in mind, so using the arrow keys (:arrow_up_down:, :left_right_arrow:) to navigate `vi` might sometimes act strangely, they should be avoided at all cost.

The key commands listed bellow will help you navigate `vi` effectly in **[Command Mode.](README.md)**

These are some basic movement keys that can help navigate through files and text within the `vi` editor

> - Take them as your modern D-PAD

1. **:arrow_up: [Move one line up](move_line-up)**
    - Move the cursor above the current line to the next one from the current cursor position.

1. **:arrow_right: [Move character to the right](move_char-right)**
    - This command moves the cusor forward after a(one) character to the right from current position.

1. **:arrow_down: [Move one line down](move_line-down)**
    - Learn how to move the cursor down from the current line to the next line with this command.

1. **:arrow_left: [Move character to the left](move_char-left)**
    - You can move the cusor backwards after a character to the left using this command.

### More on navigation

1. **:fast_forward: [Move from one word to the right](move_word-right)**
    - This command moves the cursor to the beginning of the next word to the right

1. **:rewind: [Move from one word to the left](move_word-left)**
    - To move the cursor back to the beginning of the previous word on the left, use this command.

1. **:previous_track_button: [Start of line](line_start)**
    - Use this command to take the cursor to the start of a line from the current cursor position.

1. **:next_track_button: [End of the line](line_end)**
    - Move the cursor from the current position to the end of the current line with this command.

### Manipulating texts in `vi`
> **Here's an overview of various ways we can manipulate our texts inside `vi`**

Unlike some PC editors, you cannot replace or delete text by highlighting it with the mouse. Instead use the `vi` commands in the following list.


1. **:scissors: [Copy or cut content into buffer](copy_line)**
    - This command will help you copy a full line of texts into the buffer before pasting.

1. **:x: [Delete line](delete_line)**
    - Delete an entire line of texts at the current cursor position with this command.

1. **:clipboard: [Paste](paste)**
    - Lines, or words copied into the buffer can be paste with this command.

1. **:bookmark_tabs: [Copy word](copy_word)**
    - Copying a word in `vi` is easier with this command.
    > You can copy number of words by adding the number with the command (Nyw)

1. **:no_entry: [Delete word](delete_word)**
    - How to delete the single word beginning with the character under the cursor has been made easier by using the following commad.
    > To delete a number of words at the same time, add the number to the command, like this (Ndw)

1. **:no_entry_sign: [Delete a character](delete_character)**
    - Use this command to delete just a character in `vi`.
    
1. **:leftwards_arrow_with_hook: [Undo/Redo Toggle](undo-redo)**
    - This works more like a toggle. Use this command to Undo and Redo your most recent action. 
    > You cannot go back more than one step.

**Click on the links to view each commands.**

**:point_down::point_down:**

**If there are any errors while executing these commands please let me know so that I can correct them.**

## Thank you
Feel free to recommed more new commands as they come to you, you can always reach me on [Discord.](https://discord.com/users/982980024950997073)

These are just the basics, but there is more to this commands and can be found [here](https://www.cs.colostate.edu/helpdocs/vi.html)

[Go back](../README.md)