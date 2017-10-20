# Install Mac apps and tools via Brew Bundle

Install Homebrew using the below command first
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install Brew bundle to read and install dependencies from Brewfile
```shell
brew tap Homebrew/bundle
```

Install brew packages using brew bundle command below
```shell
git clone git@github.com:deepumukundan/Brewfiles.git
cd Common
brew bundle
cd ..
cd Personal
brew bundle
cd ..
cd Work
brew bundle
```
