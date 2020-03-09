## 環境構築 (Environment Setup)
1. npmをインストールしておいてください．  
  Install npm.
1. 次を実行．  
  Execute a following command.  
    ```
    /webHydLa/static$ npm install --save-dev typescript ts-node ts-loader webpack webpack-cli @types/ace @types/dat.gui @types/jquery @types/three
    /webHydLa/static$ npm install --save ace dat.gui jquery materialize-css three three-orbitcontrols-ts
    ```

## トランスパイル (Transpile)
```
/webHydLa/static$ npm run tsc
```

## 注意 (Caution)
- tsconfig.jsonで ```"strict": true``` とすると動かなくなる．  
- TypeScriptでTHREEをインポートする（ts/plot.ts 1行目のコメントを解除する）と動かなくなる．