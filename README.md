# TetrisGame
Tetris Game in winForm

Написать тетрис на WinForms. +

Размерность игрового поля настраиваемая. Минимальная высота 20 ячеек, ширина 15 ячеек. +

Скорость падения блоков 2 ячейки в секунду. +

Управление должно происходить с помощью клавиатуры. +

Уровней сложности делать не нужно. Один бесконечный уровень. +

Дополнительно должен быть инструмент для создания новых видов блоков. +

Ограничения для создания блоков:  размерность 4 на 4 +  и не более восьми ячеек в блоке +. У каждой ячейки в блоке должна быть соседняя ячейка по оси X или Y. +

Есть некоторые проблемы с отделением логики от интерфейса, далеко не всё разнёс красиво. 
Сохранение результатов и ведение статистики не делал, хотя функционал для этого в целом весь есть.

Вновь созданные фигуры не переворачиваются, потому что не реализовывал поворот, а делал массив состояний, в целом поворот можно реализовать через матрицу вращения но логику переделывать уже не стал.

Запретить изменине размера можно добавив на главной форме  this.FormBorderStyle = FormBorderStyle.FixedSingle 
