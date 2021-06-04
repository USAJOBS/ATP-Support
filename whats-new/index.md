---
permalink: what-is-new/
layout: article
section: what-is-new
category: what-is-new
sidenav: what-is-new
title: What's new with ATP
---

## Changes made May 28. 2021
### Sitewide enhancements
#### Campaigns

* Removed the **(+)** to add team members to a campaign and added the **Team Member** tab. Within this tab, the user can see all team members who are part of a campaign and add new team members.
* Added a character count to the **Campaign title** field.
* Added validation messages for minimum and maximum required characters to the Campaign title field.
* Updated the **Desired location display** to:
  * Only show city and state. For example, “Arlington, Virginia” instead of “Arlington, Virginia, United States”. 
  * Only show the state when a user selects all of the cities in a state. For example, “Indiana”, instead of “All Indiana”. 
  * Only show United States when a user selects every state within the United States. For example, “United States” instead of “All United States”.
  * Show **All** for a country when a user selects a country outside of the United States. For example, “All Germany” instead of “All, All, Germany”.

* Updated the display of the candidate card to wrap long candidate names.
* Updated the following modals to meet USDWS standards:
  * When a user clicks **Delete list** in an active campaign.
  * When a user clicks **Remove access** within a user’s page in the Manage users section.

* Updated the user flow for **Add to campaign**—the user will be sent to the candidate’s profile page on the candidate tab.
* Removed the **Back to campaign** link when a user is in a candidate’s profile.
* Locked the tabs in **Active** and **Inactive campaigns** when a user has multiple lists that require a horizontal scroll bar. This keeps the tabs visible throughout the user experience.
#### Events

* Updated field validation in the **Associated job announcement(s)** field to check for a valid JOA control number.
* Updated field validation for the **Event name** to check it is between 10 and 70 characters.

#### Search resumes

* Added yellow highlights to keywords in a PDF version of a resume.
* Sectioned resumes into 3 equal parts and weighted those parts for a more accurate search result.

#### My Account and authentication

* Added a new optional field **I want to use ATP because I’m a** with the following responses: Recruiter, HR Specialist, Hiring Manger. This will help us better understand our users and will help us make improvements to the site. This will also appear on the revised **Complete your account information page**.
* Renamed the Required details page to **Complete your account information**.
* Removed the subtext “Please provide the following information in order to access your Agency Talent Portal account”. 


## Changes made May 14, 2021
### Sitewide enhancements
#### Events

* Increased font size to 16px for the **Event description**.
* Revised the validation text to be consistent and clear on the **Event description** and **Event logistics** page. 
* Added text wrapping, so long descriptions and overflow text do not display beyond the given space.
* Updated the look and feel of the event modals to meet USDWS standards.

#### Campaigns

* Updated the agency table and implemented new access restrictions for agencies.
  * Department Administrators will now see all agencies under the department. Example: DoD will now see all children and grandchildren relationships (AF- 11th wing). Air Force will now see all elements under them.

* Updated the look and feel of the candidate profile page within search and campaigns:
  * Removed search boxes.
  * Moved **candidate name**, **location** and **last updated** information to the top of the page—this makes it easier for the HR user to see candidate information as they navigate to different tabs.

* Updated the minimum and maximum character field validation for renaming a campaign.
* Added text wrapping for long campaign names.
* Added validation text in the **Add job announcement** modal.

#### Search

* Updated the display to only show 10,000 search results. Anything over 10,000 results will display as 10,000+ (1 of 10,000+ results).
* Fixed multiple 508 issues.


## Changes made April 30, 2021
### Sitewide enhancements

* Added a **Join the ATP Listserv** call-out and link on the home page.
* Updated the **candidate profile within search** to use a tab design and layout—this now matches what the user sees on a candidate profile within a campaign.
* Updated the **Job announcement** modal and **Remove campaign** modal to use the U.S. Web Design Web System standards.

### Bug fixes

* Fixed a bug prohibiting the **We no longer support Internet Explorer** banner from displaying. The banner now displays when a user is using Internet Explorer to access ATP. 

## Changes made April 19, 2021

### Candidate profile and Campaigns

* Added tabs to the candidate profile: **Candidate** and **Campaigns**. The **Candidate** tab displays information about the candidate, including a resume. The **Campaign** tab includes a list of campaigns the candidate has been added to. 
* Updated the navigation and UI within the candidate profile.
* Added an **Activate** button to **Archived campaigns**, so a user can reactivate a campaign.
* Updated the ability to rename a campaign using the new USDWS modal design.
* Moved the **Export to excel** feature to the **Campaign** menu.
* Updated the link label **View** to **Download** for resumes in Word. Changing the label makes it clear the user has to download the document before they can view it.

### Other changes
* Removed old ATP feature toggles (this is a change on the back end).
* Updated the **Terms and Conditions** in both the right rail and the footer to comply with POAM.
* Updated multiple modals to the new USDWS modal design.
* Changed the display of the **Last updated date** and time to reflect the user local time zone.
* Made changes to support future release of a messaging feature.


## Changes made March 9, 2021
### Search enhancements

