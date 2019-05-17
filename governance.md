# Virtual Kubelet Governance

The following document outlines how the virtual kubelet governance operates. Virtual kubelet relies on two components, the pluggable interface and the providers that "plug-in." 

There are two levels of maintainers for virtual kubelet, core maintainers and project or provider maintainers. 

### Virtual Kubelet Core Maintainers

The Virtual Kubelet Core maintainers are responsible for: 

* Maintaining the mission, vision, values, and scope of the project
* Refining the governance and charter as needed
* Making project level decisions
* Managing the Virtual Kubelet brand
* Controlling access to Virtual Kubelet assets such as source repositories, hosting, project calendars
* Handling code of conduct violations
* Deciding what sub-groups are part of the Virtual Kubelet project
* Overseeing the resolution and disclosure of security issues
* Managing financial decisions related to the project

The core maintainers have to match the following criterea: 

* Between 3 and 5 people with a diverse representation from multiple companies. No one company shall have a majority vote therefore each company will get one vote total, no matter how many maintainers they have
* Any project maintainer is eligible to become a core maintainer
* An core maintainer can step down by emailing our maintainer list at cncf-virtual-kubelet-maintainers@lists.cncf.io
* Core maintainers must remain active, and if they are unresponsive for > 3 months they will automatically move to emeritus maintainer, unless a super-majority of the other core maintainers agree to extend the period to greater than 3 months. 
* When there is an opening for an core maintainer anyone can nominate candidate as a replacement. 
    * The nomination period is one month starting the day after the position becomes avaliable. 
    * The nomination must be via the Virtual Kubelet provider mailing list.
* When the nominated individual agrees to be a canidate, the project maintainers and the current core maintainers may vote. 
    * The voting period will be a minimum of 7 days and will close when a majority of project maintainers have voted. 
    * Each maintainer will get 1 vote, yes or no, and depending on the majority the candidate will either become a core maintainer or not. Maintainers will vote through a election form (Office forms or Google forms).
    * After a maximum of 2 weeks after the voting period started, the votes will be counted up and the status of the vote will be sent out to the project and core maintainers. 
* When an org maintianer steps down they become an emeritus maintainer.

### Project/Provider Maintainers

Project maintainers are responsible for maintaing the release cycle of virtual kubelet and the specific operations they own. Techincal decisions can be made by the project maintainers. There can be up to two maintainers per provider.

When maintainers need to make a decisions there are two ways decisions are made, unless described elsewhere.

The default decision making process is lazy-consensus. This means that any decision is considered supported by the team making it as long as no one objects. Silence on any consensus decision is implicit agreement and equivalent to explicit agreement. Explicit agreement may be stated at will.

When a consensus cannot be found a maintainer can call for a majority vote on a decision. Majority vote is between the provider maintainers and core maintainers. 

The following must be voted on: 

* Removing a core, or project maintainer for any other reason other than inactivity
* Licensing and intellectual property changes (includes new logos, wordmarks)
* Adding a new core maintainer or project maintainer. To successfully vote a new maintainer in there must be a super majority of 2/3s of the vote cast in favor of the candidate. 

If a project maintainer remains inactive for a period of 2 months or more, they will get a notice of issues to close or work on that are relevant to their provider. If they do not make any significant progress (progress is determined by core maintainers) then they will be labeled as an inactive provider and after 6 months of inactivity will be subject to removal from the Virtual Kubelet organization. 

