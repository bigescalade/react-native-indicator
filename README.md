# react-native-indicator

Forked. [Original by wangdicoder](https://github.com/wangdicoder/react-native-indicator)

An indicator component for React Native

<img src="https://raw.githubusercontent.com/wangdicoder/react-native-indicator/master/screenshot/ss1.gif" width="372" height="666" />
<img src="https://raw.githubusercontent.com/wangdicoder/react-native-indicator/master/screenshot/ss2.gif" width="372" height="666" />
<img src="https://raw.githubusercontent.com/wangdicoder/react-native-indicator/master/screenshot/ss3.gif" width="372" height="666" />
<img src="https://raw.githubusercontent.com/wangdicoder/react-native-indicator/master/screenshot/ss4.gif" width="372" height="666" />

## Installation

```
$ npm install react-native-indicator --save
```

### Android

No extra setup required

### iOS

Add `ART.xcodeproj` from `node_modules/react-native/Libraries/ART` to your Libraries then link `libART.a`. To see more details about **Linking Libraries**, jump to [this](https://facebook.github.io/react-native/docs/linking-libraries-ios.html).

## Usage

```
import { CirclesLoader, TextLoader } from 'react-native-indicator';

render(){
  return(
    <View>
      <CirclesLoader />
      <TextLoader text="Loading" />
    </View>
  );
}

```

Available indicators:

- [PulseLoader](#PulseLoader)
- [DotsLoader](#DotsLoader)
- [TextLoader](#TextLoader)
- [BubblesLoader](#BubblesLoader)
- [CirclesLoader](#CirclesLoader)
- [BreathingLoader](#BreathingLoader)
- [RippleLoader](#RippleLoader)
- [LinesLoader](#LinesLoader)
- [MusicBarLoader](#MusicBarLoader)
- [EatBeanLoader](#EatBeanLoader)
- [DoubleCircleLoader](#DoubleCircleLoader)
- [RotationCircleLoader](#RotationCircleLoader)
- [RotationHoleLoader](#RotationHoleLoader)
- [CirclesRotationScaleLoader](#CirclesRotationScaleLoader)
- [NineCubesLoader](#NineCubesLoader)
- [LineDotsLoader](#LineDotsLoader)
- [ColorDotsLoader](#ColorDotsLoader)

## Props

<a name="PulseLoader" />

##### PulseLoader

| prop      | type   | default   | description       |
| --------- | ------ | --------- | ----------------- |
| size      | number | 30        | circle's size     |
| color     | string | '#1e90ff' | indicator's color |
| frequency | number | 1000      | scale's frequency |

<a name="DotsLoader" />

##### DotsLoader

| prop         | type   | default   | description               |
| ------------ | ------ | --------- | ------------------------- |
| size         | number | 10        | dot's size                |
| color        | string | '#1e90ff' | indicator's color         |
| betweenSpace | number | 5         | distance between two dots |

<a name="TextLoader" />

##### TextLoader

| prop      | type   | default   | description  |
| --------- | ------ | --------- | ------------ |
| text      | string | 'Loading' | contents     |
| textStyle | style  | inherited | text's style |

<a name="BubblesLoader" />

##### BubblesLoader

| prop      | type   | default   | description       |
| --------- | ------ | --------- | ----------------- |
| size      | number | 40        | circle's size     |
| color     | string | '#1e90ff' | indicator's color |
| dotRadius | number | 10        | each dot's size   |

<a name="CirclesLoader" />

##### CirclesLoader

| prop      | type   | default   | description       |
| --------- | ------ | --------- | ----------------- |
| size      | number | 40        | circle's size     |
| color     | string | '#1e90ff' | indicator's color |
| dotRadius | number | 8         | each dot's size   |

<a name="BreathingLoader" />

##### BreathingLoader

| prop        | type   | default   | description       |
| ----------- | ------ | --------- | ----------------- |
| size        | number | 10        | circle's size     |
| color       | string | '#1e90ff' | indicator's color |
| strokeWidth | number | 3         | outline width     |
| frequency   | number | 800       | scale's frequency |

<a name="RippleLoader" />

##### RippleLoader

| prop        | type   | default   | description       |
| ----------- | ------ | --------- | ----------------- |
| size        | number | 10        | circle's size     |
| color       | string | '#1e90ff' | indicator's color |
| strokeWidth | number | 3         | outline width     |

<a name="LinesLoader" />

##### LinesLoader

| prop         | type   | default   | description               |
| ------------ | ------ | --------- | ------------------------- |
| color        | string | '#1e90ff' | indicator's color         |
| barWidth     | number | 5         | each bar's width          |
| barHeight    | number | 40        | each bar's height         |
| barNumber    | number | 5         | the number of bar         |
| betweenSpace | number | 2         | distance between two bars |

<a name="MusicBarLoader" />

##### MusicBarLoader

| prop         | type   | default   | description               |
| ------------ | ------ | --------- | ------------------------- |
| color        | string | '#1e90ff' | indicator's color         |
| barWidth     | number | 3         | each bar's width          |
| barHeight    | number | 30        | each bar's height         |
| betweenSpace | number | 5         | distance between two bars |

<a name="EatBeanLoader" />

##### EatBeanLoader

| prop  | type   | default   | description       |
| ----- | ------ | --------- | ----------------- |
| color | string | '#1e90ff' | indicator's color |
| size  | number | 30        | indicator's size  |

<a name="DoubleCircleLoader" />

##### DoubleCircleLoader

| prop  | type   | default   | description       |
| ----- | ------ | --------- | ----------------- |
| size  | number | 30        | circle's size     |
| color | string | '#1e90ff' | indicator's color |

<a name="RotationCircleLoader" />

##### RotationCircleLoader

| prop          | type   | default   | description       |
| ------------- | ------ | --------- | ----------------- |
| size          | number | 30        | indicator's size  |
| color         | string | '#1e90ff' | indicator's color |
| rotationSpeed | number | 800       | rotation speed    |

<a name="RotationHoleLoader" />

##### RotationHoleLoader

| prop          | type   | default   | description            |
| ------------- | ------ | --------- | ---------------------- |
| size          | number | 40        | indicator's size       |
| color         | string | '#1e90ff' | indicator's color      |
| rotationSpeed | number | 800       | rotation speed         |
| strokeWidth   | number | 8         | circle outline's width |

<a name="CirclesRotationScaleLoader" />

##### CirclesRotationScaleLoader

| prop  | type   | default   | description       |
| ----- | ------ | --------- | ----------------- |
| size  | number | 50        | indicator's size  |
| color | string | '#1e90ff' | indicator's color |

<a name="NineCubesLoader" />

##### NineCubesLoader

| prop  | type   | default   | description       |
| ----- | ------ | --------- | ----------------- |
| size  | number | 20        | each cube's size  |
| color | string | '#1e90ff' | indicator's color |

<a name="LineDotsLoader" />

##### LineDotsLoader

**warning:** _this indicator will occupy a whole horizontal space automatically, which means you don't need to set any center props. Just keeping the direction of its parent View is vertical._

| prop         | type   | default   | description               |
| ------------ | ------ | --------- | ------------------------- |
| size         | number | 10        | dot's size                |
| color        | string | '#1e90ff' | indicator's color         |
| dotsNumber   | number | 5         | the number of dots        |
| betweenSpace | number | 5         | distance between two dots |

<a name="ColorDotsLoader" />

##### ColorDotsLoader

| prop         | type   | default           | description               |
| ------------ | ------ | ----------------- | ------------------------- |
| size         | number | 15                | each cube's size          |
| betweenSpace | number | 7                 | distance between two dots |
| color1       | string | '#ff4500'(red)    | 1st color                 |
| color2       | string | '#ffd700'(yellow) | 2nd color                 |
| color3       | string | '#9acd32'(green)  | 3rd color                 |

## License

MIT
