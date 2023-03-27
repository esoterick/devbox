# devbox install

Starts a new devbox shell and installs all packages mentioned in devbox.json in current directory ora directory specified via --config. 

Then exits the shell when packages are done installing.

```bash
devbox install [flags]
```

## Options

```bash
  -c, --config string   path to directory containing a devbox.json config file
  -h, --help            help for install
  -q, --quiet   Quiet mode: Suppresses logs.
```