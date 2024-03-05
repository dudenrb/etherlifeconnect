
<a name="readme-top"></a>


<br />
<div align="center">
  <a href="https://github.com/rahulsabinkar/organ-donation-platform">
    <img src="https://i.ibb.co/JmqG0X8/download.png" width="400" height="100" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Etherlife Connect</h3>

  <p align="center">
    A dApp platform connecting organ donor and acceptor via ethereum blockchain.
    <br />
    <!-- <a href="https://github.com/rahulsabinkar/organ-donation-platform"><strong>Explore the docs »</strong></a>
    <br />
    <br /> -->
    <!-- <a href="https://github.com/rahulsabinkar/organ-donation-platform">View Demo</a> -->
  </p>
</div>



## Built With

* [![Solidity][solidity-shield-url]][solidity-url]
* [![Node][node-shield-url]][node-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Prerequisites

You would need these software installed on your machine to run the project.
### node.js

  #### Windows:
  1. Visit the NodeJS web page at https://nodejs.org/en/
  2. Download and install the LTS version.
  3. Download the installer and run it. This will install both NodeJS and NPM (Node
  Package Manager).
  
  Note: If you're on Windows 11, make sure to have latest LTS version of nodejs installed, or else you'll probably run into some issues.


### Truffle
Open the command prompt or terminal and execute the following command.
```sh
npm install -g truffle
```

### Ganache
Visit the Ganache webpage at http://trufflesuite.com/ganache/
Download the platform binary for your OS and install it.

### Git

#### Windows
Install gitbash from https://gitforwindows.org/

## Installation

### Download
1. Open gitbash or terminal.
2. Clone the repo.
   ```sh
   git clone https://github.com/rahulsabinkar/organ-donation-platform.git
   ```
3. Traverse into the app folder.
   ```sh
   cd organ-donation-platform/app
   ```
4. Install npm dependencies.
   ```sh
   npm install
   ```

### Connect Ganache
While the npm dependencies are being installed, follow these instructions.
1. Open ganache.
2. Click on "New Workspace".
3. Select "Add Project" and add the truffle-config.js file located in the folder "organ-donation-platform" you just downloaded.
4. Confirm by pressing "Save Workspace" on the top-right corner.
5. Navigate to the "Contracts" tab and you should notice DonorContract is not deployed.

### Deploy Contract
Back in the gitbash or terminal window instance in which you were downloading npm dependencies, wait for it to finish up and then type in the following commands to deploy the contract.
```sh
truffle compile && truffle migrate
```

### Run the server
Now that everything is set-up, you can run the server.
1. Run the following command
   ```sh
   npm run dev
   ```
2. Open a browser and go to http://localhost:8080/


<p align="right">(<a href="#readme-top">back to top</a>)</p>

