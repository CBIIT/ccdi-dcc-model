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
<svg width="2635pt" height="392pt"
 viewBox="0.00 0.00 2635.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2631.3431,-388 2631.3431,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1168.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1168.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node22" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1493.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1493.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1214.2184,-179.7195C1271.1866,-164.4696 1368.5726,-138.4001 1431.9365,-121.4381"/>
<polygon fill="#000000" stroke="#000000" points="1433.0477,-124.764 1441.8025,-118.797 1431.2375,-118.002 1433.0477,-124.764"/>
<text text-anchor="middle" x="1399.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node2" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="685.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="685.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M677.3346,-260.7509C673.9296,-249.8944 672.3505,-236.604 680.3431,-228 694.2723,-213.0055 963.8168,-200.1841 1096.2031,-194.7623"/>
<polygon fill="#000000" stroke="#000000" points="1096.414,-198.2567 1106.2637,-194.3537 1096.1299,-191.2625 1096.414,-198.2567"/>
<text text-anchor="middle" x="723.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1493.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1493.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M88.5911,-87.1072C97.0924,-75.349 109.9179,-60.907 125.3431,-54 186.8401,-26.4633 1213.8852,-19.4593 1446.6794,-18.2225"/>
<polygon fill="#000000" stroke="#000000" points="1446.8623,-21.7216 1456.8439,-18.1695 1446.8257,-14.7217 1446.8623,-21.7216"/>
<text text-anchor="middle" x="187.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1032.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1032.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1006.9489,-261.4112C995.6149,-251.4135 986.5773,-238.7777 995.3431,-228 1008.4252,-211.9154 1055.9198,-202.78 1097.8415,-197.7396"/>
<polygon fill="#000000" stroke="#000000" points="1098.2567,-201.215 1107.7959,-196.6048 1097.4638,-194.26 1098.2567,-201.215"/>
<text text-anchor="middle" x="1074.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="243.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="243.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M246.1611,-86.7431C248.9622,-75.2993 254.4931,-61.3661 265.3431,-54 290.2194,-37.1115 1224.5548,-22.0364 1446.4286,-18.6898"/>
<polygon fill="#000000" stroke="#000000" points="1446.8029,-22.1846 1456.7492,-18.5348 1446.6978,-15.1854 1446.8029,-22.1846"/>
<text text-anchor="middle" x="321.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="394.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="394.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge31" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M385.414,-87.1544C381.3222,-76.1748 379.0138,-62.6048 387.3431,-54 406.0481,-34.6763 1238.6572,-21.6084 1446.6427,-18.6418"/>
<polygon fill="#000000" stroke="#000000" points="1446.968,-22.1376 1456.9174,-18.4962 1446.8688,-15.1383 1446.968,-22.1376"/>
<text text-anchor="middle" x="438.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="429.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="429.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M413.9743,-348.7087C396.0906,-326.4207 371.5109,-287.4012 392.3431,-261 435.4614,-206.3552 911.0193,-194.9763 1095.6569,-192.6152"/>
<polygon fill="#000000" stroke="#000000" points="1095.8558,-196.1131 1105.8121,-192.4907 1095.7699,-189.1137 1095.8558,-196.1131"/>
<text text-anchor="middle" x="436.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2067.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2067.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M483.4113,-363.0474C617.5666,-355.6433 956.632,-336.4207 980.3431,-330 994.7321,-326.1037 995.8673,-318.56 1010.3431,-315 1114.589,-289.3634 1869.6046,-308.4601 1976.3431,-297 1990.2517,-295.5067 2005.198,-292.9546 2018.8767,-290.234"/>
<polygon fill="#000000" stroke="#000000" points="2019.9648,-293.5834 2029.0517,-288.1355 2018.5508,-286.7276 2019.9648,-293.5834"/>
<text text-anchor="middle" x="1054.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node8" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1894.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1894.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1838.6697,-267.0948C1815.9942,-261.2607 1789.8709,-253.2517 1767.3431,-243 1756.2352,-237.9451 1755.927,-231.8408 1744.3431,-228 1697.7026,-212.5355 1384.325,-199.6327 1240.3859,-194.4461"/>
<polygon fill="#000000" stroke="#000000" points="1240.4399,-190.9459 1230.3211,-194.0861 1240.1896,-197.9414 1240.4399,-190.9459"/>
<text text-anchor="middle" x="1826.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- survival -->
<g id="node9" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="66.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="66.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M58.8441,-261.1178C55.5498,-250.1236 54.0659,-236.5511 62.3431,-228 71.353,-218.6921 850.917,-199.4993 1095.6744,-193.6977"/>
<polygon fill="#000000" stroke="#000000" points="1095.9719,-197.1917 1105.8863,-193.456 1095.8063,-190.1937 1095.9719,-197.1917"/>
<text text-anchor="middle" x="101.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node11" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="150.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="150.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M155.165,-347.7874C162.5503,-323.7285 179.0934,-281.9594 209.3431,-261 288.446,-206.1914 327.5948,-237.669 423.3431,-228 669.1361,-203.1789 962.3356,-195.3594 1095.777,-192.9862"/>
<polygon fill="#000000" stroke="#000000" points="1095.9394,-196.484 1105.8774,-192.8116 1095.8183,-189.485 1095.9394,-196.484"/>
<text text-anchor="middle" x="295.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge39" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M86.8045,-351.3788C57.9194,-341.2169 26.4388,-324.3989 9.3431,-297 -9.9104,-266.1428 19.7609,-241.9676 53.3431,-228 315.9921,-118.7584 1230.7858,-39.2128 1447.1953,-21.6468"/>
<polygon fill="#000000" stroke="#000000" points="1447.5743,-25.1277 1457.26,-20.8337 1447.0106,-18.1504 1447.5743,-25.1277"/>
<text text-anchor="middle" x="320.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M246.9205,-357.7387C283.9512,-354.6171 326.6036,-351.0776 365.3431,-348 560.3902,-332.5046 608.8813,-323.8396 804.3431,-315 1064.5523,-303.2322 1717.3113,-324.3824 1976.3431,-297 1990.2541,-295.5295 2005.2012,-292.9847 2018.8799,-290.2638"/>
<polygon fill="#000000" stroke="#000000" points="2019.9686,-293.613 2029.0547,-288.1638 2018.5536,-286.7575 2019.9686,-293.613"/>
<text text-anchor="middle" x="890.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2033.6376,-267.1075C1997.4829,-254.9322 1938.1329,-236.6107 1885.3431,-228 1762.8692,-208.0228 1397.1124,-197.3424 1240.6463,-193.5829"/>
<polygon fill="#000000" stroke="#000000" points="1240.728,-190.084 1230.6477,-193.3453 1240.5616,-197.082 1240.728,-190.084"/>
<text text-anchor="middle" x="1986.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2309.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2309.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2111.2873,-276.7209C2188.5844,-272.2592 2342.2658,-261.1888 2358.3431,-243 2368.9781,-230.9683 2355.9589,-217.9197 2340.6781,-208.0331"/>
<polygon fill="#000000" stroke="#000000" points="2342.4697,-205.0265 2332.092,-202.8925 2338.8739,-211.0323 2342.4697,-205.0265"/>
<text text-anchor="middle" x="2397.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2163.3431" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2163.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2063.0104,-260.9358C2061.5552,-250.4138 2061.7094,-237.4093 2068.3431,-228 2074.1075,-219.8239 2093.4166,-211.8251 2113.1349,-205.4518"/>
<polygon fill="#000000" stroke="#000000" points="2114.2741,-208.763 2122.7901,-202.46 2112.2022,-202.0767 2114.2741,-208.763"/>
<text text-anchor="middle" x="2104.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- laboratory_test -->
<g id="node13" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="867.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="867.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M786.6301,-362.8445C687.817,-357.0888 529.0392,-341.0641 492.3431,-297 482.1042,-284.7052 482.1063,-273.2966 492.3431,-261 530.4635,-215.2095 929.3944,-198.72 1095.9354,-193.802"/>
<polygon fill="#000000" stroke="#000000" points="1096.1906,-197.2962 1106.085,-193.5082 1095.9879,-190.2991 1096.1906,-197.2962"/>
<text text-anchor="middle" x="557.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M933.2495,-355.2671C1017.7206,-341.6839 1159.5567,-319.5062 1212.3431,-315 1550.7621,-286.1105 1638.7245,-334.0899 1976.3431,-297 1990.2479,-295.4725 2005.1931,-292.9093 2018.8719,-290.1892"/>
<polygon fill="#000000" stroke="#000000" points="2019.959,-293.5388 2029.0471,-288.093 2018.5465,-286.6828 2019.959,-293.5388"/>
<text text-anchor="middle" x="1277.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1336.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1336.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1352.0819,-87.4699C1362.5996,-76.6161 1377.2346,-63.0678 1392.3431,-54 1410.3376,-43.2002 1432.0708,-34.9307 1450.76,-29.0574"/>
<polygon fill="#000000" stroke="#000000" points="1451.9372,-32.3583 1460.5024,-26.1222 1449.9178,-25.6559 1451.9372,-32.3583"/>
<text text-anchor="middle" x="1440.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- genetic_analysis -->
<g id="node15" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1197.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1197.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1114.5994,-359.9985C996.8017,-351.2744 794.2288,-335.5284 788.3431,-330 777.5309,-319.844 784.4574,-311.7922 783.3431,-297 782.1413,-281.0452 773.0757,-273.2711 783.3431,-261 822.4176,-214.3 995.6914,-199.1682 1095.9613,-194.2934"/>
<polygon fill="#000000" stroke="#000000" points="1096.1984,-197.7863 1106.0254,-193.8266 1095.8739,-190.7938 1096.1984,-197.7863"/>
<text text-anchor="middle" x="853.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1250.5373,-351.5744C1297.8618,-339.4341 1369.161,-322.836 1432.3431,-315 1672.414,-285.226 1736.0082,-324.561 1976.3431,-297 1990.2405,-295.4063 2005.1833,-292.8219 2018.8621,-290.1025"/>
<polygon fill="#000000" stroke="#000000" points="2019.9474,-293.4527 2029.0378,-288.0109 2018.5379,-286.5961 2019.9474,-293.4527"/>
<text text-anchor="middle" x="1502.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge14" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2304.6808,-174.1805C2297.7176,-150.9504 2282.4289,-110.5202 2255.3431,-87 2221.5944,-57.6939 2204.2006,-62.6224 2160.3431,-54 2041.2454,-30.5853 1670.9422,-21.3922 1539.8872,-18.8186"/>
<polygon fill="#000000" stroke="#000000" points="1539.8415,-15.3171 1529.776,-18.6239 1539.7067,-22.3158 1539.8415,-15.3171"/>
<text text-anchor="middle" x="2306.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2292.5334,-206.704C2278.4488,-218.2616 2257.3292,-233.8827 2236.3431,-243 2199.4397,-259.0325 2154.8154,-268.1473 2120.6905,-273.1921"/>
<polygon fill="#000000" stroke="#000000" points="2119.8728,-269.7726 2110.4572,-274.6303 2120.847,-276.7045 2119.8728,-269.7726"/>
<text text-anchor="middle" x="2285.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- generic_file -->
<g id="node17" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2496.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2496.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2495.8499,-347.5767C2494.5694,-336.6546 2491.1216,-323.3565 2482.3431,-315 2455.6323,-289.5731 2436.4929,-308.1578 2401.3431,-297 2325.5814,-272.9505 2314.0022,-244.9497 2236.3431,-228 2187.8142,-217.4082 1472.8512,-199.339 1240.6141,-193.7195"/>
<polygon fill="#000000" stroke="#000000" points="1240.6621,-190.2197 1230.5805,-193.4772 1240.493,-197.2177 1240.6621,-190.2197"/>
<text text-anchor="middle" x="2454.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2504.6678,-348.1C2511.9403,-330.8051 2521.3431,-303.6732 2521.3431,-279 2521.3431,-279 2521.3431,-279 2521.3431,-105 2521.3431,-55.0708 1741.224,-26.1097 1540.159,-19.4745"/>
<polygon fill="#000000" stroke="#000000" points="1540.0394,-15.9688 1529.9302,-19.1398 1539.8104,-22.9651 1540.0394,-15.9688"/>
<text text-anchor="middle" x="2574.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2446.125,-354.3804C2424.1691,-348.4317 2398.4384,-340.2588 2376.3431,-330 2365.274,-324.8606 2364.8007,-319.2026 2353.3431,-315 2311.9204,-299.8063 2191.8759,-288.4638 2121.1679,-282.8754"/>
<polygon fill="#000000" stroke="#000000" points="2121.3502,-279.379 2111.1088,-282.0928 2120.8072,-286.358 2121.3502,-279.379"/>
<text text-anchor="middle" x="2429.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1663.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1663.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1679.6831,-348.2343C1691.6341,-336.5344 1708.9189,-322.1098 1727.3431,-315 1785.9267,-292.3929 1947.5898,-308.386 2009.3431,-297 2014.145,-296.1146 2019.1077,-294.9605 2024.0159,-293.6638"/>
<polygon fill="#000000" stroke="#000000" points="2025.2825,-296.9426 2033.945,-290.8425 2023.3691,-290.2091 2025.2825,-296.9426"/>
<text text-anchor="middle" x="1788.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node19" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2060.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2060.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2033.2391,-87.6321C2013.5534,-75.9567 1985.8302,-61.3976 1959.3431,-54 1881.4082,-32.2336 1642.0681,-22.5321 1540.1173,-19.3078"/>
<polygon fill="#000000" stroke="#000000" points="1539.9262,-15.8003 1529.8228,-18.9896 1539.7099,-22.797 1539.9262,-15.8003"/>
<text text-anchor="middle" x="2065.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1847.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1847.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1848.6138,-347.9406C1850.4014,-336.73 1854.5959,-322.9839 1864.3431,-315 1889.4619,-294.4253 1977.602,-303.8389 2009.3431,-297 2013.994,-295.9979 2018.8074,-294.7899 2023.5815,-293.4795"/>
<polygon fill="#000000" stroke="#000000" points="2024.6275,-296.8205 2033.2611,-290.6795 2022.6824,-290.0962 2024.6275,-296.8205"/>
<text text-anchor="middle" x="1935.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- synonym -->
<g id="node21" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1517.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1517.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1491.3018,-350.3867C1470.0425,-338.4716 1438.8052,-322.8156 1409.3431,-315 1384.3523,-308.3705 1195.6992,-315.2085 1177.3431,-297 1157.542,-277.3581 1158.1317,-243.8768 1161.8491,-220.0029"/>
<polygon fill="#000000" stroke="#000000" points="1165.3021,-220.5764 1163.6489,-210.1113 1158.4152,-219.3232 1165.3021,-220.5764"/>
<text text-anchor="middle" x="1219.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1531.3243,-348.6493C1541.9934,-336.8201 1557.8073,-322.0664 1575.3431,-315 1616.7111,-298.3301 1944.0663,-327.7799 1976.3431,-297 1993.786,-280.3661 1980.2308,-267.077 1981.3431,-243 1989.6281,-63.661 1792.3111,-117.3868 1624.3431,-54 1595.7058,-43.193 1562.4388,-34.0916 1536.595,-27.7437"/>
<polygon fill="#000000" stroke="#000000" points="1537.2656,-24.3052 1526.7238,-25.3638 1535.6249,-31.1102 1537.2656,-24.3052"/>
<text text-anchor="middle" x="2021.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1540.6774,-349.6188C1559.1739,-337.6172 1586.1761,-322.2137 1612.3431,-315 1697.4801,-291.5296 1922.3503,-312.212 2009.3431,-297 2014.153,-296.1589 2019.1208,-295.0331 2024.0319,-293.753"/>
<polygon fill="#000000" stroke="#000000" points="2025.2905,-297.0346 2033.9644,-290.9507 2023.3897,-290.2976 2025.2905,-297.0346"/>
<text text-anchor="middle" x="1654.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge19" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1493.3431,-86.9735C1493.3431,-75.1918 1493.3431,-59.5607 1493.3431,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1496.8432,-46.0033 1493.3431,-36.0034 1489.8432,-46.0034 1496.8432,-46.0033"/>
<text text-anchor="middle" x="1556.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment -->
<g id="node23" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1329.3431" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1329.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1300.1873,-263.245C1274.0217,-249.1058 1235.4352,-228.2547 1206.7598,-212.7593"/>
<polygon fill="#000000" stroke="#000000" points="1208.2878,-209.6067 1197.8262,-207.9318 1204.9599,-215.7651 1208.2878,-209.6067"/>
<text text-anchor="middle" x="1305.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2167.1956,-173.7295C2172.6085,-142.3094 2177.9036,-79.01 2139.3431,-54 2114.2896,-37.7505 1685.0056,-23.6537 1540.4296,-19.3479"/>
<polygon fill="#000000" stroke="#000000" points="1540.2204,-15.8403 1530.1213,-19.0432 1540.0135,-22.8372 1540.2204,-15.8403"/>
<text text-anchor="middle" x="2210.8431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2158.8946,-210.3155C2155.5411,-220.9265 2150.0032,-233.9365 2141.3431,-243 2133.1751,-251.5486 2122.5547,-258.3323 2111.9211,-263.5988"/>
<polygon fill="#000000" stroke="#000000" points="2110.2749,-260.5029 2102.6343,-267.8427 2113.1844,-266.8696 2110.2749,-260.5029"/>
<text text-anchor="middle" x="2191.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1490.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1490.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1452.8168,-262.6964C1426.2739,-251.6672 1389.6292,-237.4432 1356.3431,-228 1316.454,-216.6836 1270.7897,-207.8465 1234.455,-201.7601"/>
<polygon fill="#000000" stroke="#000000" points="1234.9022,-198.2868 1224.4666,-200.1166 1233.7657,-205.1939 1234.9022,-198.2868"/>
<text text-anchor="middle" x="1468.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node26" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1698.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1698.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1643.3707,-263.5687C1622.8416,-257.5286 1599.4076,-250.3025 1578.3431,-243 1561.1877,-237.0527 1557.996,-232.2492 1540.3431,-228 1485.0877,-214.6994 1331.2565,-202.7442 1239.6368,-196.5215"/>
<polygon fill="#000000" stroke="#000000" points="1239.8163,-193.0257 1229.6038,-195.846 1239.3461,-200.0099 1239.8163,-193.0257"/>
<text text-anchor="middle" x="1661.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sequencing_file -->
<g id="node27" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2038.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2038.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2021.5975,-348.3317C2014.2961,-338.4209 2008.5723,-325.896 2014.3431,-315 2017.815,-308.4448 2023.0745,-302.8619 2028.9548,-298.1895"/>
<polygon fill="#000000" stroke="#000000" points="2031.0683,-300.9823 2037.2486,-292.3768 2027.0507,-295.25 2031.0683,-300.9823"/>
<text text-anchor="middle" x="2080.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- methylation_array_file -->
<g id="node28" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2255.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2255.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2211.8461,-349.3204C2198.3136,-343.6709 2183.4987,-337.0046 2170.3431,-330 2159.5709,-324.2644 2158.051,-320.855 2147.3431,-315 2134.8841,-308.1875 2120.889,-301.5621 2108.1293,-295.8913"/>
<polygon fill="#000000" stroke="#000000" points="2109.2234,-292.5499 2098.6585,-291.7534 2106.4208,-298.9644 2109.2234,-292.5499"/>
<text text-anchor="middle" x="2261.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
