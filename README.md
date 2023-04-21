## Learning using Postgres, Koa, React and Node with TypeScript

[Github Repo](https://github.com/gurnitha/PKRN-Postgres-Koa-React-Node)

[My Learning](https://www.udemy.com/course/url-shortener-nodejs-typescript-koa-postgresql-knex-arabic/learn/lecture/37278984#overview)


## 1. Setup


#### 1.1 Modified README.md file


#### 1.2 Install modules for devDependencies
        
        Activities:

        1. Install modules

        λ npm init -y
        λ npm install -D typescript ts-node @types/node
        λ npx tsc --init

        new file:   package-lock.json
        new file:   package.json
        new file:   tsconfig.json


#### 1.3 Setup src, build and include files in tsconfig.json
        
        Activities:

        1. Create src, build folders
        2. Setup them in tsconfig.json file

        modified:   README.md
        modified:   tsconfig.json


#### 1.4 Create index.ts file and how to execute it
        
        Activities:

        1. Install modules

        λ npm install -g ts-node typescript

        2. Execute index.ts inside src folder

        λ ts-node .\src\index.ts

        3. Execute ts

        λ tsc

        4. Execute index.js inside build folder

        λ node .\build\index.js 


#### 1.5 Install eslint and other modules
        
        Activities:

        1. Install eslint with options


        λ npx eslint --init
        You can also run this command directly using 'npm init         @eslint/config'.
        Need to install the following packages:
          @eslint/create-config@0.4.3
        Ok to proceed? (y) y
        √ How would you like to use ESLint? · style
        √ What type of modules does your project use? · esm
        √ Which framework does your project use? · none
        √ Does your project use TypeScript? · No / Yes
        √ Where does your code run? · browser
        √ How would you like to define a style for your project? · guide
        √ Which style guide do you want to follow? ·         standard-with-typescript
        √ What format do you want your config file to be in? · JavaScript
        Checking peerDependencies of         eslint-config-standard-with-typescript@latest
        Local ESLint installation not found.
        The config that you've selected requires the following dependencies:

        eslint-config-standard-with-typescript@latest         @typescript-eslint/eslint-plugin@^5.43.0 eslint@^8.0.1 eslint-plugin-import@^2.25.2 eslint-plugin-n@^15.0.0 eslint-plugin-promise@^6.0.0 typescript@*
        √ Would you like to install them now? · No / Yes
        √ Which package manager do you want to use? · npm

        λ npm install -D nodemon

        To start server: 

        Before: λ nodemon .\src\index.ts

        After :λ npm start or λ npm run start

        new file:   .eslintrc.js
        modified:   README.md
        new file:   build/index.js
        modified:   package-lock.json
        modified:   package.json
        new file:   src/index.ts

        NEXT: Models