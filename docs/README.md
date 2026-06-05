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
<svg width="3172pt" height="479pt"
 viewBox="0.00 0.00 3172.04 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3168.0444,-475 3168.0444,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1755" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1755" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1449" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1449" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1700.6459,-263.5464C1645.0748,-247.7468 1559.2369,-223.3419 1503.5829,-207.5187"/>
<polygon fill="#000000" stroke="#000000" points="1504.4737,-204.1333 1493.8978,-204.765 1502.5594,-210.8665 1504.4737,-204.1333"/>
<text text-anchor="middle" x="1703" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- generic_file -->
<g id="node2" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="223" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="223" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M218.3673,-434.7737C209.9355,-396.8782 196.8461,-309.1192 242,-261 275.8987,-224.8752 305.086,-258.9123 352,-243 365.3696,-238.4653 366.3668,-231.6667 380,-228 475.4238,-202.3354 1151.1915,-194.4613 1376.2697,-192.5361"/>
<polygon fill="#000000" stroke="#000000" points="1376.3543,-196.0356 1386.3245,-192.4515 1376.2953,-189.0358 1376.3543,-196.0356"/>
<text text-anchor="middle" x="268" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample -->
<g id="node24" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1559" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1559" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M281.1485,-444.5057C362.7099,-432.9342 515.815,-412.4619 647,-402 971.7633,-376.1005 1363.1395,-368.5816 1504.6441,-366.625"/>
<polygon fill="#000000" stroke="#000000" points="1504.8412,-370.1227 1514.7931,-366.4883 1504.7469,-363.1234 1504.8412,-370.1227"/>
<text text-anchor="middle" x="700" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study -->
<g id="node30" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2268" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2268" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M168.4481,-442.9496C102.4292,-429.1971 0,-402.051 0,-366 0,-366 0,-366 0,-105 0,-73.7496 41.3086,-65.7777 97,-54 204.4084,-31.2851 1914.5372,-20.0976 2221.1276,-18.2698"/>
<polygon fill="#000000" stroke="#000000" points="2221.4579,-21.768 2231.4369,-18.2087 2221.4163,-14.7681 2221.4579,-21.768"/>
<text text-anchor="middle" x="53" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_personnel -->
<g id="node3" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="115" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="115" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M104.8535,-86.6507C100.331,-75.7565 97.6781,-62.4616 106,-54 125.2052,-34.4723 1907.629,-20.6202 2221.1701,-18.3336"/>
<polygon fill="#000000" stroke="#000000" points="2221.3063,-21.8328 2231.2805,-18.2602 2221.2554,-14.833 2221.3063,-21.8328"/>
<text text-anchor="middle" x="175.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="813" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="813" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M807.4723,-435.0215C799.6975,-405.7274 789.6324,-347.6915 820,-315 841.9482,-291.3721 934.0987,-309.0794 964,-297 988.7253,-287.0116 989.8707,-275.8797 1012,-261 1035.6564,-245.0935 1039.9152,-236.8913 1067,-228 1122.722,-209.7078 1282.5168,-199.5475 1376.8534,-194.9866"/>
<polygon fill="#000000" stroke="#000000" points="1377.0737,-198.4802 1386.8966,-194.5102 1376.742,-191.488 1377.0737,-198.4802"/>
<text text-anchor="middle" x="906" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M898.1841,-441.7703C942.5418,-435.0961 991.6763,-426.1646 1012,-417 1021.8078,-412.5773 1020.9622,-405.8723 1031,-402 1074.3045,-385.2943 1378.2145,-372.5316 1504.34,-367.8957"/>
<polygon fill="#000000" stroke="#000000" points="1504.6799,-371.3857 1514.5459,-367.5241 1504.4251,-364.3904 1504.6799,-371.3857"/>
<text text-anchor="middle" x="1117" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M720.4102,-443.5444C633.3022,-434.5026 513.028,-421.5868 491,-417 362.5919,-390.2621 304.6341,-419.7645 209,-330 174.2593,-297.3916 144.2208,-263.5008 176,-228 317.361,-70.0845 1924.1369,-25.8554 2220.9924,-19.0092"/>
<polygon fill="#000000" stroke="#000000" points="2221.4748,-22.4992 2231.3925,-18.7723 2221.3154,-15.501 2221.4748,-22.4992"/>
<text text-anchor="middle" x="262" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2120" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2120" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2187.2964,-442.727C2216.206,-436.8081 2245.3518,-428.2783 2254,-417 2258.0567,-411.7096 2258.1049,-407.253 2254,-402 2213.2475,-349.849 2013.2845,-375.267 1965,-330 1941.5179,-307.9854 1963.3578,-285.9321 1943,-261 1923.9973,-237.7274 1912.7362,-236.7719 1884,-228 1818.2421,-207.927 1627.1508,-198.223 1521.4416,-194.2736"/>
<polygon fill="#000000" stroke="#000000" points="1521.2945,-190.766 1511.1732,-193.8981 1521.0385,-197.7613 1521.2945,-190.766"/>
<text text-anchor="middle" x="2030.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2070.1061,-438.692C2052.326,-432.8689 2032.4044,-425.4955 2015,-417 2004.0328,-411.6467 2003.5438,-405.9595 1992,-402 1923.431,-378.4808 1713.756,-369.985 1613.5023,-367.2111"/>
<polygon fill="#000000" stroke="#000000" points="1613.3708,-363.7064 1603.2808,-366.9377 1613.1836,-370.7039 1613.3708,-363.7064"/>
<text text-anchor="middle" x="2080.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2113" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2113" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2086.9223,-261.7681C2067.6398,-249.9963 2040.2759,-235.2625 2014,-228 1923.4903,-202.9836 1653.3323,-195.2556 1522.1234,-192.9449"/>
<polygon fill="#000000" stroke="#000000" points="1521.8337,-189.4395 1511.7756,-192.7688 1521.7145,-196.4385 1521.8337,-189.4395"/>
<text text-anchor="middle" x="2118" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_other -->
<g id="node7" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2303" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2303" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2267.2151,-262.4613C2235.6771,-247.9465 2194.1067,-228.9887 2190,-228 2126.2725,-212.6578 1695.3367,-198.9516 1521.4938,-193.981"/>
<polygon fill="#000000" stroke="#000000" points="1521.5113,-190.4801 1511.4158,-193.6944 1521.3122,-197.4773 1521.5113,-190.4801"/>
<text text-anchor="middle" x="2292.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- radiology_file -->
<g id="node8" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2482" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2482" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2437.6389,-264.4374C2421.3785,-258.5189 2403.0391,-251.1486 2387,-243 2376.1196,-237.4723 2375.6275,-231.7068 2364,-228 2284.8156,-202.7561 1724.4638,-194.7324 1521.8653,-192.6401"/>
<polygon fill="#000000" stroke="#000000" points="1521.6615,-189.1379 1511.6265,-192.5362 1521.5904,-196.1375 1521.6615,-189.1379"/>
<text text-anchor="middle" x="2446" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_status -->
<g id="node9" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1723" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1723" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1733.2349,-87.0978C1740.9191,-75.4957 1752.5783,-61.2414 1767,-54 1806.9988,-33.9159 2105.0613,-22.8919 2221.5447,-19.3133"/>
<polygon fill="#000000" stroke="#000000" points="2221.6937,-22.8105 2231.5832,-19.0096 2221.4819,-15.8137 2221.6937,-22.8105"/>
<text text-anchor="middle" x="1823.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- pdx -->
<g id="node10" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1906" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1906" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1884.5314,-266.9937C1861.8083,-254.9092 1824.5272,-236.8323 1790,-228 1740.5373,-215.3471 1604.2694,-203.488 1519.726,-197.0394"/>
<polygon fill="#000000" stroke="#000000" points="1519.917,-193.5439 1509.6816,-196.2801 1519.3893,-200.524 1519.917,-193.5439"/>
<text text-anchor="middle" x="1856" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge40" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1924.7004,-265.5171C1983.8284,-222.8861 2167.0537,-90.7817 2238.7829,-39.0654"/>
<polygon fill="#000000" stroke="#000000" points="2240.8972,-41.8559 2246.9618,-33.1684 2236.8033,-36.1778 2240.8972,-41.8559"/>
<text text-anchor="middle" x="2119" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="351" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="351" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M362.7725,-260.8846C371.4971,-249.1874 384.5271,-234.907 400,-228 444.4525,-208.1567 1145.7682,-196.3552 1376.2344,-192.9979"/>
<polygon fill="#000000" stroke="#000000" points="1376.5747,-196.4935 1386.523,-192.8491 1376.4734,-189.4942 1376.5747,-196.4935"/>
<text text-anchor="middle" x="479.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node12" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1320" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1320" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1328.5971,-434.8451C1334.8813,-423.5952 1344.4863,-409.8414 1357,-402 1381.145,-386.8701 1453.9979,-376.5913 1505.2528,-371.0091"/>
<polygon fill="#000000" stroke="#000000" points="1505.94,-374.456 1515.5157,-369.9222 1505.2027,-367.4949 1505.94,-374.456"/>
<text text-anchor="middle" x="1448.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- synonym -->
<g id="node13" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2293" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2293" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2287.3106,-434.9952C2276.4299,-403.9862 2249.4354,-341.3032 2202,-315 2130.5269,-275.3678 2095.8713,-324.7472 2019,-297 1967.5194,-278.4177 1968.6754,-246.0337 1917,-228 1846.1202,-203.2644 1634.8457,-195.4863 1521.9813,-193.0694"/>
<polygon fill="#000000" stroke="#000000" points="1521.7757,-189.5645 1511.7059,-192.8584 1521.6319,-196.5631 1521.7757,-189.5645"/>
<text text-anchor="middle" x="2264.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2256.7752,-439.8536C2216.9559,-425.4951 2157.1247,-404.2273 2146,-402 2045.0932,-381.7973 1739.1309,-371.0893 1613.6157,-367.4498"/>
<polygon fill="#000000" stroke="#000000" points="1613.5624,-363.947 1603.4664,-367.1596 1613.3623,-370.9441 1613.5624,-363.947"/>
<text text-anchor="middle" x="2231.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2342.9062,-447.5184C2451.5869,-434.9066 2700,-402.128 2700,-366 2700,-366 2700,-366 2700,-105 2700,-77.7581 2689.4145,-67.9242 2666,-54 2636.4053,-36.4005 2413.3795,-24.4484 2314.7133,-19.9681"/>
<polygon fill="#000000" stroke="#000000" points="2314.5851,-16.459 2304.4386,-19.5082 2314.2721,-23.452 2314.5851,-16.459"/>
<text text-anchor="middle" x="2742.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1714" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1714" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1706.3724,-435.055C1700.8314,-424.0357 1692.3205,-410.4588 1681,-402 1660.89,-386.9735 1634.5834,-378.1936 1611.5488,-373.0755"/>
<polygon fill="#000000" stroke="#000000" points="1612.0667,-369.6091 1601.5684,-371.0356 1610.6649,-376.4673 1612.0667,-369.6091"/>
<text text-anchor="middle" x="1755" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- treatment_radiation -->
<g id="node15" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="612" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="612" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M611.9318,-260.77C612.9464,-249.4893 616.3097,-235.7293 626,-228 655.0738,-204.8096 1180.3504,-195.5366 1376.1939,-192.8757"/>
<polygon fill="#000000" stroke="#000000" points="1376.4331,-196.3729 1386.3853,-192.7391 1376.3392,-189.3735 1376.4331,-196.3729"/>
<text text-anchor="middle" x="709" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- consent_group -->
<g id="node16" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1890" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1890" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge22" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1884.8826,-86.7286C1883.0349,-75.8638 1883.0524,-62.5724 1891,-54 1913.0772,-30.1874 2125.5846,-21.6885 2221.4704,-19.049"/>
<polygon fill="#000000" stroke="#000000" points="2221.5689,-22.5477 2231.4724,-18.7833 2221.383,-15.5502 2221.5689,-22.5477"/>
<text text-anchor="middle" x="1954.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- cytogenomic_file -->
<g id="node17" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1898" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1898" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1873.6772,-435.4027C1855.2031,-422.3652 1831.1376,-406.1677 1820,-402 1783.0458,-388.1717 1677.3653,-376.6319 1612.3718,-370.5763"/>
<polygon fill="#000000" stroke="#000000" points="1612.5851,-367.0813 1602.3069,-369.652 1611.9449,-374.0519 1612.5851,-367.0813"/>
<text text-anchor="middle" x="1916.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="788" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="788" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M790.1572,-260.8871C792.5329,-249.5041 797.5226,-235.5846 808,-228 830.6941,-211.5718 1213.2279,-198.7402 1376.2997,-193.9911"/>
<polygon fill="#000000" stroke="#000000" points="1376.8228,-197.4775 1386.7175,-193.69 1376.6205,-190.4805 1376.8228,-197.4775"/>
<text text-anchor="middle" x="851.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- genetic_analysis -->
<g id="node19" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="533" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="533" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M521.5685,-435.0596C499.8428,-398.4538 458.163,-314.1348 498,-261 498.2452,-260.673 610.5967,-228.0665 611,-228 757.242,-203.869 1200.7986,-195.3517 1376.35,-192.875"/>
<polygon fill="#000000" stroke="#000000" points="1376.5671,-196.3725 1386.5176,-192.7341 1376.47,-189.3731 1376.5671,-196.3725"/>
<text text-anchor="middle" x="552" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M598.8597,-441.0001C666.2369,-429.1893 774.0647,-411.5735 868,-402 1104.3657,-377.9106 1387.9532,-369.5555 1504.7148,-367.0012"/>
<polygon fill="#000000" stroke="#000000" points="1504.902,-370.4981 1514.8251,-366.7855 1504.7526,-363.4997 1504.902,-370.4981"/>
<text text-anchor="middle" x="938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- survival -->
<g id="node20" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="907" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="907" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M900.9011,-260.7023C898.5277,-249.8275 898.0122,-236.5349 906,-228 921.8401,-211.0749 1232.6255,-198.9398 1376.7425,-194.1996"/>
<polygon fill="#000000" stroke="#000000" points="1376.9438,-197.695 1386.8245,-193.8711 1376.7158,-190.6987 1376.9438,-197.695"/>
<text text-anchor="middle" x="945.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1058" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1058" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1007.6396,-445.8458C948.2874,-437.1726 857.022,-422.9757 852,-417 847.7109,-411.8963 848.4951,-407.671 852,-402 889.6183,-341.1324 942.8417,-377.8977 996,-330 1023.0205,-305.6534 1010.7815,-282.6598 1040,-261 1083.7473,-228.57 1104.6061,-238.7062 1158,-228 1232.6669,-213.0282 1319.4384,-203.2611 1378.6709,-197.7284"/>
<polygon fill="#000000" stroke="#000000" points="1379.0287,-201.2103 1388.6667,-196.8105 1378.3886,-194.2397 1379.0287,-201.2103"/>
<text text-anchor="middle" x="1052.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1104.3713,-443.3231C1133.9769,-436.7704 1173.0375,-427.4285 1207,-417 1225.1503,-411.4268 1228.5433,-406.4546 1247,-402 1335.7444,-380.5813 1441.8632,-371.7804 1504.6702,-368.2544"/>
<polygon fill="#000000" stroke="#000000" points="1504.9486,-371.7446 1514.7465,-367.7133 1504.5731,-364.7547 1504.9486,-371.7446"/>
<text text-anchor="middle" x="1291.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2602" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2602" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2579.3887,-87.7954C2563.1686,-76.3529 2540.3224,-62.0053 2518,-54 2481.4196,-40.8814 2375.6501,-28.6712 2314.0358,-22.4002"/>
<polygon fill="#000000" stroke="#000000" points="2314.1075,-18.8898 2303.8077,-21.3724 2313.4076,-25.8547 2314.1075,-18.8898"/>
<text text-anchor="middle" x="2605.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge37" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1501.0638,-181.9706C1569.9511,-168.6665 1695.1504,-144.3702 1802,-123 1808.1213,-121.7757 1814.48,-120.4942 1820.8521,-119.2033"/>
<polygon fill="#000000" stroke="#000000" points="1821.7412,-122.5942 1830.8444,-117.1738 1820.3479,-115.7343 1821.7412,-122.5942"/>
<text text-anchor="middle" x="1755.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge44" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1600.7231,-359.8972C1661.0663,-350.362 1775.691,-329.5764 1869,-297 1870.9221,-296.3289 1872.8748,-295.5842 1874.8275,-294.7905"/>
<polygon fill="#000000" stroke="#000000" points="1876.7232,-297.7789 1884.4488,-290.5286 1873.8881,-291.3787 1876.7232,-297.7789"/>
<text text-anchor="middle" x="1847.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1562.7189,-347.721C1567.4461,-319.0333 1572.0465,-263.0974 1545,-228 1539.4079,-220.7433 1522.7912,-213.5018 1504.9202,-207.4366"/>
<polygon fill="#000000" stroke="#000000" points="1505.5168,-203.9507 1494.9248,-204.1954 1503.3576,-210.6093 1505.5168,-203.9507"/>
<text text-anchor="middle" x="1602.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node25" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2623" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2623" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge42" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1603.3831,-365.3753C1715.3425,-363.4275 2006.9465,-355.9433 2100,-330 2113.9779,-326.103 2114.9743,-318.7214 2129,-315 2222.5138,-290.1883 2468.6247,-313.2477 2564,-297 2568.3944,-296.2514 2572.9196,-295.2703 2577.4168,-294.1522"/>
<polygon fill="#000000" stroke="#000000" points="2578.4141,-297.5084 2587.156,-291.5226 2576.5893,-290.7504 2578.4141,-297.5084"/>
<text text-anchor="middle" x="2165.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2585.6638,-266.9522C2567.8222,-260.6698 2546.3977,-252.3469 2528,-243 2517.1196,-237.4723 2516.6371,-231.6763 2505,-228 2412.0735,-198.6434 1745.7922,-193.2183 1522.0537,-192.2222"/>
<polygon fill="#000000" stroke="#000000" points="1521.753,-188.721 1511.738,-192.178 1521.7229,-195.7209 1521.753,-188.721"/>
<text text-anchor="middle" x="2568.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2621.2877,-260.5523C2619.5503,-250.1531 2616.0503,-237.4031 2609,-228 2529.5294,-122.0085 2379.4544,-57.4607 2307.8993,-31.3801"/>
<polygon fill="#000000" stroke="#000000" points="2308.9337,-28.033 2298.3392,-27.955 2306.5728,-34.6228 2308.9337,-28.033"/>
<text text-anchor="middle" x="2575.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_surgery -->
<g id="node26" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1148" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1148" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1153.2151,-260.9998C1157.4679,-249.6644 1164.6616,-235.7555 1176,-228 1207.6855,-206.327 1307.0593,-197.6787 1376.7224,-194.2427"/>
<polygon fill="#000000" stroke="#000000" points="1376.9479,-197.7361 1386.7734,-193.7727 1376.6208,-190.7438 1376.9479,-197.7361"/>
<text text-anchor="middle" x="1254.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- sequencing_file -->
<g id="node27" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1537" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1537" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1540.5024,-434.975C1542.5033,-425.1752 1545.1724,-412.8699 1548,-402 1548.7008,-399.306 1549.4729,-396.512 1550.2732,-393.7256"/>
<polygon fill="#000000" stroke="#000000" points="1553.7112,-394.4442 1553.2181,-383.8608 1547.0037,-392.4417 1553.7112,-394.4442"/>
<text text-anchor="middle" x="1614.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node28" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2788" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2788" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge38" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2769.1647,-87.8379C2755.0696,-76.1 2734.7259,-61.3779 2714,-54 2641.4473,-28.173 2413.7383,-20.7574 2314.7364,-18.7263"/>
<polygon fill="#000000" stroke="#000000" points="2314.5073,-15.2212 2304.4408,-18.5251 2314.3704,-22.2199 2314.5073,-15.2212"/>
<text text-anchor="middle" x="2790.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node29" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1394" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1394" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1357.4328,-261.6376C1343.1257,-252.414 1332.0402,-240.4311 1341,-228 1347.2635,-219.3099 1367.5864,-211.5246 1388.9394,-205.4358"/>
<polygon fill="#000000" stroke="#000000" points="1390.0449,-208.7623 1398.7758,-202.7605 1388.2078,-202.0077 1390.0449,-208.7623"/>
<text text-anchor="middle" x="1443" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_funding -->
<g id="node31" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2943" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2943" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2917.0501,-88.0117C2897.541,-76.1961 2869.6927,-61.3033 2843,-54 2743.8487,-26.8714 2433.2304,-20.0985 2314.6456,-18.4826"/>
<polygon fill="#000000" stroke="#000000" points="2314.4891,-14.9804 2304.4445,-18.3499 2314.3981,-21.9798 2314.4891,-14.9804"/>
<text text-anchor="middle" x="2942" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node32" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3101" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3101" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge34" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3077.4494,-88.1431C3059.3909,-76.2283 3033.3422,-61.1532 3008,-54 2941.6637,-35.2756 2467.5926,-22.6679 2315.11,-19.0615"/>
<polygon fill="#000000" stroke="#000000" points="2314.7763,-15.5529 2304.697,-18.8175 2314.6122,-22.5509 2314.7763,-15.5529"/>
<text text-anchor="middle" x="3093" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
</g>
</svg>
</div>
