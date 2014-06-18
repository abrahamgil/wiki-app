Wiki-App

Purpose

Build an application that allows users to create public and private Markdown-based wikis. We'll call our application "Blocipedia", but you're free to name it anything you want.

Use case

Wikis are a great way to collaborate on community-sourced content. Whether the wiki is for a hobby or work-related project, we'll build an app that lets users create their own wikis and share them publicly or privately with other collaborators.

Requirements

As a user, I should be able to sign up for a free account by providing a user name, password and email address.
As a user, I want to be able to sign in and out of the Blocipedia.
As a user, I want to be able to create wiki pages using Markdown syntax.
As a user with a free account, I want to be able to create public wikis that anyone may view.
As a user I want to be able to upgrade my account from a free plan to a paid (premium) plan so that I can create private wikis.
As a user with a premium account, I want to be able to create private wikis that require a Blocipedia account and proper authorization to view.
As a user with a premium account, I want to be able to add collaborators to my private wikis.
As a user with a premium account, I should be able to add an unlimited number of collaborators to my wikis.
Resources

Use the Devise gem for authentication. Blocipedia's authentication system should allow users to sign up, sign in, reset their passwords and send emails for account authorization.

Use the Redcarpet gem to parse Markdown syntax.

Use Stripe so that you can charge users for creating premium accounts (for creating private wikis). The pricing plan is up to you.

Use the Friendly ID gem to create readable URLs. Check out this Railscast for an implementation demonstration.

If you'd like to challenge yourself with a slick feature, create a client-side markdown editor using a tool like Epic Editor. This will allow users to see their Markdown syntax formatted without a request being sent to the server.