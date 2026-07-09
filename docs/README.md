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
<svg width="2901pt" height="479pt"
 viewBox="0.00 0.00 2901.36 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 2897.357,-475 2897.357,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2159.357" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2159.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1336.357" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1336.357" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2139.2904,-262.635C2123.3024,-250.6421 2099.7864,-235.2424 2076.357,-228 2013.8167,-208.668 1582.8123,-197.3174 1408.8915,-193.4789"/>
<polygon fill="#000000" stroke="#000000" points="1408.883,-189.978 1398.8088,-193.2585 1408.7299,-196.9763 1408.883,-189.978"/>
<text text-anchor="middle" x="2146.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1812.357" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1812.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node14" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1049.357" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1049.357" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1761.6456,-448.7413C1708.5104,-443.6499 1622.8473,-433.6586 1550.357,-417 1529.3993,-412.1838 1525.4446,-406.2107 1504.357,-402 1429.0433,-386.9615 1206.9104,-374.0567 1103.4819,-368.6766"/>
<polygon fill="#000000" stroke="#000000" points="1103.4235,-365.169 1093.2565,-368.1492 1103.0628,-372.1598 1103.4235,-365.169"/>
<text text-anchor="middle" x="1592.857" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1825.4423,-435.5349C1831.3041,-425.4632 1835.8041,-412.7132 1830.357,-402 1794.4582,-331.3951 1744.2625,-351.0437 1686.357,-297 1657.0693,-269.6656 1663.5674,-247.1092 1628.357,-228 1591.6441,-208.0754 1482.652,-198.9155 1408.7241,-194.8983"/>
<polygon fill="#000000" stroke="#000000" points="1408.7057,-191.3926 1398.5364,-194.365 1408.3397,-198.3831 1408.7057,-191.3926"/>
<text text-anchor="middle" x="1776.857" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2268.357" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2268.357" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1851.66,-441.1205C1858.8612,-439.0242 1866.3228,-436.905 1873.357,-435 1996.8593,-401.552 2353.4654,-397.7359 2432.357,-297 2442.2221,-284.4032 2436.5535,-276.4399 2432.357,-261 2413.7039,-192.3717 2384.729,-185.8019 2351.357,-123 2335.4056,-92.9815 2340.1634,-80.0774 2318.357,-54 2313.3565,-48.0202 2307.1512,-42.5276 2300.8322,-37.7294"/>
<polygon fill="#000000" stroke="#000000" points="2302.428,-34.5701 2292.2475,-31.6363 2298.3765,-40.2784 2302.428,-34.5701"/>
<text text-anchor="middle" x="2468.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_surgery -->
<g id="node3" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2324.357" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2324.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2289.4597,-262.1545C2262.948,-250.2456 2225.2221,-235.1728 2190.357,-228 2114.9872,-212.4942 1601.1479,-198.4824 1408.8198,-193.7224"/>
<polygon fill="#000000" stroke="#000000" points="1408.8923,-190.2232 1398.8092,-193.4758 1408.7199,-197.2211 1408.8923,-190.2232"/>
<text text-anchor="middle" x="2317.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- treatment_other -->
<g id="node4" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="107.357" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="107.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M97.2475,-260.6869C92.7391,-249.8064 90.0878,-236.5131 98.357,-228 118.7661,-206.9888 1001.8642,-195.6594 1263.8381,-192.7565"/>
<polygon fill="#000000" stroke="#000000" points="1264.0408,-196.2546 1274.0017,-192.6447 1263.9637,-189.255 1264.0408,-196.2546"/>
<text text-anchor="middle" x="167.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- pdx -->
<g id="node5" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1050.357" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1050.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1067.5305,-264.5726C1082.4079,-252.8564 1105.0014,-236.8718 1127.357,-228 1171.3031,-210.56 1223.7486,-201.5581 1265.1093,-196.9172"/>
<polygon fill="#000000" stroke="#000000" points="1265.5287,-200.3924 1275.1031,-195.8559 1264.7894,-193.4316 1265.5287,-200.3924"/>
<text text-anchor="middle" x="1151.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_radiation -->
<g id="node6" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="374.357" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="374.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M390.3362,-261.1C402.0521,-249.3385 419.0524,-234.8956 437.357,-228 513.6396,-199.2633 1063.2612,-193.4548 1263.5689,-192.2896"/>
<polygon fill="#000000" stroke="#000000" points="1263.7158,-195.7889 1273.696,-192.2329 1263.6765,-188.789 1263.7158,-195.7889"/>
<text text-anchor="middle" x="520.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1783.357" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1783.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1796.8429,-87.1081C1806.6864,-75.5106 1821.1088,-61.2576 1837.357,-54 1871.7823,-38.6231 2117.4966,-25.2147 2221.7634,-20.1514"/>
<polygon fill="#000000" stroke="#000000" points="2222.171,-23.6359 2231.9913,-19.6595 2221.8347,-16.644 2222.171,-23.6359"/>
<text text-anchor="middle" x="1899.357" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="582.357" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="582.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M592.5437,-261.0007C600.2064,-249.3552 611.8597,-235.0891 626.357,-228 682.4847,-200.5538 1094.0221,-194.003 1263.6166,-192.4636"/>
<polygon fill="#000000" stroke="#000000" points="1263.7333,-195.9629 1273.7023,-192.3754 1263.672,-188.9631 1263.7333,-195.9629"/>
<text text-anchor="middle" x="694.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node9" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="790.357" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="790.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M775.2953,-261.0967C768.141,-250.3704 762.8228,-237.0953 771.357,-228 787.9511,-210.3149 1114.8545,-198.4994 1263.6766,-194.0161"/>
<polygon fill="#000000" stroke="#000000" points="1264.1861,-197.5025 1274.0773,-193.706 1263.9774,-190.5056 1264.1861,-197.5025"/>
<text text-anchor="middle" x="854.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1938.357" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1938.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1950.0642,-86.8372C1958.4496,-75.4331 1970.8047,-61.5089 1985.357,-54 2025.5472,-33.2621 2152.4171,-23.7914 2221.8426,-20.0661"/>
<polygon fill="#000000" stroke="#000000" points="2222.2551,-23.5495 2232.0607,-19.537 2221.8931,-16.5589 2222.2551,-23.5495"/>
<text text-anchor="middle" x="2033.857" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- laboratory_test -->
<g id="node11" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="148.357" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="148.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M196.5951,-438.4261C238.4269,-426.4518 300.8128,-410.1775 356.357,-402 479.3231,-383.8963 854.267,-371.5888 995.1161,-367.4949"/>
<polygon fill="#000000" stroke="#000000" points="995.348,-370.9898 1005.243,-367.203 995.1463,-363.9927 995.348,-370.9898"/>
<text text-anchor="middle" x="421.857" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M120.0195,-436.066C68.2549,-402.9442 -32.4157,-327.0482 11.357,-261 32.1513,-229.6235 52.5784,-236.0142 89.357,-228 203.7639,-203.0702 1014.7166,-194.5697 1263.782,-192.5311"/>
<polygon fill="#000000" stroke="#000000" points="1263.8406,-196.0309 1273.8119,-192.45 1263.7839,-189.0311 1263.8406,-196.0309"/>
<text text-anchor="middle" x="74.857" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2079.357" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2079.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2080.897,-86.9594C2082.7982,-75.9019 2087.0183,-62.3185 2096.357,-54 2114.6913,-37.6686 2177.9677,-27.6421 2222.4227,-22.4483"/>
<polygon fill="#000000" stroke="#000000" points="2222.8922,-25.9177 2232.4383,-21.3219 2222.1098,-18.9616 2222.8922,-25.9177"/>
<text text-anchor="middle" x="2147.357" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node13" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="357.357" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="357.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M408.2347,-438.1643C450.4737,-426.4493 512.3226,-410.6781 567.357,-402 721.0414,-377.7662 904.9427,-369.7517 994.6774,-367.1744"/>
<polygon fill="#000000" stroke="#000000" points="994.9858,-370.6673 1004.8856,-366.8931 994.793,-363.67 994.9858,-370.6673"/>
<text text-anchor="middle" x="637.357" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M304.6349,-438.3602C294.1851,-433.1866 284.3097,-426.2543 277.357,-417 235.4641,-361.2399 216.697,-315.3876 260.357,-261 302.8169,-208.1072 342.0883,-236.6842 409.357,-228 574.1448,-206.7264 1075.4744,-196.3594 1263.8148,-193.1373"/>
<polygon fill="#000000" stroke="#000000" points="1263.9494,-196.6356 1273.8886,-192.9667 1263.8307,-189.6366 1263.9494,-196.6356"/>
<text text-anchor="middle" x="306.357" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1049.5642,-347.9735C1049.6996,-336.1918 1049.8793,-320.5607 1050.0333,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="1053.5348,-307.043 1050.15,-297.0034 1046.5352,-306.9624 1053.5348,-307.043"/>
<text text-anchor="middle" x="1085.857" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1018.0238,-353.2955C976.2101,-334.5317 910.6814,-297.6587 940.357,-261 960.6947,-235.8764 1159.0103,-210.9773 1267.0375,-199.1369"/>
<polygon fill="#000000" stroke="#000000" points="1267.6376,-202.5924 1277.2009,-198.0323 1266.8812,-195.6334 1267.6376,-202.5924"/>
<text text-anchor="middle" x="976.857" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node30" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1145.357" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1145.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1084.6481,-354.8427C1098.1361,-349.1552 1112.7963,-341.0527 1123.357,-330 1129.5137,-323.5564 1134.0924,-315.1182 1137.4301,-306.9653"/>
<polygon fill="#000000" stroke="#000000" points="1140.81,-307.9099 1140.9084,-297.3155 1134.2247,-305.5362 1140.81,-307.9099"/>
<text text-anchor="middle" x="1169.857" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="830.357" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="830.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M854.0353,-435.8599C870.112,-424.8876 892.2154,-411.0603 913.357,-402 940.7069,-390.2791 972.8259,-381.5609 998.9809,-375.642"/>
<polygon fill="#000000" stroke="#000000" points="1000.0381,-378.9934 1009.0562,-373.4324 998.5385,-372.1559 1000.0381,-378.9934"/>
<text text-anchor="middle" x="974.357" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- consent_group -->
<g id="node21" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1550.357" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1550.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge31" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1372.6591,-177.2416C1408.1672,-162.8061 1462.4765,-140.7271 1501.7086,-124.7776"/>
<polygon fill="#000000" stroke="#000000" points="1503.3918,-127.8715 1511.3374,-120.8631 1500.7555,-121.3869 1503.3918,-127.8715"/>
<text text-anchor="middle" x="1505.857" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1266.357" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1266.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1275.119,-261.1379C1280.5396,-250.9338 1288.0396,-238.1838 1296.357,-228 1299.6702,-223.9433 1303.4506,-219.9368 1307.3347,-216.1532"/>
<polygon fill="#000000" stroke="#000000" points="1309.8833,-218.5631 1314.8361,-209.1971 1305.1236,-213.4303 1309.8833,-218.5631"/>
<text text-anchor="middle" x="1339.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node19" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2230.357" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2230.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2212.7396,-87.2158C2205.0795,-77.2687 2199.1208,-64.7461 2205.357,-54 2210.7235,-44.7524 2219.4566,-37.6797 2228.734,-32.3561"/>
<polygon fill="#000000" stroke="#000000" points="2230.3904,-35.4402 2237.7035,-27.7741 2227.2059,-29.2065 2230.3904,-35.4402"/>
<text text-anchor="middle" x="2261.857" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node20" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1467.357" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1467.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1436.2827,-261.44C1426.5778,-255.7491 1415.9141,-249.2807 1406.357,-243 1392.9824,-234.2106 1378.6288,-223.9138 1366.4222,-214.8825"/>
<polygon fill="#000000" stroke="#000000" points="1368.462,-212.0376 1358.3529,-208.8663 1364.2779,-217.6495 1368.462,-212.0376"/>
<text text-anchor="middle" x="1508.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge16" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1584.4647,-88.7229C1611.037,-76.8607 1649.1982,-61.5901 1684.357,-54 1786.525,-31.944 2101.8135,-22.0849 2221.5623,-19.066"/>
<polygon fill="#000000" stroke="#000000" points="2221.9489,-22.5576 2231.8592,-18.8112 2221.7756,-15.5597 2221.9489,-22.5576"/>
<text text-anchor="middle" x="1747.857" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1040.357" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1040.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1039.8366,-434.526C1039.7855,-424.8131 1040.0728,-412.7276 1041.357,-402 1041.6633,-399.4413 1042.071,-396.7972 1042.5407,-394.1579"/>
<polygon fill="#000000" stroke="#000000" points="1046.004,-394.691 1044.5759,-384.1928 1039.1456,-393.2902 1046.004,-394.691"/>
<text text-anchor="middle" x="1132.857" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_status -->
<g id="node23" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2430.357" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2430.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2404.3182,-88.1413C2387.9493,-77.8081 2366.2375,-64.5793 2346.357,-54 2333.2195,-47.009 2318.4734,-39.9986 2305.3685,-34.046"/>
<polygon fill="#000000" stroke="#000000" points="2306.719,-30.8158 2296.1626,-29.914 2303.8525,-37.202 2306.719,-30.8158"/>
<text text-anchor="middle" x="2427.857" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- diagnosis -->
<g id="node24" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1471.357" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1471.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1445.3914,-437.0507C1421.604,-422.4974 1389.6,-403.087 1386.357,-402 1335.2635,-384.874 1184.7639,-373.8256 1103.263,-368.9251"/>
<polygon fill="#000000" stroke="#000000" points="1103.3866,-365.4264 1093.1975,-368.3301 1102.9735,-372.4142 1103.3866,-365.4264"/>
<text text-anchor="middle" x="1455.857" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1486.4993,-435.4267C1491.5452,-429.5677 1497.1951,-423.0041 1502.357,-417 1513.8121,-403.6758 1598.5011,-313.1787 1605.357,-297 1617.3537,-268.6899 1630.6329,-251.1142 1610.357,-228 1597.1286,-212.9199 1484.2456,-202.1789 1407.5596,-196.5435"/>
<polygon fill="#000000" stroke="#000000" points="1407.6875,-193.0437 1397.4616,-195.8154 1407.184,-200.0256 1407.6875,-193.0437"/>
<text text-anchor="middle" x="1636.857" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2605.357" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2605.357" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2572.8924,-88.2357C2549.855,-76.9951 2517.9005,-62.7079 2488.357,-54 2429.6356,-36.692 2359.4882,-27.0285 2314.4536,-22.1706"/>
<polygon fill="#000000" stroke="#000000" points="2314.7135,-18.6788 2304.4041,-21.1215 2313.9866,-25.641 2314.7135,-18.6788"/>
<text text-anchor="middle" x="2596.857" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cytogenomic_file -->
<g id="node26" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1263.357" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1263.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1253.9973,-434.9503C1247.2513,-423.7436 1237.1027,-409.9984 1224.357,-402 1204.2478,-389.3809 1145.6163,-378.9813 1101.7216,-372.6589"/>
<polygon fill="#000000" stroke="#000000" points="1102.1478,-369.1844 1091.7576,-371.2565 1101.1722,-376.1161 1102.1478,-369.1844"/>
<text text-anchor="middle" x="1310.857" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node27" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1991.357" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1991.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1911.7197,-440.7011C1898.8966,-438.7642 1885.7636,-436.8063 1873.357,-435 1767.6814,-419.6145 1741.6178,-412.6151 1635.357,-402 1440.2265,-382.507 1207.4158,-371.9804 1103.7711,-367.9528"/>
<polygon fill="#000000" stroke="#000000" points="1103.6832,-364.4469 1093.5563,-367.5607 1103.4147,-371.4418 1103.6832,-364.4469"/>
<text text-anchor="middle" x="1840.357" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1975.3076,-434.7345C1947.5918,-404.4797 1887.5288,-344.3937 1823.357,-315 1780.7086,-295.4651 1760.5213,-319.4943 1719.357,-297 1700.3101,-286.5919 1701.5966,-276.4552 1686.357,-261 1671.3459,-245.7765 1670.7464,-237.0075 1651.357,-228 1609.6138,-208.6079 1487.9745,-199.1888 1408.6445,-194.9885"/>
<polygon fill="#000000" stroke="#000000" points="1408.3924,-191.471 1398.2261,-194.4538 1408.0336,-198.4618 1408.3924,-191.471"/>
<text text-anchor="middle" x="1937.357" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge41" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2071.3806,-440.7548C2221.3387,-417.1186 2532.7941,-364.5002 2568.357,-330 2601.858,-297.5 2570.1682,-268.5074 2593.357,-228 2626.6165,-169.9003 2675.3029,-184.6682 2701.357,-123 2714.441,-92.031 2700.5859,-68.7134 2670.357,-54 2639.0188,-38.7468 2413.5779,-25.4581 2314.6699,-20.2936"/>
<polygon fill="#000000" stroke="#000000" points="2314.826,-16.7971 2304.6587,-19.7761 2314.4646,-23.7877 2314.826,-16.7971"/>
<text text-anchor="middle" x="2679.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- generic_file -->
<g id="node28" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2451.357" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2451.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2390.8869,-445.956C2293.8789,-434.9095 2097.4093,-413.58 1930.357,-402 1618.1753,-380.3597 1242.7948,-370.3248 1104.212,-367.1598"/>
<polygon fill="#000000" stroke="#000000" points="1103.9448,-363.6529 1093.8683,-366.9263 1103.7868,-370.6512 1103.9448,-363.6529"/>
<text text-anchor="middle" x="2155.357" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2454.855,-434.7763C2462.7819,-387.3642 2475.9695,-261.5221 2400.357,-228 2377.6854,-217.9488 1644.7679,-199.4382 1408.7834,-193.725"/>
<polygon fill="#000000" stroke="#000000" points="1408.6739,-190.2215 1398.5923,-193.4788 1408.5048,-197.2194 1408.6739,-190.2215"/>
<text text-anchor="middle" x="2512.357" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge33" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2515.7436,-449.4104C2613.3068,-442.1835 2787.357,-421.5118 2787.357,-366 2787.357,-366 2787.357,-366 2787.357,-105 2787.357,-72.3099 2764.1841,-67.3785 2734.357,-54 2696.7469,-37.1306 2425.2568,-24.3604 2314.8573,-19.8099"/>
<polygon fill="#000000" stroke="#000000" points="2314.824,-16.3058 2304.6897,-19.3954 2314.5387,-23.3 2314.824,-16.3058"/>
<text text-anchor="middle" x="2840.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sequencing_file -->
<g id="node29" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="653.357" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="653.357" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M678.9018,-435.6797C697.1638,-424.1841 722.7628,-409.8206 747.357,-402 792.2917,-387.7113 921.5187,-375.8378 995.5534,-369.9641"/>
<polygon fill="#000000" stroke="#000000" points="995.9231,-373.446 1005.6192,-369.1755 995.3763,-366.4673 995.9231,-373.446"/>
<text text-anchor="middle" x="813.857" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1160.0554,-261.5173C1170.2897,-250.4004 1184.8425,-236.5407 1200.357,-228 1221.9808,-216.0961 1247.7268,-207.9805 1270.9702,-202.5172"/>
<polygon fill="#000000" stroke="#000000" points="1271.7604,-205.927 1280.7592,-200.3349 1270.2372,-199.0948 1271.7604,-205.927"/>
<text text-anchor="middle" x="1240.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- radiology_file -->
<g id="node31" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1801.357" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1801.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1778.3227,-261.7184C1761.5132,-250.0837 1737.6805,-235.5377 1714.357,-228 1659.2619,-210.1944 1501.7941,-199.874 1408.3899,-195.1502"/>
<polygon fill="#000000" stroke="#000000" points="1408.3257,-191.6428 1398.1644,-194.6424 1407.9784,-198.6341 1408.3257,-191.6428"/>
<text text-anchor="middle" x="1805.357" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node32" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1993.357" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1993.357" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1960.0989,-262.0079C1935.4492,-250.2718 1900.6676,-235.4793 1868.357,-228 1783.0478,-208.2525 1533.2949,-198.0316 1408.731,-194.0414"/>
<polygon fill="#000000" stroke="#000000" points="1408.6343,-190.5367 1398.5289,-193.7196 1408.4135,-197.5332 1408.6343,-190.5367"/>
<text text-anchor="middle" x="1992.857" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
