# mcal: orden 'cal' mejorada. <h1>

Comando mejorado de la orden '*bash*' **cal**, la cual presenta un calendario en función
de los parámtros pasados.

Uso: **mcal** *[mes] [año]*

  donde:

    [mes] respesentado entre [1..12] o [ene..dic] o [enero..diciembre],
                                       [jan..dec] o [january..december].
    [año] representado entre [1..9999].

  Por ejemplo:

    mcal          Presentará el mes y año actual.
    mcal -help    Muestra esta ayuda.
    mcal jan      Presentará el mes enero (january en inglés), y el año actual.
    mcal 10 2017  Presentará el mes octubre del año 2017.
    mcal 2017     Presentará el calendario completo del año 2017.
    mcal 13       Presentará el calendario completo del año 13.
    mcal [1..12]  Presentará el calendario del mes indicado para el año actual.

**(C)JuanRa Hortal-2018**
