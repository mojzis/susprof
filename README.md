Very simple Drupal profile for development.
-------------------------
Includes a make file  for quick download.  
Contrib modules are downloaded under sites/all/modules/contrib  


usage
-------------------------

```
mkdir newsite
cd newsite
drush make https://github.com/mojzis/susprof/raw/master/prof.make --contrib-destination=sites/all --dev --prepare-install --force-complete ./
chown (in my case the perms are not given)
drush si
```

TODO
-------------------------
* set admin theme
* shell script ?
* mothership subtheme (?)
* setup markdown filter as default
* custom modules ?
