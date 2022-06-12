cmake_minimum_required(VERSION 3.5)
project(unsplash-wallpapers)

set(BACKGROUNDS
	default.jpg
	misaka-1920x1080.png
	misaka-2560x1440.png
	cutefish-0.jpg
	cutefish-1.jpg
	cutefish-2.jpg
	cutefish-3.jpg
	cutefish-4.jpg
	cutefish-5.jpg
	cutefish-6.jpg
	cutefish-7.jpg
	cutefish-8.jpg
	cutefish-9.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/cutefishos)
