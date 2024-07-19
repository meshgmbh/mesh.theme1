# [Vvveb Bootstrap 5 template &amp; UI Kit](https://design.mesh.app/themes/landing/index.html) &nbsp; 

Bootstrap 5 html template with over 100+ sections that can be used to build any website.

Default theme used in **[Vvveb CMS](https://design.mesh.app)**

**[👉 Live Demo](https://design.mesh.app/vvvebjs/demo/landing/index.html)**   **[👉 Page builder demo](https://design.mesh.app)**



![Section list](https://design.mesh.app/themes/landing/list.png?a)

| [![](https://design.mesh.app/themes/landing/screens/home.png)](https://design.mesh.app/themes/landing/screens/home.png) | [![](https://design.mesh.app/themes/landing/screens/home-dark.png)](https://design.mesh.app/themes/landing/screens/home-dark.png) | [![](https://design.mesh.app/themes/landing/screens/blog.png)](https://design.mesh.app/themes/landing/screens/blog.png) | [![](https://design.mesh.app/themes/landing/screens/blog-dark.png)](https://design.mesh.app/themes/landing/screens/blog-dark.png) |
|:---:|:---:|:---:|:---:|
| **Home** | **Home dark** | **Blog** | **Blog dark** |
| [![](https://design.mesh.app/themes/landing/screens/shop.png)](https://design.mesh.app/themes/landing/screens/shop.png) | [![](https://design.mesh.app/themes/landing/screens/shop-dark.png)](https://design.mesh.app/themes/landing/screens/shop-dark.png) | [![](https://design.mesh.app/themes/landing/screens/product.png)](https://design.mesh.app/themes/landing/screens/product.png) | [![](https://design.mesh.app/themes/landing/screens/product-dark.png)](https://design.mesh.app/themes/landing/screens/product-dark.png) |
| **Shop**  | **Shop dark** | **Product**  | **Product dark** |
| [![](https://design.mesh.app/themes/landing/screens/contact.png)](https://design.mesh.app/themes/landing/screens/contact.png) | [![](https://design.mesh.app/themes/landing/screens/contact-dark.png)](https://design.mesh.app/themes/landing/screens/contact-dark.png) | [![](https://design.mesh.app/themes/landing/screens/cart.png)](https://design.mesh.app/themes/landing/screens/cart.png) | [![](https://design.mesh.app/themes/landing/screens/cart-dark.png)](https://design.mesh.app/themes/landing/screens/cart-dark.png) |
| **Contact** | **Contact dark** | **Cart** | **Cart dark** |
| [![](https://design.mesh.app/themes/landing/screens/post.png)](https://design.mesh.app/themes/landing/screens/post.png) | [![](https://design.mesh.app/themes/landing/screens/post-dark.png)](https://design.mesh.app/themes/landing/screens/post-dark.png) | [![](https://design.mesh.app/themes/landing/screens/checkout.png)](https://design.mesh.app/themes/landing/screens/checkout.png) | [![](https://design.mesh.app/themes/landing/screens/checkout-dark.png)](https://design.mesh.app/themes/landing/screens/checkout-dark.png) |
| **Post** | **Post dark** | **Checkout** | **Checkout dark** |
| [![](https://design.mesh.app/themes/landing/screens/signup.png)](https://design.mesh.app/themes/landing/screens/signup.png) | [![](https://design.mesh.app/themes/landing/screens/signup-dark.png)](https://design.mesh.app/themes/landing/screens/signup-dark.png) | [![](https://design.mesh.app/themes/landing/screens/signin.png)](https://design.mesh.app/themes/landing/screens/signin.png) | [![](https://design.mesh.app/themes/landing/screens/signin-dark.png)](https://design.mesh.app/themes/landing/screens/signin-dark.png) |
| **Signup** | **Signup dark** | **Signin** | **Signin dark** |
| [![](https://design.mesh.app/themes/landing/screens/user.png)](https://design.mesh.app/themes/landing/screens/user.png) | [![](https://design.mesh.app/themes/landing/screens/user-dark.png)](https://design.mesh.app/themes/landing/screens/user-dark.png) | [![](https://design.mesh.app/themes/landing/screens/orders.png)](https://design.mesh.app/themes/landing/screens/orders.png) | [![](https://design.mesh.app/themes/landing/screens/orders-dark.png)](https://design.mesh.app/themes/landing/screens/orders-dark.png) |
| **User** | **User dark** | **Orders** | **Orders dark** |
| [![](https://design.mesh.app/themes/landing/screens/profile.png)](https://design.mesh.app/themes/landing/screens/profile.png) | [![](https://design.mesh.app/themes/landing/screens/profile-dark.png)](https://design.mesh.app/themes/landing/screens/profile-dark.png) | 
| **Profile** | **Profile dark** |


## Categories

- Call to action - https://github.com/givanz/landing/blob/master/screenshots/hero/
- Features - https://github.com/givanz/landing/blob/master/screenshots/features/
- Base - https://github.com/givanz/landing/blob/master/screenshots/base/
- Contact form - https://github.com/givanz/landing/blob/master/screenshots/contact-form/
- Footer - https://github.com/givanz/landing/blob/master/screenshots/footer/
- Navigation - https://github.com/givanz/landing/blob/master/screenshots/navigation/
- Posts - https://github.com/givanz/landing/blob/master/screenshots/posts/
- Pricing table - https://github.com/givanz/landing/blob/master/screenshots/pricing table/
- Products - https://github.com/givanz/landing/blob/master/screenshots/products/
- Showcase - https://github.com/givanz/landing/blob/master/screenshots/showcase/
- Team - https://github.com/givanz/landing/blob/master/screenshots/team/
- Testimonials - https://github.com/givanz/landing/blob/master/screenshots/testimonials/


## Build

### Generate html files

```bash
npm run gulp
```

### Watch for changes for development

```bash
npm run gulp watch
```

### Generate sections list for design.mesh.app page builder

```bash
npm run gulp sections
```

### Generate blocks list for design.mesh.app editor

```bash
npm run gulp blocks
```

### Generate screenshots for sections

```bash
npm run gulp screenshots
```


## Quick start

- Clone the repo and run it.
```bash
git clone https://github.com/givanz/landing/
cd landing
npm i
npm run gulp
```


## Structure

```
├── index.html  -- **default template used for homepage**
├── index.coming-soon.html  -- *replaces homepage when site is set to coming soon*
├── index.maintenance.html  -- replaces homepage when site is set to maintenance
├── error404.html  -- page not found error page
├── error500.html  -- internal server error page
├── blank.html  -- page with basic layout with minimal or no content
└── content
│   └── index.html - blog page
│   └── post.html - singe post page
│   └── page.html - page template
│   └── tag.html - posts for tag page
│   └── category.html - posts category page
│   └── archive.html - posts for a certain date
│   └── user.html - user posts
└── product 
│   └── index.html - shop page
│   └── product.html - singe product page
│   └── manufacturer.html - manufacturer page
│   └── vendor.html - vendor page
│   └── category.html - category page
└── search 
│   └── search.html - search page
└── user
│   └── index.html - user dashboard
│   └── signup.html - user signup form
│   └── login.html - site login form
│   └── reset.html - password reset form
│   └── edit.html - user data edit
│   └── address.html - address list
│   └── comments.html - comments list
│   └── orders.html - orders list
│   └── downloads.html - digital products downloads list
└── cart 
│   └── cart.html - display cart page
└── checkout 
│   └── checkout.html - cart checkout form
│   └── confirm.html - order confirmation page
│   └── confirm.html - order confirmation page
└── email
│   └── order
│   │   └── new.html - template for new order mail
│   │   └── user
│   └── reset.html - template for new order mail
    └── signup.html - template for user welcome
```

## Documentation

For documentation check the [theme development documentation](http://dev.vvveb.com/theme-introduction)

## Support

If you like the project you can support it with a [PayPal donation](https://paypal.me/zgivan) or become a backer/sponsor via [Open Collective](https://opencollective.com/vvvebjs)


<a href="https://opencollective.com/vvvebjs/sponsors/0/website"><img src="https://opencollective.com/vvvebjs/sponsors/0/avatar"></a>
<a href="https://opencollective.com/vvvebjs/backers/0/website"><img src="https://opencollective.com/vvvebjs/backers/0/avatar"></a>


## License

Apache 2.0
