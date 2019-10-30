# EGSians Social Network

## Summary

For the internship program, you are required to develop a social network project using java nowadays popular technologies and frameworks. The solution should be SOA (Service Oriented Architecture). The main goal of the mentioned architecture will be to separate business logic from UI by exposing web services (Restful) and using independent front-end technologies to render business components. 

## Functional Requirements

Develop a social network called EGSians. It will be possible to sing up quickly on the platform by providing a full name, email, and password. Also, if possible implement Facebook and Google authentication (on click registration). Password recovery functionality should be handled as well. After successful registration user will receive a welcome email (use some free email provider API, e.g SendPult, UniSender, etc.) and automatically will be authenticated. Once the user enters into the system one will be able to update his/her profile by uploading an avatar, birth of day, mobile number, nickname, summery. User profile updating progress should be available (e.g. profile 70% completed, once all data provided user will get 100% completed profile). Here are the activities that the user can do:

* Search for other users, by the following criteria: by the first name and last name, date of birth range, email, phone number.
* Send a friend request to any user that he/she still not a friend
* Accept friend request from another user
* See the list of friends
* Unfriend any user at any time.
* Post a text or image, or both at once.
* Put a tag on the post (e.g #bestphoto)
* User can comment on the post of his/her friends only but can see the other posts
* User can edit/remove his/her own posts
* Reply on comment
* Show total count of comments under each post
* Possibility to retrieve posts sorted by date descending

Note that actions related to posting and commenting should generate notifications. This notification will be available for particular users, for example, if a user posts a comment all his friends should receive notifications. Lead this notification with email as well.

## Technical Requirements

It is required to develop a Restful API with valid functionality and provide online documentation (e.g. Swagger) and test scenarios. The UI will be plus, but don’t spend much time on it, use some ready component (Bootstrap, open-source HTML designs, etc.). Start your development using some open Git Repositories like GitHub, BitBucket. No direct commit to “develop” branch, only Pull Requests are allowed. If possible adopt the Git Workflow approach. The source code should be well documented, using clean-code approaches (DRY, KISS, SOLID, YAGNI, etc.). The software should be bug-free as much as possible, project coverage at least 70% (use testing F.I.R.S.T approach). 

## Technology Stack
* Java 8
* Spring Framework
* JPA/Hibernate as ORM
* MySQL,  H2 in-memory database for test
* GoF Design Patterns
* Swagger
* Git
* Maven
* Java Docs
* Unit / Integration Tests
