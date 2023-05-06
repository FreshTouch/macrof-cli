# Macrof MF compiler

## Install
<blockquote>
  yarn add @macrof/compiler --dev
</blockquote>

## Init
```typescript
import Micro from "@macrof/compiler";

export default new Micro({
    isShell: true,
    devServer, // your dev server configs
    plugins, // your plugins configs
    ...configs, // other configs
}).configure();
```
