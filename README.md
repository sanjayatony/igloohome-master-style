# igloohome-master-style

The reason we having this master is to have consistent look of the website. The master stylesheet made from Kage's design.
I will create this stylesheet using  `SCSS`, and export the `CSS` file into HubSpot.

## How to use (WIP)
Later I will update how to use this stylesheet so others developer can use it easily.
---
In the new template add `styles.css`. And then create new css for the page. Master is only for **header**, **footer**, and **general** style. If you need a spesific style, add other css.

### Grid
#### Container
Add `.row`. It will automatically have 1024px width and will be centered.

#### Fullwidth
Add `.row .fullwidth`. The container will be 100%.

#### Grid with no space
Add `.row .collapse`. It will remove all the padding between the grids.


### Nav
Use `header` in `igloo2019` directory. TO use dark navigation add `dark-nav` in body.


### Typography
The font will be `Sofia Pro`. If you need a `Georgia` (Enterprise) just add `.enterprise' class to an element.


### Form
#### Button
Add class `.btn` to any anchor. Add another class, `.btn-small` for small size, `btn-medium` for medium size. Add `.btn-primary` for black background or `.btn-secondary` for background green.


### Utilities
`.spacer` will add 48px space.

`.p1` will add padding 8px.

`.p2` will add padding 16px.

`.px1` will add horizontal padding 8px.

`.px2` will add horizontal padding 16px.

`.py1` will add vertical adding 8px.

`.py2` will add vertical padding 16px.

`.py3` will add vertical adding 32px.

`.py4` will add vertical padding 64px.

`.v-center` will make element vertical center. The parent position should be `absolute`.





