Description:
  Convert files to PNG files.

Usage:
  twopng [options] file...

Options:
  -d, --delete
    Delete the source file (and it's accompanying jpg file if one is present).
    This option is disabled by default.
  -f, --force
    Overwrite existing files. Disabled by default.
    If more than one of -f and -n are specified then only the final one takes
    effect.
  -n, --no-clobber
    Do not overwrite files. Enabled by default.
    If more than one of -f and -n are specified then only the final one takes
    effect.
  -h, --help
    Display this help message and exit.

Examples:
  twopng -d foo.dng bar.dng

Version:
  2png 1.0.0.0
  Copyright (C) 2017 Nathan Shearer
  Licensed under GNU General Public License 2.0
