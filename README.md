# CryptNote

> Encryption service

![CryptNote](screenshot.png)

```yml
node version: 16.16.0
```

## Quick Start 🚀

### Add a `default.json` file in `config` folder with the following

```json
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
$ npm install
```

### Install client dependencies

```bash
$ cd client
$ npm install
```

### Run both Express & React from root

```bash
$ npm run dev
```

### Build for production

```bash
$ cd client
$ npm run build
```

### Test production before deploy

After running a build in the client 👆, cd into the root of the project.  
And run...

**Linux/Unix**

```bash
$ NODE_ENV=production node server.js
```

**Windows Cmd Prompt or Powershell**

```bash
$ $env:NODE_ENV="production"
$ node server.js
```

Check in browser on [http://localhost:5000/](http://localhost:5000/)

&copy; 2022-2023 @fullstackDev. All rights Reserved.
