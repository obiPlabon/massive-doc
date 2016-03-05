### Pricing Table Shortcode ( [Live Preview](http://massivedemo.lab.themebucket.net/shortcodes/pricing-table/) )
---

![Pricing Table Shortcode](http://i.imgur.com/dajGLH3.png)

1. **Currency:** add pricing currency.
2. **Column(s):**  choose column(s) from dropdown & the available options are:
  * 1 Column
  * 2 Columns
  * 3 Columns
  * 4 Columns
  * 6 Columns
3. **Remove Gutter:** click this checkbox for gutter less table.

##### Example:
```
[massive_pricing_table columns="3"][/massive_pricing_table]
```
---
#### Package Shortcode (Depend on Pricing Table Shortcode)
---

![Package shortcode](http://i.imgur.com/e7aZ7D7.png)

1. **Package Name:** pricing package _name_ goes here.
2. **Package Price:** package price goes here.
3. **Package Duration:** add package duration.
4. **Package Features:** pricing features content goes here.
5. **Button Text:** change button text.
6. **Button Link:** add button link.
7. **Featured Package:** click this checkbox to making featured package.

##### Example:
```
[massive_package title="Startup" price="300" button_text="Purchase " button_link="#" is_featured="true"]Feature goes here Feature goes here[/massive_package]
```

##### Group Example:
```
[massive_pricing_table columns="3"][massive_package title="Startup" price="300" button_text="Purchase " button_link="#" is_featured="true"]Feature goes here Feature goes here[/massive_package][/massive_pricing_table]
```
