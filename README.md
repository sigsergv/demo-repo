# Демо-репозиторий

В этом репозитории несколько коммитов, веток и тегов, призванных продемонстрировать некоторые фичи git: rebase, merge и т.п.

Файлы здесь используются одновременно для описания происходящего и как объекты операций с git-сущностями.

Этот файл является первой версией и был закоммичен самым первым коммитом. А чтобы всё было похоже на настоящий репозиторий, рядом лежит код на python — файл `test.py`. Пока он при запуске печатает `Hello world` и с ним уже есть проблемы. Как и с этим файлом `README.md` — слишком длинные строки. Эти проблемы будут постепенно исправляться в следующих коммитах.

Этот текст был добавлен вторым коммитом, только для того, чтобы создать минимальную историю коммитов.

Эта строчка была добавлена при работе над веткой `fix_line_endings`, основная цель которой — исправить недочёты в этом файле, точнее, пока только один — отсутствующие точки в конце некоторых предложений. Ну и заодно это предложение было добавлено вторым коммитом в ветке, чтобы создать побольше истории.

Этот абзац был добавлен в параллельной ветке `fix_python_hashbang`, в которой я поправил скрипт `test.py`. Также в этом же коммите я немного стилистически исправил третий абзац, где упоминается файл `test.py` в первый раз.

# Merges

Этот абзац был добавлен в merge-коммите, который был создан при слиянии ветки `main` и ветки `fix_python_hashbang`. Так как в процессе был обнаружен конфликт в этом файле `README.md`, необходимо было его вручную разрешить, что и было сделано.

Если посмотреть на этот коммит в репозитории (а он был помечен тегом [tag-1st-merge-commit](https://github.com/sigsergv/demo-repo/releases/tag/tag-1st-merge-commit)), то видно, что изменения в этом разделе были добавлены именно в merge-коммите, а не в коммитах предыдущих веток.
