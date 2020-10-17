# Цель
Цель данного проекта - покончить с мучениями связанными с оформлением записок к курсовым работам и проектам в соответствии с требованиями [БГУИР](http://bsuir.by).
Способ достижения цели - создание шаблона структуры проекта для LaTeX с преамбулой, настроенной под соблюдение требований к оформлению записок.
Документ в соответствии с которым настраивается оформление документа: [СТАНДАРТ ПРЕДПРИЯТИЯ. ДИПЛОМНЫЕ ПРОЕКТЫ (РАБОТЫ). ОБЩИЕ ТРЕБОВАНИЯ СТП 01—2013](http://www.bsuir.by/m/12_100229_1_80040.pdf).

## Примеры

В качестве примера рекомендуется использовать оформленную записку к дипломному проекту, расположенному [здесь](https://github.com/egorshulga/new-bsuir-diploma-latex/tree/real_diploma). Там можно посмотреть способ оформления таблиц, картинок, списка литературы и т.д.

## Рекомендуемое окружение

 - [Visual Studio Code](https://code.visualstudio.com)
 - Расширение [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
 - [MiKTeX](https://miktex.org)
 - Для редактирование списка источников bibtex: [JabRef](https://www.jabref.org)

### Установка

Необходимо вручную установить пакет PSCyr для отображения русских шрифтов.

 - Windows: [note/fonts_windows.tex](note/fonts_windows.tex). В [этой инструкции](http://blog.harrix.org/?p=444) вместо шага 10 следует открыть MiKTeX Console, в меню Tasks выбрать пункт Refresh file name database.
 - Linux: [note/fonts_linux.tex](note/fonts_linux.tex)

### Использование

При открытом *.tex* файле в VSCode в боковом меню появляется панель с командами LaTeX.

![latex panel](https://raw.githubusercontent.com/egorshulga/bsuir-coursework-latex/master/note/attachments/latex-workshop-panel.png)

Первая компиляция займёт продолжительное время, потому что MiKTeX будет устанавливать все необходимые пакеты.
