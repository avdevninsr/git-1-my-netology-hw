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
Будут проигнорированы данные типы файлов:
.tfstate - будут проигнорированы все файлы с расширением tfstate
*.tfstate.* - будут проигнорированы все файлы с расширением tfstate. (вместо звездочки ещё любое расширение)
crash.log - будут проигнорированы все файлы с именем crash и с расширением log
crash.*.log - будут проигнорированы все файлы с именем crash и с расширением *.log (вместо звездочки еще любое расширение)
*.tfvars - будут проигнорированы все файлы с расширением tfvars
*.tfvars.json - будут проигнорированы все файлы с расширением tfvars.json
override.tf - будут проигнорированы все файлы с именем override и с расширением tf
override.tf.json - будут проигнорированы все файлы с именем override и с расширением tf.json
*_override.tf - будут проигнорированы все файлы, в имени которых есть _override и с расширением tf
*_override.tf.json - будут проигнорированы все файлы, в имени которых есть *_override и с расширением tf.json
.terraformrc - будут проигнорированы все файлы, заканчивающиеся на .terraformrc
terraform.rc - будут проигнорированы все файлы с именем terraform и с расширением rc.</br>
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
