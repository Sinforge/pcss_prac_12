Этот проект предоставляет функционал для работы с репозиторием 3D моделей, включая поиск, загрузку, хранение и управление правами пользователей. Основные компоненты системы описаны ниже.

# Основные возможности

- Конвертация моделей: Поддержка различных форматов для удобной работы с 3D моделями.
- Поиск моделей: Быстрый и удобный поиск по ключевым словам и категориям.
- Хранение моделей: Надежное и структурированное хранение данных.
- Управление пользователями: Регистрация, авторизация и управление профилями пользователей.
- Управление правами: Настройка доступа к моделям и действиям.
- Уведомления: Оповещения пользователей о завершении загрузок и других событиях.

# Карта проекта
```mermaid
mindmap
  root
    3D Models Repository
      Конвертация моделей
      Поиск моделей
      Хранение моделей
      Управление пользователями
      Управление правами
      Уведомления
```

# Путешествие пользователя
```mermaid
journey

    title Путешествие пользователя в репозитории 3D моделей

    section Регистрация и авторизация

      Пользователь регистрируется: 5: Пользователь

      Подтверждение регистрации: 4: Система

    section Поиск и загрузка модели

      Поиск модели: 4: Пользователь

      Отображение результатов: 4: Система

      Выбор модели для загрузки: 5: Пользователь

    section Загрузка и использование модели

      Загрузка модели: 4: Пользователь

      Уведомление о завершении загрузки: 3: Система
```

# История разработки
```mermaid
gitGraph
    commit
    branch feature/search
    commit
    commit
    branch feature/upload
    commit
    commit
    checkout main
    commit
    merge feature/search
    merge feature/upload
    commit

```

# Квадрант технологий и функций

```mermaid
quadrantChart
    title Quadrant of Features and Technologies
    x-axis Core Technologies --> Supporting Technologies
    y-axis Basic Features --> Advanced Features
    quadrant-1 Key Features
    quadrant-2 Technological Enhancements
    quadrant-3 Core Processes
    quadrant-4 Supporting Systems
    Model Search: [0.2, 0.8]
    Model Upload: [0.3, 0.7]
    User Management: [0.4, 0.5]
    Model Storage: [0.1, 0.6]
    API Gateway: [0.6, 0.4]
    Data Processing: [0.7, 0.3]
    File Storage: [0.8, 0.2]
    Notification System: [0.5, 0.1]
```
