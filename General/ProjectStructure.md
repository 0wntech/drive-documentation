## General Structure

```
+---src
|    +---actions                 // Redux Actions
|    |   +---types.js            // Redux Actions types constants
|    +---assets                  // Graphics/Fonts go here
|    |   +---animations          // Animations
|    |   +---icons               // icons
|    |   \---svgIcons            // !Automatically! created folder (don't change files here)
|    +---functional_components   // Functional Components
|    +---hooks                   // Hooks
|    +---reducers                // Redux Reducers
|    +---stateful_components     // Stateful Components
|    \---utils                   // Reusable helper Functions
```

## Components

Should be seperated in a folder with the structure:

```

+---ComponentName
|       ComponentName.js
|       ComponentName.module.css
|       package.json
```

`package.json` for a component should look like this:

```json
{
  "main": "ComponentName.js"
}
```
