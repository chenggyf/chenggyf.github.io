---
title: "mHealth"
excerpt: "Hermes: A Patient-Facing Mobile Application for the Privacy-Enhanced Transfer of Electronic Health Records <br/><img src='/images/mHealth-t.png'>"
collection: portfolio
---
2014 - 2015  Clemson University

## Background

Health Information Technology (HIT) has grown exponentially in the past decade, allowing such tools such as the health record to transcend the paper format into a more integrated and accessible electronic form. Electronic Health Record (EHR) systems have the potential to improve care and reduce costs. However, this transition has not fully embraced its potential in terms of enabling patient privacy— EHRs could more easily allow patients to take ownership of their records, yet most have inherited their predecessors’ dearth of privacy options. This runs contrary to the Office of the National Coordinator for HIT and independent research, both of which have mandated the development of such privacy options.

## Project Purpose

This project seeks to fulfill the mandate for privacy options by utilizing previously existent research as the framework for a mobile EHR sharing tool. Enabling users to share their health information in the context of the medical encounter, our application grants patients the ability to control what information is shared with each respective provider. This level of control may assuage patients’ privacy concerns, which can in turn reduce the strength and frequency of negative privacy maintenance behaviors. These behaviors, such as lying to providers or avoiding care, directly damage health outcomes. Negating the circumstances for such actions negates the harm, improving overall health outcomes.

##Design Method

To design a mobile application that enables the privacy options patients require, our team employed an iterative process beginning with a literature review and development of specific solutions. This was followed by multiple conceptualizations and an initial prototype concept. This concept began a five-stage iterative design process, including four cycles of user testing. User testing employed a think-aloud protocol, and was combined with continuous informal heuristically analysis by our design team. Combined, these methods informed the structured design and development process.

## Final Design

Our design process resulted in Hermes, a mobile application concept that allows users to select a provider and choose which health information can be accessed by that provider. These privacy options have been informed by patients’ own preferences and the design has been informed by 24 participants in multiple iterative cycles. The application is intuitive and simple to use, allowing sharing settings to be created in moments with little information required from the user. Hermes promises to not only enhance privacy, but also to ease the overall EHR transfer process from both the patient and provider perspectives.

------------------------------------------------------------------------------------------------------------------------------------------

## Design process

### Initial mock-ups

The first, conceptual phase of development involved the creation of multiple paper prototypes. Creating such prototypes assisted the designers in conceptualizing the workflow and functionality of the primary elements. Outside of conceptualizing a standard template for navigation, we did not use wireframes or other graphic tools in this stage, concerned that such tools may engender a focus on layout and restrict originality. 
![](/images/mHealth-1.png)

### Iteration 1
#### Design
Mock-ups of the first iteration were refined from the initial paper concepts and created using the graphics editor Photoshop and the Microsoft Word word. This iteration included all of the primary features of the final application: 1) Login; 2) User Selection; 3) Provider Selection; 4) Information Selection; 5) Time Restriction; 6) Review of Sharing Setting; and 7) Sharing Verification. Crucially, the provider selection and custom information selection both offered alternate interactions: each had an A and B version of the interface, using different methods to achieve the same goals.
![](/images/mHealth-2.png)

*1)Text search method for finding a provider 2)Custom setting A and 3)B, from left to right 4)Preset wheel of information selection*

#### User testing
The first stage of user testing utilized the mobile application Prototyping On Paper (POP). Our design team tested seven participants with this method. The application’s purpose was explained to each participant, before they were presented with the POP prototype running on an iPhone and given 9 brief tasks to complete in succession:

1. Log in to the app
2. Switch to a different user
3. Share this user’s health information
4. Share with Fairfax General Hospital:
4a. Text search
4b. Scan text
5. Select information to share:
5a. Use presets
5b. Use presets
6. Create custom setting
7. Create time restriction
8. Finalize sharing setting
9. Finalize sharing setting

The POP test was combined with a concurrent think-aloud protocol, as we requested participants to speak their inner-monologue as those thoughts occurred. The resulting qualitative data was combined with simple quantitative results and personal heuristic evaluations to provide design recommendations for the following iteration.

#### Results
The results from this testing resulted in several concrete recommendations for our next iteration, particularly in regard to the more novel interface designs. All participants were successfully able to find a provider using the text search method (see Design), yet 43% of participants had trouble searching for a provider using the photo tool. In particular, the labeling of “Photo Recognition” proved confusing, with one participant suggesting that it implied facial recognition. However, most users successfully intuited its function after viewing the interface. On the information selection interface, the preset wheel (see Design) and one of the custom settings (see Design) both relied on a swipe functionality. However, without a cue as to the required action both UIs were ineffective for 43% of users, largely due to a tendency towards clicking rather than swiping. The Emergency Room sharing option, labeled as “ER” on the preset screen, was problematic for 57% of participants. Analysis revealed two distinct problems: users did not notice the button, or did not interpret “ER” as emergency room.  Finally, the time restriction feature saw a 29% failure rate. This was again due to users attempting to click rather than swipe, but in this specific instance we attribute the usability failure to the low fidelity of the year scroller; the feature we designed may have not closely resembled the scrolling feature intended.

### Iteration 2
#### Design
