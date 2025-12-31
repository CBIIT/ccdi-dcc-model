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
<svg width="3577pt" height="392pt"
 viewBox="0.00 0.00 3576.79 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3572.7947,-388 3572.7947,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="480" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="480" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node23" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2857" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2857" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M531.7245,-363.658C709.6856,-355.6776 1313.2054,-329.2533 1812,-315 2023.9512,-308.9434 2555.1766,-319.6603 2766,-297 2779.9083,-295.5051 2794.8546,-292.9524 2808.5334,-290.2319"/>
<polygon fill="#000000" stroke="#000000" points="2809.6214,-293.5812 2818.7083,-288.1335 2808.2075,-286.7255 2809.6214,-293.5812"/>
<text text-anchor="middle" x="1854.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node26" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2837" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2837" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M429.086,-362.0734C305.5522,-351.8653 0,-322.2454 0,-279 0,-279 0,-279 0,-105 0,-32.1511 2422.053,-19.6488 2790.3062,-18.1689"/>
<polygon fill="#000000" stroke="#000000" points="2790.3669,-21.6688 2800.353,-18.1292 2790.3392,-14.6688 2790.3669,-21.6688"/>
<text text-anchor="middle" x="42.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node28" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1592" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1592" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M475.559,-347.8072C471.0647,-324.5443 467.4936,-284.4722 489,-261 546.6053,-198.1292 593.2088,-237.0314 678,-228 840.5357,-210.6877 1332.6909,-197.9395 1519.249,-193.6098"/>
<polygon fill="#000000" stroke="#000000" points="1519.5814,-197.1031 1529.4979,-193.3733 1519.4198,-190.105 1519.5814,-197.1031"/>
<text text-anchor="middle" x="531.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2143" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2143" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2164.1753,-87.451C2179.6982,-75.6903 2201.8461,-61.1036 2224,-54 2277.3114,-36.9058 2655.8695,-23.626 2790.0158,-19.4103"/>
<polygon fill="#000000" stroke="#000000" points="2790.4792,-22.8977 2800.3653,-19.0879 2790.2611,-15.9011 2790.4792,-22.8977"/>
<text text-anchor="middle" x="2286" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- consent_group -->
<g id="node3" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2318" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2318" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge43" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2332.109,-87.0731C2342.3722,-75.46 2357.3439,-61.2027 2374,-54 2411.5472,-37.7633 2680.5604,-24.6447 2790.4349,-19.9052"/>
<polygon fill="#000000" stroke="#000000" points="2790.7165,-23.3964 2800.558,-19.4728 2790.4178,-16.4028 2790.7165,-23.3964"/>
<text text-anchor="middle" x="2437.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_status -->
<g id="node4" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2485" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2485" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2492.9553,-86.8393C2498.9509,-75.4361 2508.3185,-61.512 2521,-54 2543.6936,-40.5572 2708.5566,-27.1258 2790.7166,-21.1779"/>
<polygon fill="#000000" stroke="#000000" points="2791.0628,-24.6622 2800.7871,-20.4564 2790.5625,-17.6801 2791.0628,-24.6622"/>
<text text-anchor="middle" x="2577.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_radiation -->
<g id="node5" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1294" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1294" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1278.7772,-260.7564C1271.8466,-250.1709 1266.8191,-237.1625 1275,-228 1291.0347,-210.0413 1431.5096,-199.8709 1519.9979,-195.1934"/>
<polygon fill="#000000" stroke="#000000" points="1520.4472,-198.675 1530.2532,-194.6635 1520.0859,-191.6843 1520.4472,-198.675"/>
<text text-anchor="middle" x="1358" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- study_personnel -->
<g id="node6" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2660" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2660" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2645.009,-86.9563C2638.1604,-76.4416 2633.138,-63.4375 2641,-54 2659.5934,-31.6805 2738.1335,-23.1521 2789.9719,-19.9258"/>
<polygon fill="#000000" stroke="#000000" points="2790.4954,-23.4015 2800.2773,-19.3317 2790.0924,-16.4131 2790.4954,-23.4015"/>
<text text-anchor="middle" x="2710.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- genetic_analysis -->
<g id="node7" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1300" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1300" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1385.3348,-361.5486C1548.3715,-352.9546 1889.1262,-334.5244 1901,-330 1911.0537,-326.1691 1909.8743,-318.6364 1920,-315 2008.4881,-283.2217 2672.5293,-307.1605 2766,-297 2779.9065,-295.4883 2794.8522,-292.9303 2808.531,-290.21"/>
<polygon fill="#000000" stroke="#000000" points="2809.6185,-293.5594 2818.7061,-288.1127 2808.2054,-286.7036 2809.6185,-293.5594"/>
<text text-anchor="middle" x="1990" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1217.1115,-360.0006C1121.8134,-350.0285 985.1377,-324.4146 1040,-261 1070.9386,-225.2385 1377.6125,-203.8104 1520.0199,-195.715"/>
<polygon fill="#000000" stroke="#000000" points="1520.6076,-199.1876 1530.3956,-195.1323 1520.215,-192.1986 1520.6076,-199.1876"/>
<text text-anchor="middle" x="1110" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1782" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1782" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1873.0506,-356.0854C1928.4101,-349.6332 2000.4497,-340.4829 2064,-330 2097.1103,-324.5383 2104.6586,-318.8043 2138,-315 2283.9961,-298.3418 2654.0301,-321.0013 2799,-297 2804.0074,-296.171 2809.1826,-295.0172 2814.2853,-293.6902"/>
<polygon fill="#000000" stroke="#000000" points="2815.2719,-297.0485 2823.9457,-290.9644 2813.371,-290.3115 2815.2719,-297.0485"/>
<text text-anchor="middle" x="2224" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1781.8456,-347.9389C1782.8058,-336.5778 1786.1408,-322.6632 1796,-315 1838.5553,-281.9235 2724.9564,-331.9347 2766,-297 2784.057,-281.6306 2796.7086,-109.5634 2804,-87 2808.7179,-72.4003 2815.8998,-56.9231 2822.3601,-44.3348"/>
<polygon fill="#000000" stroke="#000000" points="2825.538,-45.812 2827.107,-35.334 2819.3463,-42.5466 2825.538,-45.812"/>
<text text-anchor="middle" x="2878" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1681.0931,-359.2041C1592.594,-350.8922 1473.5447,-333.1854 1444,-297 1411.2007,-256.8285 1481.7799,-224.9036 1536.3485,-207.2303"/>
<polygon fill="#000000" stroke="#000000" points="1537.4889,-210.5407 1545.9786,-204.2023 1535.3892,-203.863 1537.4889,-210.5407"/>
<text text-anchor="middle" x="1530" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2883" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2883" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2873.4688,-86.9735C2867.0115,-74.7609 2858.3674,-58.4123 2851.1157,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="2854.13,-42.9101 2846.3616,-35.7057 2847.9418,-46.182 2854.13,-42.9101"/>
<text text-anchor="middle" x="2919.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cytogenomic_file -->
<g id="node10" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2584" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2584" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2590.8829,-347.8093C2596.206,-336.3935 2604.7541,-322.4666 2617,-315 2651.7003,-293.8425 2759.1663,-305.0643 2799,-297 2803.7244,-296.0435 2808.6112,-294.8546 2813.4517,-293.5468"/>
<polygon fill="#000000" stroke="#000000" points="2814.61,-296.8557 2823.2556,-290.7316 2812.678,-290.1276 2814.61,-296.8557"/>
<text text-anchor="middle" x="2688.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- medical_history -->
<g id="node11" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1710" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1710" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1686.4045,-261.6033C1668.1612,-248.1527 1642.7512,-229.4183 1622.8885,-214.7738"/>
<polygon fill="#000000" stroke="#000000" points="1624.8786,-211.8925 1614.7527,-208.7753 1620.7245,-217.5267 1624.8786,-211.8925"/>
<text text-anchor="middle" x="1727" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node12" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2108" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2064.6477,-262.0226C2033.722,-250.6084 1990.8937,-236.2013 1952,-228 1853.5319,-207.2366 1737.3118,-198.362 1664.1266,-194.6278"/>
<polygon fill="#000000" stroke="#000000" points="1664.2517,-191.1298 1654.0918,-194.1343 1663.9078,-198.1213 1664.2517,-191.1298"/>
<text text-anchor="middle" x="2111" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- pathology_file -->
<g id="node13" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2768" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2768" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2763.7569,-347.9981C2762.3334,-337.4982 2762.4896,-324.495 2769,-315 2774.3656,-307.1747 2792.6583,-299.1177 2811.1858,-292.6153"/>
<polygon fill="#000000" stroke="#000000" points="2812.4698,-295.8761 2820.8287,-289.3661 2810.2346,-289.2425 2812.4698,-295.8761"/>
<text text-anchor="middle" x="2830" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- treatment_response -->
<g id="node14" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2652" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2652" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2592.0976,-264.1978C2566.4732,-257.7939 2536.2402,-250.1427 2509,-243 2484.4913,-236.5736 2479.0374,-231.8864 2454,-228 2302.7279,-204.5189 1843.4623,-195.5838 1664.4898,-192.9361"/>
<polygon fill="#000000" stroke="#000000" points="1664.438,-189.435 1654.388,-192.7889 1664.336,-196.4343 1664.438,-189.435"/>
<text text-anchor="middle" x="2592" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3024" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3024" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3009.1511,-209.2175C2998.8532,-220.2225 2984.2861,-234.0571 2969,-243 2949.7596,-254.2562 2926.5679,-262.458 2906.2911,-268.1638"/>
<polygon fill="#000000" stroke="#000000" points="2905.3508,-264.7922 2896.6012,-270.7667 2907.1669,-271.5525 2905.3508,-264.7922"/>
<text text-anchor="middle" x="3029.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3020.4769,-173.7995C3013.6287,-140.2529 2997.637,-70.5756 2980,-54 2965.8894,-40.7386 2918.5206,-30.5792 2882.1273,-24.4865"/>
<polygon fill="#000000" stroke="#000000" points="2882.6214,-21.021 2872.1903,-22.8767 2881.5019,-27.9309 2882.6214,-21.021"/>
<text text-anchor="middle" x="3049.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_surgery -->
<g id="node16" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="127" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="127" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M134.1516,-260.9879C139.8223,-249.3368 148.9753,-235.0691 162,-228 192.0833,-211.6725 1231.4732,-196.7609 1518.9626,-192.9417"/>
<polygon fill="#000000" stroke="#000000" points="1519.3203,-196.4374 1529.2731,-192.8052 1519.2276,-189.438 1519.3203,-196.4374"/>
<text text-anchor="middle" x="240.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="344" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="344" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M329.8546,-260.9131C323.2016,-250.1176 318.4135,-236.8344 327,-228 347.8959,-206.5009 1253.2805,-195.4879 1519.2579,-192.7124"/>
<polygon fill="#000000" stroke="#000000" points="1519.6089,-196.2091 1529.572,-192.6056 1519.5363,-189.2095 1519.6089,-196.2091"/>
<text text-anchor="middle" x="406.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2978" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2978" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2943.9381,-348.6425C2934.0105,-343.1089 2923.3304,-336.6772 2914,-330 2902.7528,-321.9511 2891.2221,-312.0094 2881.5005,-303.0476"/>
<polygon fill="#000000" stroke="#000000" points="2883.8166,-300.4212 2874.1318,-296.1253 2879.0238,-305.5231 2883.8166,-300.4212"/>
<text text-anchor="middle" x="3005.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- laboratory_test -->
<g id="node19" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2268" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2268" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2287.046,-348.3258C2301.0863,-336.5062 2321.2746,-321.9004 2342,-315 2438.43,-282.8942 2698.8333,-314.2091 2799,-297 2803.8123,-296.1732 2808.7817,-295.0565 2813.6937,-293.7818"/>
<polygon fill="#000000" stroke="#000000" points="2814.9498,-297.0643 2823.6273,-290.9856 2813.053,-290.3262 2814.9498,-297.0643"/>
<text text-anchor="middle" x="2407.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2268.2868,-347.9632C2267.6572,-315.6763 2260.8503,-249.3815 2217,-228 2168.4752,-204.3392 1818.8026,-195.7206 1664.6604,-193.0475"/>
<polygon fill="#000000" stroke="#000000" points="1664.4089,-189.5428 1654.3509,-192.8725 1664.29,-196.5418 1664.4089,-189.5428"/>
<text text-anchor="middle" x="2327.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_other -->
<g id="node20" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="670" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="670" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M673.5651,-260.7355C676.8282,-249.2884 682.9084,-235.3545 694,-228 728.1678,-205.3442 1311.6605,-195.6224 1519.3415,-192.869"/>
<polygon fill="#000000" stroke="#000000" points="1519.5806,-196.3663 1529.5338,-192.7355 1519.4888,-189.3669 1519.5806,-196.3663"/>
<text text-anchor="middle" x="763.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3208" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3208" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3234.0123,-198.9396C3261.8768,-207.5768 3299.8413,-223.5836 3282,-243 3257.3981,-269.7739 3020.3665,-276.6555 2911.3576,-278.4084"/>
<polygon fill="#000000" stroke="#000000" points="2911.165,-274.9108 2901.2194,-278.5625 2911.2715,-281.91 2911.165,-274.9108"/>
<text text-anchor="middle" x="3310" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3190.087,-178.1645C3173.032,-164.7092 3146.9333,-143.3731 3126,-123 3110.6589,-108.0695 3111.7972,-98.8967 3094,-87 3029.0524,-43.5853 2937.7706,-27.4192 2883.2835,-21.4466"/>
<polygon fill="#000000" stroke="#000000" points="2883.529,-17.9535 2873.2239,-20.4143 2882.8143,-24.917 2883.529,-17.9535"/>
<text text-anchor="middle" x="3150" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- survival -->
<g id="node22" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="823" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="823" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M827.5697,-260.9577C831.4984,-249.4508 838.4166,-235.3625 850,-228 877.9277,-210.249 1338.1097,-197.8193 1519.4129,-193.5898"/>
<polygon fill="#000000" stroke="#000000" points="1519.7348,-197.0834 1529.6511,-193.3528 1519.5727,-190.0853 1519.7348,-197.0834"/>
<text text-anchor="middle" x="889.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge40" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2865.2471,-260.9264C2871.1866,-249.8558 2880.2241,-236.2701 2892,-228 2917.9359,-209.7854 2930.4278,-218.3539 2961,-210 2965.6258,-208.736 2970.4364,-207.4002 2975.2457,-206.0505"/>
<polygon fill="#000000" stroke="#000000" points="2976.3838,-209.366 2985.0556,-203.2791 2974.4806,-202.6297 2976.3838,-209.366"/>
<text text-anchor="middle" x="2928.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2899.9501,-274.4358C2944.1206,-269.1478 3014.6472,-259.0458 3074,-243 3109.5257,-233.3957 3148.7103,-217.875 3175.479,-206.4747"/>
<polygon fill="#000000" stroke="#000000" points="3176.9512,-209.6515 3184.7496,-202.4797 3174.1809,-203.223 3176.9512,-209.6515"/>
<text text-anchor="middle" x="3155.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2823.6545,-267.0436C2787.5554,-254.7204 2728.0229,-236.1884 2675,-228 2575.9508,-212.7037 1891.3653,-197.928 1664.7026,-193.4054"/>
<polygon fill="#000000" stroke="#000000" points="1664.6476,-189.9037 1654.58,-193.2042 1664.5084,-196.9023 1664.6476,-189.9037"/>
<text text-anchor="middle" x="2777.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node24" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3195" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="3195" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3158.653,-349.7222C3146.2161,-343.8462 3132.3343,-336.9433 3120,-330 3109.3652,-324.0134 3108.407,-319.3379 3097,-315 3063.7743,-302.3648 2970.0792,-290.7457 2910.0647,-284.2927"/>
<polygon fill="#000000" stroke="#000000" points="2910.3188,-280.8001 2900.0053,-283.2254 2909.5802,-287.761 2910.3188,-280.8001"/>
<text text-anchor="middle" x="3186.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node25" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="942" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="942" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M934.906,-260.6801C932.0016,-249.797 930.9525,-236.5034 939,-228 958.6962,-207.1881 1353.4845,-196.8117 1519.4712,-193.3554"/>
<polygon fill="#000000" stroke="#000000" points="1519.6648,-196.8523 1529.5907,-193.1474 1519.5208,-189.8538 1519.6648,-196.8523"/>
<text text-anchor="middle" x="982.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node27" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3246" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3246" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge42" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3216.632,-89.0669C3193.9115,-77.4671 3161.314,-62.3776 3131,-54 3045.6674,-30.4175 2942.1411,-22.2722 2883.4857,-19.4665"/>
<polygon fill="#000000" stroke="#000000" points="2883.5656,-15.9666 2873.4193,-19.0166 2883.2531,-22.9596 2883.5656,-15.9666"/>
<text text-anchor="middle" x="3224" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1652.401,-187.3147C1765.8174,-178.1056 2018.2181,-155.6607 2229,-123 2235.8033,-121.9458 2242.8756,-120.7275 2249.9269,-119.4317"/>
<polygon fill="#000000" stroke="#000000" points="2251.0336,-122.7845 2260.2093,-117.4878 2249.7332,-115.9064 2251.0336,-122.7845"/>
<text text-anchor="middle" x="2140.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- generic_file -->
<g id="node29" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="3396" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="3396" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3345.7819,-354.3804C3323.826,-348.4317 3298.0953,-340.2588 3276,-330 3264.9309,-324.8606 3264.5285,-319.004 3253,-315 3191.3226,-293.5785 3004.5857,-284.1586 2911.2772,-280.7"/>
<polygon fill="#000000" stroke="#000000" points="2911.3087,-277.1989 2901.1889,-280.3358 2911.0561,-284.1944 2911.3087,-277.1989"/>
<text text-anchor="middle" x="3329" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge36" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3404.3246,-348.1C3411.5972,-330.8051 3421,-303.6732 3421,-279 3421,-279 3421,-279 3421,-105 3421,-37.9419 3344.5421,-68.1781 3279,-54 3204.5807,-37.9016 2981.3042,-25.189 2883.6182,-20.2403"/>
<polygon fill="#000000" stroke="#000000" points="2883.6162,-16.7359 2873.4534,-19.7305 2883.2655,-23.7271 2883.6162,-16.7359"/>
<text text-anchor="middle" x="3474" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3395.5068,-347.5767C3394.2263,-336.6546 3390.7784,-323.3565 3382,-315 3355.2891,-289.5731 3336.6681,-306.3694 3301,-297 3199.0132,-270.2098 3178.1051,-244.7672 3074,-228 2934.5335,-205.5375 1944.2464,-195.1251 1665.0883,-192.6155"/>
<polygon fill="#000000" stroke="#000000" points="1664.7065,-189.112 1654.6756,-192.5226 1664.644,-196.1117 1664.7065,-189.112"/>
<text text-anchor="middle" x="3354" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_arm -->
<g id="node30" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3509" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3509" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3490.2096,-87.7096C3476.1363,-75.9095 3455.8002,-61.166 3435,-54 3383.4786,-36.2501 3015.5407,-23.4353 2883.7842,-19.3712"/>
<polygon fill="#000000" stroke="#000000" points="2883.7127,-15.8675 2873.6104,-19.0603 2883.4988,-22.8642 2883.7127,-15.8675"/>
<text text-anchor="middle" x="3511.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- radiology_file -->
<g id="node31" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1887" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1887" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1862.7429,-261.7894C1845.684,-250.4959 1821.9014,-236.3264 1799,-228 1755.0715,-212.0287 1703.256,-203.0264 1662.4554,-198.0182"/>
<polygon fill="#000000" stroke="#000000" points="1662.6713,-194.5195 1652.3312,-196.8291 1661.8547,-201.4717 1662.6713,-194.5195"/>
<text text-anchor="middle" x="1889" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node32" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2422" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2422" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2443.8911,-349.2321C2460.713,-337.3628 2485.053,-322.3055 2509,-315 2632.517,-277.3185 2671.9832,-320.3041 2799,-297 2803.8027,-296.1188 2808.7659,-294.9674 2813.6743,-293.6723"/>
<polygon fill="#000000" stroke="#000000" points="2814.9401,-296.9513 2823.6037,-290.8528 2813.028,-290.2175 2814.9401,-296.9513"/>
<text text-anchor="middle" x="2553.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2380.4445,-354.2531C2352.8476,-346.0344 2320.9763,-335.5669 2317,-330 2313.1251,-324.5751 2312.8354,-320.2058 2317,-315 2339.7667,-286.5417 2374.2333,-325.4583 2397,-297 2406.9951,-284.5061 2407.0752,-273.4294 2397,-261 2352.3747,-205.9472 2311.2517,-237.3231 2241,-228 2131.3462,-213.4478 1809.032,-200.0716 1664.0747,-194.6043"/>
<polygon fill="#000000" stroke="#000000" points="1664.0739,-191.1019 1653.9497,-194.2244 1663.8114,-198.097 1664.0739,-191.1019"/>
<text text-anchor="middle" x="2449.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
