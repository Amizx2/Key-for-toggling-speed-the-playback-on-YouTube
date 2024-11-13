# Enhancer-for-YouTube-toggle-swithc-speed 
(ENG)
In the settings of Enhancer for YouTube there is an item for adding custom scripts, I wrote a code that adds a speed switch from x1, x2 (or any other values) and back.
#How to customize for yourself:

If you need another speed modifier, then change the video in the line.playback Rate = video.playback Rate === 1 ? 2 : 1; to the required values.
Here you can check the current value of the video speed and switch to another one, respectively.

If you need another key: Change K in the line if (event.key === 'K') to the desired character.
[The values of all keys](https://javascript.info/article/keyboard-events/keyboard-dump/)
![image](https://github.com/user-attachments/assets/6016a976-949c-43f4-8435-eb40169917db)


(RU)
В настройках Enhancer для YouTube есть пункт для добавления пользовательских скриптов, я написал код, который добавляет переключение скорости с x1, x2 (или любых других значений) и обратно.
#Как настроить под себя:

Если вам нужен другой модификатор скорости, то измените video.playbackRate = video.playbackRate === 1 ? 2 : 1; на желаемые значения.
Где вы можете проверить текущее значение скорости видео и переключиться на другое, соответственно.

Если вам нужна другая клавиша: измените backslash в строке if (event.key === 'backslash') на нужный символ.
Вот где можно получить значения для всех клавиш:
https://learn.javascript.ru/article/keyboard-events/keyboard-dump/
[Значения всех клавиш](https://learn.javascript.ru/article/keyboard-events/keyboard-dump/)
