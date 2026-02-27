# devops-netology

`Будут проигнорированы:`

.terraform/ — будет игнорироваться каталог .terraform

*.tfstate — любые файлы с расширением .tfstate

*.tfstate. * — любые файлы, у которых имя содержит .tfstate. и после этого есть ещё любой суффикс

crash.log — файл с именем crash.log

crash.*.log — файлы, начинающиеся с crash. и заканчивающиеся на .log

*.tfvars — любые файлы с расширением .tfvars

*.tfvars.json — любые файлы с расширением .tfvars.json

override.tf — файл с именем override.tf

override.tf.json — файл с именем override.tf.json

*_override.tf — любые файлы, которые оканчиваются на _override.tf

*_override.tf.json — любые файлы, которые оканчиваются на _override.tf.json

.terraform.tfstate.lock.info — файл с именем .terraform.tfstate.lock.info

.terraformrc — файл с именем .terraformrc

terraform.rc — файл с именем terraform.rc