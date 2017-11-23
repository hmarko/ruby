# ruby


## How to install Ruby?


  NOTE: This guide is a shorter version of [Ruby-lang.org](https://www.ruby-lang.org/en/documentation/installation) installation guides.

#### This depends on what Operating System you use:

  1. I have [Windows](#install-ruby-on-windows)
  1. I'm a cool guy with [Ubuntu](#install-ruby-on-ubuntu)
  1. I'm A solid develoepr running [centos](#install-ruby-on-centos)
  1. I'm an Apple addict with a [Mac](#install-ruby-on-mac)
  
### Install Ruby On Windows
1. Go to: [rubyinstaller.org](https://rubyinstaller.org/)
1. Click on "Download" and select the instellation that fits your Windows system architecture
1. Follow the install wizard till complete.


### Install Ruby On Ubuntu
*Install Ruby via apt*
Most recent ubuntu distibutuins have an up to date Debian for a working Ruby 2.3.x.

To install:
  1. Open the  Terminal (Ctrl + T) 
  1. Run the following:
  ```shell
  sudo apt-get install ruby-full
  ```
  
Alternatively, you can use either [RVM or rbenv](#what-is-rvm-or-rbenv) to install Ruvy on Ubuntu:

* To install RVM on Ubuntu go to [RMV.io](https://github.com/rvm/ubuntu_rvm) and follow the instalation instructions. 
* To install rbenv on Ubuntu click [here]() and follow the instructions.

### Install Ruby On Centos
The easiest way to install Ruby on centos is by using either [RVM or rbenv](#what-is-rvm-or-rbenv)

* To install RVM on centos go to [RMV.io](https://rvm.io/rvm/install#any-other-system) and follow the instalation instructions. 
* To install rbenv on centos click [here](https://gist.github.com/soardex/e95cdc230d1ac5b824b3) or [here](https://github.com/rbenv/ruby-build/wiki) and follow the instructions.

### Install Ruby On Mac
Currently the only way to install Ruby on Mac is by using either [RVM or rbenv](#what-is-rvm-or-rbenv)

* To install RVM on Mac go to [RMV.io](https://rvm.io/rvm/install#any-other-system) and follow the instalation instructions. 
* To install rbenv on Mac click [here](https://github.com/rbenv/ruby-build/wiki) and follow the instructions.

## Which Ruby version should I install?

Ruby 2.0 release was packed with some meaningfull changes compare to previous generations of 1.9.x versions. That is why any version above 2.0 is preferable.

nevertheless, some 2.x.x Ruby versions were also [buggy](https://github.com/e2/ruby_dep/issues/8) so you should pay close attention to the interperter when running your first Ruby command.

**Our recommendation:** Any version above **Ruby 2.3.1** (inclusive) will be a suitable choice.

## What is RVM or rbenv?

RVM & rbenv are two rival command line tools that are frequently used to install different Ruby versions. You can use either of the two to install your desired Ruby version with relative ease.

* To install Ruby using RVM go to [RMV.io](https://rvm.io/rvm/install#installation) and follow the instalation instructions.
* To install Ruby using rbenv go to [rbenv wiki on Github](https://github.com/rbenv/ruby-build/wiki) and follow the installation instructions.


## How do I check which ruby version was installed?
Open your cmd and run `ruby -v`
