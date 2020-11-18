#### SafeKeep

- To get environment set for local development run the following command in your console
* `yarn` - This installs all necessary package(s)
* `yarn dev` - This starts the local server

### To Test on Live server
- Go To  [SafeKeep](https://adoring-golick-36243b.netlify.app/client/html/)
- On metamask, switch to the ropsten network
- Click on the login button on our page to connect
- Once you connect, you'll be redirected to your wallet
- To Deposit, simply click on the deposit button and a modal will appear
- Enter an amount greater than 0.001 Ether and a valid backup address and then deposit funds
- For withdrawal, simply click on the withdraw button on the header and a modal will appear, you can decide to withdraw some of your deposited ether by entering an amount less than your balance, but if you want to withdraw all just click on withdraw
- To Ping the contract at a time within a month, just click on the ping function
- After 6 months of no pings, the contract should automatically disburse the funds to your backup address
