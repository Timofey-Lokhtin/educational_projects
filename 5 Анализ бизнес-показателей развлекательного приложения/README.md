## Описание проекта

Развлекательное приложение Procrastinate Pro+ последние несколько месяцев терпит убытки, несмотря на огромные вложения в рекламу. Задача — разобраться в причинах и помочь компании выйти в плюс. 
Предстоит изучить:
* откуда приходят пользователи и какими устройствами они пользуются;
* сколько стоит привлечение пользователей из различных рекламных каналов;
* сколько денег приносит каждый клиент;
* когда расходы на привлечение клиента окупаются;
* какие факторы мешают привлечению клиентов.

## Навыки и инструменты

ICE, RICE, A/B tests, Python, pandas, seaborn, scipy

## Вывод

Для того, чтобы разобраться в причинах убытков Procrastinate Pro+ в течение последних нескольких месяцев, были загружены данные, проведена предобработка, определены функции для рассчета и анализа LTV, ROI, удержания и конверсии, проведен исследовательский анализ данных, проанализированы расходы на маркетинг и проведена оценка окупаемости рекламы на основании данных о пользователях, привлечённых с 1 мая по 27 октября 2019 года. Даны ответы на такие вопросы как: 
* откуда приходят пользователи и какими устройствами они пользуются;
* сколько стоит привлечение пользователей из различных рекламных каналов;
* сколько денег приносит каждый клиент;
* когда расходы на привлечение клиента окупаются;
* какие факторы мешают привлечению клиентов.

Пользователи на ПК конвертируются хуже, чем пользователи с другими устройствами.
Пользователи из США конвертируются в 2 раза лучше, чем пользователи из других стран, но хуже удерживаются, хотя и не в 2 раза.
Конверсия привлеченных из разных рекламных источников пользователей очень сильно отличается друг от друга. Больше 10% на 14ый день у FaceBoom, AdNonSence, lambdaMediaAds.
Удержание платящих пользователей, привлеченных рекламным источникам AdNonSense - около 3% и FaceBoom - около 1.5% на 14ый день, намного ниже, чем удержание пользователей, привлеченных другими источниками.

Основной причиной убытков Procrastinate Pro+ оказался резкий рост стоимости привлечения клиентов через один из основных рекламных источников - TipTop. Через него были привлечены 21% всех пользователей и 21% платящих пользователей. Пока CAC других маркетинговых каналов оставался примерно одинаковым в течение изучаемого периода времени, CAC TipTop вырос от 1.00 - 1 мая, до 3.50 - в конце октября. Также постоянные убытки приносили такие каналы как FaceBoom, AdNonSense. Так как пользователей из США привлекается намного больше, чем из остальных стран вместе взятых - 61829 из 93569 или 66.08% от общего числа, очень важно найти рекламный источник с низкой стоимостью привлечения для этой страны.

Рекомендую не привлекать клиентов через такие маркетинговые каналы как TipTop(высокая CAC, низкий ROI), FaceBoom(низкий ROI, высокая CAC, никзое удержание), AdNonSenseа(низкий ROI, никзое удержание), а увеличить вложение в рекламу через перспективный YRabbit(высокий ROI, низкая CAC) или MediaTornado(высокий ROI, низкая CAC) и выяснить, занимаются ли привлечением клиентов из США lambdaMediaAds(высокий ROI). 