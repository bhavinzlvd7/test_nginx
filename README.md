# test_nginx

ansible-playbook create_azure_vm.yml

ansible-playbook mysql_create.yml

ansible-playbook mysql_dump.yml -i inv -e "vm_name=myVM dump_file=dump.sql"

ansible-playbook start_webapp.yml -i inv -e "vm_name=myVM"

