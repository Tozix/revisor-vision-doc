---
description: Разметка изображений в системе RevisorVison
---

# 👀 Руководство пользователя платформы разметки

В этом руководстве мы познакомим вас с работой платформы для разметки изображений для обучения нейронных сетей. Проведём вас по всем этапам необходимым для нанесения разметки и формирования датасета.&#x20;

Приступим!



<div>

<figure><img src=".gitbook/assets/01_пустой.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/02_первый.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/03_создание группы.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/04_тип_группы.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/05_проект.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/06_создание_проекта.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/07_проекты.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/08_обзор_проекта.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/09_менеджмент.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/10_загрузка.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/11_загрузка_на_сервер.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/12_сохранение_батча.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/13_работа_с_батчами.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/14_выбрать_изображения.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/15_создание_задачи.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/16_перед_рисованием.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/17_интерфейс_рисовалки.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/18_инструменты_рисовалки.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/19_нанесение_прямоугольника.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/20_подсветить.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/21_сохранить_разметку.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/22_типы_авторазметки.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/23_выбор_классов.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/24_запуск_авторазметки.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/25_прогресс_авторазметки.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/26_задачи.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/27_ещё_модель_1.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/28_ещё_модель_2.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/29_хорошо_детектировало.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/30_полный_запуск.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/32_авторазметка_из_задачи.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/33_подсказки_текстом.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/34_подсказки_на_английском.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/35_текстом_дольше.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/37_выбор_сегментации.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/38_есть_сегментация.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/39_добавить_в_датасет.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/40_создание_датасета.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/41_датасет.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/42_анализ_датасета.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/43_генерация_версии.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/44_распределение_в_версии.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/45_препроцессинг.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/46_аугментация.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/47_итоговая_генерация.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/48_готовая_версия.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/49_экспорт.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/50_переименование.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/51_ссылка_на_скачивание.png" alt=""><figcaption></figcaption></figure>

</div>
