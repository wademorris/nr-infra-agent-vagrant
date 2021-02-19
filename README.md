# nr-infra-agent-vagrant

__Requirements__  
vagrant - can be installed with homebrew on mac  
virtualbox - https://www.virtualbox.org  

__Use__  
modify the ./etc/newrelic-infra.yml file to include your license key.  
from root dir, run "vagrant up"  
this will bring up a debian linux, copy New Relic config yaml files, install New Relic Agent packages and configure it to ingest /var/log/syslog and /var/log/syslog




