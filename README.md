# elasticsearch_pg

Good reference

https://medium.com/@adnanxteam/how-to-install-elasticsearch-5-and-kibana-on-homestead-vagrant-60ea757ff8c7

Need to have
virtualbox
vagrant
homestead

after installing virtualbox and vagrant

use github to clone the homestead

git clone https://github.com/laravel/homestead.git Homestead

run git checkout version_name for homestead to get latest release

run
bash init.sh
to get homestead initial

generate ssh keys

modify homestead.yaml

change folder to map your dev folder
folders:
   - map: your dev folder

after update homestead.yaml

in the Homestead folder
run vagrant box add laravel/homestead
and select virtualbox as your provider

after it is done
run vagrant up, it will install everything
