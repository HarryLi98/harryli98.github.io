---
title: "First name Chess Olympiad"
author: "Harry Li"
date: 2023-01-07
tags: ["chess", "dplyr"]
---













# Intro
Jan Gustafsson often asks during his chess commentary: *"which name would have the strongest chess team?"* This blog answers that question!

# Strongest Olympiad teams
The first name chess Olympiad would comprise of teams of four, whose players have the same (or very similar) first names. Alexander, Vladimir and Jan would be the top seeds! Here's a list of potential teams with an average rating greater than 2600, using the January 2023 classical ratings.


|first_name    |last_name       |country | rating| birthday| average_rating|
|:-------------|:---------------|:-------|------:|--------:|--------------:|
|Alexander     |Grischuk        |RUS     |   2745|     1983|        2683.00|
|Alexandr      |Predke          |FID     |   2684|     1994|        2683.00|
|Alexander     |Morozevich      |RUS     |   2659|     1977|        2683.00|
|Alexander     |Ipatov          |TUR     |   2644|     1993|        2683.00|
|Vladimir      |Kramnik         |RUS     |   2753|     1975|        2677.50|
|Vladimir      |Fedoseev        |FID     |   2674|     1995|        2677.50|
|Vladimir      |Malakhov        |FID     |   2650|     1980|        2677.50|
|Vladimir      |Afromeev        |RUS     |   2633|     1954|        2677.50|
|Ian           |Nepomniachtchi  |RUS     |   2793|     1990|        2674.75|
|Jan-Krzysztof |Duda            |POL     |   2729|     1998|        2674.75|
|Jan           |Gustafsson      |GER     |   2618|     1979|        2674.75|
|Jan-Christian |Schroeder       |GER     |   2559|     1998|        2674.75|
|Maxime        |Vachier-Lagrave |FRA     |   2737|     1990|        2661.75|
|Maxim         |Matlakov        |RUS     |   2662|     1991|        2661.75|
|Maksim        |Chigaev         |FID     |   2632|     1996|        2661.75|
|Maxim         |Rodshtein       |ISR     |   2616|     1989|        2661.75|
|Sergey        |Karjakin        |RUS     |   2747|     1990|        2659.75|
|Sergey A.     |Fedorchuk       |UKR     |   2640|     1981|        2659.75|
|Sergei        |Rublevsky       |RUS     |   2637|     1974|        2659.75|
|Sergei        |Movsesian       |ARM     |   2615|     1978|        2659.75|
|Dmitry        |Andreikin       |FID     |   2729|     1990|        2657.50|
|Dmitry        |Jakovenko       |RUS     |   2682|     1983|        2657.50|
|Dmitry        |Kononenko       |UKR     |   2613|     1988|        2657.50|
|Dmitrij       |Kollars         |GER     |   2606|     1999|        2657.50|
|David         |Navara          |CZE     |   2682|     1985|        2656.25|
|David         |Anton Guijarro  |ESP     |   2679|     1995|        2656.25|
|David W L     |Howell          |ENG     |   2663|     1990|        2656.25|
|David         |Baramidze       |GER     |   2601|     1988|        2656.25|
|Evgeny        |Tomashevsky     |RUS     |   2694|     1987|        2651.75|
|Evgeniy       |Najer           |RUS     |   2662|     1977|        2651.75|
|Evgeny        |Bareev          |CAN     |   2631|     1966|        2651.75|
|Evgeny        |Shtembuliak     |UKR     |   2620|     1999|        2651.75|
|Daniil        |Dubov           |RUS     |   2708|     1996|        2640.50|
|Daniel        |Naroditsky      |USA     |   2622|     1995|        2640.50|
|Daniele       |Vocaturo        |ITA     |   2619|     1989|        2640.50|
|Daniel        |Dardha          |BEL     |   2613|     2005|        2640.50|
|Peter         |Svidler         |FID     |   2683|     1976|        2638.00|
|Peter         |Leko            |HUN     |   2663|     1979|        2638.00|
|Peter Heine   |Nielsen         |DEN     |   2618|     1973|        2638.00|
|Peter         |Michalik        |CZE     |   2588|     1990|        2638.00|
|Matthew D     |Sadler          |ENG     |   2694|     1974|        2633.75|
|Matthias      |Bluebaum        |GER     |   2661|     1997|        2633.75|
|Mateusz       |Bartel          |POL     |   2615|     1985|        2633.75|
|Matthieu      |Cornette        |FRA     |   2565|     1985|        2633.75|
|Ivan          |Cheparinov      |BUL     |   2659|     1986|        2633.50|
|Ivan          |Saric           |CRO     |   2657|     1990|        2633.50|
|Ivan          |Popov           |RUS     |   2627|     1990|        2633.50|
|Ivan          |Salgado Lopez   |ESP     |   2591|     1991|        2633.50|
|Alexey        |Sarana          |FID     |   2668|     2000|        2628.25|
|Alexei        |Shirov          |ESP     |   2666|     1972|        2628.25|
|Aleksey       |Dreev           |RUS     |   2606|     1969|        2628.25|
|Alexey        |Korotylev       |RUS     |   2573|     1977|        2628.25|
|Igors         |Rausis          |FID     |   2685|     1961|        2627.75|
|Igor          |Kovalenko       |UKR     |   2674|     1988|        2627.75|
|Igor          |Lysyj           |RUS     |   2597|     1987|        2627.75|
|Igor          |Berdichevski    |RUS     |   2555|     1964|        2627.75|
|Vladislav     |Artemiev        |RUS     |   2701|     1998|        2627.25|
|Vladislav     |Tkachiev        |FRA     |   2660|     1973|        2627.25|
|Vladislav     |Kovalev         |FID     |   2623|     1994|        2627.25|
|Vladislav     |Borovikov       |UKR     |   2525|     1973|        2627.25|
|Andrey        |Esipenko        |FID     |   2675|     2002|        2626.75|
|Andrei        |Volokitin       |UKR     |   2666|     1986|        2626.75|
|Andriy        |Vovk            |UKR     |   2597|     1991|        2626.75|
|Andrey        |Baryshpolets    |UKR     |   2569|     1991|        2626.75|
|Sam           |Shankland       |USA     |   2710|     1991|        2625.25|
|Samuel        |Sevian          |USA     |   2687|     2000|        2625.25|
|Samvel        |Ter-Sahakyan    |ARM     |   2605|     1993|        2625.25|
|Samir         |Sahidi          |SVK     |   2499|     2003|        2625.25|
|Anton         |Korobov         |UKR     |   2651|     1985|        2624.75|
|Anton         |Kovalyov        |CAN     |   2631|     1992|        2624.75|
|Anton         |Demchenko       |FID     |   2625|     1987|        2624.75|
|Anton         |Filippov        |UZB     |   2592|     1986|        2624.75|
|Yuriy         |Kryvoruchko     |UKR     |   2649|     1986|        2616.75|
|Yuriy         |Kuzubov         |UKR     |   2618|     1990|        2616.75|
|Yuri          |Drozdovskij     |UKR     |   2616|     1984|        2616.75|
|Yuri          |Kruppa          |UKR     |   2584|     1964|        2616.75|
|Michael       |Adams           |ENG     |   2688|     1971|        2612.50|
|Mikhail Al.   |Antipov         |FID     |   2599|     1997|        2612.50|
|Mikhail       |Gurevich        |BEL     |   2586|     1959|        2612.50|
|Mikhail       |Kobalia         |RUS     |   2577|     1978|        2612.50|
|Boris         |Gelfand         |ISR     |   2667|     1968|        2608.50|
|Boris         |Alterman        |ISR     |   2608|     1970|        2608.50|
|Boris         |Grachev         |RUS     |   2592|     1986|        2608.50|
|Boris         |Avrukh          |ISR     |   2567|     1978|        2608.50|
|Pavel         |Eljanov         |UKR     |   2706|     1983|        2602.75|
|Pavel         |Ponkratov       |RUS     |   2577|     1988|        2602.75|
|Pavel         |Maletin         |RUS     |   2575|     1986|        2602.75|
|Pavel V.      |Tregubov        |FID     |   2553|     1971|        2602.75|

