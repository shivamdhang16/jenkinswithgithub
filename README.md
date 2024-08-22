authentication with github

To connect GitHub and Jenkins using a Personal Access Token (PAT), follow these steps:

Create a Personal Access Token on GitHub:

Go to GitHub and log in to your account.
Navigate to Settings > Developer settings > Personal access tokens.
Click Generate new token.
Give it a descriptive name, select the required scopes (e.g., repo for full control of private repositories), and click Generate token.
Copy the generated token. You won’t be able to see it again.
Configure Jenkins to Use the Token:

Install GitHub Plugin: Ensure you have the GitHub plugin installed in Jenkins. Go to Manage Jenkins > Manage Plugins > Available tab and search for "GitHub Plugin" if it’s not already installed.
Add GitHub Credentials:
Go to Manage Jenkins > Manage Credentials.
Choose the appropriate domain or (global) for all jobs.
Click Add Credentials.
Select Kind as Secret text.
Paste the GitHub PAT you created earlier into the Secret field.
Give it a meaningful ID and Description, then click OK.


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
