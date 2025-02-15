# Сегментация клиентов с использованием кластеризации
# Описание проекта

В данном проекте проводилась сегментация клиентов на основе их характеристик, таких как возраст, годовой доход и уровень расходов. Сегментация клиентов является важной задачей для бизнеса, так как она позволяет лучше понимать потребности различных групп клиентов и адаптировать маркетинговые стратегии.

# Цели и задачи

Провести сегментацию клиентов, используя три признака одновременно.

Применить алгоритмы кластеризации k-means++ и стандартного k-means, сравнив стабильность результатов с разными значениями random_state.

Провести анализ выбросов в данных и их влияние на результаты кластеризации.

Использовать метод силуэта для оценки качества кластеризации при различных количествах кластеров.

Создать новые признаки (отношение расходов к доходам) и оценить их влияние на результаты кластеризации.

# Работа была выполнена в несколько этапов:

Визуализация данных: Создание 3D-графика, демонстрирующего распределение клиентов по выбранным признакам.

Кластеризация: Выполнение кластеризации клиентов с использованием таких методов, как k-means++ и стандартный k-means, и оценка полученных результатов.

Анализ выбросов: Определение и удаление выбросов, сравнение результатов кластеризации до и после удаления.

Оценка качества кластеризации: Рассмотрение силуэтных коэффициентов для различных значений k, выявление оптимального числа кластеров.

Создание новых признаков: Разработка нового признака, что позволило улучшить результаты кластеризации.

# Используемые технологии

Python: Язык программирования, выбираемый за его мощные библиотеки для анализа данных и машинного обучения.

Pandas: Для работы с данными и их предобработки.

NumPy: Для выполнения числовых вычислений.

scikit-learn: Использована для кластеризации, оценки качества кластеров и стандартизации данных.

Matplotlib и Seaborn: Для визуализации данных и результатов анализа.

# Выбор данного стека технологий был обусловлён:

Широкой популярностью и удобством использования Python для анализа данных.

Мощностью библиотек scikit-learn для выполнения кластеризации.

Наличие графических библиотек, что позволяет легко визуализировать результаты.
