# Yet Another Portfolio - YAP
Team Members: Celeste Gambardella, Brandon Chu, Cole Bielchfield, Dylan Gray, Brendan Grau

## Project Structure
The team primarly used html, css, js, and bootstrap to construct our beta prototype. As for the structure of our application we decided to focus on the ease of use for our users. Which heavily relied on labeling and taking our color choices into consideration when developing. Our main tasks focus no the artists perspective from the application on the following pages:

- homepage.html
- customization.html
- feedback.html
- search.html

## System Concept

YAP (Yet Another Portfolio) is for artists/creators, contractors/employers, and the public. This will allow creators to post their content so that other people including potential employers can view and interact with it. Users will have the ability to like, comment, and commission future and existing work. YAP will connect creators with potential customers be that on a commission basis or for employment purposes. YAP will provide a minimal set of customization options for portfolios, with the main focus being a timeline of projects the creator posts, with interaction options next. YAP will enable users to connect and network with other users and potential employers/contractors. The users will be able to update current projects they are working on overtime. Others will be able to like, comment, and reply to an individual's portfolio post. This will allow people to connect and find others to work for potential employment opportunities.

## Workflow Diagram
![Workflow](/Users/celestegambardella/OneDrive - rit.edu/SWEN 444/Project Info/Code/YAP/src/media/Workflow.png)

The workflow diagram above shows how our various user roles interact with each other. The system consists of our YAP Database and our YAP Web interface. Artists can publish their work on the site so other artists, general users, and employers can view and interact with them. Employers can contact artists to initiate employment negotiations. 

##Affinity Diagram

![Workflow](/Users/celestegambardella/OneDrive - rit.edu/SWEN 444/Project Info/Code/YAP/src/media/WAAD.png)

The WAAD Diagram above was an interesting experience for the team. As expected, we had a few overlapping activity notes that we needed to synthesize into one note. From our work activity notes, we were able to come up with the 5 categories above: Competitors, Employer Artists Interaction, Presentation, Feedback, and Customization. These categories allow us to divide up our requirements and make sure that we are satisfying all aspects of our system. 
## Purpose of Usability Evaluation
The purpose of a usability evaluation of the YAP is to predict the expected performance of the actual customer using the current product and materials, as well as detect any serious problems prior to the release of the product. The features that will be tested through the usability evaluation process are: 
- The automatic submission of portfolios and resume to the options that allow it.
- Searching YAP for employment options 
- The ability to control the feedback on your own posts.
- The ability of artists to customize their portfolios.
- The ability of artists to post new artworks to their portfolio.

## Usability Goals
- Artists will be able to customize their portfolios with a minimum of five colors.
- Artists will be able to customize their portfolios with a minimum of three fonts.
- 90% of users will be able to find and click on an artists portfolio page within 20 seconds.
- 95% of users will be satisfied with their experience with YAP and have a 70% return rate.
- Users will learn and be able to add complex comments to a post within 60 seconds.
- Users will be able to submit their portfolio using ‘Quick Apply’ to an employer within 10 seconds.
- Users will learn how to search for other artists using the different filters within 5 seconds without any assistance.


## Social Model
![Social Diagram](/Users/celestegambardella/OneDrive - rit.edu/SWEN 444/Project Info/Code/YAP/src/media/SocialDiagram.png)

A system social model diagram that shows the major system nodes and the interactions between them.

## Sample Persona
### Artist
#### Background
	Age: 21
	Occupation: Undergraduate art student
	School: Rochester Institute of Technology, 
	Technology level: Average tech literacy.
#### Attributes
	Third-year art student
	Highly creative
	Comfortable with many artistic mediums.
	Eager to learn new skills and techniques.
	Spends most free time creating art.

#### Goals
	Find employment opportunities
	Tell their story through art
	Connect with like-minded artists
	Find inspiration for their work

