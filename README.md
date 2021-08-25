## For Developers:

Clone the source locally:

```bash
$ git clone https://github.com/swarnabgarang/foodict-backend.git
$ cd foodict-backend
```

Install project dependencies:

```bash
$ npm install
```

Create environment variables:

```bash
$ mkdir config
$ cd ./config
$ touch dev.env
```

Enter the env variables in the `dev.env` file

```
PORT=4001
MONGODB_URI=''
TEST_MONGODB_URI=''
JWT_SECRET_KEY='secret'
```

Start the app:

```bash
$ npm run start
```


## Built with

-   [NodeJS](https://nodejs.org/en/ "NodeJS")
-   [ExpressJS](https://expressjs.com/ "ExpressJS")
