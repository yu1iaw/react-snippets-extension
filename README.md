## Before Start 🟠

As the saying goes, *"God helps those who help themselves"*. So I accumulated my efforts and did it. And now you, my colleague, as well as me, have enough fingers and toes to count all snippets I've created. In addition snippets' prefix is easy to remember and find the right keys on your keyboard. Add this awesome set, enjoy and boost your productivity.⚡

Finally, I dedicate this extension to my dad, who celebrates his birthday on `13`th of May.👋🎉

# Overview

| Snippet | Description                       |                  |
| ------- | --------------------------------- |----------------- |
| `asy`   | *Arrow function named export*     | [ℹ️](#example1)  |
| `asd`   | *Arrow function default export*   | [ℹ️](#example2)  |
| `asfr`  | *File related function*           | [ℹ️](#example3)  |
| `aswr`  | *Folder related function*         | [ℹ️](#example4)  |
| `asch`  | *Choice function*                 | [ℹ️](#example5)  |
| `us`    | *useState hook*                   | [ℹ️](#example6)  |
| `uref`  | *useRef hook*                     | [ℹ️](#example7)  |
| `ue`    | *useEffect hook*                  | [ℹ️](#example8)  |
| `ule`   | *useLayoutEffect hook*            | [ℹ️](#example9)  |
| `cctx`  | *Create Context*                  | [ℹ️](#example10) |
| `fli`   | *FlatList*                        | [ℹ️](#example11) |
| `ec`    | *Expo Component*                  | [ℹ️](#example12) |
| `ss`    | *StyleSheet*                      | [ℹ️](#example13) |
| `ssac`  | *StyleSheet align center*         | [ℹ️](#example14) |
| `ssrw`  | *StyleSheet row*                  | [ℹ️](#example15) |
| `ess`   | *Export StyleSheet*               | [ℹ️](#example16) |
| `ersea` | *useLocalSearchParams*            | [ℹ️](#example17) |
| `ers`   | *Expo Router Stack layout*        | [ℹ️](#example18) |
| `ert`   | *Expo Router Tabs layout*         | [ℹ️](#example19) |


<br />

# React
> Tip: In examples below the vertical bar `|` is just a positioned cursor.


<br />

### <p id="example1">`asy` : 💡 Arrow function named export [⬆️](#overview)</p>
```javascript
export const example = () => {
    return (
        <>|</>
    )
}
```
### <p id="example2">`asd` : 💡 Arrow function default export [⬆️](#overview)</p>
```javascript
const Example| = () => {
    return (
        <></>
    )
}

export default Example|;
```
### <p id="example3">`asfr` : 💡 Function name relates to file name [⬆️](#overview)</p>
```javascript
export default function |Example() {
    return (
        <></>
    )
}
```
### <p id="example4">`aswr` : 💡 Function name relates to folder (wrapper) name [⬆️](#overview)</p>
```javascript
export default function FolderName() {
    return (
        <>|</>
    )
}
```
### <p id="example5">`asch` : 💡 Choose function name between 'Page' and 'Layout' [⬆️](#overview)</p>
```javascript
export default function |Layout() {
    return (
        <></>
    )
}
```
### <p id="example6">`us` : 💡 useState hook [⬆️](#overview)</p>
```javascript
const [|, set|] = useState("");
// press `Tab` after typing the value and let magic happen
```
### <p id="example7">`uref` : 💡 useRef hook [⬆️](#overview)</p>
```javascript
const |Ref = useRef(null);
```
### <p id="example8">`ue` : 💡 useEffect hook [⬆️](#overview)</p>
```javascript
useEffect|(() => {
    
}, [])
// press `Ctrl`+`Space` to import useEffect
```
### <p id="example9">`ule` : 💡 useLayoutEffect hook [⬆️](#overview)</p>
```javascript
useLayoutEffect|(() => {
    
}, [])
// press `Ctrl`+`Space` to import useLayoutEffect
```
### <p id="example10">`cctx` : 💡 Create React Context [⬆️](#overview)</p>
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

### <p id="example11">`fli` : 💡 FlatList [⬆️](#overview)</p>
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
### <p id="example12">`ec` : 💡 Expo Component [⬆️](#overview)</p>
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
### <p id="example13">`ss` : 💡 StyleSheet [⬆️](#overview)</p>
```javascript
const styles = StyleSheet|.create({
    
})
```
### <p id="example14">`ssac` : 💡 StyleSheet align center [⬆️](#overview)</p>
```javascript
container: {
    flex: 1,
    justifyContent: "center",
    alignItems: "center",
    gap: 16,|
},
```
### <p id="example15">`ssrw` : 💡 StyleSheet row [⬆️](#overview)</p>
```javascript
rowContainer: {
    flexDirection: "row",
    justifyContent: "space-between",
    alignItems: "center",
    margin: 16,|
},
```
### <p id="example16">`ess` : 💡 Export StyleSheet [⬆️](#overview)</p>
```javascript
import { StyleSheet } from "react-native";

export default StyleSheet.create({
    mainContainer: {
        flex: 1,
        backgroundColor: "#fff",|
    },
})
```
### <p id="example17">`ersea` : 💡 useLocalSearchParams [⬆️](#overview)</p>
```javascript
const { | } = useLocalSearchParams();
```
### <p id="example18">`ers` : 💡 Expo Router Stack layout [⬆️](#overview)</p>
```javascript
import { Stack } from "expo-router";


export default function StackLayout() {
    return (
        <Stack>
            <Stack.Screen name="|" options={{ | }} />
        </Stack>
    )
}
```
### <p id="example19">`ert` : 💡 Expo Router Tabs layout [⬆️](#overview)</p>
```javascript
import { Tabs } from "expo-router";


export default function TabsLayout() {
    return (
        <Tabs
            screenOptions={{ 
                |
            }}
        >
            <Tabs.Screen name="|" options={{ | }} />
        </Tabs>
    )
}
```

# Demo
![Demo of how some snippets work](https://raw.githubusercontent.com/yu1iaw/react-snippets-extension/main/images/Demo.gif)

**That's it! Install and happy coding!**

---
## What's next
What is next? Ouch! I guess `NEXT` is next.😉




