# Android Web Server

Assignment:
Build an ANdroid wrapper for a Mined Minds Mentoring website configured to be able to accept push notifications

This repository holds a simple messaging app linked to an AWS database to allow Firebase Cloud Messaging to be used to send push notifications to the Android app.

File Index:
- app.rb   # Sinatra base app linked to a database holding user name details, device/instance ID details, and simple messaging interface.
- pushmessage.rb # Code segments for building the https post messages to send push notifications to Firebase to be dispatched to the physical devices with the iOS wrapper app installed
- ios_post_ops.rb # code used from iOS app to post fcm token to database
- *\public  # folder holds basic stylesheet and image data*
- *\views   # folder holds the erb views for use with populating the database and generating messages for push notification*