# Common names' players
Here are the list of players who share a common name and have a classical rating greater than 2500.

<table class="kable_wrapper">
<tbody>
  <tr>
   <td> 

|first_name |last_name    |country | rating| birthday|
|:----------|:------------|:-------|------:|--------:|
|Alexander  |Grischuk     |RUS     |   2745|     1983|
|Alexandr   |Predke       |FID     |   2684|     1994|
|Alexander  |Morozevich   |RUS     |   2659|     1977|
|Alexander  |Ipatov       |TUR     |   2644|     1993|
|Aleksandar |Indjic       |SRB     |   2641|     1995|
|Alexander  |Onischuk     |USA     |   2640|     1975|
|Aleksandr  |Rakhmanov    |RUS     |   2635|     1989|
|Alexander  |Areshchenko  |UKR     |   2631|     1986|
|Alexander  |Donchenko    |GER     |   2627|     1998|
|Alexander  |Riazantsev   |RUS     |   2626|     1985|
|Alexander  |Motylev      |FID     |   2624|     1979|
|Alexander  |Chernin      |HUN     |   2614|     1960|
|Alexander  |Galkin       |RUS     |   2611|     1979|
|Alexander  |Khalifman    |RUS     |   2608|     1966|
|Alexandr   |Fier         |BRA     |   2602|     1988|
|Alexander  |Zubov        |UKR     |   2598|     1983|
|Aleksandr  |Shimanov     |RUS     |   2581|     1992|
|Alexander  |Goloshchapov |UKR     |   2578|     1978|
|Alexander  |Moiseenko    |UKR     |   2577|     1980|
|Aleksandra |Goryachkina  |RUS     |   2576|     1998|
|Aleksandr  |Lenderman    |USA     |   2572|     1989|
|Alexander  |Graf         |GER     |   2558|     1962|
|Alexander  |Goldin       |USA     |   2542|     1964|
|Alexander  |Volzhin      |RUS     |   2540|     1971|
|Aleksander |Mista        |POL     |   2534|     1983|
|Alexandar  |Budnikov     |RUS     |   2530|     1967|
|Alexander  |Huzman       |ISR     |   2526|     1962|
|Alexandre  |Danin        |RUS     |   2525|     1986|
|Alexander  |Rustemov     |RUS     |   2525|     1973|
|Alexandr   |Kharitonov   |RUS     |   2522|     1986|
|Alexandra  |Kosteniuk    |FID     |   2519|     1984|
|Alexandre  |Lesiege      |CAN     |   2510|     1975|
|Alexandr   |Triapishko   |RUS     |   2506|     2000|
|Alexandre  |Qashashvili  |GEO     |   2505|     1975|
|Aleksandr  |Poluljahov   |RUS     |   2503|     1965|

 </td>
   <td> 

