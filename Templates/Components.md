# Functional Component Templates

## Functional Component

```javascript
import React from "react";
import PropTypes from "prop-types";
import styles from "./ComponentName.module.css";

const ComponentName = props => {
  return <div></div>;
};

ComponentName.propTypes = {};

export default ComponentName;
```

## Functional Component with redux

```javascript
import React from "react";
import PropTypes from "prop-types";
import { connect } from "react-redux";
import styles from "./ComponentName.module.css";

// export for testing purpose (without connected store)
export const ComponentName = props => {
  return <div></div>;
};

const mapStateToProps = state => ({});

const mapDispatchToProps = {};

ComponentName.propTypes = {};

// export for usage
export default connect(
  mapStateToProps,
  mapDispatchToProps
)(FileName);
```

## Class Components

Replaced by [React Hooks](https://reactjs.org/docs/hooks-reference.html)
