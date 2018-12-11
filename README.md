> 2018 Dec 12-15

This is a living document: Please feel welcome to add and edit as you see fit. Want Darcy to eat monkey brains for lunch on Thursday? Just add it to the agenda! Just _no_ `--force`ing!

## Schedule

We have Wednesday evening, all day Thursday, and Friday morning.

There is a meeting at the Daily time on Thursday and Friday that will include the "Easterlies" who unfortunately can't make it to this continent on such short notice. These meetings will last 1 hour.

__Required reading:__ [Questions](#Questions) below

These meetings and time spent together should result in _Answers_ to these questions, which will be versioned and documented on the ['answers' branch](https://github.com/meowsbits/sfagenda/tree/answers) for easy diffing. From there, and with whole team review and approval, they will be documented and implemented as relevant at places like the notorious https://github.com/meowsbits/kryptoknow.


| Day       |       UTC | Pacific Time (UTC-8) | Question/Topic                                                                                                                            | Notes                                                                                  |
| ---       |       --- |                  --- | ---                                                                                                                                       | ---                                                                                    |
| Wednesday |           |            1830-1930 | ETCLABS-hosted meetup                                                                                                                     | [on eventbrite](https://www.eventbrite.com/e/hashing-mining-oh-my-tickets-52030649072) |
| Wednesday |           |          2030-:moon: | :beers:                                                                                                                                   |                                                                                        |
| Thursday  | 1600-(1700?) |            0800-(0900?) | Team name, what are we going to work on, long-term values and priorities (and logistics, eg. legal), current state of recruitment+hiring  | https://zoom.us/j/6709779999                                                           |
| Thursday  |           |            0900-1200 | Continue long term discusion if necessary, and then 2-month-scoped priorities for those projects                                          |                                                                                        |
| Thursday  |           |            1200-1300 | Security practices, github admin and security specs, development infrastructure (CI, storage), build and distribution standards           |                                                                                        |
| Thursday  |           |            1300-1400 | [Working lunch, delivery] __TODO: What's for lunch?__                                                                                     |                                                                                        |
|           |           |                 1400 | PR channels, practices                                                                                                                    |                                                                                        |
| Thursday  |           |            1600-1700 | Relationship to ETCLABs incubator cohort and curriculum                                                                                   |                                                                                        |
| Thursday  |           |                 1830 | [Dinner] __TODO: Where's dinner?__                                                                                                        |                                                                                        |
| Friday    | 1600-(1700?) |            0800-(0900?) | "Working together" practices, policies, and patterns (_not_ tooling, expenses, or style), recruiting and hiring, PR channels and policies | https://zoom.us/j/6709779999                                                           |
|           |           |            0900-1030 | Expenses, tooling, and style: patterns and policies                                                                                       |                                                                                        |
| Friday    |           |                1100- | Schedule next all-hands meetup                                                                                                            |                                                                                        |
|           |           |                      |                                                                                                                                           |                                                                                        |

----

#### Questions

- In light of the `@krykoder` fiasco, which repos are we going to contribute to?
	+ Shall we fork ETCDEVTeam/ repos?
	+ Shall we contribute to ethereumproject/ repos?
	+ Shall we contribute to ethereumclassic/ repos?
	+ 

- We name an offical 'brand' name. What shall it be? (No, `ETC DEV LABS TEAM` is not going to fly ;)

- We need to set up development infrastructure and tooling.
	- We need to set up a Github organization.
		+ What shall our name be?
		+ How do we handle the billing?
		+ Shall we have standard policies for pushing to repos?
			* Review signoffs
			* Commit formatting and requirements 
				- eg. 
					- GPG signed
					- signed-off-by suffix line
					- subject prefixing  
					- problem/solution structure
			* Tag formatting and semantic versioning (same kinds of Q's as commits)
			* Passing tests
			* Passing builds
		+ What `roles` and permissions shall team members have, and how is this determined?
		+ Who's going to be in charge of this?
		+ When should it be done by?

	- We need to set up Circle CI.
		+ How do we handle the billing?
		+ Who's going to be in charge of this?
		+ When should it be done by?

	- We need to set up Appveyor.
		+ How do we handle the billing?
		+ Who's going to be in charge of this?
		+ When should it be done by?

	- We need to set up a builds site (or cloud storage in general).
		+ Shall this tie-in with a UI at a team website at a page like `/builds`?
			* Who's going to be in charge of this?
			* When should it be done by?
		+ How do we handle the billing?
		+ Who's going to be in charge of this?
		+ When should it be done by?
		+ What should it do? (eg. archive all nightly builds for all time? rotate archived nightly builds, but keep tagged builds..)

	- Shall we standardize distribution channels across projects?
		+ eg. `homebrew`, `snap`, `AppImage`
		+ Who's going to be in charge of this?
		+ When should it be done by?

- We're going to need to work together.
	+ We're going to need to keep track of who's doing what and when, if they're blocked, and what the current and historical progress is.
		- What tools are we going to use?
			- eg.
				- Slack (pro?)
				- Zoom
				- Jira
		- How are we going to manage the planning and progress reporting? (eg. Roadmaps, Sprints, Sprint planning and retrospectives) 
		- When are we going to schedule time for these things? (Daily mtgs, Biweekly sprint plans)
		- Are these sessions all-hands, or shall we break these into small project-teams?

	+ Shall we establish shared "time-online" windows?
	+ Shall we have scheduled time for code reviews?
	+ Shall we have scheduled time and protocols for progress and performance feedback?
	+ Shall we have scheduled "watercooler" time?
	+ Shall and how shall we schedule team in-person roundups? (eg. Poland)
		* Shall these always be all-hands, or occasionally per project group?
	+ What are some rules of thumb and checklists for awesomeness-assurance that we can work and live by?
		* eg. 
			- If someone's blocked, drop what you're doing and help them (all for one, and one for all).

	+ Shall we have "house rules" style guides per language, subject, and/or medium?
		- eg. 
			+ #howto tweet good
			+ Why `gofmt` is a beacon of truth and hope and dignity.
			+ WWS&WD: What Would Strunk & White Do?

	+ Meta alert: Shall we write these policies and practices down and keep them maintained?
		- Who's in charge of that?
		- When should it be done, and be tended to?

- What are we going to work on?
	+ Geth:
		* Are we going to continue work on ethereumproject/go-ethereum?
		* Are we going to work on ethoxy/multi-geth?
		* Where do we stand w/r/t ECIP1045 (ETH::Byz+Const EVM catchup hard fork for ETC)?
		* EWASM demanded a hardfork for ETH. Are we proposing a corresponding HF for ETC (@r8d8)?
		* What are long range priorities and values for the project?
		* What are 2-month-scoped next steps?
	 
	+ Orbita:
		* Where do we stand on this? Are we going to continue work on it? 

	+ Emerald:
		* Are we going to continue work on the Emerald SDK?
		* What are long range priorities and values for the project?
		* What are 2-month-scoped next steps?

	+ SputnikVM:
		* Are we going to continue work on SputnikVM?
		* (Shall we fork it?)
		* What are long range priorities and values for the project?
		* What are 2-month-scoped next steps?

	+ Documentation:
		* What tools shall we use?
		* What are long range priorities and values for the project?
		* What are 2-month-scoped next steps?
        
    + :sky:
        * Anything else?

- How do we relate to ETC LABS Incubator?
	+ Do we spend 10% of time interfacing/advising them?
	+ Are there existing programs that ETC LABs puts the teams through, ie educational, industry-facing?
		* Who's in charge of pulling these together?
	+ Are there educational programs in place around...
		* Business in general, esp. Silicon Valley
		* Blockchain tech, both w/r/t ETC, et al.

- Are we hiring?
	+ Who's in charge of this?
	+ (Why am I being invited to random-seeming interviews with strange-looking candidates with no context)?
	+ What positions are we hiring for?
	+ Where and how are we canvassing for candidates?

- Looking beyond ourselves...
	+ Who are we going to prioritize engagement with?
		* Developers, miners, industry end-users, investors?
	+ Where are those channels going to be in each case?
	+ What are our team's social mediums?
		* eg...
			- forum.ethereumclassic.org,
			- Team website
			- Twitter
			- Discord
			- Gitter
			- Email
			- Telegram
			- Facebook
			- Youtube
			- Medium
			- Google Drive
			- Github
			- Reddit
			- Hackernews
			- Meetups (yes, with actual humans)
	+ Who's in charge of our team's social media in each case?
	+ Who has write-access to our team's social media in each case?
	+ What are the expectations for each case as far as:
		* Behavior and acceptable-use policies
		* Volume and frequency


- What are our expense policies and practices for team and team member resources?
	+ eg.
		- Standard monthly allowance for hardware and compute infrastructure costs (eg. VPS rent, hardware wallet, OS's, IDE licenses)
		- Standard allowance and timing policies for "Oh, shit" hardware and compute infrastructure costs (eg. spillt ~beer~ coffee)
		- Standard allowance for do-ocracy principles and independent research (eg. buy an Arduino, make a blockchain flamethrower)
		- Standard allowance for education; eg. books, courses, gatherings
		- Travel policies

	+ How do we handle billing and expense reporting?


#### Topics

> These unscheduled discussion and meeting points should be organized into Question format,
> and then moved to the [Questions](#Questions) section above :arrow_up:


__PR/community relations w/r/t whos forking who__
- [ ]

__Team infrastructure and tools__
- [ ] [ ] spinup logistics discussion and infrature/tooling decisions, see https://github.com/meowsbits/kryptoknow
- [ ] [project management tools](https://github.com/meowsbits/kryptoknow/issues/4)

__Team practices and policies__
- [ ] | Recruiting and hiring
- [ ] Practices and policies here: https://github.com/meowsbits/kryptoknow#daily-developer-routine-practices-and-policies

__Roadmapping__
- [ ] geth
	+ https://github.com/ethoxy/multi-geth
- [ ] Emerald
- [ ] Sputnik

__ETCLABs Incubator__
- [ ] educational sessions and opportunities covering
	+ biz and profit
	+ blockchainz

__Staffing__
- [ ] Geth
- [ ] Emerald
- [ ] SputnikVM
- [ ] Project management
- [ ] Market research or BA (not suggesting, just asking)

__Marketing/ Communication Channels__

_team channels_
- [ ] Medium
- [ ] Twitter
- [ ] Youtube
- [ ] Github (private for writing)

_community channels_
- [ ] Forum: https://forum.ethereumclassic.org/
- [ ] Discord
- [ ] Reddit: https://www.reddit.com/r/EthereumClassic/
- [ ] Telegram

__Docs and Web__

_documentation and team website_
- [ ] Docusaurus API: https://github.com/facebook/Docusaurus
- [ ] Site Hosting: Github provided
- [ ] Site Domain: Github provided
	- [ ] Update docs and edu links on ethereumclassic.org

_site map_

- roadmap
- team
- docs
	- overview
	- guides
	- reference
	- samples
	- design & quality
- jobs
- contact
- blog