|first_name |last_name   |country | rating| birthday|
|:----------|:-----------|:-------|------:|--------:|
|Alexey     |Sarana      |FID     |   2668|     2000|
|Alexei     |Shirov      |ESP     |   2666|     1972|
|Aleksey    |Dreev       |RUS     |   2606|     1969|
|Alexey     |Korotylev   |RUS     |   2573|     1977|
|Alexey     |Kuzmin      |RUS     |   2540|     1963|
|Aleksey    |Sorokin     |RUS     |   2537|     2000|
|Aleksey    |Goganov     |RUS     |   2526|     1991|
|Aleksei    |Lugovoi     |RUS     |   2507|     1975|
|Aleksei    |Pridorozhni |RUS     |   2504|     1981|
|Alexei     |Kornev      |RUS     |   2500|     1976|

 </td>
   <td> 

|first_name |last_name     |country | rating| birthday|
|:----------|:-------------|:-------|------:|--------:|
|Andrey     |Esipenko      |FID     |   2675|     2002|
|Andrei     |Volokitin     |UKR     |   2666|     1986|
|Andriy     |Vovk          |UKR     |   2597|     1991|
|Andrey     |Baryshpolets  |UKR     |   2569|     1991|
|Andrey     |Rychagov      |RUS     |   2547|     1979|
|Andrey     |Stukopin      |RUS     |   2546|     1994|
|Andrey     |Shariyazdanov |RUS     |   2541|     1976|
|Andrei     |Sokolov       |LAT     |   2516|     1972|
|Andrey     |Kvon          |UZB     |   2513|     1989|
|Andrey     |Orlov         |FID     |   2512|     1977|
|Andrey     |Zhigalko      |BLR     |   2509|     1985|
|Andrei     |Shchekachev   |FRA     |   2506|     1972|
|Andrey     |Drygalov      |RUS     |   2502|     1999|
|Andrey     |Sumets        |UKR     |   2502|     1980|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Anton      |Korobov   |UKR     |   2651|     1985|
|Anton      |Kovalyov  |CAN     |   2631|     1992|
|Anton      |Demchenko |FID     |   2625|     1987|
|Anton      |Filippov  |UZB     |   2592|     1986|
|Anton      |Smirnov   |AUS     |   2586|     2001|
|Anton      |Shomoev   |RUS     |   2555|     1981|
|Antonios   |Pavlidis  |GRE     |   2554|     1993|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Bartosz    |Socko     |POL     |   2620|     1978|
|Bartlomiej |Heberla   |POL     |   2567|     1985|
|Bart       |Michiels  |BEL     |   2556|     1986|
|Bartlomiej |Macieja   |POL     |   2525|     1977|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Boris      |Gelfand   |ISR     |   2667|     1968|
|Boris      |Alterman  |ISR     |   2608|     1970|
|Boris      |Grachev   |RUS     |   2592|     1986|
|Boris      |Avrukh    |ISR     |   2567|     1978|
|Boris      |Savchenko |RUS     |   2552|     1986|
|Boris V.   |Spassky   |RUS     |   2548|     1937|
|Boris      |Gulko     |USA     |   2542|     1947|

 </td>
   <td> 

