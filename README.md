# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Opening credentials on PowerShell since EDITOR is not recognized
$env:EDITOR="code --wait"
rails credentials:edit
Rails.application.credentials.aws[:access_key_id]
Rails.application.credentials.config[:aws][:access_key_id]

or
rails credentials:edit --environment development

Rails.application.credentials[:aws][:access_key_id]