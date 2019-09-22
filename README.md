# react-native-progress-dialog

Simple progress dialog for React Native

## Installation

`yarn add react-native-progress-dialog`

or

`npm i react-native-progress-dialog`

## Usage

First, import 
```
import { ProgressSteps, ProgressStep } from 'react-native-progress-steps';
```

Then in your component use it:

```
<ProgressDialog visible={this.state.visible}/>
```

## Props

| Name | Description | Default | Type |
|------------------|--------------------------------------------------------------------------|----------|---------|
| label | Text that should be displayed | 'Please wait...' | String |
| labelStyle | Custom styles from the label | null | Object |
| loaderColor | Color of the loader circle | '#0d0' | String |

## License
[MIT](./LICENSE)

## Author

Rashidul Hasan | www.rashidul.xyz
