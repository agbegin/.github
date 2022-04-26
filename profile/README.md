<p align="center">
  <img src="https://raw.githubusercontent.com/GaloyMoney/.github/main/img/galoy-repo.png" width="297" height="72" alt="GaloyMoney - Developing the open source standard for Bitcoin banking" />
</p>

## ⚡ Developing the open source standard for Bitcoin banking. ⚡

Engineers employed by Galoy lead and actively maintain this free and open source GaloyMoney core Bitcoin banking platform. The platform was originally built as the foundation for the Bitcoin Beach Wallet (See: [Bitcoin Banking for Communities](https://galoy.io/bitcoin-banking-for-communities-lessons-learned-from-el-zonte/)). 

The FOSS project has attracted dozens of open source developers who contribute regularly to the codebase alongside the Galoy engineers. 

GaloyMoney repositories have been forked over 100 times, most notably by [Bitcoin Jungle](https://bitcoinjungle.app/) - a GaloyMoney-based community bank in Costa Rica that seeks to replicate the success of the Bitcoin Beach community with Galoy's proof-of-concept Bitcoin Beach Wallet.

The GaloyMoney platform includes foundational parts for launching a Bitcoin bank:

### Infrastructure – for deploying the backend
- [**`galoy-infra`**](https://github.com/GaloyMoney/galoy-infra) – Terraform modules that can be used to bring up a robust infrastructure implementation suitable for running the galoy stack
- [**`charts`**](https://github.com/GaloyMoney/charts) – Kubernetes Helm charts for deploying galoy applications to your desired infrastructure.


### Backend – A collection of repos that can be used to deploy the backend components required to support a bitcoin community bank. 
- [**`galoy`**](https://github.com/GaloyMoney/galoy) – Backend application that interacts with the bitcoin and accounting layers to enable sending, receiving and holding balances.

- [**`price`**](https://github.com/GaloyMoney/price) – Service for providing realtime price data from multiple exchanges via gRPC endpoints.

- [**`dealer`**](https://github.com/GaloyMoney/dealer) – Service for implementing fiat hedging strategies via supported exchanges.

### API – API implementation & documention for communicating with a galoy instance backend.

- **`tutorial`** – one [tutorial focused on USD integration](https://studio.apollographql.com/public/galoy-hackathon/explorer?variant=current), and another [tutorial with BOLT.Fun](https://bolt.fun/guide/web-services/galoy) to get started.

- [**`documentation`**](https://galoymoney.github.io/galoy/), [**`end-user graphql schema`**](https://github.com/GaloyMoney/galoy/blob/main/src/graphql/main/schema.graphql) & [**`admin graphql schema`**](https://github.com/GaloyMoney/galoy/blob/main/src/graphql/admin/schema.graphql) schemas – GraphQL APIs for end-user and admin operations against a galoy instance backend.

### Frontend – A collection of repos that can be used by administrators and end-users to interact with a deployed galoy instance.

- [**`galoy-mobile`**](https://github.com/GaloyMoney/galoy-mobile) - Android/iOS mobile wallet for end-users of a galoy instance.

- [**`galoy-pay`**](https://github.com/GaloyMoney/galoy-pay) – A single page app that allows each user of a galoy instance to share their galoy instance vanity url to receive payments via the Lightning Network.

- [**`admin-panel`**](https://github.com/GaloyMoney/admin-panel) – A web application which lets a support team manage users and transactions on their galoy instance.  

</br>

## Get Started
Getting started with Galoy is easy. Yet, there are so many things to learn and explore! We recommend to join the [Galoy Slack](galoymoney-workspace.slack.com) and start with exploring the Galoy API in the [Hackathon environment](https://studio.apollographql.com/graph/galoy-hackathon/home?variant=current).

## Galoy Banking as a Service Implementation 
Galoy, Inc. is a for-profit company that offers implementation, customization and maintenance. Learn more and reach out at [galoy.io](https://galoy.io).

### We're Hiring
Want to work on driving Lightning adoption? Check out the latest job postings at [Bitcoiner Jobs](https://bitcoinerjobs.com/company/galoy)

### Further Reading 
- Galoy was built on the idea that Lightning will replace "Layer 2" networks like Visa and Mastercard. Read the thesis from July 2020: "[Lightning as a Retail Payment System](https://medium.com/galoymoney/lightning-as-a-retail-payment-system-part-1-7463c46342ef)."

<img width="120" alt="Galoy logo" src="https://raw.githubusercontent.com/GaloyMoney/.github/main/img/galoy.png">
