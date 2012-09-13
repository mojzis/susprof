Very simple profile for development.
Includes a make file  for quick download.
Contrib modules are downloaded under sites/all/modules/contrib

mkdir newsite
cd newsite
drush make ../susprof/susprof.make --dev --prepare-install --force-complete ./
chown (in my case the perms are not given)
drush si
