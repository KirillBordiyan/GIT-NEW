## Инструкция GIT

__контроль версий__ - возможность хранить и возвращаться к различным версиям 

гит хранит изменения в файле, а не сам файл 

__git init__ -  инициализация, начало отслеживания изменений в папке

__git status__ - проверка статуса папки, какая ветка, коммиты, что сохранять

__git add__ +file_name/top+TAB -  запись отслеживания изменений

__git commit__ -m "<comment>" - факсация изменений

__git log__ - журнал изменений, список коммитов

__git checkout__ +4 символа номера коммита - возвращение к какой-то версии (старой или новой)

__git checkout__ /master/ - в конце главную ветку, возврат в актуальную версию 

__git diff__ - разница между сохраненным файлом и в git



__git branch__ name - созздание новой ветки

__git checkout__ nmae - переход на какую-то ветку


__git merge +branch__ -находясь на ветке, с поомщью этой команды вносим измнения в нее из другой (пишем в команде)

__git branch -d +branch__ - удаление ветки 

__git log --graph__ - отображение всех веток

__git checkout -b name__ - создание и переходи в ветку


__git clone +URL__ - копирование удаленного репозитория на компьютер 

__git push__ - пуш на ГХ

__git pull__ - вкид на комп

кнопка fork - копирование одного удаленого репозитория в свой удаленный репозиторий, далее git clone -> отдельная ветка для изменений-> изменения(новые файлы, правки и пр)
-> коммит->направляем*
*направляем: git подскажет git --set...
далее, на ГХ Compare&pull requeset и отправляем 