# Key for toggling speed the playback on YouTube
#### (ENG)
In the settings of Enhancer for YouTube there is an item for adding custom scripts, I wrote a code that adds a speed switch from x1, x2 (or any other values) and back.

### How to use:
Install the [Enhancer for YouTube](https://www.mrfdev.com/enhancer-for-youtube), go to the settings, there is a "Custom script" item at the very bottom, insert the code from the file [toggle speed](https://github.com/Amizx2/Enhancer-for-YouTube-toggle-switch-speed/blob/main/toggle%20speed ). 
### Be sure to select "Automatically execute a custom script if YouTube is loaded in the tab":
![image](https://github.com/user-attachments/assets/2778d6e0-a504-4754-9f42-2c9ff627529b)



### How to customize for yourself:

If you need another speed modifier, then change the video in the line.playback Rate = video.playback Rate === 1 ? 2 : 1; to the required values.
Here you can check the current value of the video speed and switch to another one.

If you need another key: Change Backslash in the line if (event.key === 'Backslash') to the desired character.
[The values of all keys](https://javascript.info/article/keyboard-events/keyboard-dump/)

![image](https://github.com/user-attachments/assets/6016a976-949c-43f4-8435-eb40169917db)


##### I will be glad to see suggestions for improvements and adding new features.

## (RU)
## Клавиша для переключения скорости воспроизведения на YouTube.

В настройках Enhancer for YouTube есть пункт для добавления пользовательских скриптов, я написал код, который добавляет переключение скорости с x1, x2 (или любых других значений) и обратно.

### Как использовать:
Устанавливаем расширение [Enhancer for YouTube](https://www.mrfdev.com/enhancer-for-youtube), переходим в настройки, в самом низу есть пункт "Пользовательский скрипт", вставляем сюда код из файла [toggle speed](https://github.com/Amizx2/Enhancer-for-YouTube-toggle-switch-speed/blob/main/toggle%20speed). 
### Обязательно выбираем "Автоматически выполнять пользовательский скрипт, если во вкладке загружен YouTube":
![image](https://github.com/user-attachments/assets/312f8236-79df-4c2b-8222-215929eed790)




### Как настроить под себя:

Если вам нужен другой модификатор скорости, то измените video.playbackRate = video.playbackRate === 1 ? 2 : 1; на желаемые значения.
Здесь вы можете проверить текущее значение скорости видео и переключиться на другое, соответственно.

Если вам нужна другая клавиша: измените backslash в строке if (event.key === 'Backslash') на нужный символ.
[Значения всех клавиш](https://learn.javascript.ru/article/keyboard-events/keyboard-dump)

![image](https://github.com/user-attachments/assets/cca31086-b3a5-4c28-b149-34fb4fc61984)

##### Буду рад видеть предложения по улучшению и добавлению новых функций.

