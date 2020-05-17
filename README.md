# JSON API
A RESTful API for WordPress

This is a fork of the original plugin to make it compatible for Memberpress plugin. 

## Description

By default Memberpress plugin and Wordpress Rest API doesnt play well. Meaning, if you have a content restricted by plugins like memberpress it wont showup in Rest api and there is no way to authenticate. Also if you use Wp Json API plugin (without the mod) to get the post, it will ignore memberpress setting. This modified version ensures that memberpress restrictions are taken into consideration by simply authenticating the user. 

Finally remember this also returns user pass in hash! 

## How to use

I have setup a new user role Member in wordpress and also use the Membepress roles addon and while creating a membership I simply also add the role to the member. The rest api gives me back the user role and I can check if he is a Member or not. 
