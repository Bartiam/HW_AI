# HW_06

Developed with Unreal Engine 5

Цель практической работы
Научиться настраивать поведение бота при обнаружении игрока, в частности логику стрельбы.


Что нужно сделать
	- Реализуйте логику стрельбы бота, свяжите её с соответствующими анимациями.
	- Дополните дерево поведения бота, чтобы он, обнаружив игрока, начинал стрелять в него.

Советы и рекомендации
	- В проекте уже реализован базовый сетап бота, который умеет патрулировать и поворачиваться в сторону игрока при его 
	обнаружении.
	- Сначала продумайте логику и анимации бота, чтобы он умел правильно переключаться между режимами. Например, в 
	спокойном состоянии оружие находится за спиной, при переходе в режим боя проигрывается анимация доставания оружия и 
	включаются соответствующие стейты обращения с оружием.
	- Можно использовать разные Animation Blueprints и динамически переключаться между ними.
	- Вышеописанные компоненты можно будет привязать к дереву поведения, чтобы бот соответствующе реагировал на 
	происходящее.