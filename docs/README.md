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
<svg width="3305pt" height="392pt"
 viewBox="0.00 0.00 3305.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3300.9954,-388 3300.9954,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="300.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="300.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M81.8475,-351.1163C108.2378,-338.1049 144.8267,-320.4611 159.9954,-315 176.9061,-308.9117 218.574,-298.4707 252.256,-290.3959"/>
<polygon fill="#000000" stroke="#000000" points="253.5008,-293.6973 262.4163,-287.9734 251.8772,-286.8882 253.5008,-293.6973"/>
<text text-anchor="middle" x="202.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1572.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1572.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M64.6853,-348.1977C83.1962,-323.7987 120.1069,-280.7505 162.9954,-261 232.0073,-229.2194 260.3807,-265.3549 332.9954,-243 346.4881,-238.8462 347.3549,-231.6396 360.9954,-228 470.6512,-198.7409 1255.6261,-193.2306 1500.3382,-192.2205"/>
<polygon fill="#000000" stroke="#000000" points="1500.5591,-195.7197 1510.545,-192.1797 1500.531,-188.7198 1500.5591,-195.7197"/>
<text text-anchor="middle" x="205.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node26" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1479.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1479.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M43.3378,-348.1344C35.7743,-330.8644 25.9954,-303.7498 25.9954,-279 25.9954,-279 25.9954,-279 25.9954,-105 25.9954,-32.7806 1184.0704,-20.1729 1433.1616,-18.2964"/>
<polygon fill="#000000" stroke="#000000" points="1433.3523,-21.7952 1443.3264,-18.2221 1433.301,-14.7954 1433.3523,-21.7952"/>
<text text-anchor="middle" x="68.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line -->
<g id="node12" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="177.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="177.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M263.4845,-269.409C250.7025,-266.3907 236.2854,-263.2593 222.9954,-261 187.0684,-254.8924 84.3088,-270.1461 59.9954,-243 55.5476,-238.034 56.0283,-233.3579 59.9954,-228 61.1288,-226.4693 97.4523,-215.5197 129.4995,-206.0939"/>
<polygon fill="#000000" stroke="#000000" points="130.6536,-209.4029 139.2642,-203.2297 128.6833,-202.6859 130.6536,-209.4029"/>
<text text-anchor="middle" x="96.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M334.546,-267.2823C340.9804,-265.1268 347.6802,-262.9451 353.9954,-261 382.6435,-252.1765 391.0887,-253.9445 418.9954,-243 432.5046,-237.7019 433.9524,-231.6556 447.9954,-228 549.2011,-201.6542 1267.7874,-194.1968 1500.4786,-192.4606"/>
<polygon fill="#000000" stroke="#000000" points="1500.5565,-195.9603 1510.5305,-192.387 1500.5051,-188.9605 1500.5565,-195.9603"/>
<text text-anchor="middle" x="484.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node29" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="379.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="379.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M288.2016,-261.3122C282.3743,-250.9237 278.1412,-237.9272 284.9954,-228 292.0541,-217.7766 320.1122,-207.9034 343.9205,-201.0907"/>
<polygon fill="#000000" stroke="#000000" points="345.0821,-204.4011 353.7903,-198.3663 343.2195,-197.6534 345.0821,-204.4011"/>
<text text-anchor="middle" x="321.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_other -->
<g id="node3" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2353.9954" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2353.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2295.8332,-265.6005C2242.7609,-253.881 2162.0125,-237.318 2090.9954,-228 1932.8584,-207.2512 1745.8881,-197.987 1645.4696,-194.2435"/>
<polygon fill="#000000" stroke="#000000" points="1645.5555,-190.7444 1635.4344,-193.8771 1645.3,-197.7397 1645.5555,-190.7444"/>
<text text-anchor="middle" x="2247.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- exposure -->
<g id="node4" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2511.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2511.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2474.113,-266.1934C2435.9512,-253.9351 2375.1294,-236.141 2320.9954,-228 2192.2826,-208.6434 1807.3256,-197.5431 1645.7038,-193.6253"/>
<polygon fill="#000000" stroke="#000000" points="1645.4673,-190.1187 1635.3861,-193.3776 1645.2992,-197.1167 1645.4673,-190.1187"/>
<text text-anchor="middle" x="2433.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="821.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="821.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M801.4418,-348.3666C786.3487,-336.5662 764.7627,-321.9666 742.9954,-315 660.5767,-288.622 439.0266,-313.0729 353.9954,-297 350.3431,-296.3096 346.599,-295.4237 342.8721,-294.4161"/>
<polygon fill="#000000" stroke="#000000" points="343.7046,-291.0122 333.1217,-291.5154 341.7085,-297.7216 343.7046,-291.0122"/>
<text text-anchor="middle" x="839.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- genetic_analysis -->
<g id="node6" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1468.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1468.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1382.107,-363.3972C1301.3648,-359.7324 1178.1017,-350.9532 1072.9954,-330 1051.076,-325.6303 1047.0431,-318.6679 1024.9954,-315 877.8529,-290.5211 500.8268,-323.2806 353.9954,-297 350.2857,-296.336 346.4837,-295.4601 342.7025,-294.4518"/>
<polygon fill="#000000" stroke="#000000" points="343.4016,-291.0087 332.8195,-291.5278 341.4157,-297.7211 343.4016,-291.0087"/>
<text text-anchor="middle" x="1142.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1529.3603,-352.9219C1555.7563,-344.5104 1577.5643,-331.9537 1561.9954,-315 1530.1651,-280.3387 1382.8256,-331.6613 1350.9954,-297 1340.1732,-285.2153 1341.5081,-273.8838 1350.9954,-261 1369.9706,-235.2317 1450.6201,-214.9116 1509.2562,-203.1774"/>
<polygon fill="#000000" stroke="#000000" points="1510.0562,-206.5873 1519.1955,-201.2277 1508.7087,-199.7182 1510.0562,-206.5873"/>
<text text-anchor="middle" x="1420.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2667.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2667.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2622.8919,-263.6008C2585.3977,-251.5547 2530.3838,-235.6129 2480.9954,-228 2320.6027,-203.2766 1831.5696,-195.0404 1645.7138,-192.7592"/>
<polygon fill="#000000" stroke="#000000" points="1645.5436,-189.257 1635.5021,-192.6361 1645.4591,-196.2565 1645.5436,-189.257"/>
<text text-anchor="middle" x="2615.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="817.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="817.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M812.7561,-86.6133C810.8625,-75.705 810.8746,-62.4085 818.9954,-54 840.3148,-31.9254 1286.329,-21.6238 1433.4067,-18.8182"/>
<polygon fill="#000000" stroke="#000000" points="1433.5373,-22.3164 1443.4697,-18.629 1433.4057,-15.3177 1433.5373,-22.3164"/>
<text text-anchor="middle" x="875.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_surgery -->
<g id="node9" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2869.9954" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2869.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2824.6652,-263.0045C2788.2443,-250.9591 2735.5087,-235.3144 2687.9954,-228 2585.7207,-212.2555 1877.128,-197.7092 1645.8355,-193.3334"/>
<polygon fill="#000000" stroke="#000000" points="1645.5774,-189.828 1635.5132,-193.1389 1645.4455,-196.8268 1645.5774,-189.828"/>
<text text-anchor="middle" x="2831.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- methylation_array_file -->
<g id="node10" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="237.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="237.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M241.7751,-347.8484C244.535,-337.5478 249.035,-324.7978 255.9954,-315 259.5588,-309.9839 264.0072,-305.3002 268.7097,-301.0788"/>
<polygon fill="#000000" stroke="#000000" points="271.2726,-303.5014 276.7522,-294.4336 266.8138,-298.1051 271.2726,-303.5014"/>
<text text-anchor="middle" x="347.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- family_relationship -->
<g id="node11" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="462.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="462.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M493.5311,-261.8553C503.6397,-256.0248 514.8858,-249.3698 524.9954,-243 535.0079,-236.6913 535.7498,-231.6861 546.9954,-228 636.7646,-198.5752 1281.5331,-193.1967 1500.4724,-192.2171"/>
<polygon fill="#000000" stroke="#000000" points="1500.5875,-195.7168 1510.5723,-192.1737 1500.5573,-188.7168 1500.5875,-195.7168"/>
<text text-anchor="middle" x="626.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M180.3774,-210.1643C182.6816,-220.9889 187.1921,-234.2756 195.9954,-243 204.4989,-251.4273 229.4824,-260.1546 252.9457,-266.9055"/>
<polygon fill="#000000" stroke="#000000" points="252.283,-270.3542 262.8558,-269.6711 254.1646,-263.6118 252.283,-270.3542"/>
<text text-anchor="middle" x="236.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge40" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M225.2703,-186.6288C258.2481,-182.9344 303.2858,-177.9935 342.9954,-174 589.0178,-149.2582 662.5694,-201.6361 896.9954,-123 925.7599,-113.3512 926.6808,-97.8986 954.9954,-87 1031.7161,-57.4693 1055.6147,-65.632 1136.9954,-54 1242.7704,-38.8812 1367.7495,-27.3473 1433.7605,-21.7469"/>
<polygon fill="#000000" stroke="#000000" points="1434.1651,-25.2253 1443.8365,-20.8993 1433.5783,-18.2499 1434.1651,-25.2253"/>
<text text-anchor="middle" x="995.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="628.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="628.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M657.8427,-264.3716C683.4313,-252.1887 722.1965,-235.6421 757.9954,-228 829.364,-212.7647 1314.0769,-198.7268 1500.3147,-193.8334"/>
<polygon fill="#000000" stroke="#000000" points="1500.6475,-197.326 1510.5526,-193.5657 1500.4645,-190.3284 1500.6475,-197.326"/>
<text text-anchor="middle" x="797.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="644.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="644.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M633.4564,-348.0842C624.9069,-336.476 612.142,-322.22 596.9954,-315 548.1166,-291.7006 407.0568,-307.7931 353.9954,-297 350.353,-296.2591 346.6159,-295.3378 342.8936,-294.3065"/>
<polygon fill="#000000" stroke="#000000" points="343.7353,-290.9047 333.1506,-291.368 341.714,-297.6065 343.7353,-290.9047"/>
<text text-anchor="middle" x="677.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node15" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="823.9954" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="823.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M830.6459,-260.866C835.9102,-249.3194 844.4813,-235.2211 856.9954,-228 884.5261,-212.1137 1324.1424,-198.6553 1500.5658,-193.8677"/>
<polygon fill="#000000" stroke="#000000" points="1500.8884,-197.3603 1510.7904,-193.5919 1500.6996,-190.3629 1500.8884,-197.3603"/>
<text text-anchor="middle" x="958.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_status -->
<g id="node16" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1114.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1114.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge44" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1125.9988,-86.7751C1133.9406,-75.3448 1145.7505,-61.4146 1159.9954,-54 1206.4108,-29.8402 1356.0493,-21.764 1433.1326,-19.168"/>
<polygon fill="#000000" stroke="#000000" points="1433.6263,-22.6541 1443.5095,-18.837 1433.403,-15.6577 1433.6263,-22.6541"/>
<text text-anchor="middle" x="1216.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- study_personnel -->
<g id="node17" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1289.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1289.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1281.3418,-87.0723C1277.5377,-76.3368 1275.4405,-63.0606 1282.9954,-54 1301.7818,-31.4694 1381.401,-22.9996 1433.4905,-19.8433"/>
<polygon fill="#000000" stroke="#000000" points="1433.7271,-23.3356 1443.5151,-19.2803 1433.3346,-16.3467 1433.7271,-23.3356"/>
<text text-anchor="middle" x="1352.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1770.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1770.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1695.5888,-358.778C1656.8744,-355.2228 1608.9381,-351.0556 1565.9954,-348 1492.7383,-342.7873 1305.7968,-352.8372 1235.9954,-330 1224.3964,-326.2051 1224.6564,-318.5999 1212.9954,-315 1121.7777,-286.8403 448.0164,-313.5438 353.9954,-297 350.2838,-296.3469 346.4805,-295.4786 342.6983,-294.4753"/>
<polygon fill="#000000" stroke="#000000" points="343.3957,-291.032 332.814,-291.5592 341.4149,-297.7459 343.3957,-291.032"/>
<text text-anchor="middle" x="1301.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1813.6909,-350.5577C1838.0291,-339.4726 1866.8176,-322.031 1882.9954,-297 1899.7269,-271.1122 1910.5248,-250.9928 1889.9954,-228 1873.9607,-210.0413 1733.4858,-199.8709 1644.9975,-195.1934"/>
<polygon fill="#000000" stroke="#000000" points="1644.9095,-191.6843 1634.7422,-194.6635 1644.5482,-198.675 1644.9095,-191.6843"/>
<text text-anchor="middle" x="1965.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_response -->
<g id="node19" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1075.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1075.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1067.9807,-260.7451C1064.5733,-249.8865 1062.994,-236.5958 1070.9954,-228 1085.3922,-212.5338 1364.7152,-199.8842 1500.3316,-194.6267"/>
<polygon fill="#000000" stroke="#000000" points="1500.7729,-198.1124 1510.6311,-194.2309 1500.504,-191.1176 1500.7729,-198.1124"/>
<text text-anchor="middle" x="1153.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- consent_group -->
<g id="node20" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1572.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1572.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge34" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1554.1754,-87.3943C1539.9834,-74.1179 1520.3829,-55.7818 1504.8937,-41.292"/>
<polygon fill="#000000" stroke="#000000" points="1506.9129,-38.3881 1497.2191,-34.1125 1502.1308,-43.5 1506.9129,-38.3881"/>
<text text-anchor="middle" x="1595.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge31" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1572.9954,-173.9735C1572.9954,-162.1918 1572.9954,-146.5607 1572.9954,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1576.4955,-133.0033 1572.9954,-123.0034 1569.4955,-133.0034 1576.4955,-133.0033"/>
<text text-anchor="middle" x="1623.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2076.9954" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2076.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1980.6991,-357.5874C1943.6079,-354.4391 1900.841,-350.9207 1861.9954,-348 1642.1277,-331.4685 1587.2877,-324.2947 1366.9954,-315 1254.5221,-310.2545 464.8964,-316.332 353.9954,-297 350.2828,-296.3528 346.4787,-295.4886 342.6961,-294.4881"/>
<polygon fill="#000000" stroke="#000000" points="343.3925,-291.0446 332.811,-291.5763 341.4145,-297.7593 343.3925,-291.0446"/>
<text text-anchor="middle" x="1707.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2075.1682,-347.9599C2071.7302,-324.0965 2062.0085,-282.5482 2034.9954,-261 1976.2239,-214.1185 1760.2543,-198.9518 1645.6102,-194.1521"/>
<polygon fill="#000000" stroke="#000000" points="1645.6468,-190.6508 1635.5139,-193.7453 1645.3649,-197.6451 1645.6468,-190.6508"/>
<text text-anchor="middle" x="2145.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2182.7781,-361.707C2415.0697,-351.767 2951.3089,-325.8083 2977.9954,-297 2988.8686,-285.2623 2986.3224,-274.6624 2977.9954,-261 2948.8162,-213.1248 2820.5463,-164.6669 1957.9954,-54 1800.5069,-33.7939 1612.2622,-23.7103 1526.5816,-19.8843"/>
<polygon fill="#000000" stroke="#000000" points="1526.5494,-16.3796 1516.4056,-19.4379 1526.2426,-23.3729 1526.5494,-16.3796"/>
<text text-anchor="middle" x="2973.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1089.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1089.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1040.3272,-358.2217C1009.591,-352.479 969.7005,-343.3241 935.9954,-330 923.5889,-325.0955 922.8246,-318.6588 909.9954,-315 791.1153,-281.0958 475.621,-319.1173 353.9954,-297 350.2876,-296.3257 346.4869,-295.4427 342.7065,-294.4296"/>
<polygon fill="#000000" stroke="#000000" points="343.4074,-290.9868 332.8249,-291.4981 341.4165,-297.6977 343.4074,-290.9868"/>
<text text-anchor="middle" x="980.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1133.6454,-354.9824C1151.444,-349.2518 1171.6384,-341.0806 1187.9954,-330 1222.1288,-306.8772 1214.9018,-282.6378 1249.9954,-261 1292.1222,-235.0257 1424.2936,-212.708 1505.9246,-200.9252"/>
<polygon fill="#000000" stroke="#000000" points="1506.7051,-204.3493 1516.1103,-199.4717 1505.7161,-197.4195 1506.7051,-204.3493"/>
<text text-anchor="middle" x="1294.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1572.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1572.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1572.9954,-260.9735C1572.9954,-249.1918 1572.9954,-233.5607 1572.9954,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1576.4955,-220.0033 1572.9954,-210.0034 1569.4955,-220.0034 1576.4955,-220.0033"/>
<text text-anchor="middle" x="1631.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment_radiation -->
<g id="node25" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1768.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1768.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1747.1331,-261.1822C1732.9664,-250.3527 1713.7245,-236.9362 1694.9954,-228 1675.4693,-218.6835 1653.0209,-211.2254 1632.7466,-205.5677"/>
<polygon fill="#000000" stroke="#000000" points="1633.5573,-202.1613 1622.9907,-202.9347 1631.7333,-208.9195 1633.5573,-202.1613"/>
<text text-anchor="middle" x="1802.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- study_funding -->
<g id="node27" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1747.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1747.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1724.2343,-87.6737C1707.7956,-76.4777 1684.9994,-62.4671 1662.9954,-54 1618.2466,-36.7809 1564.0375,-27.437 1526.2845,-22.6189"/>
<polygon fill="#000000" stroke="#000000" points="1526.4441,-19.1126 1516.0941,-21.3772 1525.5973,-26.0612 1526.4441,-19.1126"/>
<text text-anchor="middle" x="1753.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node28" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1905.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1905.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge18" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1883.587,-88.0378C1866.9551,-76.3965 1843.2255,-61.708 1819.9954,-54 1766.7527,-36.3334 1606.7849,-25.1296 1526.7143,-20.4759"/>
<polygon fill="#000000" stroke="#000000" points="1526.6127,-16.9644 1516.4294,-19.8886 1526.2136,-23.9531 1526.6127,-16.9644"/>
<text text-anchor="middle" x="1902.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M375.1733,-209.9779C371.6875,-220.4693 366.1415,-233.4719 357.9954,-243 352.594,-249.3176 345.8031,-254.9005 338.8091,-259.6701"/>
<polygon fill="#000000" stroke="#000000" points="336.5212,-256.9751 329.9308,-265.2708 340.256,-262.8956 336.5212,-256.9751"/>
<text text-anchor="middle" x="390.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M408.2077,-191.341C562.055,-187.5787 1296.1437,-167.4011 1385.9954,-123 1420.9643,-105.7198 1448.8339,-69.242 1464.885,-44.1783"/>
<polygon fill="#000000" stroke="#000000" points="1467.9601,-45.8608 1470.2552,-35.5175 1462.0108,-42.172 1467.9601,-45.8608"/>
<text text-anchor="middle" x="1454.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node30" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3070.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3070.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3052.5795,-87.7327C3038.534,-75.7784 3018.0709,-60.8344 2996.9954,-54 2925.4675,-30.805 1774.5916,-20.3465 1526.7756,-18.3575"/>
<polygon fill="#000000" stroke="#000000" points="1526.6894,-14.8568 1516.6619,-18.2771 1526.6337,-21.8566 1526.6894,-14.8568"/>
<text text-anchor="middle" x="3073.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- cytogenomic_file -->
<g id="node31" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="460.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="460.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M457.5799,-347.8692C454.552,-336.7757 448.9929,-323.1861 438.9954,-315 409.1179,-290.5358 391.232,-307.2271 353.9954,-297 350.6615,-296.0844 347.2306,-295.0755 343.7941,-294.0172"/>
<polygon fill="#000000" stroke="#000000" points="344.761,-290.6518 334.1701,-290.9393 342.6287,-297.3192 344.761,-290.6518"/>
<text text-anchor="middle" x="521.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- generic_file -->
<g id="node32" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="3042.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="3042.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2978.2124,-362.6948C2793.7667,-353.425 2249.9579,-327.0716 1797.9954,-315 1637.5957,-310.7159 512.1411,-324.1358 353.9954,-297 350.2811,-296.3627 346.4758,-295.5054 342.6924,-294.5093"/>
<polygon fill="#000000" stroke="#000000" points="343.3872,-291.0656 332.8061,-291.6047 341.4139,-297.7817 343.3872,-291.0656"/>
<text text-anchor="middle" x="2295.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3035.5158,-347.9858C3025.3381,-325.2797 3005.2277,-286.1809 2977.9954,-261 2954.4981,-239.2727 2944.992,-235.9628 2913.9954,-228 2852.2982,-212.1505 1916.38,-197.0947 1645.7641,-193.055"/>
<polygon fill="#000000" stroke="#000000" points="1645.7092,-189.5539 1635.6582,-192.9046 1645.605,-196.5531 1645.7092,-189.5539"/>
<text text-anchor="middle" x="3058.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3098.9478,-356.3838C3140.8589,-345.5957 3190.9954,-323.4095 3190.9954,-279 3190.9954,-279 3190.9954,-279 3190.9954,-105 3190.9954,-68.2802 3160.5691,-66.3694 3125.9954,-54 3048.8083,-26.3849 1787.7564,-19.3522 1526.9638,-18.1903"/>
<polygon fill="#000000" stroke="#000000" points="1526.7166,-14.6893 1516.7013,-18.1453 1526.6859,-21.6892 1526.7166,-14.6893"/>
<text text-anchor="middle" x="3243.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
</g>
</svg>
</div>
