### Accordions Shortcode ( [Live Preview](http://massivedemo.lab.themebucket.net/shortcodes/toggle-accordion/) )
---

![Accordions shortcode](http://i.imgur.com/UGx5cgl.png)

1. **Accordions Style:** choose accordions style from dropdown & the available options are:
  * Timeline
  * Bar
2. **Toggle Mode:** click on checkbox to enable toggle mode.
3. **Customize:** click this checkbox to customize accordions & then **custom settings** will be appear on a new tab.

##### Example:
```
[massive_accordions_container customize_one="true" toggle="true"][/massive_accordions_container]
```
---
#### Accordion Item Shortcode (Depend on Accordions Shortcode)
---

![Accordion Item shortcode](http://i.imgur.com/AdOuLIj.png)

1. **Title:** accordion title goes here.
2. **Content:** accordion content goes here.

##### Example:
```
[massive_accordion title="Accordion item title goes here"]Accordion item title content goes here[/massive_accordion]
```

##### Group Example:
```
[massive_accordions_container customize_one="true" toggle="true"][massive_accordion title="Accordion item title goes here"]Accordion item title content goes here[/massive_accordion][/massive_accordions_container]
```
