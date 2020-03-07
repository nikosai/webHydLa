## 環境構築 (Environment Setup)
1. npmをインストールしておいてください．  
  Install npm.
1. 次を実行．  
  Execute a following command.  
    ```
    /webHydLa/static$ npm install --save-dev typescript ts-node @types/three @types/jquery
    ```
1. 確認．  
  Check.  
    ```
    /webHydLa/static$ npm run ts-node -v
    /webHydLa/static$ npm run tsc -v
    ```

## 動作確認 (Run) 
```
/webHydLa/static$ npm run ts-node parse.ts
```

## トランスパイル (Transpile)
```
/webHydLa/static$ npm run tsc
```