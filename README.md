# Nillion-Verifier

You should now be able to run the following in a command line to get the version number of your Docker installation:

Getting the Docker version
docker --version
Which should return a version number like the following:

```sh  Docker version 27.1.1, build 63125853e3 ```



faucet : ```sh https://faucet.testnet.nillion.com/ ```



Initialising the accuser


Create a local directory to store state.

```sh mkdir -p nillion/accuser ```
Then initialise the accuser in the mounted directory.

```sh docker run -v ./nillion/accuser:/var/tmp nillion/retailtoken-accuser:v1.0.0 initialise .```
This will output the details needed to register the accuser on the website, register them below:

accound_id: Nillion address of the accuser
public_key: Public Key of the accuser
Note The accuser will store the credentials in a file called credentials.json in the folder that was created. If you lose this file, you will lose access to the keys/address of the accuser.





auto install : 
```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```
