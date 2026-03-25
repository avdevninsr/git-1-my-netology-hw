# Домашнее задание к занятию «Системы контроля версий»

## Задание 1
Из - за технических проблем не смог нормально заскринить создание аккаунта и пришлось пересоздавать репозиторий примерно в середине процесса выполнения, поэтому названия коммитов могут не совпадать.</br>
Создание нового репозитория представлено на рисунке 1.</br>

<img src="img/new_repo.png" alt="Рисунок 1" width="auto" height="auto"></br>
Рисунок 1. Создание нового репозитория.</br>
Создание токенов представлено на рисунках 2, 3, 4 и 5.</br>

<img src="img/token_generation.png" alt="Рисунок 2" width="auto" height="auto"></br>
Рисунок 2. Создание токена 1.

<img src="img/token.png" alt="Рисунок 3" width="auto" height="auto"></br>
Рисунок 3. Токен 1 создан.

<img src="img/token_generation2.png" alt="Рисунок 4" width="auto" height="auto"></br>
Рисунок 4. Создание токена 2.

<img src="img/token2.png" alt="Рисунок 5" width="auto" height="auto"></br>
Рисунок 5. Токен 2 создан.</br>
Клонирование репозитория представлены на рисунках 6 и 7 соответственно.</br>

<img src="img/1.PNG" alt="Рисунок 6" width="auto" height="auto"></br>
Рисунок 6. Клонирование репозитория.

<img src="img/3.PNG" alt="Рисунок 7" width="auto" height="auto"></br>
Рисунок 7. Первый коммит.</br>

Создание файлов .gitignore и второго коммита представлены на рисунках 8 и 9 соответственно.</br>

<img src="img/5.PNG" alt="Рисунок 8" width="auto" height="auto"></br>
Рисунок 8. Создание .gitignore.</br>

<img src="img/6.PNG" alt="Рисунок 9" width="auto" height="auto"></br>
Рисунок 9. Второй коммит.</br>
Благодаря файлу .gitignore в папке Terraform будут проигнорированы файлы .tfstate в которых хранится содержит информацию о текущем состоянии инфраструктуры и используемых конфигурациях. Логи ошибок Терраформа, (crash.log и crash.*.log), файлы .tfvars и .tfvars.json, которые могут содержать конфиденциальные данные, такие как пароли, закрытые ключи и другие секреты. override.tf, override.tf.json, *_override.tf, *_override.tf.json - файлы переопределения, поскольку они обычно используются для локального переопределения ресурсов Игнорируются временные файлы информации о блокировке .terraform.tfstate.lock.info, созданные terraform apply Игнорируются файлы конфигурации CLI .terraformrc и terraform.rc Раскомментировав некоторые параметры можно игнорировать также выходные файлы графиков *.dot, сгенерированные с помощью программы `terraform graph Переопределённые файлы !example_override.tf, которые вы хотите добавить в систему управления версиями, используя шаблон negated Файлы tfplan (tfplan), содержащие вывод команды terraform plan -out=tfplan Файлы плана, сохраненные перед уничтожением конфигурации Terraform (planout).</br>
Создание файлов will_be_deleted.txt (с текстом will_be_deleted) и will_be_moved.txt (с текстом will_be_moved) и их коммит представлены на рисунке 10.</br>

<img src="img/8.PNG" alt="Рисунок 10" width="auto" height="auto"></br>
Рисунок 10. Создание файлов will_be_deleted.txt (с текстом will_be_deleted) и will_be_moved.txt (с текстом will_be_moved) и их коммит.</br>
Действия над файлами will_be_deleted.txt и will_be_moved.txt и их коммит представлены на рисунке 11.</br>

<img src="img/9.PNG" alt="Рисунок 11" width="auto" height="auto"></br>
Рисунок 11. Действия над файлами will_be_deleted.txt и will_be_moved.txt и их коммит.</br>
Проверка всех изменений представлена на рисунке 12.</br>

<img src="img/11.PNG" alt="Рисунок 12" width="auto" height="auto"></br>
Рисунок 12. Проверка изменений в репозитории.</br>
Отправка изменений в репозиторий представлена на рисунке 13.</br>

<img src="img/12.PNG" alt="Рисунок 13" width="auto" height="auto"></br>
Рисунок 13. Отправка изменений в репозиторий.</br>
[Созданный согласно заданию репозиторий.](https://github.com/avdevninsr2/devops-netology)