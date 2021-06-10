## Do I need to login to the app to create an alert?
Alerts are a basic feature and don't require user login. To create an alert you just need set your Search Preferences in Settings. You need to select either the district or the PIN Code where the Alert should search for vaccine slots.

## My Alert shows a date by default and I cannot change it. How do I change the search date in alert?

When alert asks the CoWIN API for a list of vaccine centers with a date, the API sends a list of vaccine centers that have slots upto a week from the date of query. Which means that if the alert date is 10-06-2021, its getting the data for sessions from 10-06-2021 to 16-06-2021. In short your alert is looking for any open slots in the next week.

## The alert shows today's date sometime and it shows tommorrow's date other times. Why is that?

From 12:00 AM to 10:00AM, the alert looks for open slots for the current date. Afterwards it starts looking for slots for the day after that. It does that because by 10 in the morning, all the slots for the current date are most likely filled, and it doesn't make much sense to run that search.

## I entered my pin code in the Search Preferences Settings but when I try to create an alert it asks me to enter the pin code again. How do I fix that?

All Text Inputs need to be submitted for their values to be saved on the device. Pin Code is entered by a Text Field, and all text fields have a submit button right next to them (The submit button is a blue checkmark). You need to press the submit button to save that value. This is also true for the API Key field.

## My alert stopped running unexpectedly. Why did that happen and how do I avoid it?

Your alert runs as long as the App is in the background. When you clear all your recent apps (including) this one, the app and all its associated processes are killed by the Operating System. Make sure that you don't clear all recent apps when an alert is running. Instead you should remove apps that no longer need to be in the background, one by one.

## I denied the SMS read permission at App Startup and now I can't login. How can I fix that?

You can grant settings to apps manually by going to your Phone Settings:
**Settings > Apps > Book My Vaccine > Permissions** and switching on the Read SMS permissions. Once you grant those permissions, auto sign in will start working.

## What are Nightly Builds?

Nightly builds are builds with some small changes or features that were implemented during the day. They may contain experimental features and aren't likely to be tested. You can still donwload them to test out new features.

## Where can I download Nightly Builds?

The latest nightly build is usually linked in the README page. But if you want other nightly builds you can find them under the nightly-builds folder of this directory. All the builds can be found in a folder with their build-date.
