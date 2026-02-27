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
<svg width="3493pt" height="392pt"
 viewBox="0.00 0.00 3493.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3489.3431,-388 3489.3431,4 -4,4"/>
<!-- generic_file -->
<g id="node1" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="84" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="84" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- study -->
<g id="node24" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1496" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1496" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M53.1985,-350.0985C29.2249,-335.2752 0,-310.7031 0,-279 0,-279 0,-279 0,-105 0,-30.5816 1195.3862,-19.6904 1449.0502,-18.2171"/>
<polygon fill="#000000" stroke="#000000" points="1449.4113,-21.7152 1459.3915,-18.1593 1449.3721,-14.7153 1449.4113,-21.7152"/>
<text text-anchor="middle" x="53" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample -->
<g id="node29" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2877" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2877" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M149.2583,-363.3762C360.0394,-354.9952 1041.7037,-328.6229 1606,-315 1741.3087,-311.7335 2690.628,-320.0437 2824,-297 2827.7136,-296.3584 2831.5183,-295.4981 2835.3014,-294.5001"/>
<polygon fill="#000000" stroke="#000000" points="2836.5812,-297.7719 2845.1872,-291.5923 2834.6059,-291.0564 2836.5812,-297.7719"/>
<text text-anchor="middle" x="1659" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- participant -->
<g id="node30" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1686" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1686" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M79.3976,-347.6559C74.7287,-324.2294 70.9692,-283.9807 93,-261 172.6942,-177.8696 235.1524,-236.477 350,-228 756.085,-198.0266 859.009,-222.7183 1266,-210 1388.3726,-206.1759 1530.7149,-199.6344 1614.3085,-195.5789"/>
<polygon fill="#000000" stroke="#000000" points="1614.6381,-199.067 1624.456,-195.0848 1614.2976,-192.0753 1614.6381,-199.067"/>
<text text-anchor="middle" x="146" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1159" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1159" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1172.1495,-261.0723C1181.772,-249.4588 1195.9166,-235.2014 1212,-228 1247.67,-212.0285 1490.0734,-199.9825 1613.7395,-194.7973"/>
<polygon fill="#000000" stroke="#000000" points="1614.0343,-198.2882 1623.8805,-194.3763 1613.7439,-191.2942 1614.0343,-198.2882"/>
<text text-anchor="middle" x="1295" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2464.5829,-348.457C2479.6897,-336.6991 2501.2802,-322.1133 2523,-315 2650.3606,-273.2893 2692.486,-322.7793 2824,-297 2827.6476,-296.285 2831.3883,-295.3818 2835.113,-294.3627"/>
<polygon fill="#000000" stroke="#000000" points="2836.2844,-297.6655 2844.8599,-291.4436 2834.2761,-290.9598 2836.2844,-297.6655"/>
<text text-anchor="middle" x="2584" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="918" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="918" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M935.3094,-87.5225C948.1206,-75.7954 966.6428,-61.2196 986,-54 1028.7361,-38.0609 1331.6287,-24.5091 1449.3595,-19.7865"/>
<polygon fill="#000000" stroke="#000000" points="1449.648,-23.2778 1459.501,-19.3832 1449.3698,-16.2834 1449.648,-23.2778"/>
<text text-anchor="middle" x="1042.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_status -->
<g id="node5" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1076" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1076" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1086.9425,-87.1987C1095.0842,-75.6416 1107.303,-61.3997 1122,-54 1150.6403,-39.5801 1355.9255,-26.0733 1449.6039,-20.584"/>
<polygon fill="#000000" stroke="#000000" points="1449.873,-24.0744 1459.6534,-20.0008 1449.4674,-17.0861 1449.873,-24.0744"/>
<text text-anchor="middle" x="1178.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node6" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1411" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1411" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1392.072,-261.1201C1383.2626,-250.6636 1376.4238,-237.663 1385,-228 1399.9808,-211.1207 1530.0169,-200.6989 1614.2022,-195.6589"/>
<polygon fill="#000000" stroke="#000000" points="1614.4526,-199.1503 1624.2306,-195.0708 1614.0428,-192.1623 1614.4526,-199.1503"/>
<text text-anchor="middle" x="1487" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1227" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1227" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge36" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1230.9067,-86.866C1234.2974,-75.6247 1240.3915,-61.8726 1251,-54 1281.5143,-31.3554 1386.7079,-22.8184 1448.8956,-19.7033"/>
<polygon fill="#000000" stroke="#000000" points="1449.4101,-23.183 1459.234,-19.2154 1449.0801,-16.1908 1449.4101,-23.183"/>
<text text-anchor="middle" x="1302" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment_surgery -->
<g id="node8" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1949" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1949" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1901.0676,-263.144C1854.5914,-247.7698 1784.3355,-224.5292 1736.8837,-208.8322"/>
<polygon fill="#000000" stroke="#000000" points="1737.7141,-205.4205 1727.1208,-205.6027 1735.5156,-212.0663 1737.7141,-205.4205"/>
<text text-anchor="middle" x="1912.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- medical_history -->
<g id="node9" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2616" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2616" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2563.6992,-264.7202C2517.575,-252.7608 2448.3459,-236.3462 2387,-228 2267.266,-211.7101 1912.352,-199.0544 1758.4928,-194.1784"/>
<polygon fill="#000000" stroke="#000000" points="1758.3161,-190.6711 1748.2109,-193.8546 1758.0957,-197.6677 1758.3161,-190.6711"/>
<text text-anchor="middle" x="2537" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cytogenomic_file -->
<g id="node10" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2628" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2628" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge44" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2636.983,-347.8183C2643.6323,-336.4062 2653.8151,-322.4802 2667,-315 2728.0885,-280.3427 2755.4699,-312.3805 2824,-297 2827.5764,-296.1973 2831.2494,-295.2404 2834.9131,-294.1922"/>
<polygon fill="#000000" stroke="#000000" points="2835.9816,-297.5255 2844.5159,-291.2472 2833.9292,-290.8331 2835.9816,-297.5255"/>
<text text-anchor="middle" x="2738.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2767" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2767" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2734.3794,-265.5648C2702.8888,-253.2966 2653.558,-235.906 2609,-228 2446.2017,-199.1142 1946.81,-193.4056 1758.6982,-192.2776"/>
<polygon fill="#000000" stroke="#000000" points="1758.6552,-188.7774 1748.6352,-192.2199 1758.615,-195.7773 1758.6552,-188.7774"/>
<text text-anchor="middle" x="2705.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_radiation -->
<g id="node12" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="313" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="313" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M329.8993,-261.2256C342.4489,-249.3586 360.6751,-234.7376 380,-228 426.488,-211.7921 1216.7922,-211.5541 1266,-210 1388.3713,-206.1352 1530.714,-199.6063 1614.308,-195.5643"/>
<polygon fill="#000000" stroke="#000000" points="1614.637,-199.0526 1624.4556,-195.0719 1614.2977,-192.0608 1614.637,-199.0526"/>
<text text-anchor="middle" x="463" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="536" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="536" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M540.5156,-260.8715C544.4208,-249.3272 551.3331,-235.2295 563,-228 596.2094,-207.4216 1226.9545,-211.3365 1266,-210 1388.3606,-205.8118 1530.7067,-199.3833 1614.3042,-195.4491"/>
<polygon fill="#000000" stroke="#000000" points="1614.6284,-198.9378 1624.4523,-194.9701 1614.2983,-191.9455 1614.6284,-198.9378"/>
<text text-anchor="middle" x="642.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2851" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2851" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2827.5479,-347.9943C2818.0255,-338.4096 2810.6035,-326.2974 2817,-315 2821.3019,-307.4021 2827.9178,-301.2328 2835.2092,-296.2888"/>
<polygon fill="#000000" stroke="#000000" points="2837.1999,-299.1764 2843.9809,-291.0358 2833.6034,-293.1709 2837.1999,-299.1764"/>
<text text-anchor="middle" x="2908.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_other -->
<g id="node15" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="741" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="741" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M730.4072,-260.7214C725.6385,-249.8539 722.7211,-236.5621 731,-228 751.6721,-206.6207 1236.2827,-211.1367 1266,-210 1388.1678,-205.3271 1530.2872,-199.0625 1613.9387,-195.2901"/>
<polygon fill="#000000" stroke="#000000" points="1614.2631,-198.7791 1624.095,-194.8313 1613.9472,-191.7862 1614.2631,-198.7791"/>
<text text-anchor="middle" x="800.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1368" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1368" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge41" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1359.4379,-86.7933C1355.8374,-76.2208 1353.9217,-63.2132 1361,-54 1371.9956,-39.688 1415.8243,-29.8505 1450.5996,-24.1216"/>
<polygon fill="#000000" stroke="#000000" points="1451.2606,-27.5606 1460.5929,-22.5447 1450.1695,-20.6462 1451.2606,-27.5606"/>
<text text-anchor="middle" x="1409.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="864" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="864" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M755.7689,-364.4887C550.0881,-360.4877 119.1434,-346.2582 74,-297 63.1897,-285.2044 63.3791,-272.9665 74,-261 156.007,-168.6037 227.1748,-241.2733 350,-228 591.2751,-201.9262 1233.6859,-255.5024 1437,-123 1464.2522,-105.2394 1480.1704,-70.2903 1488.4659,-45.6016"/>
<polygon fill="#000000" stroke="#000000" points="1491.8075,-46.6425 1491.4704,-36.053 1485.1303,-44.5415 1491.8075,-46.6425"/>
<text text-anchor="middle" x="1391" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M972.3079,-364.324C1168.6105,-360.8035 1575.8305,-351.1524 1716,-330 1741.9026,-326.0911 1747.0504,-318.5834 1773,-315 2004.3939,-283.0463 2593.8674,-337.0401 2824,-297 2827.7128,-296.354 2831.517,-295.4907 2835.2997,-294.4906"/>
<polygon fill="#000000" stroke="#000000" points="2836.581,-297.762 2845.185,-291.5797 2834.6036,-291.0471 2836.581,-297.762"/>
<text text-anchor="middle" x="1859" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M859.3988,-347.9812C854.6056,-324.5304 850.5783,-283.8565 873,-261 898.81,-234.6894 1420.1331,-205.5477 1614.114,-195.5731"/>
<polygon fill="#000000" stroke="#000000" points="1614.3995,-199.0631 1624.2074,-195.0562 1614.0414,-192.0723 1614.3995,-199.0631"/>
<text text-anchor="middle" x="959" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx -->
<g id="node18" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3130" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3130" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge28" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3102.5064,-188.7427C2969.1088,-172.9802 2375.8832,-103.3662 1889,-54 1763.7701,-41.3027 1615.8836,-28.2894 1542.3525,-21.9528"/>
<polygon fill="#000000" stroke="#000000" points="1542.3178,-18.437 1532.0547,-21.0672 1541.718,-25.4113 1542.3178,-18.437"/>
<text text-anchor="middle" x="2552" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3142.9137,-208.3412C3149.8813,-219.2466 3155.4842,-233.3095 3147,-243 3133.0167,-258.9714 3005.8246,-270.2485 2931.1086,-275.5593"/>
<polygon fill="#000000" stroke="#000000" points="2930.6636,-272.0817 2920.9314,-276.269 2931.1506,-279.0648 2930.6636,-272.0817"/>
<text text-anchor="middle" x="3175" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- consent_group -->
<g id="node19" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1563" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1563" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge32" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1549.1176,-86.9735C1539.3411,-74.2788 1526.123,-57.115 1515.3186,-43.0853"/>
<polygon fill="#000000" stroke="#000000" points="1517.83,-40.6101 1508.9555,-34.8228 1512.284,-44.8812 1517.83,-40.6101"/>
<text text-anchor="middle" x="1597.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1865" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1865" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1818.2804,-89.6649C1783.8932,-78.7416 1735.8656,-64.2404 1693,-54 1641.3603,-41.6635 1581.2302,-31.235 1541.1137,-24.8279"/>
<polygon fill="#000000" stroke="#000000" points="1541.5349,-21.3511 1531.1112,-23.2475 1540.4424,-28.2653 1541.5349,-21.3511"/>
<text text-anchor="middle" x="1815.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node21" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2100" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2100" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2129.8257,-350.8855C2155.6084,-338.6622 2194.2551,-322.3231 2230,-315 2359.3734,-288.495 2694.0458,-320.4929 2824,-297 2827.7085,-296.3296 2831.5097,-295.4492 2835.2904,-294.4379"/>
<polygon fill="#000000" stroke="#000000" points="2836.5792,-297.7065 2845.1725,-291.5092 2834.5902,-290.995 2836.5792,-297.7065"/>
<text text-anchor="middle" x="2274.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2092.7746,-348.1213C2087.071,-336.5297 2077.9089,-322.2783 2065,-315 2004.3112,-280.7823 1811.9872,-332.4333 1752,-297 1736.6766,-287.9488 1713.6217,-246.8027 1699.2104,-218.7867"/>
<polygon fill="#000000" stroke="#000000" points="1702.3242,-217.1884 1694.6781,-209.8543 1696.0818,-220.3558 1702.3242,-217.1884"/>
<text text-anchor="middle" x="1796.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- genetic_analysis -->
<g id="node22" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2261" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2261" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2288.7959,-348.787C2311.7512,-334.7268 2341.5714,-316.8765 2348,-315 2449.613,-285.3395 2719.9064,-316.2215 2824,-297 2827.6552,-296.3251 2831.4013,-295.45 2835.1296,-294.4496"/>
<polygon fill="#000000" stroke="#000000" points="2836.2882,-297.7568 2844.8821,-291.5604 2834.2998,-291.0451 2836.2882,-297.7568"/>
<text text-anchor="middle" x="2418" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2227.8051,-349.2266C2212.8512,-339.4922 2200.6268,-326.8481 2211,-315 2250.8732,-269.4574 2306.1268,-342.5426 2346,-297 2369.8025,-269.8132 2336.8631,-240.6082 2303,-228 2253.1753,-209.4489 1910.6754,-198.0444 1758.545,-193.84"/>
<polygon fill="#000000" stroke="#000000" points="1758.4578,-190.3364 1748.3658,-193.5616 1758.2664,-197.3338 1758.4578,-190.3364"/>
<text text-anchor="middle" x="2425" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- synonym -->
<g id="node23" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3278" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3278" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge37" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3286.3246,-348.1C3293.5972,-330.8051 3303,-303.6732 3303,-279 3303,-279 3303,-279 3303,-105 3303,-59.5765 1826.6029,-25.1872 1542.8525,-18.9974"/>
<polygon fill="#000000" stroke="#000000" points="1542.5775,-15.4907 1532.5039,-18.7726 1542.4255,-22.489 1542.5775,-15.4907"/>
<text text-anchor="middle" x="3345.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3238.5869,-353.9832C3220.0841,-347.7621 3197.978,-339.4816 3179,-330 3168.0827,-324.5456 3167.451,-319.2204 3156,-315 3115.8444,-300.2003 2999.9139,-288.7923 2930.7761,-283.0681"/>
<polygon fill="#000000" stroke="#000000" points="2930.7664,-279.5558 2920.5151,-282.2318 2930.1977,-286.5327 2930.7664,-279.5558"/>
<text text-anchor="middle" x="3221.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3277.2887,-347.7976C3275.9261,-336.9587 3272.4685,-323.6703 3264,-315 3244.5467,-295.0832 3230.2119,-306.3834 3204,-297 3129.1635,-270.2098 3116.7187,-244.6742 3039,-228 2913.8779,-201.1557 2022.0002,-193.9296 1758.8874,-192.3718"/>
<polygon fill="#000000" stroke="#000000" points="1758.7023,-188.8708 1748.682,-192.3124 1758.6615,-195.8707 1758.7023,-188.8708"/>
<text text-anchor="middle" x="3246.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line -->
<g id="node25" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2877" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2877" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2827.6989,-190.675C2608.8426,-184.5984 1733.9412,-158.1795 1688,-123 1662.3349,-103.3469 1689.0997,-75.544 1665,-54 1647.1419,-38.0358 1585.7982,-27.9797 1542.1724,-22.6731"/>
<polygon fill="#000000" stroke="#000000" points="1542.3926,-19.175 1532.0533,-21.4878 1541.5782,-26.1275 1542.3926,-19.175"/>
<text text-anchor="middle" x="1728.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2917.5061,-202.319C2930.4741,-207.7452 2943.423,-215.8879 2951,-228 2961.2974,-244.4608 2944.098,-256.9694 2923.701,-265.4785"/>
<polygon fill="#000000" stroke="#000000" points="2922.2872,-262.2717 2914.1917,-269.1065 2924.7824,-268.8119 2922.2872,-262.2717"/>
<text text-anchor="middle" x="2994.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- exposure -->
<g id="node26" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2119" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2119" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2089.2214,-264.0339C2064.5861,-252.3242 2028.3532,-236.6264 1995,-228 1915.627,-207.4711 1821.7379,-198.6302 1758.456,-194.8342"/>
<polygon fill="#000000" stroke="#000000" points="1758.3633,-191.3233 1748.1796,-194.246 1757.9633,-198.3118 1758.3633,-191.3233"/>
<text text-anchor="middle" x="2084.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_funding -->
<g id="node27" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3408" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3408" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3384.6991,-87.6783C3367.1016,-75.6969 3341.8173,-60.7428 3317,-54 3228.9252,-30.0702 1818.2387,-20.0204 1542.5231,-18.2801"/>
<polygon fill="#000000" stroke="#000000" points="1542.4771,-14.7799 1532.4553,-18.2171 1542.4332,-21.7797 1542.4771,-14.7799"/>
<text text-anchor="middle" x="3413" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- radiology_file -->
<g id="node28" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2264" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2264" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2230.3868,-262.9033C2204.2034,-251.1369 2166.6085,-235.9072 2132,-228 2062.8541,-212.2019 1865.4194,-200.6243 1757.9003,-195.2846"/>
<polygon fill="#000000" stroke="#000000" points="1757.943,-191.7825 1747.7833,-194.7873 1757.5994,-198.7741 1757.943,-191.7825"/>
<text text-anchor="middle" x="2240" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2918.9189,-273.1391C2952.2145,-267.6697 2999.5685,-258.0562 3039,-243 3061.1879,-234.528 3084.5236,-221.3525 3102.0086,-210.5156"/>
<polygon fill="#000000" stroke="#000000" points="3103.9971,-213.3994 3110.5817,-205.0991 3100.2582,-207.4815 3103.9971,-213.3994"/>
<text text-anchor="middle" x="3106.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2875.1791,-260.7043C2874.6947,-255.0358 2874.2398,-248.7649 2874,-243 2873.6979,-235.7361 2873.8968,-227.8952 2874.3068,-220.5916"/>
<polygon fill="#000000" stroke="#000000" points="2877.813,-220.6265 2875.025,-210.4051 2870.8303,-220.1342 2877.813,-220.6265"/>
<text text-anchor="middle" x="2910.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2847.0133,-265.6577C2815.6179,-251.9421 2768.2571,-232.0342 2749,-228 2652.8825,-207.8641 1982.4799,-196.3343 1758.6008,-193.012"/>
<polygon fill="#000000" stroke="#000000" points="1758.6489,-189.5124 1748.5983,-192.8646 1758.5457,-196.5116 1758.6489,-189.5124"/>
<text text-anchor="middle" x="2825.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge35" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1632.4256,-182.6439C1603.7907,-176.4472 1572.6733,-167.3682 1564,-156 1559.1445,-149.6358 1557.5932,-141.4077 1557.6181,-133.4252"/>
<polygon fill="#000000" stroke="#000000" points="1561.1234,-133.4929 1558.4133,-123.2505 1554.1446,-132.9474 1561.1234,-133.4929"/>
<text text-anchor="middle" x="1614.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node31" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3068" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="3068" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3046.4603,-348.5144C3030.3958,-335.7321 3009.633,-319.8221 3000,-315 2977.0356,-303.5044 2949.776,-295.0567 2926.7622,-289.2454"/>
<polygon fill="#000000" stroke="#000000" points="2927.3956,-285.7975 2916.852,-286.8373 2925.7428,-292.5996 2927.3956,-285.7975"/>
<text text-anchor="middle" x="3088.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- laboratory_test -->
<g id="node32" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1772" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1772" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1828.1781,-352.8959C1883.6807,-340.5964 1971.1753,-322.9377 2048,-315 2219.5774,-297.2723 2654.1526,-327.0823 2824,-297 2827.7108,-296.3428 2831.5137,-295.4716 2835.2955,-294.4663"/>
<polygon fill="#000000" stroke="#000000" points="2836.5802,-297.7364 2845.1793,-291.5472 2834.5974,-291.0231 2836.5802,-297.7364"/>
<text text-anchor="middle" x="2113.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1693.7778,-360.2922C1650.7365,-355.3459 1603.3926,-346.3012 1590,-330 1570.5326,-306.3047 1576.0077,-288.2885 1590,-261 1601.0448,-239.4598 1622.288,-223.122 1641.9887,-211.7649"/>
<polygon fill="#000000" stroke="#000000" points="1643.7958,-214.7658 1650.8897,-206.8964 1640.4367,-208.6244 1643.7958,-214.7658"/>
<text text-anchor="middle" x="1655.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
