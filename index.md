![Toronto](images/toronto.jpeg) 

Welcome to the first international workshop on Blockchains and Distributed Ledger Technologies (DLTs) @ [ACM SACMAT](http://www.sacmat.org/2019/index.php), on June 3rd, 2019 in Toronto, Canada! The event is hosted at the [Ted Rogers School of Information Technology Management](https://www.ryerson.ca/information-technology-management/), [Ryerson University](https://www.ryerson.ca).

![Ryerson](images/ryersonbuilding.jpeg)

## Objectives

The objective of this one-day workshop is to bring blockchain researchers and 
practitioners together and discuss opportunities to exploit blockchain and DLTs across a variety of application domains. 
Furthermore, this workshop will also examine the state-of-art in blockchain research, and challenges to be solved in order to improve usability and adoption of the technology.

The workshop aims to provide a balanced outlook and is designed for wide audience of industrial and academic participants. There will be a broad range of talks to cater to both beginners and advanced blockchain users. Furthermore, the talks will range from applications and experiences using DLTs to theoretical, technical, and system-oriented topics.

## Venue Location ##

Talks will take place in Room TRS 1-099 on the 7th floor of 55 Dundas Street West.

Registration, breakfasts, lunches, breaks and receptions in TRSM Commons (Rooms TRS 1-148 & 1-150) also on the 7th floor of 55 Dundas Street West.
 
[Map of the 7th floor](https://www.ryerson.ca/content/dam/tedrogersschool/documents/TRSM_level1_7thfloor.pdf)

[Campus map](https://www.ryerson.ca/maps/)

## Program ##

8:00-8:30 Breakfast and registration

8:30-10:00 Tutorial 1

<details>
  <summary>Kaiwen Zhang (ÉTS Montreal): Blockchain Tutorial Part 1: Consensus, Bitcoin</summary>
    
<b>Abstract</b>: Popularly known for powering cryptocurrencies such as Bitcoin and Ethereum, blockchains is seen as a disruptive technology capable of impacting a wide variety of domains, ranging from finance to governance, by offering superior security, reliability, and transparency in a decentralized manner. In this tutorial presentation, we first study the original Bitcoin design, as well as Ethereum and Hyperledger, and reflect on their design from an academic perspective. We provide an overview of potential applications and associated research challenges, as well as a survey of ongoing research projects. We mention opportunities blockchain creates for event-based systems. Finally, we conclude with a walkthrough showing the process of developing a decentralized application (DApp), using a popular Smart Contract language (Solidity) for the blockchain platform of Ethereum.
<br />
<b>Speaker Bio</b>: Kaiwen Zhang is an Assistant Professor in the Department of Software and IT Engineering at ÉTS Montréal (University of Québec), head of the [FUSÉE Laboratory](https://fuseelab.github.io/). Previously, he was an Alexander von Humboldt postdoctoral fellow in Computer Science at the TU Munich (2015-2017) and a member of the Middleware Systems Research Group. Dr. Zhang obtained his B.Sc. and M.Sc. at McGill University in Montréal and his Ph.D. at the University of Toronto. His research interests include blockchain technologies, publish/subscribe systems, massively multiplayer online games, and software-defined networking. Dr. Zhang's expertise lies at the intersection of distributed systems, networking, and data management. His research is published in premier distributed systems conferences such as IEEE ICDCS and ACM Middleware.</details>
<details>
  <summary>Yahya Shahsavari (ÉTS Montreal): Performance Modeling and Analysis of the Bitcoin Inventory Protocol</summary>

<b>Abstract</b>: Blockchains are currently gaining attention as a newly emerging technology in both academia and industry, capable of impacting a variety of domains beyond cryptocurrencies. Performance modeling can be used to provide us with a deeper understanding of the behavior and dynamics within blockchain peer-to-peer networks. Blockchain system architects can leverage network models to properly tune their system and to reduce design costs significantly. In this paper, we focus on the original and well-established Bitcoin blockchain network. In particular, we propose a random graph model for performance modeling and analysis of the inventory-based protocol for block dissemination. This model addresses the impact of key blockchain parameters on the overall performance of Bitcoin. We derive some explicit and closed-form equations for block propagation delay and traffic overhead. We implement our model using the popular network simulator OMNet++. We validate the accuracy of our theoretical model and its implementation with our dataset mined from the Bitcoin network. Our results show the trade-off between the default number of connections per node, network bandwidth, and block size in order to compute the optimal block propagation delay over the network.
<br />
<b>Speaker Bio</b>: Yahya Shahsavari earned a BSc in Electronics Engineering from the University of Zanjan, and an MSc in Information and Communication Technology from Iran University of Science and Technology, Iran, in 2008 and 2016 respectively. Currently he is pursuing his PhD degree at the<br /> FUSÉE laboratory, a pioneer laboratory dedicated to blockchain systems at ÉTS.
</details><br />

Tutorial slides: [Part 1](files/bc-tutorial-mw-sacmat.pdf), [Part 2](files/blockchain-hands-on-Tutorial.pdf)

10:00-10:30 Tea break

10:30-12h00 Tutorial 2

<details>
  <summary>Kaiwen Zhang (ÉTS Montreal): Blockchain Tutorial Part 2: Smart contracts, Ethereum, Hyperledger</summary>
 
<b>Abstract</b>: Popularly known for powering cryptocurrencies such as Bitcoin and Ethereum, blockchains is seen as a disruptive technology capable of impacting a wide variety of domains, ranging from finance to governance, by offering superior security, reliability, and transparency in a decentralized manner. In this tutorial presentation, we first study the original Bitcoin design, as well as Ethereum and Hyperledger, and reflect on their design from an academic perspective. We provide an overview of potential applications and associated research challenges, as well as a survey of ongoing research projects. We mention opportunities blockchain creates for event-based systems. Finally, we conclude with a walkthrough showing the process of developing a decentralized application (DApp), using a popular Smart Contract language (Solidity) for the blockchain platform of Ethereum.
<br />
<b>Speaker Bio</b>: Kaiwen Zhang is an Assistant Professor in the Department of Software and IT Engineering at ÉTS Montréal (University of Québec), head of the [FUSÉE Laboratory](https://fuseelab.github.io/). Previously, he was an Alexander von Humboldt postdoctoral fellow in Computer Science at the TU Munich (2015-2017) and a member of the Middleware Systems Research Group. Dr. Zhang obtained his B.Sc. and M.Sc. at McGill University in Montréal and his Ph.D. at the University of Toronto. His research interests include blockchain technologies, publish/subscribe systems, massively multiplayer online games, and software-defined networking. Dr. Zhang's expertise lies at the intersection of distributed systems, networking, and data management. His research is published in premier distributed systems conferences such as IEEE ICDCS and ACM Middleware.</details><br />

12h00-13h00 Lunch break

13h-14h40 Session 1

<details>
  <summary>Edward Zhang (UofT): Optimizing Consensus Algorithms for Permissioned Blockchains</summary>

<b>Abstract</b>: Classical distributed consensus algorithms are widely used in backing permissioned blockchains. Our objective is to optimize these algorithms with respect to runtime and message complexity. We provide a brief review of consensus algorithms and give an overview of our current work on analyzing and optimizing consensus algorithms.
<br />
<b>Speaker Bio</b>: I'm currently a PhD student under the supervision of Hans-Arno Jacobsen. My research interests focus on the development of efficient consensus algorithms for blockchain, distributed and parallel systems. I am also broadly interested in machine learning, reinforcement learning and deep learning with an emphasis on optimizing system events.

Previously, I received my BS degree from Hunan University in 2005, and my MS degree from the University of Chinese Academy of Sciences in 2008, studying under Ken-li Li and Cheng-Zhong Xu respectively.
</details>
<details>
  <summary>Claudio Miceli (Federal University of Rio de Janeiro): A smart contract for patient records in odontology school</summary>

<b>Abstract</b>: In this presentation we intend to discuss the smart contract developed to attend the UFRJ's School of Dentistry. This smart contract was used to register and validate the patient activities on the clinic. Also the smart contract is used to register the students activities regarding those patients. Later the smart contract adds another layer regarding a professor validation over the patient analysis done by the students. In this way all patients and student activities can be monitored and evaluated. If needed this is also a way to provide legal evidence.
<br />
<b>Speaker Bio</b>: Claudio Miceli de Farias received a M.Sc. degree on Computer Science in 2010 and his doctorate degree in 2014 from the Federal University of Rio de Janeiro, Brazil. He is nowadays professor at the Tercio Pacitti Institute for Applications and Computational Research. His research interests include nanonets, wireless sensor networks, network security, Internet of Things, blockchains and Machine Learning.
</details>
<details>
  <summary>James Webster (Penn State), Michael Steward (Penn State):  Granting and revoking permissions using a distributed ledger, at a global scale</summary>

<b>Abstract</b>: Our project seeks to design a globally scalable system to grant permissions, and to enable prompt global revocation of those permissions. We use a blockchain to coordinate consensus on a canonical representation of the permission, and Bloom filters to broadcast early revocations. Previous systems do not envision a global, compact, timely broadcast of the kind of information necessary to enable fine-grained trust relationships to be built up between strangers. Recent work on blockchains has shown the way to use distributed control to achieve global consensus on a canonical, tamper-resistant database. We use a blockchain in our system as a flexible and global root of trust, as a way for oracles to make broadly applicable and verifiable statements that can be used to anchor other parts of our system, to limit the damage caused by stolen private keys, and for an anti-spam function. We use Merkel trees to achieve compact proofs that a permission is registered in the blockchain at a particular point in time. We use Bloom filters to broadcast compact proofs that a particular permission has not been revoked at a given point in time. For our blockchain framework we have chosen Hyperledger Fabric and implemented a network of peers residing on different computers and communicating using a peer-to-peer protocol. We discuss strategies for mending broken permission chains, and strategies for expressing permissions in a language that is flexible and actionable. Our system enables strangers meeting anywhere in the world to present a document which proves through a chain of facts that they have some particular permission. These facts can be verified by seeing that they have been digitally signed a relevant authority, whose authority can be established using the same system back to some suitable root of trust, and they have not expired or been revoked. On this basis, the strangers can make a decision about whether or not some action should be permitted with a higher level of confidence that would otherwise be possible.
<br />
<b>Speaker Bio</b>: James Webster works as a Research Engineer for the Applied Research Laboratory at Penn State, developing new applications for recent innovations in software technology. He has experience with process optimization, software development, system integration and automation. James has experience applying distributed computer systems, including blockchain systems like Hyperledger to solve logistics challenges. James obtained his B.S. in Industrial Engineering from Cal Poly San Luis Obispo in 2006.
<br />
Michael Steward is currently a M.S student in Computer Science and Engineering department at Penn State University, advised by Dr. Trent Jaeger. Michael also received his Bachelor’s degree in Computer Engineering with a minor in Engineering Leadership Development from Penn State University. Michael has been a student researcher at Penn State’s Applied Research lab for four years and has on worked various enterprise and expeditionary system. His research interests broadly lie in distributed ledger technology, access control, and other system security topics.</details>
<details>
  <summary>Paul Chafe (Zero31Skytech): Currency as a Technology</summary>

<b>Abstract</b>: Money is a concept.  Currency is a technology implementing that concept.  This presentation will model currency as a technological system designed to increase transaction efficiency, with performance that results from the interaction of its physical and contextual properties.  The tradeoffs made between these dictate both the efficiency of the currency and its relative strengths and weaknesses.  Cryptocurrencies using Proof of Work and Proof of Stake are a specific case of commodity currency.  Their characteristics generate tradeoffs between scalability, security, and decentralization, which make it difficult to realize their potential.   In particular, economies of scale drive centralization, which undercuts their ability to provide the distributed trust required to function.
<br />
<b>Speaker Bio</b>: Paul is the Chief Technology Officer at Zero31Skytech, a leader in open, distributed computing.  He has 34 years of experience in technology development, working at every level from chip design to high level system integration. 
</details><br />
    
14h40-15h10 Coffee break

15h10-17h15 Session 2

<details>
  <summary>Andreas Schaad (University of Applied Sciences Offenburg): Using a secure element as a blockchain oracle</summary>

<b>Abstract</b>: Blockchain frameworks enable the immutable storage of data. A still open practical question is the so called “oracle” problem, i.e. the way real world data is actually transferred into and out of a Blockchain while preserving its integrity. We present a case study that demonstrates how to use an existing industrial strength secure element for cryptographic software protection (Wibu-Systems CmDongle) to function as such a hardware-based oracle for the Hyperledger Blockchain framework. We also present a real world business case that motivated this work (https://www.wibu.com/de/blog/article/cmdongle-in-a-hyperledger-blockchain.html).
<br />
<b>Speaker Bio</b>: Andreas Schaad is a Professor of IT Security at the University of Applied Sciences Offenburg. Before that he worked at Wibu-Systems AG Corporate Technology, as well as in various technical and managerial IT Security roles for Ernst & Young, SAP Research Security & Trust and HUAWEI Security Research. He holds 13 international patents and authored over 50 peer-reviewed publications in the domain of IT Security.
</details>
<details>
  <summary>Victor Ermolaev (Bitfury), Albert Dercksen (Nedap):  Quis custodiet ipsos custodes?</summary>
  
<b>Abstract</b>: The notion of physical security in business has evolved from asset protection to assurance of critical business processes. Globalization and digital transformation are increasing the pace of business and life in general which leads to new and more dynamic risks on business continuity. Mitigation strategies require more fluid access control policies which are better able to capture the dynamics of an organization. Policy changes reflect cross cutting concerns from multiple stakeholders and can easily result in inconsistencies which may result in serious security risks. To ensure transparency and accountability of the access control policy updates during their life cycle, we introduce a blockchain-based approach. We discuss the relevance of our proposed solution on the basis of a typical security investigation scenario in which access control policy reconstruction is required to discover the root cause of an incident. We will argue that current best practices built on good intentions and best effort of operators and security administrators are not capable of delivering the required levels of immutability and trustworthiness of the audit logs. If the stakes are high, next level solutions are needed. Our solution addresses accountability, removes single points of failure, provides a verification framework and ultimately results in better business continuity at lower costs.
<br />
<b>Speaker Bio</b>: Albert Dercksen completed MSc in Applied Mathematics and later worked in the maritime technology sector. His main interests were in the field of numerical fluid dynamics applied to floating offshore constructions. In 2000, he joined Nedap Security Management as head of product development. Based on extensive experience with physical access management in large, multinational organizations, he now leads a multidisciplinary innovation team to explore and develop new conceptual models for physical access management.
 <br />
Victor Ermolaev obtained a PhD degree in Mathematics and Physics from University of Groningen. In 2011 he joined Nedap Security Management in capacity of a researcher in the field of access control, his joint theoretical paper was presented at SACMAT 2014. Since 2018 he occupies an analytical position at Bitfury Exonum focusing on applied blockchain research.
</details>
<details>
  <summary>Wes Fulford (Bitfarms): Overview of the mining industry in North America</summary>
  
<b>Abstract</b>: Bitfarms has led a campaign in Quebec, Canada to engage with government, decision makers and the general public regarding blockchain technology education and how it can foster innovation and economic development within the province. Bitfarms realized early on that the emerging blockchain and cryptocurrency sector requires social acceptability in order for the Company to compete globally and to garner access to clean hydroelectricity at a competitive price.
<br />
<b>Speaker Bio</b>: Wes Fulford is the Chief Executive Officer of Bitfarms, one of North America’s largest vertically-integrated blockchain infrastructure and cryptocurrency mining companies. Wes brings 15 years of investment banking, capital markets and asset management experience to Bitfarms. Wes manages corporate direction and strategy at Bitfarms, facilitating company activities in capital markets, sales, marketing, strategic alliances and business development. Prior to joining Bitfarms, Wes led the financial institutions and fintech investment banking practice for one of Canada’s largest financial institutions, Desjardins Group. 
</details>
<details>
  <summary>Will Zhang (Finetics): Blockchain On Cloud for Industrial Usecase</summary>
  
<b>Abstract</b>: With the rise of blockchain and cloud computing technology, more and more companies begin to adopt and combine both technology fields in the industry. Blockchain creates a transparent, decentralized, immutable distributed system while cloud computing makes operationalize such system much easier. Today we will look at how solutions that combine the best practice for cloud computing and blockchain can provide best value for separate use cases such as real estate, finance, and supply chain management.
<br />
<b>Speaker Bio</b>: Will is the founder and solutions architect at Fintelics, an emerging technology consulting company specializing in AI, Blockchain, Cloud, Data Engineering, and Fullstack Omnichannel Software Development. Graduated from the University of Toronto in engineering science, he is the winner of 2019 Canada Developer 30 Under 30, and is currently a Professional AWS Certified Solutions Architect. Will is passionate about consulting and solutioning for all types of businesses. Since he founded Fintelics, he has consulted for enterprises such as the Toronto Stock Exchange, Citco, Thomson Reuters, Liangzi Education Inc. as well as creating Blockchain and Cloud architecture for startups such as Nobul, Graindiscovery, Eye Network, Alfasommet and Just Wallet.
</details><br />

17h30 - Reception

## Registration ##
SACMAT conference attendees are welcome to attend the workshop day. For others, the option to register for one day is available on the SACMAT [registration page](http://www.sacmat.org/2019/registration.php).

## Structure
We are soliciting participants to present their work at the workshop. We are looking for (but are not limited to) the following types of talks:
1. Presentations of **previously published** conference or journal articles at other venues
2. Presentations on **ongoing**, unpublished, research (can optionally be part of the SACMAT proceedings)
3. Presentations on the design, implementation, and evaluation of **novel use cases** for blockchains
4. Presentations on **adoption roadmap**, technical and non-technical barriers, especially in **industry**
5. Presentations of **vision/blue-sky** topics or **position papers**
6. Presentations on **related aspects** to blockchains (e.g. cryptocurrency mining, exchanges, etc.)

## Topics (not limited to this list)
1. Integration of access control technologies with DLTs
2. Cryptography mechanisms for blockchains
3. Application domains for blockchains (e.g., eHealth, IoT, supply chains, real estate, etc.)
4. Scalability and performance of blockchain systems
5. Security, privacy, and trust in blockchains
6. Consensus mechanisms (e.g., Proof-of-work, Proof-of-stake, PBFT, Merkle DAG, etc.)
7. On-going research in popular blockchain systems (e.g. Ethereum, Hyperledger, etc.)
8. Layer 2 and off-chain solutions (e.g., State channels, Plasma)
9. Smart contract languages, modeling, and verification
10. Theory, cryptoeconomy, and attacks of blockchain systems

## Workshop Chair
[Kaiwen Zhang](https://fuseelab.github.io/), [École de technologie supérieure](https://www.etsmtl.ca/Bottin/ETS/MotCle/FicheEmploye?Numero=6866), Montréal (Canada)

## Submission Information
Please submit an abstract and speaker biography to the workshop chair: [kaiwen.zhang@etsmtl.ca](mailto:kaiwen.zhang@etsmtl.ca).<br/>
The submission deadline is: ~~**March 31st, 2019**~~.

## Sponsorship

We thank [Bitfarms](https://www.bitfarms.io/) for sponsoring our event.

![Bitfarms](images/bf-logo.jpg) 
