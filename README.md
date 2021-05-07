# Scripts for working with data related to OHBM 2021  

_If you would like to **add or modify events** for OHBM 2021, instructions for preparing the necessary information is at the bottom of this page._ 

**Getting started:** In addition to the enclosed scripts, you'll need to create a `.env` file with:  
  1. your login credentials for Firebase  
  2. api information for Attendee Interactive  
  3. location of the Sparkle `scripts` directory  

See the `.env.sample` for the required information.


# Generating abstract book  


# Schedule


### Optimizing scheduling  

### Generating schedule files  

### Assigning posters to categories for stand-by times  

#### Generating individual poster events  

### Sharing the schedule  



## Importing OHBM content to Sparkle conference platform  


### Creating events from schedule  


### Creating poster pages  


### Creating poster events  


# Adding events to OHBM  

**Adding event/s:** To add events to sparkle, simply create a `.csv` file with one event per row that includes the following comma-delimited fields:  


| Title | Speaker | Moderator | Date Start | Time Start | Date End | Time End | Location | TimeZoneBlock | Categories |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  "Example Title", | "Jane Doe", | , | 20210622, | 140000, | 20210622, | 150000, | mainauditorium | AmericasEurope | keynote | 

_If you prefer to make this file in excel, simply export the file as `.csv`_

**Tips:**  
- If the field has multiple words, place quotes around it.  
- If a specific field isn't necessary for your event, leave it blank by placing a `comma`  
- `Moderator` can refer to a person that is moderating and/or an organization that is organizing. If some cases this can be used to describe content of the event. 
- Dates are specified in UTC as `YYYYMMDD`
- Times are specified in UTC as `HHMMSS`  
- `Location` refers to the venue name in Sparkle. If you don't know at this stage, simply write `TBD` and we'll sort that out on our end. This is updated regularly, though current options include: ['mainauditorium', 'symposiumhall1', 'symposiumhall2','symposiumhall3' 'symposiumhall4', 'posterhall', 'lounge', 'opendiscussion', 'exhibithall']
- `TimeZoneBlock` options are: `AmericasEurope`, `AmericasAsia`, `EuropeAsia`  
- `Categories` refers to the program category, and currently includes the following options: ['Talairach', 'Keynote', 'Symposium', 'Poster Highlights', 'Posters', 'Sponsored Symposia', 'Social', 'Announcements', 'Roundtables', 'Exhibitors Hour']

_If you have any specific needs that aren't met by these fields, please get in touch to discussion options._ 

**Modifying existing events:** 

If you find any errors in the schedule, please let us know and we'll get them fixed as soon as possible.  

# Adding rooms/venues to Sparkle  

To add new rooms/venues, best to send along a `.csv` spreadsheet with the following information:

- Template type
- Name
- Link 
- 

# Adding poster and video content to Sparkle  

Same procedure as above, but the `.cvs` files should contain:

- Title 
- Author name
- URL of poster
- URL of thumbnail
- List of categories
- Poster ID number, if already assigned elsewhere
