## Исследование новой системы поиска анкет в дейтинговом приложении через интерпритацию результатов А/B теста

**Для проверки работы нового алгоритма для поиска наиболее подходящих анкет был проведен АБ-тест, в рамках которого все пользователи приложения были разделены на две группы. Пользователи в группе с номером 0 пользовались приложением со старым алгоритмом. Все пользователи в группе 1 пользовались приложением с новым алгоритмом для поиска анкет.**  

### ЦЕЛЬ ПРОЕКТА: 
**Оценить, правда ли, что новый алгоритм улучшил качество сервиса и ответить на вопрос, стоит ли включать новую систему поиска анкет на всех пользователей.**  

**Анализ проведен на Python**     
**Для работы над проектом были использованы библиотеки:**     
**pandas, seaborn, matplotlib.pyplot, scipy.stats, pingouin, numpy**  
**Выводы в файле A_B_test_2.ipynb** 

### ЭТАПЫ:

**1. Прочитала файл и сделала предобработку данных** 

**2. Сделала статистический анализ следующих метрик:**  
**- Соотношение мэтчей и не мэтчей в группах**  
**- Среднее число анкет на каждого пользователя**  
**- Среднее число мэтчей на каждого пользователя**  

**3. Сделала аналитическое заключение с ответом на вопрос, стоит ли включать системы поиска анкет на всех пользователей.**  

### РЕЗУЛЬТАТ:

**В ходе анализа выявила, что количество уникальных пользователей в обоих группах одинаковое, a количество анкет в приложении с новым алгоритмом для поиска анкет ВЫРОСЛО. Новый алгоритм улучшил качество сервиса, пользователи видят в приложении наиболее подходящие им анкеты, ставят друг другу больше лайков, получая мэтч, тем самым у них появляется больше возможности познакомиться, в чем и состоит цель приложения для онлайн-знакомств. Рекомендовала раскатать новую систему поиска на всех пользователей приложения.**


