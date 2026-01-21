# Vim Cheatsheet

## Vim Motions

ensure you are in command/normal mode, not insert or ex mode.

### Navigation Through Text

- `gg`	->	Go to the begining of the buffer.
- `G`	->	Go to the end of the buffer.
- `0`	->	Go to the beginning of the line(note this is a zero, not a capital letter 'O').
- `$`	->	Go to the end of the line.
- `w`	->	Go forward one word.
- `b`	->	Go back one word.
- `h`	->	Go left.
- `j`	->	Go down.
- `k`	->	Go up.
- `l`	->	Go right.
- `)`	->	Go forward one senctence.
- `(`	->	Go back one sentence.

motions can take a `{count]` to indicate how many motions you want to make, such as `3w` to move forward three words.

### Inserting Text at Specific Positions

- `i`	->	Insert at cursor.
- `I`	->	Insert before the first non-whitespace character in the current line
- `a`	->	Append text after the cursor.
- `A`	->	Append text at the end of the current line.
- `o`	->	Open a new line below the postition.
- `O`	->	Open a new line above the current line.

### Operating on a Range of Text
a Vim operator is any command that can be applied to a range of text. you can combine operators with counts and motions to rapidly manipulate a specific
part of the buffer.

#### essential Vim operators
- `c`	->	Change the range; that is, delete the characters and move into insert mode at the beginning of the range.
- `d`	->	Delete the range.
- `y`	->	Yank the range; that is, copy it to a register(Vim's version of a clipboard) ready to paste later.
- `g~`	->	Invert the range case(change uppercase character to lowercase character and vice versa.
- `gU`	->	Make the range uppercase("go upper")
- `gu`	->	Make the range lowercase("go lower")
- `!`	->	Send the range through an external program.

you can also quickly apply these operators just type them twice

### Search for Text Patterns
with search motions you can quickly select a range of character for an operator to perform on.

#### essential search motions
- `fcharacter`	->	Move forward to(onto) character.
- `Fcharacter`	->	Move backward to(onto) character.
- `tcharacter`	->	Move forward to just before character.
- `Tcharacter`	->	Move backward to just before character.






