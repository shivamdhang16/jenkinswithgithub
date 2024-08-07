authentication with github

Create PAT on github --> github-devoloper setting-PAT-Classice
go to jenkins- your item -configure-user(github emailid)--password(PAT)
required Step-->>>
Repository URL
Credentials
Branches to build


**Shell command to run**

ls
git clone https://github.com/shivamdhang16/jenkinswithgithub.git
cd jenkinswithgithub
cat jenkins.py
echo ${jenkins-a} | sudo -S apt-get install -y python3
/usr/bin/python3 jenkins.py


**how to add variable**
managejenkins--Global properties--Environment variables 
print like     echo "enviromet is ${GLOBAL_VAR}"   





ls
git clone https://github.com/shivamdhang16/jenkinswithgithub.git
cd jenkinswithgithub
ls
echo ${jenkins1} | sudo -S /usr/bin/apt-get install -y python3
/usr/bin/python3 jenkins.py
echo "its done"

##printvariable
name=shivam
echo "my name is ${name}"
echo "branch name is ${BUILD_ID}"
echo "job name is ${JOB_NAME}"
echo "enviromet is ${GLOBAL_VAR}"
