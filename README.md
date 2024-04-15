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
| `fli`   | *FlatList*                        |
| `ec`    | *Expo Component*                  |
| `ss`    | *StyleSheet*                      |
| `ssac`  | *StyleSheet align center*         |
| `ssrw`  | *StyleSheet row*                  |
| `ess`   | *Export StyleSheet*               |


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

### `fli` : 💡 FlatList
```javascript
<FlatList|
    data={data|}
    keyExtractor={item => item.id}
    showsVerticalScrollIndicator={false}
    renderItem={({ item }) => (
        <RenderItem| />
    )}
/>
```
### `ec` : 💡 Expo Component
```javascript
import { View, Text } from 'react-native';

export const Example = () => {
    return (
        <View>
            <Text>Example|</Text>
        </View>
    )
}
```
### `ss` : 💡 StyleSheet
```javascript
const styles = StyleSheet|.create({
    
})
```
### `ssac` : 💡 StyleSheet align center
```javascript
container: {
    flex: 1,
    justifyContent: "center",
    alighItems: "center",
    gap: 16,|
},
```
### `ssrw` : 💡 StyleSheet row
```javascript
rowContainer: {
    flexDirection: "row",
    justifyContent: "space-between",
    alignItems: "center",
    margin: 16,|
},
```
### `ess` : 💡 Export StyleSheet
```javascript
import { StyleSheet } from "react-native";

export default StyleSheet.create({
    mainContainer: {
        flex: 1,
        backgroundColor: "#fff",|
    },
})
```

# Demo
![Demo of how some snippets work](https://raw.githubusercontent.com/yu1iaw/react-snippets-extension/main/images/Demo.gif)

**That's it! Install and happy coding!**

---
## What's next
What is next? Ouch! I guess `NEXT` is next.😉




