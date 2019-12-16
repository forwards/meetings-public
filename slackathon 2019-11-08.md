# Slackathon 8-11 November 2019

## Attendance

### Core team

Present:Heather Turner (HT), Emily Dodwell (ED), Kevin O'Brien (KO), Noa Tamir (NT)  
Absent: Tania Allard (TA), Jenny Bryan (JB), Jonathan Godfrey (JG), Isabella Gollini (IG), Julie Josse (JJ), Tanja Kecojevic (TK), Michael Lawrence (ML), Angela Li (AL), Shakirah Nakalungi (SN)

### Sub-teams

Present: Liz Hare (LH), Ritwik Mitra (RM), Lorna Maria Aine (LM),  Nujcharee Haswell (NH)  
Absent: , Damiano Cerasuolo (DCerasuolo), Di Cook (DCook), Nic Crane (NC), Madlene Hamilton (MH), Zhian Kamvar (ZK), Liz Kellogg (LK), Joslynn Lee (JL), Florencia Mangini (FM), Imke Mayer (IMayer), David Meza (DM), Ileena Mitra (IMitra), Ritwik Mitra (RM), Jesse Mostipak (JM), Richard Ngamita (RN), Wenfeng Qin (WQ), Emma Rand (ER), Joyce Robbins (JR), David Smith (DS), Samantha Toet (ST), Charlotte Wickham (CW), Yizhe Xu (YX)

## Minutes

