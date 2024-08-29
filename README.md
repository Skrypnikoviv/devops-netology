# devops-netology
**/.terraform/* - Игнорирует все директории и файлы, находящиеся в любых каталогах с именем `.terraform`

*.tfstate, .tfstate. - Игнорирует все файлы, оканчивающиеся на `.tfstate`, и файлы, начинающиеся с `.tfstate.`

crash.log, crash.*.log - Игнорирует файлы журналов с информацией о сбоях. где crash.*.log значит игнорировать все файлы с именем crash, за которым следует любой символ и затем .log.

*.tfvars, *.tfvars.json - Игнорирует все файлы с расширением `.tfvars` и `.tfvars.json`

override.tf, override.tf.json, *_override.tf, *_override.tf.json - игнорируются файлы перекрытий и любые файлы содержащие *_override.tf, *_override.tf.json

.terraform.tfstate.lock.info - файл блокировки состояния Terraform, который создается при использовании команды terraform apply и содержит информацию о блокировке.

.terraformrc, terraform.rc - файлы конфигурации для командной строки Terraform, которые также не должны быть частью контроля версий.

!example_override.tf - файл исключение знак ! указывает на включение файла в репозиторий 
