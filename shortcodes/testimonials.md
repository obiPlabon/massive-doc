### Testimonials Shortcode ( [Live Preview](http://massivedemo.lab.themebucket.net/shortcodes/testimonial/) )
---

![Testimonials shortcode](http://i.imgur.com/XTWtqCO.png)

1. **Testimonials Style:** choose testimonials style from dropdown & the available options are:
  * Grid
  * Carousel: Center Aligned
  * Carousel: Center Aligned Boxed
  * Carousel: Left Aligned Bubble
  * Carousel: Left Aligned Regular
2. **Customize:** click this checkbox to customize testimonials & then **custom settings** will be appear on a new tab.

##### Example:
```
[massive_testimonials_container][/massive_testimonials_container]
```
---
#### Testimonial Item Shortcode (Depend on Testimonials Shortcode)
---

![Testimonial Item shortcode](http://i.imgur.com/ZBVV063.png)

1. **Name:** testimonial provider's name goes here.
2. **Job Title:** testimonial provider's job title goes here.
3. **Testimonial Content:** testimonial content goes here.
4. **Avatar:** choose avatar type from dropdown & the available options are:
  * Image
  * Icon  
  * None

##### Example:
```
[massive_testimonial which_avatar="icon" has_icon="icon-alarmclock"][/massive_testimonial]
```

##### Group Example:
```
[massive_testimonials_container][massive_testimonial which_avatar="icon" has_icon="icon-alarmclock"][/massive_testimonial][/massive_testimonials_container]
```