|first_name         |last_name |country | rating| birthday|
|:------------------|:---------|:-------|------:|--------:|
|Christopher Woojin |Yoo       |USA     |   2584|     2006|
|Christopher        |Lutz      |GER     |   2527|     1971|
|Christopher        |Noe       |GER     |   2516|     1996|
|Christopher        |Repka     |SVK     |   2511|     1998|

 </td>
   <td> 

|first_name     |last_name      |country | rating| birthday|
|:--------------|:--------------|:-------|------:|--------:|
|Daniil         |Dubov          |RUS     |   2708|     1996|
|Daniel         |Naroditsky     |USA     |   2622|     1995|
|Daniele        |Vocaturo       |ITA     |   2619|     1989|
|Daniel         |Dardha         |BEL     |   2613|     2005|
|Daniel         |Stellwagen     |NED     |   2605|     1987|
|Daniil         |Yuffa          |ESP     |   2604|     1997|
|Daniel         |Fridman        |GER     |   2595|     1976|
|Daniel         |Forcen Esteban |ESP     |   2576|     1994|
|Daniil         |Lintchevski    |RUS     |   2551|     1990|
|Danyyil        |Dvirnyy        |ITA     |   2548|     1990|
|Daniel         |Alsina Leal    |ESP     |   2520|     1988|
|Daniel Eduardo |Pulvett Marin  |ESP     |   2509|     1991|
|Daniel         |Sadzikowski    |POL     |   2503|     1994|

 </td>
   <td> 

|first_name |last_name      |country | rating| birthday|
|:----------|:--------------|:-------|------:|--------:|
|David      |Navara         |CZE     |   2682|     1985|
|David      |Anton Guijarro |ESP     |   2679|     1995|
|David W L  |Howell         |ENG     |   2663|     1990|
|David      |Baramidze      |GER     |   2601|     1988|
|David      |Paravyan       |RUS     |   2586|     1998|
|David      |Arutinian      |GEO     |   2549|     1984|
|David      |Gavrilescu     |ROU     |   2522|     2003|
|David      |Zilberstein    |ITA     |   2500|     1941|

 </td>
   <td> 

|first_name |last_name    |country | rating| birthday|
|:----------|:------------|:-------|------:|--------:|
|Denis      |Khismatullin |RUS     |   2594|     1984|
|Denis      |Kadric       |MNE     |   2584|     1995|
|Dennis     |Wagner       |GER     |   2584|     1997|
|Denis      |Lazavik      |BLR     |   2532|     2006|

 </td>
   <td> 

