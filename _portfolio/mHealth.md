---
title: "mHealth"
excerpt: "Hermes: A Patient-Facing Mobile Application for the Privacy-Enhanced Transfer of Electronic Health Records <br/><img src='/images/mHealth-t.png'>"
collection: portfolio
---
2014 - 2015  Clemson University  
Winner of 2015 HFES ”mHealth Applications for Consumers” Design Competition

## Background

Health Information Technology (HIT) has grown exponentially in the past decade, allowing such tools such as the health record to transcend the paper format into a more integrated and accessible electronic form. Electronic Health Record (EHR) systems have the potential to improve care and reduce costs. However, this transition has not fully embraced its potential in terms of enabling patient privacy— EHRs could more easily allow patients to take ownership of their records, yet most have inherited their predecessors’ dearth of privacy options. This runs contrary to the Office of the National Coordinator for HIT and independent research, both of which have mandated the development of such privacy options.

## Project Purpose

This project seeks to fulfill the mandate for privacy options by utilizing previously existent research as the framework for a mobile EHR sharing tool. Enabling users to share their health information in the context of the medical encounter, our application grants patients the ability to control what information is shared with each respective provider. This level of control may assuage patients’ privacy concerns, which can in turn reduce the strength and frequency of negative privacy maintenance behaviors. These behaviors, such as lying to providers or avoiding care, directly damage health outcomes. Negating the circumstances for such actions negates the harm, improving overall health outcomes.

## Design Method

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
The results from this testing resulted in several concrete recommendations for our next iteration, particularly in regard to the more novel interface designs. All participants were successfully able to find a provider using the text search method (see 1)Text search), yet 43% of participants had trouble searching for a provider using the photo tool. In particular, the labeling of “Photo Recognition” proved confusing, with one participant suggesting that it implied facial recognition. However, most users successfully intuited its function after viewing the interface. On the information selection interface, the preset wheel (see 4)Preset wheel) and one of the custom settings (see 3)Custom B) both relied on a swipe functionality. However, without a cue as to the required action both UIs were ineffective for 43% of users, largely due to a tendency towards clicking rather than swiping. The Emergency Room sharing option, labeled as “ER” on the preset screen, was problematic for 57% of participants. Analysis revealed two distinct problems: users did not notice the button, or did not interpret “ER” as emergency room.  Finally, the time restriction feature saw a 29% failure rate. This was again due to users attempting to click rather than swipe, but in this specific instance we attribute the usability failure to the low fidelity of the year scroller; the feature we designed may have not closely resembled the scrolling feature intended.

### Iteration 2
#### Design
An interactive iteration of Hermes was developed on the JustinMind software for the second iteration. Given our push towards high accessibility and simplicity, we adopted many of Google’s Material Design guidelines beginning with this iteration. As designers of a health application that may be operated by older, inexperienced, or disabled users, we appreciated the strictures of simplicity, bold design, and visual cueing. With this consideration, we chose an easily legible typeface in a font size larger than 12 point, and worked towards creating large interaction areas and simple, intuitive text, per the recommendation of the National Institute on Aging.

This iteration also dramatically changed presets and the custom interaction selection. In terms of interactions, nearly all swipe features were traded for a familiar click interaction. In the preset screen, the wheel was exchanged for a horizontal bar of clickable, visually-associated preset options.  Our custom setting interface largely kept the previous design, exchanging swipes for clicks as the driving interaction. The exception was switching users, which did retain a swipe feature. Crucially, this interaction was cued by a static feature: dots beneath the primary user’s profile picture cue the user to the existence of more users. The resulting wireframe could be simulated on mobile devices, allowing real-time interactions, gestures, and animations within a mobile context. Simultaneously, the relatively simple nature of the design permitted rapid iteration.
![](/images/mHealth-3.png)

*1)Home screen 2)Presets screen 3)Text recognition 4)Custom*

