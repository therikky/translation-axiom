# Панель главного меню
Строка главного меню предоставляет пользователям доступ к важнейшим функциям программы. Здесь находятся пункты меню для доступа к окнам, работы с выбором, выполнения операций и просмотра полезной информации.

## Редактирование
    
| Функции        | сочитания клавиш по умолчанию | Описание                                              |
|----------------|------------------|----------------------------------------------------------|
| Отмена         | Ctrl+Z           | Отменяет последнее действие                              |
| Повтор         | Ctrl+Y           | Отменяет последнее отменяющее действие                   |
| Вырезать       | Ctrl+X           | Снимает выделение и сохраняет его в буфере обмена        |
| Копирование    | Ctrl+C           | Копирует выбранный элемент в буфер обмена                |
| Сохранить      | Ctrl+P           | Сохраняет текущий выбор в качестве чертежа для последующего использования |

## Выделение
    
Подменю выбора позволяет пользователям выполнять различные функции, связанные с выбором.
    
| Функция  | Описание                     |
|----------|------------------------------|
| Очистка  | Очистка текущего выделения   |
| Маска    | Выбирает блоки в текущей выборке, которые соответствуют выбранному блоку |
| Развернуть | Расширяет текущий выбор на заданное количество блоков |
| сокращение | Сокращает текущее выделение на заданное количество блоков |
| Искажение  | Искажает текущее выделение симплексным шумом на заданный радиус и расстояние. Радиус - это масштаб шума, а расстояние - величина, на которую он искажается |
| Сглаживание | Применяет к выделению размытие по Гауссу, чтобы сгладить выделение. Стандартное отклонение — это интенсивность операции сглаживания, а порог — это «отсечка» того, сколько входного веса необходимо, чтобы повлиять на результат.. |
| Граничная зона | Создает кубоидное выделение вокруг самых удаленных точек выделения, заключая в себе все выделение |

## Просмотр

Подменю просмотра позволяет настроить параметры, связанные с просмотром и визуализацией определенных элементов в мире.

| Функция        | сочитания клавиш по умолчанию | Описание |
|----------------|------------------|-------------|
| Новый вид       | Нет             | Создать новый [Вид](views.html) |
| Показать выделение | Нет             | Позволяет переключать визуализацию вашего выделения |
| Показать биомы    | Ctrl+B           | Включает овердей биома[^note1] |
| Минимальная яркость | Нет             | Ползунок в диапазоне от 0 до 1. Он позволяет изменить внешний вид темных неосвещенных мест в вашем мире. Значение 1 означает, что все блоки полностью освещены, это также называется полной яркостью. 
| Непрозрачность жидкости  | Нет            | A slider ranging from 0 to 1. This lets you change the opacity of transluscent[^note2] fluids to make it easier to look through. A value of 0 will make the fluid invisible |
| Show Key Presses| None            | This shows your inputs including mouse clicks on the bottom right of the viewport. This is useful for making tutorials. |

[^note1]: Be aware that biomes in Minecraft are defined in a 4x4x4 grid. However, in order to make biomes feel more natural, vanilla warps the biomes visually. The biome overlay shows the "real" position of biomes, while biome blending and the f3 screen show the "warped" position of biomes.
    
[^note2]: Lava and other non-translucent fluids (if the game is modded) are not affected by opacity due to performance and mod compatibility concerns.

## Create
    
The **Create** submenu lets you make geometric shapes with your active block. Since these shapes are computed mathematically, they can adjust to any angle and transformation, giving you a lot of control over their look. When you 'place' these objects, you can use the [gizmo](gizmos.md) to reposition them and rotate them at arbitrary angles.
    
Each shape lets you tweak their XZ or XYZ dimensions, as well as having a toggle for individual sliders. In addition to controling rotation using the gizmo, you can also input specific angles for yaw, pitch, and roll in the 'advanced options' dropdown. Plus, there are options for making the shapes hollow, placing only the outer layer.
    
The current available shapes are:    
 - Sphere
 - Cuboid
 - Cylinder
 - Cone
 - Pyramid

## Operations
    
The **Operations** submenu has a lot of features for modifying the selected part of your world 
    
| Function             | Default Shortcut | Description  |
|----------------------|------------------|--------------|
| Fill                 | Ctrl+F           | Fill a selection with the chosen block |
| Fill Nearest         | None             | Fills an area with the closest neighbor blocks, useful to repair areas or fill in gaps |
| Replace              | Ctrl+R           | Replace specific blocks in the selection with the chosen block |
| Set Biome            | None             | Sets the selection to the chosen biome |
| Drain                | None             | Drains an area of all fluids, including waterlogged blocks |
| Waterlog             | None             | Floods an area with water, including turning waterloggable blocks into their waterlogged counterpart |
| Simulation > Gravity | None             | Gravity simulation makes all blocks with air below 'fall' as if they were affected by gravity |
| Analyze              | None             | Analyzes the blocks in the selection, giving information on counts and distribution |

## Tool Masks
    
Clear and open the tool mask editing window. See [Tool Masks](toolmasks.md)

## Window
    
The **Windows** submenu lets the user toggle the visibility of important windows. If you ever close a window and want it back, this submenu allows you to reenable it.
    
## Help
    
The **Help** submenu contains useful information and configuration options.

Users can configure keybinds, find useful links to Axiom related resources and view this documentation.
