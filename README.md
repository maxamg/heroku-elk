#heroku-elk

Tested on: OSX 10.9.5, anisble 1.7.1, vagrant 1.6.3, virtualbox 4.3.16

### Instructions

1. clone repo
2. export HEROKU_API_KEY=blah
3. Check group_vars/all and ensure it has the correct herokuapp name(s) ### only tested 1 so far
4. vagrant up
5. Hit http://localhost:8080

Kibana page should display - default user/pass is kibana/kibana