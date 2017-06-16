# Install Ruby on Rails

- [macOS install](#mac-os)
- [Ubuntu/Linux install](#ubuntu)
- [Windows install](#windows)

![macOS logo](/assets/images/macos.png)
<a id="mac-os"></a>
### macOS install

#### Install rbenv (ruby environment)
[rbenv](https://github.com/rbenv/rbenv) is a ruby version manager similar to [rvm](https://rvm.io/) however rbenv works on both Mac & Linux. If you have to learn something - it's nicer to learn something that covers two environments rather than one in case you ever need to use it in a linux environment.

1. Install [brew](https://brew.sh/) if you haven't already
2. Install rbenv (Terminal app)
  ```
  brew install rbenv
  ```
3. Setup rbenv
  ```
  rbenv init
  ```
4. Add rbenv to your *~/.bash_profile*
  ```
  echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
  echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
  ```
5. Reopen the terminal and install ruby
  ```
  rbenv install 2.4.1
  ```
6. Setup the version of Ruby you wish to use
  ```
  rbenv local 2.4.1
  ```
7. Optional: Install Ruby On Rails
  ```
  gem install rails --version 5.1.1 --no-ri --no-rdoc && rbenv rehash
  ```
  Type ```rails -v``` to test your version


<a id="ubuntu"></a>
![ubuntu logo](/assets/images/ubuntu.png)
### Ubuntu Install

![windows logo](/assets/images/windows.png)
<a id="windows"></a>
### Windows Install
