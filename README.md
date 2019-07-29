# cisco-csr1000v-ios-upgrade-downgrade
network automation with ansible 

# For ansible use 
## Step1 
create ios_var.yml file for your personal use
## Step2 
$ansible-playbook run.yml -i invenory -vvv

# For tower use
## Step1 
create each template for pre_check_actions, ftp_actions, upgrade_actions and post_check_acitons
## Step2
create one work flow template by compainging of above four templates
## Step3
create survey instead of using ios_var.yml
