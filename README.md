# Circles
*an esolang editor-slash-interpreter about clockwork, ring buffers, and self-destructive programming*

## Usage
Open the attached pages site to start using the editor. In the center is a circle; this is the current program.

### Editing a Program
Using the 'Edit' switch at the top right of the screen, you can enter Edit mode for the current program. On the left, a palette of the 30 available glyphs will appear. Consult the standard for each of their meanings. Clicking on one of the glyphs will select it; hovering over a valid location on the program will preview placement of that glyph. Click again to confirm placement. Selecting the single glyph with an X at the bottom of the palette enters Delete mode. Hovered glyphs are previewed for deletion; click again to confirm their removal. Once the program is ready, turn off the 'Edit' switch to end the editing.

### Running a Program
With edit mode turned off, click the 'Start' button to run the program. The program will execute until completion, but can be interrupted at any time with the 'Reset' button.

### I/O
When a procedure Reads from input, an editable text box will appear in the lower middle. Pressing Enter will submit the number to the program (see the Standard for more details).
When a procedure Prints to the output, text is added to the output log on the lower right side.

### Visual Controls
Scrolling or laptop zoom gestures zoom in and out of the program. Click-and-dragging or laptop pan gestures move around the program.

### Saving/Loading
Using Ctrl-C or Command-C copies a text version of the current program. This can be pasted into some other text editor to save programs. To restore a saved program, use Ctrl-V or Command-V to convert the text version to a program. If it does not succeed, the program is not formatted correctly.

## Standard
In progress!
