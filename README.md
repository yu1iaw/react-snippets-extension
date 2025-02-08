## Before we start 🟠

You can remember and find the right keys for these snippets on your keyboard with ease. Add this awesome set to boost your productivity.⚡

> **Note**: kebab-case, snake_case, camelCase are formatted in PascalCase. <br />
E.g. primary-btn.jsx + `asfr` turns into `export default function PrimaryBtn() {}` etc.


Finally, I dedicate this extension to my dad, who celebrates his birthday on `13`th of May.👋🎉

# Overview

| Snippet | Description                       |                  |
| ------- | --------------------------------- |----------------- |
| `asy`   | *Arrow function named export*     | [ℹ️](#example1)  |
| `asd`   | *Arrow function default export*   | [ℹ️](#example2)  |
| `asfr`  | *File related function*           | [ℹ️](#example3)  |
| `aswr`  | *Folder related function*         | [ℹ️](#example4)  |
| `uas`   | *useActionState hook*             | [ℹ️](#example5)  |
| `us`    | *useState hook*                   | [ℹ️](#example6)  |
| `uo`    | *useOptimistic hook*              | [ℹ️](#example7)  |
| `uref`  | *useRef hook*                     | [ℹ️](#example8)  |
| `ue`    | *useEffect hook*                  | [ℹ️](#example9)  |
| `ule`   | *useLayoutEffect hook*            | [ℹ️](#example10) |
| `cctx`  | *Create Context*                  | [ℹ️](#example11) |
| `fli`   | *FlatList*                        | [ℹ️](#example12) |
| `ec`    | *Expo Component*                  | [ℹ️](#example13) |
| `ss`    | *StyleSheet*                      | [ℹ️](#example14) |
| `ssac`  | *StyleSheet align center*         | [ℹ️](#example15) |
| `ssrw`  | *StyleSheet row*                  | [ℹ️](#example16) |
| `ess`   | *Export StyleSheet*               | [ℹ️](#example17) |
| `ersea` | *useLocalSearchParams hook*       | [ℹ️](#example18) |
| `ers`   | *Expo Router Stack layout*        | [ℹ️](#example19) |
| `ert`   | *Expo Router Tabs layout*         | [ℹ️](#example20) |


<br />

# React
> **Note**: In examples below the vertical bar `|` is just a positioned cursor.


<br />

### <p id="example1">`asy` : 💡 Arrow function named export [⬆️](#overview)</p>
```javascript
export const Example = () => {
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
export default function Example() {
    return (
        <>|</>
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
### <p id="example5">`uas` : 💡 useActionState hook [⬆️](#overview)</p>
```javascript
const [error, action, isPending] = useActionState(fn, null);
```
### <p id="example6">`us` : 💡 useState hook [⬆️](#overview)</p>
```javascript
const [|, set|] = useState("");
// press `Tab` after typing the value and let magic happen
```
### <p id="example7">`uo` : 💡 useOptimistic hook [⬆️](#overview)</p>
```javascript
const [optimistic|, setOptimistic|] = useOptimistic(asyncRes, (state, action) => {});
// press `Tab` after typing the value and let magic happen
```
### <p id="example8">`uref` : 💡 useRef hook [⬆️](#overview)</p>
```javascript
const |Ref = useRef(null);
```
### <p id="example9">`ue` : 💡 useEffect hook [⬆️](#overview)</p>
```javascript
useEffect|(() => {
    
}, [])
// press `Ctrl`+`Space` to import useEffect
```
### <p id="example10">`ule` : 💡 useLayoutEffect hook [⬆️](#overview)</p>
```javascript
useLayoutEffect|(() => {
    
}, [])
// press `Ctrl`+`Space` to import useLayoutEffect
```
### <p id="example11">`cctx` : 💡 Create React Context [⬆️](#overview)</p>
```javascript
import { createContext, useContext } from "react";

export const |Context = createContext(null);

export const |ContextProvider = ({ children }) => {
    

    return (
        <|Context value={{}}>
            {children}
        </|Context>
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

### <p id="example12">`fli` : 💡 FlatList [⬆️](#overview)</p>
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
### <p id="example13">`ec` : 💡 Expo Component [⬆️](#overview)</p>
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
### <p id="example14">`ss` : 💡 StyleSheet [⬆️](#overview)</p>
```javascript
const styles = StyleSheet|.create({
    
})
```
### <p id="example15">`ssac` : 💡 StyleSheet align center [⬆️](#overview)</p>
```javascript
container: {
    flex: 1,
    justifyContent: "center",
    alignItems: "center",
    gap: 16,|
},
```
### <p id="example16">`ssrw` : 💡 StyleSheet row [⬆️](#overview)</p>
```javascript
rowContainer: {
    flexDirection: "row",
    justifyContent: "space-between",
    alignItems: "center",
    margin: 16,|
},
```
### <p id="example17">`ess` : 💡 Export StyleSheet [⬆️](#overview)</p>
```javascript
import { StyleSheet } from "react-native";

export default StyleSheet.create({
    mainContainer: {
        flex: 1,
        backgroundColor: "#fff",|
    },
})
```
### <p id="example18">`ersea` : 💡 useLocalSearchParams hook [⬆️](#overview)</p>
```javascript
const { } = useLocalSearchParams();
```
### <p id="example19">`ers` : 💡 Expo Router Stack layout [⬆️](#overview)</p>
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
### <p id="example20">`ert` : 💡 Expo Router Tabs layout [⬆️](#overview)</p>
```javascript
import { Tabs } from "expo-router";


export default function TabsLayout() {
    return (
        <Tabs
            screenOptions={{|}}
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
## Lastly
Just to make your work with this extension more comfortable, you can disable [abc] suggestion in VS Code using following steps: 

##### `Ctrl + ,` opens **Settings**⚙️ > type "show words" in the **Search** field > uncheck **'Editor>Suggest: Show Words'**




