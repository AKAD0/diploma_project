<div align="center">
<sup>Дипломный проект "NLP веб-приложение"</sup>
  
<sup>Намнанов Арсалан Батоевич, 2024</sup>
<div><img src="gitpage_mats/logo.png" width="400" alt="Warp" /></div>
<div><b>Локальный чатбот "AI Chat"</b></div>

AI Chat — это чатбот, вдохновленный ChatGPT, с которым можно общаться на широкие темы,<br />способный помнить давно прошедшие разговоры.

[Презентация](#презентация) •
[Технологии](#технологии) •
[Принцип работы](#принцип-работы)
</div>

## Презентация
https://github.com/user-attachments/assets/3243483d-4016-4436-b134-9d0569b45859

## Технологии
Проект включал решение следующих задач:
1) Обучение <a href="https://huggingface.co/tiiuae/falcon-7b"><u>LLM Falcon 7B</u></a>, на датасете <a href="https://huggingface.co/datasets/tatsu-lab/alpaca"><u>Alpaca</u></a> методом <a href="https://arxiv.org/abs/2106.09685"><u>LoRA</u></a> при помощи фреймворка <a href="https://github.com/Lightning-AI/litgpt"><u>LitGPT</u></a>; <br />

<table align="center">
  <tr>
    <td><img src="gitpage_mats/graph.png" height="512" align="center"></td>
    <td><img src="gitpage_mats/bench.png" height="512" align="center"></td>
  </tr>
  <tr>
    <td align="center">Динамика функции ошибки по процесу обучения</td>
    <td align="center">Показатели тестирования на бенчмарках</td>
  </tr>
</table>

2) Написание <a href="https://flask.palletsprojects.com/en/stable/"><u>Flask</u></a> веб-приложения для чата с LLM с применением <a href="https://flask-sqlalchemy.readthedocs.io/"><u>ORM Flask-SQLAlchemy</u></a>; <br />
<table align="center">
  <tr>
    <td><img src="gitpage_mats/diagram_2.png" height="512" align="center"></td>
  </tr>
  <tr>
    <td align="center">Работа веб-приложения на диаграмме деятельности</td>
  </tr>
</table>

3) Деплой веб-приложения.

## Принцип работы
фыва
