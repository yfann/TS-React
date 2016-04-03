#TS-React

This is sample project for develop react+typescript+less using vs code+webpack.

##SetUp 

+ install vs code

+ install nodejs

+ [setup typescript project](https://code.visualstudio.com/Docs/languages/typescript)

    - cmd:npm install -g typescript(use npm to manage tsc version so remove tsc in path of environment of windows OS)

    - create tsconfig.json
    
      set rootDir,outDir
    
    - create tasks.json
    
      set compiling based on a tsconfig.json
    
    - ctrl+shift+B //build
    
+ install 3rd party lib

    - create package.json
    
    - cmd:npm install
    
+ add React Type definitions

    - cmd:npm install tsd -g
    
    - cmd:tsd init
    
    - cmd:tsd install react --save
        
      ??download [react-global.d.ts](https://raw.githubusercontent.com/borisyankov/DefinitelyTyped/master/react/react-global.d.ts) to typings/react
    
    - change tsconfig.json
    
      set jsx

+ run application

    - cmd:npm install -g http-server
    
    - cmd:http-server
    
    - http://127.0.0.1:8080/  
    
   
 + [integrated webpack](https://www.npmjs.com/package/ts-loader)
 
    - cmd:npm install -g webpack
 
    - cmd:npm install ts-loader --save-dev
    
    - create webpack.config.js
    
    - define entry file (using CMD, not with namespace)
    
    - cmd:webpack
    
 + fix error alert
    
##Config

###[tsconfig.json](http://www.typescriptlang.org/docs/handbook/tsconfig.json.html)

###tasks.json

###[Defined Type](http://definitelytyped.org/)

##Command

###vs code

+ ctrl+K+C/ctrl+K+U //注释

+ shit+alt+a //批量注释

+ ctrl+shift+b //build

+ ctrl+shift+u //build error message


#ref
+ [Working with React and TypeScript](http://blog.wolksoftware.com/working-with-react-and-typescript)
+ [TypeScript and webpack](http://www.jbrantly.com/typescript-and-webpack/)
+ [ES6 modules with TypeScript and webpack](http://www.jbrantly.com/es6-modules-with-typescript-and-webpack/)