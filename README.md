
- Аргументы запуска. Собираем фикстуры, марки, и другую полезную информацию для отладки
  - --co
  - -k
  - -m
  - --markers
  - --fixtures
  - --durations=10
  - -l (--showlocals)
  - --setup-plan

- Марки. Пропускаем тесты правильно
  - skip
  - xfail
  - uxefixtures

- Параметризация. На тесте, на фикстуре. Переопределение параметров
  - pytest.mark.parametrize на тесте. Использование нескольких параметров
  - параметризация фикстуры. 
  - indirect параметризация