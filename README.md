## rn-fade-in-image

React Native fade in image using animation API. Have your images fade in the way your users will love.

### Installation

```
npm i rn-fade-in-image --save
or
yarn add rn-fade-in-image
```

### Usage

```javascript
import React from 'react';
import { View } from 'react-native';
import FadeInImage from 'rn-fade-in-image';


export default class App extends React.Component {
  render() {
    return (
      <View style={styles.container}>
       <FadeInImage
     style={styles.image} //required
     duration={500} //optional
      source={{ uri: 'https://images.unsplash.com/photo-1485832329521-e944d75fa65e?auto=format&fit=crop&w=1000&q=80&ixid=dW5zcGxhc2guY29tOzs7Ozs%3D' }}
    />
    </View>
    );
  }
}
```

#### props

- `style` adds style to the image component. Required.
- `duration` control the duration of the component render. Optional. Default is 400
