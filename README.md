# Домашнее задание к занятию «Сетевое взаимодействие в K8S. Часть 2»
### Задание 1. Создать Deployment приложений backend и frontend
> Создать Deployment приложения frontend из образа nginx с количеством реплик 3 шт.

![img.png](img/img.png)

> Создать Deployment приложения backend из образа multitool.

![img_1.png](img/img_1.png)

> Добавить Service, которые обеспечат доступ к обоим приложениям внутри кластера.

![img_2.png](img/img_2.png)

> Продемонстрировать, что приложения видят друг друга с помощью Service.

![img_3.png](img/img_3.png)
![img_4.png](img/img_4.png)

> Предоставить манифесты Deployment и Service в решении, а также скриншоты или вывод команды п.4.

[Манифесты тут](./manifest)

---
### Задание 2. Создать Ingress и обеспечить доступ к приложениям снаружи кластера

> Включить Ingress-controller в MicroK8S.

![img.png](img.png)

> Создать Ingress, обеспечивающий доступ снаружи по IP-адресу кластера MicroK8S так, чтобы при запросе только по адресу открывался frontend а при добавлении /api - backend.
 
![img_1.png](img_1.png)
 
> Продемонстрировать доступ с помощью браузера или curl с локального компьютера.
 
![img_2.png](img_2.png)
 
> Предоставить манифесты и скриншоты или вывод команды п.2.

Скриншоты предоставлен, [вот тут манифест](./manifest/ingress.yaml)