|first_name |last_name   |country | rating| birthday|
|:----------|:-----------|:-------|------:|--------:|
|Dmitry     |Andreikin   |FID     |   2729|     1990|
|Dmitry     |Jakovenko   |RUS     |   2682|     1983|
|Dmitry     |Kononenko   |UKR     |   2613|     1988|
|Dmitrij    |Kollars     |GER     |   2606|     1999|
|Dmitry     |Kokarev     |RUS     |   2588|     1982|
|Dmitry     |Obolenskikh |RUS     |   2536|     1985|
|Dmitriy    |Khegay      |RUS     |   2532|     1997|
|Dmitry     |Gordievsky  |RUS     |   2517|     1996|
|Dmitry     |Bocharov    |RUS     |   2516|     1982|
|Dmitry     |Kryakvin    |RUS     |   2505|     1984|

 </td>
   <td> 

|first_name |last_name    |country | rating| birthday|
|:----------|:------------|:-------|------:|--------:|
|Eric       |Hansen       |CAN     |   2609|     1992|
|Erik       |Van den Doel |NED     |   2581|     1979|
|Erik       |Blomqvist    |SWE     |   2538|     1990|

 </td>
   <td> 

|first_name |last_name      |country | rating| birthday|
|:----------|:--------------|:-------|------:|--------:|
|Evgeny     |Tomashevsky    |RUS     |   2694|     1987|
|Evgeniy    |Najer          |RUS     |   2662|     1977|
|Evgeny     |Bareev         |CAN     |   2631|     1966|
|Evgeny     |Shtembuliak    |UKR     |   2620|     1999|
|Evgeny     |Romanov        |NOR     |   2596|     1988|
|Evgenij    |Miroshnichenko |UKR     |   2589|     1978|
|Evgeny     |Alekseev       |RUS     |   2575|     1985|
|Evgenij    |Agrest         |SWE     |   2567|     1966|
|Evgeny     |Postny         |ISR     |   2556|     1981|
|Evgeny     |Pigusov        |RUS     |   2555|     1961|
|Evgeny     |Prokopchuk     |RUS     |   2523|     1978|
|Evgeny     |Shaposhnikov   |RUS     |   2517|     1981|
|Evgeny     |Ermakov        |RUS     |   2513|     1965|

 </td>
   <td> 

|first_name |last_name    |country | rating| birthday|
|:----------|:------------|:-------|------:|--------:|
|Francisco  |Vallejo Pons |ESP     |   2710|     1982|
|Francesco  |Rambaldi     |ITA     |   2569|     1999|
|Francesco  |Sonis        |ITA     |   2558|     2002|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Grigoriy   |Oparin    |USA     |   2670|     1997|
|Grzegorz   |Gajewski  |POL     |   2594|     1985|
|Gregory    |Kaidanov  |USA     |   2557|     1959|
|Grzegorz   |Nasuta    |POL     |   2550|     1996|
|Grigory    |Serper    |USA     |   2522|     1969|
|Grigor     |Grigorov  |BUL     |   2510|     1987|

 </td>
   <td> 

|first_name     |last_name    |country | rating| birthday|
|:--------------|:------------|:-------|------:|--------:|
|Igors          |Rausis       |FID     |   2685|     1961|
|Igor           |Kovalenko    |UKR     |   2674|     1988|
|Igor           |Lysyj        |RUS     |   2597|     1987|
|Igor           |Berdichevski |RUS     |   2555|     1964|
|Igor           |Janik        |POL     |   2535|     2000|
|Igor           |Novikov      |USA     |   2527|     1962|
|Igor           |Koniushkov   |RUS     |   2514|     1962|
|Igor           |Khenkin      |GER     |   2508|     1968|
|Igor           |Miladinovic  |SRB     |   2507|     1974|
|Igor-Alexandre |Nataf        |FRA     |   2506|     1978|

 </td>
   <td> 

|first_name |last_name   |country | rating| birthday|
|:----------|:-----------|:-------|------:|--------:|
|Illya      |Nyzhnyk     |UKR     |   2654|     1996|
|Ilia       |Smirin      |ISR     |   2596|     1968|
|Ilya       |Gurevich    |USA     |   2586|     1972|
|Ilia       |Iljiushenok |RUS     |   2543|     1993|
|Ilja       |Zaragatski  |GER     |   2516|     1985|

 </td>
   <td> 

