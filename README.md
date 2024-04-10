## Before Start 🟠

As the saying goes, *"God helps those who help themselves"*. So I accumulated my efforts and did it. And now you, my colleague, as well as me, have enough fingers and toes to count all snippets I've created. In addition snippets' prefix is easy to remember and find the right keys on your keyboard. Add this awesome set, enjoy and boost your productivity.⚡

Finally, I dedicate this extention to my dad, who celebrates his birthday on `13`th of May.👋🎉

# Overview

| Snippet | Description                       |
| ------- | --------------------------------- |
| `asy`   | *Arrow function named export*     |
| `asd`   | *Arrow function default export*   |
| `asfr`  | *File related function*           |
| `aswr`  | *Folder related function*         |
| `asch`  | *Choice function*                 |
| `us`    | *useState hook*                   |
| `uref`  | *useRef hook*                     |
| `ue`    | *useEffect hook*                  |
| `ule`   | *useLayoutEffect hook*            |
| `cctx`  | *Create Context*                  |
| `ec`    | *Expo Component*                  |
| `ecss`  | *Expo Component & StyleSheet*     |
| `ess`   | *Expo StyleSheet*                 |


<br />

# React
> Tip: In examples below the vertical bar `|` is just a positioned cursor.


<br />

### `asy` : 💡 Arrow function named export
```javascript
export const example = () => {
    return (
        <>|</>
    )
}
```
### `asd` : 💡 Arrow function default export
```javascript
const Example| = () => {
    return (
        <></>
    )
}

export default Example|;
```
### `asfr` : 💡 Function name relates to file name
```javascript
export default function |Example() {
    return (
        <></>
    )
}
```
### `aswr` : 💡 Function name relates to folder (wrapper) name
```javascript
export default function FolderName() {
    return (
        <>|</>
    )
}
```
### `asch` : 💡 Choose function name between 'Page' and 'Layout'
```javascript
export default function |Layout() {
    return (
        <></>
    )
}
```
### `us` : 💡 useState hook
```javascript
const [|, set|] = useState("");
// press `Tab` after typing the value and let magic happen
```
### `uref` : 💡 useRef hook
```javascript
const |Ref = useRef(null);
```
### `ue` : 💡 useEffect hook
```javascript
useEffect|(() => {
    
}, [])
// press `Ctrl`+`Space` to import useEffect
```
### `ule` : 💡 useLayoutEffect hook
```javascript
useLayoutEffect|(() => {
    
}, [])
// press `Ctrl`+`Space` to import useLayoutEffect
```
### `cctx` : 💡 Create React Context
```javascript
import { createContext, useContext } from "react";

const |Context = createContext(null);


export const |ContextProvider = ({ children }) => {
    

    return (
        <|Context.Provider value={{}}>
            {children}
        </|Context.Provider>
    );
}

export const use| = () => {
    const value = useContext(|Context);

    if (!value) {
        throw new Error(`use| must be wrapped inside |ContextProvider`);
    }

    return value;
}
```
<br />

# React Native, Expo

### `ec` : 💡 Expo Component
```javascript
import { View, Text } from 'react-native';

export const example = () => {
    return (
        <View>
            <Text>example|</Text>
        </View>
    )
}
```
### `ecss` : 💡 Expo Component & StyleSheet
```javascript
import { View, Text, StyleSheet } from 'react-native';

export const example = () => {
    return (
        <View>
            <Text>example|</Text>
        </View>
    )
}

const styles = StyleSheet.create({
    
})
```
### `ess` : 💡 Expo StyleSheet
```javascript
import { StyleSheet } from "react-native";

export default StyleSheet.create({
    container: {
        flex: 1,
        backgroundColor: "#fff",
        |
    },
})
```

# Demo
![Demo of how some snippets work](https://github.com/yu1iaw/react-snippets-extension/blob/5a2aac8acdf0e4c86297a4194d13b6d2b498ff2b/images/Code_VR2VUygHSA.gif)

**That's it! Enjoy and happy coding!**

---
## What's next
What is next? Ouch! I guess `NEXT` is next.😉




