# ST-Lesson_09

Software-Testing.Ru LMS<br />
Группа: sel-1<br />
<h2>Задание 9. Проверить сортировку стран и геозон в админке</h2>

**Сделайте сценарии, которые проверяют сортировку стран и геозон (штатов) в учебном приложении litecart.**

1. на странице http://localhost/litecart/admin/?app=countries&doc=countries
  * проверить, что страны расположены в алфавитном порядке
  * для тех стран, у которых количество зон отлично от нуля -- открыть страницу этой страны и там проверить, что зоны расположены в алфавитном порядке

2. на странице http://localhost/litecart/admin/?app=geo_zones&doc=geo_zones
  * зайти в каждую из стран и проверить, что зоны расположены в алфавитном порядке
