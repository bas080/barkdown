# Barkdown

Demonstrate the execution of terminal commands easily.

Instead of typing out or copy pasting the commands and their outputs you can
have barkdown do that for you.

## Usage

Take this document; it is generated using barkdown.

Simply start the line with a `$` (dollar sign) followed by a command. Let's
see what this README looks like before running it through `barkdown`.

> Prefixed with two spaces to prevent confusing the $ of the file for
  a command.

```
$ sed 's/^/\  /g' < ./README.bd
  #!./barkdown

  # Barkdown

  Demonstrate the execution of terminal commands easily.

  Instead of typing out or copy pasting the commands and their outputs you can
  have barkdown do that for you.

  ## Usage

  Take this document; it is generated using barkdown.

  Simply start the line with a `$` (dollar sign) followed by a command. Let's
  see what this README looks like before running it through `barkdown`.

  > Prefixed with two spaces to prevent confusing the $ of the file for
    a command.

  `$ sed 's/^/\  /g' < ./README.bd`

  ## License

  GNU General Public License 3.0
```

## License

GNU General Public License 3.0
