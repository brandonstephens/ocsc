# Open Color for Styled Components

Original work:
<https://yeun.github.io/open-color/>

Wanted to access them in my Styled Components. I use this with [styled-components](https://www.styled-components.com/), but it would work with any js file. 


## Installation 

1. Download `oc.js`
2. Import the file into your js file

```
import oc from ../path/to/file/oc
```

## Usage

Here is an example of the oc library referenced inside a styled-component. 


```
 const ChunkyButton = styled.button`
  padding: 55px 89px;
  width: 100%;
  background-color: ${oc.yellow[6]};
  border-radius: 21px;
`
```