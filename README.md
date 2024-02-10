# SnapSwift - Chat Application 

![Screenshot 2024-02-10 160829](https://github.com/ShreyanshEC088/SnapSwift/assets/114645979/88e6a7d3-09e5-4968-ad00-14481a9b1e92)

![Screenshot 2024-02-10 160819](https://github.com/ShreyanshEC088/SnapSwift/assets/114645979/6426407a-b6fa-47b2-98ad-ee530458f32b)

![Screenshot 2024-02-10 161445](https://github.com/ShreyanshEC088/SnapSwift/assets/114645979/da9d1fb3-cc3f-4593-a21d-c897d3f73ecc)


## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/ShreyanshEC088/SnapSwift
cd SnapShift
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