|first_name |last_name     |country | rating| birthday|
|:----------|:-------------|:-------|------:|--------:|
|Ivan       |Cheparinov    |BUL     |   2659|     1986|
|Ivan       |Saric         |CRO     |   2657|     1990|
|Ivan       |Popov         |RUS     |   2627|     1990|
|Ivan       |Salgado Lopez |ESP     |   2591|     1991|
|Ivan       |Sokolov       |NED     |   2588|     1968|
|Ivan       |Bocharov      |RUS     |   2559|     1990|
|Ivan       |Smikovski     |RUS     |   2534|     1972|
|Ivan       |Ivanisevic    |SRB     |   2531|     1977|
|Ivan       |Schitco       |MDA     |   2515|     2003|
|Ivan       |Rozum         |RUS     |   2513|     1991|

 </td>
   <td> 

|first_name    |last_name      |country | rating| birthday|
|:-------------|:--------------|:-------|------:|--------:|
|Ian           |Nepomniachtchi |RUS     |   2793|     1990|
|Jan-Krzysztof |Duda           |POL     |   2729|     1998|
|Jan           |Gustafsson     |GER     |   2618|     1979|
|Jan-Christian |Schroeder      |GER     |   2559|     1998|
|Jan           |Smeets         |NED     |   2558|     1985|
|Jan           |Markos         |SVK     |   2555|     1985|
|Jan           |Werle          |NED     |   2550|     1984|
|Ian           |Rogers         |AUS     |   2545|     1960|
|Jan H         |Timman         |NED     |   2526|     1951|
|Jan           |Krejci         |CZE     |   2522|     1992|
|Jan           |Bernasek       |CZE     |   2506|     1986|
|Jan           |Smejkal        |CZE     |   2504|     1946|

 </td>
   <td> 

|first_name |last_name  |country | rating| birthday|
|:----------|:----------|:-------|------:|--------:|
|Kirill     |Alekseenko |FID     |   2686|     1997|
|Kirill     |Shevchenko |UKR     |   2662|     2002|
|Kiril      |Georgiev   |MKD     |   2546|     1965|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Konstantin |Sakaev    |RUS     |   2589|     1974|
|Konstantin |Tarlev    |UKR     |   2589|     1987|
|Konstantin |Maslak    |RUS     |   2555|     1984|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Matthew D  |Sadler    |ENG     |   2694|     1974|
|Matthias   |Bluebaum  |GER     |   2661|     1997|
|Mateusz    |Bartel    |POL     |   2615|     1985|
|Matthieu   |Cornette  |FRA     |   2565|     1985|
|Matthias   |Wahls     |GER     |   2541|     1968|

 </td>
   <td> 

|first_name |last_name       |country | rating| birthday|
|:----------|:---------------|:-------|------:|--------:|
|Maxime     |Vachier-Lagrave |FRA     |   2737|     1990|
|Maxim      |Matlakov        |RUS     |   2662|     1991|
|Maksim     |Chigaev         |FID     |   2632|     1996|
|Maxim      |Rodshtein       |ISR     |   2616|     1989|
|Maxime     |Lagarde         |FRA     |   2583|     1994|
|Maxim      |Turov           |RUS     |   2565|     1979|
|Maxim      |Vavulin         |FID     |   2552|     1998|
|Maxim      |Dlugy           |USA     |   2523|     1966|

 </td>
   <td> 

