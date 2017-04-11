# fact-check
A home for all things fact-checking-related in D4D. 

**Slack:** [#factcheckbot](https://datafordemocracy.slack.com/messages/factcheckbot/)

**Project Description:**
So much information is quickly and easily disseminated on social media, with little way for users to fact-check within social media itself. As such, incorrect “facts” can spread across user networks largely unchecked. We aim to create a service/technology that quickly and easily increases the number of research and fact-based social media posts. By implementing a platform-based solution, we will be able to insert our technology across multiple endpoints, including at the content creation phase.

**Project Lead:**  
[@ccarey](https://datafordemocracy.slack.com/messages/@ccarey/)

**Skills:**  
_Skills you may learn or already posses relevant to this project._
* natural language processing
* experience with different social media APIs
* database management
* crowdsourcing
* communication with potential organizational partners
* research into best practices & the state of the field of fact-checking
* the ability to tell fact from alt-fact! 

## Background Readings
### automated fact-checking:
* [The Year of the Fact-Checking Bot](http://www.niemanlab.org/2016/12/the-year-of-the-fact-checking-bot/), by Professor Bill Adair  
 _A very quick and recent read on the increasing importance of real-time automated fact-checking._
* [366 Links to Understand Fact-checking in 2016](http://www.poynter.org/2016/366-links-to-understand-fact-checking-in-2016/440618/), by Alexios Mantzarlis  
  _Literally 366 well curated and organized links about different aspects of fact-checking!_
* [Automated Fact Checking: The Holy Grail of Political Communication](http://nordicapis.com/automated-fact-checking-the-holy-grail-of-political-communication/), by Bill Doerrfeld & Kirsty Moreland  
  _A mid-length article that describes each part of the fact-checking process, which could be helpful in mapping out different segments of the project._ 
* [The State of Automated Factchecking](https://fullfact.org/media/uploads/full_fact-the_state_of_automated_factchecking_aug_2016.pdf), by FullFact.org  
  _A fairly comprehensive overview of the fact-checking tech from a major UK org._
* [Design Solutions for Fake News](https://docs.google.com/document/d/1OPghC4ra6QLhaHhW8QvPJRMKGEXT7KaZtG_7s5-UQrw/edit), by MediaReDesign  
  _A massive crowdsourced document for fighting fake news._ 

### natural language processing: 
Word vectors are a way to encode words as vectors with a few hundred dimensions that capture semantics such as gender, hierarchy, and sentiment, as well as syntax. This means that vectors can also be built for phrases (or tweets), which can then be used in traditional machine learning algorithms to label them with a particular fact.
* [A Beginner's Guide to word2vec](https://www.distilled.net/resources/a-beginners-guide-to-word2vec-aka-whats-the-opposite-of-canada/)
* [The Amazing Power of Word Vectors](https://blog.acolyer.org/2016/04/21/the-amazing-power-of-word-vectors/)

## Current Sub-Projects
### FactCheckBot
**Project Description:**
As one potential endpoint, we plan to develop a Twitter-based fact-checking bot, which would behave as follows:
```
Original Poster: We are entering a new ice age. 
Skeptical User: @CatchyNameTBD, is that true?
@CatchyNameTBD: No, the earth’s temperature is warming at a rate of X per year [link to journal article]
```
Original tweets would be parsed using natural language processing techniques, which would link them to a database of verified facts, against which claims could be checked. This database would be comprised both of an existing archival knowledge base and a crowdsourced factbase of verified users who could submit links to reliable science or news articles to support their claims. 

**Project Scope:**
At first, we will focus on fact-checking claims related to _climate science_. We will rely on the existing [Skeptical Science](https://www.skepticalscience.com/) knowledgebase.
