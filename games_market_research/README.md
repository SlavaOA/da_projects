# Исследование рынка видеоигр


## Данные

В наличии были исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). 

### Описание данных.

- Name – название игры;
- Platform – платформа;
- Genre – жанр игры;
- NA_sales – продажи в Северной Америки (миллионы проданных копий);
- EU_sales - продажи в Европе (миллионы проданных копий);
- JP_sales - продажи в Японии (миллионы проданных копий);
- Other_sales – продажи игр в других странах (миллионы проданных копий);
- Critic_Score – оценка критиков (максимум 100);
- User_Score – оценка пользователей (максимум 10);
- Rating – рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## Задача

Для формирования плана продаж на предстоящий год необходимо подготовить данные для анализа, провести исследователький анализ данных - построить и описать графики, определить актуальный период рынка, составить портрет пользователя для каждого региона.

Проверить гипотезы:
- Средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
- Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.

## Используемые библиотеки
*pandas, numpy, scipy, plotly.express*
