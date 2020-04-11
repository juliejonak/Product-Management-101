Imagine you are the PM working on an alarm clock app. Write a PRD for the initial version.

Frame the problem: Describe the opportunity. What are the benefits to the user? What are key insights? What does the competition do? Why does this matter?

What are the product goals: What does success look like? How do you measure success?

What should the product do? How should each feature be prioritized?

Include any other components that you think could be helpful.


-------------------

`Main goal:` alerts the user at a specific time

`Necessary Features:`
- Way to tell the time
- Way to set the specified time for alert
- Way to alert the user
- Way to turn off the alert

`Other Possible Features:`
- Set multiple alarm times
- Set scheduled alarms (by day/week for schedules)
- Have a timer/stopwatch
- Shows times in other timezones
- Updates to current timezone
- Connect to things user already interacts with (computer, phone, watch)
- Snooze button to delay alert -- or alternative that is scientifically more effective
- Engaged methods of waking up heavy sleepers (stand, puzzle, etc)
- Sense user's sleep state to wake them optimally out of REM
- Choose alert style (sound, light, radio, TV, diffuser/smell)
- Progressive alarms
- Connect to ambient devices (lights, coffee maker, tv, etc)
- Charges devices (plug in phone)
- Connects to internet
- Automatically handles daylight savings
- Ability to wake solely one user (i.e. one person by wireless headphones or watch, while other partner sleeps longer)
- Pro-active alerts about leaving/waking up earlier if delays getting to destination (traffic, road closure)
- Email/calendar integration to auto-set alarms for categories of events (work meetings, children's appointments, date night)
- Reduce anxiety around alarms
- Integrate wind-down or wake-up meditation, other routines
- Voice first setting and interaction
- Accessible settings for deafness, blindness or other needs
- Interconnected network of alarms for household to setup childrens' schedules (varied school and bed times)
- If app based, ensure the app works even if it's not actively running. Auto-whitelisted if battery saving apps on phone.
- White noise for sleeping, with gentle rousing (adjusts sounds/loudness gradually)
- Integrated weather forecast and other notifications relevant to that day's activities
- Add location awareness to adjust normal schedule if user deviates (i.e. vacation, work trip)
- Enforce kids' schedules with time based wifi access, lights, etc.
- Sleep graphs and statistics to evaluate user's sleep cycle and improve quality of sleep, using accelerometer or device
- Reduced battery consumption features


<br>

`Opportunities:` The existing alarm clock market is full of competitors, from basic and cheap varieties to built-in free ones on existing household devices, like TVs, phones, computers and voice-first devices.

To differentiate, there are two possible paths:

1. Build a more integrated product that simplifies decision making and alarm setting across a variety of functions - home life, work, and optimized sleep schedule.

2. Build an alarm clock that serves a specific niche, either focused on accessibility (deaf and/or blind customers) or families (syncing schedules across multiple people).

By creating extensions that include accessibility options, like flashing lights or vibration add-ons, we could design a synced schedules alarm clock that can be modified for many people.

If we focus on families juggling a busy work schedule and handling kids' extracurriculars, we can gear the product towards a niche market that would pay for the convenience of integrated solutions that help solve schedule problems across different aspects of their life.

<br>

## Interesting Research Points

### Wake-up styles

- `Walk Me Up!` is an iOS app that only turns off the alarm when the user gets up and walks around. There is no snooze, mute or pause. `SpinMe` similarly requires the user to spin around to turn it off.

- `Alarmy` is an iOS and Android app that only turns off when you get up and take a photo of something specific (toothbrush, shower head, coffee pot). `I Can't Wake Up!` gives small chores or cognitive tasks (math, memory tests, word pairs) or barcode scanning to ensure you're awake.

- `Wakie` is an iOS and Android app that provides wake-up calls from real people instead of an alarm clock. Calls are made through the app to preserve privacy.

`Conclusion:` some users prefer or need a more aggressive style of waking up -- but not all. Allows users to indicate their preferred method of being woken up, so anxiety affected users can have more calming methods, while heavy sleepers can use more effective methods.

<br>

### Device integration

- Alexa allows light bulb and other wifi appliance integration into Routines, to auto-run a series of events at specific times. I.e. Lights dim over 10 minutes leading up to your pre-set bedtime on weekdays; coffee maker begins when you wake up on work mornings.

Downside: currently the calendar treats Fridays as weekdays (bad for evening routines) and Sunday nights as weekends. This makes automating a work-specific schedule difficult.

Downside: setting up the routnies can take a long time/be difficult to test. When wifi is interfered with, resetting routines can take time or have to be setup all over again.

`Conclusion:` integration with household devices is effective and can eliminate manual repetitive processes -- but must account for varied schedules alongside "standard" work week schedules. Alarm needs to make onboarding new products into existing or new routines very simple, with plans for how to handle "offline" issues when wifi or electricity goes down, and re-onboarding the devices when power/internet connection is restored without the user manually being involved.

<br>

### Schedule integration

- `Reminder with Alarm`, an Android app, auto-syncs with Google calendar to provide the user with timely alarms for deadlines, meetings, homework, birthdays, errands, bills, medication and more. (https://play.google.com/store/apps/details?id=com.arthurivanets.reminder)

<br>

### Accessibility

- Visual schedules (with icons depicting the activity to do) provide a clearly, predictable schedule that reduces stress and anxiety, particularly in individuals affected by Autism, Asperger, ADHD, dementia, and other intellectual disabilities. Competitor: [Autiplan](https://autiplan.com)

- [Vibrating bed shakers](https://www.maxiaids.com/alarm-clocks) and other integrations enable those with hearing-related issues to benefit from alarms

- Olfactory alarm clocks (like Sensorwake) use scents to wake individuals, with familiar scents like coffee, peppermint, and more.

- `Smartshaker 2` is a portable, travel-sized pod placed under a pillwo to wake users with vibration. Helps wake a single person without interrupting their partner's sleep, or those with visual/hearing impairments, or tactile geared children.

- Alexa and other voice-enabled apps allow for voice-first interactions, so visually impaired individuals can set alarms easily

- `Ok to Wake!` is a light-driven alarm clock geared to tell children when they are okay to wake up. The alarm clock glows green when it's time to wake up. Children know to go back to sleep or play in their room until the alarm clock turns green, enabling parents to more easily maximize their sleep schedule. Good for users who are not yet able to read or interpret a clock.

- Sunrise simulation clocks help individuals who dislike early mornings or have anxiety, slowly wake up through gradual light displays.

`Conclusion:` utilizing lights, sounds and vibrations can make for a more soothing and inclusive alarm system.


<br>
<br>

--------------------------------

Alarm clocks already have extensive competition in the marketplace, from cheap standard clocks to elaborate device-app integrations.

To stand out from existing solutions, an unmet need is automated alarm scheduling across multiple individuals, to more cohesively plan work and personal life priorities.

Currently, there is no all-in-one solution that combines alarm clock functionality with calendar integration, multiple users (with varied permissions) and home-device integration to set daily or weekly routines.

The primary user is a working professional parent who has to oversee a busy work and personal life schedule that includes another partner and/or children with extracurricular activities. By reducing their mental and manual overhead on routine actions, we can provide more structure and peace of mind to the user's life.

While competitor apps and products include one or two of these features, there is not a competitor combining them into one space. Instead of building the hardware to support this application, we can leverage existing products such as Apple Watch, Alexa, wifi enabled home devices, and Google Calendar.

----------

The products goals are to:

- Keep track of time
- Alert the user to specified times
- Set and turn off alerts
- Provide customization options for users, based on if they need soothing or aggressive alerts
- Integrate with existing devices and calendar to automate alerts based on schedule, weather, traffic, and meetings/activities
- Reduce planning overhead
- Integrate multiple users' schedules seamlessly
- Allow management of childrens' devices and schedules
- Incorporate methods for improving sleep, by tracking sleep cycle, providing sleep help (sounds, meditation) and integrating with existing sleep apps/devices already used

Success would look like:
- High user ratings
- User decreasing time spent setting alarms
- User reporting happier feelings upon waking
- User being more timely to events
- User reporting improved sleep quality
- User delight at alarms being automatically set
- Seamless intergration across multiple users
- High DAU count and user retention
- Profitability  

Success would be measured by:

- User feedback and reviews
- Sleep monitoring data over time
- Daily Active User metrics
- Revenue
- Usability tests
- Integration metrics with apps and devices
- Referral program success

----------------

While this alarm clock could have an endless number of integrations, two things should shape our prioritization of features:

1. Most needed features to successfully alert users across multiple schedule, automatically.

This includes:

- Calendar integration
- Routine scheduling (for work days, school days, etc)
- The ability to see time, set alarms and turn off alarms
- Account management for multiple user profiles per account

2. Integrating highly used devices and apps, to support the most users possible.

This might include prioritizing apps and products like:

- Google Calendar
- Popular work place scheduling apps (like Calendly or Jira)
- Alexa, Siri and Google integration to support phone events and in-home devices
- Apple Watch or other wearables (Oura sleep ring)
- Sleep assisting apps, like Headspace or White Noise makers

By working with apps that users already use frequently, we can incentivize them to try out our alarm system quickly and make onboarding seamless. We can include a feedback/product request area so users can indicate what they would most like integrated next, helping us prioritize next features.

While these are core features that are needed for intial rollout, engineering and design insight will help prioritize each feature's development.

Long-term features that would help the app standout but aren't needed for MVP might include:

- Sleep monitoring with statistics and suggestions to improve quality of sleep
- Aggressive/Calm alarm capabilities
- Device integration to automate daily/nightly routines (dimming lights, making coffee)
- Auto-adjusting alarms based on weather/traffic or other events
- Accessibility integration with lights, vibrations and sounds
- Location tracking to notice deviations from usual schedule
- Battery saving capabilities

---------------