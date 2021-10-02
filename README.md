# devops-netology

--------------
1.    Найдите полный хеш и комментарий коммита, хеш которого начинается на aefea.
commit aefead2207ef7e2aa5dc81a34aedf0cad4c32545
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com>
Date:   Thu Jun 18 10:29:58 2020 -0400

    Update CHANGELOG.md

2.    Какому тегу соответствует коммит 85024d3?
tag: v0.12.23

3.    Сколько родителей у коммита b8d720? Напишите их хеши.

4.    Перечислите хеши и комментарии всех коммитов которые были сделаны между тегами v0.12.23 и v0.12.24.
33ff1c03b (tag: v0.12.24) v0.12.24
b14b74c49 [Website] vmc provider links
3f235065b Update CHANGELOG.md
6ae64e247 registry: Fix panic when server is unreachable
5c619ca1b website: Remove links to the getting started guide's old location
06275647e Update CHANGELOG.md
d5f9411f5 command: Fix bug when using terraform login on Windows
4b6d06cc5 Update CHANGELOG.md
dd01a3507 Update CHANGELOG.md
225466bc3 Cleanup after v0.12.23 release
85024d310 (tag: v0.12.23) v0.12.23

5.    Найдите коммит в котором была создана функция func providerSource, ее определение в коде выглядит так func providerSource(...) (вместо троеточего перечислены аргументы).
8c928e835

6.    Найдите все коммиты в которых была изменена функция globalPluginDirs.
35a058fb3 main: configure credentials from the CLI config file
c0b176109 prevent log output during init
8364383c3 Push plugin discovery down into command package

7.    Кто автор функции synchronizedWriters?
Author: Martin Atkins <mart@degeneration.co.uk>
---------------
в файле .gitignore в папке terraform :
Исключена локальная дирректория .terraform
Исключены файлы с расширением *.tfstate
Исключены файлы в название которых присутствут .tfstate.
Исключен файл crash.log
Исключены файлы с расширением *.tfvars
Исключены  файлы override.tf и override.tf.json
А так же файлы, в начале которых могут стоять любые символы и заканчивающиеся на _override.tf и _override.tf.json
Исключены файлы  CLI configuration .terraformrc и terraform.rcо
