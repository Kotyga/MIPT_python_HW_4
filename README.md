<div id="view-counter" style="text-align: center; font-size: 24px; margin: 20px;">
    <h2>Число просмотров: <span id="count">0</span></h2>
</div>

<script>
    // Инициализация счетчика
    let viewCount = 0;

    // Функция для обновления счетчика
    function updateViewCount() {
        viewCount++;
        document.getElementById('count').innerText = viewCount;
    }

    // Обновление счетчика при загрузке страницы
    window.onload = updateViewCount;
</script>


# MIPT_python_HW_4

## 1. Задача

Описать поведение бота, который будет играть с такими же ботами в игру «камень-ножницы-бумага». Поведение бота описывается с помощью функции, которая принимает на вход информацию о прошлых играх.
После описания поведения агентов запустить турнир между ними и проверить, какая стратегия показывает себя лучше всех.
Отметим, что вам необязательно использовать «качественные» стратегии — в этом задании основной упор необходимо сделать на разнообразие (т.е. агенты, которые бы играли, придерживаясь стратегии «только камень» или »только ножницы» – это нормально).

## 2. Как скачать репозиторий

Вы можете скачать репозиторий с помощью команды Git. Откройте терминал и выполните следующую команду:

```
git clone https://github.com/Kotyga/MIPT_python_HW_4.git
```

## 3. Как использовать

После того как вы скачали репозиторий, вы можете использовать скрипты и ноутбуки, предоставленные в проекте, для анализа данных и построения моделей.

## 4. Как установить зависимости

Для установки необходимых зависимостей, выполните следующую команду в терминале:

```bash
pip install -r requirements.txt
```

Файл requirements.txt содержит список всех необходимых библиотек для работы с проектом.

## 5. Как создать окружение

Рекомендуется создать виртуальное окружение для работы с проектом. Вы можете сделать это с помощью venv или conda. Вот как создать окружение с помощью venv:

### Создание виртуального окружения
```bash
python -m venv myenv
```

### Активация виртуального окружения (Windows)
```bash
myenv\Scripts\activate
```
### Активация виртуального окружения (Mac/Linux)
```bash
source myenv/bin/activate
```
После активации окружения установите зависимости, как указано в пункте 4.
