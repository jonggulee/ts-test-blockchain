# test-blockchain-typescript

Make Blockchain with Typescript

# Requirement
1. node
2. typescript
3. crypto-js
4. tsc-watch


# Setting Typescript Up
1. Install
```
# node
brew install node

# yarn
npm install --global yarn

# tsc-watch
yarn add tsc-watch --dev

# crypto-js
yarn add crypto-js
```

2. Install typescript
```
yarn global add typescript
```

3. Start yarn
```
yarn start
```

# Testing
## Create block
```
createNewBlock("{Block Name}");
```
## Validate block
* Checking previous hash in log
```
console.log(blockchain);
```
