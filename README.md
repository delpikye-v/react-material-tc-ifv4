<div align="center">
    <h1>react-material-tc-i4z</h1>
    <a href="https://github.com/delpikye-v/react-material-tc-ifv4">react-material-tc-i4z</a>
    <br />
    <br />
    <b><a href="https://codesandbox.io/s/h8vjx8">LIVE EXAMPLE</a>
    </b>
</div>

---

#### Description

React Material (v.4). Truncate text and show tooltip if need (Text overflow)

---
### Usage

Install the package

```js
npm install react-material-tc-i4z
```

Import the module in the place you want to use:
```js
import "react-material-tc-i4z/dist/styles.css";

import TruncateTooltip from "react-material-tc-i4z";

```

#### Snippet

###### simple

```js
const [size, setSize] = useState(200);

<Button
  onClick={() => setSize(400)}
  onClick={() => setSize(200)}
  // style={{
  //    width: size, // => you should update it from css class
  // }}
  >
  <TruncateShowTooltip title="abdc">
    <span // it should be html element.
      style={{
        width: size, // => you should update it from css class
      }}
    >
      Hellofds fdsfsfsfdsdf fdsf s
    </span>
  </TruncateShowTooltip>
</Button>
```

<br />

---


#### props

<b>TooltipProps</b>: from <b>react: @material-ui/core</b>


| props               | type                      | description                                      |
|---------------------|---------------------------|--------------------------------------------------|
| always              | boolean                   | default: false:  show if text is overflow        |
| bootstrapCss        | boolean                   | default: true: arrow and color like bootstrapCss |
| tooltipBgColor      | string                    | default: #000:                                   |
| tooltipColor        | string                    | default: #fff:                                   |

<br />

#### Note



#### RUN

<b><a href="https://codesandbox.io/s/h8vjx8">LIVE EXAMPLE</a>

<br />

### License

MIT