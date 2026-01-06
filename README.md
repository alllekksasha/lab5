# Student Grade Tracker - Lab 5: Agile & Scrum

Student Grade Tracker - Python приложение для учителей 11 классов. Учет оценок, статистика успеваемости, отчеты Excel/PNG. Реализован полный Scrum-процесс через GitHub Issues. Технологии: pandas, matplotlib, CLI. **Sprint 1:** 13 Story Points, 3/5 задач завершены.

## Sprint Review

**Завершенные задачи:**
- #1 Setup structure - папки + requirements.txt созданы [PR #1]
- #2 Add student/grade - JSON CRUD, 20 тестовых записей [PR #2]  
- #4 View grades - таблица + средний балл [PR #3]

**Доставлено по итогу спринта:**
- Рабочий трекер оценок 11А/11Б классов
- students.json + grades.json (20 учеников, 50 оценок)
- Табличный просмотр по предметам + средние баллы

**Не завершенные задачи:**
- #3 Statistics - не успели matplotlib графики (blocked CI)
- #5 Excel export - зависит от статистики

## Sprint Retrospective

**Что прошло хорошо:**
- Четкие DoD ускорили проверку готовности
- High-priority задачи закрыты первыми  
- Быстрое создание структуры проекта

**Что пошло не так:**
- Story Points занижены для #3 (3SP → реально 8SP)
- matplotlib не работает в GitHub Actions
- Не учли зависимость #5 от #3

**Что улучшить в следующем спринте:**
- Spike-задачи для новых библиотек (matplotlib)
- Dependency mapping между задачами
- Daily standup комментарии в issues