|first_name  |last_name     |country | rating| birthday|
|:-----------|:-------------|:-------|------:|--------:|
|Michael     |Adams         |ENG     |   2688|     1971|
|Mikhail Al. |Antipov       |FID     |   2599|     1997|
|Mikhail     |Gurevich      |BEL     |   2586|     1959|
|Mikhail     |Kobalia       |RUS     |   2577|     1978|
|Michael     |Roiz          |ISR     |   2577|     1983|
|Mikhail     |Demidov       |RUS     |   2568|     1992|
|Mikhail     |Panarin       |RUS     |   2562|     1983|
|Mikheil     |Mchedlishvili |GEO     |   2553|     1979|
|Michal      |Krasenkow     |POL     |   2541|     1963|
|Michael     |Wilder        |USA     |   2540|     1962|
|Michail     |Brodsky       |UKR     |   2524|     1969|
|Mikhail     |Mozharov      |RUS     |   2521|     1990|
|Michal      |Olszewski     |POL     |   2521|     1989|
|Michael     |Prusikin      |GER     |   2514|     1978|
|Mikhail     |Kazakov       |UKR     |   2513|     1972|
|Michael     |Brown         |USA     |   2509|     1997|
|Michael F   |Stean         |ENG     |   2500|     1953|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Nikita     |Vitiugov  |FID     |   2723|     1987|
|Nikita     |Meshkovs  |LAT     |   2576|     1994|
|Nikita     |Afanasiev |RUS     |   2562|     2000|
|Nikita     |Petrov    |RUS     |   2535|     1996|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Pavel      |Eljanov   |UKR     |   2706|     1983|
|Pavel      |Ponkratov |RUS     |   2577|     1988|
|Pavel      |Maletin   |RUS     |   2575|     1986|
|Pavel V.   |Tregubov  |FID     |   2553|     1971|
|Pavel      |Smirnov   |RUS     |   2545|     1982|
|Pavel      |Anisimov  |RUS     |   2523|     1986|

 </td>
   <td> 

|first_name  |last_name |country | rating| birthday|
|:-----------|:---------|:-------|------:|--------:|
|Peter       |Svidler   |FID     |   2683|     1976|
|Peter       |Leko      |HUN     |   2663|     1979|
|Peter Heine |Nielsen   |DEN     |   2618|     1973|
|Peter       |Michalik  |CZE     |   2588|     1990|
|Peter       |Acs       |HUN     |   2582|     1981|
|Peter       |Prohaszka |HUN     |   2574|     1992|

 </td>
   <td> 

|first_name |last_name      |country | rating| birthday|
|:----------|:--------------|:-------|------:|--------:|
|Robert     |Markus         |SRB     |   2609|     1983|
|Robert     |Hovhannisyan   |ARM     |   2597|     1991|
|Robert     |Hess           |USA     |   2591|     1991|
|Robert     |Huebner        |GER     |   2574|     1948|
|Robert     |Fontaine       |SUI     |   2547|     1980|
|Robert     |Kempinski      |POL     |   2539|     1977|
|Robert     |Aghasaryan     |ARM     |   2537|     1994|
|Robert     |Ruck           |HUN     |   2537|     1977|
|Roberto    |Garcia Pantoja |CUB     |   2507|     1992|
|Robert     |Hungaski       |USA     |   2506|     1987|

 </td>
   <td> 

|first_name |last_name    |country | rating| birthday|
|:----------|:------------|:-------|------:|--------:|
|Sam        |Shankland    |USA     |   2710|     1991|
|Samuel     |Sevian       |USA     |   2687|     2000|
|Samvel     |Ter-Sahakyan |ARM     |   2605|     1993|

 </td>
   <td> 

|first_name |last_name    |country | rating| birthday|
|:----------|:------------|:-------|------:|--------:|
|Sergey     |Karjakin     |RUS     |   2747|     1990|
|Sergey A.  |Fedorchuk    |UKR     |   2640|     1981|
|Sergei     |Rublevsky    |RUS     |   2637|     1974|
|Sergei     |Movsesian    |ARM     |   2615|     1978|
|Sergej     |Dyachkov     |RUS     |   2572|     1976|
|Sergei     |Zhigalko     |BLR     |   2572|     1989|
|Sergey     |Grigoriants  |HUN     |   2569|     1983|
|Sergei     |Azarov       |FID     |   2562|     1983|
|Sergey     |Dolmatov     |RUS     |   2560|     1959|
|Sergey     |Erenburg     |USA     |   2559|     1983|
|Sergei     |Ovsejevitsch |UKR     |   2554|     1977|
|Sergey     |Smagin       |RUS     |   2551|     1958|
|Sergei     |Tiviakov     |NED     |   2548|     1973|
|Sergey     |Drygalov     |RUS     |   2547|     1999|
|Sergei     |Shipov       |RUS     |   2541|     1966|
|Sergei     |Lobanov      |RUS     |   2540|     2001|
|Sergei     |Matsenko     |RUS     |   2530|     1990|
|Sergey     |Makarichev   |RUS     |   2520|     1953|
|Sergey     |Trushnikov   |RUS     |   2513|     1975|
|Sergey     |Kayumov      |UZB     |   2505|     1981|
|Sergey     |Ionov        |RUS     |   2502|     1962|

 </td>
   <td> 

