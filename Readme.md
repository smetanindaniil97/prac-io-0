  # Задание:

  1. Необходимо написать функцию nash_equilibrium(a), которая принимает матрицу выигрыша и возвращает значение игры и оптимальные стратегии первого и второго игроков.
  2. Проиллюстрировать работу вашего кода путем решения нескольких игр и визуализации спектров оптимальных стратегий игроков в Jupyter.
     В частности, нужно привести игры, в которых:
     1. спектр оптимальной стратегии состоит из одной точки (т.е. существует равновесие Нэша в чистых стратегиях),
     2. спектр оптимальной стратегии неполон (т.е. некоторые чистые стратегии не используются),
     3. спектр оптимальной стратегии полон.
  3. Оформить ваше решение в виде пакета.
  4. Написать unit-тесты для функции nash_equilibrium(a).
  
  # Решение
  
  1. Создана функцию nash_equilibrium(A,v), которая получает на вход матрицу антагонистической игры и решает поставленную задачу путем сведения ее к паре двойственных задач линейного программирования.
  2. Визуализироввана оптимальная стратегия игроков
  
  # Запуск программы:
  
   В командной строке Windows 10 пишем: cd путь-к-папке-с-прогарммой
   Далее пишем: jupyter-notebook
   Открываем файл с названием nash.ipynb
   
   # Необходимые ПО
   
   Windows 10
   
   # Необходимые программы(библиотеки)
   
   Необходимо установить программу Anaconda3, которая содержит минимально необходимый набор библиотек.
   
   ## Используемые библиотеки:
   1) numpy
   2) scipy
   3) matplotlib
   4) unittest
   
   ## Программы:
   Python 3.6
   Anaconda3
   jupyter-notebbok
   
   # Участники:
   Павлов Антон Сергеевич (311 группа):
   1) Разработка алгоритма выполнения программы
   2) Программная реализация задачи(процедуры nash_equilibrium)
   3) Реализация unit-тестов
   4) Подготовка отчетности
   
   Сметанин Даниил Алексеевич (311 группа):
   1) Разработка алгоритма выполнения программы
   2) Графическая демонстрация
   3) Оформления задания в виде пакетов
   4) Подоготовка файла Readme
