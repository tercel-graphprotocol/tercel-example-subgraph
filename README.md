# Example Subgraph

An example to help you get started with The Graph. For more information see the docs on https://thegraph.com/docs/.

Steps:
1) Register an account in https://thegraph.com/explorer/
2) Install Graph CLI globally on your machine 
` yarn global add @graphprotocol/graph-cli `
3) Init Subgraph
```
yarn install
yarn codegen
```
4) Deploy Subgraph
```
graph deploy --access-token <ACCESS_TOKEN> \
    --debug \
    --node https://api.thegraph.com/deploy/ \
    --ipfs https://api.thegraph.com/ipfs/ \
    <GITHUB_USERNAME>/<SUBGRAPH_NAME>
```