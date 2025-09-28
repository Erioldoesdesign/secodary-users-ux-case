# secondary-users-ux-case

# Ideas & problem statement

How might we improve the experience for secodary users?

What does 'improve' mean to both secondary users and primary users and/or do they have the same/similar goals/needs?


# User research needs

What designer needs to know/understand better to address basic secondary user level behaviours.

1. On average, how many primary users are there vs secondary users? How many secondary users are their typically across a significant sized smart home?
    1a. Are secondary users typically residents in a smart home or temporary vistors? 
    1b. What are temporary vistors needs (if any aka short term let properties aka airbnb's etc.)?
2. What are the common needs for secondary users re. what devices/functions they need to edit?
3. What are the worries/concerns that secondary users (who are of legal adult consent age) have about access/data/tracking etc?
4. How do users balance and/or describe the power of information/convinience vs. their privacy and safety from other people on the smart home network.
5. How would a primary user describe a secondary users needs and access vs. a secondary users?
6. What devices do secondary users primarily interact with home settings on? (likely a mobile device for kids/young people and also adults not doing primary work/life tasks on a laptop/desktop).
7. How and in what tools do primary and secondary users typically communicate about devices?
8. What are the common 'fail safe' proceedures in households across legal/standards policies? e.g. in the UK smart lights can always be turned on/off via the light switch as well as the smart device controls. 

# Planning the work

## Understanding the problem described & ideas: #1

### Onboarding, Tutorials, requesting access and permission levels

To me, it seems like a critical function for secondary users is **informed consent** when accessing, modifying and being monitored/recognised by a smart device/tracked metric for the home. This connects to **permissions** levels for people/user types (inclusive of the process for primary users to configure these user types e.g. Admin, resident, guest etc.) as well as any essential **onboarding or tutorials** for existing, complex or newly added devices to the home ecosystem by the primary user (assumed 'for' the secondary users).

A system of **learning** before accessing a potentially **risky or destructive** home device is preferable to **completly restricting access via permissions**. We don't want to encourage or give the impression of a controlled, dictated environment in the home either for residents and/or guests (secondary users). A default selectable process of learning could be configured for devices that are popular and/or be **templated** as to what level of destructive/risky the device is considered to be by the primary user.

Additional improvements or adaptions to access and permisson levels can be user profiles that **time out** or only have access for an **alloted amount of time** as defined by the primary users and/or a secondary user can request additional timed access to devices.

Additionally, there could be **notifications** for primary users when a certain threshold is exceeded on a device or a certain change is made on a home connected device that then sends a notification request to the primary user before activating. A risk here is many notifications for a primary user.


# Steps to take a specific solution

*What area of the product requires the most attention regarding this problem? And why? Make a design (maximum 10 screens) to convince your fellow PM and engineers to focus on this area.*

## 30 days

**The improvement to make in 30 days**

1. Designs for hierarchy layouts for primary users to configure (visible by both primary and secondary users) and ways for primary users to define levels of risky/destructive actions by secondary users at a device level. 
2. Design to incorporate good accessibility rules aka not just defining the hierarchy by colours and/or opacity (greyed out) areas but including heading sizes, sections that take up more/less area, button states, informative contextual text etc. (example text: thesedevices have been designated/labbelled as risky to change. Please change with caution or refer to the person who set up the smart home devices for guidance) 
3. Visuals for what a secondary user can see as a hierarchy of actions on devices in a home ecosystem. 
4. Function for primary users to define access levels for different kinds of secondary users. e.g. a guest has access to change/adapt TV, Lights etc. Does not have access to change/view security cameras, motion sensors, locks can request access to kitchen appliances.
5. Mobile mode visuals for both primary and secondary users for the above functions.
6. Simple tutorial templates for most common device types (likely lights, cameras, motion sensors)
7. User testing this function in differing levels of complexity households e.g. house hold with minimal devices, household with maximum devices, household with 2 people, household with many people, household that is a short-term rental, household with people with access needs like elderyly or disabled people.
8. Adapt and iterate based on the user testing feedback via a [RITE process](https://en.wikipedia.org/wiki/RITE_Method)


## 60 days

**The improvement to make in 60 days**

1. Prioritise findings from user testing as improvement tickets that were not able to be covered under the RITE process.
2. Improvements to access levels and onboarding steps to help secondary users learn critical functions of destructive/risky device changes and actions.
3. Nuanced access levels and permissions that can be configured by the primary user and requested by the secondary user. e.g. A primary user can configure that a secondary user might only have access to TV and media during certain hours (imagine an underage/child that has agree to not have TV/Device time at certain times of the day on the network so they can concentrate on homework/school work, though this specific config can be done at the device settingl). They can request access to the primary user with a short text of the circumstance that appears as a request/notification.
4. Wider rollout for less common device patterns for tutorials and templates.
5. User testing additional/improved functions in differing levels of complexity households. Possibly implement bugzilla like in system reporting.


## 90 days

**The improvement to make in 90 days**

1. Prioritise findings from user testing as improvement tickets that were not able to be covered. Continually improve, test/assess and iterate on feature every half year.
2. More complex functions (if needed) e.g.: Recovery mode for destructive/risky actions for primary users to set an automatic 'revert' mode should a device be changed according to some rules that a primary user dictate not be broken. With this, allow a secondary user to view a warning or messaging that informs then that this limit has been set and what will happen should they try to edit/change the device function. This Shouldn't stop the secondary user from performing the function, but offer options like 'Message that states the timer that this edit will be on e.g. 60 seconds' with buttons [do anyway] [request device setting change] [go back]. The setting change request can be requested for different intervals of time with written reasoning. Emergency situations should be able to be covered in these circumstances.
3. A general emergency mode that can be toggled on/off by all users but is 1-2 clicks away from a main dashboard. An emergency mode will allow changes by any user to any device. Circumstances for use might be if there is a fire or other home emergency or if a disabled or elderly person has an accident and an emergency team need to intevene. 
4. Continued improvements to features like notifications, onboarding, tutorials and learning for secondary users via user testing but also a longer term study could be done via survey information or 'check ins' over the 90 day period to see how needs change.
5. Simulation of crisis or emergency events and/or 'war gaming' any extreme situations that mean features could cause extreme harm to any users.


----


## Understanding the problem described & ideas: #2

### Incognito modes and privacy respecting for secondary users inclusive of ways to collect evidence

# Steps to take a specific solution

## 30 days

**The improvement to make in 30 days**

## 60 days

**The improvement to make in 60 days**

## 90 days

**The improvement to make in 90 days**

----

## Understanding the problem described & ideas: #2

### Chat function about device and/or a history of use and changes to a device

# Steps to take a specific solution

## 30 days

**The improvement to make in 30 days**

## 60 days

**The improvement to make in 60 days**

## 90 days

**The improvement to make in 90 days**

----

## Understanding the problem described & ideas: #2

### Alerts for anomalous activity

# Steps to take a specific solution

## 30 days

**The improvement to make in 30 days**

## 60 days

**The improvement to make in 60 days**

## 90 days

**The improvement to make in 90 days**
