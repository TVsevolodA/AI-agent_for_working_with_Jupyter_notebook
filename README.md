# AI-agent_for_working_with_Jupyter_notebook
Репозиторий по реализации собственного ии-агента, работающего с блокнотами Jupyter. Проект основан на библиотеках LangChain и LangGraph.

## Схема агента в виде графа
![Схема агента](https://github.com/TVsevolodA/AI-agent_for_working_with_Jupyter_notebook/blob/main/agent_scheme.png)

## Инструменты агента
* Возможность производить CRUD операции с ячейками блокнота;
* Запуск/остановка ядра Jupyter (для выполнения ячеек блокнота);
* Создание/открытие блокнота из файловой системы;
* Поиск информации в сети Интернет;

## Память
Для агента реализована краткосрочная и долгосрочная память, для лучшего понимания контекста.
В качестве базы данных используется [![General badge](https://img.shields.io/badge/ChromaDB-VectorDB-orange)](https://docs.trychroma.com/)
На ее основе реализовано собственое хранилище BaseStore.
