Dia da Semana
=============

Calcula o dia da semana de uma determinada data.

 

Programa
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
[Data]--+ Dia da Semana +-->[dia]
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
[Date]--+ Week Day +-->[index of week]
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
[Date]--+ Day of Week +-->[day of week]
        |             |
        +--+ piece +--+
           | /sunday/monday/tuesday/wednesday/thursday/friday/saturday
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Terminal
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
$ pak Dia_da_Semana

> Data: 11/05/2016
    - dia = quarta-feira

> Data: 31/12/14
    - dia = sábado

> Data: (ENTER)
$
$ pak Week_Day

> Date: ?  (enter YYYY-MM-DD)

> Date: 2016-05-11
    - index of week = 4

> Date:
$
$pak Day_of_Week

> Date: 2016-05-11
    - day of week = wednesday

> Date: 14-12-31  (enter YYYY-MM-DD)

> Date: 2014-12-31
    - day of week = saturday

> Date: 
$
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
