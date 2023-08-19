# Волшебный выбор

The **Волшебный выбор**Инструмент является мощным инструментом выбора, который значительно улучшает процесс построения, если его правильно использовать. Одним щелчком мыши по типу блока инструмент «Волшебное выделение» быстро выделяет все соседние блоки того же типа, упрощая процесс выбора.

Инструмент имеет следующие параметры:
The **Сравнивать**Режим опций позволяет вам выбирать типы блоков, которые он может выбирать рядом с исходным блоком. Режим по умолчанию — «Блокировка».

|Сравнить|Описание|
|---|---|
|Блокировать|Все блоки одного типа, включая все состояния блоков.|
|состояние блокировки|Все блоки точно такого же состояния блока, что и целевой блок.|
|Твердый|Любой блок, через который вы не можете пройти. Например, камень, стеклянные панели и т. д. Не цветы, вода и т. д.|
|Любой|Все блоки, непосредственно примыкающие друг к другу, включая нетвердые блоки, кроме воздушных. Это заставляет его «останавливаться», когда он достигает воздуха.|


The **Limit** option is a slider which can be configured to set how many blocks it should select in total. The magic select algorithm works by expanding outwards from the centre block to form an octahedron. Increasing the limit simply lets you select more blocks. The default limit is set to 100,000 blocks but can be set to any arbitrary limit.

The **Range** option is a slider which lets you set how far the algorithm should look for any adjacent blocks. This lets the tool ‘jump the gap’ between two blocks. The range simply represents how far it can look before cutting off. For example a bushy tree might have two or more blocks of air between it’s leaves and logs. This lets you select all the leaves that are on the tree regardless of the fact that there are air blocks between two branches with leaves.

The **Surface Only** option is a toggle which makes the tool only select the blocks on the surface of the selection or, equivalently, all blocks adjacent to air or the ‘outside’.
