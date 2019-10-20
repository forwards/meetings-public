# Slackathon 2019-09-20

## Attendance

### Core team

Present: Heather Turner (HT), Angela Li (AL), Emily Dodwell (ED), Kevin O'Brien (KO)  
Absent: Tania Allard (TA), Jenny Bryan (JB), Jonathan Godfrey (JG), Isabella Gollini (IG), Julie Josse (JJ), Tanja Kecojevic (TK), Michael Lawrence (ML), Shakirah Nakalungi (SN),  Noa Tamir (NT), Florencia Mangini (FM)

### Sub-teams

Present: Nic Crane (NC), Lorna Maria Aine (LM), Joyce Robbins (JR)  
Absent:  Damiano Cerasuolo (DCerasuolo), Di Cook (DCook), Liz Hare (LH), Madlene Hamilton (MH), Nujcharee Haswell (NH), Zhian Kamvar (ZK), Liz Kellogg (LK), Joslynn Lee (JL),  Imke Mayer (IMayer), David Meza (DM), Ileena Mitra (IMitra), Ritwik Mitra (RM), Jesse Mostipak (JM), Richard Ngamita (RN), Wenfeng Qin (WQ), Emma Rand (ER), David Smith (DS), Charlotte Wickham (CW), Yizhe Xu (YX)

## Minutes

### Core team/General
- (HT) Several teams were able to meet in August, and the remainder have met/will meet in September. It took quite a bit to organise, but I think this is a good way to get to know new members and prioritise team tasks. I suggest we do it again next August.
    - (ED) Team call minutes from slack (if available) have been copied below under the respective team's section.
 
