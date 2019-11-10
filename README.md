# :cyclone: Reclone

A heroku buildpack for install tools for backup your data to cloud. 

This Buildpack contains :

 - Rclone
 - Aria2 (v1.35.0)
 - p7zip (16.02)

## Commons Issue
If you have issue weird file / folder name you can use command below on Heroku CLI

    heroku config:add LANG=en_US.UTF-8

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/danipragustia/reclone.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/danipragustia/reclone.git
```
