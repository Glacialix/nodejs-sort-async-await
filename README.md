Сортировка файлов из сложной структуры папок и файлов неограниченной вложенности и раскладывает все файлы по папкам в алфавитном порядке

how to install:

- git clone
- npm install
- node index.js

Команда для указания пути откуда брать картинки для сортировки: --from=<путь до картинки>
Команда для указания пути куда класть картинки для сортировки: --to=<путь до картинки>
Команда для удаления исходной папки: --del-old

Пример с использованием флагов:

- node index.js --from=./images --to=./images_sorted --del-old
