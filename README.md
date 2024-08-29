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


















## JANCOKK

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF







