# Android Web Server

# Introduction

As part of the final project for the TECH HIRE bootcamp we should "Build an Android wrapper for a Mined Minds Mentoring website"  able to accept push notifications.

This repository holds a simple messaging app linked to an AWS database to allow Firebase Cloud Messaging to be used to send push notifications to the Android app and receive post requests from the app.

# Getting Started

1. Make sure you have Ruby on your computer https://www.ruby-lang.org/en/downloads/
2. Clone this repository.
3. Run the file with command: ruby "file.rb"


# Explanation
- app.rb   # Sinatra base app linked to a database holding user name details, device/instance ID details, and simple messaging interface.
- pushmessage.rb # Code segments for building the https post messages to send push notifications to Firebase to be dispatched to the physical devices with the iOS wrapper app installed
- ios_post_ops.rb # code used from iOS app to post fcm token to database
- *\public  # folder holds basic stylesheet and image data*
- *\views   # folder holds the erb views for use with populating the database and generating messages for push notification*
