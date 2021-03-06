# Проект

В репозитории есть 3 папки:

`data` - геномы пяти выбранных мной организмов рода Paracoccus

`alignments` - все белковые выравнивания для выбранных кластеров

`coordinates` - предсказания участков Z-DNA для 5 выбранных геномов

Ссылка на колаб: https://colab.research.google.com/drive/1eWhnvPpf0wQ-EaBV-70bckaTlzHpvpBk?usp=sharing

Таксон: `Alphaproteobacteria`

Вид: `Paracoccus` 

# Таблица аннотированных генов

| **Вид** | **Кол-во хромосом** | **Длина** | **Кол-во анотированных генов** | **Длина всех генов** | **Доля анотированных генов** | **Кол-во предсказанных участков z-dna** | **Кол-во участков с zh-score >500 и их общая длина** |
| ------------- | ------------- |--------------------| ---- | --- | --- | --- | ------ |
| Paracoccus mutanolyticus| 1 | 3592357 | 3047 | 2003651 | 55.78% | 3592357 | 60421; 586328  |
| Paracoccus pantotrophus| 2 (+2 плазмиды) | 3774098 (2248278(хр.1) + 1525820(хр.2) + 99949(пл.1) + 535332(пл.2) | 4210 | 3885491 | 88.12% | 4409379 | 57049; 550722 |
| Paracoccus liaowanqingii| 1 (+10 плазмид) | 3271357 + 310431(пл.1) + 244326(пл.2) + 255051(пл.3) + 260425(пл.4) + 216963(пл.5) + 170285(пл.6) + 82441(пл.7) + 83454(пл.8) + 13537(пл.9) + 16958(пл.10) | 4528 | 4181975 | 84.91% | 4925228 | 59765; 583944 |
| Paracoccus suum| 1 | 3250998 | 3149 | 2926464 | 90.02% | 3250998 | 57259; 556558 |
| Paracoccus yeei| 1 (+6 плазмид)  | 3588087 (хромосома) + 327671(пл.1) + 225271(пл.2) + 167927(пл.3) + 172023(пл.4) + 114679(пл.5) + 24567(пл.6)  | 4393 | 4111523 | 88.97% | 4620225 | 65631; 635310  |

Координаты участков Z-DNA для 5 выбранных геномов находятся в папке `coordinates` (1 столбец - начало участка, 2 - конец, 3 - zh-score)

# Гистограммы значений ZH-score

![image](https://user-images.githubusercontent.com/93254228/173683903-e8f3886d-2498-4871-81b8-f68eb5c8ca10.png)
![image](https://user-images.githubusercontent.com/93254228/173683933-3e71e518-2734-473f-96da-964854543299.png)

![image](https://user-images.githubusercontent.com/93254228/173683956-6cde75b2-a145-405f-89cb-2d79a7db8c05.png)
![image](https://user-images.githubusercontent.com/93254228/173683991-2daf431a-bea5-4c4f-b687-71dc31f68b31.png)

![image](https://user-images.githubusercontent.com/93254228/173684007-4e828f08-cf0c-457f-ac26-539f375ef1eb.png)

# Распределение участков Z-ДНК

![image](https://user-images.githubusercontent.com/93254228/173684159-0d79d8f5-6091-4cbe-8582-23695b6fa923.png)

# Кластеры белков

![image](https://user-images.githubusercontent.com/93254228/173684337-9fc68996-442d-4c90-9b4d-af0fb986ed63.png)
Всего 3756 кластеров.

# Информация о кластерах

| **Номер кластера** | **Кол-во генов** | **Названия генов** | **Функция генов** | **Z-ДНК и их расположение** | **Z-DNA score** | 
| ------------- | ------------- |--------------------| ---- | --- | ----- |
| Cluster 1| 5| WP_099648568.1,	WP_080621616.1,	WP_114076729.1,	WP_228461422.1,	WP_167521775.1 |zinc-binding dehydrogenase | 21	 (5 в промоторе) | См. ниже | 
| Cluster 2| 5 | WP_036761720.1, WP_112887316.1,	WP_241963421.1,	WP_135313141.1,	WP_208852026.1 | YigZ family protein | 9 (5 в промоторе) | См. ниже | 
| Cluster 3| 5 | WP_099649861.1,	WP_028717671.1,	WP_241963419.1,	WP_135311757.1,	WP_024845674.1 | DUF1190 domain-containing protein | 28 (5 в промоторе) | См. ниже |
| Cluster 4| 5 | WP_099648227.1,	WP_028718530.1,	WP_114075728.1,	WP_135313748.1,	WP_024844026.1 | protein-L-isoaspartate O-methyltransferase |  20	 (5 в промоторе) | См. ниже |
| Cluster 5| 5 | WP_028718016.1,	WP_028718016.1,	WP_114076211.1,	WP_135312084.1,	WP_024845795.1 | alpha/beta hydrolase | 17 (5 в промоторе) | См. ниже |
| Cluster 6| 5 | WP_028719775.1,	WP_028719775.1,	WP_114076144.1,	WP_135312821.1,	WP_024843127.1 | DUF465 domain-containing protein | 9 (5 в промоторе) | См. ниже |
| Cluster 7| 5 | WP_028720152.1,	WP_028720152.1,	WP_114076332.1,	WP_135312464.1,	WP_024843319.1 | peptidylprolyl isomerase | 19 (5 в промоторе) | См. ниже |
| Cluster 8| 5 | WP_028718321.1,	WP_080621994.1,	WP_114075408.1,	WP_135312130.1,	WP_024843352.1 | heme o synthase | 22	 (5 в промоторе) | См. ниже |

# Множественное белковое выравнивание

Результаты выравнивания для восьми кластеров см. в папке `alignments`

# Визуализация расположения участков Z-DNA

Было выбрано 8 кластеров (порядок в таблице). Для каждого гена в одном кластере приведены значения Z-DNA score:

![image](https://user-images.githubusercontent.com/93254228/173687114-3bf9ddcf-c20d-4787-adfa-c03e5128f910.png)

![image](https://user-images.githubusercontent.com/93254228/173687129-767f0150-de45-4887-b3cc-dcd57e65080c.png)

![image](https://user-images.githubusercontent.com/93254228/173687158-b6015306-9046-4496-8ecf-7fa62e924aa9.png)

![image](https://user-images.githubusercontent.com/93254228/173687188-245e9a7e-7653-4728-8165-302ad7192019.png)

![image](https://user-images.githubusercontent.com/93254228/173687207-1074a244-e2bb-4d8b-b975-9cce0d4057db.png)

![image](https://user-images.githubusercontent.com/93254228/173687238-5a524d77-e517-47b5-8dc6-c3d563c3d8ab.png)

![image](https://user-images.githubusercontent.com/93254228/173687269-79033ad4-4773-491e-92d5-6d5792dc6fd8.png)

![image](https://user-images.githubusercontent.com/93254228/173687394-ce087123-5fac-40aa-8151-c43ff1c99e38.png)

Файл ipynb с кодом также прилагается.
