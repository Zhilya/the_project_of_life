# The project of life

## Цель: Создать  TBS (Turn-based strategy) игру с RPG элементами в стиле heroes of might and magic 3.

## Игра имеет следующие сущности:
### Доступные к управлению игроком*:
#### На глобальной карте:
* Замок
* Герой(герои?)
* Месторождения ресурсов (захват/оборона)
#### На полях сражения:
* Боевые единицы (существа на поле боя)
* не управляемые игроком:
#### На глобальной карте
* Боевые нейтральные** единицы
* Консъюмблы (ресурсы, артефакты, бонусы)
* Строения для взаимодействия (источники артефактов, бонусов, ресурсов, опыта)

##### (*) - могут быть под контролем вражеского ИИ.
##### (**) - под контролем нейтрального ИИ.

##  Игровая задача - победить вражеского ИИ:
1. Оставить без замков на определённый срок
1. Оставить без замков и героев

Вражеский ИИ имеет цель победить игрока, имеет возможности как у игрока.
Нейтральный ИИ на глобальной карте статичен, в боях на полях сражений имеет цель победить игрока.
### Задачи на поле сражений:
1. Уничтожить всех юнитов соперника
1. Вынудить соперника отступить и принять отступление

### Возможности игрока:
1. Исследование карты (передвижение по карте) посредствам управления передвижениями собственных героев
1. Взаимодействие с боевыми нейтральными единицами, месторождениями ресурсов(союзными(С),нейтральными(Н),вражескими(В), замками (СНВ), консъюмблами, строениями для взаиодействия, героями(СВ)
1. Управление собственными боевыми единицами на полях сражений
1. Управление собственными замками
