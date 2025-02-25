---
title: Сброс нумерации заказов
layout: default
---

В Api V9Preview1 была добавлена возможность сбрасывать нумерацию заказов внутри группы через Api. 

Для этого в Api была добавлен новый метод [`ResetOrderCounter`](https://iiko.github.io/front.api.sdk/v9/html/M_Resto_Front_Api_IOperationService_ResetOrderCounter.htm). Для его использования необходимо, чтобы кассовые смены на всех терминалах группы были закрыты. В результате работы метода - нумерация новых заказов начинается снова с 1.

Данный метод является аналогом настройки __Начинать с 1 нумерацию заказов в каждой кассовой смене__ в iikoOffice в разделе __[`Дополнительно`](https://ru.iiko.help/articles/iikooffice-8-7/topic-252/a/h2_1804485782)__, однако он позволяет проводить сброс нумерации заказов в лишь нужных ситуациях, без необходимости менять настройки iikoOffice.

