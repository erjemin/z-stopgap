﻿# Страница http://z.msk.rsvo.local по умолчанию

Данный набор файлов размещается на сервере z.msk.rsvo.local в папке `~/default`.

Все незадействованные домены сервера `z.msk.rsvo.local` (10.3.1.135) редиректятся сюда и все запросы релоцируются (подменяются) на единую странику **NOT SERVISED**:
 
![Страничка NOT SERVISED](html/img/Title%20-%20z.msk.rsvo.local.png) 
 
 Таким образом в каталоге логов `~/default/logs` будут сохранятся все поступившие запросы с сохраннем полных URL к которым пытались получить доступ, а значит можно будет обнаружить сканеры и попыки поиска уязвимостей на не обслуживаемых доменах.

Всем пис.  

