# test_nginx

ansible-playbook create_azure_vm.yml

ansible-playbook mysql_create.yml -i inv

ansible-playbook mysql_dump.yml -i inv -e "vm_name=myVM dump_file=mysql_dump"

ansible-playbook start_webapp.yml -i inv -e "vm_name=myVM"

