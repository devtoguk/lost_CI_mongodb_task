# Adventure Awaits
![Tile Quake responsive view](docs/responsive-screenshot.jpg)

The live deployed site can be accessed using the following link: [Adventure Awaits](https://devtoguk.github.io/milestone-2-TILE-QUAKE/)

## Table of Contents
- [Summary](#summary)
- [Business Goals](#business-goals)
- [Customer Goals](#customer-goals)
- [Advertise Goals](#advertise-goals)
- [UX](#ux)
  * [Ideal Customer:](#ideal-customer-)
  * [Ideal Advertiser:](#ideal-advertiser-)
- [User Stories](#user-stories)
  * [Customer](#customer)
  * [Advertiser](#advertiser)
- [Wireframe Designs](#wireframe-designs)
- [Surface](#surface)
- [Technologies Used](#technologies-used)
- [Features](#features)
  * [Pages / screens](#pages---screens)
- [Future Features/Changes](#future-features-changes)
- [Testing](#testing)
- [Additional Notes](#additional-notes)
- [Deployment](#deployment)
  * [Running this project locally](#running-this-project-locally)
- [Credits](#credits)
  * [Text content](#text-content)
  * [Logo](#logo)
  * [Photos](#photos)
  * [Audio](#audio)
  * [Code](#code)
- [Acknowledgments](#acknowledgments)
- [Disclaimer](#disclaimer)

## Summary
The purpose of the ‘Adventutre Awaits’ project is to create a website which will
allow people to find activities to do. From small adventures in the garden, to big
adventures on days out.

## Business Goals

- Create an easy to use website which will keep users coming back time-after-time
with a growing database of activities.
- Allow users to submit their own activity ideas.
- Allow advertisers to have banners on the website to help generate revenue.

## Customer Goals
- Search for an activity to do.
- Easy to find the information so they can make an informed decision.
- Have the ability to submit an activity idea for the website.
- Be able to leave reviews of existing activities.

## Advertiser Goals
- The ability to have a banner on the website to attract potential cusomters to
their website.
- Access information about how many clicks my banner has received

## UX

### Ideal Customer:
- English speaking (UK based)
- Looking for an activity for themselves or the family.

### Ideal Advertiser:
- English speaking (UK based)
- Wants to adevertise their service/product on an activity based website.

## User Stories

### Customer
1. How do I search for an activity?
2. How can I submit my own idea for an activity to the database.
3. How do I leave a review of an activity.

### Advertiser
1. How do I get my banner on the website?
2. How can I find out how many clicks my banner has received.

## Information Architecture
### Database Choice
For this project I chose to use the NoSQL database, MongoDB.
This choice was based on....
Mention IDs used as foreign keys where relationships are required???
Also mention One-to-Many, one user can have many activities, etc

### Database Schema
The Adventure Awaits database has four collections: activities, users, reviews and advertisers.

#### Activities Collection
| Title    | Database key | Data Type | Notes |
| --- | ---- | --- | --- |
|ID | _id | ObjectId | Unique ObjectID identifier, generate by MongoDB |
|Title | title | String | Main title for the activity max length of 30 chars |
| Short Description | short_descr | String | max length of 200 chars
| Long Description | long_descr | String | --- |
| Location | location | int32 | set to either (0) for 'home' or (1) for 'out and about' |
| Age Range | age_range | int32 | set to lower end of the age range, so 5 will display as 5+ |
| Venue | venue | object | optional object to hold data about an 'out-and-about' venue |
|  | venue.title | String | venue property for the title of the venue |
|  | venue.addr1 | String | address line 1 |
|  | venue.addr2 | String | address line 2 |
|  | venue.town | String |  |
|  | venue.county | String |  |
|  | venue.postcode | String |  |
|  | venue.email | String |  |
|  | venue.telephone | String |  |
|  | venue.website | String |  |


## Wireframe Designs

Click the link below to view a PDF file containing all the wireframe screen designs for Desktop, Tablet & Mobile.

[Wireframe PDF](https://devtoguk.github.io/milestone-2-TILE-QUAKE/docs/wireframes.pdf)  (ctrl-click to open in a new tab)

## Surface
???????

## Technologies Used
- HTML
- CSS
- JavaScript
- Python v?????
- Flask micro-framework ????
- Bootstrap v?????
- [Google Fonts](https://fonts.google.com/) - for the website font 'Play'.
- [GitPod](https://www.gitpod.io/) - online IDE used to create this project.
- [Autoprefixer](https://autoprefixer.github.io/) - used to ensure the CSS code was valid for browsers which match (last 2 versions, > 5%)
- [Optimizilla](https://imagecompressor.com/) - used to compress JPEG/PNG content.

## Features
?????
### Pages / screens
???? Desktops, tablets and mobiles all display in the same format. ????

## Future Features/Changes
- ????
- ????
- ????

## Testing
For testing information please use the following link [TESTING.md](/TESTING.md)

## Additional Notes
????

## Deployment
The live project was deployed using Heroku, this was done using the procedure below:

The live site can now be accessed using the link below:

### Running this project locally
If you wish to work on / run this project locally then use the cloning procedure below:

Do we need this section? If so, what do we put???

## Credits

### Text content
Apart from character names all text content has been written by R.Thompson and proof read by E. Thompson.
All character names remain the property of their respective copyright owners.

### Logo
The logo image was created from scratch using Adobe Photoshop.
(the cracked Earth effect was cropped from an image by Micaela Parente on [Unsplash](https://unsplash.com/photos/UzTBnxFiSWE)

### Photos
?????
### Audio
?????

### Code
Thanks to the Stackoverflow and other communities & blogs for helping solve some issues/problems.
- ?????. [Stackoverflow thread](https://stackoverflow.com/questions/2450954/how-to-randomize-shuffle-a-javascript-array)

## Acknowledgments
The idea for this project came from the fact that we to are always looking for activity ideas
for the family.

A big thank you to my mentor, the Slack community and many great reference sites out there including Stackoverflow and W3Schools.

## Disclaimer
The content of this website is solely for educational purposes.