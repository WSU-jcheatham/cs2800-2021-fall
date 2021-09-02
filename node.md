# Node and npm

Node is a JavaScript interpreter for the desktop (as opposed to browsers). Npm
is the Node Package Manager -- it lets you install libraries (packages) for
Node programs to use.

## Ubuntu (WSL or standard Linux)

1. Open an Ubuntu prompt
2. Run `curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -`
3. Run `sudo apt-get install -y nodejs`
4. Run `npm -v` to verify that Node and npm are installed

## Windows

1. Download the Windows installer from https://nodejs.org/en/download/
2. Run the installer
3. **Open a new command prompt or PowerShell prompt**
4. Run `npm -v` to verify that Node and npm are installed

## Mac

### Homebrew

1. Run `brew install node`
2. Run `npm -v` to verify that Node and npm are installed

### Installer

1. Download the macOS installer from https://nodejs.org/en/download/
2. Run the installer
3. **Open a new terminal**
4. Run `npm -v` to verify that Node and npm are installed
