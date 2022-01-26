# Debug

## Compile

- [Understanding TypeScript Configuration Options](https://javascript.plainenglish.io/typescript-configuration-options-tsconfig-json-561d4a2ad4b)
  - saveAs: error TS2686: 'Foo' refers to a UMD global, but the current file is a module. Consider adding an import instead.

  ```json
  {
    "compilerOptions": {
      "allowUmdGlobalAccess": true
    }
  }
  ```
