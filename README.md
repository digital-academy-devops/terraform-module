# Модуль 5. Terraform

Целью данного модуля является применение на практике Hashicorp Terraform, а также знакомство и использованием gitops-подходов к управлению инфраструктурой.


## Задание
Используя https://github.com/digital-academy-devops/terraform-gitops, создайте:
 1. `Каталог` в `облаке` Yandex Cloud, который будете использовать в дальнейшем для создания инфраструктуры необходимой для выполнения практических занятий.
 1. Тестовую инфраструктуру внутри `каталога`:
    1. VPC сеть, а так же подсеть внутри неё 
    1. Виртуальную машину:
       - Прерываемую
       - 2 CPU/2 Gb RAM
       - Гарантированная доля vCPU - 20%
       - Дисковое пространство - 10 Gb
       - Образ - `ubuntu-2204-lts`
       - Платформа: standard-v1

# Документация
- [Иерархия ресурсов Yandex Cloud](https://cloud.yandex.ru/docs/resource-manager/concepts/resources-hierarchy)
- [Yandex.Cloud Terraform Provider](https://registry.tfpla.net/providers/yandex-cloud/yandex/latest/docs)

## Дополнительная информация

- Используйте документацию в [terraform-gitops](https://github.com/digital-academy-devops/terraform-gitops).
- Описание механики работы [terraform-gitops](https://github.com/digital-academy-devops/terraform-gitops), а также пример создания каталога и инфраструктуры в нём дан в ходе онлайн-занятия и доступен в записи.
- `Каталог` с примером:
  - https://github.com/digital-academy-devops/terraform-gitops/blob/main/states/system/folder.tf#L1
  - https://github.com/digital-academy-devops/terraform-gitops/tree/main/states/mostashkin
- Репозиторий с кодом написанный и разобранный в ходе лекций по Terraform - https://github.com/digital-academy-devops/terraform-tutorial
