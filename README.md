cha-cli
=======
> The Cha command line interface application.

Install this globally and you'll have access to the `cha` command anywhere on your system.

```shell
npm install -g cha-cli
```
## CLI Options

- `-v` or `--version` will display the CLI and local cha versions
- `--require <module path>` will require a module before running the chafile. This is useful for transpilers but also has other applications. You can use multiple `--require` flags
- `--chafile <chafile path>` manually set path of chafile. Useful if you have multiple chafiles. This will set the CWD to the chafile directory as well.
- `--cwd <dir path>` manually set the CWD. The search for the chafile, as well as the relativity of all requires will be from here.
- `--no-color` will disable colored output.
