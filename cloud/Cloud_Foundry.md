## Installation Ubuntu
wget -q -O - https://packages.cloudfoundry.org/debian/cli.cloudfoundry.org.key | sudo apt-key add -
echo "deb http://packages.cloudfoundry.org/debian stable main" | sudo tee /etc/apt/sources.list.d/cloudfoundry-cli.list
sudo apt-get update
sudo apt-get install cf-cli



## Pivotal Cloud Foundry
cf -help

cf login -a https://api.run.pivotal.io

cf push

cf logs cf-spring --recent
cf logs cf-spring

cf marketplace -s elephantsql
cf create-service elephantsql turtle cf-spring-db
cf bind-service cf-spring cf-spring-db

dfd
cf restart cf-spring
dfdf2=4p12p
cf services

cf scale cf-spring -i 2
cf scale cf-spring -m 1G
cf scale cf-spring -k 512M

cf app cf-spring

## Reference
https://pivotal.io/platform/pcf-tutorials/getting-started-with-pivotal-cloud-foundry/next-steps

http://cf-spring-preracing-yellowbird.cfapps.io/

https://github.com/settings/repositories