- (HT) We have been notified of a couple of up-coming conferences, listed below. Please add any events you think Forwards should promote/be aware of, e.g. events you will be at!
    - [caRdiff satRday](https://cardiff2019.satrdays.org/): 16 November 2019 at Cardiff University. This will include a pre-conference hackathon on the Transgender Day of Remembrance data set. ([Call for Speakers](https://sessionize.com/cardiff-satrday-2019))
    - satRday Nairobi
    - R workshop prior to [Data Science conference at University of Rajshahi](http://www.ru.ac.bd/stat/conference-2019/): 18-19 December 2019 in Bangladesh (site does not show workshop yet)
    - [Use of R in Official Statistics](https://twitter.com/uRosconf/status/1174580475165380608?s=20) (uRos2020): 6-8 May 2020 in Vienna, Austria
 
- (HT) Samantha Toet is joining the Community team as a regular member. She is lead of the R Consortium's R Community Diversity and Inclusion working group, and she is particularly interested in working together on initiatives such as smoothing the visa application process for R conference attendees and supporting AfricaR.
    - (AL) Hooray! So glad that this is happening.

**ACTIONS**
 - Add to these minutes any progress that has been made since your team meeting (or the last slackathon) (ALL)
 - Add minutes of team meetings to these minutes (ED - done)
 - Advertise events on Twitter (SN)
 - Add events to Webpage (JR)

### Community team
- Community Team [Call Notes](https://rforwards.slack.com/archives/C3WKWBDLG/p1565978021026000) (August 16)
    1. Supporting Rainbow R: DCerasuolo is talking to Rencontres R and eRum organizers about organizing meetups at those conferences. NT has admin access now to the Slack. It would be good to have access to the GitHub and Twitter. The webpage could have info on how to join the Rainbow R Slack and thing like interviews. Interviews with RLGBT folk could be crossposted on the Forwards blog (cc LM, DS).
    2. Institutional memory: KO is adding pieces of information as issues on the Community Repository, e.g. about COC enforcement, how finances are mananged, etc. This could be built up into a GitHub wiki. It is also an opportunity for people in remote locations to contribute.
    3. TA is organising an event on Python and R in Mexico. She will keep us posted and is willing to write a blog post afterwards (cc LM)
    - *Actions*: If folks (DCerasuolo, NC) send KO their GtiHub username and Twitter handle, KO can ask Ben to give you access.

- (NC): DCerasuolo and I met with leadership from QueerInAI earlier this month and received some good ideas, currently outlined in #community [on slack](https://rforwards.slack.com/archives/C3WKWBDLG/p1568233736014600), about getting sponsorship for events. Recommendations included requesting to add a survey onto the conference survey.

**ACTIONS**
- Find appropriate repo to document recommendations from QueerInAI (options [on slack](https://rforwards.slack.com/archives/C3WKWBDLG/p1569355426003300)) (NC)
- Decide if there's anything this year we can collaborate on a proposal for.


### Conferences team
(No slackathon items at this time.)

**ACTIONS**
- Team call scheduled for Wednesday, September 25 (no slackathon minutes).


### On-ramps team
- On-ramps Team [Call Notes](https://rforwards.slack.com/archives/C3WLPNEJD/p1566416422037800 (August 21)
    - Potential areas for the team (from existing issues):
        1. Blog post series on collaboration/contribution
        2. Promoting good first issues
        3. Supporting first CRAN submissions
    - Consensus to focus on 2, which fits in with [this issue](https://github.com/forwards/Community/issues/17) to provide opportunities for remote participation.
    - *How should we gather issues?*
        1. Create search URLs, e.g. for "good-first-issue" + "documentation", in R repos. NB can encourage labelling "good-first-issue" but can't label issues unless we're a collaborator.
        2. Create search URLs for common typos in R packages.
        3. Maybe fork a repo and break bigger issues down into micro-issues, e.g. "fix this typo": creates a safe space, issues can be combined in one PR to minimise work for maintainer.
        4. Gather documentation with typos in [my_first_pr rep](https://github.com/forwards/my_first_pr) and add related issue. Invite people to fix the issue and mentor them (create/link to HOWTOs?). After dry run on our repo, support them to make PR to actual repo.
        5. Adopt package as R-Ladies did with praise package/find friendly maintainers to work with.
        6. Create a deliberately messy sandbox package that people can practice on. People can file a PR to fix an issue or create a bug so that it continues to be a messy package, but they see theit PRs merged. Repo created [here](https://github.com/forwards/r_package_sandbox).
    - *How can we promote these issues?*
        1. At package workshops
        2. At conferences like useR! where we can give "How to start contributing" presentations (or even host a contributing session/tutorial)
        3. Via other community events (get taskforce members/R-Ladies to help advertise)
        4. Through Twitter/FB/LinkedIn
        5. Through a Twitter/Slack bot or similar
        6. Through a blog post. Issue here is making sure people have enough support to get started - can we link to other HOWTOs? May be best to focus on a theme, e.g. fixing a typo.
    - *How can we recognise people's contribution?*
        1. Listed as CRAN contributor on CRAN website? Probably too much to ask at this level.
        2. Tie in with something like Hacktoberfest? Need to check details.
        3. List on Forwards website/elsewhere once achieved a certain milestone (e.g. 3 pull requests).
        4. Get funding for our own t-shirts/other small gifts
    - *Suggested actions:*
        1. Start gathering faulty documentation in my_first_pr (KO)
        2. Create some search URLs (ZK)
        3. Look for existing HOWTOs/support material (CW)
        4. Check status of praise package and existing R package projects that R-Ladies are working on (HT)
        
(No slackathon items at this time.)


### Social media team
- Social Media Team Call Notes (September 19)
    - Focus on reactivating the blog. Team meeting was a walk-through of how to add and publish a new post.
- (HT) Blog post on package development workshops has been [published](https://forwards.github.io/blog/2019/09/22/workshops-for-women-and-girls/).
    - Main changes from draft enumerated in #social-media [here](https://rforwards.slack.com/archives/C3WKN5S4Q/p1569152970004300)
    - (JR) Post appeared on [R-Bloggers](https://www.r-bloggers.com/workshops-for-women-and-girls/)

**ACTIONS**
- Advertise publishing of blog post on Twitter and/or retween R-bloggers and R Weekly tweets about it (SN)


### Surveys
- Surveys Team Call Notes (no slack minutes)
    - Focus on useR! reports, assigned as follows: 2017 (DM), 2018 (TK), 2019 (NH)
- (HT) NH has done first draft of report on useR! 2019 registration and survey data (on private survey repo). I have reviewed this so she can work on a second draft.

**ACTIONS**
- Second draft of useR! 2019 report (NH)
