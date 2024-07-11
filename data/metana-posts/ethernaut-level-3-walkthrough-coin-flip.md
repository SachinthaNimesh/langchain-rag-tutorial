



Ethernaut Level 3 Walkthrough: Coin Flip - Metana






















































































 












Skip links* [Skip to primary navigation](#primary-nav)
* [Skip to content](#lqd-site-content)



 





 


 




Call us +1 415 416 0800 


















 [![Metana](https://metana.io/wp-content/uploads/2022/07/Metana-Logo.png)](https://metana.io/) 








* [Solidity BootcampHot 🔥](https://metana.io/web3-solidity-bootcamp-ethereum-blockchain/)
* [Bootcamps](#) 








###### Web3

 






### Web3 Solidity Bootcamp



Most Popular 🔥
The most advanced Solidity curriculum on the internet











### Full Stack Web3 Beginner Bootcamp



New ✨ | Beginner 👨‍💻
Starting off with web development and seamlessly integrating web3 development











### Web3 Rust Bootcamp



Become an expert Solana blockchain developer with one course!














###### Coding + Career Growth

 




 








### Software Engineering Bootcamp



Become a Software Engineer - Balance everyday life commitments & launch your coding career in as little as 16 weeks











### Metana's JobCamp™️



Learn to make a lasting first impressions, network effectively & search for jobs with confidence.















 ![](https://metana.io/wp-content/uploads/2023/10/Screenshot-2023-10-25-at-7.51.33 PM-300x61.png) 




 Rated
the Best

 





 Ranked as the industry's premier Web3 bootcamp with a stellar 4.8/5 star rating on Course Report.

 




[Read more reviews here](/reviews/)












[Still Unsure?](https://formless.ai/c/6bPi6ASGJ4ge)
* [Resources](#)
	+ [Reviews](https://metana.io/reviews/)
	+ [Metana’s Job Guarantee](https://metana.io/job-guarantee/)
	+ [Tuition](https://metana.io/tuition/)
	+ [Events](https://metana.io/events/)
* [Blog](https://metana.io/blog/)

 





[Apply now](https://metana.typeform.com/general)






















 







 [![Metana](https://metana.io/wp-content/uploads/2022/07/Metana-Logo.png)](https://metana.io/) 









Metana Bootcamps
----------------

 






* [Solidity BootcampHot 🔥](https://metana.io/web3-solidity-bootcamp-ethereum-blockchain/)
* [Full Stack Web3 Bootcamp](https://metana.io/web3-beginner-bootcamp/)
* [Rust Bootcamp](https://metana.io/web3-rust-bootcamp-solana-blockchain/)
* [Cybersecurity Bootcamp](https://metana.io/cybersecurity-bootcamp/)
* [AI & Machine Learning Bootcamp](https://metana.io/ai-machine-learning-bootcamp/)
* [Data Analytics Bootcamp](https://metana.io/data-analytics-bootcamp/)
* [Data Science Bootcamp](https://metana.io/data-science-bootcamp/)
* [Full Stack Bootcamp](https://metana.io/full-stack-software-engineer-bootcamp/)
* [Jobcamp](https://metana.io/jobcamp/)

 














Menu Items
----------

 






* [Blog](https://metana.io/blog/)
* [Metana’s Job Guarantee](https://metana.io/job-guarantee/)
* [Refer a Friend](https://metana.io/refer/)
* [Tuition](https://metana.io/tuition/)
* [Withdrawal and Refund Policy](https://metana.io/withdrawal-and-refund-policy/)

 









 








 [[email protected]](/cdn-cgi/l/email-protection)

 




 

[Facebook](https://www.facebook.com/metanahq) 


[Twitter](https://twitter.com/metanahq) 


[Linkedin](https://www.linkedin.com/school/metana/) 


























 [![Metana](https://metana.io/wp-content/uploads/2022/07/Metana-Logo.png)](https://metana.io/) 




[Apply now](https://metana.typeform.com/general)
























 
#### Table of Contents





 







Ethernaut Level 3 Walkthrough: Coin Flip
========================================

 



 * [Sven Daneel](https://metana.io/blog/author/sven-daneel/)
* [April 2, 2024](https://metana.io/blog/2024/04/02/)
* [Ethernaut Walkthrough](https://metana.io/blog/category/ethernaut-walkthrough/)














The **Ethernaut Level 3**, called “Coin Flip,” is a lesson on the weak spots in how smart contracts handle chance and prediction. This article walks you through the Coin Flip game, showing where the contract has a weak spot that makes its outcomes not so random. 


The article will show you step by step how to use this weak spot to your advantage, which teaches us about how the Ethereum blockchain works. It also talks about why being random and unpredictable is important for smart contracts, giving tips on how to make them safer and more reliable in the decentralized world of apps.


![ethernaut level 3ethernaut challenge 3coin flip challengewalkthroughrandomness](https://metana.io/wp-content/uploads/2024/04/image.png)
The Coin Flip Challenge
-----------------------


In the realm of Ethereum and [blockchain technology](https://metana.io/blog/how-does-the-blockchain-work-blockchain-technology-explained-in-simple-words/), understanding the intricacies of smart contract security is paramount. Today, I want to take you through my journey with the “Coin Flip” challenge, a fascinating puzzle that sheds light on the subtleties of randomness within smart contracts and its potential vulnerabilities.


The Essence of the Challenge
----------------------------


**The Coin Flip challenge** is an interesting task designed to expose the deterministic nature of Ethereum’s randomness and how it can be exploited. The core objective is to predict the outcome of a coin flip in a smart contract consistently. At first glance, this seems like a game of luck. However, the deterministic environment of Ethereum means “**randomness**” can be foreseen if one knows where to look.


Understanding the Contract
--------------------------


**The first step** in tackling this challenge involves a deep dive into the smart contract’s mechanics. Specifically, it’s crucial to understand how the contract generates its “random” outcome. Typically, contracts might use variables such as block number and difficulty to produce randomness. However, this method introduces predictability, a key vulnerability we aim to exploit.


Predicting the Outcome
----------------------


Armed with knowledge of the contract’s randomness generation technique, the next phase is to craft a function that mirrors this logic to predict the outcome accurately. This step requires a blend of technical prowess in Solidity and an understanding of Ethereum’s block mechanics.


Interacting with the Contract
-----------------------------


Once we have a prediction mechanism in place, the final step is to interact with the contract’s `flip` function, using our predicted outcome. Successfully predicting the coin flip outcome consistently not only completes the challenge but also unveils a critical lesson in smart contract design.


The Illusion of Pseudo-Randomness
---------------------------------


This challenge serves as a stark reminder that what appears to be random in a [smart contract](https://metana.io/blog/best-practices-for-smart-contract-testing-how-to/) might not truly be random, especially when it relies on blockchain data. This pseudo-randomness can lead to predictable outcomes, which could be exploited by malicious actors.


Security Implications
---------------------


The Coin Flip challenge underscores the importance of robust randomness sources in [smart contract](https://metana.io/blog/solidity-smart-contracts/) design. It highlights the need for developers to understand the potential vulnerabilities associated with pseudo-randomness to prevent exploits.


Forward-Looking Thoughts
------------------------


Navigating through the Ethernaut challenges, including the Coin Flip, has been an enlightening experience. Each challenge has offered unique insights into smart contract security and the nuances of Solidity programming. As I continue on this blockchain adventure, I look forward to sharing more reflections and learnings. Stay tuned for more deep dives into the fascinating world of Ethereum smart contracts.


The journey through the Coin Flip challenge is more than just a technical exercise; it’s a vital lesson in the importance of understanding the underlying mechanics of smart contracts to ensure their security and reliability.


Ready for the next Ethernaut challenge? Click to check out the [previous ethernaut challenge](https://metana.io/blog/ethernaut-level-2-walkthrough-fallout) and see what’s [next](https://metana.io/blog/ethernaut-level-4-walkthrough-telephone) in our series!



![faq](https://metana.io/wp-content/uploads/2024/01/Questions-cuate-1024x1024.png)
FAQs
----


**What is Ethernaut Level 3: Coin Flip?**


* Ethernaut Level 3: Coin Flip is a blockchain-based challenge that tests players’ understanding of Ethereum smart contracts and their vulnerabilities.\*


**How do you solve the Coin Flip challenge in Ethernaut Level 3?**


* Solving the Coin Flip challenge involves predicting the outcome of a pseudo-random function within the contract and exploiting its vulnerability.\*


**What skills are needed to complete Ethernaut Level 3?**


* To complete Level 3, you need a basic understanding of Ethereum, Solidity, and smart contract vulnerabilities.\*


**Why is understanding smart contract vulnerabilities important in Ethernaut?**


* Understanding these vulnerabilities helps players identify and fix similar issues in real-world blockchain applications, enhancing security.\*


**How does the Coin Flip challenge illustrate blockchain concepts?**


* It demonstrates the importance of true randomness and the potential risks of predictable outcomes in smart contracts.\*


**What is Ethereum?**


* Ethereum is a decentralized, blockchain-based platform that enables the creation of smart contracts and decentralized applications (dApps).\*


**What is a smart contract?**


* A smart contract is a self-executing contract with the terms of the agreement directly written into lines of code.\*


**What is Solidity?**


* Solidity is a programming language designed for developing smart contracts on the Ethereum blockchain.\*


**How can I learn more about blockchain security?**


* You can learn more by exploring online courses, tutorials, and participating in challenges like Ethernaut to gain practical experience.\*


**What are crypto games?**


* Crypto games are digital games that utilize blockchain technology, allowing for verifiable ownership of in-game assets and often incorporating cryptocurrency.






![](https://metana.io/wp-content/uploads/2024/04/Ethernaut-Level-3-Walkthrough-Coin-Flip.jpg) 





[PrevPreviousWhat is Event Handling in Web3.js? [Explained]](https://metana.io/blog/what-is-event-handling-in-web3-js-explained/) 




[NextNFT Marketplace Development with Solidity: Essential GuideNext](https://metana.io/blog/nft-marketplace-development-with-solidity-essential-guide/) 







#### Metana Guarantees  a Job 💼

 





#### Plus Risk Free 2-Week Refund Policy ✨

 




 You’re guaranteed a new job in web3—or you’ll get a full tuition refund. We also offer a hassle-free two-week refund policy. If you’re not satisfied with your purchase for any reason, you can request a refund, no questions asked.

 






Web3 Solidity Bootcamp
======================

 





 The most advanced Solidity curriculum on the internet!

 




* 4 Months
* Prior coding experience required
* 20h/ Week
* 1-on-1 mentorship
* Expert code reviews
* Coaching & career services






[View Program](/web3-solidity-bootcamp-ethereum-blockchain/)







Full Stack Web3 Beginner Bootcamp
=================================

 





 Learn foundational principles while gaining hands-on experience with Ethereum, DeFi, and Solidity.

 




* 7 Months
* Beginner - Zero to Hero
* 25h/ Week
* Your very own personal support tutor
* 1-on-1 mentorship
* Expert code reviews
* Coaching & career services






[View Program](/web3-beginner-bootcamp/)













You may also like
-----------------

 






![](https://metana.io/wp-content/uploads/2024/07/Protect-Yourself-from-Rug-Pulls-Tips-to-Avoid-Crypto-Scams-640x364.jpg)







### [Metana Editorial](https://metana.io/blog/author/editorial/)




12 mins ago

#### [Protect Yourself from Rug Pulls: Tips to Avoid Crypto Scams](https://metana.io/blog/protect-yourself-from-rug-pulls-tips-to-avoid-crypto-scams/)




The world of Web3 is brimming with promises of high returns and revolutionary projects, driving 


![](https://metana.io/wp-content/uploads/2024/07/ERC-Token-Standards-Your-Simplified-Guide-copy-640x364.jpg)







### [Metana Editorial](https://metana.io/blog/author/editorial/)




1 day ago

#### [Address Poisoning in Smart Contracts](https://metana.io/blog/address-poisoning-in-smart-contracts/)




Web3 thrives on user empowerment and the ease of sending and receiving cryptocurrency. However, a 
 







#### Metana Guarantees  a Job 💼

 





#### Plus Risk Free 2-Week Refund Policy

 




You’re guaranteed a new job in web3—or you’ll get a full tuition refund. We also offer a hassle-free two-week refund policy. If you’re not satisfied with your purchase for any reason, you can request a refund, no questions asked.

 






#### Web3 Solidity Bootcamp

 





 The most advanced Solidity curriculum on the internet

 




* 4 Months
* Prior coding experience required
* 20h/ Week
* 1-on-1 mentorship
* Expert code reviews
* Coaching & career services






[View Program](/web3-solidity-bootcamp-ethereum-blockchain/)







Full Stack Web3 Beginner Bootcamp
=================================

 





 Learn foundational principles while gaining hands-on experience with Ethereum, DeFi, and Solidity.

 




* 7 Months
* Beginner - Zero to Hero
* 25h/ Week
* Your very own personal support tutor
* 1-on-1 mentorship
* Expert code reviews
* Coaching & career services







 Learn foundational principles while gaining hands-on experience with Ethereum, DeFi, and Solidity.

 




[View Program](/web3-beginner-bootcamp/)







Events by Metana
================

 





 Dive into the exciting world of Web3 with us as we explore cutting-edge technical topics, provide valuable insights into the job market landscape, and offer guidance on securing lucrative positions in Web3. 

 




 





 







Do you have anything you want us to cover in our blog posts? What should we talk about next? We need your suggestions! 
 





Submit
















Start Your  Application
-----------------------

 






Secure your spot now. Spots are limited, and we accept qualified applicants on a first come, first served basis..




 






Email(Required)

Career Track(Required)


Web3



Data



Full Stack



Cyber

  








Δ










The application is free and takes just 3 minutes to complete.

 















##### What is included in the course?

 






### Expert-curated curriculum










### Weekly 1:1 video calls with your mentor










### Weekly group mentoring calls










### On-demand mentor support










### Portfolio reviews by Design hiring managers










### Resume & LinkedIn profile reviews










### Active online student community










### 1:1 and group career coaching calls










### Access to our employer network










### Job Guarantee




















 






###### Address

 





 44 Montgomery St,   

San Francisco, CA 94104, United States

 












Email 







Subscribe












###### Contact us

 





###### Call us directly

 





 (415) 416-0800

 





###### Mail us directly

 





 [[email protected]](/cdn-cgi/l/email-protection)

 









### Company

 




* [Home](/)
* [Blog](https://metana.io/blog/)
* [Jobs at Metana](/jobs/)
* [Bootcamp Application](https://metana.io/apply/)
* [Refer a friend](/refer/)
* [Student Perks](/perks/)
* [Testimonials](/reviews)
* [LMS login](https://app.metana.io/)
* [Open LMS login (Full Stack)](https://open.metana.io/)









### Bootcamp

 




* [Web3 Bootcamps](https://metana.io/web3-0-bootcamp/)
* [- Solidity Bootcamp](https://metana.io/web3-solidity-bootcamp-ethereum-blockchain/)
* [- Web3 Beginner Bootcamp](https://metana.io/web3-solidity-bootcamp-ethereum-blockchain/)
* [- Rust Bootcamp](https://metana.io/web3-rust-bootcamp-solana-blockchain/)
* [- ZK Bootcamp](/web3-zero-knowledge-bootcamp/)
* [Data + AI bootcamps](#)
* [- Data Analytics Bootcamp](/data-analytics-bootcamp/)
* [- Data Science Bootcamp](/data-science-bootcamp/)
* [- AI/ML Bootcamp](/ai-machine-learning-bootcamp/)
* [Software Engineering Bootcamp](/full-stack-software-engineer-bootcamp/)
* [Cybersecurity Bootcamp](/cybersecurity-bootcamp/)
* [Jobcamp](/jobcamp/)
* [Tuition](https://metana.io/tuition/)









### For businesses

 




* [Business](https://metana.io/business/)
* [- Hiring Partner](https://metana.io/business/hiring-partner/)
* [- Upskill Your Team](/business/upskill-your-team/)









### Legal

 




* [Licences](https://metana.io/licences/)
* [Metana's Job Guarantee](https://metana.io/job-guarantee/)
* [Withdrawal and Refund Policy](https://metana.io/withdrawal-and-refund-policy/)
* [Privacy Policy](/privacy-policy/)













[Still Unsure?](https://formless.ai/c/6bPi6ASGJ4ge)








[![](https://metana.io/wp-content/uploads/2022/07/Metana-Logo-Black-Full.png)](https://metana.io) 







 Disclaimer:
‍
Metana is involved in the Blockchain Education activities only. We are not dealing with any Crypto related stuff nor provide advice in the Crypto related field.

 

















 Metana is a pioneer in education and career transformation, specializing in today’s most in-demand skills. The leading source for training, staffing, and career transitions, we foster a flourishing community of professionals pursuing careers they love.
| © 2023 Edmore (private) limited

 








[Facebook](https://www.facebook.com/metanahq) 





[Linkedin](https://www.linkedin.com/school/metana/) 












































































Adding {{itemName}} to cart


Added {{itemName}} to cart













Loading...



×