|first_name |last_name   |country | rating| birthday|
|:----------|:-----------|:-------|------:|--------:|
|Viktor     |Laznicka    |CZE     |   2610|     1988|
|Viktor     |Erdos       |HUN     |   2588|     1987|
|Victor     |Bologan     |MDA     |   2574|     1971|
|Viktor     |Gazik       |SVK     |   2555|     2001|
|Viktorija  |Cmilyte     |LTU     |   2538|     1983|
|Viktor     |Matviishen  |UKR     |   2533|     2002|
|Victor     |Mikhalevski |ISR     |   2516|     1972|
|Viktor     |Savinov     |UKR     |   2507|     1966|

 </td>
   <td> 

|first_name |last_name  |country | rating| birthday|
|:----------|:----------|:-------|------:|--------:|
|Vladimir   |Kramnik    |RUS     |   2753|     1975|
|Vladimir   |Fedoseev   |FID     |   2674|     1995|
|Vladimir   |Malakhov   |FID     |   2650|     1980|
|Vladimir   |Afromeev   |RUS     |   2633|     1954|
|Volodymyr  |Onyshchuk  |UKR     |   2619|     1991|
|Vladimir   |Akopian    |USA     |   2612|     1971|
|Vladimir   |Belov      |FID     |   2598|     1984|
|Vladimir   |Potkin     |RUS     |   2574|     1982|
|Vladimir   |Chuchelov  |BEL     |   2554|     1969|
|Vladimir   |Baklan     |UKR     |   2544|     1978|
|Vladimir B |Tukmakov   |UKR     |   2540|     1946|
|Vladimir   |Zakhartsov |RUS     |   2537|     1997|
|Vladimir   |Kozhakin   |RUS     |   2533|     1957|
|Vladimir   |Magai      |KGZ     |   2521|     1968|
|Vladimir   |Kosyrev    |RUS     |   2520|     1980|
|Vladimir   |Belous     |RUS     |   2512|     1993|
|Vladimir   |Hamitevici |MDA     |   2505|     1991|
|Volodymyr  |Eryomenko  |UKR     |   2503|     1987|
|Volodymyr  |Vetoshko   |UKR     |   2502|     1998|

 </td>
   <td> 

|first_name |last_name  |country | rating| birthday|
|:----------|:----------|:-------|------:|--------:|
|Vladislav  |Artemiev   |RUS     |   2701|     1998|
|Vladislav  |Tkachiev   |FRA     |   2660|     1973|
|Vladislav  |Kovalev    |FID     |   2623|     1994|
|Vladislav  |Borovikov  |UKR     |   2525|     1973|
|Vladislav  |Nozdrachev |RUS     |   2515|     1992|

 </td>
   <td> 

|first_name |last_name       |country | rating| birthday|
|:----------|:---------------|:-------|------:|--------:|
|Yuriy      |Kryvoruchko     |UKR     |   2649|     1986|
|Yuriy      |Kuzubov         |UKR     |   2618|     1990|
|Yuri       |Drozdovskij     |UKR     |   2616|     1984|
|Yuri       |Kruppa          |UKR     |   2584|     1964|
|Yuri       |Vovk            |UKR     |   2534|     1988|
|Yuri       |Yakovich        |RUS     |   2526|     1962|
|Yuri       |Gonzalez Vidal  |CUB     |   2525|     1981|
|Yuri       |Solodovnichenko |UKR     |   2514|     1978|
|Yuriy      |Ajrapetjan      |UKR     |   2502|     1988|

 </td>
   <td> 

|first_name |last_name |country | rating| birthday|
|:----------|:---------|:-------|------:|--------:|
|Zoltan     |Almasi    |HUN     |   2677|     1976|
|Zoltan     |Gyimesi   |HUN     |   2674|     1977|
|Zoltan     |Medvegy   |HUN     |   2509|     1979|

 </td>
  </tr>
</tbody>
</table>

# About
The list of players can be downloaded from the FIDE website https://ratings.fide.com/download_lists.phtml. This was a quick data manipulation exercise using R and [`dplyr`](https://dplyr.tidyverse.org/). I applied personal judgement when deciding whether names are the same or not.
