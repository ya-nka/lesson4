[к содержанию](./readme.md)

## Коммиты
 
 Основы работы с Git предполагают понимание коммитов. Команда ``git commit`` откроет текстовый редактор для ввода сообщения коммита. Также эта команда принимает несколько аргументов:
  

 - _-m_ позволяет написать сообщение вместе с командой, не открывая редактор. Например ``git commit -m "Пофиксил баг"``
  

 - _-a_ переносит все отслеживаемые файлы в область подготовленных файлов и включает их в коммит (позволяет пропустить ``git add`` перед коммитом);
  

 - _--amend_ заменяет последний коммит новым изменённым коммитом, что бывает полезно, если вы неправильно набрали сообщение последнего коммита или забыли включить в него какие-то файлы.