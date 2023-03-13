# LEARNING THE SHELL

## what is the shell

`program that takes keyboard commands and passes them to the operating system to carry out`

- Almost all Linux distributions supply a shell program from the GNU Project called bash.
- The name bash is an acronym for Bourne Again Shell
- The name bash is an acronym for Bourne Again Shell

## Terminal Emulators

- When using a graphical user interface, we need another program called
  a terminal emulator to interact with the shell.
- If we look through our desktop menus, we will probably find one
- KDE uses konsole and GNOME uses
  gnome-terminal
- though it’s likely called simply “terminal” on our menu
- . A
  number of other terminal emulators are available for Linux, but they all do
  basically the same thing: give us access to the shell
- You will probably develop
  a preference for one or another based on the number of bells and whistles
  it has.

## Your First Keystrokes

So let’s get started. Launch the terminal emulator! Once it comes up, yo u
should see something like this: <br><br>

<p align = "center">
  <code>
  [me@linuxbox ~]$
  </code>
</p>

- This is called a shell prompt, and it appears whenever the shell is ready to accept input
- While it may vary in appearance somewhat, depending on the distribution
- it will usually include your username@machinename, followed by the current working directory (more about that in a little bit) and a dollar sign.
- If the last character of the prompt is a hash mark (#) rather than a dollar sign, the terminal session has superuser privileges.
- This means that either we are logged in as the root user or we’ve selected a terminal emulator that provides superuser (administrative) privileges.

## Command History

- If we press the up-arrow key, we see that the previous command reappears after the prompt
- Most Linux distributions remember the last 500 commands by default
- Press the down-arrow key, and the previous command disappears

## copy and paste

[راجعها ولخصها بشكل أفضل]

- If you highlight some text by holding down the left mouse button and dragging the mouse over it (or double-clicking a word), it is copied into a buffer maintained by X. Pressing the middle mouse button will cause the text to bepasted at the cursor location

## Simple Commands

- _data: This command displays the current time and date:_

```shell
[me@linuxbox ~]$ date
Thu Oct 25 13:51:54 EDT 2012
```

- _cal: displays a calendar of the current month:_

```shell
[me@linuxbox ~]$ cal
 October 2012
Su Mo Tu We Th Fr Sa
 1 2 3 4 5 6
 7 8 9 10 11 12 13
14 15 16 17 18 19 20
21 22 23 24 25 26 27
28 29 30 31
```

- _df: To see the current amount of free space on your disk drives_

```shell
[me@linuxbox ~]$ df
```

- _free: to display the amount of free memory_

```shell
[me@linuxbox ~]$ free
```

## Ending a Terminal Session

- We can end a terminal session by either closing the terminal emulator window or entering the exit command at the shell prompt:

```shell
[me@linuxbox ~]$ exit
```
