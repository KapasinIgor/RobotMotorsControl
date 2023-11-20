# RobotMotorsControl

### Общее описание проекта RobotMotorsControl:

Это учебный проект для закрепления знаний по использованию Git.
Тестирование пинов Raspberry Pi.
В начальной версии скрипта было реализовано только движение вперед
В дальнейшем были внесены изменения в код для движения назад.

### Порядок выполнения работы

- Для работы над проектом на GitHub был создан пустой репозитарий:
https://github.com/KapasinIgor/RobotMotorsControl

- После этого он был склонирован на локальный компьютер под управлением Ubuntu 20.04:
```bash
git clone https://github.com/KapasinIgor/RobotMotorsControl.git 
```
- Созданы файл скрипта motors_control.py и файл README.md.

- Оба файла добавлены командой:
```bash
git add .
```

- И закомичены с сообщением:
```bash
git commit -m "added files motors_control.py and readme.md"
```
- Затем запушены на GitHub (при этом необходимо было авторизоваться на GitHub через браузер).
```bash
git push -u origin master
```
- Создана новая ветка и в неё перенесены все предыдущие изменения:
```bash
git checkout -b dev
```
- Далее были внесены правки в код (добавлено движение вперёд) добавлены, закоммичены, запушена новая ветка на GitHub:
```bash
git add .
git commit -m "modified file motors_control.py"
git push --set-upstream origin dev
```
### Заключение: 
C системой git очень удобно работать! 

*Для выполнения этого задания использовал VSCode.*