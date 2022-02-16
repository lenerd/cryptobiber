# Cryptobiber - More efficient cryptobib with biblatex/biber

1. Have Python 3 installed.
2. Put the `cryptobiber` file in your `PATH` (or use an absolute path below).
3. Add the following line to your `latexmk` configuration file (either in `~/.latexmkrc` or
   `$XDG_CONFIG_HOME/latexmk/latexmkrc`:

```
$biber = 'cryptobiber %O %S %Y'
```
