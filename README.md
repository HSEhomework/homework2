# Цифровая грамотность. Второе домашнее задание. Дедлайн 20.09.2017 23:59.
0. Установить [notepad++](https://notepad-plus-plus.org/) или [Geany](https://www.geany.org/) (или любой другой редактор, способный работать с регулярными выражениями). **Склонировать репозиторий** с необходимыми файлами: https://github.com/HSEhomework/homework_2.git
1. Дан файл опрос.txt. Это часть ответов на [опрос](https://docs.google.com/forms/d/e/1FAIpQLSfpxfbIcvC3vLfVvRlmfoysZmR-COSlbGulmzrAFVz3EmoO0g/viewform) с [Wiki](http://wiki.cs.hse.ru/Цифровая_грамотность)-страницы. Файл отличается от задания с семинара! **Задание**: выписать регулярное выражение, которое найдет все записи, относящиеся к Вашей группе. 
2. Дан файл emails.txt. Это коллекция email-писем корпорации [Enron](https://ru.wikipedia.org/wiki/Enron) ([оригинал](https://www.kaggle.com/wcukierski/enron-email-dataset#_=_)). **Задание**: выписать регулярное выражение, которое найдет все e-mail адреса в файле, начинающиеся с **гласной** буквы.
3. **Бонусное задание**: для файла emails.txt выписать регулярное выражение, которое найдет все письма, отправленные в период времени 00:00-03:00. Регулярное выражение должно выдавать именно строки с message-ID.

## Важно! Правила сдачи:
Создаем отдельный репозиторий на [GitHub](https://github.com/) (Важно: под тем же самым профилем, под которым Вы сдавали первое дз) с именем **DL_homework_2**. Под каждое задание нужен отдельный файл в репозитории с именами **task_1.txt**, **task_2.txt**, **task_3.txt**
### Формат файла task_X.txt:
1. На первой строке файла: регулярное выражение.
2. На второй строке файла: сколько было найдено совпадений по этому регулярному выражению. Число!
3. Далее: Строки, найденные этим регулярным выражением.

### Внимание: При нарушении правил сдачи задание может быть оценено в 0 баллов!

P.S. По вопросам, связанным с дз, обращайтесь, пожалуйста, в Telegram-группы нашего курса. Ссылки есть на [Wiki](http://wiki.cs.hse.ru/Цифровая_грамотность).
