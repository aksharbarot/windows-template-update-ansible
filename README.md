# windows-template-update-ansible
windows template patching/update

Run cmd as follow
``` ansible-playbook templatepatch.yaml -i localhost, --extra-vars "user1=$user pass1=$pass hostname=$vchost wintemp=$wintemp"```
