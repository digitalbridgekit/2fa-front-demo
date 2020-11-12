# Chainlink Oracle 2FA frontend demo 

![Google Authenticator 2FA first screen](/src/img/screenshot1.png)

Packages used:
* "@material-ui/core": "^4.11.0",
* "@material-ui/icons": "^4.9.1",
* "@material-ui/lab": "^4.0.0-alpha.56",
* "@testing-library/jest-dom": "^4.2.4",
* "@testing-library/react": "^9.5.0",
* "@testing-library/user-event": "^7.2.1",
* "jshint": "^2.12.0",
* "react": "^16.13.1",
* "react-dom": "^16.13.1",
* "react-scripts": "3.4.1",
* "web3": "^1.2.11"

# How to test this demo online

1) Install metamask https://docs.chain.link/docs/install-metamask#install--configure
2) Fund your address with Ether
https://docs.chain.link/docs/install-metamask#fund-your-address-with-ether
3) Install Google Authenticator app for andriod tap here
https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2 , for ios
tap here https://apps.apple.com/es/app/google-authenticator/id388497605
4) Tap this link https://digitalbridge.sismatech.com.ar:3000/  (the demo is momentarily offline)
5) Open Google Autenthicator app, tap plus button and scan QR code
6) Copy the PIN code
7) Tap the NEXT button
8) Paste PIN code
9) Tap SEND button
10) Wait the result


Digital Bridge IO
https://twitter.com/DigitalBridgeIO

Sample screenshots 

![Google Authenticator 2FA second screen](/src/img/screenshot2.png)
 
![Google Authenticator 2FA resut screen](/src/img/screenshot3.png)

## How backend works 

[![Demo Two-Factor Authentication for smart Contracts](https://img.youtube.com/vi/6Yh3rmcrKRc/0.jpg)](https://www.youtube.com/watch?v=6Yh3rmcrKRc "Demo Two-Factor Authentication for smart Contracts")


## How to install

Install NodeJs version 12 or superior

### Steps to complete installation:

In Remix https://remix.ethereum.org/
* Create new file from src/contract/GoogleAuthenticatorPINCheck.sol 
* Compile this smartcontract
* Deploy it into Ethereum Ropsten testnet
  
Next steps: 
* Download this repository
* unzip downloaded file
* setup src/config.js file with contract address and ABI json from deployed contract
* To install dependencies, run "npm install" command.
* exec "npm install express"
* To run the demo, exec "npm start"
* To test the demo follow these steps:
  * Install metamask https://docs.chain.link/docs/install-metamask#install--configure
  * Fund your address with Ether
https://docs.chain.link/docs/install-metamask#fund-your-address-with-ether
  * Install Google Authenticator app for andriod tap here
https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2 , for ios
tap here https://apps.apple.com/es/app/google-authenticator/id388497605
  * Tap this link http://localhost:3000/
  * Open Google Autenthicator app, tap plus button and scan QR code
  * Copy the PIN code
  * Tap the NEXT button
  * Paste PIN code
  * Tap SEND button
  * Wait the result
