# web-development-setup

Cheat sheats to setup web development environment on macOS

# Install and manage Ruby with rbenv on OSX

Install Homebrew

```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install rbenv

```bash
brew update
brew install rbenv ruby-build
```

Add rbenv to bash so that it loads every time you open a terminal

```bash
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile
```

List all available Ruby versions

```bash
rbenv install -l
```

Install Ruby

```bash
rbenv install 2.6.4
rbenv global 2.6.4
ruby -v
```

To select a particular ruby version to be used globally

```bash
rbenv global 2.3.1
```

Check for all the ruby versions that are installed on the system

```bash
ls ~/.rbenv/versions
```
