# Issues & Recommendations for Wormhole Documentation  

## 1) **Deprecation of Polygon RPC**  
The RPC for **Polygon** is deprecated and requires an update.  

🚨 **Action Required:**  
- Ensure the correct RPC endpoint is used.  

![Polygon RPC Deprecation](https://github.com/user-attachments/assets/8e1caadd-2de0-44f0-9f7d-c8fbc0a79e0a)  

## 2) **Incorrect Base Network Reference**  
The documentation references **Base Goerli**, which is deprecated.  

🚨 **Action Required:**  
- Update to **Base Sepolia** or the correct testnet/mainnet reference.  

![Base Goerli Reference](https://github.com/user-attachments/assets/a008540e-d206-48dc-a108-00767031f071)  

## 3) **Incorrect Naming for Polygon Testnet**  
The testnet is incorrectly labeled **PolygonSepolia**.  

🚨 **Action Required:**  
- Update the name to **Polygon Amoy**.  
- Use the correct RPC: **`https://rpc-amoy.polygon.technology`**.  

## 4) **Lack of a Centralized Supported Chains List**  
There is no **single, centralized** reference listing all supported **testnets and mainnets**.  

🚨 **Action Required:**  
- A **dedicated section** should clearly document all supported chains, their RPCs, and testnet/mainnet availability.  

## 5) **Aptos Testnet is Deprecated**  
The **Aptos Testnet** is no longer functional.  

🚨 **Action Required:**  
- Remove or replace references to Aptos Testnet.  

![Aptos Testnet Deprecation](https://github.com/user-attachments/assets/f9da579a-f1e5-4165-91aa-daa858b1a03d)  

## 6) **Excessive Delay in Fetching VAA Bytes**  
Retrieving **VAA bytes** takes significantly longer than expected.  

🚨 **Action Required:**  
- Optimize response times for fetching VAAs.  
- Provide **timeout recommendations** for developers.  

![VAA Fetching Delay](https://github.com/user-attachments/assets/8fa4992b-6585-4c0d-b646-a2eb5ad0c554)  

## 7) **Unexpected Chain Behavior in Testnet**  
- Using **Ethereum as the chain on Testnet** did not work, despite utilizing **Sepolia RPC**.  
- However, explicitly setting the **source chain to Sepolia** resolved the issue.  

🚨 **Action Required:**  
- Investigate inconsistencies in **chain behavior** and ensure uniformity across networks.  

## 8) **Lack of Timeout Recommendations**  
There is no guidance on **standard timeout durations** for different network operations.  

🚨 **Action Required:**  
- Clearly define **timeout settings** for various chains and processes.  
- In testing, **Sepolia required manual timeout adjustments (20 mins)** to function properly.  

## 9) **Lack of a Quickstart Guide**  
The documentation lacks a **clear and concise** quickstart example for bridging assets.  

🚨 **Action Required:**  
- Introduce a **step-by-step Quickstart Guide** for bridging assets.  
- The current learning curve is steep—users report spending **7+ hours** navigating the documentation, when the process should take **15 minutes**.  

