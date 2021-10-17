# The task is to prepare data for a project to track the impact of students' living conditions on their performance in mathematics.

The task for module 2:

UNICEF has invited you to participate in one of the projects - an international unit of the United Nations, whose mission is to improve the well-being of children around the world.

The essence of the project is to track the impact of living conditions of students aged 15 to 22 on their performance in mathematics to identify students at an early stage at risk.

This can be done with a model that predicts the results of the state exam in mathematics for each student in the school. (Here it is, the power of ML!). To determine the parameters of the future model, conduct an exploratory analysis of the data and draw up a report on its results.

Variables that the dataset contains:
1. school - abbreviation of the school in which the student is studying
2. sex - the gender of the student ('F' - female, 'M' - male)
3. age - student's age (from 15 to 22)
4. address - the type of student's address ('U' - city, 'R' - outside the city)
5. famsize - family size ('LE3' <= 3, 'GT3'> 3)
6. Pstatus - the status of parents' joint housing ('T' - live together 'A' - separately)
7. Medu - mother's education (0 - no, 1 - 4 grades, 2 - 5-9 grades, 3 - specialized secondary or 11 grades, 4 - higher)
8. Fedu - father's education (0 - no, 1 - 4 grades, 2 - 5-9 grades, 3 - specialized secondary or 11 grades, 4 - higher)
9. Mjob - mother's work ('teacher' - teacher, 'health' - health sector, 'services' - state service, 'at_home' - does not work, 'other' - other)
10. Fjob - father's work ('teacher' - teacher, 'health' - health care, 'services' - state service, 'at_home' - doesn't work, 'other' - other)
11. reason - reason for choosing a school ('home' - proximity to home, 'reputation' - school reputation, 'course' - educational program, 'other' - other)
12. guardian - guardian ('mother' - mother, 'father' - father, 'other' - other)
13. traveltime - travel time to school (1 - <15 min., 2 - 15-30 min., 3 - 30-60 min., 4 -> 60 min.)
14. studytime - study time outside of school per week (1 - <2 hours, 2 - 2-5 hours, 3 - 5-10 hours, 4 -> 10 hours)
15. failures - the number of extracurricular failures (n, if 1 <= n <= 3, otherwise 0)
16. schoolsup - additional educational support (yes or no)
17. famsup - family educational support (yes or no)
18. paid - additional paid lessons in mathematics (yes or no)
19. activities - additional extracurricular activities (yes or no)
20. nursery - attended kindergarten (yes or no)
21. higher - wants to get higher education (yes or no)
22. internet - the presence of the Internet at home (yes or no)
23. romantic - in a romantic relationship (yes or no)
24. famrel - family relationships (from 1 - very bad to 5 - very good)
25. freetime - free time after school (from 1 - very little to 5 - very much)
26. goout - spending time with friends (from 1 - very little to 5 - a lot)
27. health - current state of health (from 1 - very bad to 5 - very good)
28. absences - number of missed classes
29. score - points on the state exam in mathematics

# Задача подготовить данные для проекта отслеживания влияние условий жизни учащихся на их успеваемость по математике.

Задание:

Вас пригласили поучаствовать в одном из проектов UNICEF — международного подразделения ООН, чья миссия состоит в повышении уровня благополучия детей по всему миру. 

Суть проекта — отследить влияние условий жизни учащихся в возрасте от 15 до 22 лет на их успеваемость по математике, чтобы на ранней стадии выявлять студентов, находящихся в группе риска.

И сделать это можно с помощью модели, которая предсказывала бы результаты госэкзамена по математике для каждого ученика школы (вот она, сила ML!). Чтобы определиться с параметрами будущей модели, проведите разведывательный анализ данных и составьте отчёт по его результатам. 

Переменные, которые содержит датасет:
1. school — аббревиатура школы, в которой учится ученик
2. sex — пол ученика ('F' - женский, 'M' - мужской)
3. age — возраст ученика (от 15 до 22)
4. address — тип адреса ученика ('U' - городской, 'R' - за городом)
5. famsize — размер семьи('LE3' <= 3, 'GT3' >3)
6. Pstatus — статус совместного жилья родителей ('T' - живут вместе 'A' - раздельно)
7. Medu — образование матери (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее)
8. Fedu — образование отца (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее)
9. Mjob — работа матери ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое)
10. Fjob — работа отца ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое)
11. reason — причина выбора школы ('home' - близость к дому, 'reputation' - репутация школы, 'course' - образовательная программа, 'other' - другое)
12. guardian — опекун ('mother' - мать, 'father' - отец, 'other' - другое)
13. traveltime — время в пути до школы (1 - <15 мин., 2 - 15-30 мин., 3 - 30-60 мин., 4 - >60 мин.)
14. studytime — время на учёбу помимо школы в неделю (1 - <2 часов, 2 - 2-5 часов, 3 - 5-10 часов, 4 - >10 часов)
15. failures — количество внеучебных неудач (n, если 1<=n<=3, иначе 0)
16. schoolsup — дополнительная образовательная поддержка (yes или no)
17. famsup — семейная образовательная поддержка (yes или no)
18. paid — дополнительные платные занятия по математике (yes или no)
19. activities — дополнительные внеучебные занятия (yes или no)
20. nursery — посещал детский сад (yes или no)
21. higher — хочет получить высшее образование (yes или no)
22. internet — наличие интернета дома (yes или no)
23. romantic — в романтических отношениях (yes или no)
24. famrel — семейные отношения (от 1 - очень плохо до 5 - очень хорошо)
25. freetime — свободное время после школы (от 1 - очень мало до 5 - очень мого)
26. goout — проведение времени с друзьями (от 1 - очень мало до 5 - очень много)
27. health — текущее состояние здоровья (от 1 - очень плохо до 5 - очень хорошо)
28. absences — количество пропущенных занятий
29. score — баллы по госэкзамену по математике
