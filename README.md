# IntregationProvider

## What' included
- Jenkins
- Gitlab

## The "normal" build process
- Check in the code to GitLab
- GitLab will start the Jenkins Build
- Jenkins provide your Code to the FTP-Server 
- Jenkins will create a tag in GitLab

### Jenkins 
- Composer 
- PHP Checks.....

### Install 
- Frest install of RHEL 
- Add Subscription for RHEL & OpenShift
- SSH Server installieren bzw. starten
- Add Repos for OpenShift
subscription-manager repos \
    --enable="rhel-7-server-rpms" \
    --enable="rhel-7-server-extras-rpms" \
    --enable="rhel-7-server-ose-3.2-rpms"
