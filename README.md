# main_course

# Starter for beginners.
Курс основ системного администрирования на доступном языке, объясняющий основы методик DevOps и SRE.

## Введение
Цель: помочь разобраться в профессии новичкам, имеющим технический бэкграунд и опыт программирования, администрирования и настройки Linux/Unix серверов. Поиск удобных уроков, статей, платных курсов и занятий. Возможность быстрого самостоятельного стаарта без затрат. Снижение порога вхождения в профессию.

Дополнить: Что такое DevOps, откуда взялся, какие задачи и цели выполняет.
Какие инструменты использует в работе.

## Команда DevOps
В идеальном мире разработкой занимается достаточно большая команда, включающая в себя руководителей, которые в то же время являются и разработчиками, наравне с остальной командой. 

* CTO - технический директор
  * Team Leader:  https://habr.com/ru/post/446284/
  * Architect/Tech Leader (software architecture)
   * Project Manager
     * Developers
     * Frontend
     * Backend
     * Database
     * Mobile
     * DevOps
     * Software testing


## Архитектура
Устройство серверов-контейнеров позволяющее разрабатывать, тестировать и работать конечному продукту. continuous delivery (CD)/Continuous Integration (CI) - практики, когда команда выкладывает код в репозиторий, из которого код попадает на stage серверы, где разработчик может посмотреть результаты работы, на этом этапе становится понятно, не ломают ли нововведения общую инфраструктуру. 

Если все ок - код заливается на тестовые серверы, где уже команда тестировщиков может посмотреть на сколько все хорошо работает и не нарушены ли бизнес-процессы. 

Если все ок - код попадает на боевые серверы, доступные клиентам. 

Таким образом разработка остается невидимой для конечного пользователя. 


- Stage - серверы для разработки
- Test - серверы для тестирования
- Prod - серверы с конечной версией продукта
	

## Сервисная архитектура 

### Микросервисы

Планирование, взаимодействие

Почитать про:

Agile - система взаимодействия между участниками процесса разработки и запуска ПО, заказчиком ПО, нацеленная на быстрое внесение изменений в продукт. (https://rb.ru/story/agile-scrum-kanban/)
- [Agile-манифест](https://agilemanifesto.org/iso/ru/manifesto.html)

Jira - один из продуктов  [Atlassian.com](https://www.atlassian.com/), нацеленный на помощь в коммуникациях между участниками процесса разработки. Серия продуктов помогает взаимодействовать всем участникам процесса разработки. 

[Курсы по продуктам Atlassian](https://www.luxoft-training.ru/training/katalog_kursov/kursy-po-poduktam-atlassian/)


Что нужно знать?
Завести аккаунт в [Atlassian.com](https://www.atlassian.com/)

## Codebase

Устройство репозитория

Версии кода продукта:
- Stage - ветки разработчиков
- Test - ветки, проверенные на stage серверах
- Production - ветки, проверенные на тест серверах и готовые к переносу на боевые серверы.

Работа с кодом
- Tagging - маркировка кода, указание версий продукта.
- Branching - Разветвление, когда у разработчиков своя ветка, позволяющая вести разработку части продукта, не мешая остальным разработчикам.
- Merging - сращивание веток, когда весь код собирается в единую ветку с продуктом. 

Что нужно знать? 
- [GitHub](https://github.com)
- [GitLab](https://gitlab.com)
- [Книга Pro Git](https://git-scm.com/book/ru/v2)

Создать в каждой системе тестовый проект, попробовать поработать с ветками из консоли


## Базы данных
PostgreSQL 
- [link](https://ru.wikipedia.org/wiki/PostgreSQL)

## Автоматизация

### Системы автоматизации развертки серверов - Puppet, Chef, Ansible, Salt
- [link](https://habr.com/ru/post/211306/)

### Ansible
- [link](https://docs.ansible.com/)
- [Установка и настройка]( https://linux-notes.org/ustanovka-i-nastrojka-ansible-v-unix-linux/)
- [Плейбуки](https://habr.com/ru/company/express42/blog/254959/)
- [Jenkins](https://jenkins.io/)

## Виртуализация

### Docker
- [Запуск](https://habr.com/ru/post/346634/)
- [Готовые контейнеры](https://hub.docker.com/)

### Kubernetes
- [Основы](https://habr.com/ru/post/258443/)
- [Запуск кластера](https://habr.com/ru/post/348688/)

## Резервирование

## Тестирование

## Мониторинг

## Практика

## Составление резюме
