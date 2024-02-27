
# [Intosoft QRCode](https://qrcode.intosoft.com/) &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Intosoft/qrcode/blob/main/LICENSE) 

Intosoft QRCode is a fully customizable open source QR code generator tool.
-    **Versatile and Customizable:**  Fully color, style, content customization
-   **Seamless Integration:** Integrate Intosoft QRcode seamlessly into your existing tech stack, whether you're working with React, React Native, NodeJS, Vue.js, Angular, or pure JavaScript.  
 
[Start cutomizing](https://qrcode.intosoft.com)

## Installation
NPM
```
npm i @intosoft/qrcode
```
Yarn
```
yarn add @intosoft/qrcode
```  
## Examples 

React
```jsx
import { generateSVGFromMatrix } from  '@intosoft/qrcode';

const svgString = generateSVGFromMatrix();

export  const  RenderQR = () => {
	return (<div dangerouslySetInnerHTML={{__html: svgString}}/>);
};
```

React Native
First Install [react-native-svg](https://github.com/software-mansion/react-native-svg)
```jsx
import { SvgFromXml } from  "react-native-svg";
import { generateSVGFromMatrix } from  '@intosoft/qrcode';

const svgString = generateSVGFromMatrix();

export  const  RenderQR = () => {
	return (<SvgFromXml  xml={svgString}  />);
};
```
 
### License   [MIT licensed](./LICENSE).

*QR Code is a registered trademark of DENSO WAVE INCORPORATED.*