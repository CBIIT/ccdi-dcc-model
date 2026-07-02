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
<svg width="3822pt" height="479pt"
 viewBox="0.00 0.00 3822.24 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3818.2382,-475 3818.2382,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1480.0444" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1480.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2190.0444" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2190.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1470.9911,-348.0339C1460.8256,-325.0162 1448.2826,-285.2088 1469.0444,-261 1510.7551,-212.3642 1943.0615,-197.4352 2117.5777,-193.3697"/>
<polygon fill="#000000" stroke="#000000" points="2117.7771,-196.8662 2127.6949,-193.1395 2117.6178,-189.868 2117.7771,-196.8662"/>
<text text-anchor="middle" x="1505.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1085.0444" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1085.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1436.0843,-362.9407C1384.2543,-358.6311 1295.8254,-349.068 1222.0444,-330 1204.064,-325.3531 1200.4277,-321.5354 1183.0444,-315 1165.7416,-308.4949 1146.6719,-301.4594 1129.9891,-295.3485"/>
<polygon fill="#000000" stroke="#000000" points="1131.0675,-292.0163 1120.4737,-291.8684 1128.6631,-298.5904 1131.0675,-292.0163"/>
<text text-anchor="middle" x="1258.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1180.0444" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1180.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1444.1517,-355.2163C1407.7508,-344.4383 1349.7154,-327.6886 1299.0444,-315 1262.8498,-305.9364 1252.2894,-309.2471 1217.0444,-297 1215.1213,-296.3318 1213.1679,-295.5892 1211.2146,-294.7972"/>
<polygon fill="#000000" stroke="#000000" points="1212.1528,-291.3851 1201.5917,-290.5397 1209.3205,-297.7865 1212.1528,-291.3851"/>
<text text-anchor="middle" x="1389.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="848.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="848.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge26" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M87.8788,-88.429C107.2037,-76.495 135.1684,-61.2666 162.0444,-54 223.2569,-37.4496 656.2275,-23.5518 801.0156,-19.3221"/>
<polygon fill="#000000" stroke="#000000" points="801.4395,-22.8113 811.3338,-19.0228 801.2365,-15.8143 801.4395,-22.8113"/>
<text text-anchor="middle" x="213.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- consent_group -->
<g id="node3" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1728.0444" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1728.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge31" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1655.2816,-97.8064C1479.9233,-80.4698 1037.845,-36.7644 894.0292,-22.5462"/>
<polygon fill="#000000" stroke="#000000" points="894.0973,-19.036 883.8014,-21.5351 893.4085,-26.002 894.0973,-19.036"/>
<text text-anchor="middle" x="1403.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="214.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="214.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge43" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M236.3626,-87.7564C252.9507,-75.9789 276.6652,-61.2432 300.0444,-54 347.2228,-39.3835 677.0524,-24.8431 801.0588,-19.8317"/>
<polygon fill="#000000" stroke="#000000" points="801.5134,-23.3163 811.365,-19.418 801.2326,-16.322 801.5134,-23.3163"/>
<text text-anchor="middle" x="356.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_surgery -->
<g id="node5" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1325.0444" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1325.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1315.9594,-260.6862C1311.9928,-249.8054 1309.8765,-236.5121 1318.0444,-228 1345.5442,-199.3414 1913.1482,-193.4779 2117.519,-192.2944"/>
<polygon fill="#000000" stroke="#000000" points="2117.5743,-195.7943 2127.5545,-192.2384 2117.5351,-188.7944 2117.5743,-195.7943"/>
<text text-anchor="middle" x="1396.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1257.0444" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1257.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1265.3305,-434.9074C1271.4125,-423.683 1280.7515,-409.9343 1293.0444,-402 1314.7828,-387.9693 1379.8399,-377.6383 1427.1209,-371.7278"/>
<polygon fill="#000000" stroke="#000000" points="1427.7138,-375.1815 1437.2174,-370.4984 1426.8676,-368.2329 1427.7138,-375.1815"/>
<text text-anchor="middle" x="1384.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="3091.0444" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="3091.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3037.513,-449.2957C2907.7937,-440.3923 2566.3114,-417.3899 2281.0444,-402 2000.2229,-386.85 1663.7754,-373.1913 1534.3941,-368.1055"/>
<polygon fill="#000000" stroke="#000000" points="1534.473,-364.606 1524.3435,-367.7113 1534.1986,-371.6006 1534.473,-364.606"/>
<text text-anchor="middle" x="2569.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3107.7345,-435.7737C3136.4185,-407.0502 3197.9921,-349.1622 3260.0444,-315 3282.2061,-302.7992 3299.2523,-317.523 3314.0444,-297 3333.4949,-270.0139 3315.122,-242.2094 3285.0444,-228 3238.8926,-206.1967 2500.0751,-195.6448 2262.7978,-192.8067"/>
<polygon fill="#000000" stroke="#000000" points="2262.5929,-189.3041 2252.552,-192.6852 2262.5098,-196.3036 2262.5929,-189.3041"/>
<text text-anchor="middle" x="3304.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1604.0444" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1604.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1634.4696,-264.2124C1660.5174,-252.2765 1699.3594,-236.1715 1735.0444,-228 1805.8494,-211.7864 2008.5997,-200.3321 2117.994,-195.1359"/>
<polygon fill="#000000" stroke="#000000" points="2118.4569,-198.6181 2128.2816,-194.6526 2118.1283,-191.6258 2118.4569,-198.6181"/>
<text text-anchor="middle" x="1778.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node9" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1805.0444" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1805.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1813.66,-260.7794C1820.0809,-249.3509 1829.9896,-235.4212 1843.0444,-228 1866.4135,-214.7155 2024.2486,-202.5431 2118.8117,-196.3291"/>
<polygon fill="#000000" stroke="#000000" points="2119.1353,-199.8156 2128.887,-195.6738 2118.6809,-192.8303 2119.1353,-199.8156"/>
<text text-anchor="middle" x="1945.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="380.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="380.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M395.4425,-87.1235C406.5644,-75.5328 422.6399,-61.2817 440.0444,-54 504.1562,-27.1769 708.2265,-20.327 801.1499,-18.5874"/>
<polygon fill="#000000" stroke="#000000" points="801.4468,-22.0828 811.384,-18.4082 801.3242,-15.0839 801.4468,-22.0828"/>
<text text-anchor="middle" x="502.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node11" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2057.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2057.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2051.9605,-260.7406C2050.1582,-250.1495 2050.0489,-237.1407 2057.0444,-228 2065.6926,-216.6997 2095.0279,-208.1274 2123.9544,-202.1882"/>
<polygon fill="#000000" stroke="#000000" points="2124.9922,-205.5516 2134.1344,-200.1971 2123.6485,-198.6818 2124.9922,-205.5516"/>
<text text-anchor="middle" x="2140.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2137.4969,-182.1047C2054.4362,-166.4634 1892.6704,-136.001 1799.2556,-118.4099"/>
<polygon fill="#000000" stroke="#000000" points="1799.7986,-114.9507 1789.3236,-116.5396 1798.5032,-121.8298 1799.7986,-114.9507"/>
<text text-anchor="middle" x="2036.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node13" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1480.0444" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1480.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1480.0444,-434.9735C1480.0444,-423.1918 1480.0444,-407.5607 1480.0444,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="1483.5445,-394.0033 1480.0444,-384.0034 1476.5445,-394.0034 1483.5445,-394.0033"/>
<text text-anchor="middle" x="1551.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="562.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="562.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M562.6186,-86.7739C563.9833,-75.6425 567.6528,-62.0463 577.0444,-54 593.7701,-39.6701 728.7175,-27.1941 801.6523,-21.4174"/>
<polygon fill="#000000" stroke="#000000" points="802.2444,-24.8819 811.9417,-20.6143 801.6996,-17.9032 802.2444,-24.8819"/>
<text text-anchor="middle" x="646.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1099.3056,-261.5895C1110.1776,-249.7312 1126.2707,-234.9675 1144.0444,-228 1189.2113,-210.294 1887.1617,-197.0731 2117.1607,-193.1788"/>
<polygon fill="#000000" stroke="#000000" points="2117.4902,-196.6738 2127.4298,-193.0058 2117.3722,-189.6748 2117.4902,-196.6738"/>
<text text-anchor="middle" x="1184.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge36" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1041.3494,-270.4974C1020.1106,-264.9713 994.9427,-256.2601 975.0444,-243 932.5619,-214.69 923.4333,-201.3782 900.0444,-156 878.6603,-114.5116 895.0067,-96.1909 875.0444,-54 873.2902,-50.2925 871.12,-46.5916 868.7781,-43.0505"/>
<polygon fill="#000000" stroke="#000000" points="871.4249,-40.7364 862.7425,-34.6647 865.7435,-44.8256 871.4249,-40.7364"/>
<text text-anchor="middle" x="940.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1196.794,-264.5288C1212.1147,-252.2699 1235.9925,-235.5223 1260.0444,-228 1340.847,-202.7289 1912.6921,-194.707 2117.3889,-192.6289"/>
<polygon fill="#000000" stroke="#000000" points="2117.4733,-196.1283 2127.4378,-192.5287 2117.4034,-189.1287 2117.4733,-196.1283"/>
<text text-anchor="middle" x="1284.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1157.8021,-267.8202C1145.2009,-261.1621 1129.346,-252.23 1116.0444,-243 1009.0267,-168.7402 992.2324,-137.2447 892.0444,-54 886.6379,-49.5078 880.8342,-44.7289 875.2728,-40.1704"/>
<polygon fill="#000000" stroke="#000000" points="877.3289,-37.3305 867.3724,-33.7085 872.8971,-42.7489 877.3289,-37.3305"/>
<text text-anchor="middle" x="1030.0444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="727.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="727.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge42" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M721.048,-86.7972C718.7608,-76.2262 718.1372,-63.2186 725.0444,-54 734.6453,-41.1863 772.3277,-31.4018 803.4821,-25.2905"/>
<polygon fill="#000000" stroke="#000000" points="804.1448,-28.7273 813.3239,-23.4362 802.8487,-21.8483 804.1448,-28.7273"/>
<text text-anchor="middle" x="773.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node18" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="849.0444" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="849.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M881.4,-435.7666C904.9964,-424.0749 938.1221,-409.4396 969.0444,-402 1054.4668,-381.4483 1312.4236,-371.1758 1425.7049,-367.5578"/>
<polygon fill="#000000" stroke="#000000" points="1425.9964,-371.0504 1435.8816,-367.2383 1425.7767,-364.0539 1425.9964,-371.0504"/>
<text text-anchor="middle" x="1055.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M851.1634,-434.9901C855.3064,-406.6712 866.7863,-351.2315 896.0444,-315 943.2611,-256.5297 968.9399,-249.193 1041.0444,-228 1092.6602,-212.829 1872.6736,-197.6714 2117.2635,-193.2703"/>
<polygon fill="#000000" stroke="#000000" points="2117.5323,-196.7662 2127.4679,-193.0874 2117.4068,-189.7673 2117.5323,-196.7662"/>
<text text-anchor="middle" x="982.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M825.0502,-435.191C783.3716,-402.5712 698.998,-328.6587 667.0444,-243 641.3834,-174.2099 688.6667,-257.504 796.0444,-123 814.8643,-99.4257 829.3291,-67.9312 838.1694,-45.6021"/>
<polygon fill="#000000" stroke="#000000" points="841.52,-46.6394 841.8308,-36.0492 834.9837,-44.1342 841.52,-46.6394"/>
<text text-anchor="middle" x="753.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- laboratory_test -->
<g id="node20" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="3562.0444" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="3562.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3497.1345,-441.9992C3480.515,-439.4381 3462.6468,-436.9063 3446.0444,-435 3250.7793,-412.58 3201.3551,-411.6557 3005.0444,-402 2430.1012,-373.7208 1732.0953,-367.5105 1534.4873,-366.2801"/>
<polygon fill="#000000" stroke="#000000" points="1534.3853,-362.7795 1524.3642,-366.2187 1534.3428,-369.7794 1534.3853,-362.7795"/>
<text text-anchor="middle" x="3327.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3554.5487,-435.0112C3542.062,-406.7212 3514.7077,-351.3204 3478.0444,-315 3424.3821,-261.8396 3404.545,-249.1978 3332.0444,-228 3230.0356,-198.1745 2498.4598,-193.0563 2262.9107,-192.1803"/>
<polygon fill="#000000" stroke="#000000" points="2262.7506,-188.6798 2252.7381,-192.144 2262.7255,-195.6797 2262.7506,-188.6798"/>
<text text-anchor="middle" x="3556.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- genetic_analysis -->
<g id="node21" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2655.0444" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2655.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2572.4207,-446.8823C2346.2004,-430.1324 1721.157,-383.8526 1533.8029,-369.9804"/>
<polygon fill="#000000" stroke="#000000" points="1533.8829,-366.4768 1523.6518,-369.2288 1533.366,-373.4577 1533.8829,-366.4768"/>
<text text-anchor="middle" x="2207.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2674.0788,-435.1302C2719.4312,-390.7456 2824.8305,-275.6388 2752.0444,-228 2712.0904,-201.85 2405.8267,-194.6465 2262.9786,-192.7011"/>
<polygon fill="#000000" stroke="#000000" points="2262.6131,-189.1961 2252.568,-192.5647 2262.5213,-196.1955 2262.6131,-189.1961"/>
<text text-anchor="middle" x="2835.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- pathology_file -->
<g id="node22" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1664.0444" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1664.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1655.1336,-434.8619C1648.778,-423.7656 1639.2108,-410.1755 1627.0444,-402 1611.3959,-391.4846 1567.0975,-381.4457 1531.1876,-374.6535"/>
<polygon fill="#000000" stroke="#000000" points="1531.7824,-371.2042 1521.3125,-372.8262 1530.5086,-378.0874 1531.7824,-371.2042"/>
<text text-anchor="middle" x="1703.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1071.0444" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1071.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1099.5264,-437.8078C1122.7104,-426.1308 1156.6246,-410.5898 1188.0444,-402 1268.9187,-379.89 1366.1297,-371.3329 1425.4782,-368.0387"/>
<polygon fill="#000000" stroke="#000000" points="1425.9441,-371.5192 1435.7471,-367.5005 1425.5776,-364.5288 1425.9441,-371.5192"/>
<text text-anchor="middle" x="1230.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1077.4931,-434.7771C1086.3565,-406.1663 1098.4066,-350.3338 1072.0444,-315 1059.1633,-297.7351 1039.1207,-314.8371 1027.0444,-297 1018.0743,-283.7509 1017.9066,-274.1339 1027.0444,-261 1051.1381,-226.3698 1074.651,-236.145 1116.0444,-228 1213.5094,-208.8217 1892.146,-196.6373 2117.4962,-193.0836"/>
<polygon fill="#000000" stroke="#000000" points="2117.6178,-196.5822 2127.5617,-192.9258 2117.5081,-189.5831 2117.6178,-196.5822"/>
<text text-anchor="middle" x="1123.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge37" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1023.5962,-445.6003C986.0775,-439.0287 937.3881,-428.6758 921.0444,-417 880.5628,-388.0803 861.0444,-372.2505 861.0444,-322.5 861.0444,-322.5 861.0444,-322.5 861.0444,-105 861.0444,-85.0177 857.6484,-62.7345 854.3278,-45.7224"/>
<polygon fill="#000000" stroke="#000000" points="857.7459,-44.9675 852.3011,-35.8788 850.8897,-46.3792 857.7459,-44.9675"/>
<text text-anchor="middle" x="903.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_other -->
<g id="node24" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2267.0444" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2267.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2253.9075,-261.0606C2246.3597,-251.0649 2236.5216,-238.5454 2227.0444,-228 2223.6128,-224.1816 2219.8644,-220.2696 2216.1129,-216.4971"/>
<polygon fill="#000000" stroke="#000000" points="2218.5597,-213.9944 2208.9769,-209.4754 2213.65,-218.984 2218.5597,-213.9944"/>
<text text-anchor="middle" x="2308.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2457.0444" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2457.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2436.4201,-261.5179C2422.0635,-250.2542 2401.9863,-236.2266 2382.0444,-228 2343.5007,-212.0995 2297.6964,-203.1684 2260.4946,-198.1799"/>
<polygon fill="#000000" stroke="#000000" points="2260.605,-194.6658 2250.243,-196.8749 2259.721,-201.6098 2260.605,-194.6658"/>
<text text-anchor="middle" x="2476.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="3371.0444" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="3371.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3308.2184,-447.4013C3265.1335,-443.651 3206.6506,-438.7355 3155.0444,-435 2916.5515,-417.7369 2856.9028,-413.1148 2618.0444,-402 2201.4301,-382.6136 1698.5243,-370.729 1534.569,-367.1493"/>
<polygon fill="#000000" stroke="#000000" points="1534.3379,-363.6435 1524.2643,-366.9255 1534.1859,-370.6419 1534.3379,-363.6435"/>
<text text-anchor="middle" x="2948.0444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3373.3022,-434.8234C3377.8704,-388.6529 3382.2307,-267.7099 3309.0444,-228 3263.0699,-203.0548 2503.0695,-194.6059 2262.474,-192.5493"/>
<polygon fill="#000000" stroke="#000000" points="2262.4609,-189.0491 2252.4317,-192.4646 2262.4018,-196.0489 2262.4609,-189.0491"/>
<text text-anchor="middle" x="3423.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3427.0262,-443.4929C3507.4322,-426.2684 3646.0444,-381.6838 3646.0444,-279 3646.0444,-279 3646.0444,-279 3646.0444,-105 3646.0444,-33.1881 1259.7142,-19.8145 894.6515,-18.1887"/>
<polygon fill="#000000" stroke="#000000" points="894.4601,-14.6879 884.4448,-18.144 894.4293,-21.6879 894.4601,-14.6879"/>
<text text-anchor="middle" x="3699.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- family_relationship -->
<g id="node27" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2660.0444" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2660.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2629.2115,-261.6308C2607.2707,-250.1128 2576.7153,-235.7427 2548.0444,-228 2495.7637,-213.8815 2350.0808,-202.3737 2261.4976,-196.4167"/>
<polygon fill="#000000" stroke="#000000" points="2261.4636,-192.9068 2251.2534,-195.7354 2260.999,-199.8913 2261.4636,-192.9068"/>
<text text-anchor="middle" x="2668.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- survival -->
<g id="node28" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2864.0444" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2864.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2848.8275,-261.7131C2837.2912,-249.9146 2820.3412,-235.1716 2802.0444,-228 2753.0051,-208.7785 2413.8819,-197.7581 2262.61,-193.7486"/>
<polygon fill="#000000" stroke="#000000" points="2262.5743,-190.2466 2252.486,-193.4833 2262.3909,-197.2442 2262.5743,-190.2466"/>
<text text-anchor="middle" x="2865.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_status -->
<g id="node29" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="3744.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3744.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3722.7618,-87.6392C3706.6302,-75.6384 3683.3324,-60.6771 3660.0444,-54 3590.7689,-34.1374 1256.0622,-20.2839 894.797,-18.257"/>
<polygon fill="#000000" stroke="#000000" points="894.708,-14.7565 884.6886,-18.2005 894.6688,-21.7564 894.708,-14.7565"/>
<text text-anchor="middle" x="3750.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- radiology_file -->
<g id="node30" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="3004.0444" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="3004.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2979.5413,-261.9056C2961.0818,-250.0372 2934.6533,-235.1249 2909.0444,-228 2848.0169,-211.021 2432.7278,-198.3569 2262.5495,-193.8219"/>
<polygon fill="#000000" stroke="#000000" points="2262.5211,-190.32 2252.432,-193.5542 2262.3359,-197.3176 2262.5211,-190.32"/>
<text text-anchor="middle" x="3003.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node31" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1841.0444" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1841.0444" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1821.5058,-435.3627C1807.6153,-423.8788 1787.9581,-409.657 1768.0444,-402 1726.5229,-386.0346 1605.2746,-374.967 1534.0286,-369.6358"/>
<polygon fill="#000000" stroke="#000000" points="1534.1249,-366.1335 1523.8952,-368.8909 1533.6117,-373.1147 1534.1249,-366.1335"/>
<text text-anchor="middle" x="1862.5444" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment_radiation -->
<g id="node32" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="3200.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="3200.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3164.8709,-262.0187C3138.375,-250.124 3100.7914,-235.1294 3066.0444,-228 2988.4992,-212.0893 2458.5302,-198.265 2262.6301,-193.6426"/>
<polygon fill="#000000" stroke="#000000" points="2262.5193,-190.1391 2252.4399,-193.4033 2262.355,-197.1372 2262.5193,-190.1391"/>
<text text-anchor="middle" x="3198.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
</g>
</svg>
</div>
