# NodeJS ✨🐢🚀✨

- [50 вопросов для собеседования на прикладного бекенд программиста](https://github.com/tshemsedinov/NodeJS-Interview-Questions/blob/main/README.md#50-вопросов-для-собеседования-на-прикладного-бекенд-программиста)
- [20 вопросов для собеседования на системного (платформенного) Node.js программиста](https://github.com/tshemsedinov/NodeJS-Interview-Questions/blob/main/README.md#20-вопросов-для-собеседования-на-системного-платформенного-nodejs-программиста)
- [Заметки по методике проведения собеседований](https://github.com/tshemsedinov/NodeJS-Interview-Questions/blob/main/README.md#заметки-по-методике-проведения-собеседований)

Если вас интересуют ответы, то тут у меня самый большой бесплатный курс по ноде, который обновляется каждый год: https://github.com/HowProgrammingWorks/Index/blob/master/Courses/NodeJS.md а тут новый практически курс с ревью кода, созвонами по 2 раза в неделю, ответами на вопросы, лайвкодингом и большим архивом решений даля практических задач: https://github.com/HowProgrammingWorks/Index/blob/master/Courses/NodeJS-2022-2023.md И там и там есть все ответы.

## 50 вопросов для собеседования на прикладного бекенд программиста

1. Что можно сделать с помощью for await с объектом request: IncomingMessage?
2. Чем в ноде нативно хешировать пароли и в каких случаях для этого нужны зависимости?
3. Какое API реализует nodejs/undici?
4. Чем современным заменить node:domain API?
5. Когда мы можем использовать синхронные версии операций с файлами из node:fs вместо асинхронных и на что обращать внимание, принимая такое решение?
6. Приведите лучшие практики для обработки ошибок в асинхронном коде.
7. Как в проектах на ноде могут появиться уязвимости? Объясните на выбор XSS, Path traversal, SQL injection, CSRF? Как от них защищаться?
8. Как возможно состояние гонки (race condition) в асинхронном программировании? И как от этого защищаться?
9. В чем плюсы и минусы разделения кода на .js и отдельно тайпинги .d.ts?
10. Приведите несколько типичных для Node.js паттернов проектирования (по GoF и не только) с примерами.
11. В чем заключается проблема толстых контролеров? (с примерами на ноде)
12. Приведите примеры протекания абстракций (типичных для ноды).
13. Как можно создать Singleton с помощью системы модульности в ноде?
14. Как проще всего реализовать паттерн Strategy на JavaScript (и где его использовать в ноде)?
15. Приведите пример паттерна Adapter из встроенных библиотек ноды (есть несколько).
16. Какой паттерн проектирования реализует EventEmitter?
17. Как связаны контракты EventEmitter и Readable?
18. Какие вы можете привести антипаттерны (или примеры плохого стиля) программирования для node.js?
19. Зачем нам следующие поля Error: error.cause, error.code, error.message, error.stack?
20. Как скопировать папку с вложенными файлами и папками с помощью node:fs?
21. Можем ли мы делать real-time приложения на Node.js?
22. Какие есть подходы к логированию? Их отличия, плюсы и минусы.
23. Где хранить секреты? (ключи api, точены и пароли от баз данных)
24. Почему нужно делать return await внутри асинхронных функций и методов а не возвращать промис?
25. Как не заблокировать обслуживание других пользователей, обрабатывая запрос от одного из них?
26. Что делать если обработка запроса привела к необходимости завершить процесс (ведь он обслуживает много запросов параллельно)?
27. Какие стили и парадигмы программирования вы используете в node.js приложениях? Почему?
28. В чем слабые стороны node.js? Что на ноде писать плохо или невозможно?
29. В чем разница между stateful and stateless подходами для node.js приложений? Как выбрать?
30. Как ограничить пропускную способность эндпоинта (кол-во запросов в единицу времени)?
31. В чем опасность примесей (mixins) для прикладного кода? (с типичными примерами на Node.js)
32. Как реализовать архитектурную границу в приложениях на node.js?
33. Что такое DI (внедрение зависимостей) и как его реализовать на ноде? (желательно несколько вариантов)
34. Почему middleware является антипаттерном? И как писать без него?
35. Как снизить зацепление кода в приложениях на node.js?
36. Почему нужно добавлять префикс node: при загрузке встроенных модулей?
37. Зачем нужен AbortController? Приведите примеры API, где он используется.
38. JSON сериализация и десериализация может работать долго и заблокировать поток, что с этим делать?
39. Как могут утечь все соединения из пула конекшенов к базе данных и как это предотвратить?
40. Как вы организовываете слой доступа к данным?
41. В чем преимущество async/await и промисов перед callback в ноде? Где невозможно обойтись без callback?
42. Что делать, если в двух частях одного приложения вам нужны разные версии npm зависимостей?
43. Какие Web API появились в ноде в последнее время и зачем их туда тянут?
44. Что можно использовать вместо устаревших pm2 и forever в современном мире?
45. Как сделать бизнес-логику независимой от фреймворка и от протокола, через который приходят запросы?
46. Почему нам больше ну нужны axios, request, node-fetch?
47. Для чего нам могут быть необходимы очереди внутри приложения и внешние MQ системы?
48. Чем может быть опасно, если зависимость патчит глобальные объекты, классы и прототипы?
49. Что такое Node.js LTS и что он нам дает?
50. Для чего нам Websocket, почему в 2023 брать socket.io плохой вариант и что брать для Websocket?

## 20 вопросов для собеседования на системного (платформенного) Node.js программиста

1. Чего не хватает в ESM, но есть (поддерживается) в CJS?
2. Для чего используется new Error.captureStackTrace?
3. Почему node.js не однопоточный? Докажите, что даже не был однопоточным.
4. Как связаны node:async_hooks и AsyncLocalStorage?
5. Какие в ноде встроенные средства сериализации аналогичны JSON только для бинарной сериализации?
6. Как следить за изменениями файлов и директорий на диске и какие с этим могут возникать проблемы?
7. Чем заменить deprecated: fs.exists и почему его выпиливают из ноды?
8. Что такое back pressure для стримов и какая проблема была бы без него?
9. Как защитить SharedArrayBuffer от записи из разных worker_threads?
10. Докажите, что любой модуль в ноде при загрузке оборачивается в функцию и создает замыкание?
11. Где в ноде используется паттерн Revealing constructor (открытый конструктор, есть много таких мест)?
12. Как сделать переопределение write для экземпляра Writable без создания класса наследника?
13. В чем причина медленных вызовов из JavaScript кода к аддонам на C, C++ или подключенных через N-API?
14. Что такое MessagePort и BroadcastChannel?
15. Чем отличаются fs.stat, fs.fstat, fs.lstat?
16. Почему важно выполнять правило eslint: consistent-return учитывая оптимизацию v8?
17. Зачем в ноде есть WASI и какие возможности он нам дает?
18. Что можно сделать при помощи node:vm (любые примеры)?
19. Какие вы знаете deprecated API и какова стратегия их вывода из употребления?
20. Какие вы знаете проблемы, баги и узкие места в node.js?
21. Объясните, как можно написать (или напишите) адаптеры асинхронности promisify и callbackify?
22. Почему у event loop есть фазы? Почему мало одной очереди?
23. Чем отличаются микротаски и макротаски?
24. В чем особенности обработки uncaught exceptions в Node.js?
25. Чем отличается nextTick, setImmediate, setTimeout, 
26. Зачем есть ref и unref у таймеров, сокетов, серверов и других подобных классов?
27. Почему Server.connections сделали deprecated и что как теперь получить подключения?
28. Перечислите основные случаи, приводящие к утечке памяти и как с этим бороться?
29. Чем отличается node:cluster и nodechild_process? И когда cluster может становиться узким местом?
30. В каких случаях нужно отключать автоматическую сборку мусора и брать ее вызов в свои руки?
31. Какие есть способы отладки приложений и в каких случаях вы их используете?
32. Как сбросить кеш require для определенной библиотеки? Как быть в случае ESM?
33. Откуда берутся идентификаторы __dirname и __filename, require и import, fetch и Array?
34. Почему следует отказаться от использования библиотеки node:url?
35. Какие можно предложить стратегии масштабирования для приложений на ноде? Сравните их.
36. Чем отличаются cpu-intensive, ram-intensive и io-intensive задачи? Приведите примеры.
37. Почему не нужно использовать process.on('multipleResolves', handler)?
38. Расскажите, на что влияет опция noDelay у серверов, метод setNoDelay у request и socket?
39. Как работает keep-alive в http протоколе и как мы можем управлять им из ноды?
40. Для чего используется модуль node:perf_hooks? И может ли он работать с воркерами?
41. Что вы думаете про экспериментально API итерируемых методов (filter, map, reduce) у стримов?
42. Какие вы знаете способы интернационализации приложений?
43. Используете ли вы встроенный test runner и библиотеку node:assert?
44. Какие вы использовали ключи при запуске ноды?
45. Как сдампить хип процесса и что с ним дальше делать?
46. Как построить flame graph?
47. Расскажите про ALPN и SNI и их поддержку в ноде.
48. Как реализовать автоматическую перезагрузку процесса нативными средствами при изменении кода?
49. Для чего нам модуль, который называется модуль, а именно node:module?
50. Как работать с самоподписанными SSL сертификатами? И в чем ограничение их использования?

## Заметки по методике проведения собеседований

Я сторонник того, чтобы давать людям на собесах возможность листать доки, гуглить и даже спрашивать у нейронок. Что должен проверять собес? Эффективность, способность решать задачи, а не задротство, зубрежку и феноменальную память. Если вы начнете это делать, то внезапно для себя выявите, что даже при этом многие люди не справляются, полный интернет шедевров говнокода, оверинженеринга и архитектурного маразма. Еще мне важно, чтобы человек показал свое субъективное мнение, даже эмоциональную позицию по отношению к конкретным решениям и технологиям, именно это он будет проявлять в работе. А что сейчас на собесах происходит: эффект ивентлупа — люди вызубрили и могут наизусть рассказать фазы и красиво объяснить, а применить для принятия решений в коде не смогут, т.е. оно ничего не дает им в каждодневной работе.
