### Clients Shortcode ( [Live Preview](http://massivedemo.lab.themebucket.net/shortcodes/clients/) )
---
#### Clients Style: Carousel
---

![Clients shortcode - Carousel Style: ](http://i.imgur.com/XfhsZG0.png?1)

1. **Autoplay:** choose _autoplay_ from dropdown & the available options are:
  * Yes
  * No
2. **Items:** add the number of item you want to see on the screen at a time.
3. **Pagination:** choose _autoplay_ from dropdown & the available options are:
  * Yes
  * No


---
#### Clients Style: Grid
---
![Clients](http://i.imgur.com/vjlXIGL.png?1)

1. **Box Style:** choose clients grid _box style_ from dropdown & the available options are:
  * Angle Box
  * Plus Box
2. **Grid Size:** choose clients _grid size_ from dropdown & the available options are:
  * 2 Grid
  * 3 Grid
  * 4 Grid
  * 5 Grid
  * 6 Grid

#### Example:
```
[massive_clients_container items="3"][/massive_clients_container]
```

---
#### Client Item Shortcode (Depend on Clients Shortcode)
---
![Clients](http://i.imgur.com/IalpGMJ.png)

1. **Client Log:** add client logo/image.
2. **Client URL:** add client's _website URL_

#### Example:
```
[massive_client url="#" id="1175"]
```

#### Group Example:
```
[massive_clients_container items="3"][massive_client url="#" id="1175,1234,1678"][/massive_clients_container]
```