* Updated the **Series** filter to include parent and child series.
* Added the ability to add multiple **Series** for a search. 
* Separated **U.S. Citizen** from the **Hiring Path** filter and made its own filter. 

### Other enhancements

* Updated the look and feel for Location name. 
* Updated the look and feel for Preferences.
* Removed the Resume User role.
* Upgraded old General Users to a new General User role.

## Changes made February 19, 2021
### Campaign enhancements

* Added a drop-down menu in the individual candidate card to allow the user to move the candidate to another list when they are not able to use “drag and drop” functionality. 
* Updated the look and feel of both active and archived campaign boards.
* Updated the look and feel of the **List** menu – replaced Remove list with **Delete list**.

### Other enhancements

* Added a filter in **Search** for education level.
* Updated the look and feel of the **Event** creation process.


## Changes made February 5, 2021

### Campaign enhancements

* Redesigned the **Add list** feature to make it clear how to add a list to a campaign.
* Added a pop-over menu to a campaign so users can add a job announcement to their campaign.
* Added the ability to archive a campaign. 
* Created a **List** tab within a campaign and moved all lists under this tab.

### Search enhancements

* Highlighted the search terms in a resume builder resume.
* Added ability to search on state abbreviations (i.e. TX for Texas) when a user does not use the auto suggest (i.e. typed full state or copy and pasted) 
* Removed continents from the search suggestion list.
* Updated the instructions presented to the user when there are no search results.

### Other enhancements

* Added **My Account** to the drop down under the users name that will allow users to change their name and phone number.
* Updated the “hint text” in **Events** so it is more clear which field being used and updated the content clarify how to format URLs.
* Updated the modal styles for consistency.

## Changes made January 22, 2021
### Search enhancements

* Added the ability to filter by **Grade** (GS Scale only).
* Added the ability to filter by **Last Updated** (when a candidate edited/created/applied, etc) date.
* Updated text for **Clear All filters**.
* Removed the **Resume uploaded** date from the profile detail.
* Implemented stop words to refine the **Search** results.
* Added synonyms for state and territory abbreviations in **Search**.
* Moved the job title on **Builder resumes**.
* Updated the search tips on the **Search landing** page.
* Indexed additional fields in the **Profile**.

### Updates to Events

* Added fields for online location options and event types to the **Events** logistics page.

### Updates to Manage Users

* Added ability to export agency users to an Excel spreadsheet.
* Added ability for HelpDesk Users to edit profile fields.
* Added cancel button to manage user tasks.
* Updated the username sign in text to email.

### Changes to the user experience and user interface

* Updated the way **Events** display.
* Replaced job seeker with acndidate.
* Updated required and optional instructions for form fields.
* Updated the padding around the mass save banner
* Updated the wording on the **Search results** page.
* Updated the **Forgot password** label for email sign in.
* Updated the session expiration message.
* Updated the **Series** tag.
* Shortened the **Location** field on the card that displays for a candidate.
* Moved all hiring path icons to one line in cards.

## Changes made January 8, 2021
### Site-wide enhancements

* Upgraded Elasticsearch to 7.10.X.
* Added new search filters including:
  * Travel and relocation
  * Series
  * Work schedule
  
* Improved the Campaign experience.
* Made several user interface and user experience updates.


## Changes made December 11, 2020
### Site-wide enhancements

* Updated the **Add to Campaign** experience.
* Added the ability to save several candidates at one time to a campaign.
* Updated the search results **Sort by** to default to **Sort by relevance**.
* Updated the user interface and experience across the site.
* Updated the Profile details page.
* Fixed several bugs.

## Changes made November 16, 2020
### Site-wide enhancements

* Updated the entire site to meet the USWDS 2.0 Web Design standards.
* Fixed several bugs.

## Changes made September 18, 2020

### Site-wide enhancements

- Added ability for system administrators to update a user's name, email and agency.
- Fixed several bugs.
- Added a new category **Information Session** to the **Event Type** field.
- Updated the landing page.
- Updated the Help Center icon to link to the ATP Help Center.

## Changes made September 4, 2020

### Site-wide enhancements

- Updated the landing page.
- Displayed Role Permissions drive content.
- Created event coordinator invite user email template.
- Updated the URL for the help center icon on the landing page.
- Updated the **How to create ATP profile** text.

## Changes made August 21, 2020

### Site-wide enhancements

- Updated the **Events calendar**.
- Updated the **Event description** contact information field.
- Created a view to display all **Expired Events** list on the Events page.
- Created an **Event Coordinator** role.
- Moved the **Search Resume** filter to the right side of the page.
- Added a new filter option for **Status**.
- Enhanced the **Certificate registration** flow.
- Updated authentication methods.

  - Decoupled ATP from Seeker Portal.
  - Enhanced PIV authentication.
  - Enhanced UN/PW authentication.
  - Enabled SSO for USA Staffing users.

## Changes made August 7, 2020

### Site-wide enhancements

- Removed all ATP references from USAJOBS and Open Opportunities, because ATP will have its own authentication process (coming soon!).
- Enhanced Campaigns to require all campaigns to have at least 1 member assigned to it.
