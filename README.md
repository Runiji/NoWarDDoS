# NoWarDDoS
DDoS Russian websites to help Ukraine to win this hybrid war

# ENGLISH
<br />▪ Install Python 3.8+ (Be sure to check the box "Add to path")
![alt text](https://miro.medium.com/max/1344/0*7nOyowsPsGI19pZT.png)
<br />▪ Open the terminal (console), go to the root, where we unpacked our program using command cd
<br />▪ At the root, enter the following command: 
<br />  Windows: python attack.py <number of threads>
<br />  macOS/Linux: python3 attack.py <number of threads>
<br />  
<br />▪ On 8 CPU and 16 gigs of RAM we put 500 threads. The proxy is installed automatically. 
<br />▪ Experiment, choose the optimal number of threads so that the processor runs at 100% 
<br />▪ Example: python3 attack.py 500
<br />
#
<br />▪ Everything works through a proxy, do not be afraid! 
<br />▪ If there are problems, we answer Telegram 24/7: https://t.me/esen1n25, https://t.me/EdwardBrave
<br />▪ All coordination via chat Telegram: https://t.me/incourse911
<br />▪ The program is updated automatically, it will update itself and run the attack again, updates are checked every minute
<br />▪ If you notice in the chat an update that I did not post, let me know in tg 
<br />
<br />▪ If it knocks out an error related to ModuleNotFoundError or others, try: 
<br />    Windows: python -m pip install --upgrade pip
<br />             pip install -r requirements.txt
<br />    macOS/Linux: python3 -m pip install --upgrade pip
<br />                 pip3 install -r requirements.txt
<br />
<br />
<br />▪ If something is broken, reenter the following commands:
<br />  Windows: python updater.py <number of threads>
<br />  macOS/Linux: python3 updater.py <number of threads>
<br />▪ If it does not help, be sure to write in tg!
<br />**Слава Україні!**

## Build for Windows:

https://github.com/EdwardBrave/NoWarDDoS/issues/1#issue-1153116910

## Instructions for direct start:
1. through the console we enter the command 

Windows:
```shell
python attack.py <number of threads>
```
macOS/Linux:
```shell
python3 attack.py <number of threads>
```
number of threads - 500+ or whoever can, so that the computer does not hang

## Instructions for pushing on Heroku:

1. Make fork on your account
2. Register and create a bot on https://heroku.com
3. Connect heroku to the repository and put automatic builds. Build once by hand just to be shure. Instruction: https://devcenter.heroku.com/articles/github-integration
4. Go to the Resources tab and start working 

On questions on it we write in Issues in this repository 

## Instructions to run with `Docker`:
1. Installing [Docker](https://www.docker.com/)
2. Build an image
```shell
docker build . -t nowarddos
```
3. Launch it
```shell
docker run --rm nowarddos 500
```


# УКРАЇНСЬКА

<br />▪ Встановлюємо Python 3.8+ (Обов'язково ставимо галку "Add to path")
![alt text](https://miro.medium.com/max/1344/0*7nOyowsPsGI19pZT.png)
<br />▪ Відкриваємо термінал(консоль), переходимо в корінь, куди розпакували нашу програму командою cd
<br />▪ В корені вводимо наступну команду: 
<br />  Windows: python attack.py КІЛЬКІСТЬ_ПОТОКІВ
<br />  macOS/Linux: python3 attack.py КІЛЬКІСТЬ_ПОТОКІВ
<br />  
<br />▪ На 8 CPU і 16 гігів оперативки ставим 500 потоків. Проксі встановлюється автоматично. 
<br />▪ Експерементуйте, обтирайте оптимальну кількість потоків, щоб проц в сотку довбився ))
<br />▪ Приклад: python3 attack.py 500
<br />
#
<br />▪ Все працює через проксі, не бійтесь!
<br />▪ Якщо виникнуть проблеми, 24/7 відповідаю Telegram: https://t.me/esen1n25, https://t.me/EdwardBrave
<br />▪ Вся координація через чат Telegram: https://t.me/incourse911
<br />▪ Програма оновлюється автоматично, вона сама оновиться та знову запустить атаку, оновленния перевіряються кожну хвилину
<br />▪ Якщо помітили в чаті оновлення яке я не виклав, повідомте в тг
<br />
<br />▪ Якщо вибиває помилку пов'язану з ModuleNotFoundError aбо інші, спробуйте:
<br />    Windows: python -m pip install --upgrade pip
<br />             pip install -r requirements.txt
<br />    macOS/Linux: python3 -m pip install --upgrade pip
<br />                 pip3 install -r requirements.txt
<br />
<br />    ~~macOS з ARM (M1) тимчасово не підтримується, очікуйте оновлення в найближчі години~~
<br />    macOS ARM (M1) все працює!
<br />
<br />▪ Якщо щось зламалося вводимо наступну команду:
<br />  Windows: python updater.py КІЛЬКІСТЬ_ПОТОКІВ
<br />  macOS/Linux: python3 updater.py КІЛЬКІСТЬ_ПОТОКІВ
<br />▪ Якщо не допомагає, обов'язково пишіть в тг!
<br />**Слава Україні!**

## Білд для Windows:

https://github.com/EdwardBrave/NoWarDDoS/issues/1#issue-1153116910

## Інструкця для прямого запуску:

через консоль вводимо команду
```shell
python3 attack.py <кількість потоків>
```
кількість потоків - 500+ або хто скільки може, щоб комп'ютер не зависав

## Інструкця для виливки в Heroku:

1. Робимо fork на свій акаунт
2. Реєструємось та створюємо бота на https://heroku.com
3. Підключаємо heroku до репозиторію та ставимо автобілди. Білдимо один раз вручну. Інструкція: https://devcenter.heroku.com/articles/github-integration
4. Переходимо в вкладку Resources та запускаємо в роботу

По питанням по цьому пишемо в Issues в цей репозиторій

## Інструкця для запуску у `Docker`:
1. Ставимо [докер](https://www.docker.com/)
2. Білдимо імадж
```shell
docker build . -t nowarddos
```
3. Запускаємо
```shell
docker run --rm nowarddos 500
```
