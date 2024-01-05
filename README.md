# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:


```
npx hardhat help
```

<h1>Testing contracts</h1>

  ```
  npx hardhat test
  ```
  ```
  REPORT_GAS=true npx hardhat test
  ```
<h1>Deploying your contracts</h1>

  ```
  npx hardhat node
  ```
  ```
  npx hardhat run scripts/deploy.ts
  ```
  
  <p>You can deploy in local with hardhat: This is command </p>

```
npx hardhat run --network localhost scripts/deploy.ts
```

<h1>Verifying your contracts</h1>
 <p>You can get Sepolia eth</p>
 <p>https://sepoliafaucet.com/</p>
 <p>To be fair to all developers, You only get 0.5 Sepolia ETH every 24 hours.<p>

<h1>Writing tasks and scripts</h1>
<p>Here's a script that does the same as our accounts task. Create an accounts.js file in the scripts directory with this content:</p>
<p>https://hardhat.org/hardhat-runner/docs/guides/tasks-and-scripts</p>
<h1>Using the Hardhat console</h1>
<h3>npx hardhat console</h3>
<p>config</p>
<p>ethers</p>
<p>hre.ethers</p>
<h1>Using TypeScript</h1>
<p>https://hardhat.org/hardhat-runner/docs/guides/typescript</p>
<h1>Using the Hardhat console</h1>
<p>https://hardhat.org/hardhat-runner/docs/guides/command-line-completion</p>
<p>To use the Hardhat shorthand you need to install it globally<p>


```
npm install --global hardhat-shorthand
```

<h3>Installing the command-line completions</h3>
<p>To enable autocomplete support you'll also need to install the shell completion script using hardhat-completion, which comes with hardhat-shorthand. Run hardhat-completion install and follow the instructions to install the completion script:</p>

```
$ hardhat-completion install
✔ Which Shell do you use ? · zsh
✔ We will install completion to ~/.zshrc, is it ok ? (y/N) · true
=> Added tabtab source line in "~/.zshrc" file
=> Added tabtab source line in "~/.config/tabtab/zsh/__tabtab.zsh" file
=> Wrote completion script to /home/fvictorio/.config/tabtab/zsh/hh.zsh file

      => Tabtab source line added to ~/.zshrc for hh package.

      Make sure to reload your SHELL.
```