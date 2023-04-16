# 💻 Как оформить дипломную или курсовую работу с помощью LaTeX. Часть 2


<div align="center">
 
![logo](https://user-images.githubusercontent.com/28728575/232098357-dff9a15f-43a4-4113-8b69-579543e32c65.png)

</div>

## Что такое LaTeX?

$\LaTeX$ — это программное обеспечение для набора текста, используемое для создания профессиональных документов, таких как:
- научные статьи,
- книги,
- презентации и другие документы.

[**LaTeX**][latex_wiki] — лучший выбор, если вы являетесь студентом или ученым и хотите написать свою диссертацию или, например,  научную статью. А готовые шаблоны, доступные в открытом доступе, могут значительно облегчить вам задачу.

Репозиторий кода [LaTeX2e][latex2e].
 

## Установка

Для локальной работы необходимо установить [Visual Studio Code][3] и [MiKTeX][4]. Также потребуется установить необходимое расширение для работы — [LaTeX Workshop][latex_ws].

### Видеоинструкции
- Видеоинструкция установки на **Mac** доступна по [ссылке][s].
- Видеоинструкция установки на **Windows** доступна по [ссылке][2].
> К сожалению, видеоинструкция для **Linux** отсутствует. Но процесс установки не отличается от стандартного, поэтому проблем быть не должно. 

## Шаблоны LaTeX

- Статьи:
  - Подготовка статьи в шаблоне [MDPI][mdpi];
  - Подготовка статьи в шаблоне [APL Photonics][apl_photonics];
  - Подготовка статьи в шаблоне [JETP Letters][jetpletters].
- Презентации:
  - Подготовка презентации в шаблоне [VK][vk];
  - [Слайды][borgelt] курса по искусственным нейронным сетям.
<!-- - Дипломные/курсовые/диссертационные работы. -->

Рассмотренные на вебинаре примеры находятся в папке [Examples](./Examples).



<!-- ## Где рисовать

- METAPOST. [Ссылка][metapost] на краткий курс. -->


## 📝 Ссылки и дополнительная литература
- К. В. Воронцов. [LaTeX2e][latex_examples] в примерах. — 2005. — 56 c.
- Добавление ссылок на литературу с помощью [bibtex][bibtex]. Онлайн [конвертер][bib2bib] bibtex в bibitem.



<!-- Mac -->
[s]: https://www.youtube.com/watch?v=CmagZthwhaY&t
<!-- Windows -->
[2]: https://www.youtube.com/watch?v=4lyHIQl4VM8&t
[3]: https://code.visualstudio.com/
[4]: https://miktex.org/
[mdpi]: https://www.mdpi.com/authors/latex
[metapost]: http://mech.math.msu.su/~shvetz/54/inf/metapost/mpshort.pdf
[latex_examples]: http://www.machinelearning.ru/wiki/images/0/06/Voron05latex.pdf
[latex_ws]: https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop
[apl_photonics]: https://aip.scitation.org/app/authors/manuscript
[jetpletters]: http://jetpletters.ru/en/info.shtml
[vk]: https://ru.overleaf.com/latex/templates/vk-presentation-template/wcsvpzskcxrk
[borgelt]: https://borgelt.net/courses.html
[latex2e]: https://github.com/latex3/latex2e
[latex_wiki]: https://en.wikipedia.org/wiki/LaTeX
[bibtex]: https://www.overleaf.com/learn/latex/Bibliography_management_with_bibtex
[bib2bib]: https://asouqi.github.io/bibtex-converter/
