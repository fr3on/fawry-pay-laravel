# Fawry Pay
Fawry pay payment gateway is a powerful payment processor that helps you pay through credit cart & Fawry Machines.

## Installation

1) In your terminal:

``` bash
$ composer require fr3on/fawry-pay
```

2) Publish the config file & run the migrations 

```bash
php artisan vendor:publish --provider="Fr3on\LaravelFawryPay\LaravelFawryPayServiceProvider"
php artisan migrate
```
