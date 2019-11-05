***Usecase***: 
      At present, in pharmacology one of the most serious problems is counterfeit drugs.
      The Health Research Funding organization reported that in developing countries, nearly 10–30% of
      the drugs are fake. Counterfeiting is not the main issue itself, but, rather, the fact that, as compared to
      traditional drugs, these counterfeit drugs produce different side effects to human health. According to
      WHO, around 30% of the total medicine sold in Africa, Asia, and Latin America is counterfeit. This is
      the major worldwide problem, and the situation is worse in developing countries, where one out of
      every 10 medicines are either fake or do not follow drug regulations. The rise of Internet pharmacies
      has made it more difficult to standardize drug safety. It is difficult to detect counterfeits because
      these drugs pass through different complex distributed networks, thus forming opportunities for
      counterfeits to enter the authentic supply chain. The safety of the pharmaceutical supply chain has
      become a major concern for public health, which is a collective process. **In this we are using
      a novel drug supply chain management using Hyperledger Fabric based on blockchain technology to
      handle secure drug supply chain records. This is like a POC which solves this problem by conducting
      drug record transactions on a blockchain to create a smart healthcare ecosystem with a drug supply
      chain**
      
**Installation instructions**

-- Make sure you have Node.js, Go and Docker (CE edition is fine) installed.

--Install Hyperledger

-- Clone this repository
-- From the drup-app folder, to remove any pre-existing Docker containers, run:

-- docker rm -f $(docker ps -aq)

-- Start up Hyperledger

-- sudo ./startFabric.sh

Now we install the required Node packages and register the Admin and User components of the network before starting the application.

-- npm install

-- node registerAdmin.js

-- node registerUser.js

-- node server.js

The client should launch on localhost:8000 in any web browser.
