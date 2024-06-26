### Тестовое задание для PHP

Разработка интеллектуальной системы рекомендаций для книг.

*Уровень сложности: **Простой + Средний***

*Ожидаемое время выполнения задания: **до 3-х дней***

### Описание задачи

Ваша задача — создать интеллектуальную систему рекомендаций для книг. Система должна рекомендовать книги пользователям на основе их предпочтений и поведения, а также учитывать нестандартные условия и скрытые связи между книгами и пользователями.

### Условия задачи

- Задача должна быть решена на PHP без использования PHP-фреймворков.
- Допускается использование менеджера пакетов composer.
- Запрещается использовать ORM для базы данных, решение задачи должно быть на PHP PDO.


### Основная задача

1. **Составление данных**:
    - Вам нужно собрать и обработать данные о пользователях и книгах. Создайте свой пример данных, который может быть и в каком формате будут эти данные.
    - Данные о книгах включают такие параметры, как название, автор, жанр, год издания.
    - Данные о пользователях включают их историю чтения, оценки книг, предпочтения по жанрам и авторам.

2. **Получение/парсинг данных**:
    - Теперь, после того, как у вас есть формат данных, вам нужно получить эти данные.
    - Реализуйте код получения/парсинга данных.
   
3. **Алгоритм рекомендаций**:
    - Реализуйте алгоритм, который будет рекомендовать книги пользователям на основе их предпочтений: истории чтения и их оценок.
    - Создайте условие: Если пользователь оценил книгу ниже 3 баллов, не предлагать книги того же автора.

### Дополнительная задача
***(реализовывать её не обязательно, но даст дополнительные баллы при оценке)***
1. **Усовершенствованный алгоритм рекомендаций**:
    - Учитывайте скрытые связи между пользователями и книгами (например, пользователи с похожими вкусами, книги с общими авторами или жанрами).
    - Если у книги низкий рейтинг у нескольких пользователей, снижать её приоритет в рекомендациях. 
    - Если пользователь не читал книги в течение долгого времени, предлагать популярные книги для возвращения интереса.
2. **Аналитика рекомендаций**
    - Создайте функцию для генерации отчетов о рекомендациях и их успешности (Формат на ваше усмотрение).
            

### Чек-лист выполнения задания:
##### Основное задание:
- [ ] Выбран формат данных.
- [ ] Данные о книгах содержат: название, автор, жанр, год издания.
- [ ] Данные о пользователях содержат: историю чтения, оценки книг, предпочтения по жанрам и авторам.
- [ ] Функция парсинга данных корректно обрабатывает данные о пользователях и книгах.
- [ ] Алгоритм рекомендаций учитывает предпочтения, историю чтения и оценку.
- [ ] Алгоритм рекомендаций учитывает оценку книги ниже 3 баллов.
##### Дополнительное задание:
- [ ] Алгоритм рекомендаций учитывает скрытые связи между пользователями и книгами.
- [ ] Алгоритм рекомендаций учитывает низкий рейтинг у нескольких пользователей и снижает приоритет в рекомендациях.
- [ ] Алгоритм рекомендаций предлагает пользователю популярные книги, если пользователь давно ничего не читал. 
- [ ] Функция генерации отчетности о рекомендациях.


## Отправка тестового задания
- Создайте новый репозиторий в Github.
- Загрузите в созданный репозиторий – готовый код выполненного задания.
- Направьте ссылку на репозиторий нашему HR.
- Ожидайте обратной связи, мы обязательно её дадим.
- Обычно, анализ выполнения тестовго задания занимает 1-2 дня с момента отправки ссылки на репозиторий нашему HR.