# CHANGELOG

## v1.1.1

- Камера теперь следит за центром юнита, не учитывая направление зрения
- Снова можно зумить на всю карту
- Исправлен режим повтора (`--repeat`) приложения

## v1.1.0

- Антиалиасинг теперь выключен по умолчанию (улучшенная производительность визуализатора и фикс падения приложения для некоторых пользователей)
- Исправлено выравнивание текста (`PlacedText.alignment`) в отладочном интерфейсе
- Исправлен баг - лут (и другие сущности) были невидимы под юнитами, но в вне сектора зрения
- выделение игрока в таблице очков, за чьим юнитом следит камера
- Добавлены опции приложения `--fullscreen`, `--window-width/--window-height`, `--start-paused`
- Новые версии клиентов теперь также получают номер отображаемого тика в методе `debug_update`
- Автоматическое слежение за юнитом на старте и переключение при смерти текущего отслеживаемого юнита
- Клик по игроку в таблице очков теперь переводит слежение камеры на следующего юнита этого игрока
