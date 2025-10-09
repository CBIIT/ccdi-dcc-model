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
<svg width="3289pt" height="392pt"
 viewBox="0.00 0.00 3289.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3285.3431,-388 3285.3431,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2554.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2554.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2927.3431" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2927.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2592.8558,-270.0172C2660.3695,-254.27 2800.0951,-221.6798 2875.8357,-204.0138"/>
<polygon fill="#000000" stroke="#000000" points="2876.6947,-207.4075 2885.6382,-201.7274 2875.1046,-200.5905 2876.6947,-207.4075"/>
<text text-anchor="middle" x="2798.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2554.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2554.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2582.476,-264.9861C2590.7317,-259.3644 2598.7665,-252.0415 2603.3431,-243 2610.1209,-229.61 2599.2568,-217.3802 2586.0519,-208.2552"/>
<polygon fill="#000000" stroke="#000000" points="2587.5341,-205.0544 2577.1982,-202.7261 2583.8262,-210.9917 2587.5341,-205.0544"/>
<text text-anchor="middle" x="2641.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1625.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1625.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2525.6909,-265.1871C2496.7969,-251.5194 2454.0145,-232.0661 2436.3431,-228 2365.6153,-211.7259 1883.6619,-198.334 1698.0268,-193.7221"/>
<polygon fill="#000000" stroke="#000000" points="1697.9041,-190.2181 1687.8207,-193.47 1697.7312,-197.216 1697.9041,-190.2181"/>
<text text-anchor="middle" x="2510.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- genetic_analysis -->
<g id="node2" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="3146.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="3146.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3095.6058,-351.2291C3077.2802,-345.337 3056.6152,-338.0379 3038.3431,-330 3025.7777,-324.4724 3024.4862,-318.963 3011.3431,-315 2937.4168,-292.7094 2713.0071,-283.5274 2608.707,-280.3885"/>
<polygon fill="#000000" stroke="#000000" points="2608.7955,-276.8897 2598.6971,-280.0947 2608.5901,-283.8866 2608.7955,-276.8897"/>
<text text-anchor="middle" x="3108.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3168.7967,-348.1841C3178.9479,-337.9955 3186.9479,-325.2455 3178.3431,-315 3142.3584,-272.154 2737.9942,-233.7997 2682.3431,-228 2490.9649,-208.0553 1904.4765,-196.6384 1698.1046,-193.1541"/>
<polygon fill="#000000" stroke="#000000" points="1698.0388,-189.6527 1687.9815,-192.9845 1697.9214,-196.6517 1698.0388,-189.6527"/>
<text text-anchor="middle" x="3211.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- radiology_file -->
<g id="node3" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1847.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1847.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1808.165,-263.6464C1770.1366,-248.7434 1712.3981,-226.1161 1672.0112,-210.2888"/>
<polygon fill="#000000" stroke="#000000" points="1673.2392,-207.011 1662.6515,-206.6209 1670.685,-213.5284 1673.2392,-207.011"/>
<text text-anchor="middle" x="1809.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2108.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2108.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2152.2213,-355.2247C2175.7545,-348.9062 2205.0373,-340.1704 2230.3431,-330 2243.8074,-324.5887 2245.3806,-318.9515 2259.3431,-315 2363.12,-285.6305 2395.658,-318.5139 2501.3431,-297 2504.9854,-296.2586 2508.7225,-295.3368 2512.4447,-294.3053"/>
<polygon fill="#000000" stroke="#000000" points="2513.6244,-297.6052 2522.1876,-291.3664 2511.6029,-290.9035 2513.6244,-297.6052"/>
<text text-anchor="middle" x="2303.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2092.3478,-348.5276C2087.7304,-342.8925 2082.9661,-336.4336 2079.3431,-330 2063.3386,-301.579 2074.5346,-286.6166 2054.3431,-261 2037.8607,-240.089 2029.4534,-236.8552 2004.3431,-228 1949.5951,-208.6929 1791.5273,-198.9316 1697.7123,-194.7066"/>
<polygon fill="#000000" stroke="#000000" points="1697.5856,-191.1977 1687.4414,-194.2545 1697.2778,-198.1909 1697.5856,-191.1977"/>
<text text-anchor="middle" x="2113.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node5" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1992.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1992.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1962.5426,-263.7844C1938.7219,-252.2541 1904.1662,-236.9205 1872.3431,-228 1814.0801,-211.668 1745.8927,-202.4422 1695.94,-197.4293"/>
<polygon fill="#000000" stroke="#000000" points="1696.1763,-193.9359 1685.8846,-196.4523 1695.4993,-200.903 1696.1763,-193.9359"/>
<text text-anchor="middle" x="1956.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="735.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="735.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2273.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2273.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2228.945,-263.5601C2193.2889,-251.8251 2141.6954,-236.3267 2095.3431,-228 2020.9448,-214.6351 1809.1792,-201.8127 1697.0394,-195.7092"/>
<polygon fill="#000000" stroke="#000000" points="1697.0098,-192.2026 1686.8354,-195.1574 1696.6318,-199.1924 1697.0098,-192.2026"/>
<text text-anchor="middle" x="2228.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2742.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2742.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2736.696,-347.836C2732.3236,-336.7293 2725.159,-323.1374 2714.3431,-315 2697.4587,-302.2968 2646.3707,-292.2226 2606.4152,-285.999"/>
<polygon fill="#000000" stroke="#000000" points="2606.9359,-282.538 2596.5244,-284.5004 2605.8873,-289.4591 2606.9359,-282.538"/>
<text text-anchor="middle" x="2792.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2966.1907,-203.2618C2991.2608,-212.4147 3016.5794,-226.4873 3001.3431,-243 2988.1945,-257.2502 2724.7632,-271.1247 2608.5879,-276.5769"/>
<polygon fill="#000000" stroke="#000000" points="2608.3087,-273.086 2598.4823,-277.0474 2608.6343,-280.0785 2608.3087,-273.086"/>
<text text-anchor="middle" x="3045.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2878.3906,-189.0634C2812.9877,-185.2118 2693.477,-178.4253 2591.3431,-174 2505.7654,-170.292 1127.6041,-159.9869 1050.3431,-123 1031.2984,-113.8828 1036.1842,-99.736 1019.3431,-87 991.5886,-66.0108 981.5735,-64.3252 948.3431,-54 892.3087,-36.5892 825.2072,-27.0134 781.4959,-22.1989"/>
<polygon fill="#000000" stroke="#000000" points="781.7658,-18.708 771.4519,-21.1312 781.0258,-25.6688 781.7658,-18.708"/>
<text text-anchor="middle" x="1090.8431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M92.7477,-87.2197C104.0608,-75.5131 120.5122,-61.0865 138.3431,-54 188.8992,-33.9075 556.7822,-22.5857 688.5505,-19.1401"/>
<polygon fill="#000000" stroke="#000000" points="688.819,-22.6344 698.7253,-18.8774 688.6383,-15.6367 688.819,-22.6344"/>
<text text-anchor="middle" x="200.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="259.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="259.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M260.8682,-86.7646C262.8345,-75.4817 267.2904,-61.7213 277.3431,-54 309.4372,-29.3492 578.501,-21.1577 688.6307,-18.8213"/>
<polygon fill="#000000" stroke="#000000" points="688.8529,-22.3176 698.779,-18.6131 688.7093,-15.3191 688.8529,-22.3176"/>
<text text-anchor="middle" x="346.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="427.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="427.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge19" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M420.9147,-86.8429C418.3389,-76.021 417.5641,-62.7347 425.3431,-54 442.5566,-34.6719 606.7775,-24.1408 688.9643,-20.0424"/>
<polygon fill="#000000" stroke="#000000" points="689.2237,-23.534 699.0416,-19.5516 688.8831,-16.5423 689.2237,-23.534"/>
<text text-anchor="middle" x="476.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2554.3431,-210.0034C2554.3431,-221.7801 2554.3431,-237.4102 2554.3431,-250.8156"/>
<polygon fill="#000000" stroke="#000000" points="2550.8432,-250.9735 2554.3431,-260.9735 2557.8432,-250.9736 2550.8432,-250.9735"/>
<text text-anchor="middle" x="2578.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2526.2424,-191.4343C2319.8732,-187.268 1046.0892,-161.3507 1027.3431,-156 999.5637,-148.0709 992.229,-142.9586 971.3431,-123 944.8736,-97.7056 956.7738,-74.3572 926.3431,-54 903.1048,-38.4543 829.9191,-27.9499 781.1868,-22.4741"/>
<polygon fill="#000000" stroke="#000000" points="781.5067,-18.9883 771.1858,-21.382 780.7467,-25.9469 781.5067,-18.9883"/>
<text text-anchor="middle" x="995.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- generic_file -->
<g id="node14" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="518.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="518.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M582.115,-361.4714C637.0206,-357.6425 718.3815,-352.1358 789.3431,-348 1081.6591,-330.9631 1154.6963,-324.8346 1447.3431,-315 1564.4052,-311.066 2385.948,-317.0743 2501.3431,-297 2505.056,-296.3541 2508.8602,-295.4908 2512.6429,-294.4908"/>
<polygon fill="#000000" stroke="#000000" points="2513.9241,-297.7622 2522.5282,-291.58 2511.9468,-291.0473 2513.9241,-297.7622"/>
<text text-anchor="middle" x="1500.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M512.7807,-347.8335C502.9729,-312.2394 486.2478,-231.7603 515.3431,-174 552.6233,-99.9912 643.5073,-53.7522 696.0593,-32.259"/>
<polygon fill="#000000" stroke="#000000" points="697.412,-35.4877 705.4043,-28.5327 694.8191,-28.9856 697.412,-35.4877"/>
<text text-anchor="middle" x="568.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M527.7693,-348.0031C541.2193,-324.1887 568.2262,-282.6956 603.3431,-261 661.4152,-225.1225 685.6485,-236.7749 753.3431,-228 907.0991,-208.0695 1372.2977,-196.998 1552.7286,-193.3585"/>
<polygon fill="#000000" stroke="#000000" points="1552.9822,-196.8542 1562.9102,-193.1549 1552.8422,-189.8556 1552.9822,-196.8542"/>
<text text-anchor="middle" x="656.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment -->
<g id="node15" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2434.3431" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2434.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2398.1762,-264.9182C2360.2393,-250.1957 2305.3964,-229.069 2300.3431,-228 2187.1269,-204.0492 1847.7432,-195.6353 1697.857,-193.0342"/>
<polygon fill="#000000" stroke="#000000" points="1697.8884,-189.5343 1687.8304,-192.864 1697.7695,-196.5333 1697.8884,-189.5343"/>
<text text-anchor="middle" x="2387.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node16" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="766.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="766.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M758.8708,-261.1436C755.5872,-250.1596 754.1051,-236.5889 762.3431,-228 775.9643,-213.7988 1347.7208,-198.6769 1552.9537,-193.6966"/>
<polygon fill="#000000" stroke="#000000" points="1553.1175,-197.1938 1563.0299,-193.4531 1552.9483,-190.1958 1553.1175,-197.1938"/>
<text text-anchor="middle" x="801.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- synonym -->
<g id="node17" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="850.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="850.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M902.2907,-364.1479C1054.6409,-358.6048 1493.5954,-341.8008 1557.3431,-330 1578.4878,-326.0858 1582.1406,-318.5878 1603.3431,-315 1800.1411,-281.6986 2304.7517,-331.4998 2501.3431,-297 2505.055,-296.3486 2508.8586,-295.4815 2512.6408,-294.479"/>
<polygon fill="#000000" stroke="#000000" points="2513.9238,-297.7497 2522.5254,-291.5641 2511.9438,-291.0356 2513.9238,-297.7497"/>
<text text-anchor="middle" x="1645.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M805.1244,-357.0671C767.0875,-347.6112 713.167,-329.4328 676.3431,-297 643.2031,-267.8117 639.3579,-252.7656 628.3431,-210 611.0601,-142.8974 672.1295,-74.3884 709.0941,-40.2291"/>
<polygon fill="#000000" stroke="#000000" points="711.5002,-42.7722 716.5792,-33.4741 706.8104,-37.5755 711.5002,-42.7722"/>
<text text-anchor="middle" x="670.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M845.8332,-347.7435C841.2645,-324.4116 837.6129,-284.2652 859.3431,-261 906.1372,-210.9005 1370.8137,-196.7772 1552.7938,-193.1504"/>
<polygon fill="#000000" stroke="#000000" points="1552.8772,-196.6495 1562.8072,-192.9557 1552.7411,-189.6508 1552.8772,-196.6495"/>
<text text-anchor="middle" x="901.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2919.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2919.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2905.1441,-348.276C2894.8407,-336.7534 2879.858,-322.521 2863.3431,-315 2819.216,-294.9041 2684.9792,-285.2883 2608.7439,-281.3374"/>
<polygon fill="#000000" stroke="#000000" points="2608.5502,-277.8233 2598.3871,-280.817 2608.1989,-284.8145 2608.5502,-277.8233"/>
<text text-anchor="middle" x="2946.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- consent_group -->
<g id="node24" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="842.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="842.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1562.9216,-191.4532C1381.757,-189.5629 867.1032,-181.9246 842.3431,-156 836.6673,-150.0572 835.107,-141.72 835.4241,-133.5057"/>
<polygon fill="#000000" stroke="#000000" points="838.9255,-133.7062 836.6614,-123.3561 831.9769,-132.8591 838.9255,-133.7062"/>
<text text-anchor="middle" x="892.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2302.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2302.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2324.1208,-348.3068C2339.2662,-336.9516 2360.4201,-322.9011 2381.3431,-315 2431.7957,-295.9477 2448.9352,-309.7221 2501.3431,-297 2504.7516,-296.1726 2508.2525,-295.2207 2511.752,-294.1958"/>
<polygon fill="#000000" stroke="#000000" points="2513.0214,-297.4665 2521.5328,-291.1572 2510.9446,-290.7817 2513.0214,-297.4665"/>
<text text-anchor="middle" x="2452.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_arm -->
<g id="node21" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1200.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1200.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1165.5454,-90.2531C1136.5756,-78.5901 1093.9709,-62.8458 1055.3431,-54 959.7825,-32.1165 844.9923,-23.3214 782.1535,-19.9518"/>
<polygon fill="#000000" stroke="#000000" points="781.9491,-16.4368 771.783,-19.42 781.5906,-23.4276 781.9491,-16.4368"/>
<text text-anchor="middle" x="1152.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2525.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2525.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2525.5198,-347.6095C2526.1033,-337.7026 2527.6271,-325.4116 2531.3431,-315 2532.5258,-311.6864 2534.0599,-308.3648 2535.7746,-305.1518"/>
<polygon fill="#000000" stroke="#000000" points="2538.829,-306.8632 2540.9434,-296.4815 2532.8164,-303.2787 2538.829,-306.8632"/>
<text text-anchor="middle" x="2622.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1417.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1417.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1498.7821,-354.0541C1584.7313,-341.9734 1724.253,-323.8573 1845.3431,-315 1990.7872,-304.3614 2357.7996,-322.7376 2501.3431,-297 2505.0526,-296.3349 2508.8544,-295.4582 2512.6356,-294.4493"/>
<polygon fill="#000000" stroke="#000000" points="2513.9228,-297.7185 2522.5184,-291.5245 2511.9362,-291.0063 2513.9228,-297.7185"/>
<text text-anchor="middle" x="1931.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1309.7766,-363.3152C1121.6184,-357.4988 748.8641,-340.5599 709.3431,-297 698.5921,-285.1503 708.4908,-276.9773 709.3431,-261 711.5415,-219.7904 725.412,-100.8948 731.9462,-46.1741"/>
<polygon fill="#000000" stroke="#000000" points="735.4354,-46.473 733.1496,-36.1277 728.485,-45.6404 735.4354,-46.473"/>
<text text-anchor="middle" x="803.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1414.4887,-347.8413C1411.9643,-324.9825 1411.3176,-285.7226 1431.3431,-261 1448.7458,-239.5155 1515.9499,-218.802 1566.4165,-205.772"/>
<polygon fill="#000000" stroke="#000000" points="1567.4361,-209.1243 1576.267,-203.2705 1565.7131,-202.3396 1567.4361,-209.1243"/>
<text text-anchor="middle" x="1517.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge34" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M820.9473,-87.6033C804.1291,-73.9288 780.5943,-54.793 762.457,-40.0458"/>
<polygon fill="#000000" stroke="#000000" points="764.5139,-37.2073 754.5469,-33.6143 760.0978,-42.6386 764.5139,-37.2073"/>
<text text-anchor="middle" x="858.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_response -->
<g id="node25" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1058.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1058.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1065.0339,-260.9351C1070.3157,-249.4185 1078.8911,-235.3277 1091.3431,-228 1130.0745,-205.2075 1415.2275,-196.3046 1552.24,-193.315"/>
<polygon fill="#000000" stroke="#000000" points="1552.7167,-196.8057 1562.6398,-193.0932 1552.5674,-189.8073 1552.7167,-196.8057"/>
<text text-anchor="middle" x="1174.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- family_relationship -->
<g id="node26" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1281.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1281.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1267.9328,-261.0875C1261.6346,-250.3577 1257.1239,-237.0822 1265.3431,-228 1284.2398,-207.1194 1453.3377,-197.8269 1552.9159,-194.134"/>
<polygon fill="#000000" stroke="#000000" points="1553.0533,-197.6314 1562.9206,-193.773 1552.8009,-190.6359 1553.0533,-197.6314"/>
<text text-anchor="middle" x="1344.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- laboratory_test -->
<g id="node27" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1890.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1890.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1937.8539,-351.3117C1979.0626,-339.2659 2040.5374,-322.9508 2095.3431,-315 2274.0936,-289.0681 2323.8319,-330.3762 2501.3431,-297 2504.9961,-296.3132 2508.7407,-295.4297 2512.4679,-294.4238"/>
<polygon fill="#000000" stroke="#000000" points="2513.6303,-297.7297 2522.2188,-291.5257 2511.636,-291.0198 2513.6303,-297.7297"/>
<text text-anchor="middle" x="2160.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1884.5535,-347.7736C1879.9118,-336.3426 1872.1851,-322.4124 1860.3431,-315 1817.638,-288.2691 1670.0753,-332.5174 1634.3431,-297 1614.5621,-277.3378 1615.148,-243.8604 1618.8589,-219.9929"/>
<polygon fill="#000000" stroke="#000000" points="1622.3115,-220.569 1620.6558,-210.1043 1615.4243,-219.3174 1622.3115,-220.569"/>
<text text-anchor="middle" x="1699.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_admin -->
<g id="node28" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1348.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1348.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1312.9671,-89.3979C1284.4851,-77.5723 1243.1132,-62.0312 1205.3431,-54 1125.3424,-36.9891 883.7349,-24.595 781.6589,-19.9789"/>
<polygon fill="#000000" stroke="#000000" points="781.7944,-16.4815 771.6479,-19.5309 781.4815,-23.4745 781.7944,-16.4815"/>
<text text-anchor="middle" x="1314.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
</g>
</svg>
</div>
