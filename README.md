# Learning-Cython

Изучаю Cython на случай, когда он (вдруг) пригодится в Python.

## Содержание

- [Введение](#введение)
- [Подготовка окружения](#подготовка-окружения)
- [Ссылки](#ссылки)

### Введение

Cython - это язык программирования, заявленный как надмножество языка Python. А ещё Cython - это компилятор как для языка Cython, так и Python. На языке Cython можно писать Си-расширения, которые можно использовать в Python (CPython) среде.

Проект зародился на основе моих заметок по [изучению Python пакетов](https://github.com/stankudrow/Learning-Python-Packaging), когда во [второй главе](https://github.com/stankudrow/Learning-Python-Packaging/tree/main/notes/ch02) я решил ввести Cython чтобы посмотреть что из этого выйдет.

Заметки выстроены в духе "Cython в действии на примерах". Также можете посмотреть [Jupyter тетрадку](https://github.com/stankudrow/Learning-Python-Packaging/blob/main/notes/ch02/extra/cython.ipynb), с которой началось вот это всё.

### Подготовка окружения

- Почитать за [установку Cython](https://cython.readthedocs.io/en/latest/src/quickstart/install.html) на вашей системе.
- `uv venv` - создание виртуального окружения (версия подсасывается из файла [.python-version](.python-version).
- `uv pip install -r requirements.txt` - установить зависимости в окружение из файла [requirements.txt](requirements.txt).
- `python3 -m ipykernel install --user --name=cy_notes --display-name="Cython Notes"` - создать IPython ядро, нацеленное на Python из виртуального окружения, которое можно использовать в Jupyter Notebook.
- `cd notes && jupyter notebook` - запускаем из директории [notes](./notes) и развлекаемся из Jupyter интерфейса.

Спасибо моей [допзаметке](https://github.com/stankudrow/Learning-Python-Packaging/blob/main/notes/ch02/extra/enote.md) за уже пройденные опыт и страдания (возможно она уже дополнена или даже удалена).

### Ссылки

- Cython:

  - [Проект](https://cython.org/)
  - [Документация](https://cython.readthedocs.io/en/latest/index.html)
  - [Вики](https://github.com/cython/cython/wiki)
  - [ЧАВО](https://cython.readthedocs.io/en/latest/src/userguide/faq.html)

- [Jupyter](https://jupyter.org/) - интерфейс, в котором были написаны эти заметки.
- [UV](https://docs.astral.sh/uv/) - больше чем просто проектный менеджер.
