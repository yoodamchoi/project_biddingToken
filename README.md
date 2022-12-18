# Project voting system using Blockchain

## Requirements
Looking at the electronic voting process, it can be divided into the voter registration step of creating a list of voters, the step of checking the candidate's agenda, the step of voting, and the counting step. A system is built using blockchain technology so that a series of processes are safely and fairly voted. The built system must meet the requirements. The requirements related to the safety of electronic voting are as follows.
> 1. Integrity : 
> Voting is completely conducted from start to finish. It must be accurate and accurately counted.
> 2. Personalization : 
> Confidentiality must be maintained so that no one can know who the voter is and what he or she voted for. 
> 3. Impossiblility of double voting : 
> A voter must be able to vote only once. 
> 4. Right to vote : 
> Only voters who are eligible to vote cannot vote, and must be able to certify their identity. Only one person, one vote is allowed, and no double vote is allowed.
> 5. Fairness : 
> By making it possible to know the count of votes during the process, It should not have any influence on the vote cast.
> 6. Verifiability : 
> Voters can check their votes and know if their votes were correctly counted. Anyone can check the vote count, so no one can tamper with the voting results. 

### Problem Statement
An alliance of small organizations need to create an efficient and fair system that will allow all organizations to come to an agreement on which proposed projects that they will collectively fund. The organizations are independent with no one organization having control over another, thusly no one organization can have control over the consensus system, it must be impartial  so no organization has undue advantage over the system and it must be transparent and free of internal tampering.
### Goals
Provide open, fair voting mechanism for group consensus: This will be accomplished if the system is easily accessible and. Visible to all voting organizations, and the voting process only allows restricted votes for the selected projects and no organization will have undue voting privileges or unfair say in the voting process.
### Stakeholders
1. Election manager/administrator : Register candidates, period, voters, and participants. The election begins. Manage voting while elections are in progress. When the period expires, the election ends. • Count the votes. 
2. Voters : authenticate themselves and vote. Voters register their personal information and key. The election management side stores the data of eligible voters and pays them the gas necessary for voting. 
3. Miner : connect to the P2P network and record votes, that is, mine them. A boot node must be registered in the network to participate. 
### Restrictions / Rules

### Data

### Exceptions

### User / Technical Stories
|Story|Context|
|---|---|
|The organization has to apply(register) for voter.|Only authorized organization could allowed to use this system.|
|Once the organization is accepted as an authorized organization, it will going to receive one token for make vote or propose the project for the choice.|""""|
|The organization can propose the project.|Proposing project is not essential but if they want to propose their project they can propose one. And if they don’t want they don’t want to. And also there will be deadline for proposing the project.|
|The organization will vote after the deadline of the propose. They can vote until deadline that is set by admin.|After the deadline, the each organization that has the token will going to vote one choice that they like. |
|After the organization finished voting(after the deadline), the token is going to be burn.|They cannot cancel or edit their choice. Once they clicked one choice and confirm they cannot go to previous page.|
|Once the voting due date is over, the voting result will show up to voters.|The ones who can see the result is limited to the voters(organization) who did the vote.|
