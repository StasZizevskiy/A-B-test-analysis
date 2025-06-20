# AB_test_analysis
Анализ A/B теста 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 	![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) 	![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)	![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
Исходные данные: 
Есть сервис, имеющий функционал социальной сети, в которой можно писать сообщения и листать ленту новостей. 
Проведён A/B тест. Эксперимент проходил с 2025-01-31 по 2025-02-06 включительно. Для эксперимента были задействованы 2 группы. В группе 2 был использован один из новых алгоритмов рекомендации постов, группа 1 использовалась в качестве контрольной. Основная гипотеза заключается в том, что новый алгоритм во 2-й группе приведет к увеличению CTR. 

Основная задача: проанализировать данные А/B-теста. 

Результаты:
1. Сравнил CTR в группах при помощи t-теста, Пуассоновский бутстрепа, теста Манна-Уитни, t-тест на сглаженном ctr (α=5) а также t-теста и теста Манна-Уитни поверх бакетного преобразования.
2. Проанализировал результаты тестов.
3. Описал потенциальную ситуацию, когда возможно подобное изменение.
4. Написал рекомендацию, раскатывать новый алгоритм на всех новых пользователей или все-таки не стоит. 
