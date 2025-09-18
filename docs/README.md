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
<svg width="3016pt" height="392pt"
 viewBox="0.00 0.00 3015.64 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3011.6396,-388 3011.6396,4 -4,4"/>
<!-- cytogenomic_file -->
<g id="node1" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1920.5952" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1920.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1860.5952" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1860.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1897.5744,-348.5689C1891.4668,-343.1242 1885.2771,-336.7583 1880.5952,-330 1875.7208,-322.9639 1871.8018,-314.5716 1868.7688,-306.6464"/>
<polygon fill="#000000" stroke="#000000" points="1871.999,-305.2802 1865.3958,-296.9948 1865.391,-307.5896 1871.999,-305.2802"/>
<text text-anchor="middle" x="1952.0952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2079.5952" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2079.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node24" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2327.5952" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2327.5952" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2074.6288,-86.8653C2072.838,-76.0519 2072.8622,-62.7665 2080.5952,-54 2093.6833,-39.1625 2213.7985,-27.1738 2281.5783,-21.5203"/>
<polygon fill="#000000" stroke="#000000" points="2281.9009,-25.0057 2291.5814,-20.7001 2281.3288,-18.0291 2281.9009,-25.0057"/>
<text text-anchor="middle" x="2142.5952" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1209.5952" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1209.5952" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node6" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1570.5952" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1570.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge24" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1257.5332,-180.4471C1321.4627,-165.0402 1434.8376,-137.7172 1506.1829,-120.5232"/>
<polygon fill="#000000" stroke="#000000" points="1507.06,-123.9121 1515.9616,-118.1665 1505.4199,-117.1069 1507.06,-123.9121"/>
<text text-anchor="middle" x="1463.0952" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1309.5952" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1309.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1333.6095,-348.6081C1351.4223,-336.7588 1376.8147,-321.9982 1401.5952,-315 1488.5067,-290.4555 1718.8396,-313.6881 1807.5952,-297 1811.2481,-296.3132 1814.9927,-295.4297 1818.7199,-294.4238"/>
<polygon fill="#000000" stroke="#000000" points="1819.8824,-297.7297 1828.4708,-291.5257 1817.888,-291.0198 1819.8824,-297.7297"/>
<text text-anchor="middle" x="1468.0952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- genetic_analysis -->
<g id="node5" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1070.5952" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1070.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1047.1412,-348.4447C1036.2878,-338.2248 1027.5841,-325.3557 1036.5952,-315 1074.5952,-271.3295 1117.8557,-329.7423 1165.5952,-297 1190.8393,-279.6862 1201.6431,-244.8913 1206.2394,-220.1036"/>
<polygon fill="#000000" stroke="#000000" points="1209.7037,-220.6051 1207.8532,-210.1731 1202.7944,-219.4822 1209.7037,-220.6051"/>
<text text-anchor="middle" x="1263.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1121.9164,-351.3749C1142.4831,-345.2118 1166.3078,-337.6897 1187.5952,-330 1203.8975,-324.1111 1206.6528,-318.6608 1223.5952,-315 1350.5058,-287.578 1679.8327,-320.1309 1807.5952,-297 1811.3035,-296.3286 1815.1045,-295.4476 1818.8852,-294.4358"/>
<polygon fill="#000000" stroke="#000000" points="1820.1743,-297.7043 1828.7672,-291.5064 1818.1848,-290.9929 1820.1743,-297.7043"/>
<text text-anchor="middle" x="1293.5952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge1" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1621.5528,-91.0667C1666.8811,-79.2459 1735.1568,-62.8399 1795.5952,-54 1973.5359,-27.9739 2187.7657,-20.7169 2280.7441,-18.7304"/>
<polygon fill="#000000" stroke="#000000" points="2281.0179,-22.2256 2290.9448,-18.5234 2280.8759,-15.2271 2281.0179,-22.2256"/>
<text text-anchor="middle" x="1859.0952" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_response -->
<g id="node7" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="887.5952" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="887.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M888.4745,-260.9468C890.027,-249.7386 893.9489,-235.9931 903.5952,-228 921.307,-213.3236 1053.3633,-202.117 1138.1106,-196.3433"/>
<polygon fill="#000000" stroke="#000000" points="1138.4571,-199.828 1148.2003,-195.6662 1137.9883,-192.8437 1138.4571,-199.828"/>
<text text-anchor="middle" x="986.5952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- radiology_file -->
<g id="node8" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1083.5952" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1083.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1075.5529,-260.7913C1072.2174,-250.2181 1070.5602,-237.2105 1077.5952,-228 1086.1721,-216.7707 1115.2864,-208.2034 1143.9967,-202.2492"/>
<polygon fill="#000000" stroke="#000000" points="1144.9692,-205.6248 1154.1007,-200.252 1143.6118,-198.7576 1144.9692,-205.6248"/>
<text text-anchor="middle" x="1136.5952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="54.5952" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="54.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M54.4417,-347.7329C55.2677,-324.3896 60.2895,-284.2308 83.5952,-261 123.0741,-221.648 149.4878,-236.3867 204.5952,-228 384.4283,-200.6316 937.3669,-193.9656 1136.8672,-192.4326"/>
<polygon fill="#000000" stroke="#000000" points="1136.9754,-195.932 1146.949,-192.3572 1136.923,-188.9322 1136.9754,-195.932"/>
<text text-anchor="middle" x="128.0952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M93.9714,-353.4699C101.7374,-351.3628 109.8734,-349.4068 117.5952,-348 293.5242,-315.9491 339.9767,-323.5868 518.5952,-315 661.6661,-308.1221 1666.4403,-321.3293 1807.5952,-297 1811.309,-296.3599 1815.1139,-295.5006 1818.8971,-294.5033"/>
<polygon fill="#000000" stroke="#000000" points="1820.1765,-297.7754 1828.7831,-291.5966 1818.2019,-291.0596 1820.1765,-297.7754"/>
<text text-anchor="middle" x="563.0952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1526.5952" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1526.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1530.2334,-347.8441C1533.5274,-336.4429 1539.6146,-322.5193 1550.5952,-315 1597.8323,-282.6529 1751.4702,-308.299 1807.5952,-297 1811.239,-296.2664 1814.9772,-295.3502 1818.7002,-294.3223"/>
<polygon fill="#000000" stroke="#000000" points="1819.8774,-297.6232 1828.4443,-291.3894 1817.8598,-290.9202 1819.8774,-297.6232"/>
<text text-anchor="middle" x="1642.0952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment -->
<g id="node11" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1408.5952" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1408.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1374.8375,-264.2416C1341.4493,-249.6448 1290.1847,-227.2326 1253.6156,-211.2451"/>
<polygon fill="#000000" stroke="#000000" points="1254.7519,-207.9221 1244.1873,-207.1232 1251.9479,-214.3359 1254.7519,-207.9221"/>
<text text-anchor="middle" x="1368.5952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node12" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1532.5952" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1532.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1505.038,-264.1698C1482.6189,-252.6977 1449.8508,-237.2554 1419.5952,-228 1373.5195,-213.9051 1319.9629,-204.8334 1278.4675,-199.3222"/>
<polygon fill="#000000" stroke="#000000" points="1278.826,-195.8395 1268.4603,-198.0307 1277.9301,-202.7819 1278.826,-195.8395"/>
<text text-anchor="middle" x="1498.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2453.5952" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2453.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2429.5989,-88.4312C2409.0497,-74.2424 2379.3729,-53.7513 2357.3226,-38.5261"/>
<polygon fill="#000000" stroke="#000000" points="2359.2015,-35.5702 2348.9838,-32.7684 2355.2241,-41.3305 2359.2015,-35.5702"/>
<text text-anchor="middle" x="2446.0952" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- generic_file -->
<g id="node14" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="192.5952" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="192.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M185.3117,-348.0372C177.2993,-325.0231 168.0781,-285.2196 188.5952,-261 246.2607,-192.928 297.8673,-237.2998 386.5952,-228 531.1119,-212.8528 964.739,-199.0701 1137.4558,-194.0293"/>
<polygon fill="#000000" stroke="#000000" points="1137.5685,-197.5276 1147.4626,-193.7385 1137.3651,-190.5306 1137.5685,-197.5276"/>
<text text-anchor="middle" x="241.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M254.4521,-359.9202C370.0436,-348.8338 626.7516,-325.509 843.5952,-315 950.5993,-309.8142 1702.0652,-315.4448 1807.5952,-297 1811.3075,-296.3511 1815.1113,-295.4858 1818.8938,-294.4845"/>
<polygon fill="#000000" stroke="#000000" points="1820.176,-297.7555 1828.7787,-291.5714 1818.1972,-291.041 1820.176,-297.7555"/>
<text text-anchor="middle" x="896.5952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M144.7317,-353.4493C90.2133,-337.7126 8.5952,-309.1233 8.5952,-279 8.5952,-279 8.5952,-279 8.5952,-105 8.5952,-45.9634 1953.6708,-22.0907 2281.0801,-18.4905"/>
<polygon fill="#000000" stroke="#000000" points="2281.208,-21.9894 2291.1692,-18.3804 2281.1316,-14.9898 2281.208,-21.9894"/>
<text text-anchor="middle" x="61.5952" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- medical_history -->
<g id="node15" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="388.5952" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="388.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M387.3836,-260.878C387.7055,-249.6416 390.2536,-235.8905 399.5952,-228 427.5087,-204.4223 943.1139,-195.4078 1136.8424,-192.844"/>
<polygon fill="#000000" stroke="#000000" points="1136.9741,-196.3427 1146.9276,-192.7126 1136.8828,-189.3433 1136.9741,-196.3427"/>
<text text-anchor="middle" x="467.5952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node16" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1736.5952" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1736.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1735.3046,-347.9116C1735.5227,-337.1156 1737.6678,-323.8323 1745.5952,-315 1764.761,-293.6463 1780.2259,-305.6158 1807.5952,-297 1810.7003,-296.0225 1813.9004,-294.9926 1817.1173,-293.9407"/>
<polygon fill="#000000" stroke="#000000" points="1818.3506,-297.2193 1826.7409,-290.7498 1816.1475,-290.575 1818.3506,-297.2193"/>
<text text-anchor="middle" x="1806.5952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2198.5952" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2198.5952" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2186.2926,-209.6775C2177.2606,-221.1794 2163.9291,-235.4061 2148.5952,-243 2138.2236,-248.1363 1994.3637,-264.4464 1913.9876,-273.2435"/>
<polygon fill="#000000" stroke="#000000" points="1913.1243,-269.8169 1903.5632,-274.3813 1913.8839,-276.7755 1913.1243,-269.8169"/>
<text text-anchor="middle" x="2209.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge33" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2200.9851,-173.7296C2204.6433,-151.4574 2213.3475,-113.516 2232.5952,-87 2248.1714,-65.5418 2272.446,-48.0755 2292.5578,-36.0846"/>
<polygon fill="#000000" stroke="#000000" points="2294.5351,-38.985 2301.4592,-30.9658 2291.0455,-32.9168 2294.5351,-38.985"/>
<text text-anchor="middle" x="2273.0952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="774.5952" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="774.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M728.368,-350.9268C678.3643,-332.2643 609.895,-298.3396 642.5952,-261 674.7345,-224.3007 992.4719,-203.2521 1137.7616,-195.4774"/>
<polygon fill="#000000" stroke="#000000" points="1138.1169,-198.9636 1147.9181,-194.9406 1137.7473,-191.9734 1138.1169,-198.9636"/>
<text text-anchor="middle" x="708.0952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M831.1873,-352.9094C887.0972,-340.6199 975.2296,-322.9685 1052.5952,-315 1219.5374,-297.8053 1642.3511,-326.322 1807.5952,-297 1811.3058,-296.3416 1815.1085,-295.4695 1818.8902,-294.4637"/>
<polygon fill="#000000" stroke="#000000" points="1820.1753,-297.7337 1828.7739,-291.5438 1818.1919,-291.0205 1820.1753,-297.7337"/>
<text text-anchor="middle" x="1118.0952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1834.0365,-264.3567C1808.9373,-250.7952 1772.9144,-232.1192 1757.5952,-228 1670.0785,-204.4676 1410.3538,-196.0332 1282.4389,-193.2503"/>
<polygon fill="#000000" stroke="#000000" points="1282.4146,-189.7491 1272.3427,-193.0364 1282.2663,-196.7475 1282.4146,-189.7491"/>
<text text-anchor="middle" x="1827.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1899.8245,-270.4763C1931.4456,-263.4785 1977.0066,-253.1089 2016.5952,-243 2062.077,-231.3863 2113.5583,-216.8272 2150.1325,-206.2408"/>
<polygon fill="#000000" stroke="#000000" points="2151.4079,-209.5152 2160.0356,-203.366 2149.4563,-202.7927 2151.4079,-209.5152"/>
<text text-anchor="middle" x="2108.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node27" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1936.5952" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1936.5952" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1898.5105,-269.464C1912.203,-264.0303 1926.3135,-255.679 1934.5952,-243 1938.9752,-236.2943 1940.5115,-227.9657 1940.6662,-219.9964"/>
<polygon fill="#000000" stroke="#000000" points="1944.1572,-219.7202 1940.1967,-209.8935 1937.1648,-220.0452 1944.1572,-219.7202"/>
<text text-anchor="middle" x="1976.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node20" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2601.5952" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2601.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2573.1394,-88.4706C2552.9156,-77.3378 2524.8018,-63.0828 2498.5952,-54 2457.112,-39.6227 2407.8851,-29.9962 2372.9256,-24.3436"/>
<polygon fill="#000000" stroke="#000000" points="2373.4332,-20.8805 2363.011,-22.7851 2372.3461,-27.7956 2373.4332,-20.8805"/>
<text text-anchor="middle" x="2590.0952" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_personnel -->
<g id="node21" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2776.5952" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2776.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2742.6887,-88.3122C2717.8005,-76.8038 2682.8533,-62.1613 2650.5952,-54 2554.2183,-29.6166 2437.5035,-21.7442 2374.0981,-19.2055"/>
<polygon fill="#000000" stroke="#000000" points="2374.1408,-15.7047 2364.0171,-18.8292 2373.8796,-22.6999 2374.1408,-15.7047"/>
<text text-anchor="middle" x="2766.0952" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="544.5952" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="544.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M539.3551,-260.6126C537.4613,-249.7041 537.4733,-236.4075 545.5952,-228 565.8851,-206.9965 969.0157,-196.7036 1137.0433,-193.3126"/>
<polygon fill="#000000" stroke="#000000" points="1137.1131,-196.812 1147.0413,-193.1134 1136.9736,-189.8134 1137.1131,-196.812"/>
<text text-anchor="middle" x="589.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2240.5952" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2240.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2280.2324,-354.1456C2300.0242,-347.3428 2320.9458,-338.4892 2326.5952,-330 2330.2886,-324.4499 2331.1485,-319.8694 2326.5952,-315 2285.8269,-271.4017 2109.6209,-327.9716 2058.5952,-297 2027.9051,-278.3718 2047.4927,-246.282 2016.5952,-228 1985.2837,-209.473 1474.365,-197.3255 1282.043,-193.3901"/>
<polygon fill="#000000" stroke="#000000" points="1282.0991,-189.8906 1272.0301,-193.1868 1281.9569,-196.8892 1282.0991,-189.8906"/>
<text text-anchor="middle" x="2101.0952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2189.6399,-362.0648C2149.5979,-357.679 2093.0277,-348.583 2046.5952,-330 2035.2648,-325.4654 2034.847,-319.7259 2023.5952,-315 1988.2738,-300.1647 1945.9672,-291.0514 1913.3079,-285.7064"/>
<polygon fill="#000000" stroke="#000000" points="1913.4856,-282.1916 1903.0642,-284.1009 1912.4017,-289.1072 1913.4856,-282.1916"/>
<text text-anchor="middle" x="2089.0952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2279.5753,-353.9656C2306.0274,-345.4861 2337.0041,-334.8177 2341.5952,-330 2352.1677,-318.9056 2349.3487,-312.1597 2351.5952,-297 2353.9406,-281.1728 2353.1417,-276.9251 2351.5952,-261 2349.3625,-238.0099 2344.6629,-232.8937 2341.5952,-210 2333.8384,-152.1127 2330.1479,-83.7896 2328.5866,-46.2516"/>
<polygon fill="#000000" stroke="#000000" points="2332.0767,-45.9288 2328.1847,-36.0747 2325.0822,-46.2051 2332.0767,-45.9288"/>
<text text-anchor="middle" x="2384.0952" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2944.5952" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2944.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge31" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2918.0766,-88.5833C2897.4866,-76.7302 2867.7881,-61.5354 2839.5952,-54 2752.5503,-30.7346 2483.5305,-21.7615 2374.3545,-19.0183"/>
<polygon fill="#000000" stroke="#000000" points="2374.3822,-15.5181 2364.2995,-18.7721 2374.2108,-22.516 2374.3822,-15.5181"/>
<text text-anchor="middle" x="2929.5952" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node26" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2419.5952" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2419.5952" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2397.2657,-348.3112C2382.2916,-337.2527 2361.6999,-323.5369 2341.5952,-315 2308.4486,-300.9253 2295.9815,-310.4959 2262.5952,-297 2235.1411,-285.9021 2176.9599,-236.5046 2148.5952,-228 2107.347,-215.6326 1495.2423,-199.1734 1282.1114,-193.7877"/>
<polygon fill="#000000" stroke="#000000" points="1282.0503,-190.2852 1271.9653,-193.5321 1281.8739,-197.283 1282.0503,-190.2852"/>
<text text-anchor="middle" x="2348.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2341.0956,-353.5666C2300.3159,-346.9278 2249.7065,-338.4086 2204.5952,-330 2172.0337,-323.9307 2164.2546,-320.5176 2131.5952,-315 2056.1948,-302.2616 1968.3608,-291.2979 1913.6094,-284.9206"/>
<polygon fill="#000000" stroke="#000000" points="1913.7837,-281.4175 1903.4478,-283.7455 1912.9795,-288.3712 1913.7837,-281.4175"/>
<text text-anchor="middle" x="2290.5952" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2424.608,-347.8485C2433.3163,-312.9518 2448.3343,-234.5944 2426.5952,-174 2416.6793,-146.3613 2401.0083,-147.3481 2384.5952,-123 2367.5031,-97.6447 2351.194,-66.6716 2340.4343,-44.9593"/>
<polygon fill="#000000" stroke="#000000" points="2343.4371,-43.1327 2335.8983,-35.6885 2337.1494,-46.2092 2343.4371,-43.1327"/>
<text text-anchor="middle" x="2520.5952" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1914.1296,-203.0475C1903.4538,-209.1991 1891.1818,-217.702 1882.5952,-228 1876.8878,-234.8448 1872.434,-243.3946 1869.0725,-251.5261"/>
<polygon fill="#000000" stroke="#000000" points="1865.719,-250.502 1865.5031,-261.0946 1872.2775,-252.9486 1865.719,-250.502"/>
<text text-anchor="middle" x="1906.5952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1932.4755,-174.089C1928.3286,-151.1308 1925.1327,-111.3877 1945.5952,-87 1987.983,-36.4809 2188.8149,-22.8778 2281.0626,-19.2725"/>
<polygon fill="#000000" stroke="#000000" points="2281.3644,-22.7639 2291.229,-18.8987 2281.1071,-15.7686 2281.3644,-22.7639"/>
<text text-anchor="middle" x="1969.5952" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node28" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1698.5952" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1698.5952" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1656.2652,-262.6175C1625.0316,-251.1805 1581.2478,-236.4952 1541.5952,-228 1453.1627,-209.0542 1349.23,-199.8306 1281.5222,-195.5155"/>
<polygon fill="#000000" stroke="#000000" points="1281.5852,-192.0128 1271.3883,-194.8891 1281.1533,-198.9994 1281.5852,-192.0128"/>
<text text-anchor="middle" x="1674.0952" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
