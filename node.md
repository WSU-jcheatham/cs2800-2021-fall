# Node and npm

Node is a JavaScript interpreter for the desktop (as opposed to browsers). Npm
is the Node Package Manager -- it lets you install libraries (packages) for
Node programs to use.

When you install Node, you also get npm. Corollary: to get npm, install Node.

## Ubuntu (WSL or standard Linux)

1. Open an Ubuntu prompt
2. Run `curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -`
3. Run `sudo apt-get install -y nodejs`
4. Run `npm -v` to verify that Node and npm are installed

If you are using Ubuntu in Windows and your session always opens as the root
user:

1. In Ubuntu, run `adduser someusername` (like `adduser jason`)
2. Fill out what it asks for
3. Run `usermod -G admin someusername`
4. In a Windows command prompt (not Ubuntu), run `ubuntu config --default-user
   someusername`

The next time you start Ubuntu, it should come up logged in as `someusername`.
At that point, install Node as described above.

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
