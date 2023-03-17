# gitlab-playbook

Make a dedicated directory for gitlab:

`mkdir gitlab`

For convenience, we will also set an environment variable that will contain the path to our Gitlab directory:

`export GITLAB_HOME=$(pwd)/gitlab`

Run ansible playbook gitlab-up.yml to install and start gitlab and gitlab-down.yml to stop the docker container.
