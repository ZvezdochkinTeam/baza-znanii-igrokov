# 🎙️ Голосовые реплики

Что это такое и зачем оно нужно ?

**Голосовые реплики или войс команды** - это предопределенные фразы, используемые для общения и взаимодействия с другими игроками, если у использующего, к примеру, нету микрофона или микрофон не работает (или иногда лень использовать микро, прям как мне)

## Какие голоса используются для этих реплик ?

* Разведчик (Scout)
* Медик (Medic)
* Солдат (Soldier)
* Снайпер (Sniper)
* Инженер (Engineer)
* Подрывник (Demoman)
* Шпион (Spy)
* Пулеметчик (Heavy)

## Какие типы реплик доступны ?

* Help (Позвать на помощь)
* BattleCry (Боевой Клич)
* Cheers (Ура!)
* Jeers (Отстой!)
* Positive (Шикарно)
* Negative (Ужасно)
* NiceShot (Отличный выстрел)
* GoodJob (Хорошая работа)
* Incoming (Враг наступает)
* Spy (Шпион)
* Medic (МЕДИК!)
* Thanks (Спасибо)
* GoGoGo (Вперёд)
* MoveUp (Продвигаемся)
* GoLeft (Налево)
* GoRight (Направо)
* Yes (Да)
* No (Нет)
* Laugh (Смех)
* Taunt (Насмешка)
* Scream (Крик ужаса)

## Как их использовать ?

{% stepper %}
{% step %}
Откройте консоль (по умолчанию на клавишу `Ё`)
{% endstep %}

{% step %}
Введите команду `.voicecommand (тут тип реплики) (необязательно, но можно указать тут номер конкретной реплики)`
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Примеры использования**

.voicecommand BattleCry

.voicecommand BattleCry 5

.voicecommand Help
{% endhint %}

## Как их быстрее использовать ?

Можно использовать бинды (привязка клавиш)

{% stepper %}
{% step %}
Откройте консоль (по умолчанию на клавишу `Ё`)
{% endstep %}

{% step %}
Введите команду `cmdbind (код клавиши) .voicecommand (тут тип реплики)`
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Пример использования**

cmdbind 51 .voicecommand No
{% endhint %}

## Как изменить голос озвучки ?

{% stepper %}
{% step %}
Откройте консоль (по умолчанию на клавишу `Ё`)
{% endstep %}

{% step %}
Введите команду `.changevoicename (Название Озвучки)`
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Примеры использования**

.changevoicename Scout

.changevoicename Soldier
{% endhint %}

## Как узнать список доступных озвучек ?

{% stepper %}
{% step %}
Откройте консоль (по умолчанию на клавишу `Ё`)
{% endstep %}

{% step %}
Введите команду `.voicenamelist`
{% endstep %}
{% endstepper %}

## Где я могу узнать код той или иной клавиши ?

По этой [кликабельной ссылке](https://gist.github.com/kgrela/0f43050afddaabe31db7a1ce40e25d4c) вы можете узнать всё, что вам нужно

## Как их отключить и не слышать ?

### Способ №1

{% stepper %}
{% step %}
Откройте консоль (по умолчанию на клавишу `Ё`)
{% endstep %}

{% step %}
Введите команду `.changevoicemode`
{% endstep %}
{% endstepper %}

### Способ №2

{% stepper %}
{% step %}
Открыть список игроков (по умолчанию на клавишу `N`)
{% endstep %}

{% step %}
Найти нужного игрока
{% endstep %}

{% step %}
Заглушить его через иконку 🔊
{% endstep %}
{% endstepper %}

## Список заготовок для биндов

### Вариант №1 (без Numpad)

От клавиши с цифрой `3` до клавиши `Backspace`

cmdbind 51 .voicecommand Yes\
cmdbind 52 .voicecommand No\
cmdbind 53 .voicecommand Positive\
cmdbind 54 .voicecommand Negative\
cmdbind 55 .voicecommand Cheers\
cmdbind 56 .voicecommand Jeers\
cmdbind 57 .voicecommand GoGoGo\
cmdbind 48 .voicecommand GoLeft\
cmdbind 45 .voicecommand GoRight\
cmdbind 61 .voicecommand MoveUp\
cmdbind 8 .voicecommand BattleCry

Клавиши `Y` `H` `U` `J` `I` `K` `O` `L` `P` `:` `{`

cmdbind y .voicecommand Medic\
cmdbind h .voicecommand Help\
cmdbind u .voicecommand Spy\
cmdbind j .voicecommand Incoming\
cmdbind i .voicecommand Scream\
cmdbind k .voicecommand Laugh\
cmdbind o .voicecommand Taunt\
cmdbind l .voicecommand Thanks\
cmdbind p .voicecommand GoodJob\
cmdbind 34 .voicecommand NiceShot

### Вариант №2 (c Numpad)

Клавиши `Insert` `Delete` `Home` `End` `PgUp` `PgDown`

cmdbind 277 .voicecommand Yes\
cmdbind 127 .voicecommand No\
cmdbind 278 .voicecommand Positive\
cmdbind 279 .voicecommand Negative\
cmdbind 280 .voicecommand Cheers\
cmdbind 281 .voicecommand Jeers

Клавиши **Numpad**

cmdbind 256 .voicecommand Medic\
cmdbind 266 .voicecommand Help\
cmdbind 257 .voicecommand Spy\
cmdbind 258 .voicecommand Incoming\
cmdbind 259 .voicecommand Scream\
cmdbind 260 .voicecommand Laugh\
cmdbind 261 .voicecommand Taunt\
cmdbind 262 .voicecommand Thanks\
cmdbind 263 .voicecommand GoodJob\
cmdbind 264 .voicecommand NiceShot\
cmdbind 265 .voicecommand BattleCry\
cmdbind 270 .voicecommand MoveUp\
cmdbind 271 .voicecommand GoGoGo\
cmdbind 267 .voicecommand GoLeft\
cmdbind 268 .voicecommand GoRight

## ЧАВО или "У меня не работает"

{% hint style="info" %}
**У меня не работают бинды**

Убедитесь, что вы на правильную клавишу поставили бинд

Если клавиша правильная, то попробуйте свернуть и развернуть приложение игры (`ALT` + `TAB`)

Если и этот способ не помог, то попробуйте 2 раза открыть и закрыть RA-панель (по умолчанию клавиша `M`)
{% endhint %}

{% hint style="info" %}
**Я не могу использовать команду за тот или иной игровой класс**

Голосовые реплики сейчас доступны только для некоторых классов (зависит от сервера)
{% endhint %}

{% hint style="info" %}
**А как говорить через рацию или интерком ?**

Голосовые реплики работают только с SCP-1576 и с рацией (она должна быть в руках и включена)
{% endhint %}

{% hint style="info" %}
**Как удалить старые бинды ?**

В папке с игрой необходимо запустить файл с названием **appdata** (файл расширения **.bat**), который откроет папку с конфигами игры, где должен находиться файл с названием **cmdbindings.txt**
{% endhint %}

**Добро пожаловать в команду, боец!**

{% embed url="https://youtu.be/MY22ly7qDBA?si=DRW36e0MgO3ArIjv" %}

{% content-ref url="golosovye-repliki.md" %}
[golosovye-repliki.md](golosovye-repliki.md)
{% endcontent-ref %}
