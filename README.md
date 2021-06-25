# [Domq GDB](https://github.com/domq/homebrew-gdb)
Backported 8.0.1 GDB based on v10.1 working locally on MacOS and for remote debugging on the Mac from Visual Studio on Windows.

Based heavily on https://github.com/domq/homebrew-gdb, here only with updated installation instructions and links.
Thank you very much for your great work and help, [@domq](https://github.com/domq). Please continue to prefer using [the original](https://github.com/domq/homebrew-gdb).

## How do I install GDB for MacOS?
1. [Install Homebrew](https://docs.brew.sh/Installation)
2. `brew install --force --build-from-source vegz78/gdb/gdb`

See here for further details about setup and signing of GDB on your Mac:
- https://gist.github.com/mike-myers-tob/9a6013124bad7ff074d3297db2c98247
- https://dev.to/jasonelwood/setup-gdb-on-macos-in-2020-489k#command-file
- https://docs.microsoft.com/en-us/cpp/linux/deploy-run-and-debug-your-linux-project (no gdbserver)
- https://docs.microsoft.com/en-us/cpp/build/configure-cmake-debugging-sessions

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

## Disclaimer
Any usage of this repo is [on one's own responsibility](https://www.merriam-webster.com/dictionary/on%20one%27s%20own%20responsibility).
