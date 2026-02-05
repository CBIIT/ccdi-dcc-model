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
<svg width="3647pt" height="392pt"
 viewBox="0.00 0.00 3647.04 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3643.0444,-388 3643.0444,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1690.0444" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1690.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1586.0444" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1586.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1673.402,-261.2329C1663.5212,-251.0605 1650.5212,-238.3105 1638.0444,-228 1632.3999,-223.3356 1626.1675,-218.6583 1620.0365,-214.2915"/>
<polygon fill="#000000" stroke="#000000" points="1622.0104,-211.401 1611.8037,-208.5595 1618.0106,-217.1458 1622.0104,-211.401"/>
<text text-anchor="middle" x="1723.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node28" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="737.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="737.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge32" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M57.8022,-86.6105C55.9076,-75.7012 55.9195,-62.4046 64.0444,-54 85.7854,-31.5107 540.9038,-21.4721 690.1229,-18.7769"/>
<polygon fill="#000000" stroke="#000000" points="690.3917,-22.2728 700.3279,-18.5955 690.2672,-15.2739 690.3917,-22.2728"/>
<text text-anchor="middle" x="115.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2524.0444" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2524.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2494.0681,-349.121C2486.6901,-343.7997 2479.3841,-337.3588 2474.0444,-330 2455.1407,-303.9481 2474.4725,-284.0875 2452.0444,-261 2421.1923,-229.2409 2401.5073,-236.4539 2358.0444,-228 2225.4927,-202.2175 1824.1157,-194.7231 1658.5996,-192.6973"/>
<polygon fill="#000000" stroke="#000000" points="1658.5591,-189.1966 1648.5181,-192.5771 1658.4756,-196.1961 1658.5591,-189.1966"/>
<text text-anchor="middle" x="2529.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="3092.0444" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="3092.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2576.0627,-352.0391C2594.7622,-346.2289 2615.7444,-338.7744 2634.0444,-330 2645.0489,-324.7236 2645.4314,-318.7519 2657.0444,-315 2737.9117,-288.8734 2955.5467,-312.8197 3039.0444,-297 3042.6964,-296.3081 3046.4403,-295.4211 3050.1671,-294.4128"/>
<polygon fill="#000000" stroke="#000000" points="3051.3311,-297.7181 3059.9173,-291.5109 3049.3343,-291.0089 3051.3311,-297.7181"/>
<text text-anchor="middle" x="2722.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_other -->
<g id="node4" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2943.0444" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2943.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2896.6146,-263.6218C2857.691,-251.5017 2800.3964,-235.4466 2749.0444,-228 2641.7481,-212.4408 1896.5167,-197.6603 1658.7618,-193.2946"/>
<polygon fill="#000000" stroke="#000000" points="1658.5609,-189.7905 1648.4985,-193.1069 1658.4327,-196.7893 1658.5609,-189.7905"/>
<text text-anchor="middle" x="2888.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="226.0444" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="226.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M235.1315,-348.2236C248.3737,-324.264 275.3387,-282.1759 311.0444,-261 381.3762,-219.2884 410.7382,-236.7016 492.0444,-228 690.9677,-206.7106 1302.7149,-196.0886 1513.6549,-192.9881"/>
<polygon fill="#000000" stroke="#000000" points="1513.7448,-196.4872 1523.6926,-192.8418 1513.6427,-189.488 1513.7448,-196.4872"/>
<text text-anchor="middle" x="353.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M277.5194,-362.9718C435.0849,-353.8427 924.7933,-326.512 1331.0444,-315 1425.9005,-312.312 2945.5017,-312.958 3039.0444,-297 3042.7593,-296.3662 3046.565,-295.5114 3050.3487,-294.5171"/>
<polygon fill="#000000" stroke="#000000" points="3051.6261,-297.7898 3060.2355,-291.615 3049.6545,-291.0732 3051.6261,-297.7898"/>
<text text-anchor="middle" x="1373.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M210.4709,-348.7467C197.1259,-332.1293 180.0444,-305.6534 180.0444,-279 180.0444,-279 180.0444,-279 180.0444,-105 180.0444,-53.5417 555.9451,-27.9163 690.1397,-20.4076"/>
<polygon fill="#000000" stroke="#000000" points="690.7056,-23.8819 700.4981,-19.8373 690.3208,-16.8925 690.7056,-23.8819"/>
<text text-anchor="middle" x="222.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- exposure -->
<g id="node6" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="458.0444" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="458.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M473.2079,-261.5743C484.7183,-249.7087 501.6594,-234.9424 520.0444,-228 566.3995,-210.4958 1280.6128,-197.0933 1513.343,-193.1723"/>
<polygon fill="#000000" stroke="#000000" points="1513.4595,-196.6709 1523.3994,-193.0037 1513.3421,-189.6719 1513.4595,-196.6709"/>
<text text-anchor="middle" x="563.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_response -->
<g id="node7" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="634.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="634.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M618.8982,-261.0163C611.7121,-250.2598 606.3901,-236.9811 615.0444,-228 630.5996,-211.8574 1290.1507,-197.6955 1513.2044,-193.36"/>
<polygon fill="#000000" stroke="#000000" points="1513.5614,-196.8538 1523.4918,-193.161 1513.4259,-189.8551 1513.5614,-196.8538"/>
<text text-anchor="middle" x="698.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="775.0444" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="775.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M770.4455,-347.6593C765.7804,-324.2364 762.025,-283.9916 784.0444,-261 833.9639,-208.8765 1325.5323,-195.9446 1513.485,-192.8941"/>
<polygon fill="#000000" stroke="#000000" points="1513.6028,-196.3928 1523.5464,-192.7356 1513.4924,-189.3936 1513.6028,-196.3928"/>
<text text-anchor="middle" x="870.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M877.3705,-359.921C1086.0242,-347.6123 1554.4602,-320.4456 1715.0444,-315 1862.0846,-310.0137 2894.0529,-321.963 3039.0444,-297 3042.7584,-296.3606 3046.5634,-295.5018 3050.3466,-294.5048"/>
<polygon fill="#000000" stroke="#000000" points="3051.6258,-297.7769 3060.2327,-291.5986 3049.6515,-291.0611 3051.6258,-297.7769"/>
<text text-anchor="middle" x="1801.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M682.0462,-356.6745C553.9978,-342.5545 339.0444,-313.6858 339.0444,-279 339.0444,-279 339.0444,-279 339.0444,-105 339.0444,-69.7764 372.9011,-72.2047 448.0444,-54 532.0073,-33.6586 632.633,-24.4334 690.2747,-20.5472"/>
<polygon fill="#000000" stroke="#000000" points="690.7714,-24.0224 700.5238,-19.8822 690.3181,-17.0371 690.7714,-24.0224"/>
<text text-anchor="middle" x="425.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- family_relationship -->
<g id="node9" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1065.0444" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1065.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1050.5067,-261.0657C1043.6278,-250.3277 1038.5775,-237.0513 1047.0444,-228 1062.7447,-211.2161 1370.4952,-199.0262 1513.784,-194.2371"/>
<polygon fill="#000000" stroke="#000000" points="1513.9317,-197.7342 1523.8103,-193.9051 1513.6999,-190.738 1513.9317,-197.7342"/>
<text text-anchor="middle" x="1126.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="444.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="444.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M446.0778,-86.9146C448.3273,-75.6933 453.0653,-61.9451 463.0444,-54 480.4848,-40.1143 617.0253,-27.4156 690.5367,-21.4994"/>
<polygon fill="#000000" stroke="#000000" points="691.2121,-24.9569 700.9037,-20.6764 690.658,-17.9788 691.2121,-24.9569"/>
<text text-anchor="middle" x="525.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="599.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="599.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M592.4392,-86.7153C589.8554,-76.1152 588.9713,-63.106 596.0444,-54 607.767,-38.9083 654.8717,-29.0818 691.4485,-23.5677"/>
<polygon fill="#000000" stroke="#000000" points="692.0496,-27.0173 701.4477,-22.126 691.0506,-20.089 692.0496,-27.0173"/>
<text text-anchor="middle" x="644.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- consent_group -->
<g id="node21" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="794.0444" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="794.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1524.5033,-188.5624C1401.7205,-181.1331 1117.8484,-161.0947 882.0444,-123 875.4248,-121.9306 868.5461,-120.7126 861.6823,-119.4261"/>
<polygon fill="#000000" stroke="#000000" points="862.1492,-115.9518 851.6683,-117.5015 860.828,-122.826 862.1492,-115.9518"/>
<text text-anchor="middle" x="1183.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3092.0444" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3092.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3090.0694,-210.4051C3089.255,-220.0991 3088.5947,-232.1886 3089.0444,-243 3089.1456,-245.4321 3089.285,-247.9542 3089.4488,-250.4832"/>
<polygon fill="#000000" stroke="#000000" points="3085.9777,-250.9974 3090.2235,-260.7043 3092.9576,-250.4683 3085.9777,-250.9974"/>
<text text-anchor="middle" x="3113.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3063.9778,-191.8273C2846.0427,-190.4359 1430.2766,-180.4745 1344.0444,-156 1316.2532,-148.1123 1310.885,-140.6883 1288.0444,-123 1253.7552,-96.4456 1258.466,-72.0783 1219.0444,-54 1180.1196,-36.1495 896.8127,-23.8771 783.5995,-19.6365"/>
<polygon fill="#000000" stroke="#000000" points="783.6291,-16.1353 773.5064,-19.2629 783.3701,-23.1305 783.6291,-16.1353"/>
<text text-anchor="middle" x="1312.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1373.0444" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1373.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1388.163,-261.8734C1399.0185,-250.6174 1414.5869,-236.4582 1431.0444,-228 1457.7422,-214.2789 1489.6998,-205.72 1517.6427,-200.413"/>
<polygon fill="#000000" stroke="#000000" points="1518.5141,-203.8127 1527.7387,-198.6014 1517.2777,-196.9227 1518.5141,-203.8127"/>
<text text-anchor="middle" x="1470.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1513.0444" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1513.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1511.6722,-260.5621C1511.7981,-250.1661 1513.5481,-237.4161 1520.0444,-228 1524.6306,-221.3526 1530.8554,-215.8154 1537.6589,-211.2402"/>
<polygon fill="#000000" stroke="#000000" points="1539.721,-214.0852 1546.5063,-205.9482 1536.1277,-208.0778 1539.721,-214.0852"/>
<text text-anchor="middle" x="1579.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- generic_file -->
<g id="node16" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1201.0444" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1201.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1196.6346,-347.8357C1192.1741,-324.6036 1188.6395,-284.5648 1210.0444,-261 1249.8027,-217.2298 1416.3888,-200.9624 1513.9773,-195.1173"/>
<polygon fill="#000000" stroke="#000000" points="1514.2884,-198.6053 1524.0702,-194.5352 1513.8852,-191.6169 1514.2884,-198.6053"/>
<text text-anchor="middle" x="1263.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1265.496,-362.1983C1427.6296,-352.7676 1865.5935,-328.1158 2231.0444,-315 2320.7867,-311.7792 2950.6134,-312.6205 3039.0444,-297 3042.7555,-296.3445 3046.5586,-295.4745 3050.3405,-294.47"/>
<polygon fill="#000000" stroke="#000000" points="3051.6248,-297.7403 3060.2246,-291.5521 3049.6428,-291.0267 3051.6248,-297.7403"/>
<text text-anchor="middle" x="2284.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1136.9978,-361.6626C948.5855,-348.7552 408.5683,-310.6433 396.0444,-297 385.2246,-285.2131 387.2365,-274.3575 396.0444,-261 427.7204,-212.9621 463.5089,-235.595 515.0444,-210 585.1045,-175.2049 610.9804,-176.5053 668.0444,-123 692.1316,-100.415 711.8584,-67.8266 723.9595,-44.9617"/>
<polygon fill="#000000" stroke="#000000" points="727.2029,-46.3082 728.6693,-35.8153 720.9795,-43.1035 727.2029,-46.3082"/>
<text text-anchor="middle" x="648.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_status -->
<g id="node17" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="961.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="961.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M944.506,-87.3465C933.0553,-76.1575 916.8925,-62.2816 900.0444,-54 863.0393,-35.8104 816.8177,-26.7195 783.0551,-22.2322"/>
<polygon fill="#000000" stroke="#000000" points="783.3565,-18.7428 773.0011,-20.9824 782.4929,-25.6894 783.3565,-18.7428"/>
<text text-anchor="middle" x="979.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="3564.0444" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="3564.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3573.4853,-348.2706C3577.7422,-337.6097 3580.3638,-324.3423 3573.0444,-315 3523.218,-251.4025 3300.1351,-238.6204 3220.0444,-228 3064.3696,-207.3568 1956.0511,-195.4956 1659.0902,-192.6646"/>
<polygon fill="#000000" stroke="#000000" points="1658.9043,-189.1628 1648.8716,-192.5677 1658.8379,-196.1625 1658.9043,-189.1628"/>
<text text-anchor="middle" x="3594.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3529.6118,-351.9C3515.2755,-345.6731 3498.6102,-337.9645 3484.0444,-330 3473.3366,-324.145 3472.5596,-319.042 3461.0444,-315 3404.3763,-295.1087 3234.2496,-285.0877 3146.1874,-281.1167"/>
<polygon fill="#000000" stroke="#000000" points="3146.2697,-277.617 3136.1253,-280.6732 3145.9614,-284.6102 3146.2697,-277.617"/>
<text text-anchor="middle" x="3528.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3061.8739,-265.7551C3029.9853,-252.0116 2981.6471,-231.9738 2962.0444,-228 2834.2789,-202.0997 1924.5838,-194.1973 1658.7931,-192.4286"/>
<polygon fill="#000000" stroke="#000000" points="1658.5114,-188.9268 1648.4886,-192.361 1658.4653,-195.9267 1658.5114,-188.9268"/>
<text text-anchor="middle" x="3039.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3120.2173,-265.084C3134.9058,-255.7667 3148.4196,-242.5703 3141.0444,-228 3137.0354,-220.0799 3130.3728,-213.4785 3123.2326,-208.1841"/>
<polygon fill="#000000" stroke="#000000" points="3125.0304,-205.1767 3114.7616,-202.5686 3121.1627,-211.0112 3125.0304,-205.1767"/>
<text text-anchor="middle" x="3179.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node27" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3442.0444" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3442.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3129.8331,-269.6068C3193.0118,-253.9024 3320.1314,-222.3041 3391.1301,-204.6558"/>
<polygon fill="#000000" stroke="#000000" points="3392.3234,-207.9658 3401.1838,-202.1568 3390.6348,-201.1725 3392.3234,-207.9658"/>
<text text-anchor="middle" x="3323.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1136.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1136.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1109.9048,-87.6886C1091.2307,-76.1972 1065.0799,-61.8349 1040.0444,-54 993.3036,-39.3724 856.0076,-27.0942 783.3555,-21.4028"/>
<polygon fill="#000000" stroke="#000000" points="783.3641,-17.8931 773.1239,-20.6114 782.8241,-24.8723 783.3641,-17.8931"/>
<text text-anchor="middle" x="1145.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge19" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M782.234,-86.9735C774.1022,-74.5619 763.1715,-57.8782 754.0975,-44.0284"/>
<polygon fill="#000000" stroke="#000000" points="756.8587,-41.8562 748.4508,-35.4097 751.0034,-45.6924 756.8587,-41.8562"/>
<text text-anchor="middle" x="832.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="3134.0444" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="3134.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3122.2179,-348.0365C3118.7275,-342.3815 3115.0429,-336.0348 3112.0444,-330 3108.3957,-322.6565 3104.9361,-314.4747 3101.9521,-306.852"/>
<polygon fill="#000000" stroke="#000000" points="3105.1396,-305.3857 3098.3275,-297.2711 3098.5924,-307.8626 3105.1396,-305.3857"/>
<text text-anchor="middle" x="3203.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node23" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2098.0444" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2098.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2023.1428,-264.2728C1968.3601,-253.6808 1892.2006,-239.327 1825.0444,-228 1766.7146,-218.1617 1700.1513,-208.2421 1652.1106,-201.3141"/>
<polygon fill="#000000" stroke="#000000" points="1652.5463,-197.8408 1642.15,-199.8822 1651.5502,-204.7696 1652.5463,-197.8408"/>
<text text-anchor="middle" x="2009.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- cytogenomic_file -->
<g id="node24" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="3357.0444" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="3357.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3337.6584,-348.2027C3323.1509,-335.2484 3304.2844,-319.2593 3295.0444,-315 3268.9674,-302.9793 3195.8377,-291.8854 3144.8785,-285.2783"/>
<polygon fill="#000000" stroke="#000000" points="3145.0471,-281.7715 3134.6845,-283.9778 3144.1612,-288.7152 3145.0471,-281.7715"/>
<text text-anchor="middle" x="3386.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sequencing_file -->
<g id="node25" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2747.0444" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2747.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2766.4875,-348.3485C2780.5581,-336.701 2800.6192,-322.2921 2821.0444,-315 2912.603,-282.3125 2943.8593,-316.7801 3039.0444,-297 3042.6331,-296.2542 3046.3148,-295.3375 3049.9843,-294.3163"/>
<polygon fill="#000000" stroke="#000000" points="3051.0345,-297.6554 3059.5966,-291.4151 3049.0118,-290.954 3051.0345,-297.6554"/>
<text text-anchor="middle" x="2887.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- genetic_analysis -->
<g id="node26" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2075.0444" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2075.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2006.3689,-354.7604C1940.4865,-342.7132 1847.1311,-321.9182 1820.0444,-297 1796.0395,-274.9168 1820.057,-248.9349 1795.0444,-228 1774.464,-210.7748 1709.548,-201.4935 1657.4647,-196.6945"/>
<polygon fill="#000000" stroke="#000000" points="1657.5046,-193.1845 1647.236,-195.7934 1656.8903,-200.1575 1657.5046,-193.1845"/>
<text text-anchor="middle" x="1890.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2146.0808,-355.3053C2228.566,-343.3443 2368.8203,-324.417 2490.0444,-315 2611.7433,-305.5461 2918.9529,-318.8639 3039.0444,-297 3042.7521,-296.325 3046.5527,-295.4414 3050.333,-294.4279"/>
<polygon fill="#000000" stroke="#000000" points="3051.6232,-297.696 3060.2145,-291.4959 3049.632,-290.9852 3051.6232,-297.696"/>
<text text-anchor="middle" x="2560.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3480.8714,-203.2428C3505.9307,-212.3858 3531.2448,-226.4543 3516.0444,-243 3491.5329,-269.6809 3255.6104,-276.6104 3146.6773,-278.3921"/>
<polygon fill="#000000" stroke="#000000" points="3146.4878,-274.8945 3136.5432,-278.5489 3146.5962,-281.8936 3146.4878,-274.8945"/>
<text text-anchor="middle" x="3560.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3393.2721,-188.7635C3331.7183,-184.7782 3222.5768,-178.0422 3129.0444,-174 3031.2058,-169.7717 1455.4618,-165.1027 1367.0444,-123 1347.9808,-113.9223 1353.4246,-98.9899 1336.0444,-87 1300.6318,-62.5703 1287.127,-62.9396 1245.0444,-54 1157.7886,-35.4643 892.4793,-23.7828 784.0116,-19.6661"/>
<polygon fill="#000000" stroke="#000000" points="783.8339,-16.1571 773.7099,-19.2801 783.5717,-23.1522 783.8339,-16.1571"/>
<text text-anchor="middle" x="1407.5444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_surgery -->
<g id="node29" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2344.0444" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2344.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2288.0175,-264.0321C2241.9224,-252.3214 2174.7063,-236.6232 2115.0444,-228 1953.1956,-204.6074 1761.2316,-196.345 1658.8878,-193.4787"/>
<polygon fill="#000000" stroke="#000000" points="1658.7563,-189.974 1648.6653,-193.2021 1658.5669,-196.9714 1658.7563,-189.974"/>
<text text-anchor="middle" x="2275.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_admin -->
<g id="node30" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1527.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1527.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1489.8687,-89.7165C1458.9138,-77.7383 1413.3775,-61.8315 1372.0444,-54 1259.2663,-32.6316 910.8517,-22.227 783.9189,-19.0718"/>
<polygon fill="#000000" stroke="#000000" points="783.8317,-15.5688 773.749,-18.8229 783.6603,-22.5667 783.8317,-15.5688"/>
<text text-anchor="middle" x="1485.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_radiation -->
<g id="node31" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="2733.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2733.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2675.3171,-263.8507C2626.9927,-251.8667 2556.0225,-235.8833 2493.0444,-228 2332.1912,-207.8651 1844.0836,-196.8422 1658.609,-193.2899"/>
<polygon fill="#000000" stroke="#000000" points="1658.483,-189.7869 1648.4183,-193.0964 1658.3501,-196.7857 1658.483,-189.7869"/>
<text text-anchor="middle" x="2662.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- pathology_file -->
<g id="node32" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2924.0444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2924.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2939.2922,-348.1946C2949.5384,-337.231 2963.8977,-323.6638 2979.0444,-315 3003.2112,-301.1769 3012.5258,-305.4779 3039.0444,-297 3042.1452,-296.0087 3045.342,-294.9686 3048.5567,-293.9094"/>
<polygon fill="#000000" stroke="#000000" points="3049.7948,-297.1861 3058.1758,-290.7046 3047.5822,-290.545 3049.7948,-297.1861"/>
<text text-anchor="middle" x="3040.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
