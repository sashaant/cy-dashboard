npm init npm install cypress npm install prettier

Re-write cypress open comand 
"scripts": { 
    "cy:open": "cypress open", 
    "cy:run": "cypress run"
},


To run only(one) special file, run the command:
npx cypress run --spec="cypress/integration/login.js" --record --key 6491d817-54e5-47bd-bc51-269743243f94


Jenkins:
dowload jenkins.war
java -jar jenkins.war --httpPort=8080 --enable-future-java