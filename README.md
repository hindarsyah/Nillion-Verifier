# Nillion-Verifier

## Intro CAK

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Site | Wakwaw |
| ------ | ------ |
| Website | https://verifier.nillion.com |
| Faucet |  https://faucet.testnet.nillion.com |





 




## Set up for Linux



### auto install : 

#### 1. Verifying Docker install
```sh
docker --version
```

```sh
Docker version 27.1.1, build 63125853e3
```




#### 2. Initialising the accuser
 
#### Create a local directory to store state.

```sh
mkdir -p nillion/accuser
```

#### Then initialise the accuser in the mounted directory.
```sh
docker run -v ./nillion/accuser:/var/tmp nillion/retailtoken-accuser:v1.0.0 initialise
```
This will output the details needed to register the accuser on the website, register them below:

#### accound_id: Nillion address of the accuser
#### public_key: Public Key of the accuser

















Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the right
- ✨Magic ✨

## Features

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF



## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```



## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```



