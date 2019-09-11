# test_nginx

ansible-playbook create_azure_vm.yml

ansible-playbook run_webapp.yml -i inv -e "vm_name=myVM dump_file=mysql_dump"


## Run individual role using ansible command:

ansible -i inv myVM -m include_role -a name=dump_mysql_db -e "dump_file=mysql_dump"

