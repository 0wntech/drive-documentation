## SVG Icons

Drive uses svgr to create Inline SVG Icons

- Place `icon.svg` in `src/assets/icons`
- run `npm run svgr` (this will automatically create an Icon component in `src/assets/svgIcons`)
- Import the Icon `import Icon from '../../assets/svgIcons/Icon';`
- Use it like this: `<Icon className={styles.editIcon} />` (all props get passed down to the wrapped SVG)

## CSS Modules

Drive uses css modules

- create a `ComponentName.module.css` file and define a class `.button{color: #22FFFFF};`
- import it: `import styles from './ComponentName.module.css'`
- Apply class: `<div className={styles.button}/>`
