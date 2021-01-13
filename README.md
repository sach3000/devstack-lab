## Шаблон и скрипты
____

Для создания ВМ в Server Group наоснове шаблона heat
`openstack stack create -t tmpl-heat-provision.yml --parameter instance_name="web01" --parameter net="public" --parameter server_group="1afb1acb-778e-48a0-a5b4-99d068ca1090" my_stack1`