#### User testing
Development of this iteration was followed by the concurrent think-aloud protocol with a similar set of tasks and questions. While much of the methodology rolled over from the previous iteration, the real-time interaction was a significant asset for testing. JustinMind specifically enabled more flexibility with interactions and gestures, as well as allowing information cueing through motion and transitions. These new interactions were tested with the help of older participants, seeking feedback on usability from a source outside of our standard 20-30 age group.

#### Results
Testing of the second iteration revealed two primary problem areas: the photo recognition feature and the custom selector. Half of participants were unable to initially use the text recognition tool, being confused by the terminology (See 3)Text recognition). One participant suggested:

*“Every app I have with something similar uses the word ‘Scan’. Maybe ‘scan text’.”  P10*

Only one participant was unable to use the custom setting tool, but half were confused during the process:

*“So does it share now or later? I feel like it needs checkboxes.” P8*

*“I don’t understand what happens when I press these; am I immediately sharing when I select them?” P9*

In addition, participants highlighted several problem areas in time restriction section, highlighting the need for better terminology and feedback. Testing also provided preliminary support for the efficacy of several designs: Switching between users, using the text search to find providers, and using the preset options were easily utilized by all users in this iteration.

### Iteration 3
#### Design
The third iteration built upon the previous interactive prototype, incorporating cueing, adding more options, and dramatically changing the custom information selection interface based on user input. Additionally, this iteration began an increased focus on consistency across button placements and sizes.

#### User Testing
This iteration used the same user testing methods as its predecessor: the think-aloud protocol and previously utilized task set. 

#### Results
![](/images/mHealth-4.png)

The third iteration was more successful than its predecessors in user testing; only the scan text and emergency sharing setting were not usable by more than 1 participant. Notably, when tasked to find a provider, all participants initially used the text search function. That interface succeeded in being both intuitive and hedonic— users were familiar with text searching, but were also pleased by the autocomplete function:

### Iteration 4
#### Design
The final user-tested iteration was similar to its predecessor, featuring significant changes at the preset, summary, and sharing verification screens. These changes utilized the gestalt principles of similarity and proximity to improve the usability of weak areas highlighted by user testing. 


#### User testing
The fourth iteration is the most recent to have been user tested. We utilized the same think aloud protocol and task list as the prior iterations.

#### Results
![](/images/mHealth-5.png)

*1)Home screen 2)Presets screen*

Our final user testing supported the usability of Hermes’ primary features, revealing only two notable usability issues (See appendix for results). One-fourth of participants failed to switch users because they did not notice the triple ellipses under the user pictures (See 1)Home screen). This may not be an issue in the full application, as the user would personally add each additional profile. Regardless, this error prompted increased salience of the ellipses in the final iteration. A separate issue arose in regard to the Emergency button-- users saw and could operate the button, but two did not intuitively understand the purpose or benefit of using the feature (See 2)Presets screen). That advantage was correctly summarized by one participant as follows: 

*“It’s an emergency, so you have a limited amount of time to go through the app. You want to share now, it’s like a 911 situation.” P21*

This response in particular prompted the final iteration to keep the familiar red cross symbol while renaming it “Share Now”. Similar changes were enacted throughout the app based on participant feedback. Examples include changing a checkmark to an arrow to avoid misinterpretation, and changing other labels to become more intuitive. This iteration also received the greatest quantity of positive feedback, with users complimenting the large buttons, persistent picture ID, 3-step progress bar, and *“pleasant” colors (P24)*. 

However, participants appreciated more than physical appearance. Likert-scale ratings after the usability test revealed that many participants would gladly use Hermes; On a 10 point scale where 1 is unlikely and 10 is likely, fully half of this iteration’s participants selected nine, indicating that they would almost definitely use this product.

------------------------------------------------------------------------------------------------------------------------------------------
## Final design
![](/images/mHealth-6.png)

![](/images/mHealth-7.png)

![](/images/mHealth-8.png)

![](/images/mHealth-9.png)

