## For Developers:

Clone the source locally:

```bash
$ git clone https://github.com/arihantbansal/khalo-backend.git
$ cd khalo-backend
```

Install project dependencies:

```bash
$ npm install
```

Create environment variables:

```bash
$ touch .env
```

Enter the env variables in the `.env` file

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
