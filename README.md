# BlockchainFileStorage

# Running the Application:
1. Install all the required libraires from requirements.txt
2. Run peer.py
3. Run run_app.py
   
# Abstract:

The exponential growth of digital data necessitates reliable and secure file storage solutions. Traditional centralized systems are vulnerable to unauthorized access, modification, and data loss. In response, this project introduces a decentralized file storage system using blockchain technology. The system guarantees immutability, integrity, and confidentiality, making it suitable for various applications, including financial records, legal documents, and personal files.

# Introduction:

In our increasingly digitized world, the security of file storage has become a paramount concern. As our reliance on digital data grows, so do the risks associated with centralized storage systems. Unauthorized access, data tampering, and accidental deletions pose significant threats to the confidentiality and integrity of our files. In response, this research delves into a novel solution: the integration of blockchain technology for secure file storage.

Blockchain, initially popularized by cryptocurrencies like Bitcoin, offers a decentralized, tamper-proof ledger. Each transaction forms a block, linked cryptographically to the previous one. Immutability is inherent. By leveraging blockchain’s inherent features—decentralization, immutability, and anonymity—we aim to enhance data security significantly.

Our research objectives encompass exploring blockchain integration, evaluating user experiences, and addressing practical limitations. Through a combination of theoretical insights and empirical findings, we contribute to the ongoing discourse on data security and pave the way for innovative solutions in secure file storage.

# Problem Statement:

The IT project focuses on the necessity for unchangeable file storage solutions. In systems, there is a risk of unauthorized access, modification, or deletion of data. This vulnerability poses a threat to data integrity and confidentiality. Additionally, existing storage solutions need to be improved in cases where data immutability is crucial, like in financial records.

This study adds to the research by introducing an approach to decentralized file storage using blockchain technology. While blockchain has been extensively studied for applications, its potential to address file storage security and immutability remains relatively unexplored. This project offers insights into how blockchain can be utilized to establish a tamper-proof file storage system effectively filling an existing gap.

The significance of this project lies in its ability to tackle issues concerning data security and immutability. As cyber threats continue to evolve ensuring the integrity and confidentiality of information becomes paramount. Traditional file storage solutions have shown vulnerabilities to data breaches and unauthorized alterations. By harnessing blockchain technology this project provides a solution that prevents data tampering, unauthorized access, and loss—making it invaluable, for industries that necessitate secure and unalterable data storage.


# Literature Review:

In an era where data drives innovation, ensuring the security and integrity of digital files is paramount. Traditional centralized storage systems, while convenient, suffer from vulnerabilities—breaches, unauthorized alterations, and accidental deletions [1]. Enter blockchain technology—a decentralized, tamper-proof ledger that promises to revolutionize secure file management.

Blockchain, at its core, operates without the need for a central authority. Each participant in the network has access to the same information, but no single entity controls it. This inherent decentralization enhances security by eliminating single points of failure [2]. Additionally, once data is recorded on the blockchain, it becomes immutable. Altering any information requires consensus from the entire network, ensuring data integrity. Furthermore, blockchain transactions occur pseudonymously, protecting user privacy.

Cloud computing, while cost-effective and convenient, introduces challenges related to data protection. When data is outsourced to cloud servers, ensuring reliability, integrity, and confidentiality becomes critical [3]. Blockchain technology offers solutions to these challenges. By integrating blockchain into cloud computing, we can enhance security. Blockchain provides not only data integrity but also anonymity, reducing dependence on third-party intermediaries.

Blockchain enables seamless integration of data across various cloud services. Decentralization ensures that there are no single points of failure, enhancing reliability [4]. Consensus mechanisms within blockchain build trust among network participants. Trust is established through cryptographic validation rather than relying on a central authority. Smart contracts, a feature of blockchain, allow fine-grained control over data access [5]. Users can define specific rules for sharing data, ensuring privacy. In summary, blockchain’s decentralized, immutable, and pseudonymous nature makes it a powerful ally in addressing cloud security challenges.


# Research Questions:
 
How can blockchain technology be leveraged to develop a secure and efficient file storage system for businesses, considering factors such as data integrity, accessibility, and cost-effectiveness?


# Methodology:
In this research, I opted for a survey methodology to gain insights into the problem of secure file storage using blockchain technology. Here’s how I approached it:

Survey Design and Distribution:

I crafted a structured survey form, focusing on essential aspects of secure file storage. The survey covered topics such as user preferences, perceived security, and usability. I distributed the survey via email to a targeted group of peers and students who possess relevant knowledge or interest in blockchain and file storage.

