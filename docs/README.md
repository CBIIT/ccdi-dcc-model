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
<svg width="3080pt" height="479pt"
 viewBox="0.00 0.00 3080.00 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3076,-475 3076,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1656" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1656" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node31" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1439" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1439" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1649.8226,-434.9494C1645.053,-423.7423 1637.3298,-409.9969 1626,-402 1604.862,-387.0801 1539.6711,-376.9473 1492.1955,-371.325"/>
<polygon fill="#000000" stroke="#000000" points="1492.3896,-367.8243 1482.0555,-370.1601 1491.5907,-374.7786 1492.3896,-367.8243"/>
<text text-anchor="middle" x="1705.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node2" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="397" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="397" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1567" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1567" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M426.9563,-264.5391C453.9749,-252.2869 495.1631,-235.5434 533,-228 626.4211,-209.3749 1275.0132,-196.8975 1494.5507,-193.1683"/>
<polygon fill="#000000" stroke="#000000" points="1494.7372,-196.6657 1504.6766,-192.9973 1494.6189,-189.6667 1494.7372,-196.6657"/>
<text text-anchor="middle" x="573.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="995" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="995" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M401.0046,-261.0318C410.4776,-222.843 437.9584,-133.3174 496,-87 541.92,-50.3557 566.1434,-64.2012 624,-54 739.6278,-33.6126 877.7118,-24.0408 948.3406,-20.1944"/>
<polygon fill="#000000" stroke="#000000" points="948.8717,-23.6713 958.6723,-19.6466 948.501,-16.6811 948.8717,-23.6713"/>
<text text-anchor="middle" x="490.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- consent_group -->
<g id="node14" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1250" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1250" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge23" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1521.5816,-179.535C1466.1195,-164.3136 1372.1123,-138.5135 1310.5434,-121.616"/>
<polygon fill="#000000" stroke="#000000" points="1311.1444,-118.1516 1300.5746,-118.8801 1309.2917,-124.902 1311.1444,-118.1516"/>
<text text-anchor="middle" x="1477.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1045" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1045" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1069.9481,-435.668C1087.7972,-424.1671 1112.8443,-409.802 1137,-402 1181.8695,-387.5077 1311.1222,-375.7147 1385.1785,-369.9083"/>
<polygon fill="#000000" stroke="#000000" points="1385.5472,-373.3903 1395.2473,-369.1291 1385.007,-366.4112 1385.5472,-373.3903"/>
<text text-anchor="middle" x="1208.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="582" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="582" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M601.4975,-87.498C615.5931,-75.9191 635.6615,-61.5307 656,-54 708.4537,-34.578 868.2525,-24.2109 948.2886,-20.1153"/>
<polygon fill="#000000" stroke="#000000" points="948.7569,-23.5963 958.5697,-19.6013 948.4073,-16.6051 948.7569,-23.5963"/>
<text text-anchor="middle" x="718" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node6" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="740" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="740" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M757.8409,-87.7243C770.5489,-76.4018 788.5791,-62.2243 807,-54 852.544,-33.6661 909.3052,-24.8008 948.4761,-20.9458"/>
<polygon fill="#000000" stroke="#000000" points="948.8948,-24.4222 958.5353,-20.0277 948.2585,-17.4512 948.8948,-24.4222"/>
<text text-anchor="middle" x="858" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment_radiation -->
<g id="node7" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="569" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="569" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M589.5385,-261.3191C604.6244,-249.4962 626.2081,-234.8894 648,-228 727.6376,-202.8228 1291.0156,-194.7527 1494.1805,-192.6445"/>
<polygon fill="#000000" stroke="#000000" points="1494.4828,-196.1417 1504.4466,-192.5399 1494.4114,-189.1421 1494.4828,-196.1417"/>
<text text-anchor="middle" x="731" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="777" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="777" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M793.9248,-261.1488C806.2833,-249.4097 824.1185,-234.9734 843,-228 902.9069,-205.8749 1322.9694,-196.2031 1494.4025,-193.1459"/>
<polygon fill="#000000" stroke="#000000" points="1494.6555,-196.6421 1504.5924,-192.9667 1494.5324,-189.6432 1494.6555,-196.6421"/>
<text text-anchor="middle" x="911" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- genetic_analysis -->
<g id="node9" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2880" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2880" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2871.2437,-434.6283C2857.0622,-406.3083 2826.8056,-351.4539 2789,-315 2735.447,-263.3618 2717.2882,-249.2701 2646,-228 2550.3148,-199.4505 1866.2645,-193.4861 1639.6867,-192.2889"/>
<polygon fill="#000000" stroke="#000000" points="1639.5855,-188.7884 1629.5676,-192.237 1639.5495,-195.7883 1639.5855,-188.7884"/>
<text text-anchor="middle" x="2873" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2809.4906,-442.2132C2792.3318,-439.7176 2774.0206,-437.1624 2757,-435 2621.3022,-417.7601 2587.4391,-411.7711 2451,-402 2085.8801,-375.8519 1645.2304,-368.4236 1493.4509,-366.5615"/>
<polygon fill="#000000" stroke="#000000" points="1493.4917,-363.0618 1483.4505,-366.4418 1493.4078,-370.0613 1493.4917,-363.0618"/>
<text text-anchor="middle" x="2684" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="908" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="908" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M909.3124,-86.7863C910.9081,-76.2114 914.3996,-63.2037 922,-54 930.3069,-43.9408 942.1161,-36.455 953.8214,-30.9947"/>
<polygon fill="#000000" stroke="#000000" points="955.2861,-34.1752 963.1175,-27.0395 952.5455,-27.734 955.2861,-34.1752"/>
<text text-anchor="middle" x="991.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M966.1606,-261.0247C975.1293,-249.3899 988.4434,-235.1267 1004,-228 1047.4621,-208.0896 1352.0942,-197.6096 1494.2529,-193.7565"/>
<polygon fill="#000000" stroke="#000000" points="1494.7107,-197.2456 1504.6136,-193.4796 1494.5236,-190.2481 1494.7107,-197.2456"/>
<text text-anchor="middle" x="1063" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pathology_file -->
<g id="node12" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1229" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1229" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1253.4133,-435.7708C1269.6895,-424.9008 1291.895,-411.2225 1313,-402 1337.5341,-391.279 1366.1395,-382.807 1389.8879,-376.782"/>
<polygon fill="#000000" stroke="#000000" points="1390.8722,-380.1442 1399.7424,-374.3502 1389.1951,-373.348 1390.8722,-380.1442"/>
<text text-anchor="middle" x="1374" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_admin -->
<g id="node13" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1083" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1083" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1078.3964,-86.8292C1074.9879,-76.2695 1069.4467,-63.2627 1061,-54 1053.324,-45.5824 1043.2102,-38.7199 1033.2131,-33.3307"/>
<polygon fill="#000000" stroke="#000000" points="1034.6478,-30.1349 1024.1383,-28.7931 1031.5172,-36.3959 1034.6478,-30.1349"/>
<text text-anchor="middle" x="1127.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge15" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1233.2264,-87.1687C1221.6032,-75.9045 1205.1788,-62.0117 1188,-54 1162.4051,-42.0633 1089.0757,-30.4956 1040.5352,-23.8208"/>
<polygon fill="#000000" stroke="#000000" points="1040.9588,-20.3464 1030.5795,-22.4724 1040.0192,-27.283 1040.9588,-20.3464"/>
<text text-anchor="middle" x="1275.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="183" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="183" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M185.5054,-434.7737C190.1313,-406.6483 202.2054,-352.0501 230,-315 270.4002,-261.1468 290.1106,-249.2247 354,-228 408.2006,-209.994 1241.0831,-196.6599 1494.4386,-193.0041"/>
<polygon fill="#000000" stroke="#000000" points="1494.6878,-196.501 1504.6365,-192.8577 1494.5873,-189.5017 1494.6878,-196.501"/>
<text text-anchor="middle" x="316" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M126.1008,-437.6489C72.3807,-421.4282 0,-394.3186 0,-366 0,-366 0,-366 0,-105 0,-56.7685 751.7538,-26.6527 948.3928,-19.6002"/>
<polygon fill="#000000" stroke="#000000" points="948.5382,-23.0973 958.4074,-19.2438 948.2892,-16.1017 948.5382,-23.0973"/>
<text text-anchor="middle" x="86" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M271.2124,-442.3963C369.9317,-430.8788 534.7079,-412.6979 677,-402 941.9391,-382.0811 1259.5784,-371.2735 1384.6281,-367.5292"/>
<polygon fill="#000000" stroke="#000000" points="1384.8206,-371.0251 1394.7124,-367.2301 1384.613,-364.0282 1384.8206,-371.0251"/>
<text text-anchor="middle" x="763" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_status -->
<g id="node16" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1417" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1417" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge44" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1397.5089,-87.4807C1383.4163,-75.8938 1363.3487,-61.5031 1343,-54 1288.8271,-34.0251 1123.1847,-23.8639 1041.5167,-19.9568"/>
<polygon fill="#000000" stroke="#000000" points="1041.6665,-16.4601 1031.514,-19.4895 1041.3398,-23.4525 1041.6665,-16.4601"/>
<text text-anchor="middle" x="1427.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_response -->
<g id="node17" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1150" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1150" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1134.9986,-261.1527C1127.867,-250.4475 1122.5515,-237.1749 1131,-228 1155.0587,-201.873 1376.7232,-194.7068 1494.3852,-192.7419"/>
<polygon fill="#000000" stroke="#000000" points="1494.4575,-196.2413 1504.4007,-192.583 1494.3464,-189.2421 1494.4575,-196.2413"/>
<text text-anchor="middle" x="1214" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2367" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2367" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2413.3754,-438.1012C2426.3091,-432.6675 2439.8569,-425.6736 2451,-417 2496.0344,-381.9459 2480.3964,-344.9095 2529,-315 2565.9708,-292.2491 2597.2767,-330.4045 2625,-297 2645.9291,-271.782 2628.2302,-242.8178 2599,-228 2556.3567,-206.3826 1868.0379,-195.7934 1639.8504,-192.8648"/>
<polygon fill="#000000" stroke="#000000" points="1639.7029,-189.3627 1629.6592,-192.7352 1639.6138,-196.3622 1639.7029,-189.3627"/>
<text text-anchor="middle" x="2594.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2294.4479,-444.478C2202.0069,-433.7731 2037.263,-415.2091 1896,-402 1750.3726,-388.3828 1578.3126,-375.7638 1492.8222,-369.7276"/>
<polygon fill="#000000" stroke="#000000" points="1493.0544,-366.2353 1482.8333,-369.0245 1492.5629,-373.2181 1493.0544,-366.2353"/>
<text text-anchor="middle" x="2103.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- family_relationship -->
<g id="node19" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1482" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1482" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1474.7118,-260.5723C1471.8657,-250.1798 1470.6157,-237.4298 1477,-228 1483.7811,-217.984 1493.8489,-210.7545 1504.8233,-205.5363"/>
<polygon fill="#000000" stroke="#000000" points="1506.3305,-208.6997 1514.2028,-201.609 1503.627,-202.2428 1506.3305,-208.6997"/>
<text text-anchor="middle" x="1556.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1653" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1653" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1650.4189,-260.8085C1648.1312,-250.2414 1643.8703,-237.2341 1636,-228 1630.3305,-221.348 1623.1205,-215.7591 1615.5106,-211.1208"/>
<polygon fill="#000000" stroke="#000000" points="1616.905,-207.8921 1606.4618,-206.1058 1613.5117,-214.0146 1616.905,-207.8921"/>
<text text-anchor="middle" x="1687.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_surgery -->
<g id="node22" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1823" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1823" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1797.889,-261.5849C1780.8412,-250.4965 1757.4057,-236.6432 1735,-228 1702.7309,-215.5519 1665.2282,-206.9948 1633.853,-201.3576"/>
<polygon fill="#000000" stroke="#000000" points="1634.3472,-197.8912 1623.8959,-199.6288 1633.1497,-204.788 1634.3472,-197.8912"/>
<text text-anchor="middle" x="1843.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_arm -->
<g id="node23" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1565" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1565" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1545.2982,-87.7929C1530.5819,-76.0332 1509.3963,-61.3036 1488,-54 1406.2565,-26.097 1148.2471,-19.8166 1041.7146,-18.4066"/>
<polygon fill="#000000" stroke="#000000" points="1041.6307,-14.9054 1031.5881,-18.2814 1041.544,-21.9049 1041.6307,-14.9054"/>
<text text-anchor="middle" x="1565.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- survival -->
<g id="node24" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1988" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1988" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1972.4442,-261.6911C1960.8699,-250.0435 1944.0165,-235.4934 1926,-228 1875.8792,-207.154 1729.0694,-198.0334 1639.4677,-194.3165"/>
<polygon fill="#000000" stroke="#000000" points="1639.5044,-190.8152 1629.3718,-193.9105 1639.223,-197.8096 1639.5044,-190.8152"/>
<text text-anchor="middle" x="1989.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node25" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1938" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1984.8762,-443.7272C2011.8563,-437.3335 2041.9692,-428.0168 2050,-417 2055.0501,-410.0721 2089.0498,-487.4685 2045,-261 2042.0203,-245.6808 2045.428,-237.4393 2033,-228 2002.4383,-204.7879 1762.5602,-196.223 1639.4214,-193.3333"/>
<polygon fill="#000000" stroke="#000000" points="1639.3975,-189.8319 1629.3203,-193.1028 1639.2378,-196.8301 1639.3975,-189.8319"/>
<text text-anchor="middle" x="2101.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1892.79,-442.7401C1867.2442,-436.4079 1834.93,-427.4946 1807,-417 1792.6721,-411.6164 1790.716,-406.2084 1776,-402 1724.1897,-387.1835 1573.999,-375.1397 1492.7319,-369.486"/>
<polygon fill="#000000" stroke="#000000" points="1492.9125,-365.9902 1482.6959,-368.7959 1492.4322,-372.9737 1492.9125,-365.9902"/>
<text text-anchor="middle" x="1851.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node26" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1439" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1439" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1439,-434.9735C1439,-423.1918 1439,-407.5607 1439,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="1442.5001,-394.0033 1439,-384.0034 1435.5001,-394.0034 1442.5001,-394.0033"/>
<text text-anchor="middle" x="1530.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- pdx -->
<g id="node27" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2588" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2588" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2573.4293,-263.3279C2561.0592,-251.2085 2542.1483,-235.3041 2522,-228 2480.755,-213.0479 1855.6079,-198.2255 1639.69,-193.5276"/>
<polygon fill="#000000" stroke="#000000" points="1639.4887,-190.0226 1629.4152,-193.305 1639.337,-197.0209 1639.4887,-190.0226"/>
<text text-anchor="middle" x="2571" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2598.2014,-262.1106C2603.3144,-251.2441 2606.9135,-237.4406 2599,-228 2314.5419,111.3524 2057.7968,-105.5285 1618,-54 1403.6955,-28.8912 1145.7734,-21.0616 1041.8049,-18.8226"/>
<polygon fill="#000000" stroke="#000000" points="1041.7165,-15.3201 1031.6458,-18.6113 1041.5708,-22.3186 1041.7165,-15.3201"/>
<text text-anchor="middle" x="2551" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_other -->
<g id="node28" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2179" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2179" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2152.3317,-261.8272C2132.6289,-250.084 2104.7014,-235.3601 2078,-228 1997.6064,-205.8398 1760.7766,-196.8278 1639.8492,-193.5924"/>
<polygon fill="#000000" stroke="#000000" points="1639.6658,-190.0865 1629.5778,-193.3241 1639.4829,-197.0841 1639.6658,-190.0865"/>
<text text-anchor="middle" x="2184.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- synonym -->
<g id="node29" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="428" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="428" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M430.7935,-434.7388C434.1509,-405.5663 436.0382,-348.349 406,-315 385.3642,-292.0897 357.7623,-321.4682 339,-297 329.264,-284.3031 329.0586,-273.5367 339,-261 378.9892,-210.571 416.1956,-236.4393 480,-228 676.834,-201.965 1283.8547,-194.4104 1494.2816,-192.543"/>
<polygon fill="#000000" stroke="#000000" points="1494.3284,-196.0428 1504.2975,-192.4558 1494.2674,-189.0431 1494.3284,-196.0428"/>
<text text-anchor="middle" x="459.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M378.5867,-447.3902C310.1917,-436.5687 195,-405.9552 195,-322.5 195,-322.5 195,-322.5 195,-105 195,-66.8337 778.0536,-30.4261 948.646,-20.5906"/>
<polygon fill="#000000" stroke="#000000" points="949.0263,-24.0746 958.8096,-20.008 948.6257,-17.0861 949.0263,-24.0746"/>
<text text-anchor="middle" x="237.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M478.4678,-448.5548C579.7858,-439.6409 815.1843,-418.9811 1013,-402 1146.7599,-390.5176 1304.1711,-377.2891 1385.0354,-370.5142"/>
<polygon fill="#000000" stroke="#000000" points="1385.7824,-373.964 1395.4553,-369.6415 1385.1981,-366.9884 1385.7824,-373.964"/>
<text text-anchor="middle" x="1055.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- generic_file -->
<g id="node30" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2682" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2682" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2684.4127,-434.7515C2689.2932,-388.9565 2694.4277,-269.8512 2623,-228 2580.673,-203.1996 1871.5523,-194.7082 1639.7066,-192.5875"/>
<polygon fill="#000000" stroke="#000000" points="1639.718,-189.0876 1629.6868,-192.4972 1639.6548,-196.0873 1639.718,-189.0876"/>
<text text-anchor="middle" x="2735" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge41" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2739.4716,-444.1689C2822.4573,-427.7866 2966,-384.2391 2966,-279 2966,-279 2966,-279 2966,-105 2966,-55.2289 1340.3499,-24.1034 1041.8039,-18.807"/>
<polygon fill="#000000" stroke="#000000" points="1041.8087,-15.3066 1031.7484,-18.6295 1041.685,-22.3055 1041.8087,-15.3066"/>
<text text-anchor="middle" x="3019" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge42" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2621.3651,-445.9171C2526.0526,-435.0111 2335.2946,-414.1028 2173,-402 1919.2551,-383.0775 1615.3905,-371.789 1493.5012,-367.7245"/>
<polygon fill="#000000" stroke="#000000" points="1493.4233,-364.2201 1483.313,-367.3875 1493.1918,-371.2162 1493.4233,-364.2201"/>
<text text-anchor="middle" x="2394" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1394.8266,-364.2596C1228.3935,-357.4917 639.306,-331.5795 455,-297 450.9198,-296.2345 446.7226,-295.2786 442.541,-294.2091"/>
<polygon fill="#000000" stroke="#000000" points="443.445,-290.8278 432.8744,-291.5432 441.584,-297.5759 443.445,-290.8278"/>
<text text-anchor="middle" x="799.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1402.4232,-355.6606C1350.7711,-339.2296 1266.298,-304.5187 1300,-261 1324.1684,-229.7918 1427.9732,-210.1602 1498.7994,-200.1395"/>
<polygon fill="#000000" stroke="#000000" points="1499.5696,-203.5664 1508.9964,-198.7306 1498.6114,-196.6323 1499.5696,-203.5664"/>
<text text-anchor="middle" x="1336.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1483.1497,-364.3011C1595.6141,-359.8616 1902.0233,-347.0653 2157,-330 2244.666,-324.1326 2466.2783,-320.2806 2551,-297 2552.9631,-296.4606 2554.9477,-295.8181 2556.9246,-295.1024"/>
<polygon fill="#000000" stroke="#000000" points="2558.7371,-298.1381 2566.611,-291.0491 2556.035,-291.6806 2558.7371,-298.1381"/>
<text text-anchor="middle" x="2454.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node32" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2413" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2413" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2371.3618,-261.9435C2340.6009,-250.1759 2297.4017,-235.3721 2258,-228 2141.2025,-206.147 1792.2722,-196.5704 1639.7289,-193.3466"/>
<polygon fill="#000000" stroke="#000000" points="1639.6008,-189.8433 1629.5301,-193.1344 1639.4551,-196.8418 1639.6008,-189.8433"/>
<text text-anchor="middle" x="2416" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
</g>
</svg>
</div>
