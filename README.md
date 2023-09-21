# Классификация качества вина (Оформление по CRISP-DM)

В этом проекте мы будем классифицировать (предсказывать) качество вина, используя набор данных о качестве красного вина. 

В нем выполняются шаги, основанные на модели CRISP-DM, которая является стандартом для проектов машинного обучения. 
Мы будем использовать следующие модели и сравнивать их производительность:
1. Классификатор Random Forest
2. Классификатор Support Vector
3. Классификатор K-Neighbors

### 1. Business Understanding
Набор данных был загружен из репозитория машинного обучения UCI.

Эти два набора данных относятся к красному и белому вариантам португальского вина "Винью Верде". Из-за конфиденциальности и логистических проблем доступны только физико-химические (входные данные) и сенсорные (выходные данные) переменные (например, отсутствуют данные о сортах винограда, марке вина, отпускной цене вина и т.д.).

#### Информация об атрибутах:
Входные переменные (на основе физико-химических тестов):
1. fixed acidity -> фиксированная кислотность
2. volatile acidity -> летучая кислотность
3. citric acid -> лимонная кислота
4. residual sugar -> остаточный сахар
5. chlorides -> хлориды
6. free sulfur dioxide -> свободный диоксид серы
7. total sulfur dioxide -> общий диоксид серы
8. density -> плотность
9. рН
10. sulphates -> сульфаты
11. alcohol -> алкоголь

Выходная переменная (на основе сенсорных данных):
12. quality -> качество (оценка от 0 до 10)


### Другие разделы в Jupiter NoteBook
notebooks/1.0-asvorobyev-crispdm_wine.ipynb