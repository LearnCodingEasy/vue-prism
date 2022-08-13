# vue-prism

# INSTALL
```
npm i prismjs
```
```
npm i vue-prism-component
```

# IMPORT
#### import in File Main.js To Make Prism Global For Using In App

```
import 'prismjs
```
# Can You Chose Theme
```
import "prismjs/themes/prism-coy.css";
```

```
import "prismjs/themes/prism-dark.css";
```
```
import "prismjs/themes/prism-okaidia.css";
```
```
import "prismjs/themes/prism-solarizedlight.css";
```
```
import "prismjs/themes/prism-tomorrow.css";
```
```
import "prismjs/themes/prism-twilight.css";
```
```
import "prismjs/themes/prism.css";
```
# USE
#### Html
```
<prism language="javascript">{{ code }}</prism>
```
#### Import
```
import Prism from "vue-prism-component";
```
#### Data
```
Data(){
    return{
        code: "const a = b",
    }
},
```
#### Components
```
components: {Prism,},
```