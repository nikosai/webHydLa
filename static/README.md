## 環境構築 (Environment Setup)
1. npmをインストールしておいてください．  
  Install npm.
1. 次を実行．  
  Execute a following command.  
    ```
    /webHydLa/static$ npm install --save-dev typescript ts-node @types/three @types/jquery @types/ace @types/dat-gui
    npm WARN deprecated @types/three@0.103.2: This is a stub types definition. three provides its own type definitions, so you do not need this installed.
    npm WARN deprecated @types/dat-gui@0.6.3: '@types/dat-gui' is now '@types/dat.gui'
    npm WARN static@1.0.0 No repository field.

    + @types/jquery@3.3.33
    + ts-node@8.6.2
    + typescript@3.8.3
    + @types/three@0.103.2
    + @types/dat-gui@0.6.3
    + @types/ace@0.0.42
    added 15 packages from 67 contributors and audited 15 packages in 3.203s
    found 0 vulnerabilities
    ```

## トランスパイル (Transpile)
```
/webHydLa/static$ npm run tsc
```

## 注意 (Caution)
- tsconfig.jsonで ```"strict": true``` とすると動かなくなる．  
- TypeScriptでTHREEをインポートする（ts/plot.ts 1行目のコメントを解除する）と動かなくなる．