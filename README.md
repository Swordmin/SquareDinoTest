
Проект должен быть гибким и расширяемым. Например, чтобы при
необходимости без редактирования кода можно было добавить новые
вейпоинты, врагов или изменить скорость пули.

1. Необходимо собрать аккуратную, простую игровую локацию. Используем
ассет, представленный по ссылке ниже:

2. Расставить вейпоинты и реализовать движение персонажа по ним,
желательно с использованием NavMesh. При старте уровня необходимо
расположить персонажа на первом вейпоинте и без врагов. Начало игры
реализовать через тап по экрану. На каждом следующем вейпоинте
необходимо останавливать персонажа для расстрела врагов. После их
убийства персонаж автоматически двигается к следующему вейпоинту. При
достижении последнего вейпоинта, рестартим сцену и начинаем с начала.

3. Стрельба должна быть реализована тапом по экрану. В момент тапа
создается пуля и летит в точку тапа. Если пуля попала в любой из
коллайдеров, то она удаляется (необходимо использовать пул объектов).

Игровой уровень должен быть собран аккуратно. Не нужно собирать
большую и сложную локацию.
Камеру должна быть от 3-го лица. Ракурс камеры выставить на свое
усмотрение. Допускается использование Cinemachine. Персонаж должен иметь 2 вида анимаций: Run и Idle. Можно взять с
mixamo.com
Для врагов можно использовать ту же модель, что и у игрока, но другого
цвета. Враги стоят и проигрывают Idle анимацию. Умирают от попадания
пули.

Дополнительные задания

После смерти у врагов активируется
рэгдолл и они падают на землю.

Добавить врагам жизни и отображение
уровня здоровья над ними (в виде UI).

Пояснительная записка к работе:
Не использовал DI т.к это увеличило бы срок работы.
