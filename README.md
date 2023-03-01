# EVM-Study-Group
Learning about the EVM, in depth, from first principles.

## Intention
The intention of this group is to learn about the EVM in as much depth as possible. The base for the discussions will be the Yellow Paper. This study group's intention is not to cover all the knowledge needed for a security researcher. The EVM is the sole target of this group.

## Motivation
The motivation behind starting this study group is the ever changing nature of this field. New concepts are constantly being built on top of eachother. The knowledge base needed to become a skilled security researcher is vast and ranges from computer science fundamentals to finance/new DeFi primatives. In my experience, many individuals (myself included), want to build this knowledge base as fast as possible. Some do and find success early, while others find themselves struggling to catch up. 

The aim of this group is to take a "slow and steady" approach to build the required knowledge base to become a successful security researcher. It is worth noting that the EVM is just *one* component of your knowledge base, albiet an important one.

Ideally, everyone participating in this study group will receive value: those that learn new concepts receive knowledge, while those that teach said concepts gain a deeper understanding. Therefore, It will be encouraged that everyone participates and voices their perspectives. No one starting out in this field should be hesitant about stating their knowledge gaps. We are all trying to learn and we should all respect eachother's time while doing so.

## Consideration
We are all busy going through the motions of our own lives. Some of us have families, some of us are in school, some of us are working multiple jobs, etc... Our time is our most valuable commodity and we should treat it as such. Therefore, it is expected that everyone is respectful, considerate, and mindful of the time all other participants are setting aside to have these discussions. Similarly, we should all express the same sentiments towards ourselves and do so by asking questions, voicing concerns, providing critique, and offering explanations.

## Preparation
Each discussion will be accompanied by articles/videos/other study materials that all participants are expected to review before the discussion. This will ensure that everyone is well prepared to participate and maximize their learning with questions.

The study material will be familiar with all of you and you will be able to find most of it on the [Web3SecurityDAO Wiki Page](https://www.web3securitydao.xyz/collaborating/resources). Any suggestions for preparatory study materials is welcomed and encouraged.

## Discussions
The base of all discussions will be the Yellow Paper. One goal of this group will be to understand every chapter in the Yellow Paper that relates directly to the EVM (implementation, tx execution, gas, etc...). The chapters pertaining to the consensus mechanism of ethereum/block finality will not be discussed initially. 

Below is a rough "game plan"/syllabus for this group. It is not at all finalized and I would very much appreciate any suggestions for improvements:

* Yellow Paper + Relevant EIPs as they appear
  * every chapter pertaining to the EVM, starting from the beginning
* Write common contracts in HUFF (do this live during study session with input/aid from participants)
* Write common contracts in YUL/inline assembly (do this live during study session with input/aid from participants)
* Understand the high level abstractions the solidity language provides (ex: immutables/constants, data types, etc...)
* Dissect (potentially debunk) the most common gas optimizations in audit reports/C4 reports.
  * this will include stepping through the bytecode of such optimizations and physically counting the gas savings (or lackthereof)
  
I belive that going through all the topics above will lead to a thorough understanding of the EVM as it pertains to security researchers/auditors. Certain topics are not explicitly stated above as we will naturally touch on them as we steps through the discussion topics: calldata, abi, components of a smart contract (construction, function dispathing, etc...), + anything else you can think of.

If you believe specific, necessary knowledge would not be covered in any of the topics above, please feel free to suggest any improvements.