### Core team/General
- HT: Cardiff satRday is next week and there will be a [pre-conference hackathon](https://www.meetup.com/Cardiff-R-User-Group/events/265508847/) centred on the Transgender Day of Remembrance data. Hope to have some outputs we can share more widely afterwards. There are also tentative plans to livestream the satRday talks so that remote folk can tune in - we'll probably just advertise this on the day if we get it working!

### Community team
- NT posted a [first draft](https://github.com/forwards/event_best_practices/blob/meetup-advice/meetup_best_practices.md) for DEI recommendations for meetup organizers (work shared with NumFOCUS DISC) -- feedback is welcome.
- KO proposed satRday events promoted well in advance that allow parents to attend (with reasonable minimal overhead for sorting out childcare).
    - Dublin R is gone for the time being (lack of access to venues was a problem). We are going to set up an Irish version of WhyR (as a legal entity) and hope to revert to how we did things with Dublin R.
    - NT received feedback from satRdayorganisers that it can be much harder to get venues for the weekend.
- KO proposed following general topics for the year ahead (see [thread in #community](https://rforwards.slack.com/archives/C3WKWBDLG/p1573309433005600) for full proposal and discussion):
    1. Accessibility of event websites for R community users with visual impairments.
        - What does a website need?
        - As the organizers are typically volunteers - what is a reasonable amount of overhead and cost?
        - I believe that amending the HTML tags for images to include descriptors can make a huge difference.
        - We should collaborate with other communities (e.g. Python, Julia) in this regards.
        - LH: Web accessibility guidelines [here](https://www.w3.org/WAI/standards-guidelines/wcag/#whatis2).
        - LH: I have been looking into open source web accessibility checking software. Re: use of Blogdown in the R community, I have found the blogdown materials that I’ve read to be accessible. I have not studied what needs to be done, if anything, to make sure they can be navigated it easily.
        - KO: Section about better website accessibility on Blogdown tutorial website could be a big prompting signal to everyone to do more there.
    2. Accessibility Chairs & Publication of Accessibility Plans
        - Event organizers should, ideally, have accessibility co-ordinators from now on.
        - An accessibility plan should be devised for both the conference venue and the location of the social event. Organizers should mitigate accessibility as much as possible.
        - Accessibility plans should be published on the website (not necessarily with prominence).
        - It may be the case that, for a social event, a venue is provided for free, but has poor accessibility. What is the best thing to do here?
        - LH: I agree with all these points. It’s important to have a contact person for access questions and early because the answers to accessibility questions will help people to decide whether to attend.
        - LH: Social events need to be accessible to everyone. They are an integral part of the conference experience and inclusion shouldn’t be optional (e.g. wheelchair access, sign language interpretation).
    3. Developing Cost Effective Live-streaming capabilities
        - Develop a knowledge base for
         1. Camera Equipment
         2. Microphones
         3. Livestreaming platforms
         4. Sharing slides 
        - This is something the JuliaCon organizers are really good at. The videos are posted online on LinkedIn and Twitter to publicise the use of Julia.
        - We are going to trial livestreaming at SatRdays Cardiff
        - LH: Make sure platforms are accessible to users of screen readers and an other adaptive equipment. Will videos they be captioned? The automatic captioning service is provided by platforms like YouTube are not accurate enough for technical material.
        - LH: Remote conferences are a big win for people with disabilities who can’t attend, in addition to all the other people who benefit from not having to travel.
    4. The R consortium working Group on Diversity and Inclusion
        - Chaired by ST (RStudio)
         - Recent talking points are Conference Best practices, Accessibility, R in Africa
         - The Working group is recruiting new personnell
    5. Collaborations with other communities
        - Europython is coming to Dublin in July 2020.  This is a European level Python conference that would be roughly the same size as useR! run by the Europython Society and is administered by a series of working groups.  See [here](https://www.europython-society.org/workgroups).  This is a very good way to retain and develop institutional knowledge.
        - JuliaCon 2020 is taking place in Lisbon the week after. It is much smaller, but it is organized more or less the same way.
        - I reckon that involvement with events present a great learning opportunity in how to deliver a great conference for everybody.
    6. The R Consortium Working Group on Diversity and Inclusion.
        - The RCWGDI is now a top level project of the R Consortium.  There is a montly conference call on the first Monday of each month, chaired by ST.
        - The first series of projects have wrapped up, and the working group is developing a new task set, including a Visa Expediation project, and and Remote Accessibility / Livestreaming knowledge base.
        - There is a conferences best practice knowledge base developed by NT.
    7. The Visa Problem
        - There are, once again after controversy about it last year, problems with African AI researchers being refused entry to Canada to take part in the NeurIPS conference. There seemingly was a visa chair, but at the end of the day, the Canadian Immigration Agency can seemingly say "no" without much accountability. There are now calls to move the NeurIPS conference, and other such conferences, to "Visa Friendly" countries.
        - It is my understanding that an invitation signed by a Government agency can improve the chances of a Visa Application being accepted.
        - R Conference organizers should be encouraged to enlist their National Statistical Agencies in running conferences.
        - Relevant links: [Schengen Visa Info](https://www.schengenvisainfo.com/news/10-easiest-schengen-countries-to-obtain-a-schengen-visa/), [Twitter thread](https://twitter.com/vzakhary/status/1193247955265802240), [Most Welcoming Countries Rank](https://www.passportindex.org/byWelcomingRank.php), [Twitter thread](https://twitter.com/mpd37/status/1193457862560882688)
    8. Sponsorship and Revenue
        - As noted at the R consortium Working Group Conference Call, implementation of a comprehensive  accessibility plan (e.g. livestreaming, captioning) would require significant financial costs.
        - Diversification of sponsorship by conference and event organizations is important (i.e. don't rely solely on R Consortium or RStudio to contribute to this effort). Python Community has better systems in generating revenues to fund DEI, Accessibility and African programs that we should look at.
        - (See [conversation on funding for inclusion](https://rforwards.slack.com/archives/C3WKWBDLG/p1573349188019900) with following key points:)
        - HT: Not only due to the amount needed, but also for stability of income. Big sponsors have come and gone (sometimes even pulling out near to the conference after promising money); others want to make a one-off big splash when they launch, so can't be depended on long-term; others have PR issues so organizers would rather not have them as sponsors.
        - LH: I think it will be a lot easier to fund livestreaming than accessibility, and that organizations that have taken leadership roles in the R environment should be involved with inclusion efforts (i.e. RStudio is not accessible for blind people using screen readers). HT: As I understand it RStudio are working on making their IDE screen-reader friendly, but I haven't seen an update recently.
        - KO: The best avenue of advance may be to educate the general R community about what it is like to interact with it as blind or visually impaired person. If more people know about it, companies would be more responsive to community needs.
- HT: useR! 2020 are thinking of not covering visa expenses in the diversity scholarships and NT and I are trying to persuade them otherwise.

### Conferences team
- LH will add to draft of Best Practices for Diversity Inclusion after finding more resources on disability and inclusion at conferences.
- NT: [Task list](https://github.com/forwards/conferences/blob/master/Documentation_plans.md) of things to document from past initiatives in a tool-kit style for future useR! organisers to make it easier for current and future organisers to repeat Forwards’ DEI initiatives.
- NT: [Thread](https://twitter.com/timnitGebru/status/1191970600941707265) points to wider problem of denied visas for conferences and events.
    - HT: Idea of dedicated visa chair is interesting.
    - NT: Recruitment chair for the Black in AI workshop said it’s all the same letters and communications work, but he is open to share experience and ideas on their issues and concerns.

### On-ramps team
(No items at this time.)

### Social media team
- LM completed "The state of R in Africa" post, which has been published [here](https://forwards.github.io/blog/2019/11/15/the-state-of-r-in-africa/).

**ACTIONS**
- Public blog post written by AL and ST about R-Ladies Charlottesville workshop.

### Surveys
(No items at this time.)

### Teaching
(No items at this time.)

### AOB
- Next slackathon will be in January 2020.  Vote for your preferred weekend via the [survey in Slack](https://rforwards.slack.com/archives/C3XD6925A/p1575252709000800)
