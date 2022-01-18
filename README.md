# Тут будут выполнены все ДЗ по курсу devops-15

## Задание № 1

1. Будут игнорироваться все файлы в папке .terraform во всех подпапках проекта 
 > **/.terraform/*

2. Будут игнорироваться все файлы, которые в конце имеют окончание ".tfstate" и все файлы в имени которых есть буквосочетание ".tfstate." 
*.tfstate
 > *.tfstate.*

3. Будет игнорироваться файл с названием "crash.log"
 > crash.log

4. Будут игнорироваться все файлы, которые в конце имеют окончание ".tfvars"
 > *.tfvars

5. Будут игнорироваться все файлы, которые в конце имеют окончание  "_override.tf" и "_override.tf.json", а также файлы с названием override.tf и override.tf.json
 > override.tf
 > override.tf.json
 > *_override.tf
 > *_override.tf.json

6. Будут игнорироваться файлы c названием ".terraformrc" и "terraform.rc"
> .terraformrc
> terraform.rc

## Домашнее задание к занятию «2.4. Инструменты Git»

1. Полный хеш коммита aefead2207ef7e2aa5dc81a34aedf0cad4c32545 "Update CHANGELOG.md"

2. Соответствует тегу "v0.12.23"

3. У коммита b8d720 - 2 родителя  "56cd7859e05c36c06b56d013b55a252d0bb7e158" и "9ea88f22fc6269854151c571162c5bcf958bee2b".

4. Коммиты dd01a35078f040ca984cdd349f18d0b67e486c35 "Cleanup after v0.12.23 release" 225466bc3e5f35baa5d07197bbc079345b77525e "Update CHANGELOG.md" 4b6d06cc5dcb78af637bbb19c198faff37a066ed "Update CHANGELOG.md" d5f9411f5108260320064349b757f55c09bc4b80 " command: Fix bug when using terraform login on Windows" 06275647e2b53d97d4f0a19a0fec11f6d69820b5 "Update CHANGELOG.md 5c619ca1baf2e21a155fcdb4c264cc9e24a2a353 " website: Remove links to the getting started guide's old location Since these links were in the soon-to-be-deprecated 0.11 language section, I think we can just remove them without needing to find an equivalent link." 6ae64e247b332925b872447e9ce869657281c2bf " registry: Fix panic when server is unreachable Non-HTTP errors previously resulted in a panic due to dereferencing the resp pointer while it was nil, as part of rendering the error message. This commit changes the error message formatting to cope with a nil response, and extends test coverage." 3f235065b9347a758efadc92295b540ee0a5e26e "Update CHANGELOG.md" b14b74c4939dcab573326f4e3ee2a62e23e12f89 "[Website] vmc provider links"

5. commit 8c928e83589d90a031f811fae52a81be7153e82f

6. 78b122055 52dbf9483 41ab0aef7 66ebff90c 8364383c3

7. Martin Atkins mart@degeneration.co.uk
