# Installing ImageMagick and Rmagick on OSX El Capitan

This repo shows how to get ImageMagick and Rmagick install on OSX 10.11 __without using Homebrew__.  

_Remark: source folder contains the tar balls I used_

## Install Xcode and OSX Development Tools from Apple

* Install XCode From AppStore
* Install Command Line Tools: `xcode-select --install`

# Install JPEG Group libjpg

* `tar xfvz jpegsrc.v9a.tar.gz`
* `cd jpeg-9a`
* `./configure`
* `make`
* `sudo make install`



## Install Libtools

* `tar xfvz libtool-2.4.6.tar.gz`
* `cd libtool-2.4.6`
* `./configure`
* `make`
* `sudo make install`


## Install Pkg-Config

* Easier to install this as a pkg binary (from here: http://rudix.org/packages/pkg-config.html)

## Install ImageMagick

* `tar xfvz ImageMagick-x86_64-apple-darwin15.0.0.tar.gz`
* `cd ImageMagick-6.9.2`
* `./configure`
* `make`
* `sudo make install`

## Install Rmagic

* `sudo gem install rmagick`


## Install Carrierwave (Optional)

* `sudo gem install carrierwave`