---
title: Спаси София
tags: exercise, save sofia, urban environment, project architecture
---

# Задача "Спаси София"

Постоянно п(р)опадаме на нередности в градската среда около нас - разбити улици и тротоари, криви и разтърсващи шахти, нераглементирани сметища, натрошени пейки, изтърбушени кошчета, бетонирани дървета, "кални точки" и прочие. Основната причина за това е както гаменщината на определени индивиди от обществото, така и крайното нехайство на институциите да поддържат сътвореното.

Важна роля в контрола на изпълнението на поддръжката на градската среда имат самите граждани - къде, кога и какъв проблем са констатирали. Всеки надлежно описан и достигнал до съответната институция проблем обикновено бива отстраняван. Нека създадем такъв проект с QGIS!


## Задание

Да проектираме QGIS проект и база данни, в която могат да се записват нередности в градската среда по райони в София.

Представете си, че вие сте отговорник за събиране на данни за нередности в градската среда на общината. Вашето задължение е тази информация да бъде събрана и подредена по подходящ начин, за да послужи за определяне на приоритетните проекти на администрацията. Трябва да проектирате структурата на базата данни и проекта с вашия екип. Нахвърляли сте записки от срещите до момента:

- имате бюджет да наемете дузина студенти "доносници", които са запознати, но не и професионалисти в ГИС, които да обикалят специално отредените ми индивидуални райони, за които да откриват и попълват нередности;
- проблемите се делят на различни категории (шахти, сметища, пейки и т.н.);
- един проблем може да трябва да бъде описан **точно веднъж**;
- един проблем може да бъде проверяван **повече от веднъж** от различни "доносници";
- необходимо е снимково доказателство за проблема;
- важно е проектът да стартира поне за централните райони на общината;
- на втора фаза ще активирате данните да се попълват от QField, но финансирането в момента е достатъчно само за създаване на QGIS проект.


## Основна цел

Осмисляне на основните стъпки при проектиране на географска база данни и превръщането ѝ в удобна за работа за хора, които не са ГИС професионалисти.


## Цели

- проектиране на цялостен QGIS проект и географска база данни от нулата:
- изграждане на чувство за избиране на адекватни геометрия и атрибути на слоевете за попълване според конкретното приложение на проекта;
- изграждане на чувство за подходящо определяне и настройка на адекватните слоеве за картна основа;
- добиване на умения за изготване на подходящи формуляри за удобно попълване на обекти;
- запознаване с релациите в QGIS (връзка едно към много);

## Препоръки

- внимателно да се премисли какви слоеве и кои какви данни (атрибути) биха послужили на общината за справяне с проблема; избор на подходяща геометрия;
- проектът трябва да съдържа поне три векторни слоя, като поне два са с геометрия;
- слой с границите на районите ще помогне на "доносниците" да знаят докъде да следят за нередности;
- векторните слоеве с административните границите могат да бъдат маркирани само за прочитане (read-only);
- задължително трябва да съдържа поне една картна основа, за да може "доносниците" да се ориентират къде в пространството да въвеждат данните;
- картните основи могат да бъдат повече от една и да са във взаимоизключващата се група;
- проектът трябва да съдържа поне една релация;
- формулярите за попълване и редакция на векторните слоеве трябва да бъдат настроени ръчно, а не да се използват автоматично генерираните;
- някои полета във формулярите могат да притежават стойности по подразбиране;
- всички векторни слоеве трябва да бъдат съхранявани в един единствен `.gpkg` файл.


## Резултат

QGIS проект с удобни за попълване формуляри на констатирани проблеми в градската среда, подходящ за бъдещо донастройване за работа с QField.


## Източници на данни

Всички необходими данни за съставяне на базисния проект са налични от свободни и безплатни източници.


## Време за изпълнение
За опитен потребител 2 ч.
За запознат потребител 8 ч.
За незапознат потребител 20 ч.


## Задължителни материали за четене

- (EN) https://docs.qgis.org/3.16/en/docs/training_manual/create_vector_data/create_new_vector.html
- (EN) https://docs.qgis.org/3.16/en/docs/training_manual/create_vector_data/forms.html
- (EN) https://docs.qgis.org/3.16/en/docs/user_manual/working_with_vector/attribute_table.html#vector-relations
- (BG)(WIP) https://qgisbg.github.io/docs/gisintro/05_data_capture/ или в оригинал (EN) https://docs.qgis.org/3.16/en/docs/gentle_gis_introduction/data_capture.html


## Срок на изпълнение
Както винаги, срокът на задачата е 24:00 на първата неделя след две седмици (14 дни).
