# Project Name
Inventory-management-system using typescript with mongodb and prisma


## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (v20.14.0)
- [TypeScript](https://www.typescriptlang.org/) (v5.6.2)
- [Prisma](https://www.prisma.io/) (v5.19.1)
- Any other dependencies

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AmitUpadhyay878/nodejs-ts-inventory-sysntem-092024.git

   ```

 2. check typescript version:

  ```bash 
  npx tsc -v
  ```

 3. install typescript into our project
   ```bash
   npm i -D typescript @types/node   
   ```

 4. create a typescript.config file

    ```bash
    npx tsc --init   
    ```
 
 5. install Prisma with mongodb datasource provider

   ```bash
   npx prisma init --datasource-provider mongodb      
   ```

 ## below packages are used
  ### Main dependencies:

   ```bash
  npm install express @types/express cors dotenv bcrypt @types/bcrypt prisma @prisma/client
  ```

  ### Development dependencies:
   
     ```bash   
      npm install --save-dev tsc-alias ts-node-dev tsconfig-paths 
      
