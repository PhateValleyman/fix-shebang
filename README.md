# Termux Fix Shebang
This script is designed to rewrite shebangs for Termux
to run scripts properly under the Termux environment.
Termux is a terminal emulator and Linux environment for Android.

## Options:
-a, --all
Edit shebang of every file in all subdirectories.

-h, --help
Display usage information.

## Examples:
To fix the shebang of a single file:
termux-fix-shebang script.sh

To fix the shebang of every file in all subdirectories:
termux-fix-shebang --all

## Notes:
Make sure to set the script as executable before running it:
chmod +x termux-fix-shebang
Always use caution when modifying shebang lines, as incorrect
changes could render scripts unusable.
