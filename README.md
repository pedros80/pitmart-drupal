## Pitmart/Drupal Bridge - v1.0 Readme
[Peter Somerville](http://www.pedros-stuffs.com) - peterwsomerville@gmail.com

### License.
GNU GPL - see LICENSE.txt for more information

### About

A series of modules to allow drupal websites to include product data from
[www.pitmart.com](http://www.pitmart.com) using the remote web service feeds provided by Pitmart.

These products can be selected from a single user, by most recently listed or 'exclusive' listings only.


### Installation

- clone this repository to your development environment
- to `sites/all/modules/custom/` add the directory `pitmart`
- enable the module `pitmart` from the package `pitmart`.
- configure the `pitmart` module by entering the user id of the required pitmart member and either http://www.pitmart.com/ or http://www.pitmart.com/demo/ to select live or demo data.

- enable the module `Recent Auctions` and configure as required (number of products, show pictures? etc)
- **and/or**
- enable the module `User Auctions` and configure as required (number of products, show pictures? etc)


Enabling the modules dependent on `pitmart` will create a block containing a series of `<div>`s, each containing the required data on a single auction depending on the module you are using, which can be placed on any or all pages of your drupal site.

These divs are given user-definable classes so further customisation can be applied using your theme's css file.