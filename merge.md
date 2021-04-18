[к содержанию](./readme.md)

## Слияние

Ветку, в которую мы хотим слить изменения, будем называть основной, а ветку, из которой мы будем их сливать, — *тематической*.

Слиние включает в себя создание нового коммита, который основан на общем коммите-предке двух ветвей и указывает на оба HEAD в качестве предыдущих коммитов. Для слияния мы переходим на основную ветку и используем команду ``git merge`` <тематическая ветка>.

 Если обе ветви меняют одну и ту же часть файла, то возникает конфликт слияния — ситуация, в которой Git не знает, какую версию файла сохранить, поэтому разрешать конфликт нужно собственноручно. Чтобы увидеть конфликтующие файлы, используйте `git status`.

 Замените в этом блоке всё на версию, которую вы хотите оставить, и подготовьте файл. После разрешения всех конфликтов можно использовать `git commit` для завершения слияния.