## Interface Rational
### Homepage & Navigation Bar
The homepage was intended to be a sort of brief showcase of every profile, with links to a wide variety of content to advertise users, much like an art gallery. We afforded users the ability to know who created each work by separating them by name, and how to use it cognitively by making use of the scrollbars in either direction when necessary, that would be noticed in a desktop browser, or intuitively scrollable on a touch screen. The navigation bar is a common and simple directory of different places users can expect to want to go to and is hence present on every page. Either back to the homepage by clicking on the “YAP” logo, searching portfolios by clicking on the spyglass icon, a commonly-afforded symbol of searching, or going to the employment page (should you be an artist looking for work). There is also a login/account option we opted to put on the navigation bar for quick access, which could be from anywhere.

### Employment Search
For the Employment Search designs, we wanted to focus on ease of use for our users. We used cognitive affordances by carefully labeling buttons and navigation to help the user navigate. For the “Quick Apply” (lightning bolt), something that may not be extremely intuitive, instructions are labeled when a job opportunity card is clicked. Also, the quick apply button is the same color to help them make the association with the lightning bolt. For error prevention, we decided to make job opportunities in a card popup style instead of renavigating the user to a separate job description page. This would reduce the time it would take to navigate back if the user accidentally clicked on the wrong job opportunity.

### Artist Customization
In regards to the artist's customization, we are hoping to minimize the number of clicks and amount of time an artist would have to take to customize their portfolio. In doing so we have edit icons for each of the subtasks on the artists’ portfolio page. We used cognitive affordances by using universal symbols of edit, setting, and info icons. This way the artist will know what options they have just by looking at the page with meaningful labels to help artists if they might be confused with what something might mean. The icons we use also act as a physical affordance as well. By prior experience artists have on other websites we stuck closely to the universal symbols on the customization page. Also, have the general location of the save button is at the bottom of the screen or popup screen lets users know they can click the button. The functional affordance of the dropdown menus explaining what the information adds more functionality behind the idea of the dropdown or have the button be labeled save. The idea we had behind having pop-ups for all the different edit options lets the artists stay on the current page and not have to be redirected onto other pages. While also being able to easily access certain parts of their portfolio to customize quickly.

### Feedback Control
For the feedback control, we wanted an easy way to switch between artworks in chronological order since most use of this feature will be with artworks that were recently published. To do this, we went with arrows to switch between artworks and a small display so that the user could tell what artwork they would be moving to. In terms of the actual functionality of the feature, the ellipsis was chosen to open a menu next to any comment as it is a commonly recognized means of doing this on many other systems. The menu will be displayed as close to the comment as possible to clearly remind the user what comment they are modifying.

### Art Submission
For the art submission, we wanted to help guild the user through the process, to minimize any error, by breaking it down into two distinct steps. First users must choose the file they wish to upload. The drag and drop option gives a physical affordance, allowing the user to drag the file, rather than navigate through files to select it. The labels and order of the options are meant to supply multiple cognitive affordances. Clear labels for each option, followed by the instructions for that method only help the user to quickly understand what to do. Additionally, the options are ordered to help the user. The spot to drop is bigger than the other option and requires a different interaction, as such, it is the top-most option with a unique label on it. Below are the options for navigating to a file on the computer or drive, in that order. The local file is first so that it is closer to the drop option, a similar option.  The two are grouped together as they accomplish the same thing in different places. Finally, the spot to insert a URL is at the bottom and is white to indicate to the user that it is a text file and not a button. 

Once a file is selected the user is able to start on the second step, filling out all the information for the art. Again the layout of this screen aims to help the user understand and interact with it as efficiently as possible. The title, description, and search tags are all large text fields, grouped together and colored white to indicate they require text input. The next option down is the medium drop down, the last of the required fields. The use of a drop-down saves the user from worrying if they are putting in a bad option. The start date and end date will only allow the user to input three 2 digit numbers to prevent them from putting in the wrong date. To the right are checkboxes to enable comments and rating, making their state clear to the user. After this users can verify they have their correct art, can submit their art, only after they agree to the ToS. Once submitted they receive a popup giving a sensory affordance by informing them that it was successful. Their only option at this point is to finish the submission process by returning to their profile, or using one of the navigation buttons at the top.
