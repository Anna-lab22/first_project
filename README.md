# Title
### Title3
My first git repo  😻  
paragraph  
List1:
* point1
* point2

*tekst to light*  **tekst to light**  ***tekst to light*** 

_tekst to light_  __tekst to light__ ___tekst to light___ 
---
***
___
`some code`
```sql
SELECT distinct
	Company,
    UnionSiteId,
   InventLocationId,
    SiteId,
    case when 
    COUNT(DISTINCT SiteId) OVER(PARTITION BY UnionSiteId) >1 then 1 else 0 end  AS Multi_Union_SiteId_Flag
FROM core_ax.invent_location
```
\***
> Life is movement

#### References:
* <https://ya.ru/>
* [ya_link](https://ya.ru/ "Go to ya")

:closed_umbrella:

### To-do:
- [ ] eat food
  - [ ] breakfast
  - [x] lunch
  - [ ] dinner
- [x] drink water

#### Таблицы
<!-- Вы можете создавать таблицы, 
чтобы представить данные в структурированном виде: -->

| Имя         | Возраст | Город               |
|:-------------|:---------:|---------------------:|
| Алиса       | 25      | Москва              |
| Боб         | 30      | Санкт-Петербург     |
| Иван        | 35      | Новосибирск         |
