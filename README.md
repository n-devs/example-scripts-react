# Example Scripts React

### Get Started

### npm

```sh
npm install --dev example-script-react
```

### Yarn

```sh
yarn add --dev example-script-react
```

Let you create a directory called `examples` folder in `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── examples
    ├── README.md
    ├── node_modules
    ├── package.json
    ├── .gitignore
    ├── public
    │   ├── favicon.ico
    │   ├── index.html
    │   └── manifest.json
    └── src
        ├── App.css
        ├── App.js
        ├── App.test.js
        ├── index.css
        ├── index.js
        ├── logo.svg
        └── serviceWorker.js
```
 
## Setting Package

***package.json***
```
{
  "name": "examples",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "example-scripts-react start",
    "build": "example-scripts-react build",
    "test": "example-scripts-react test",
    "init": "example-scripts-react init",
    "eject": "example-scripts-react eject"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "react": "^16.8.6",
    "react-dom": "^16.8.6"
  },
  "devDependencies": {
    "example-scripts-react": "1.0.4"
  }
}

```
## Available Scripts

In the project directory, you can run:

### `npm start` or `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test` or `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build` or `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject` or `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.


## คู่มือภาษาไทย

### Available Scripts

ใน project directory คุณสามารถเรียกใช้คำสั่งได้ต่อไปนี้:

### `npm start` or `yarn start`

รันแอพ ในโหมด development.<br>

เปิด  [http://localhost:3000](http://localhost:3000) เพื่อดูในเบราว์เซอร์.

หน้าเว็บจะโหลดใหม่หากคุณทำการแก้ไข.<br>
คุณจะเห็น error ในคอนโซล.

### `npm test` or `yarn test`

ประกาศ test runner ในโหมด interactive watch. <br>
ดูหัวข้อเกี่ยวกับ [running tests](https://facebook.github.io/create-react-app/docs/running-tests) สำหรับข้อมูลเพิ่มเติม.

### `npm run build` or `yarn build`

สร้างแอพสำหรับ production ไปที่ `build` folder.<br>
มันรวมกลุ่มอย่างถูกต้อง React ในโหมด production และปรับโครงสร้างให้เหมาะสมเพื่อประสิทธิภาพที่ดีที่สุด.

build ถูกย่อขนาดและชื่อไฟล์รวมถึง hashes.
แอปของคุณพร้อมที่จะใช้งานแล้ว!.

### `npm run eject` or `yarn eject`

**หมายเหตุ: นี่เป็นการดำเนินการทางเดียว เมื่อคุณ `eject` คุณไม่สามารถกลับไป!**

หากคุณไม่พอใจกับ build tool และตัวเลือกการกำหนดค่า คุณสามารถ `eject` เวลาไหนก็ได้ คำสั่งนี้จะลบการพึ่งพาการสร้างเดียวจากโครงการของคุณ.

Instead มันจะคัดลอกไฟล์การตั้งค่าทั้งหมดและ transitive dependencies (Webpack, Babel, ESLint, etc) ลงในโครงการของคุณเพื่อให้คุณสามารถควบคุมได้อย่างเต็มที่.
ทั้งหมดของ commands except `eject` จะยังคงทำงาน แต่พวกเขาจะชี้ไปที่สคริปต์ที่คัดลอกเพื่อให้คุณสามารถปรับแต่งได้.
เมื่อมาถึงจุดนี้คุณต้องจัดการด้วยตัวเอง.

คุณไม่จำเป็นต้องใช้เลย  `eject` ชุดคุณสมบัติที่คัดสรรแล้วเหมาะสำหรับการปรับใช้ขนาดเล็กและขนาดกลาง และคุณไม่ควรผูกพันที่จะใช้คุณลักษณะนี้.
อย่างไรก็ตามเราเข้าใจว่าเครื่องมือนี้จะไม่เป็นประโยชน์หากคุณไม่สามารถปรับแต่งได้เมื่อคุณพร้อม.
