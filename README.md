# GitHub Account NFT Tapp - MVP

## Overview
The **GitHub Account NFT Tapp** MVP allows developers to mint dynamic NFTs based on their **GitHub contributions**. These NFTs display meaningful information about the developer's work, such as **pull requests merged**, **issues closed**, and **top repositories**, while allowing **Twitter followers** to interact with the NFTs using the **Tlink extension**.

## Features
1. **Meaningful GitHub Metrics**: The NFT automatically pulls and displays key data from the developer’s GitHub profile.
    - **GitHub Username and Profile Picture**
    - **Pull Requests Merged**
    - **Issues Closed**
    - **Top Repositories**
    - **Languages Used**

2. **Interactive Features for Twitter Audience**: When the NFT is shared on Twitter, users with the **Tlink extension** can interact with it directly through two key actions:
    - **Give Kudos (Thumbs Up)**: Twitter users can give the developer kudos via the NFT’s frontend. A visible counter shows how many kudos the developer has received.
    - **Crypto Tips**: integrate with Buy me a beer, beers.smartlayer.networkTwitter, users can send **crypto tips** to the NFT owner, allowing developers to be financially supported for their open-source contributions.

## GitHub Profile Integration
- **OAuth for GitHub**: Developers will authenticate with GitHub via OAuth, allowing the app to pull **real-time data** from their GitHub profile.
- **ERC-721 NFT**: Each NFT is unique to the developer and serves as a dynamic representation of their GitHub work, updating automatically as they contribute to repositories.
- **Real-Time Data**: The NFT dynamically updates based on new contributions, such as **pull requests merged** or **issues closed**.

## ERC-721 and TokenScript Integration
- **ERC-721 Standard**: The NFT is generated using the **ERC-721 standard**, ensuring that each developer’s NFT is unique and owned by them.
- **TokenScript**: The **TokenScript frontend** linked to the NFT via **ERC-5169** provides an interactive interface where GitHub data is displayed and social interactions take place.

## Twitter Sharing via Tlink
- The NFT can be easily shared on Twitter using the **Tlink extension**. Once shared, the audience can view the NFT in their feed and interact with it directly (giving kudos or sending crypto tips).

## Roadmap for MVP Development
### Step 1: GitHub Data Integration
- Set up **GitHub OAuth** for user authentication and **GitHub API** integration to pull meaningful data (pull requests merged, issues closed, repositories, languages).
- Design the backend to process and display this data dynamically on the NFT.

### Step 2: ERC-721 NFT and TokenScript Frontend
- Develop the **ERC-721 smart contract** to mint the GitHub profile NFT.
- Build the **TokenScript frontend** to display key GitHub data and enable interactions (give kudos, crypto tips).

### Step 3: Tlink Integration and Twitter Sharing
- Enable easy **Twitter sharing** of the NFT with **Tlink**.
- Ensure that the NFT remains fully interactive when shared on Twitter.

### Step 4: Launch and Testing
- Launch the MVP for early testing by a small group of GitHub users.
- Gather feedback on **interaction features**, **data accuracy**, and **user experience**.

## Benefits
- **Recognition**: Developers can showcase their GitHub contributions in a dynamic, interactive way on social platforms like Twitter.
- **Engagement**: The kudos system provides an easy way for followers to engage and recognize the developer’s work.
- **Monetization**: The crypto tipping feature allows developers to receive financial support for their contributions to open-source projects.

## How to Contribute
We welcome contributions! If you would like to contribute to the **GitHub Account NFT Tapp** project, please follow the steps below:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed explanation of your changes.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
