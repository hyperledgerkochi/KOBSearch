# KOBSearch

| Title | KOBSearch |
|--- | ---|
| Version | *TBD* |


## Abstract   

The KOBSearch is a search service that provides a registered user with the information about the organizations or members of the organization, that are operating in the city of Cochin and registered with KochiOrgBook (KOB). It is the KOBAW (KOB Association Wallet) that will contain the verifiable data about the organizations thus enabling trusted digital verification service. The search can be performed at two levels:
1. Wallet level : *To search for the details about an organization*
2. VCR level :  *To search for the details about the members of an organization*

## Dependent Projects

* [KOBAssociation Wallet](https://github.com/hyperledgerkochi/KOBAW)
* [KOBConnect Wallet](https://github.com/hyperledgerkochi/KOBConnect)

## Motivation

In the existing scenario, there are many possibilities for document frauds like forging, counterfeiting, altering, falsification etc. This makes it difficult for a citizen to confirm the original identity of various associations or people and thereby fall into the traps set by cheaters. That means, there is an element of trust that is missing. In order to avoid this, finding authentic and authoritative data about people or organization, has become a crucial factor. KOBSearch provides the facility of searching for the data that they can trust. 

## Status of the project

Incubation

## Solution

KOBSearch helps the people to establish a trusted relationship with an entity (can be an organization or a member of the organization) by confirming their identities. KOBAW serves as a searchable public wallet containing open verifiable data about the organizations that are operating in the city of Cochin. Once registered with KOBAW, the entities get a digital identity of their own. 

A citizen can avail the service of KOBSearch to quickly verify if the entity is a legitimate one or not. The citizen is able to easily retrieve data regarding the entity in the form of verifiable credentials. The data can include registration ID, registration status, registration date and other essential details. These data are cryptographically verified ones; so a citizen can completely trust the information. The search can also lookup for third-party service providers that are registered on KOB with a public DID. It is also possible to search for associations and credentials that the associations can issue or verify. The third-party service providers can be leveraged for these verification purposes. For example, if a restaurant needs to be verified, it can be done by the 3rd party services like Swiggy or Zomato. These verifications can also be done by another association, like the restaurant owner's association. One can also search how to get a credential as a restaurant owner in Kochi (either through a food delivery provider or restaurant owners' association).

The search is performed on two types of data stores. One type is the Wallet data that are stored on the mobile phone of the citizen. So a search performed on this data will be a local search. The other type of search is for the data at the VCR level, which would be a broader search on the registered entities. Two capabilities of KOBSearch can also be noted here. Looking at KOBSearch as yellow pages, it becomes a service offering utility. While as a component, KOBSearch gets embedded into the Association Wallet.


## Contributors

[Shahna Mohammed](https://github.com/shahnamohammed)

## Testing the project

*TBD*

## References

* [OrgBook BC](https://www.orgbook.gov.bc.ca/en/home)
* [Edx Course - Introduction to Hyperledger Sovereign Identity Blockchain Solutions](https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS172x+3T2019/home)