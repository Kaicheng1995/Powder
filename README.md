# Powder
> check it out: [redirected domain](http://powder.zone")  
> check it out: [original domain](https://limitless-beach-89648.herokuapp.com/")


**"No friends on powder days!"** When the snow, especially for **powder** snow, is good to take care of all the needs as a snowboarder, or skier, there would be no time for dealing with friendship stuff.  
<div align=center>
  <img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/friends-powder-days_h_0.jpg" width="400"> 
</div>

As a snowboarding lover, I wrote this web app, and hope to establish a snowboards shopping website in China. Since China is going to host the 2022 Winter Olympic Games, and there isn't any direct sales channel for snowboards in China, I think it should be a good opportunity to start a business with the blooming market.


## Usage example

Create a new account, or login with below:
```diff
+ USER ACCOUNT:
  Email: kaicheng_jia@126.com
  Password: 123456
 
- ADMIN ACCOUNT:
  Email: ares.jia@hotmail.com
  Password: 123456
```
<div align=center>
<img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/login1.png" width="600"> 
  <img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/register1.png" width="600"></div>  
  

  
Dashboard: you can modify some info here **(PLS DONT MODIFY IF YOU LOGIN AS ADMIN!!)**
```diff
DASHBOARD
+ Edit profile
+ Check Cart
+ Check transaction history
 
- Add product:
- Manage Categories
```
<div align=center>
<img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/dashboard.png" width="600"> 
</div>

Check Product: go to homepage, select one product and click "SHOP NOW", "VIEW PRODUCT"
```diff
! HOME PAGE
  Main slide
  Best selling products
  Promotion area
  New arrival products

! PRODUCT PAGE
  Product detail
```
<div align=center>
<img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/home.png" width="600"> 
  <img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/productpage.png" width="600"> 
</div>

Search product, Add to Cart:
```diff
! SHOP PAGE
  Filter box: you can select the products using filter
  Product layout: you can change the layout

! CART PAGE
  you can check the items you've added to the cart
```
<div align=center>
<img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/shop.png" width="600"><img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/shop2.png" width="600"> 
  <img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/cart.png" width="600"> 
</div>



Payment: you can finish buying products with the test paypal account below
```diff
+ TEST PAYPAL ACCOUNT: 
   Account: sb-5yiaa1243914@personal.example.com
   Password: testing123
```
<div align=center>
<img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/pay1.png" width="600"><img src="https://github.com/Kaicheng1995/powder.zone/blob/master/img/pay2.png" width="600"> 
</div>

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```


## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
