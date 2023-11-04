# Phase II: Refining interaction and designing wireframes

## Introduction

To further refine the user experience of our revolutionary application, we have shifted our focus towards obtaining user feedback to help identify potential areas for improvement. This user feedback has been instrumental as we increase the efficiency and satisfaction of navigating the Tee-Together app interface in its current wireframe form.

## Methods

Near the end of Phase 1, the Tee-Together software engineers presented their current progress on the app to their classmates. During this presentation, we provided three questions with which the software engineers could solicit informal feedback:

 1. Is there anything visually uncomfortable about the design (does anything look out of place)?
 2. What things have bothered you about other mobile apps that we should avoid?
 3. What are some additional features that you would like to see in the app?

The major research method from the second sprint was a cognitive walkthrough of our wireframe, conducted by two fellow Usability Engineering students. Each student acted as a user of the app and was tasked with fulfilling the goals in Darryl Wood's scenario, which required them to simulate creating an account, finding a course to play, and creating a scorecard by traversing a PDF copy of the wireframe. At each step of the process, the students were expected to describe their thought process and answer the following two questions:

 1. Will a user know what to do at this step?
 2. If the user does the right thing, will they know that they did the right thing and are making progress toward the goal?

## Findings

The informal feedback obtained by the Tee-Together software engineers was returned to us as a brief, aggregated list of suggestions rather than as answers to the three questions we provided. This is the feedback verbatim:

> default to 9 or 18 holes on the scorecard, option to choose how many holes the user plays, store scorecard to the database, too many notifications, sign in automatically, no ads, unnecessary steps, friend each other accounts (view stats on friends), integrate maps, one player can keep score of many in one scorecard, send scorecard to friends, daily leaderboards, less android-y UI

Here is the feedback again, reworded and reformatted to fit with the provided questions:

 1. Is there anything visually uncomfortable about the design (does anything look out of place)?
> *The app's aesthetic does not do enough to distinguish itself from default Android app themes.*
 2. What things have bothered you about other mobile apps that we should avoid?
> *Avoid subjecting users to superfluous tasks, excessive notifications, or advertisements of any form. Users should not be logged out every time the app is closed.*
 3. What are some additional features that you would like to see in the app?
> *Allow users to participate in daily leaderboards, view maps of golf courses, view other user profiles, become friends with other users, and send scorecards to friends. When creating the scorecard, include default course length options (ideally, 9 and 18-hole courses) and allow multiple players on the same scorecard. Scorecards should be stored remotely, allowing users to access their scorecards on multiple devices with a single account.*

For the cognitive walkthrough, our two users were able to successfully navigate to the Scorecard Creation and Courses pages, meaning that the two questions were answered with "yes" at every step. We had considered these pages to be the goals of Daryll Wood’s scenario. However, the first draft of the wireframe lacked the proper screens to transition to after a course had been selected, or a scorecard had been created. The users, unsure of where to go after having created a scorecard or selected a course, answered "no" to the two questions and moved on to the next page of the wireframe PDF. In both cases, this movement was not a correct flow through the app, which only caused further confusion. One user also made a complaint about the ambiguity of the “Handle” field in the Create Account section and the “72” icon in the bottom navbar. The user encouraged us to explain these icons somewhere within the app or rework them to be more recognizable.

## Conclusions
The informal feedback provided by the Software Engineering students offered plenty of suggestions for features to be added or avoided, but only provided one broad criticism of the app's visual design: in its current form, it is too conventional. In the interest of keeping the user experience simple and efficient, we plan to stay the course and keep the layout conventional for our MVP. Ideally, our app will begin to stand out more as we and the software engineers incorporate other elements of the visual design not covered by the wireframe. Of the features suggested, most are already planned for the minimum viable product but have not been implemented yet. Daily leaderboards and course maps are the two notable exceptions to this, as these are considered to be post-MVP additions.

From the two cognitive walkthroughs we received, it is clear that our first wireframes came close but did not fully realize the goals defined in the scenario of our persona, Daryll Wood. Several screens have since been added to accommodate all three of our existing scenarios. This includes a Scorecard Editing page and Course Details page which finally resolve Daryll's scenario, as well as an Events and Event Details page to resolve Barrett Green's scenario. Clint Wedge's scenario is also resolved by the Course Details page, which contains a section on course accessibility information.

To address the complaints about the “Handle” field and the “72” icon, we decided to add clarfying captions to the Create Account input fields and redid the Icons in our homepage navigation bar. "Handle" is a term borrowed from other social media sites like X (formerly known as Twitter) and Instagram, denoting a unique account identifier starting with the @ symbol (for example, @teetogether). To clarify this, a brief text snippet explaining the purpose of the handle has been placed below the Handle input field in our updated wireframe. The "72" icon, which was originally meant to denote the Events section, was changed into a 5-point star with a superimposed golf club, to symbolically represent Events as "special golf". This symbol may be revised again down the line if further testing deems it an unfitting symbol.

## Caveats

While we are grateful to now have access to some user feedback, it is uncertain (and unlikely) that any of it has come from users within our target demographic.

Regarding the informal feedback, we do not know which software engineers we received feedback from, let alone their level of interest in golf. While we infer that the Software Engineering students are experienced enough with smartphones to use our app, they may be too experienced to provide meaningful feedback on usability. Due to their extra experience working with smartphone apps, likely with the same platform and foundational code as ours, they may already be familiar with commonly used poor design conventions that average Tee-Together users would not understand and mistake their specific understanding of the convention for general recognizability.

The cognitive walkthroughs received from our peers may have had different results if performed under different circumstances. For example, if the users had viewed the wireframes as they appear in Adobe XD, rather than as an ordered set of PDF pages, they might have been more likely to recognize when they had reached the end of the navigation flow, rather than erroneously moving to the "next page". It is also important to note that walkthroughs are moreuseful when done iteratively; here, they were performed for a single use case on a single version of the application. 
