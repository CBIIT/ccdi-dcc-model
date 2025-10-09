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
<svg width="2973pt" height="392pt"
 viewBox="0.00 0.00 2973.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2969.1938,-388 2969.1938,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1268" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1268" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node4" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1882" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1882" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1326.5799,-185.6974C1423.9328,-174.914 1625.0483,-151.3235 1794,-123 1800.6132,-121.8913 1807.4875,-120.6473 1814.3487,-119.3446"/>
<polygon fill="#000000" stroke="#000000" points="1815.2092,-122.743 1824.3598,-117.403 1813.8764,-115.8711 1815.2092,-122.743"/>
<text text-anchor="middle" x="1714.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node2" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="602" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="602" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M594.0881,-261.187C590.5535,-250.2203 588.7992,-236.6526 597,-228 617.337,-206.5426 1026.2803,-196.4932 1195.5795,-193.2402"/>
<polygon fill="#000000" stroke="#000000" points="1195.7179,-196.7383 1205.6497,-193.0493 1195.5851,-189.7396 1195.7179,-196.7383"/>
<text text-anchor="middle" x="640.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="446" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="446" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M441.8237,-348.0411C437.6157,-325.0312 434.3538,-285.2323 455,-261 494.2185,-214.9696 527.1969,-236.9709 587,-228 702.599,-210.6594 1045.0367,-198.651 1195.5965,-194.066"/>
<polygon fill="#000000" stroke="#000000" points="1195.7761,-197.5623 1205.6658,-193.7618 1195.5646,-190.5655 1195.7761,-197.5623"/>
<text text-anchor="middle" x="497.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2220" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2220" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M395.7051,-361.4219C279.0648,-350.1293 0,-318.938 0,-279 0,-279 0,-279 0,-105 0,-82.1101 69.8219,-75.9278 421,-54 776.585,-31.797 1926.7357,-20.5798 2173.2205,-18.3985"/>
<polygon fill="#000000" stroke="#000000" points="2173.3085,-21.8979 2183.2773,-18.31 2173.2469,-14.8982 2173.3085,-21.8979"/>
<text text-anchor="middle" x="42.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node26" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2161" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2161" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.2264,-358.3145C517.083,-354.685 546.515,-350.5907 573,-348 842.3345,-321.654 910.5635,-324.9617 1181,-315 1283.9496,-311.2078 2006.5256,-314.775 2108,-297 2111.7121,-296.3498 2115.5158,-295.4835 2119.2981,-294.4815"/>
<polygon fill="#000000" stroke="#000000" points="2120.5807,-297.7524 2129.1829,-291.5674 2118.6013,-291.038 2120.5807,-297.7524"/>
<text text-anchor="middle" x="1223.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge39" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1893.6987,-86.8207C1902.0805,-75.4096 1914.4349,-61.4838 1929,-54 1970.5919,-32.6295 2102.3535,-23.3914 2173.4469,-19.8783"/>
<polygon fill="#000000" stroke="#000000" points="2173.6557,-23.3724 2183.478,-19.4007 2173.3228,-16.3803 2173.6557,-23.3724"/>
<text text-anchor="middle" x="1992.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1921" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1921" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1941.5561,-348.3494C1955.883,-337.0126 1975.9529,-322.9667 1996,-315 2042.8524,-296.3808 2059.0692,-309.1494 2108,-297 2111.4041,-296.1548 2114.9018,-295.1901 2118.3992,-294.1564"/>
<polygon fill="#000000" stroke="#000000" points="2119.6745,-297.4249 2128.1762,-291.1025 2117.5875,-290.7432 2119.6745,-297.4249"/>
<text text-anchor="middle" x="2067.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment -->
<g id="node6" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="939" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="939" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M958.8777,-261.9818C973.4468,-250.4713 994.229,-235.9653 1015,-228 1047.4711,-215.5478 1135.0533,-204.846 1198.0699,-198.4206"/>
<polygon fill="#000000" stroke="#000000" points="1198.7521,-201.8698 1208.3522,-197.3877 1198.0524,-194.9048 1198.7521,-201.8698"/>
<text text-anchor="middle" x="1062" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2144" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2144" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2142.6213,-347.8548C2142.306,-338.0197 2142.6152,-325.7192 2145,-315 2145.6406,-312.1209 2146.5193,-309.1902 2147.5379,-306.3069"/>
<polygon fill="#000000" stroke="#000000" points="2150.8666,-307.4129 2151.3964,-296.8313 2144.3835,-304.7729 2150.8666,-307.4129"/>
<text text-anchor="middle" x="2236.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_arm -->
<g id="node8" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1725" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1725" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1746.1524,-88.1486C1762.1531,-76.401 1785.1962,-61.5334 1808,-54 1874.7132,-31.9608 2080.2108,-22.5792 2173.3069,-19.3826"/>
<polygon fill="#000000" stroke="#000000" points="2173.6778,-22.8722 2183.5554,-19.0402 2173.444,-15.8761 2173.6778,-22.8722"/>
<text text-anchor="middle" x="1856.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- medical_history -->
<g id="node10" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1100" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1100" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1104.6261,-260.9583C1108.3641,-249.9004 1114.7325,-236.3169 1125,-228 1137.3411,-218.0034 1171.3094,-209.2405 1203.0426,-202.8636"/>
<polygon fill="#000000" stroke="#000000" points="1204.0902,-206.2255 1213.2368,-200.8785 1202.7521,-199.3545 1204.0902,-206.2255"/>
<text text-anchor="middle" x="1193" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node11" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1308" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1308" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1282.7346,-261.2657C1277.213,-256.0617 1272.0982,-249.8915 1269,-243 1265.8545,-236.0031 1264.7232,-227.902 1264.6032,-220.2449"/>
<polygon fill="#000000" stroke="#000000" points="1268.1017,-220.3463 1264.9722,-210.2243 1261.1065,-220.0887 1268.1017,-220.3463"/>
<text text-anchor="middle" x="1352" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pathology_file -->
<g id="node12" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2354" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2354" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2349.1046,-347.8249C2345.1835,-336.7138 2338.5546,-323.1212 2328,-315 2310.3018,-301.3823 2255.6422,-291.3289 2213.6276,-285.3584"/>
<polygon fill="#000000" stroke="#000000" points="2213.905,-281.8636 2203.5207,-283.9651 2212.949,-288.798 2213.905,-281.8636"/>
<text text-anchor="middle" x="2401" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- genetic_analysis -->
<g id="node13" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1599" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1599" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1612.9006,-348.063C1618.7449,-338.2889 1623.3028,-325.9802 1619,-315 1607.0662,-284.5466 1596.9327,-278.0174 1569,-261 1530.0024,-237.2416 1409.6214,-214.549 1333.4361,-202.0242"/>
<polygon fill="#000000" stroke="#000000" points="1333.8855,-198.5513 1323.4531,-200.3995 1332.761,-205.4604 1333.8855,-198.5513"/>
<text text-anchor="middle" x="1680" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1625.6112,-348.6147C1645.2864,-336.7686 1673.2044,-322.0091 1700,-315 1875.6016,-269.0667 1929.6124,-330.5209 2108,-297 2111.653,-296.3136 2115.3976,-295.4304 2119.1249,-294.4246"/>
<polygon fill="#000000" stroke="#000000" points="2120.2872,-297.7306 2128.8759,-291.5269 2118.2931,-291.0206 2120.2872,-297.7306"/>
<text text-anchor="middle" x="1770" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sequencing_file -->
<g id="node14" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2531" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2531" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2513.9635,-348.2951C2501.7562,-336.7811 2484.2974,-322.551 2466,-315 2421.8691,-296.7881 2290.234,-286.4395 2215.111,-281.8648"/>
<polygon fill="#000000" stroke="#000000" points="2215.0911,-278.3575 2204.9009,-281.2574 2214.6754,-285.3452 2215.0911,-278.3575"/>
<text text-anchor="middle" x="2557.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node15" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1999" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1999" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1949.9802,-263.2591C1911.303,-251.5209 1855.7611,-236.1622 1806,-228 1718.395,-213.6304 1465.2832,-200.7923 1339.9974,-195.1041"/>
<polygon fill="#000000" stroke="#000000" points="1339.8883,-191.5957 1329.7407,-194.6415 1339.5728,-198.5886 1339.8883,-191.5957"/>
<text text-anchor="middle" x="1954.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node16" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="222" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="222" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M221.5286,-260.7754C222.3032,-249.4969 225.3931,-235.7374 235,-228 253.6985,-212.9403 963.4335,-197.8941 1195.4386,-193.3691"/>
<polygon fill="#000000" stroke="#000000" points="1195.5351,-196.8679 1205.4652,-193.1743 1195.399,-189.8693 1195.5351,-196.8679"/>
<text text-anchor="middle" x="294" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- survival -->
<g id="node17" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="362" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="362" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M356.8056,-261.0662C354.8092,-250.0513 354.6938,-236.4753 363,-228 391.9526,-198.458 984.8864,-193.1584 1194.9834,-192.2078"/>
<polygon fill="#000000" stroke="#000000" points="1195.3072,-195.7065 1205.292,-192.1633 1195.2769,-188.7066 1195.3072,-195.7065"/>
<text text-anchor="middle" x="402.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2521" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2521" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge38" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2495.0857,-184.8592C2459.7429,-174.4524 2395.1994,-153.0334 2346,-123 2325.302,-110.3651 2323.5282,-102.6446 2305,-87 2286.0787,-71.0235 2264.4003,-53.4368 2247.6721,-40.017"/>
<polygon fill="#000000" stroke="#000000" points="2249.4109,-36.9257 2239.4165,-33.4098 2245.037,-42.391 2249.4109,-36.9257"/>
<text text-anchor="middle" x="2370" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2495.1228,-198.9599C2457.376,-209.0452 2384.9601,-228.1402 2323,-243 2285.3319,-252.0339 2242.5458,-261.5085 2210.4075,-268.4691"/>
<polygon fill="#000000" stroke="#000000" points="2209.4031,-265.1052 2200.3671,-270.6369 2210.8805,-271.9475 2209.4031,-265.1052"/>
<text text-anchor="middle" x="2407" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2066" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2066" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2061.2296,-86.6052C2059.6192,-75.966 2059.764,-62.9544 2067,-54 2080.3322,-37.5017 2133.8983,-27.765 2173.9138,-22.6621"/>
<polygon fill="#000000" stroke="#000000" points="2174.5158,-26.1147 2184.0203,-21.4334 2173.6709,-19.1659 2174.5158,-26.1147"/>
<text text-anchor="middle" x="2136.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="691" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="691" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M686.3735,-347.6327C681.6786,-324.1812 677.8909,-283.9055 700,-261 733.938,-225.8395 1051.2997,-203.964 1196.3194,-195.7245"/>
<polygon fill="#000000" stroke="#000000" points="1196.6689,-199.2105 1206.4567,-195.1548 1196.2761,-192.2215 1196.6689,-199.2105"/>
<text text-anchor="middle" x="786" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M597.1739,-356.9114C444.4613,-341.7443 157.3014,-311.5098 140,-297 118.0801,-278.6169 121,-264.108 121,-235.5 121,-235.5 121,-235.5 121,-105 121,-51.8338 1863.2787,-23.3296 2173.1542,-18.6803"/>
<polygon fill="#000000" stroke="#000000" points="2173.6213,-22.1738 2183.5679,-18.525 2173.5168,-15.1746 2173.6213,-22.1738"/>
<text text-anchor="middle" x="207" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M798.0798,-362.7959C953.363,-357.6259 1227.2554,-346.3431 1270,-330 1280.0494,-326.1577 1278.8756,-318.6399 1289,-315 1374.6545,-284.2054 2018.3633,-312.8196 2108,-297 2111.7112,-296.345 2115.5144,-295.4754 2119.2963,-294.4712"/>
<polygon fill="#000000" stroke="#000000" points="2120.5804,-297.7416 2129.1805,-291.5537 2118.5987,-291.0279 2120.5804,-297.7416"/>
<text text-anchor="middle" x="1375" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2220" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2220" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2220,-173.7078C2220,-143.3436 2220,-82.3226 2220,-46.3464"/>
<polygon fill="#000000" stroke="#000000" points="2223.5001,-46.0471 2220,-36.0471 2216.5001,-46.0471 2223.5001,-46.0471"/>
<text text-anchor="middle" x="2260.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2231.9486,-209.5102C2237.3955,-219.8357 2241.3631,-232.8284 2235,-243 2228.7881,-252.93 2218.9654,-260.1921 2208.4817,-265.4765"/>
<polygon fill="#000000" stroke="#000000" points="2206.8798,-262.3586 2199.1729,-269.6287 2209.7313,-268.7515 2206.8798,-262.3586"/>
<text text-anchor="middle" x="2278.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_funding -->
<g id="node22" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2480" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2480" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2442.8567,-89.0766C2417.2918,-78.4242 2382.4081,-64.4899 2351,-54 2321.8691,-44.2706 2288.4799,-35.1248 2262.7015,-28.4862"/>
<polygon fill="#000000" stroke="#000000" points="2263.4204,-25.0576 2252.8658,-25.9795 2261.6916,-31.8408 2263.4204,-25.0576"/>
<text text-anchor="middle" x="2452" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- laboratory_test -->
<g id="node23" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1287" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1287" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1214.7325,-357.377C1177.6679,-350.1274 1144.2564,-337.2472 1165,-315 1204.0428,-273.1271 1378.2947,-333.98 1422,-297 1440.845,-281.0548 1432.0908,-267.5137 1435,-243 1435.7857,-236.3798 1439.188,-233.187 1435,-228 1422.6331,-212.6831 1378.1859,-203.5712 1338.2546,-198.3476"/>
<polygon fill="#000000" stroke="#000000" points="1338.5773,-194.8609 1328.2222,-197.102 1337.7147,-201.8076 1338.5773,-194.8609"/>
<text text-anchor="middle" x="1499.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1348.9045,-354.0772C1383.1859,-347.3248 1426.5262,-338.5415 1465,-330 1492.6767,-323.8556 1498.9043,-318.7925 1527,-315 1783.0242,-280.4409 1853.7902,-343.0446 2108,-297 2111.7083,-296.3283 2115.5093,-295.4471 2119.2899,-294.4352"/>
<polygon fill="#000000" stroke="#000000" points="2120.5791,-297.7036 2129.1718,-291.5056 2118.5895,-290.9923 2120.5791,-297.7036"/>
<text text-anchor="middle" x="1592.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- publication -->
<g id="node24" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2638" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2638" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge40" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2607.275,-89.0873C2583.5248,-77.4981 2549.4926,-62.413 2518,-54 2431.0841,-30.781 2325.8757,-22.5066 2266.5715,-19.5797"/>
<polygon fill="#000000" stroke="#000000" points="2266.5511,-16.0751 2256.3997,-19.1083 2266.2269,-23.0676 2266.5511,-16.0751"/>
<text text-anchor="middle" x="2613" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- generic_file -->
<g id="node25" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2772" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2772" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2771.569,-347.5106C2770.3119,-336.5637 2766.8668,-323.2626 2758,-315 2753.4924,-310.7996 2329.1201,-228.7116 2323,-228 2132.2342,-205.8192 1546.6959,-195.8275 1340.6484,-192.9336"/>
<polygon fill="#000000" stroke="#000000" points="1340.589,-189.4326 1330.5412,-192.7931 1340.4916,-196.4319 1340.589,-189.4326"/>
<text text-anchor="middle" x="2728" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2780.3246,-348.1C2787.5972,-330.8051 2797,-303.6732 2797,-279 2797,-279 2797,-279 2797,-105 2797,-43.3487 2728.0511,-67.9553 2668,-54 2592.6522,-36.4899 2365.278,-24.5081 2266.5693,-19.9949"/>
<polygon fill="#000000" stroke="#000000" points="2266.4531,-16.4861 2256.3053,-19.5314 2266.1372,-23.479 2266.4531,-16.4861"/>
<text text-anchor="middle" x="2850" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2722.1685,-354.2576C2700.1661,-348.264 2674.2924,-340.0899 2652,-330 2640.5405,-324.8132 2639.9489,-318.9302 2628,-315 2552.7763,-290.2579 2321.7065,-282.326 2215.4661,-279.947"/>
<polygon fill="#000000" stroke="#000000" points="2215.3515,-276.4438 2205.2784,-279.7274 2215.2006,-283.4422 2215.3515,-276.4438"/>
<text text-anchor="middle" x="2705" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2130.3063,-265.9631C2095.4614,-251.2098 2042.7941,-229.0715 2038,-228 1971.1789,-213.0653 1519.1056,-199.0021 1340.4424,-193.9615"/>
<polygon fill="#000000" stroke="#000000" points="1340.4457,-190.4603 1330.3514,-193.6782 1340.2492,-197.4575 1340.4457,-190.4603"/>
<text text-anchor="middle" x="2110.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2205.4205,-278.4004C2306.2816,-276.5784 2545.7479,-269.4806 2570,-243 2580.9156,-231.0814 2567.6528,-217.9366 2552.189,-207.9773"/>
<polygon fill="#000000" stroke="#000000" points="2553.8923,-204.9179 2543.5112,-202.8 2550.3058,-210.9293 2553.8923,-204.9179"/>
<text text-anchor="middle" x="2609.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2155.2518,-260.8792C2153.0857,-250.5889 2152.3357,-237.8389 2158,-228 2162.1482,-220.7947 2168.3527,-214.8985 2175.258,-210.1188"/>
<polygon fill="#000000" stroke="#000000" points="2177.5431,-212.8263 2184.2776,-204.6472 2173.9125,-206.8414 2177.5431,-212.8263"/>
<text text-anchor="middle" x="2194.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_admin -->
<g id="node27" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2895" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2895" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2873.2751,-87.7203C2857.1086,-75.9253 2833.9581,-61.1835 2811,-54 2759.6594,-37.9357 2397.1194,-24.0722 2266.6432,-19.5514"/>
<polygon fill="#000000" stroke="#000000" points="2266.6786,-16.0506 2256.5642,-19.2048 2266.438,-23.0465 2266.6786,-16.0506"/>
<text text-anchor="middle" x="2898.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node28" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1759" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1759" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1717.1392,-354.332C1693.3543,-345.5529 1670.7332,-332.1099 1684,-315 1703.6839,-289.6141 1734.3161,-322.3859 1754,-297 1763.8042,-284.3557 1764.4885,-273.0827 1754,-261 1727.178,-230.101 1467.0845,-206.73 1338.8113,-196.9817"/>
<polygon fill="#000000" stroke="#000000" points="1338.9217,-193.4802 1328.6872,-196.2198 1338.3963,-200.4604 1338.9217,-193.4802"/>
<text text-anchor="middle" x="1805.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1793.5431,-351.95C1809.067,-345.4874 1827.5554,-337.5844 1844,-330 1857.5368,-323.7567 1859.6338,-318.9792 1874,-315 1974.5224,-287.1569 2005.8154,-317.9359 2108,-297 2111.6413,-296.254 2115.3777,-295.329 2119.0995,-294.2953"/>
<polygon fill="#000000" stroke="#000000" points="2120.2807,-297.5948 2128.8417,-291.353 2118.2568,-290.8937 2120.2807,-297.5948"/>
<text text-anchor="middle" x="1918.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
