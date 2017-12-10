# Training Wheels

Helps onboard & train new WordPress users

## Concept

I conduct training for new WordPress users in large batches and sometimes I need to check if they've setup everything properly and even score them.

So, I need to know if my trainees:

 1. Have performed some activities (install & activate themes or plugins, for example)
 1. Have saved proper settings
 
This plugin hooks into actions and filters to compare against a checklist (config file) to see if a user has performed all the necessary activities.

It also compares against a settings configuration to check if the user has saved correct settings.

It gets these config files either from a remote (instructor's) url or through uploaded ones.

It sends the results to a url and/or as email to a defined (instructor's) email address.

These results can be processed to score or give feedback to the students.
