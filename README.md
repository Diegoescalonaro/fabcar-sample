# hf-fabcar-sample
Car Factory example for Hyperledger Fabric (Network and Chaincode)

## Test network

The [Fabric test network](test-network) in the samples repository provides a Docker Compose based test network with two
Organization peers and an ordering service node. You can use it on your local machine to run the samples listed below.
You can also use it to deploy and test your own Fabric chaincodes and applications. To get started, see
the [test network tutorial](https://hyperledger-fabric.readthedocs.io/en/latest/test_network.html).


## Fabcar chaincode
The [fabcar chaincode](chaincode/fabcar) is a smart contract that allows you to add and change data on the ledger using the Fabric contract API. Also contains an example on how to run chaincode as an external service. Languages: Go, Java, JavaScript, Typescript 