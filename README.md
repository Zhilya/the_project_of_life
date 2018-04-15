# The project of life

### Цель: Создать  TBS (Turn-based strategy) игру с RPG элементами в стиле heroes of might and magic 3.

### Игра имеет следующие сущности:
** Доступные к управлению игроком*:
**На глобальной карте:
* Замок
* Герой(герои?)
* Месторождения ресурсов (захват/оборона)
** На полях сражения:
* Боевые единицы (существа на поле боя)
* не управляемые игроком:
На глобальной карте
1 - боевые нейтральные** единицы
2 - консъюмблы (ресурсы, артефакты, бонусы)
3 - строения для взаимодействия (источники артефактов, бонусов, ресурсов, опыта)

* - могут быть под контролем вражеского ИИ
** - под контролем нейтрального ИИ

игровая задача - победить вражеского ИИ:
1 оставить без замков на определённый срок
2 оставить без замков и героев
вражеский ИИ имеет цель победить игрока, имеет возможности как у игрока
нейтральный ИИ на глобальной карте статичен, в боях на полях сражений имеет цель победить игрока
задачи на поле сражений:
1 - уничтожить всех юнитов соперника
2 - вынудить соперника отступить и принять отступление

возможности игрока:
1 - исследование карты (передвижение по карте) посредствам управления передвижениями собственных героев
2 - взаимодействие с боевыми нейтральными единицами, месторождениями ресурсов(союзными(С),нейтральными(Н),вражескими(В), замками (СНВ), консъюмблами, строениями для взаимодействия, героями(СВ)
3 - управление собственными боевыми единицами на полях сражений
4 - управление собственными замками
