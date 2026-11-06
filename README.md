# Learning-Cython

Изучаю Cython (Сайтон) - вдруг пригодится.

Проект зародился на основе моих заметок по [изучению Python (Пайтон) пакетов](https://github.com/stankudrow/Learning-Python-Packaging).

## Содержание

- [Введение](#введение)
- [Подготовка окружения](#подготовка-окружения)
- [Ссылки](#ссылки)

### Введение

Cython - это и язык программирования, и компилятор. Cython [заявлен](https://cython.readthedocs.io/en/latest/src/quickstart/overview.html) языком, стремящимся быть надмножеством языка Python, с помощью которого можно писать Си-расширения без Си-болей.

### Подготовка окружения

Прежде следует почитать за [установку Cython](https://cython.readthedocs.io/en/latest/src/quickstart/install.html) на Вашей системе.

Возможные подготовительные шаги:
- `uv venv` - создание виртуального окружения (версия подсасывается из файла [.python-version](.python-version);
- `uv pip install -r requirements.txt` - установить зависимости в окружение из файла [requirements.txt](requirements.txt);
- `python3 -m ipykernel install --user --name=cy_notes --display-name="Cython Notes"` - создать IPython ядро, нацеленное на Python из виртуального окружения, которое можно использовать в Jupyter Notebook;
- `jupyter notebook` - запуститить Jupyter (Джупитер, или Юпитер) сервер если требуется.

### Ссылки

- Cython:

  - [Проект](https://cython.org/)
  - [Документация](https://cython.readthedocs.io/en/latest/index.html)
  - [Вики](https://github.com/cython/cython/wiki)
  - [ЧАВО](https://cython.readthedocs.io/en/latest/src/userguide/faq.html)

- Программирование и Си:
  - [Введение в профессию - Столяров А.В.](http://www.stolyarov.info/books/programming_intro)

- [Jupyter](https://jupyter.org/) - интерфейс, в котором были написаны эти заметки.
- [UV](https://docs.astral.sh/uv/) - больше чем просто проектный менеджер.
