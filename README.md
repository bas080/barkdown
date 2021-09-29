# Deprecated

Instead have a look at [Markatzea][1].

# Barkdown

> **EXPERIMENTAL**

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
  #!/usr/bin/env barkdown
  
  # Deprecated
  
  Instead have a look at [Markatzea][1].
  
  # Barkdown
  
  > **EXPERIMENTAL**
  
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
  
  [1]:https://github.com/bas080/markatzea
```

## License

GNU General Public License 3.0

[1]:https://github.com/bas080/markatzea
