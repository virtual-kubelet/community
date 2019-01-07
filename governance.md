# Virtual Kubelet Governance

The following document outlines how the virtual kubelet governance operates. Much of this document has been repurposed from Helm's governance guidelines. 

Virtual kubelet relies on two components, the pluggable interface and the providers that "plug-in." 

## Maintainers Structure

There are two levels of maintainers for virtual kubelet. The virtual kubelet core maintainers oversee the overall project and it's health. 

### Virtual Kubelet Core Maintainers

The Virtual Kubelet Core maintainers are responsible for: 

* Maintaining the mission, vision, values, and scope of the project
* Refining the governance and charter as needed
* Making project level decisions
* Managing the Virtual Kubelet brand
* Controlling access to Helm assets such as source repositories, hosting, project calendars
* Handling code of conduct violations
* Deciding what sub-groups are part of the Helm project
* Overseeing the resolution and disclosure of security issues
* Managing financial decisions related to the project

The core maintainers have to match the following criterea: 

* There will be between 3 and 5 people
* Any project maintainer is eligible to become a core maintainer
* An core maintainer can step down by emailing our maintainer list (LINK TBA)
* Core maintainers must remain active, and if they are unresponsive for > 3 months maintainership unless a super-majority of the other core maintainers agree to extend the period to greater than 3 months. 
* When there is an opening for an core maintainer anyone can nominate a project maintainer as a replacement. 
    * The nomination period is one month starting the day after the position becomes avaliable. 
    * The nomination must be via the VK mailing list (LINK TBA)
* When the nominated individual agrees to be a canidate, the project maintainers may vote. 
    * The voting period will be a minimum of 7 days and will close when a majority of project maintainers have voted. 
* When an org maintianer steps down they become an emeritus maintainer.

### Project Maintainers

Project maintainers are responsible for maintaing the release cycle of virtual kubelet and the specific operations they own. Techincal decisions can be made by the project maintainers. 

When maintainers need to make a decisions there are two ways decisions are made, unless described elsewhere.

The default decision making process is lazy-consensus. This means that any decision is considered supported by the team making it as long as no one objects. Silence on any consensus decision is implicit agreement and equivalent to explicit agreement. Explicit agreement may be stated at will.

When a consensus cannot be found a maintainer can call for a majority vote on a decision.

The following must be voted on: 

* Removing a maintainer for any other reason other than inactivity
* Licensing and intellectual property changes (includes new logos, wordmarks)

