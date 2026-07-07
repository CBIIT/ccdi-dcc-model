<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/ccdi-dcc-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Childhood Cancer Data Initiative Data Coordination Center Model

[View model on GitHub Pages](https://cbiit.github.io/ccdi-dcc-model/)



Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/ccdi-dcc-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="3215pt" height="479pt"
 viewBox="0.00 0.00 3215.39 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3211.3875,-475 3211.3875,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2422.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2422.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- treatment_other -->
<g id="node2" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2404.0444" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2404.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1874.0444" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1874.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2376.9252,-261.6861C2357.2323,-250.0362 2329.5069,-235.4852 2303.0444,-228 2237.9671,-209.5921 2050.508,-199.2194 1946.2197,-194.7206"/>
<polygon fill="#000000" stroke="#000000" points="1946.2251,-191.2178 1936.0857,-194.2907 1945.9283,-198.2115 1946.2251,-191.2178"/>
<text text-anchor="middle" x="2409.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- treatment_surgery -->
<g id="node3" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2742.0444" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2742.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2711.9864,-261.6637C2689.8356,-249.8413 2658.5528,-235.09 2629.0444,-228 2563.9523,-212.3602 2122.9166,-198.7799 1946.6322,-193.913"/>
<polygon fill="#000000" stroke="#000000" points="1946.5099,-190.4084 1936.4175,-193.6326 1946.3177,-197.4058 1946.5099,-190.4084"/>
<text text-anchor="middle" x="2748.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge42" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M57.7797,-86.9964C55.7553,-75.9538 55.6351,-62.3729 64.0444,-54 85.3016,-32.8349 2045.4097,-20.2421 2375.1989,-18.2723"/>
<polygon fill="#000000" stroke="#000000" points="2375.382,-21.7714 2385.361,-18.2119 2375.3403,-14.7715 2375.382,-21.7714"/>
<text text-anchor="middle" x="115.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node5" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2497.0444" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2497.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- sample -->
<g id="node20" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1984.0444" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1984.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2442.9714,-438.7322C2419.036,-432.2932 2390.5786,-424.4689 2365.0444,-417 2343.5925,-410.7252 2338.9258,-406.5562 2317.0444,-402 2220.0471,-381.8032 2104.6545,-372.5438 2038.3207,-368.6094"/>
<polygon fill="#000000" stroke="#000000" points="2038.2903,-365.102 2028.1061,-368.0228 2037.8889,-372.0905 2038.2903,-365.102"/>
<text text-anchor="middle" x="2435.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2499.309,-434.935C2505.0203,-385.5107 2517.2386,-250.2602 2483.0444,-228 2460.8827,-213.5729 2102.5671,-199.7433 1946.1452,-194.3615"/>
<polygon fill="#000000" stroke="#000000" points="1946.2534,-190.8633 1936.1396,-194.0194 1946.0141,-197.8592 1946.2534,-190.8633"/>
<text text-anchor="middle" x="2576.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2739.0444" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2739.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2759.2894,-435.1375C2783.1328,-412.9249 2822.1331,-372.6932 2843.0444,-330 2863.1229,-289.0072 2867.5781,-255.365 2831.0444,-228 2672.2079,-109.0258 2519.7691,-278.9568 2397.0444,-123 2379.2209,-100.3501 2391.8391,-67.0143 2404.7533,-44.0091"/>
<polygon fill="#000000" stroke="#000000" points="2407.9228,-45.527 2410.0291,-35.1436 2401.9074,-41.9472 2407.9228,-45.527"/>
<text text-anchor="middle" x="2932.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2661.1297,-440.3819C2627.6251,-434.3229 2588.1686,-426.3389 2553.0444,-417 2533.0774,-411.6912 2529.2994,-406.0744 2509.0444,-402 2420.1465,-384.1175 2153.4419,-372.3218 2038.1349,-367.9257"/>
<polygon fill="#000000" stroke="#000000" points="2038.2423,-364.4274 2028.1175,-367.5479 2037.9784,-371.4224 2038.2423,-364.4274"/>
<text text-anchor="middle" x="2639.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2736.09,-434.8006C2733.9623,-424.7236 2730.4858,-412.2094 2725.0444,-402 2701.0326,-356.9483 2689.2419,-347.7074 2650.0444,-315 2591.4599,-266.1156 2575.0638,-250.1359 2502.0444,-228 2450.133,-212.263 2100.5235,-199.2687 1946.5793,-194.2391"/>
<polygon fill="#000000" stroke="#000000" points="1946.3919,-190.7312 1936.2836,-193.905 1946.1649,-197.7276 1946.3919,-190.7312"/>
<text text-anchor="middle" x="2753.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- laboratory_test -->
<g id="node7" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2298.0444" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2298.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2245.0711,-439.1436C2226.0307,-433.3439 2204.6688,-425.8694 2186.0444,-417 2175.026,-411.7527 2174.3404,-406.6193 2163.0444,-402 2122.5481,-385.4396 2073.6863,-376.2717 2037.2513,-371.3388"/>
<polygon fill="#000000" stroke="#000000" points="2037.6874,-367.8661 2027.3216,-370.0571 2036.7913,-374.8085 2037.6874,-367.8661"/>
<text text-anchor="middle" x="2251.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2361.2674,-441.456C2413.0389,-431.8551 2478.0828,-419.3876 2480.0444,-417 2484.2764,-411.8489 2483.3068,-407.8139 2480.0444,-402 2469.0872,-382.4735 2325.8255,-310.6081 2308.0444,-297 2289.5695,-282.861 2288.6289,-274.9947 2270.0444,-261 2246.967,-243.6219 2241.4759,-237.06 2214.0444,-228 2165.8407,-212.0795 2030.2666,-201.3622 1945.595,-196.0025"/>
<polygon fill="#000000" stroke="#000000" points="1945.7291,-192.5041 1935.5308,-195.3754 1945.2938,-199.4906 1945.7291,-192.5041"/>
<text text-anchor="middle" x="2429.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- survival -->
<g id="node8" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="412.0444" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="412.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M445.1014,-265.8898C478.1507,-253.4926 530.7266,-235.6786 578.0444,-228 698.5729,-208.4409 1545.9116,-196.1745 1801.3384,-192.8904"/>
<polygon fill="#000000" stroke="#000000" points="1801.661,-196.3867 1811.6154,-192.7591 1801.5715,-189.3873 1801.661,-196.3867"/>
<text text-anchor="middle" x="617.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2466.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2466.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2456.9276,-86.9735C2450.7511,-74.7609 2442.4828,-58.4123 2435.5463,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="2438.6355,-43.0498 2430.999,-35.7057 2432.3889,-46.209 2438.6355,-43.0498"/>
<text text-anchor="middle" x="2494.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- consent_group -->
<g id="node10" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2116.0444" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2116.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge20" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2149.7693,-88.5623C2173.6633,-77.4717 2206.7309,-63.2292 2237.0444,-54 2283.6818,-39.8008 2338.6973,-29.9354 2376.5415,-24.1689"/>
<polygon fill="#000000" stroke="#000000" points="2377.3633,-27.5852 2386.739,-22.6509 2376.3326,-20.6615 2377.3633,-27.5852"/>
<text text-anchor="middle" x="2300.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- pathology_file -->
<g id="node11" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1480.0444" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1480.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1494.7939,-435.0849C1505.4846,-423.477 1521.0078,-409.2211 1538.0444,-402 1573.2945,-387.0589 1818.7425,-373.7806 1929.7456,-368.4646"/>
<polygon fill="#000000" stroke="#000000" points="1930.2338,-371.9455 1940.0566,-367.9752 1929.9019,-364.9533 1930.2338,-371.9455"/>
<text text-anchor="middle" x="1599.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1657.0444" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1657.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1658.294,-434.9148C1660.0729,-423.6935 1664.2657,-409.9454 1674.0444,-402 1693.4709,-386.2156 1846.3805,-374.4608 1929.9424,-369.1427"/>
<polygon fill="#000000" stroke="#000000" points="1930.2601,-372.6298 1940.0216,-368.5111 1929.8222,-365.6435 1930.2601,-372.6298"/>
<text text-anchor="middle" x="1740.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2008.0444" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2008.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2003.2087,-261.2077C1999.3871,-250.2493 1993.0043,-236.683 1983.0444,-228 1970.3555,-216.938 1954.1733,-209.2565 1938.1844,-203.9292"/>
<polygon fill="#000000" stroke="#000000" points="1938.8732,-200.48 1928.287,-200.9071 1936.829,-207.1749 1938.8732,-200.48"/>
<text text-anchor="middle" x="2019.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_response -->
<g id="node14" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="583.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="583.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M615.4031,-261.7748C639.6183,-249.8414 673.9527,-234.9051 706.0444,-228 812.5535,-205.0828 1562.6746,-195.2782 1801.3231,-192.7163"/>
<polygon fill="#000000" stroke="#000000" points="1801.6614,-196.213 1811.6236,-192.6068 1801.5869,-189.2134 1801.6614,-196.213"/>
<text text-anchor="middle" x="789.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- methylation_array_file -->
<g id="node15" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1874.0444" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1874.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1832.8968,-436.1322C1816.4638,-426.9482 1803.6292,-414.8518 1814.0444,-402 1828.5384,-384.1153 1886.1669,-374.7604 1930.3504,-370.1213"/>
<polygon fill="#000000" stroke="#000000" points="1930.7995,-373.594 1940.4039,-369.1212 1930.1065,-366.6283 1930.7995,-373.594"/>
<text text-anchor="middle" x="1905.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- generic_file -->
<g id="node16" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="298.0444" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="298.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge39" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M253.097,-439.8554C219.7503,-427.0179 180.0444,-403.7966 180.0444,-366 180.0444,-366 180.0444,-366 180.0444,-105 180.0444,-93.3184 394.1905,-69.0955 635.0444,-54 988.0784,-31.8736 2129.6038,-20.6053 2375.2123,-18.4041"/>
<polygon fill="#000000" stroke="#000000" points="2375.5981,-21.9009 2385.5665,-18.3119 2375.5358,-14.9011 2375.5981,-21.9009"/>
<text text-anchor="middle" x="233.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M361.8112,-448.7112C501.7383,-439.3888 846.2673,-416.9191 1135.0444,-402 1435.1495,-386.4957 1795.1848,-372.8726 1929.7829,-367.9528"/>
<polygon fill="#000000" stroke="#000000" points="1929.9728,-371.4483 1939.8385,-367.5861 1929.7176,-364.4529 1929.9728,-371.4483"/>
<text text-anchor="middle" x="1188.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M292.2422,-435.0185C279.4209,-391.3915 254.3816,-279.7214 315.0444,-228 343.6583,-203.6037 1497.3723,-194.4352 1801.2929,-192.4406"/>
<polygon fill="#000000" stroke="#000000" points="1801.34,-195.9404 1811.317,-192.3754 1801.2944,-188.9406 1801.34,-195.9404"/>
<text text-anchor="middle" x="330.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_radiation -->
<g id="node17" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="810.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="810.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M837.5038,-261.5634C857.7914,-249.6926 886.5483,-234.9245 914.0444,-228 999.0859,-206.5837 1592.3838,-196.058 1801.3897,-192.9838"/>
<polygon fill="#000000" stroke="#000000" points="1801.6941,-196.4798 1811.642,-192.8345 1801.5921,-189.4806 1801.6941,-196.4798"/>
<text text-anchor="middle" x="997.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- study_status -->
<g id="node18" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2614.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2614.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2595.1088,-87.5269C2582.347,-76.5569 2564.6793,-62.8587 2547.0444,-54 2521.5037,-41.1698 2490.6648,-32.2268 2466.009,-26.4632"/>
<polygon fill="#000000" stroke="#000000" points="2466.724,-23.0367 2456.2001,-24.2602 2465.19,-29.8666 2466.724,-23.0367"/>
<text text-anchor="middle" x="2626.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2789.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2789.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2761.0805,-87.8643C2741.1519,-76.4534 2713.3406,-62.1152 2687.0444,-54 2612.8025,-31.0884 2522.3863,-22.7478 2468.6657,-19.7187"/>
<polygon fill="#000000" stroke="#000000" points="2468.5964,-16.2103 2458.4266,-19.181 2468.2292,-23.2007 2468.5964,-16.2103"/>
<text text-anchor="middle" x="2793.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1982.0292,-347.6878C1981.5275,-337.8039 1981.8615,-325.5099 1985.0444,-315 1986.1636,-311.3044 1987.7788,-307.6231 1989.642,-304.103"/>
<polygon fill="#000000" stroke="#000000" points="1992.8075,-305.6319 1994.9829,-295.2628 1986.816,-302.0121 1992.8075,-305.6319"/>
<text text-anchor="middle" x="2021.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2022.2173,-356.6287C2035.9453,-351.2176 2050.0128,-342.8388 2058.0444,-330 2065.6662,-317.8162 2083.8515,-267.8519 2047.0444,-228 2033.0071,-212.8015 1985.7379,-203.6249 1944.1514,-198.3438"/>
<polygon fill="#000000" stroke="#000000" points="1944.3504,-194.8424 1934.0023,-197.1157 1943.5094,-201.7917 1944.3504,-194.8424"/>
<text text-anchor="middle" x="2106.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node28" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2212.0444" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2212.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2018.1847,-354.3836C2038.0648,-347.5114 2063.5648,-338.5114 2086.0444,-330 2114.2957,-319.3032 2145.7978,-306.5523 2170.2361,-296.4761"/>
<polygon fill="#000000" stroke="#000000" points="2171.6671,-299.6718 2179.5706,-292.6159 2168.992,-293.2031 2171.6671,-299.6718"/>
<text text-anchor="middle" x="2161.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1913.1948,-177.9253C1954.1973,-163.1847 2018.8054,-139.9578 2064.0614,-123.6881"/>
<polygon fill="#000000" stroke="#000000" points="2065.4676,-126.9019 2073.6939,-120.2252 2063.0994,-120.3147 2065.4676,-126.9019"/>
<text text-anchor="middle" x="2060.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node22" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1018.0444" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1018.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1045.0951,-261.9008C1065.4159,-250.03 1094.3897,-235.1168 1122.0444,-228 1186.5808,-211.3918 1625.5286,-198.3985 1801.3963,-193.8005"/>
<polygon fill="#000000" stroke="#000000" points="1801.6824,-197.2943 1811.5881,-193.5357 1801.5006,-190.2967 1801.6824,-197.2943"/>
<text text-anchor="middle" x="1190.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2964.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2964.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2938.9058,-88.1456C2919.9982,-76.3965 2892.9914,-61.5283 2867.0444,-54 2793.3367,-32.6143 2567.3719,-22.7725 2468.8209,-19.412"/>
<polygon fill="#000000" stroke="#000000" points="2468.6803,-15.9054 2458.5692,-19.0702 2468.447,-22.9016 2468.6803,-15.9054"/>
<text text-anchor="middle" x="2959.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node24" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1250.0444" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1250.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1254.0164,-260.7876C1257.5245,-249.3625 1263.8826,-235.4335 1275.0444,-228 1296.6194,-213.6316 1646.784,-199.8426 1801.5085,-194.4188"/>
<polygon fill="#000000" stroke="#000000" points="1801.9858,-197.9044 1811.8579,-194.0583 1801.7421,-190.9086 1801.9858,-197.9044"/>
<text text-anchor="middle" x="1377.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- family_relationship -->
<g id="node25" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1497.0444" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1497.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1487.1294,-260.8699C1482.6941,-250.0582 1480.0515,-236.773 1488.0444,-228 1508.6895,-205.3399 1695.4403,-196.6999 1801.4217,-193.6012"/>
<polygon fill="#000000" stroke="#000000" points="1801.8342,-197.0911 1811.7313,-193.3098 1801.6364,-190.0939 1801.8342,-197.0911"/>
<text text-anchor="middle" x="1567.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- synonym -->
<g id="node26" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1105.0444" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1105.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1057.0154,-445.8966C899.8396,-422.2605 407.863,-345.0459 355.0444,-297 333.882,-277.7498 336.0444,-264.108 336.0444,-235.5 336.0444,-235.5 336.0444,-235.5 336.0444,-105 336.0444,-52.1905 2065.6987,-23.4185 2374.9982,-18.6956"/>
<polygon fill="#000000" stroke="#000000" points="2375.4509,-22.1892 2385.3966,-18.5378 2375.3446,-15.19 2375.4509,-22.1892"/>
<text text-anchor="middle" x="378.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1147.3721,-442.3415C1175.1718,-435.2856 1212.3147,-425.753 1245.0444,-417 1269.1075,-410.5647 1274.4607,-406.0109 1299.0444,-402 1420.0152,-382.2634 1789.3426,-370.9905 1929.4053,-367.3312"/>
<polygon fill="#000000" stroke="#000000" points="1929.576,-370.828 1939.4822,-367.0707 1929.3951,-363.8303 1929.576,-370.828"/>
<text text-anchor="middle" x="1341.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1105.5191,-434.5571C1106.7926,-423.6278 1110.2397,-410.3287 1119.0444,-402 1279.8987,-249.8426 1410.1992,-400.2987 1606.0444,-297 1626.6219,-286.1464 1624.3159,-273.3296 1644.0444,-261 1679.4664,-238.8625 1692.1832,-240.4849 1732.0444,-228 1758.934,-219.578 1789.1457,-211.7029 1814.7676,-205.4788"/>
<polygon fill="#000000" stroke="#000000" points="1815.8043,-208.8294 1824.7099,-203.09 1814.1689,-202.0231 1815.8043,-208.8294"/>
<text text-anchor="middle" x="1604.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- radiology_file -->
<g id="node27" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1726.0444" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1726.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1729.0245,-260.6245C1731.7101,-249.7204 1736.7366,-236.4244 1746.0444,-228 1756.1811,-218.8254 1784.3417,-210.4336 1811.6764,-204.0644"/>
<polygon fill="#000000" stroke="#000000" points="1812.6887,-207.4241 1821.6748,-201.8117 1811.15,-200.5953 1812.6887,-207.4241"/>
<text text-anchor="middle" x="1805.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2181.8847,-264.6328C2156.757,-253.193 2119.7587,-237.5636 2086.0444,-228 2038.9293,-214.635 1984.4319,-205.5142 1942.4902,-199.7973"/>
<polygon fill="#000000" stroke="#000000" points="1942.7572,-196.302 1932.3828,-198.4521 1941.8336,-203.2408 1942.7572,-196.302"/>
<text text-anchor="middle" x="2169.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- diagnosis -->
<g id="node29" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1331.0444" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1331.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1353.6966,-436.5012C1371.3681,-424.605 1397.0348,-409.3923 1422.0444,-402 1469.8561,-387.8679 1798.2686,-373.4012 1929.7731,-368.105"/>
<polygon fill="#000000" stroke="#000000" points="1930.1623,-371.5923 1940.0143,-367.6951 1929.8823,-364.5979 1930.1623,-371.5923"/>
<text text-anchor="middle" x="1466.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1344.8964,-435.1492C1354.6268,-423.8768 1368.6209,-409.9821 1384.0444,-402 1439.2013,-373.4547 1885.0055,-336.3622 1933.0444,-297 1957.9417,-276.5996 1972.5839,-254.9892 1955.0444,-228 1949.447,-219.387 1941.2617,-212.818 1932.2185,-207.8127"/>
<polygon fill="#000000" stroke="#000000" points="1933.4776,-204.5332 1922.9535,-203.3108 1930.4183,-210.8293 1933.4776,-204.5332"/>
<text text-anchor="middle" x="1926.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node30" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1871.0444" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1871.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1868.7054,-260.5723C1867.7914,-250.8721 1867.1519,-238.7839 1868.0444,-228 1868.2548,-225.4584 1868.5473,-222.826 1868.8909,-220.1943"/>
<polygon fill="#000000" stroke="#000000" points="1872.3613,-220.6534 1870.4041,-210.2409 1865.4408,-219.6013 1872.3613,-220.6534"/>
<text text-anchor="middle" x="1911.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- cytogenomic_file -->
<g id="node31" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2097.0444" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2097.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2053.1517,-437.2326C2041.6611,-431.879 2029.7776,-425.144 2020.0444,-417 2011.9013,-410.1864 2004.7184,-401.1188 1998.9535,-392.5202"/>
<polygon fill="#000000" stroke="#000000" points="2001.7749,-390.4326 1993.4783,-383.8434 1995.855,-394.1682 2001.7749,-390.4326"/>
<text text-anchor="middle" x="2091.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node32" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3130.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3130.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3101.274,-88.0169C3079.7018,-76.2039 3049.0272,-61.312 3020.0444,-54 2915.9285,-27.7327 2590.7341,-20.4182 2468.8249,-18.5714"/>
<polygon fill="#000000" stroke="#000000" points="2468.7442,-15.0699 2458.6941,-18.4235 2468.6419,-22.0692 2468.7442,-15.0699"/>
<text text-anchor="middle" x="3122.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
