## Шаблон и скрипты
____

Для создания ВМ в Server Group на основе шаблона heat

`openstack stack create -t tmpl-heat-provision.yml --parameters "instance_name=web01;net=public;server_group=1afb1acb-778e-48a0-a5b4-99d068ca1090" my_stack1`