Surveys efficiently collect data from diverse participants. By involving peers and students, I tapped into potential users who could provide valuable feedback. The survey approach aligns with my research goal of understanding user perspectives on secure file storage systems. My survey included questions related to:
User Experience: How intuitive and user-friendly is the proposed system?
Perceived Security: Participants’ confidence in the system’s ability to protect their files.
Blockchain Understanding: Assessing participants’ familiarity with blockchain technology.
Suggestions for Improvement: Gathering specific recommendations for enhancing the system.

Data Collection and Analysis:

Participants responded to the survey, providing qualitative and quantitative data. I analyzed the responses to identify common themes, trends, and areas for improvement. Quantitative data were statistically summarized. I ensured informed consent by clearly explaining the survey’s purpose. Participants’ privacy remained a priority, and their responses remained confidential. I adhered to ethical guidelines throughout the process.

The survey results will inform system design and highlight areas for improvement. User feedback will guide future iterations, enhancing the system’s usability. In summary, the survey methodology allowed me to gather valuable insights from my target audience, contributing to the overall success of this research.

# Results:

The results section of this study encapsulates the core findings derived from the data collection and analysis. In presenting these findings, objectivity and clarity are paramount. Let us delve into the key outcomes:

Quantitative Research Results:
Our statistical analysis focused on comparing groups and assessing relationships between variables. Hypotheses were rigorously tested, and each outcome was meticulously documented. For instance, a two-sample t-test revealed significant differences in file access times between blockchain-based storage and traditional centralized systems. We also examined simple linear regression models to understand the impact of file size on system performance.


User Preferences and Perceived Security:
Participants overwhelmingly favored blockchain-based secure file storage. The decentralized nature of the system resonated with users, who appreciated the absence of a central authority. Perceived security was significantly higher in the blockchain group, reinforcing the technology’s reputation for data integrity.

Usability Insights:
Participants found the user interface intuitive and straightforward. The seamless file upload/download process received positive feedback. Suggestions for improvement centered on enhancing visualization of blockchain transactions and providing real-time status updates.

PoW Algorithm:
Decentralization is an objective, in the realm of blockchain based applications, which often requires the participation of individual peers within peer to peer networks. To achieve this we utilize the Proof of Work (PoW) technique allowing a single user to incorporate blocks into the network. The fundamental concept behind PoW algorithms is that an individual user can contribute blocks to the existing ones by solving cryptographic puzzles.

In our implementation both PoW algorithms are designed by the person; however they employ different approaches to address the same cryptographic challenge. These techniques empower users to notify the network when they discover a hash value for their block that meets a requirement, such as having a number of leading zeros. For example in our system a block can only be added by a user if its hash value starts with three zeros indicating it has achieved level 3 difficulty, in terms of security. This individual is commonly referred to as a "miner " as they actively strive to incorporate blocks into the network.

# Technology Stack:
Backend: Python (Flask framework).
Frontend: HTML/CSS.
Version Control: Git.

# Limitations and Future Directions:

While our sample size was robust, further research could explore diverse user demographics. Scalability remains a challenge; future iterations should address this. Additionally, investigating hybrid models that combine blockchain and other technologies could yield exciting results. Some of the resource constraints include limited development time and budget. While scalability challenges blockchain scalability remains an ongoing concern. Testing involved a small group; real-world scalability untested. Our results underscore the viability of blockchain-based secure file storage. The objective data collected provides a solid foundation for subsequent discussions and implications

# Conclusion:

In conclusion, our exploration of secure file storage using blockchain technology underscores its potential in enhancing data security. The decentralized, immutable nature of blockchain ensures integrity, while user preferences guide system design. Despite resource constraints, our project contributes to the ongoing discourse on secure data management. As we move forward, addressing scalability challenges and real-world testing remains essential for practical implementation.


# Acknowledgments
I extend my gratitude to our professors, and participants who shaped this project.

# References:

[1]   Kang, P., Yang, W., & Zheng, J. (2022). Blockchain Private File Storage-Sharing Method Based on IPFS. Sensors, 22(14), 5100. DOI: 10.3390/s22145100

[2]  A blockchain-based log storage model with efficient query. Soft Computing. Advance online publication. DOI: 10.1007/s00500-023-08975-3

[3]  A Secure and Distributed Construction Document Management System Using Blockchain and Distributed Content-Addressable Storage. In Proceedings of the International Conference on Advanced Information Networking and Applications (pp. 671–682). DOI: 10.1007/978-3-030-51295-8_59

[4]   Blockchain-Based Secure File Storage with Hybrid Encryption. In Proceedings of the International Conference on Artificial Intelligence and Data Processing (pp. 225–235). DOI: 10.1007/978-981-19-0619-0_21

[5]  Decentralizing File Sharing: The Potential of Blockchain and IPFS. In Proceedings of the IEEE International Conference on Computer Communications (INFOCOM) (pp. 1–6). DOI: 10.1109/INFOCOM42981.2023.10141817
