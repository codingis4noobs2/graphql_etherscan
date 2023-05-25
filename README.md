# GraphQL With Etherscan APIs Bounty

## What is this project about?
This project aims to complete the [GraphQL With Etherscan APIs Bounty](https://app.stackup.dev/bounty/graphql-with-etherscan-apis), You can fetch the balance of a single user and check the total supply of ether using etherscan APIs
For more details check this out:
- Get Ether Balance for a Single Address (https://docs.etherscan.io/api-endpoints/accounts#get-ether-balance-for-a-single-address)
- Get Total Supply of Ether (https://docs.etherscan.io/api-endpoints/stats-1#get-total-supply-of-ether) 

## Deliverables
![image](https://github.com/codingis4noobs2/graphql_etherscan/assets/87560178/65d037b5-8891-47c2-9a82-cdfd9deb30f0)

## How to get started with this project on your machine:
1. Sign up for a new [Etherscan account](https://etherscan.io/register) to generate your API key if you do not have one. 
2. Clone this git repository 
3. Create a new .env file and create a `ETHERSCAN_API` key variable to insert your Etherscan API key value
4. Run the `$npm install` command to install the necessary dependencies
5. Run the `$node index.js` command to initialise the GraphQL server and run your queries

### What i learned while completing this bounty:
1. I learned how to define a GraphQL schema using the GraphQL schema language. The schema describes the available queries and their return types.

2. I became familiar with Apollo Server, which is a popular implementation of a GraphQL server. You learned how to create an instance of Apollo Server, provide it with the schema and resolver functions, and start the server.

3. I learned how to create a custom data source by extending the RESTDataSource class provided by Apollo. This allowed you to encapsulate the logic for making API requests to the Etherscan API and fetch Ethereum-related data.

4. I learned how to define resolver functions that correspond to the queries defined in the schema. These resolver functions handle the request and response flow, fetching data from the data sources and returning the results to the client.

5. I gained knowledge of how to interact with the Etherscan API to retrieve Ethereum blockchain data. Specifically, you learned how to fetch the Ether balance for a specific address and retrieve the total supply of Ether.
