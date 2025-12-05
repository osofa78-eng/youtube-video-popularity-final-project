# youtube-video-popularity-final-project
Репозиторий для итогового проекта по курсу "Введение Data Science".
# Описание
Создание модели для предсказания популярности видео на ютуб, определение ключевых метрик, влияющих на популярность.
# Данные
https://www.kaggle.com/datasets/datasnaek/youtube-new
dataset по статистике популярности видео на ютуб.
# Цель 
Разработать модель машинного обучения (MLM) для прогнозирования количества просмотров видео на YouTube.
# Используемые технологии
pandas, numpy, sklearn, matplotlib, seaborn, keras, tensorflow
# Pipeline проекта
* Загрузка данных
* Очистка
* EDA
* Baseline модель
* Улучшение
* Выводы
# Результаты
Основные метрики (по порядку значимости): likes, comments, categories, dislikes
# Примеры визуализаций 
> зависимость просмотров от категорий
<img width="1189" height="489" alt="image" src="https://github.com/user-attachments/assets/ecdd4ead-3dc4-469e-9408-9eb9691d3e8e" />

> корреляция между метриками видео
<img width="588" height="526" alt="image" src="https://github.com/user-attachments/assets/465d2d85-b36c-4aa7-b202-f8c53750d1e0" />

> предсказанные/истинные просмотры, обучение модели
<img width="1189" height="390" alt="image" src="https://github.com/user-attachments/assets/23d77a42-cc82-4c14-8548-f6f0f6493120" />

# Выводы
Создана рабочая модель-прототип, успешно предсказывающая популярность видео (R²=0.75). Лайки и активность в комментариях — самые сильные ранние сигналы будущего успеха видео.

