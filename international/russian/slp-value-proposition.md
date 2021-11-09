# 🇷🇺 Angle’s Value Proposition for Standard Liquidity Providers

- Based on: [Angle’s Value Proposition for Standard Liquidity Providers Blog Article](https://blog.angle.money/angles-value-proposition-for-standard-liquidity-providers-2164a150d2f)
- Last Updated: 8th of October 2021
- Author: Liquidus#2384

## В чем заключается ценность протокола Angle для Стандартных провайдеров ликвидности?

Стандартные провайдеры ликвидности (SLPs) предоставляют ликвидность в залоговые пулы, получая взамен токены доходности, так называемые sanTokens (например, токены sanUSDC_EUR получают в случае предоставления USDC для поддержки стейблкоина agEUR).

Таким образом, они создают избыточное обеспечение протокола и добавляют еще один уровень безопасности для держателей токенов agTokens: вместе с избыточным обеспечением, накопленным протоколом, их депозиты составляют страховой фонд протокола.

В этой статье мы расскажем, какие источники доходности существуют для Стандартных провайдеров ликвидности в Angle.

## Общие тезисы

- Стандартные провайдеры ликвидности Angle получают доход от своих депозитов, как и «стандартные» провайдеры ликвидности в протоколах Compound или Aave;
- Angle — это протокол стейблкоинов, но при этом он использует такие стратегии, как Yearn, для накопления доходности по своему обеспечению;
- благодаря этому, а также благодаря мультипликативному эффекту на резервы протокола, Стандартные провайдеры ликвидности могут получить более высокую доходность с Angle, чем на других платформах;
- Стандартные провайдеры ликвидности также зарабатывают часть комиссий за транзакции пользователей при выпуске или обратном обмене (сжигании) стейблкоинов, без риска непостоянной потери (impermanent loss);
- токены sanTokens можно отправить в стейкинг для получения токенов управления ANGLE.

## SLPs: “продвинутые” провайдеры ликвидности

В качестве вознаграждения за предоставление ликвидности протоколу Стандартные провайдеры ликвидности могут получить значительно более высокую доходность, чем на других традиционных платформах. Мы называем это мультипликативным эффектом.

Мультипликативный эффект возникает из-за того, что протокол инвестирует средства пользователей, Стандартных провайдеров ликвидности и Хеджирующих агентов в стратегии доходности, однако полученная прибыль распределяется только между Стандартными провайдерами ликвидности и протоколом.

Например, предположим, что протокол имеет в общей сложности 150 USDC, 20 из которых были предоставлены Стандартными провайдерами ликвидности. Допустим, между Стандарными провайдерами ликвидности распределяется 60% прибыли (остальная часть идет в протокол для поддержания избыточного обеспечения), а протокол инвестирует 80% своих средств с доходностью 10%. В таком случае, Стандартные провайдеры ликвидности получат
80% _ 150 _ 10% \* 60% = 7.2 USDC,
что составляет 36% реальной доходности при стратегии 10%.

Таким образом, Стандартные провайдеры ликвидности получают хороший множитель x3,6 на свои инвестиции по сравнению с тем, что они заработали бы, инвестируя при стратегии 10% самостоятельно или с помощью другого протокола, такого как Yearn.

Для того, чтобы иметь доступ к таким стратегиям с 10% APY, протокол взял за основу некоторые из стратегий Yearn, пытаясь оптимизировать их для получения большей доходности, чем в Compound и Aave. Однако в будущем возможно добавление и других, более прибыльных стратегий получения доходности.

## Вознаграждение в виде комиссий за транзакции

Помимо прибыли от стратегий получения доходности, Стандартные провайдеры ликвидности получают часть комиссий за транзакции пользователей при выпуске или обратном обмене (сжигании) стейблкоинов, аналогично провайдерам ликвидности на таких площадках как Uniswap или SushiSwap.

Основное отличие заключается в том, что пользователь, становясь Стандартным провайдером ликвидности в Angle, не испытывает непостоянных потерь (impermanent loss), а также отсутствует необходимость предоставлять два актива. Единственный риск заключается в том, что при недостаточном обеспечении протокола им, возможно, придется заплатить небольшое проскальзывание (эквивалентное комиссии за транзакцию) при выводе средств.

## Награды в виде токенов управления

Предоставляя дополнительную ликвидность в качестве страховки, Стандартные провайдеры ликвидности играют очень важную роль в протоколе. Поэтому они могут получать вознаграждение за помощь протоколу в виде токенов управления ANGLE путем стейкинга своих токенов sanToken, что дополнительно стимулирует их участвовать в управлении протоколом.