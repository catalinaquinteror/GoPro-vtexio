## Store Theme GoPro

GoPro-vtexio was developed with VTEX IO technology.

[GoPro Colombia](https://goprocol.co) is the e-commerce used to replicate VTEX IO technology.

---

<!-- ## Image Roll

### Desktop

---

### Mobile -->

---

## Configuration

### Step 1

Get into [basic guide config](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-2-basicsetuptodevelopinvtexio) and follow the steps.

### Step 2

Clone this repository.
### Step 3

Edit in `manifest.json` file `vendor` and `name` fields.
### Step 4

To use Store Framework it is mandatory has installed `vtex.store-sitemap` and `vtex.store`, checking by execute `vtex link` comand, otherwise execute `vtex install vtex.store-sitemap vtex.store -f` to install them.
### Step 5

In case it has installed a predetermined store-theme, run `vtex uninstall` followed by the name, e.g.

```
vtex uninstall vtex.store-theme
```
### Step 6
Check builders and dependencies

**Builders**
```
{
    "styles": "2.x",
    "store": "0.x",
    "docs": "0.x",
    "assets": "0.x"
}
```
**Dependencies**
```
{
    "vtex.store": "2.x",
    "vtex.store-header": "2.x",
    "vtex.product-summary": "2.x",
    "vtex.store-footer": "2.x",
    "vtex.store-components": "3.x",
    "vtex.styleguide": "9.x",
    "vtex.slider": "0.x",
    "vtex.carousel": "2.x",
    "vtex.shelf": "1.x",
    "vtex.menu": "2.x",
    "vtex.minicart": "2.x",
    "vtex.product-details": "1.x",
    "vtex.product-kit": "1.x",
    "vtex.search-result": "3.x",
    "vtex.login": "2.x",
    "vtex.my-account": "1.x",
    "vtex.flex-layout": "0.x",
    "vtex.rich-text": "0.x",
    "vtex.store-drawer": "0.x",
    "vtex.locale-switcher": "0.x",
    "vtex.product-quantity": "1.x",
    "vtex.product-identifier": "0.x",
    "vtex.product-specification-badges": "0.x",
    "vtex.product-review-interfaces": "1.x",
    "vtex.telemarketing": "2.x",
    "vtex.order-placed": "2.x",
    "vtex.stack-layout": "0.x",
    "vtex.tab-layout": "0.x",
    "vtex.responsive-layout": "0.x",
    "vtex.slider-layout": "0.x",
    "vtex.iframe": "0.x",
    "vtex.breadcrumb": "1.x",
    "vtex.sticky-layout": "0.x",
    "vtex.add-to-cart-button": "0.x",
    "vtex.store-icons": "0.x",
    "vtex.store-image": "0.x",
    "vtex.store-link": "0.x",
    "vtex.modal-layout": "0.x",
    "vtex.search": "1.x",
    "vtex.checkout-summary": "0.x",
    "vtex.disclosure-layout": "1.x",
    "vtex.store-newsletter": "1.x",
    "vtex.product-list": "0.x",
    "vtex.product-price": "1.x"
    }
```

**PeerDependencies**
```
{
  "vtex.mega-menu": "2.x",
  "vtex.wish-list": "1.x"
}
```


**Custom Apps**
```
{
   "itgloberspartnercl.whatsapp-button": "0.x",
   "itgloberspartnercl.bullets-diagramation": "0.x",
   "itgloberspartnercl.add-to-cart-info": "0.x",
   "itgloberspartnercl.custom-department-search": "0.x",
   "itgloberspartnercl.pdf-reader": "0.x",
   "itgloberspartnercl.quick-order": "0.x",
   "itgloberspartnercl.special-diagramation": "0.x"
}
```

### Step 7

Run `vtex link` and after `vtex browse` to see changes at real time.