## SVG Icons

Drive uses svgr to create Inline SVG Icons

- Place `icon.svg` in `src/assets/icons`
- run `npm run svgr` (this will automatically create a Icon component in `src/assets/svgIcons`)
- Import the Icon ```javascript
  import Icon from '../../assets/svgIcons/Icon';

````
- Use it like this: ```javascript
  <EditIcon className={styles.editIcon} /> //all props get passed down to the wrapped SVG

````
