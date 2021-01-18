# Countly push-to-country plugin

This is a fork of the official `push` plugin. It adds the ability to select audience based on the country code.

### Deploying new changes
* Ensure changes are merged to `master` branch
* Login to the instance via ssh
* change to the plugin directory
```
cd /usr/local/countly/plugins/push
```
* Pull changes from this repository
```
git pull origin master
```
* Run the `upgrade` command that compiles and minifies the JS and restarts the server.
```
sudo countly upgrade
```
* Login to Countly web interface to verify that changes were deployed
