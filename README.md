# VeriTrace
React Native app for product tracking and authentication via RFID chips and the Hyperledger Fabric blockchain.

Technologies used:
- React Native
- react-native-nfc-manager
- Amazon Web Services (Lambda function, Amazon Managed Secrets, Amazon Managed Blockchain)


1) User scans RFID chip using VeriTrace mobile app
2) Scan event triggers API call to Lambda 
3) Lambda retrieves credentials from AWS Secrets Manager and queries product data from the HyperLedger Fabric blockchain. 
4) Lambda then returns the query response from the blockchain network to VeriTrace. <br> <br>

<p align="center">
<img src = "https://user-images.githubusercontent.com/99369436/231776250-27dde7f8-8928-4f10-8208-ce399366040d.png" width=20% height=20%> <img src = "https://user-images.githubusercontent.com/99369436/231776296-edd90807-ad0d-4807-a086-5a9518e1e3d0.png" width=20% height=20%> <img src = "https://user-images.githubusercontent.com/99369436/231776334-afe311f7-ac3f-4ff6-b99b-152e9089171f.png" width=20% height=20%> <img src = "https://user-images.githubusercontent.com/99369436/231776405-00383c3b-86d3-47d2-aa2a-c7b5444cf44f.png" width=20% height=20%>
