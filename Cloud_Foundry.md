##Pivotal Cloud Foundry
cf -help

cf login -a https://api.run.pivotal.io

cf push

cf logs cf-spring --recent
cf logs cf-spring

cf marketplace -s elephantsql
cf create-service elephantsql turtle cf-spring-db
cf bind-service cf-spring cf-spring-db


cf restart cf-spring

cf services

cf scale cf-spring -i 2
cf scale cf-spring -m 1G
cf scale cf-spring -k 512M

cf app cf-spring

##Reference
https://pivotal.io/platform/pcf-tutorials/getting-started-with-pivotal-cloud-foundry/next-steps

http://cf-spring-preracing-yellowbird.cfapps.io/

https://github.com/settings/repositories