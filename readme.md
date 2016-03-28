#TS-React

This is sample project for develop react+typescript+less using vs code+webpack.

##SetUp 

+ install vs code

+ [setup typescript project](https://code.visualstudio.com/Docs/languages/typescript)

    - npm install -g typescript

    - create tsconfig.json
    
      set rootDir,outDir
    
    - create tasks.json
    
      set compiling based on a tsconfig.json
    
    - ctrl+shift+B //build
    
+ install 3rd party lib

    - create package.json
    
    - npm install
    
+ add React Type definitions

    - npm install tsd -g
    
    - tsd init
    
    - tsd install react --save
    
    - download [react-global.d.ts](https://raw.githubusercontent.com/borisyankov/DefinitelyTyped/master/react/react-global.d.ts) to typings/react

+ run application

    - npm install -g http-server
    
    - http-server
    
    - http://127.0.0.1:8080/  
    
    
##Config

###[tsconfig.json](http://www.typescriptlang.org/docs/handbook/tsconfig.json.html)

###tasks.json

##Command

###vs code

+ ctrl+K+C/ctrl+K+U //注释

+ shit+alt+a //批量注释

+ ctrl+shift+b //build

+ ctrl+shift+u //build error message


#ref
+ [Working with React and TypeScript](http://blog.wolksoftware.com/working-with-react-and-typescript)