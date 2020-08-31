---
permalink: job-announcement-playbook/details/this-job-is-open-to/
layout: joa-details
category: this-job-is-open-to
title: This job is open to
sidenav: this-job-is-open-to
lead: This section gives an "at-a-glance" view of who the job is open to.
---
<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__required-by-usajobs">
  <h4>Required by USAJOBS</h4>
  <p>Yes</p>
</div>
<div class="usajobs-recruitment-joa-playbook-details__required-by-policy">
  <h4>Required by Policy</h4>
  <p>Yes</p>
</div>
</div>

**How to update the "This job is open to" section**

There are two ways to populate this section:
1. Using the multi-select hiring path list in your TAS. If your agency TAS has updated their system to use the multi-select, this will be your only option to add a hiring path to your job announcement.  The hiring path icons and their text descriptions will appear in the “This job is open to” section based on the options you select.
2. Using the text in the [Who May Apply](../duties#who-may-apply) section. If your agency TAS has not updated their system to use the multi-select hiring path list, you will continue to use the **Who May Apply** section. The hiring path icons and their text descriptions will appear in the “This job is open to” section based on the text that is in **Who May Apply**.

**Mapping Who May Apply to the hiring paths**

The table below shows the content you need to use in the Who May Apply section to display the matching hiring path. For example, if you want your job announcement to display “Open to the public”, you must enter “U.S. Citizens” in the Who May Apply field. Or, we'll also display "Open to the public", if you don't enter anything in the Who May Apply field.

{: .usajobs-recruitment-joa-playbook-details__table}
| Hiring Path                   | Who May Apply content |
| ----------------------------- | --------------------- |
| Open to the public | U.S. Citizens |
| Federal employees - Competitive service| Federal Employees, Current Federal Employees, Merit Promotion, Status Candidates |
| Federal employees - Excepted service| Excepted Service |
| Internal to an agency| Internal Employee, Agency Employee |
| Career transition (CTAP, ICTAP, RPL) | CTAP, Career Transition Assistance Program, ICTAP, Interagency Career Transition Assistance Program, Reemployment Priority List, RPL |
| Veterans | Expanded Veteran Hiring Opportunity,  EVHO, Veterans Recruitment, VRA, VEOA, Veterans Employment Opportunity Act, 30% Disabled |
| Students | Students, Current Intern |
| Recent graduates | Recent Graduate |
| Individuals with disabilities | Schedule A, Individuals with Disabilities |
| Military spouses | Military Spouse |
| National Guard & Reserves | National Guard |
| Native Americans | Indian Preference, Native American |
| Land and base management | Land Management, Base Management |
| Peace Corps & AmeriCorps Vista | Peace Corps, AmeriCorps, Vista |
| Senior Executives | Determined by ES pay plan and minimum salary of $119,000|
| Family of overseas employees | Overseas, Family Member Preference, Eligible Family Member |

### Clarification from agency
Use this section for additional eligibility information.

**Example**
If you only want to hire from within a specific department, you would select the **Internal to an agency** hiring path and use the **Clarification from agency** section to indicate the job is open to department employees only.  

<div class="usajobs-recruitment-joa-playbook-details__container">
<div class="usajobs-recruitment-joa-playbook-details__required-by-usajobs">
  <h4>Required by USAJOBS</h4>
  <p>Conditional. If you use an exclusive hiring path or special authority, you need to include clarification text.</p>
</div>
<div class="usajobs-recruitment-joa-playbook-details__required-by-policy">
  <h4>Required by Policy</h4>
  <p>No.</p>
</div>
</div>

**Questions about the hiring paths?**

If you don't understand why a job announcement is being assigned a hiring path based on the text you provide then you and your Talent Acquisition System (TAS) vendor can use the [full list of valid and invalid text for hiring paths](https://developer.usajobs.gov/General/Hiring-Paths) (production) located on our developer site ([UAT](https://developer.uat.usajobs.gov/General/Hiring-Paths)).

**NOTE:** We have established our hiring paths as an enumerated list that your Talent Acquisition System (TAS) vendor can use in the future to allow you to select valid options without having to supply the text. The two fields are named "Hiring Path Code" and "Hiring Path Explanation" in our [Data Dictionary](https://developer.usajobs.gov/General/Schemas). Talk to your vendor about this feature. We strongly encourage agencies to switch to using these new fields. String parsing is a temporary solution that allows us to transition to a more structured way of providing and presenting this information to job seekers.

#### Example

This example shows all of the possible hiring paths. No single job would feature all of these.

<div class="usajobs-recruitment-joa-playbook-details__example-img this-job-is-open-to">
<amp-img src="{{ '/assets/images/job-announcement-playbook/this-job-is-open-to-v7.1.png' | relative_url }}"
  srcset="{{ '/assets/images/job-announcement-playbook/this-job-is-open-to-v7.1.png' | relative_url }} 768w,
  {{ '/assets/images/job-announcement-playbook/this-job-is-open-to-v7.1-SM.png' | relative_url }} 100w"
  width="320"
  height="1907"
  layout="responsive"
  alt="This job is open to... v7.1 example"></amp-img>
</div>


### Second announcement

Use this section when the job is also open in a second job announcement to other hiring paths.

The **Second announcement** section will appear directly below the **This job is open to**.  The **Second announcement** says "This job is also open in another announcement to" and will list the other hiring paths.

Clicking on the link will open a new tab or window, depending on the preference the user set in their browser, with the the full second job announcement.

**NOTE:** This is a new field and may not yet be offered by your Talent Acquisition System (TAS). Work with your vendor in order to be able to use this field.
