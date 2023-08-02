# :floppy_disk:Saving files and exiting `vi`
When you are using vi, you can save your changes to a file, discard changes, save a file to another existing file, and lots of other file operation commands.
> This commands work only when you're in the command mode.

## Table of Contents

1. [Save an existing file](/vi/saving/save_current)
    - If you have opened a file called "example.txt" in `vi` and made some changes, you can save them by pressing "Esc" and type the command.
    This will save the changes to the file and exit `vi`.

2. [Save a new file](/vi/saving/save_new-file)
    - For example, if you want to save the file as "example2.txt", you can use the command in the link and the file will now be saved to disk.

3. [Quit vi](/vi/saving/quit_vi)
    - This command qiuts `vi` when there are no more pending operations to any changed file.

4. [Save and quit](/vi/saving/save_and_quit)
    - This will save the file and exit vi.

5. [Quit without saving](/vi/saving/quit_no-save)
    - To force quit `vi` without effecting the past changes to a file, you can use this command.

6. [Save to existing file forcefully](/vi/saving/save_to-existing-forcefully)
    - This command helps you to write contents of a file to replace an already existing file on disk.

**Note:** _The cursor moves to bottom of screen whenever a colon (:) is typed. This type of command is completed by hitting the <Return> (or <Enter>) key._ 