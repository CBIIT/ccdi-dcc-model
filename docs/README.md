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
<svg width="3511pt" height="392pt"
 viewBox="0.00 0.00 3511.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3507.3431,-388 3507.3431,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2519.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2519.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.077,-86.9949C70.0519,-75.9517 69.9316,-62.3707 78.3431,-54 100.3889,-32.0611 2135.8783,-20.0798 2472.4566,-18.2479"/>
<polygon fill="#000000" stroke="#000000" points="2472.8346,-21.746 2482.8155,-18.1918 2472.7966,-14.7461 2472.8346,-21.746"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line -->
<g id="node2" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="241.3431" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="241.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge26" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M233.0185,-348.1C225.746,-330.8051 216.3431,-303.6732 216.3431,-279 216.3431,-279 216.3431,-279 216.3431,-105 216.3431,-46.401 2145.9616,-22.1847 2472.6332,-18.505"/>
<polygon fill="#000000" stroke="#000000" points="2472.7433,-22.004 2482.7035,-18.3923 2472.665,-15.0045 2472.7433,-22.004"/>
<text text-anchor="middle" x="256.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="996.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="996.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M239.3702,-347.967C239.2305,-336.7672 241.2353,-323.0233 250.3431,-315 276.2234,-292.2016 774.5215,-282.4307 941.9807,-279.782"/>
<polygon fill="#000000" stroke="#000000" points="942.1124,-283.2804 952.0566,-279.6249 942.0033,-276.2813 942.1124,-283.2804"/>
<text text-anchor="middle" x="290.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="967.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="967.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M958.6985,-347.9591C955.1347,-337.9316 952.7835,-325.4142 957.3431,-315 959.4601,-310.165 962.5822,-305.6913 966.1538,-301.6593"/>
<polygon fill="#000000" stroke="#000000" points="968.7757,-303.989 973.4298,-294.4711 963.8561,-299.0093 968.7757,-303.989"/>
<text text-anchor="middle" x="1001.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2250.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2250.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1006.3219,-353.2031C1014.1944,-351.0907 1022.4716,-349.2007 1030.3431,-348 1070.7765,-341.8322 1737.7774,-359.2729 1766.3431,-330 1770.9992,-325.2287 1770.9862,-319.784 1766.3431,-315 1719.7369,-266.9794 1210.9494,-345.0206 1164.3431,-297 1153.1998,-285.5185 1153.9358,-273.1527 1164.3431,-261 1226.3688,-188.5724 1281.4419,-237.3105 1376.3431,-228 1531.0906,-212.8182 1997.4949,-198.89 2177.9525,-193.9238"/>
<polygon fill="#000000" stroke="#000000" points="2178.234,-197.4175 2188.1343,-193.6448 2178.0421,-190.4201 2178.234,-197.4175"/>
<text text-anchor="middle" x="1208.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node5" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2095.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2095.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2090.1947,-86.6998C2088.3353,-75.824 2088.3515,-62.5313 2096.3431,-54 2121.6439,-26.9908 2367.627,-20.203 2472.4331,-18.5319"/>
<polygon fill="#000000" stroke="#000000" points="2472.7709,-22.0273 2482.7171,-18.3772 2472.6655,-15.0281 2472.7709,-22.0273"/>
<text text-anchor="middle" x="2165.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pathology_file -->
<g id="node6" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="384.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="384.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M410.3098,-349.0726C429.8273,-337.2872 457.6787,-322.4056 484.3431,-315 569.1635,-291.4425 828.0433,-282.804 941.7771,-280.0882"/>
<polygon fill="#000000" stroke="#000000" points="942.0788,-283.5822 951.9948,-279.8509 941.9162,-276.5841 942.0788,-283.5822"/>
<text text-anchor="middle" x="545.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- family_relationship -->
<g id="node7" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2063.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2063.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2067.5204,-260.8687C2071.0036,-249.7751 2077.0991,-236.1855 2087.3431,-228 2102.2551,-216.0846 2144.9794,-206.8997 2182.9451,-200.7902"/>
<polygon fill="#000000" stroke="#000000" points="2183.6437,-204.2237 2192.9859,-199.2263 2182.5663,-197.3071 2183.6437,-204.2237"/>
<text text-anchor="middle" x="2166.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2266.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2266.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2257.1827,-260.7422C2254.8228,-255.1833 2252.5967,-248.9634 2251.3431,-243 2249.8077,-235.6958 2249.1749,-227.6732 2249.0168,-220.197"/>
<polygon fill="#000000" stroke="#000000" points="2252.517,-220.1401 2249.0647,-210.1235 2245.517,-220.1067 2252.517,-220.1401"/>
<text text-anchor="middle" x="2319.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M952.0234,-279.7185C828.3756,-282.0133 481.4349,-290.5112 370.3431,-315 368.0561,-315.5042 320.8945,-334.2357 284.2524,-348.8513"/>
<polygon fill="#000000" stroke="#000000" points="282.7113,-345.6978 274.7207,-352.6549 285.3058,-352.1993 282.7113,-345.6978"/>
<text text-anchor="middle" x="406.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="996.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="996.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M958.4278,-269.6133C933.2215,-261.3715 906.8609,-247.615 919.3431,-228 928.3118,-213.9064 944.4052,-205.2377 959.5685,-199.952"/>
<polygon fill="#000000" stroke="#000000" points="960.7914,-203.2375 969.3144,-196.944 958.727,-196.5489 960.7914,-203.2375"/>
<text text-anchor="middle" x="955.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1017.8989,-263.274C1038.0395,-248.652 1065.4383,-228.9735 1068.3431,-228 1120.9934,-210.355 1929.0543,-196.8196 2177.9399,-193.0522"/>
<polygon fill="#000000" stroke="#000000" points="2178.0177,-196.5516 2187.9638,-192.9012 2177.9122,-189.5523 2178.0177,-196.5516"/>
<text text-anchor="middle" x="1104.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="594.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="594.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M600.1745,-347.8397C604.8339,-336.4367 612.5646,-322.5127 624.3431,-315 650.5029,-298.3145 845.2543,-286.4649 942.0531,-281.54"/>
<polygon fill="#000000" stroke="#000000" points="942.4192,-285.0261 952.2313,-281.0293 942.0684,-278.0349 942.4192,-285.0261"/>
<text text-anchor="middle" x="715.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge19" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1024.4503,-191.1059C1193.8828,-185.6194 2075.7286,-155.6659 2191.3431,-123 2223.8737,-113.8088 2226.8975,-99.4052 2258.3431,-87 2332.1212,-57.8948 2422.4032,-37.1188 2475.1343,-26.3777"/>
<polygon fill="#000000" stroke="#000000" points="2476.0486,-29.764 2485.1638,-24.3637 2474.6704,-22.901 2476.0486,-29.764"/>
<text text-anchor="middle" x="2282.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M996.3431,-210.0034C996.3431,-221.7801 996.3431,-237.4102 996.3431,-250.8156"/>
<polygon fill="#000000" stroke="#000000" points="992.8432,-250.9735 996.3431,-260.9735 999.8432,-250.9736 992.8432,-250.9735"/>
<text text-anchor="middle" x="1020.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2422.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2422.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2414.091,-260.9335C2408.1495,-249.8658 2399.1117,-236.2806 2387.3431,-228 2374.9654,-219.2907 2342.8195,-210.6341 2312.7761,-203.9929"/>
<polygon fill="#000000" stroke="#000000" points="2313.2127,-200.5067 2302.6996,-201.8208 2311.7375,-207.3495 2313.2127,-200.5067"/>
<text text-anchor="middle" x="2445.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node13" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2378.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2378.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2387.0706,-86.72C2393.0923,-75.852 2402.0447,-62.5601 2413.3431,-54 2431.2336,-40.4455 2454.5549,-31.7941 2474.7661,-26.3804"/>
<polygon fill="#000000" stroke="#000000" points="2475.8449,-29.7187 2484.7026,-23.9057 2474.1532,-22.9262 2475.8449,-29.7187"/>
<text text-anchor="middle" x="2464.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2708.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2708.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2670.3364,-267.8596C2662.4141,-265.5673 2654.1112,-263.1868 2646.3431,-261 2592.6867,-245.8955 2579.9937,-238.9764 2525.3431,-228 2456.1254,-214.0978 2375.9848,-204.311 2320.14,-198.486"/>
<polygon fill="#000000" stroke="#000000" points="2320.3088,-194.985 2310.0033,-197.4443 2319.5931,-201.9483 2320.3088,-194.985"/>
<text text-anchor="middle" x="2625.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- genetic_analysis -->
<g id="node15" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1565.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1565.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1480.4018,-361.2325C1397.9192,-355.7964 1278.9619,-345.5908 1235.3431,-330 1223.8512,-325.8924 1223.7145,-319.4305 1212.3431,-315 1183.3906,-303.7196 1103.3436,-292.1669 1049.2579,-285.2889"/>
<polygon fill="#000000" stroke="#000000" points="1049.503,-281.7923 1039.1448,-284.0187 1048.6306,-288.7377 1049.503,-281.7923"/>
<text text-anchor="middle" x="1305.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1650.6176,-361.5079C1705.4675,-356.9409 1770.2861,-347.8626 1791.3431,-330 1815.9939,-309.0888 1789.6818,-281.8988 1814.3431,-261 1867.9381,-215.582 2068.3838,-199.8281 2177.8564,-194.544"/>
<polygon fill="#000000" stroke="#000000" points="2178.332,-198.0257 2188.1585,-194.0646 2178.0066,-191.0333 2178.332,-198.0257"/>
<text text-anchor="middle" x="1884.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2519.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2519.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2519.3431,-86.9735C2519.3431,-75.1918 2519.3431,-59.5607 2519.3431,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="2522.8432,-46.0033 2519.3431,-36.0034 2515.8432,-46.0034 2522.8432,-46.0033"/>
<text text-anchor="middle" x="2567.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="811.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="811.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M808.996,-347.7488C808.6601,-336.8915 810.2689,-323.601 818.3431,-315 834.9944,-297.2625 896.2584,-287.8277 942.2946,-283.1314"/>
<polygon fill="#000000" stroke="#000000" points="942.8375,-286.5952 952.4527,-282.1456 942.1613,-279.628 942.8375,-286.5952"/>
<text text-anchor="middle" x="884.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- generic_file -->
<g id="node18" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2744.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2744.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2791.7319,-353.462C2800.8454,-351.3821 2810.3518,-349.438 2819.3431,-348 2843.5615,-344.1267 3022.7227,-348.0358 3039.3431,-330 3043.8609,-325.0975 3041.9351,-321.1422 3039.3431,-315 3023.1829,-276.7043 2808.6429,-72.3424 2771.3431,-54 2736.1241,-36.6808 2628.4732,-26.0648 2565.8495,-21.1874"/>
<polygon fill="#000000" stroke="#000000" points="2566.0661,-17.6939 2555.8296,-20.426 2565.5356,-24.6738 2566.0661,-17.6939"/>
<text text-anchor="middle" x="2999.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2679.7702,-362.6616C2600.539,-358.6669 2462.0936,-352.0159 2343.3431,-348 2255.4817,-345.0287 1636.3198,-356.0071 1552.3431,-330 1540.6854,-326.3897 1540.9592,-318.7423 1529.3431,-315 1445.496,-287.9877 1221.0929,-304.7447 1133.3431,-297 1105.0947,-294.5068 1073.7222,-290.478 1048.1342,-286.8635"/>
<polygon fill="#000000" stroke="#000000" points="1048.306,-283.3524 1037.9105,-285.3981 1047.3128,-290.2816 1048.306,-283.3524"/>
<text text-anchor="middle" x="1605.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2755.6419,-347.9106C2768.0531,-325.4787 2783.9179,-287.0266 2765.3431,-261 2739.134,-224.2762 2713.4841,-237.3346 2669.3431,-228 2605.0314,-214.3998 2423.8922,-202.121 2322.0924,-196.0334"/>
<polygon fill="#000000" stroke="#000000" points="2322.0823,-192.5267 2311.8926,-195.4283 2321.6677,-199.5144 2322.0823,-192.5267"/>
<text text-anchor="middle" x="2826.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node19" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1129.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1129.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1099.7953,-348.8241C1090.013,-342.9916 1079.129,-336.3433 1069.3431,-330 1054.9764,-320.6874 1039.3788,-309.8881 1026.3038,-300.6311"/>
<polygon fill="#000000" stroke="#000000" points="1028.2907,-297.7493 1018.1141,-294.8017 1024.2314,-303.4521 1028.2907,-297.7493"/>
<text text-anchor="middle" x="1140.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2880.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2880.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2929.8272,-360.218C2973.9822,-354.2697 3034.6179,-343.9137 3054.3431,-330 3076.0188,-314.7105 3085.3431,-305.5256 3085.3431,-279 3085.3431,-279 3085.3431,-279 3085.3431,-105 3085.3431,-52.5563 2700.828,-27.46 2565.6557,-20.258"/>
<polygon fill="#000000" stroke="#000000" points="2565.7795,-16.7597 2555.61,-19.7313 2565.413,-23.7501 2565.7795,-16.7597"/>
<text text-anchor="middle" x="3127.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2842.9449,-353.3254C2835.2237,-351.174 2827.0844,-349.2381 2819.3431,-348 2449.2089,-288.8036 1506.9691,-327.1192 1133.3431,-297 1104.8454,-294.7027 1073.1893,-290.6432 1047.4919,-286.9602"/>
<polygon fill="#000000" stroke="#000000" points="1047.9949,-283.4966 1037.5947,-285.5184 1046.9857,-290.4235 1047.9949,-283.4966"/>
<text text-anchor="middle" x="2675.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2858.9916,-349.5732C2848.7579,-339.6317 2840.1354,-326.6623 2847.3431,-315 2856.7477,-299.7831 2873.9386,-312.2169 2883.3431,-297 2891.7548,-283.3896 2893.4649,-273.3915 2883.3431,-261 2848.3579,-218.1697 2481.3023,-200.1383 2322.6884,-194.3062"/>
<polygon fill="#000000" stroke="#000000" points="2322.668,-190.8033 2312.548,-193.9396 2322.415,-197.7987 2322.668,-190.8033"/>
<text text-anchor="middle" x="2931.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- consent_group -->
<g id="node22" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2676.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2676.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge32" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2301.3078,-181.6024C2367.474,-168.1019 2486.5364,-143.8036 2588.3431,-123 2594.4593,-121.7502 2600.8144,-120.4511 2607.1843,-119.1488"/>
<polygon fill="#000000" stroke="#000000" points="2608.0778,-122.5386 2617.1739,-117.1061 2606.6754,-115.6805 2608.0778,-122.5386"/>
<text text-anchor="middle" x="2546.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge24" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2660.1307,-86.9821C2649.6497,-76.2126 2635.2261,-62.9324 2620.3431,-54 2602.3487,-43.2002 2580.6155,-34.9307 2561.9262,-29.0574"/>
<polygon fill="#000000" stroke="#000000" points="2562.7685,-25.6559 2552.1839,-26.1222 2560.749,-32.3583 2562.7685,-25.6559"/>
<text text-anchor="middle" x="2703.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3131.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3131.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3194.3499,-351.3249C3252.9738,-335.786 3331.3431,-309.3394 3331.3431,-279 3331.3431,-279 3331.3431,-279 3331.3431,-105 3331.3431,-66.2051 2737.6253,-30.1439 2565.5545,-20.5073"/>
<polygon fill="#000000" stroke="#000000" points="2565.7247,-17.0114 2555.5456,-19.95 2565.3355,-24.0006 2565.7247,-17.0114"/>
<text text-anchor="middle" x="3417.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3052.8075,-353.5352C2970.6525,-341.1246 2837.8213,-322.8288 2722.3431,-315 2017.6931,-267.2287 1837.8321,-347.0909 1133.3431,-297 1104.825,-294.9723 1073.1674,-290.9314 1047.4744,-287.1912"/>
<polygon fill="#000000" stroke="#000000" points="1047.9846,-283.7287 1037.5792,-285.7231 1046.9572,-290.6529 1047.9846,-283.7287"/>
<text text-anchor="middle" x="2954.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3123.1744,-347.5729C3117.6946,-336.9223 3109.6029,-323.9099 3099.3431,-315 3054.8793,-276.3863 3034.3279,-279.2689 2978.3431,-261 2911.7983,-239.2851 2893.6868,-237.5504 2824.3431,-228 2645.3922,-203.3539 2432.7027,-195.5633 2323.3318,-193.1135"/>
<polygon fill="#000000" stroke="#000000" points="2323.1477,-189.6088 2313.0746,-192.8927 2322.997,-196.6072 2323.1477,-189.6088"/>
<text text-anchor="middle" x="3160.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node24" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3429.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3429.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3407.9978,-87.8517C3391.8351,-75.9566 3368.5257,-61.0344 3345.3431,-54 3270.875,-31.4037 2729.8221,-21.2569 2566.1336,-18.6825"/>
<polygon fill="#000000" stroke="#000000" points="2565.9595,-15.1795 2555.9064,-18.5239 2565.8508,-22.1787 2565.9595,-15.1795"/>
<text text-anchor="middle" x="3432.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- laboratory_test -->
<g id="node25" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2252.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2252.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2170.7494,-363.7292C1964.2542,-357.8251 1434.6892,-341.6433 1398.3431,-330 1386.7209,-326.2769 1386.9041,-318.9093 1375.3431,-315 1324.2583,-297.726 1186.9868,-302.5146 1133.3431,-297 1105.1336,-294.1 1073.764,-290.0401 1048.168,-286.5099"/>
<polygon fill="#000000" stroke="#000000" points="1048.3277,-282.9985 1037.9404,-285.0854 1047.3619,-289.9315 1048.3277,-282.9985"/>
<text text-anchor="middle" x="1463.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2316.6459,-354.742C2377.2939,-342.7866 2462.1247,-322.158 2484.3431,-297 2504.8152,-273.8194 2513.5456,-251.4159 2493.3431,-228 2482.0976,-214.9657 2388.3735,-204.0525 2320.6842,-197.7698"/>
<polygon fill="#000000" stroke="#000000" points="2320.7569,-194.262 2310.4803,-196.8392 2320.1211,-201.2331 2320.7569,-194.262"/>
<text text-anchor="middle" x="2570.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- radiology_file -->
<g id="node26" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1335.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1335.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1353.7964,-261.3495C1367.4204,-249.541 1387.0513,-234.9389 1407.3431,-228 1479.0952,-203.4642 1986.2952,-195.0674 2177.5774,-192.7538"/>
<polygon fill="#000000" stroke="#000000" points="2177.8523,-196.2509 2187.81,-192.6322 2177.7691,-189.2514 2177.8523,-196.2509"/>
<text text-anchor="middle" x="1466.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment_response -->
<g id="node27" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1531.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1531.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1527.7896,-260.8976C1526.7507,-249.8155 1527.7162,-236.2278 1536.3431,-228 1559.2919,-206.1129 2000.8007,-196.2263 2177.8279,-193.1303"/>
<polygon fill="#000000" stroke="#000000" points="2177.8956,-196.6297 2187.8336,-192.9576 2177.7747,-189.6308 2177.8956,-196.6297"/>
<text text-anchor="middle" x="1619.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment -->
<g id="node28" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1711.3431" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1711.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1706.1406,-260.6486C1704.2609,-249.7537 1704.2746,-236.4587 1712.3431,-228 1728.1769,-211.4006 2035.2699,-199.1126 2178.2436,-194.2674"/>
<polygon fill="#000000" stroke="#000000" points="2178.3709,-197.7652 2188.2478,-193.9315 2178.1359,-190.7692 2178.3709,-197.7652"/>
<text text-anchor="middle" x="1759.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
</g>
</svg>
</div>
