# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

Custom

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat test
npx hardhat run scripts/deploy.js
npx hardhat node
npx hardhat run scrtipts/deploy.js --network localhost
```
Ket noi metamask (
    them moi mang voi rpc url la http://127.0.0.1:8545/(sau khi chay npx hardhat la co link nay)
    symbol dien la ETH (cai gi cung dc)
    chainID: gõ đại một số rồi out focus input text, nó sẽ đề nghị dc chain id đúng của local vừa run
)
Add thử account 0 (sau khi chạy lệnh npx hardhat node thì có 10 account, chọn address private key accout đầu tiên) -> mở metamask import account rồi dán address mới chọn vào