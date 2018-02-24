### Myth: Hyperledger is a blockchain
Hyperledger is an open source collaborative project hosted by The Linux Foundation.



### Myth: Hyperledger is Hyperledger Fabric
Hyperledger consists of nine different projects -- five frameworks and four tools.



### Myth: Hyperledger is the core software that the other nine projects are built on
Each project is unique software; however, there are collaborative efforts amongst the projects.

Note: In talking with some of the end users of the different Hyperledger frameworks, I have been asked what is implemented inside the core of Hyperledger that the frameworks get for free? I have to admit, when I was asked this question, I was confused. They then clarified the question by comparing Hyperledger to the Linux kernel whereas the frameworks would be like Linux distributions. Unlike the Linux kernel and the individual Linux distributions, each of the individual Hyperledger frameworks is standalone. There are no core components that are shared across all frameworks. That being said, we do see a lot of collaboration that is occurring across our different projects. For example, SETH (Sawtooth Ethereum) came out of a collaboration between the Hyperledger Sawtooth and Hyperledger Burrow communities to develop an EVM Transaction Family for Hyperledger Sawtooth. The Hyperledger Fabric and Hyperledger Burrow communities are working together to bring the EVM to Hyperledger Fabric in the future. We also have an architecture working group within Hyperledger that is looking at understanding the components of the different Hyperledger frameworks to determine if there is a common interface that could be defined for these components. The Hyperledger Architecture - Consensus whitepaper is the first step in this work.



### Myth: Hyperledger is a blockchain network
Hyperledger frameworks provide the software for you to create your own blockchain networks.

Note: Unlike Bitcoin and Ethereum, which provide public blockchain networks, Hyperledger frameworks are designed for enterprise usage. As such, there is no single "Hyperledger network" that you can utilize for your application. Instead, you will use one of the Hyperledger frameworks to create a network for your use case. This network will run on-premises within your own data center or using the infrastructure of a cloud provider. This would be the same as using Oracle or MySQL within your systems. There is no one "Oracle database" or one "MySQL database" that all data is stored on, but rather a number of distinct databases set up for your application purposes.
