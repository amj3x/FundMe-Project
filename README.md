# FundMe 
FundMe is a crowdfunding smart contract. It allows users to contribute ETH to a project, and the contract owner can withdraw the funds when needed.

## Quickstart
```
git clone https://github.com/amj3x/FundMe-Project.git
cd FundMe-Project
make
```

## Deploy
```
forge script script/DeployFundMe.s.sol
```

## Test
```
forge test
```
## Testing a single function
```
forge test --mt testFunctionName
```
