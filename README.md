# Best appart in paris

Find your best apartment fastest in time of public transport

Compaire with 2 origin

# Setting values

Set 2 fix destination..

```python
origin = "Strasbourg+Saint-Denis"
displayOrigin = "Strasbourg Saint-Denis"
origin2 = "Montparnasse-Bienven"
displayOrigin2 = "Montparnasse"
key = ""
```

# Run

```
python3 best_appart.py
```

TraceLog
```
Abbesses
22 mins
4.5 km
Abbesses
26 mins
6.6 km
----

Ablon
35 mins
18.7 km
Ablon
38 mins
18.9 km
----

Acheres+Grand+Cormier
36 mins
24.4 km
Acheres+Grand+Cormier
44 mins
24.5 km
----

Acheres-Ville
41 mins
26.7 km
Acheres-Ville
48 mins
26.8 km
----

Aeroport+Charles-de-Gaulle+1
40 mins
30.4 km
Aeroport+Charles-de-Gaulle+1
55 mins
36.2 km
----
```

# Use of generated csv


Import in excel with `;` séparator

```
Station;Duration Strasbourg Saint-Denis;Duration Strasbourg Saint-Denis;Duration Montparnasse;Duration Montparnasse;Distance Strasbourg Saint-Denis;Distance Strasbourg Saint-Denis;Distance Montparnasse;Distance Montparnasse
Abbesses;22 mins;1345;26 mins;1585;4.5 km;1345;6.6 km;1585
Ablon;35 mins;2072;38 mins;2288;18.7 km;2072;18.9 km;2288
Acheres+Grand+Cormier;36 mins;2132;44 mins;2648;24.4 km;2132;24.5 km;2648
Acheres-Ville;41 mins;2458;48 mins;2876;26.7 km;2458;26.8 km;2876
Aeroport+Charles-de-Gaulle+1;40 mins;2404;55 mins;3307;30.4 km;2404;36.2 km;3307
Aeroport+Roissy+Charles+de+Gaulle;40 mins;2404;55 mins;3307;30.4 km;2404;36.2 km;3307
Alesia;22 mins;1331;14 mins;823;6.7 km;1331;2.7 km;823
Alexandre+Dumas;24 mins;1422;40 mins;2379;3.7 km;1422;9.5 km;2379
Alma+Marceau;17 mins;1046;23 mins;1359;4.7 km;1046;5.8 km;1359
Anatole+France;26 mins;1579;31 mins;1839;6.7 km;1579;9.1 km;1839
Antony;54 mins;3227;45 mins;2719;20.2 km;3227;16.3 km;2719
Anvers;15 mins;907;28 mins;1667;2.6 km;907;7.3 km;1667
Arcueil+-+Cachan;26 mins;1532;21 mins;1267;9.0 km;1532;6.0 km;1267
Argentine;26 mins;1577;26 mins;1554;5.6 km;1577;6.2 km;1554
Arpajon;18 mins;1050;17 mins;1026;3.5 km;1050;2.1 km;1026
Arts+et+Metiers;27 mins;1629;21 mins;1254;5.3 km;1629;4.3 km;1254
Asnieres+Gennevilliers+Les+Courtilles;37 mins;2204;30 mins;1803;11.5 km;2204;12.4 km;1803
Assemblee+Nationale;18 mins;1099;14 mins;815;4.0 km;1099;3.1 km;815
Athis-Mons;58 mins;3453;1 hour 1 min;3669;21.9 km;3453;22.2 km;3669
Auber;12 mins;730;27 mins;1603;2.1 km;730;5.2 km;1603
Aubervilliers-Pantin+Quatre+Chemins;19 mins;1120;38 mins;2264;5.0 km;1120;9.8 km;2264
Aulnay-sous-Bois;29 mins;1716;43 mins;2587;16.2 km;1716;22.0 km;2587
Avenue+du+president+Kennedy;36 mins;2145;20 mins;1211;8.2 km;2145;4.1 km;1211
Avenue+Emile+Zola;29 mins;1735;22 mins;1303;6.8 km;1735;3.5 km;1303
Avenue+Foch;26 mins;1544;28 mins;1659;6.5 km;1544;5.7 km;1659
Avenue+Henri+Martin;28 mins;1679;29 mins;1757;6.8 km;1679;5.4 km;1757
Avron;20 mins;1182;33 mins;2000;4.7 km;1182;8.8 km;2000
Bagneux;37 mins;2216;28 mins;1708;9.7 km;2216;5.7 km;1708
Balard;27 mins;1597;20 mins;1228;7.8 km;1597;5.1 km;1228
Barbes+Rochechouart;9 mins;532;27 mins;1616;2.1 km;532;7.0 km;1616
Basilique+de+Saint-Denis;40 mins;2371;33 mins;1970;12.0 km;2371;12.9 km;1970
Bastille;13 mins;806;29 mins;1742;2.5 km;806;7.9 km;1742
Bel-Air;15 mins;914;15 mins;890;3.3 km;914;1.9 km;890
Belleville;21 mins;1277;36 mins;2184;3.9 km;1277;7.8 km;2184
Berault;27 mins;1599;38 mins;2289;6.7 km;1599;12.9 km;2289
Bercy;29 mins;1717;30 mins;1815;6.0 km;1717;6.9 km;1815
Bibliotheque+Francois+Mitterand;27 mins;1620;24 mins;1444;6.5 km;1620;5.5 km;1444
Bibliotheque+Francois+Mitterand;27 mins;1620;24 mins;1444;6.5 km;1620;5.5 km;1444
Bievres;1 hour 9 mins;4162;39 mins;2318;29.5 km;4162;22.8 km;2318
Billancourt;34 mins;2065;32 mins;1935;10.8 km;2065;8.5 km;1935
Bir-Hakeim;28 mins;1658;13 mins;776;6.4 km;1658;3.2 km;776
Blanche;21 mins;1242;23 mins;1360;3.4 km;1242;6.4 km;1360
Bobigny+Pablo+Picasso;32 mins;1934;51 mins;3078;9.5 km;1934;14.4 km;3078
Bobigny-Pantin+Raymond+Queneau;26 mins;1570;45 mins;2714;7.0 km;1570;11.9 km;2714
Boissiere;26 mins;1570;17 mins;1016;5.6 km;1570;4.9 km;1016
Boissy-Saint-Leger;43 mins;2552;54 mins;3248;25.4 km;2552;28.0 km;3248
Bolivar;23 mins;1387;38 mins;2300;3.2 km;1387;9.7 km;2300
Bonne+Nouvelle;5 mins;300;25 mins;1498;0.3 km;300;5.2 km;1498
Botzaris;24 mins;1429;39 mins;2336;4.4 km;1429;8.3 km;2336
Boucicaut;21 mins;1260;22 mins;1328;6.6 km;1260;3.6 km;1328
Boulainvilliers;27 mins;1642;28 mins;1704;7.5 km;1642;4.8 km;1704
Boulogne+Jean+Jaures;39 mins;2352;28 mins;1689;10.3 km;2352;7.5 km;1689
Boulogne+Pont+de+Saint-Cloud;41 mins;2472;30 mins;1809;11.0 km;2472;8.2 km;1809
Bouray;59 mins;3512;1 hour 2 mins;3728;44.2 km;3512;44.4 km;3728
Bourg-la-Reine;30 mins;1772;21 mins;1267;11.6 km;1772;8.7 km;1267
Bourse;13 mins;768;27 mins;1633;1.4 km;768;6.7 km;1633
Breguet+Sabin;14 mins;852;31 mins;1873;2.2 km;852;6.8 km;1873
Bretigny;50 mins;2972;53 mins;3188;35.8 km;2972;36.1 km;3188
Breuillet+Bruyeres-le-Chatel;1 hour 7 mins;4030;1 hour 10 mins;4208;45.1 km;4030;45.4 km;4208
Breuillet-Village;1 hour 10 mins;4210;1 hour 13 mins;4388;47.2 km;4210;47.5 km;4388
Brie-sur-Marne;29 mins;1713;40 mins;2409;17.1 km;1713;19.8 km;2409
Brochant;25 mins;1490;19 mins;1137;4.7 km;1490;7.0 km;1137
Bry-sur-Marne;29 mins;1713;40 mins;2409;17.1 km;1713;19.8 km;2409
Bures-sur-Yvette;49 mins;2912;44 mins;2647;28.1 km;2912;25.1 km;2647
Bussy-Saint-Georges;54 mins;3228;1 hour 5 mins;3924;32.0 km;3228;34.6 km;3924
Buttes+Chaumont;23 mins;1374;40 mins;2411;3.7 km;1374;7.6 km;2411
Buzenval;17 mins;1016;36 mins;2162;4.4 km;1016;9.0 km;2162
Cadet;11 mins;652;30 mins;1785;2.1 km;652;6.0 km;1785
Cambronne;24 mins;1466;10 mins;596;5.8 km;1466;2.0 km;596
Campo+Formio;24 mins;1457;22 mins;1334;5.1 km;1457;4.4 km;1334
Cardinal+Lemoine;24 mins;1412;21 mins;1269;3.7 km;1412;3.9 km;1269
Carrefour+Pleyel;33 mins;1958;26 mins;1557;9.4 km;1958;10.3 km;1557
Censier+Daubenton;21 mins;1244;21 mins;1278;4.8 km;1244;4.6 km;1278
Cergy-Le+Haut;56 mins;3370;1 hour 3 mins;3788;40.5 km;3370;40.6 km;3788
Cergy-Prefecture;56 mins;3370;1 hour 3 mins;3788;40.5 km;3370;40.6 km;3788
Cergy-Saint-Christophe;53 mins;3190;1 hour 0 mins;3608;38.8 km;3190;38.9 km;3608
Cernay;33 mins;1956;50 mins;2997;17.0 km;1956;20.7 km;2997
Chamarande;1 hour 7 mins;3992;1 hour 10 mins;4208;50.4 km;3992;50.6 km;4208
Champigny;46 mins;2732;53 mins;3174;16.3 km;2732;19.0 km;3174
Champs+de+Mars+Tour+Eiffel;30 mins;1813;16 mins;931;6.5 km;1813;3.4 km;931
Champs+Elysees+Clemenceau;22 mins;1309;11 mins;635;4.3 km;1309;3.4 km;635
Chardon+Lagache;34 mins;2032;27 mins;1638;9.3 km;2032;5.3 km;1638
Charenton+-+Ecoles;24 mins;1441;37 mins;2228;8.2 km;1441;9.9 km;2228
Charles+de+Gaulle+Etoile;18 mins;1082;21 mins;1239;5.9 km;1082;6.0 km;1239
Charles+Michels;29 mins;1722;19 mins;1149;6.8 km;1722;3.6 km;1149
Charonne;19 mins;1167;39 mins;2368;4.6 km;1167;9.1 km;2368
Chateau+d'eau;4 mins;232;23 mins;1376;0.3 km;232;5.2 km;1376
Chateau+de+Vincennes;35 mins;2073;47 mins;2792;7.7 km;2073;12.1 km;2792
Chateau+Landon;11 mins;678;30 mins;1822;1.3 km;678;6.2 km;1822
Chateau+rouge;15 mins;876;33 mins;1960;2.5 km;876;7.4 km;1960
Chatelet;10 mins;592;18 mins;1108;1.9 km;592;3.6 km;1108
Chatelet+-+Les+Halles;9 mins;524;20 mins;1220;1.3 km;524;3.9 km;1220
Chatillon-Montrouge;33 mins;1983;14 mins;828;10.5 km;1983;4.9 km;828
Chatou-Croissy;32 mins;1892;39 mins;2348;17.3 km;1892;17.4 km;2348
Chaussee+d'Antin+La+Fayette;9 mins;566;23 mins;1389;1.7 km;566;5.4 km;1389
Chaville+-+Velizy;41 mins;2444;29 mins;1727;17.1 km;2444;12.9 km;1727
Chemin+d'Antony;50 mins;3010;49 mins;2923;25.7 km;3010;13.0 km;2923
Chemin+Vert;10 mins;601;30 mins;1810;1.9 km;601;8.0 km;1810
Chevaleret;30 mins;1779;17 mins;1015;7.3 km;1779;4.4 km;1015
Chilly-Mazarin;49 mins;2912;40 mins;2404;20.9 km;2912;16.9 km;2404
Choisy-le-Roi;28 mins;1652;37 mins;2228;14.0 km;1652;14.2 km;2228
Cite;11 mins;667;17 mins;1003;2.1 km;667;3.0 km;1003
Cite+Universitaire;22 mins;1295;17 mins;1030;6.3 km;1295;3.4 km;1030
Cluny+La+Sorbonne;15 mins;901;19 mins;1117;2.7 km;901;2.9 km;1117
Colonel+Fabien;23 mins;1362;35 mins;2087;4.2 km;1362;9.8 km;2087
Commerce;19 mins;1140;20 mins;1207;6.0 km;1140;3.0 km;1207
Concorde;14 mins;848;20 mins;1182;3.2 km;848;3.9 km;1182
Conflans-Fin+d'Oise;42 mins;2530;49 mins;2948;28.9 km;2530;29.0 km;2948
Convention;30 mins;1770;14 mins;843;6.8 km;1770;2.7 km;843
Corentin+Cariou;16 mins;972;35 mins;2084;3.7 km;972;8.6 km;2084
Corentin+Celton;33 mins;1973;17 mins;1046;8.5 km;1973;4.4 km;1046
Corvisart;30 mins;1778;13 mins;775;7.2 km;1778;3.0 km;775
Cour+Saint-Emilion;22 mins;1304;30 mins;1813;6.0 km;1304;6.8 km;1813
Courcelle-sur-Yvette;1 hour 1 min;3640;56 mins;3375;33.4 km;3640;30.4 km;3375
Courcelles;28 mins;1664;31 mins;1846;5.7 km;1664;6.8 km;1846
Couronnes;21 mins;1256;38 mins;2267;3.0 km;1256;11.0 km;2267
Creteil+-+L'Echat;32 mins;1921;45 mins;2708;12.2 km;1921;13.9 km;2708
Creteil+-+Universite;41 mins;2440;54 mins;3227;13.6 km;2440;15.3 km;3227
Creteil+Pointe+du+Lac;38 mins;2281;51 mins;3068;15.7 km;2281;17.4 km;3068
Creteil+Prefecture;35 mins;2101;48 mins;2888;14.4 km;2101;16.1 km;2888
Crimee;15 mins;912;33 mins;1964;3.2 km;912;8.1 km;1964
Croix+de+Chavaux;23 mins;1376;43 mins;2577;7.1 km;1376;11.5 km;2577
Danube;28 mins;1654;45 mins;2691;4.7 km;1654;8.6 km;2691
Daumesnil;18 mins;1071;23 mins;1365;5.1 km;1071;6.8 km;1365
Denfert-Rochereau;19 mins;1160;10 mins;595;5.9 km;1160;1.6 km;595
Dourdan;1 hour 45 mins;6287;1 hour 48 mins;6465;61.4 km;6287;61.7 km;6465
Dourdan-la-Foret;1 hour 41 mins;6066;1 hour 44 mins;6244;61.1 km;6066;61.4 km;6244
Drancy;24 mins;1416;38 mins;2287;13.2 km;1416;19.0 km;2287
Dugommier;23 mins;1369;21 mins;1255;5.5 km;1369;6.2 km;1255
Dupleix;24 mins;1465;12 mins;716;5.9 km;1465;2.7 km;716
Duroc;21 mins;1274;5 mins;299;5.2 km;1274;0.9 km;299
Ecole+Militaire;22 mins;1318;16 mins;980;5.9 km;1318;2.7 km;980
Ecole+veterinaire+de+Maisons-Alfort;32 mins;1921;45 mins;2708;9.6 km;1921;11.3 km;2708
Edgar+Quinet;21 mins;1289;5 mins;273;4.8 km;1289;0.3 km;273
Eglise+d'Auteuil;33 mins;2003;22 mins;1329;9.0 km;2003;5.0 km;1329
Eglise+de+Pantin;27 mins;1602;44 mins;2654;5.9 km;1602;10.8 km;2654
Egly;27 mins;1602;44 mins;2654;5.9 km;1602;10.8 km;2654
Epinay-sur-Orge;40 mins;2372;43 mins;2588;28.0 km;2372;28.3 km;2588
Epinay-sur-Seine;38 mins;2258;45 mins;2699;12.7 km;2258;15.5 km;2699
Ermont+Eaubonne;34 mins;2023;41 mins;2457;16.1 km;2023;19.2 km;2457
Esplanade+de+La+Defense;33 mins;1997;28 mins;1694;8.8 km;1997;8.6 km;1694
Etampes;1 hour 16 mins;4532;1 hour 19 mins;4748;60.3 km;4532;60.6 km;4748
Etienne+Marcel;5 mins;320;19 mins;1136;0.8 km;320;4.1 km;1136
Etrechy;1 hour 10 mins;4172;1 hour 13 mins;4388;53.2 km;4172;53.4 km;4388
Europe;6 mins;384;13 mins;777;0.8 km;384;5.0 km;777
Exelmans;29 mins;1766;33 mins;1958;9.2 km;1766;7.9 km;1958
Faidherbe+Chaligny;14 mins;842;34 mins;2051;3.6 km;842;9.7 km;2051
Falguiere;25 mins;1493;9 mins;566;5.0 km;1493;0.9 km;566
Felix+Faure;20 mins;1200;22 mins;1328;6.3 km;1200;3.2 km;1328
Filles+du+Calvaire;7 mins;421;27 mins;1630;1.3 km;421;7.3 km;1630
Fontaine-Michalon;37 mins;2240;32 mins;1927;15.9 km;2240;13.0 km;1927
Fontenay+aux-Roses;42 mins;2524;38 mins;2259;14.2 km;2524;11.2 km;2259
Fontenay-sous-Bois;23 mins;1352;35 mins;2108;13.6 km;1352;16.2 km;2108
Fort+d'Aubervilliers;22 mins;1332;40 mins;2384;6.5 km;1332;11.3 km;2384
Franconville+Le+Plessis-Bouchard;36 mins;2136;52 mins;3117;18.9 km;2136;22.6 km;3117
Franklin+D.+Roosevelt;18 mins;1079;14 mins;820;4.0 km;1079;3.6 km;820
Front+populaire;27 mins;1616;37 mins;2245;5.8 km;1616;11.1 km;2245
Gabriel+Peri+Asnieres-Gennevilliers;32 mins;1932;26 mins;1531;9.6 km;1932;10.5 km;1531
Gaite;23 mins;1392;4 mins;237;6.2 km;1392;0.6 km;237
Gallieni;21 mins;1278;40 mins;2378;5.3 km;1278;12.4 km;2378
Gambetta;20 mins;1189;38 mins;2289;4.1 km;1189;11.2 km;2289
Gare+d'Austerlitz;25 mins;1525;28 mins;1693;4.5 km;1525;5.6 km;1693
Gare+d'Austerlitz;25 mins;1525;28 mins;1693;4.5 km;1525;5.6 km;1693
Gare+de+l'Est;8 mins;470;25 mins;1522;1.1 km;470;5.9 km;1522
Gare+de+Lyon;22 mins;1302;26 mins;1543;3.6 km;1302;4.6 km;1543
Gare+du+Nord;9 mins;523;26 mins;1575;1.6 km;523;6.5 km;1575
Garibaldi;9 mins;523;26 mins;1575;1.6 km;523;6.5 km;1575
Gennevilliers;39 mins;2335;37 mins;2217;11.9 km;2335;12.7 km;2217
Gentilly;23 mins;1352;18 mins;1087;6.7 km;1352;3.8 km;1087
Georges+V;25 mins;1497;24 mins;1411;5.2 km;1497;4.3 km;1411
Gif-sur-Yvette;53 mins;3152;48 mins;2887;30.2 km;3152;27.3 km;2887
Glaciere;30 mins;1808;13 mins;805;6.7 km;1808;2.5 km;805
Goncourt;13 mins;799;31 mins;1836;2.1 km;799;6.0 km;1836
Grands+Boulevards;7 mins;420;22 mins;1330;0.9 km;420;5.2 km;1330
Gravigny-Ballizy;50 mins;3010;53 mins;3188;29.8 km;3010;30.1 km;3188
Guy+Moquet;26 mins;1538;19 mins;1137;6.1 km;1538;7.0 km;1137
Havre+Caumartin;11 mins;662;24 mins;1466;2.1 km;662;5.0 km;1466
Hoche;25 mins;1482;42 mins;2534;5.2 km;1482;10.1 km;2534
Hotel+de+Ville;15 mins;884;23 mins;1400;2.1 km;884;3.7 km;1400
Houilles+Carrieres-sur-Seine;27 mins;1592;35 mins;2108;15.8 km;1592;15.9 km;2108
Iena;19 mins;1166;22 mins;1329;5.2 km;1166;5.3 km;1329
Igny;53 mins;3164;41 mins;2460;23.2 km;3164;28.2 km;2460
Invalides;55 mins;3324;27 mins;1615;4.3 km;3324;2.1 km;1615
Invalides;55 mins;3324;27 mins;1615;4.3 km;3324;2.1 km;1615
Issy;44 mins;2636;33 mins;1993;10.3 km;2636;6.0 km;1993
Issy+Val+de+Seine;30 mins;1784;27 mins;1617;9.4 km;1784;8.4 km;1617
Ivry-sur-Seine;39 mins;2360;38 mins;2297;8.6 km;2360;9.2 km;2297
Jacques+Bonsergent;9 mins;529;30 mins;1787;0.7 km;529;5.7 km;1787
Jasmin;26 mins;1586;30 mins;1778;8.0 km;1586;6.6 km;1778
Jaures;20 mins;1182;34 mins;2027;2.9 km;1182;9.4 km;2027
Javel;29 mins;1720;31 mins;1848;8.1 km;1720;5.0 km;1848
Javel+Andre+Citroen;31 mins;1872;20 mins;1209;7.1 km;1872;4.3 km;1209
Joinville-le-Pont;30 mins;1818;42 mins;2514;14.7 km;1818;17.3 km;2514
Jourdain;17 mins;1039;35 mins;2076;3.6 km;1039;7.5 km;2076
Jouy-en-Josas;1 hour 18 mins;4683;47 mins;2839;30.1 km;4683;23.4 km;2839
Jules+Joffrin;19 mins;1112;29 mins;1765;3.3 km;1112;7.8 km;1765
Jussieu;18 mins;1089;24 mins;1462;4.1 km;1089;4.2 km;1462
Juvisy;33 mins;1952;36 mins;2168;23.5 km;1952;23.8 km;2168
Kleber;29 mins;1723;21 mins;1283;5.8 km;1723;5.2 km;1283
La+Chapelle;30 mins;1824;41 mins;2453;4.4 km;1824;9.7 km;2453
La+Courneuve+-+Aubervilliers;19 mins;1116;31 mins;1868;8.0 km;1116;12.5 km;1868
La+Courneuve+8+Mai+1945;25 mins;1487;42 mins;2539;7.3 km;1487;12.1 km;2539
La+Croix+de+Berny;29 mins;1712;24 mins;1447;13.7 km;1712;10.8 km;1447
La+Defense+Grande+Arche;22 mins;1329;32 mins;1943;10.7 km;1329;10.0 km;1943
La+Fourche;24 mins;1418;17 mins;1017;5.5 km;1418;6.4 km;1017
La+Hacquiniere;51 mins;3032;46 mins;2767;29.0 km;3032;26.0 km;2767
La+Motte+Picquet+Grenelle;20 mins;1188;11 mins;656;5.5 km;1188;2.3 km;656
La+Muette;23 mins;1406;27 mins;1598;7.2 km;1406;5.8 km;1598
La+Muette;23 mins;1406;27 mins;1598;7.2 km;1406;5.8 km;1598
La+Norville+Saint-Germain-les-Arpajon;58 mins;3490;1 hour 1 min;3668;39.3 km;3490;39.5 km;3668
La+Plaine+-+Stade+de+France;16 mins;936;28 mins;1688;6.2 km;936;10.7 km;1688
La+Tour+Maubourg;15 mins;900;15 mins;902;4.1 km;900;2.6 km;902
La+Varenne+Chennevieres;35 mins;2072;46 mins;2768;20.4 km;2072;23.1 km;2768
Lamarck+Caulaincourt;21 mins;1257;27 mins;1645;3.9 km;1257;7.2 km;1645
Laplace;25 mins;1472;24 mins;1465;4.1 km;1472;5.9 km;1465
Lardy;1 hour 3 mins;3752;1 hour 6 mins;3968;47.2 km;3752;47.5 km;3968
Laumiere;21 mins;1242;38 mins;2294;3.4 km;1242;8.3 km;2294
Le+Blanc-Mesnil;46 mins;2760;1 hour 0 mins;3574;13.4 km;2760;21.8 km;3574
Le+Bourget;41 mins;2488;54 mins;3215;11.5 km;2488;19.1 km;3215
Le+Guichet;23 mins;1355;1 min;45;4.9 km;1355;53 m;45
Le+Kremlin+Bicetre;28 mins;1689;22 mins;1303;8.3 km;1689;5.7 km;1303
Le+Parc+de+Saint-Maur;30 mins;1772;41 mins;2468;17.1 km;1772;19.7 km;2468
Le+Peletier;14 mins;842;27 mins;1611;1.6 km;842;5.8 km;1611
Le+Vesinet-Centre;34 mins;2012;41 mins;2487;19.0 km;2012;19.1 km;2487
Le+Vesinet-Le-Pecq;55 mins;3283;1 hour 3 mins;3758;24.1 km;3283;24.1 km;3758
Ledru+-+Rollin;12 mins;721;32 mins;1930;2.9 km;721;9.0 km;1930
Les+Agnettes;34 mins;2018;27 mins;1617;10.6 km;2018;11.4 km;1617
Les+Ardoines;31 mins;1832;34 mins;2048;11.9 km;1832;12.1 km;2048
Les+Baconnets;39 mins;2360;34 mins;2047;16.7 km;2360;13.7 km;2047
Les+Gobelins;26 mins;1538;16 mins;959;5.6 km;1538;2.7 km;959
Les+Gresillons;37 mins;2215;35 mins;2097;10.4 km;2215;11.2 km;2097
Les+Halles;11 mins;658;23 mins;1354;1.5 km;658;4.1 km;1354
Les+Sablons;30 mins;1817;25 mins;1514;7.0 km;1817;6.8 km;1514
Les+Saules;18 mins;1105;36 mins;2157;1.7 km;1105;6.6 km;2157
Liberte;14 mins;816;31 mins;1868;1.4 km;816;6.3 km;1868
Liege;22 mins;1347;15 mins;897;3.6 km;1347;5.5 km;897
Lognes;38 mins;2252;50 mins;3008;25.3 km;2252;27.9 km;3008
Longjumeau;56 mins;3370;49 mins;2928;32.8 km;3370;36.1 km;2928
Louis+Blanc;13 mins;794;31 mins;1846;1.8 km;794;6.7 km;1846
Louise+Michel;15 mins;871;34 mins;2067;1.4 km;871;6.1 km;2067
Lourmel;22 mins;1320;24 mins;1448;7.1 km;1320;4.1 km;1448
Louvre+Rivoli;15 mins;920;22 mins;1308;1.8 km;920;5.6 km;1308
Lozere+Ecole+Polytechnique;1 hour 8 mins;4072;1 hour 3 mins;3807;25.9 km;4072;23.0 km;3807
Luxembourg;38 mins;2301;20 mins;1182;3.0 km;2301;1.5 km;1182
Mabillon;16 mins;942;15 mins;918;3.4 km;942;2.0 km;918
Madeleine;12 mins;696;21 mins;1236;2.6 km;696;4.4 km;1236
Mairie+d'Issy;35 mins;2093;19 mins;1166;9.0 km;2093;4.9 km;1166
Mairie+d'Ivry;33 mins;1989;28 mins;1663;9.6 km;1989;7.1 km;1663
Mairie+de+Clichy;28 mins;1670;22 mins;1317;6.5 km;1670;8.8 km;1317
Mairie+de+Montreuil;26 mins;1574;46 mins;2775;7.8 km;1574;12.3 km;2775
Mairie+de+Montrouge;24 mins;1460;16 mins;952;7.9 km;1460;4.0 km;952
Mairie+de+Saint-Ouen;31 mins;1838;24 mins;1437;8.3 km;1838;9.2 km;1437
Mairie+des+Lilas;22 mins;1339;40 mins;2376;5.8 km;1339;9.7 km;2376
Maison+Blanche;20 mins;1224;26 mins;1537;4.9 km;1224;6.0 km;1537
Maisons-Alfort+-+Stade;28 mins;1681;41 mins;2468;10.3 km;1681;12.0 km;2468
Maisons-Alfort+Les+Juilliottes;30 mins;1801;43 mins;2588;11.2 km;1801;12.9 km;2588
Maisons-Laffitte;43 mins;2589;52 mins;3105;21.0 km;2589;21.1 km;3105
Malakoff+Plateau+de+Vanves;29 mins;1752;10 mins;597;8.9 km;1752;3.2 km;597
Malakoff+Rue+Etienne+Dolet;34 mins;2041;15 mins;886;10.1 km;2041;4.4 km;886
Malesherbes;20 mins;1219;25 mins;1479;4.4 km;1219;6.8 km;1479
Maraichers;18 mins;1076;38 mins;2277;4.8 km;1076;9.3 km;2277
Marcadet+Poissonniers;11 mins;684;29 mins;1736;2.8 km;684;7.7 km;1736
Marcel+Sembat;33 mins;2006;37 mins;2198;10.8 km;2006;9.5 km;2198
Marne-La-Vallee+Chessy+(Parc+Disneyland);57 mins;3442;1 hour 9 mins;4138;38.8 km;3442;41.4 km;4138
Marolles-en-Hurepoix;55 mins;3272;58 mins;3488;40.6 km;3272;40.8 km;3488
Marx+Dormoy;22 mins;1316;32 mins;1945;3.7 km;1316;9.0 km;1945
Massy+-+Palaiseau;36 mins;2132;31 mins;1867;19.4 km;2132;16.4 km;1867
Massy+-+Verrieres;41 mins;2480;36 mins;2167;17.9 km;2480;14.9 km;2167
Maubert+-+Mutualite;18 mins;1109;20 mins;1209;3.0 km;1109;3.4 km;1209
Menilmontant;23 mins;1368;39 mins;2327;3.6 km;1368;11.4 km;2327
Meudon-val-Fleury;36 mins;2144;24 mins;1418;12.5 km;2144;8.2 km;1418
Michel+Ange+Auteuil;27 mins;1646;24 mins;1441;8.6 km;1646;5.4 km;1441
Michel+Ange+Molitor;29 mins;1738;32 mins;1930;8.9 km;1738;7.6 km;1930
Michel+Bizot;18 mins;1081;29 mins;1733;5.5 km;1081;7.3 km;1733
Mirabeau;31 mins;1859;26 mins;1560;7.4 km;1859;4.7 km;1560
Miromesnil;14 mins;858;11 mins;689;3.1 km;858;4.1 km;689
Monceau;23 mins;1368;26 mins;1543;6.3 km;1368;6.3 km;1543
Montgallet;19 mins;1150;30 mins;1806;4.5 km;1150;6.9 km;1806
Montigny+Beauchamp;40 mins;2376;57 mins;3428;22.0 km;2376;26.9 km;3428
Montparnasse-Bienvenue;22 mins;1310;1 min;0;4.9 km;1310;1 m;0
Mouton+Duvernet;20 mins;1220;12 mins;712;6.2 km;1220;2.2 km;712
Musee+d'Orsay;20 mins;1222;19 mins;1127;4.7 km;1222;2.9 km;1127
Nanterre-Prefecture;23 mins;1352;30 mins;1808;11.6 km;1352;11.6 km;1808
Nanterre-Universite;41 mins;2449;40 mins;2396;13.2 km;2449;15.7 km;2396
Nanterre-Ville;25 mins;1472;36 mins;2157;12.8 km;1472;15.4 km;2157
Nation;18 mins;1055;30 mins;1774;4.0 km;1055;8.6 km;1774
Nationale;31 mins;1839;16 mins;955;7.8 km;1839;4.0 km;955
Neuilly-Plaisance;26 mins;1532;37 mins;2228;15.7 km;1532;18.4 km;2228
Neuilly-Porte+Maillot;33 mins;1967;28 mins;1664;6.6 km;1967;6.4 km;1664
Neuville-Universite;45 mins;2710;52 mins;3128;31.8 km;2710;31.9 km;3128
Nogent-sur-Marne;24 mins;1412;35 mins;2108;12.6 km;1412;15.3 km;2108
Noisiel;44 mins;2633;55 mins;3329;24.6 km;2633;27.2 km;3329
Noisy-Champs;34 mins;2040;46 mins;2736;21.4 km;2040;24.0 km;2736
Noisy-le-Grand+Mont+d'Est;42 mins;2492;53 mins;3188;23.6 km;2492;26.3 km;3188
Notre-Dame+de-Lorette;19 mins;1153;29 mins;1723;2.0 km;1153;5.9 km;1723
Notre-Dame+des-Champs;19 mins;1155;8 mins;455;4.7 km;1155;0.6 km;455
Oberkampf;9 mins;536;32 mins;1929;1.3 km;536;8.2 km;1929
Odeon;16 mins;956;12 mins;697;3.0 km;956;2.1 km;697
Olympiades;24 mins;1418;27 mins;1636;7.6 km;1418;4.8 km;1636
Opera;12 mins;693;23 mins;1363;1.9 km;693;4.6 km;1363
Orly-Ville;58 mins;3454;1 hour 1 min;3632;19.1 km;3454;19.4 km;3632
Orsay+-+Ville;47 mins;2802;42 mins;2537;26.8 km;2802;23.9 km;2537
Ourcq;22 mins;1302;39 mins;2354;4.0 km;1302;8.9 km;2354
Palais+Royal+Musee+du+Louvre;16 mins;964;22 mins;1302;2.7 km;964;5.3 km;1302
Palaiseau;38 mins;2252;33 mins;1987;20.7 km;2252;17.8 km;1987
Palaiseau+-+Villebon;40 mins;2372;35 mins;2107;22.0 km;2372;19.0 km;2107
Parc+de+Sceaux;46 mins;2766;42 mins;2548;13.7 km;2766;10.9 km;2548
Parc+des+Expositions;32 mins;1948;17 mins;1021;7.7 km;1948;3.6 km;1021
Parmentier;15 mins;896;33 mins;1995;2.2 km;896;6.2 km;1995
Passy;29 mins;1718;14 mins;836;6.8 km;1718;3.7 km;836
Pasteur;31 mins;1854;12 mins;748;5.7 km;1854;1.4 km;748
Pelleport;26 mins;1537;44 mins;2636;4.4 km;1537;8.5 km;2636
Pere+Lachaise;22 mins;1312;40 mins;2411;4.1 km;1312;8.2 km;2411
Pereire;22 mins;1339;27 mins;1599;5.2 km;1339;7.7 km;1599
Pereire-Levallois;24 mins;1439;28 mins;1699;5.3 km;1439;7.7 km;1699
Pernety;25 mins;1512;6 mins;357;7.0 km;1512;1.3 km;357
Petit+Jouy-les-Loges;1 hour 1 min;3632;23 mins;1368;30.1 km;3632;20.4 km;1368
Petit-Vaux;48 mins;2890;51 mins;3068;28.3 km;2890;28.5 km;3068
Philippe+Auguste;25 mins;1474;42 mins;2507;3.9 km;1474;12.4 km;2507
Picpus;19 mins;1116;24 mins;1410;5.1 km;1116;6.8 km;1410
Pierre+Curie;20 mins;1187;25 mins;1487;4.4 km;1187;4.6 km;1487
Pierrelaye;44 mins;2616;1 hour 1 min;3668;25.4 km;2616;30.3 km;3668
Pigalle;22 mins;1325;26 mins;1584;3.1 km;1325;6.4 km;1584
Place+d'Italie;25 mins;1513;17 mins;1021;6.2 km;1513;3.6 km;1021
Place+de+Clichy;24 mins;1467;17 mins;1039;4.0 km;1467;6.0 km;1039
Place+des+Fetes;19 mins;1153;37 mins;2190;4.0 km;1153;7.9 km;2190
Place+Monge;19 mins;1149;22 mins;1303;4.5 km;1149;4.9 km;1303
Plaisance;33 mins;1992;14 mins;835;7.5 km;1992;2.2 km;835
Poissonniere;15 mins;901;29 mins;1724;2.0 km;901;6.6 km;1724
Poissy;43 mins;2599;40 mins;2399;28.9 km;2599;30.8 km;2399
Pont+de+l'Alma;19 mins;1167;25 mins;1480;4.8 km;1167;5.9 km;1480
Pont+de+Levallois+Becon;28 mins;1699;33 mins;1959;7.3 km;1699;9.7 km;1959
Pont+de+Neuilly;31 mins;1877;26 mins;1574;8.0 km;1877;7.9 km;1574
Pont+de+Rungis+Aeroport+d'Orly;43 mins;2590;46 mins;2768;20.8 km;2590;21.0 km;2768
Pont+de+Sevres;36 mins;2186;40 mins;2378;11.8 km;2186;10.5 km;2378
Pont+du+Garigliano;35 mins;2075;25 mins;1497;8.5 km;2075;7.3 km;1497
Pont+Marie;17 mins;1034;26 mins;1550;2.8 km;1034;4.4 km;1550
Pont+Neuf;15 mins;873;16 mins;982;2.3 km;873;3.1 km;982
Pontoise;27 mins;1627;25 mins;1484;3.6 km;1627;3.8 km;1484
Porchefontaine;46 mins;2744;29 mins;1728;19.4 km;2744;15.0 km;1728
Port-Royal;17 mins;992;11 mins;653;3.9 km;992;1.5 km;653
Porte+d'Auteuil;33 mins;1984;25 mins;1509;8.9 km;1984;5.7 km;1509
Porte+d'Italie;29 mins;1719;23 mins;1393;7.4 km;1719;4.9 km;1393
Porte+d'Ivry;29 mins;1749;25 mins;1483;8.0 km;1749;5.5 km;1483
Porte+d'Orleans;24 mins;1447;16 mins;939;7.3 km;1447;3.3 km;939
Porte+Dauphine;35 mins;2084;32 mins;1936;8.1 km;2084;7.3 km;1936
Porte+de+Bagnolet;23 mins;1366;41 mins;2465;4.8 km;1366;8.8 km;2465
Porte+de+Champerret;24 mins;1459;29 mins;1719;5.6 km;1459;8.1 km;1719
Porte+de+Charenton;21 mins;1261;34 mins;2048;6.4 km;1261;8.1 km;2048
Porte+de+Choisy;29 mins;1728;23 mins;1402;7.7 km;1728;5.2 km;1402
Porte+de+Clichy;28 mins;1695;22 mins;1294;6.8 km;1695;7.6 km;1294
Porte+de+Clichy;28 mins;1695;22 mins;1294;6.8 km;1695;7.6 km;1294
Porte+de+Clignancourt;14 mins;864;32 mins;1916;3.6 km;864;8.5 km;1916
Porte+de+la+Chapelle;25 mins;1491;35 mins;2120;4.6 km;1491;9.9 km;2120
Porte+de+la+Villette;20 mins;1228;38 mins;2280;4.2 km;1228;9.1 km;2280
Porte+de+Montreuil;19 mins;1136;39 mins;2337;5.2 km;1136;9.6 km;2337
Porte+de+Pantin;23 mins;1362;40 mins;2414;4.4 km;1362;9.2 km;2414
Porte+de+Saint-Cloud;33 mins;1989;36 mins;2181;10.1 km;1989;8.8 km;2181
Porte+de+Saint-Ouen;27 mins;1598;20 mins;1197;6.6 km;1598;7.5 km;1197
Porte+de+Vanves;28 mins;1683;9 mins;528;8.3 km;1683;2.7 km;528
Porte+de+Versailles;32 mins;1937;17 mins;1010;7.7 km;1937;3.6 km;1010
Porte+de+Vincennes;23 mins;1388;35 mins;2107;5.0 km;1388;9.4 km;2107
Porte+des+Lilas;21 mins;1279;38 mins;2256;5.0 km;1279;8.9 km;2256
Porte+Doree;22 mins;1329;35 mins;2116;6.1 km;1329;7.8 km;2116
Porte+Maillot;31 mins;1860;26 mins;1557;6.4 km;1860;6.2 km;1557
Pre+St-Gervais;27 mins;1594;44 mins;2631;5.0 km;1594;8.9 km;2631
Pyramides;13 mins;768;23 mins;1389;2.3 km;768;6.6 km;1389
Pyrenees;16 mins;979;34 mins;2016;3.2 km;979;7.1 km;2016
Quai+de+la+Gare;29 mins;1719;18 mins;1075;6.9 km;1719;4.8 km;1075
Quai+de+la+Rapee;20 mins;1217;30 mins;1807;3.4 km;1217;5.6 km;1807
Quatre+Septembre;12 mins;739;25 mins;1478;1.7 km;739;6.2 km;1478
Rambuteau;11 mins;650;24 mins;1466;1.2 km;650;4.5 km;1466
Ranelagh;25 mins;1526;29 mins;1718;7.6 km;1526;6.3 km;1718
Raspail;18 mins;1100;9 mins;535;5.2 km;1100;1.0 km;535
Reaumur+Sebastopol;6 mins;349;21 mins;1285;0.5 km;349;4.5 km;1285
Rennes;17 mins;1031;11 mins;685;4.3 km;1031;1.4 km;685
Republique;8 mins;454;28 mins;1663;0.8 km;454;6.9 km;1663
Reuilly+-+Diderot;16 mins;943;35 mins;2089;4.0 km;943;7.9 km;2089
Richard+Lenoir;15 mins;922;35 mins;2089;2.0 km;922;7.2 km;2089
Richelieu+Drouot;9 mins;558;23 mins;1358;1.3 km;558;5.1 km;1358
Riquet;14 mins;852;33 mins;1964;2.8 km;852;7.7 km;1964
Robespierre;21 mins;1256;41 mins;2457;6.0 km;1256;10.5 km;2457
Robinson;38 mins;2290;32 mins;1927;14.9 km;2290;11.9 km;1927
Rome;25 mins;1484;22 mins;1296;4.3 km;1484;6.4 km;1296
Rue+de+la+Pompe;26 mins;1544;27 mins;1637;6.6 km;1544;5.4 km;1637
Rue+des+Boulets;14 mins;836;36 mins;2154;3.3 km;836;8.9 km;2154
Rue+du+Bac;24 mins;1469;15 mins;921;4.3 km;1469;2.4 km;921
Rue+Saint-Maur;19 mins;1115;37 mins;2214;2.5 km;1115;6.5 km;2214
Rueil-Malmaison;30 mins;1772;37 mins;2247;16.1 km;1772;16.2 km;2247
Rungis+La+Fraternelle;46 mins;2770;49 mins;2948;22.4 km;2770;22.7 km;2948
Saint+francois+Xavier;21 mins;1234;6 mins;379;4.7 km;1234;1.5 km;379
Saint+Germain+des-Pres;14 mins;818;13 mins;794;3.2 km;818;1.8 km;794
Saint+Marcel;23 mins;1397;26 mins;1545;4.7 km;1397;4.7 km;1545
Saint-Ambroise;13 mins;760;36 mins;2153;2.0 km;760;8.9 km;2153
Saint-Augustin;16 mins;972;18 mins;1091;3.0 km;972;4.5 km;1091
Saint-Cheron;1 hour 14 mins;4450;1 hour 17 mins;4628;50.9 km;4450;51.2 km;4628
Saint-Cyr;34 mins;2062;29 mins;1759;6.6 km;2062;6.5 km;1759
Saint-Denis+-+Universite;40 mins;2395;33 mins;1994;13.0 km;2395;13.9 km;1994
Saint-Denis+Porte+de+Paris;36 mins;2177;30 mins;1776;11.0 km;2177;11.8 km;1776
Saint-Fargeau;27 mins;1640;50 mins;3025;4.8 km;1640;8.2 km;3025
Saint-Georges;26 mins;1573;24 mins;1469;3.5 km;1573;6.2 km;1469
Saint-Germain-en-Laye;41 mins;2437;49 mins;2912;23.0 km;2437;23.1 km;2912
Saint-Gratien;38 mins;2256;40 mins;2397;18.5 km;2256;16.9 km;2397
Saint-Jacques;21 mins;1253;23 mins;1380;3.1 km;1253;3.6 km;1380
Saint-Lazare;17 mins;1023;15 mins;878;3.0 km;1023;5.2 km;878
Saint-Mande;25 mins;1508;36 mins;2169;5.9 km;1508;12.2 km;2169
Saint-Martin+d'Etampes;1 hour 19 mins;4750;1 hour 23 mins;4974;62.0 km;4750;62.3 km;4974
Saint-Maur-Creteil;37 mins;2232;49 mins;2928;16.8 km;2232;19.4 km;2928
Saint-Michel;11 mins;662;15 mins;878;2.4 km;662;2.6 km;878
Saint-Michel-sur-Orge;50 mins;3010;53 mins;3188;32.5 km;3010;32.8 km;3188
Saint-Ouen;32 mins;1921;25 mins;1520;8.4 km;1921;9.3 km;1520
Saint-Ouen-l'Aumone;50 mins;2976;1 hour 3 mins;3777;30.3 km;2976;34.0 km;3777
Saint-Ouen-l'Aumone+Liesse;47 mins;2796;1 hour 0 mins;3597;28.0 km;2796;31.7 km;3597
Saint-Paul;19 mins;1125;25 mins;1509;2.7 km;1125;7.1 km;1509
Saint-Philippe+du+Roule;17 mins;1016;15 mins;926;3.6 km;1016;4.5 km;926
Saint-Placide;14 mins;860;9 mins;536;4.1 km;860;0.8 km;536
Saint-Quentin-en-Yvelynes;1 hour 1 min;3634;27 mins;1630;20.5 km;3634;17.2 km;1630
Saint-Remy-les-Chevreuse;1 hour 0 mins;3572;55 mins;3307;35.2 km;3572;32.2 km;3307
Saint-Sebastien+Froissart;8 mins;481;28 mins;1690;1.5 km;481;7.6 km;1690
Saint-Sulpice;17 mins;1019;14 mins;815;3.8 km;1019;1.8 km;815
Sainte-Gennevieve-des-Bois;27 mins;1630;19 mins;1122;7.5 km;1630;3.5 km;1122
Sartrouville;31 mins;1870;38 mins;2307;18.7 km;1870;18.7 km;2307
Savigny-sur-Orge;44 mins;2650;47 mins;2828;26.2 km;2650;26.4 km;2828
Sceaux;38 mins;2290;32 mins;1927;14.9 km;2290;11.9 km;1927
Segur;28 mins;1652;14 mins;856;5.4 km;1652;1.7 km;856
Sentier;8 mins;487;26 mins;1548;0.6 km;487;4.9 km;1548
Sermaise;1 hour 18 mins;4690;1 hour 21 mins;4868;55.5 km;4690;55.7 km;4868
Sevran+-+Beaudottes;32 mins;1896;46 mins;2767;19.5 km;1896;25.3 km;2767
Sevres+Babylone;19 mins;1169;13 mins;798;3.9 km;1169;1.8 km;798
Sevres+Lecourbe;27 mins;1638;9 mins;555;6.4 km;1638;1.4 km;555
Simplon;13 mins;804;31 mins;1856;3.2 km;804;8.0 km;1856
Solferino;23 mins;1359;16 mins;975;4.4 km;1359;2.7 km;975
St-Michel+Notre-Dame;11 mins;686;15 mins;902;2.4 km;686;2.6 km;902
Stalingrad;13 mins;792;32 mins;1907;2.2 km;792;8.9 km;1907
Strasbourg+Saint-Denis;1 min;0;22 mins;1293;1 m;0;4.9 km;1293
Sucy-Bonneuil;39 mins;2350;49 mins;2948;23.3 km;2350;25.9 km;2948
Sully+Morland;16 mins;969;25 mins;1483;3.0 km;969;6.3 km;1483
Telegraphe;19 mins;1159;37 mins;2196;4.4 km;1159;8.3 km;2196
Temple;10 mins;628;32 mins;1914;1.0 km;628;5.3 km;1914
Ternes;32 mins;1938;31 mins;1859;6.0 km;1938;5.6 km;1859
Tolbiac;25 mins;1487;23 mins;1373;6.5 km;1487;4.0 km;1373
Torcy;27 mins;1598;37 mins;2227;4.0 km;1598;9.4 km;2227
Trinite+d'Estienne+d'Orves;15 mins;915;21 mins;1285;2.2 km;915;5.1 km;1285
Trocadero;23 mins;1398;19 mins;1130;6.0 km;1398;4.7 km;1130
Tuileries;18 mins;1065;22 mins;1315;3.0 km;1065;3.9 km;1315
Val+d'Europe;56 mins;3342;1 hour 6 mins;3940;37.0 km;3342;39.6 km;3940
Val+de+Fontenay;25 mins;1510;34 mins;2048;13.6 km;1510;16.2 km;2048
Vaneau;23 mins;1381;9 mins;552;4.8 km;1381;1.3 km;552
Varenne;18 mins;1092;7 mins;417;4.1 km;1092;2.0 km;417
Vauboyen;55 mins;3310;29 mins;1728;26.4 km;3310;24.1 km;1728
Vaugirard;25 mins;1471;23 mins;1364;6.4 km;1471;3.4 km;1364
Vavin;18 mins;1082;10 mins;574;4.9 km;1082;1.0 km;574
Versailles+Chantiers;49 mins;2924;16 mins;948;20.7 km;2924;16.3 km;948
Versailles+Rive+Gauche;49 mins;2924;29 mins;1722;21.3 km;2924;17.4 km;1722
Victor+Hugo;16 mins;978;33 mins;2005;2.4 km;978;4.7 km;2005
Villejuif+Leo+Lagrange;31 mins;1847;24 mins;1423;8.9 km;1847;6.4 km;1423
Villejuif+Paul+Vaillant-Couturier;32 mins;1907;26 mins;1543;9.9 km;1907;7.4 km;1543
Villejuif-Louis+Aragon;38 mins;2286;32 mins;1922;11.4 km;2286;8.9 km;1922
Villeneuve-le-Roi;31 mins;1870;34 mins;2048;16.9 km;1870;17.1 km;2048
Villepinte;51 mins;3062;1 hour 5 mins;3903;23.6 km;3062;29.6 km;3903
Villiers;19 mins;1159;24 mins;1419;3.8 km;1159;6.3 km;1419
Vincennes;21 mins;1270;30 mins;1808;9.1 km;1270;11.8 km;1808
Viroflay+Rive+Gauche;43 mins;2564;23 mins;1368;18.0 km;2564;13.6 km;1368
Vitry-sur-Seine;28 mins;1690;31 mins;1868;9.8 km;1690;10.1 km;1868
Volontaires;27 mins;1613;11 mins;686;5.8 km;1613;1.7 km;686
Voltaire;16 mins;955;22 mins;1345;3.0 km;955;2.9 km;1345
Wagram;21 mins;1279;26 mins;1539;4.8 km;1279;7.2 km;1539
```
