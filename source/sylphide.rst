Танец Сильфиды
==============

Многие знают про Гейзенбаг: если программу запускать - баг есть,
если отлаживать и логировать - бага нет, в код смотришь - всё как нужно.
Возможные причины этого (если вы отлаживали такое, знаете и без меня), например,
печать в stdout, по-умолчанию он сбрасывает буфер, а если не вызывать его,
буфер не сбросится. Ещё бывает, в динамических языках это доступ до аттрибута - вы его
запросили, а он появился, а не должен был в нормальном потоке исполнения
или был какой-то fallback на неявный метод.

Как оказалось, есть многие другие, но менее известные (Шрёдинбаг, например).

Одна из самых известных таких "шуток" это закон Мёрфи, который не закон,
а житейская мудрость и небольшое обобщение статистики и когнитивных искажений
человека. Я уверен, вы подтверждали на своём опыте его правдивость не раз,
как и все мы.

Есть что-то схожее и называется эффект Паули, когда высокотехнологичная (и, видимо,
хрупкая) аппаратура не работает в присутствии "сильного" человека
(вашего опытного руководителя, учителя и проч.), и демонстрирует вашу
недостаточную подготовку к эксперименту. В добавок у физиков
это описывает увеличивающуюся пропасть между теорией и практикой
(согласно wiki, лично я не видел живых физиков "за работой").

Но с недавних пор, я придумал называть ситуацию, в которой часто оказываюсь,
танцем Сильфиды. 

Сильфида это балет, героиня которого фея, явившаяся Джеймсу во сне,
в которую он и влюбился.
Главный герой разрушает свою собственную жизнь и пленит Сильфиду хитростью.
Сильфида погибает от плена, а герой остаётся один и у "разбитого корыта"
(но это из другого "балета", как говорится).
Поэтому, можно сказать, что Сильфида - это ошибка которой нет.
Вы думаете, что у вас есть ошибка 
и преследуете её, отлаживаете, переписываете, а потом оказывается,
что это было напрасно и проблемы в изначальной постановке вовсе нет.

Так же, можно сослаться на известную цитату Кнута о том, что корень всех
зол это преждевременная оптимизация.

Так же, бывает и при дизайне кроссфункциональных команд
из 3-4 разработчиков и микросервисной архитектуры. При 3-4 разработчиках
всего в организации.

Но ваше время и силы уже потрачены. Послушали злую колдунью.

По-моему, это забавно, остальные схожие явления связаны с учёными,
а здесь будет отсылка к балету.
