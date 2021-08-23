# Trial Signup: Introduction

This project is a Proof of Concept to show you how you can utilize the SignupRequest API with Lightning flows to allow internal and external users to provision trials.

**Dependency**
This project relies on the SignupRequest API being enabled in the target org.

## What does this project contain?
- Custom App - Trialforce Manager
- Custom Object - Trial Template
- Custom Report Type - Trail Signup Requests
- Lightning Flow - Signup Request
- Custom Settings - Trial Params
The custom object allows you to store multiple template ids (for example trials to target different industries).
The custom setting allows you to add flexibility to the signup request process. For example, create a lead with each request.

## Where can I find out more information?
- Make it easy for your customers to provision trials - [Part1](https://medium.com/inside-the-salesforce-ecosystem/signuprequest-api-and-trials-part-1-a8031258163a) and [Part2](https://medium.com/inside-the-salesforce-ecosystem/make-it-easy-for-your-customers-to-provision-trials-part-2-99cb9578675a)
- [SignupRequest API documentation](https://developer.salesforce.com/docs/atlas.en-us.212.0.object_reference.meta/object_reference/sforce_api_objects_signuprequest.htm)
- [Trailhead - Trail Management](https://trailhead.salesforce.com/content/learn/modules/isv_app_trials?trail_id=isv_developer_beginner)

