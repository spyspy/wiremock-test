1. DOWNLOAD
http://wiremock.org/docs/download-and-installation/

2. RUN COMMAND LINE and RUN wiremock server
http://wiremock.org/docs/running-standalone/

java -jar wiremock-jre8-standalone-2.29.1.jar

2-1 Or You Might USE: NPM RUN

npm run go


3. Go to Browser

EX:
http://localhost:8080/test/api/json

http://localhost:8080/test/api

http://localhost:8080/test/xml

=================
Github PROCESS

1. NEW a repo in my Github

https://github.com/spyspy/wiremock-test.git


2. Local File Folder and Command Line

Reference:
https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line


cd my-wiremock-folder

git init -b main
git add .
git commit -m "First commit"
git remote add origin  <REMOTE_URL> 
git remote -v

---------------------
What you will see:
git remote -v
origin  https://github.com/spyspy/wiremock-test.git (fetch)
origin  https://github.com/spyspy/wiremock-test.git (push)
---------------------

git push origin main