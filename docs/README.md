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
<svg width="4909pt" height="392pt"
 viewBox="0.00 0.00 4909.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 4905.3351,-388 4905.3351,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="3420.5404" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="3420.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2467.5404" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2467.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3389.2176,-262.1401C3365.3743,-250.2238 3331.3463,-235.1481 3299.5404,-228 3226.6481,-211.6182 2729.0736,-198.2213 2540.1217,-193.6686"/>
<polygon fill="#000000" stroke="#000000" points="2540.0912,-190.167 2530.0102,-193.4264 2539.9235,-197.165 2540.0912,-190.167"/>
<text text-anchor="middle" x="3411.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_radiation -->
<g id="node2" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1678.5404" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1678.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1698.2158,-261.1425C1712.4626,-249.4005 1732.7906,-234.9633 1753.5404,-228 1813.1418,-207.9986 2225.6439,-197.1073 2395.107,-193.4344"/>
<polygon fill="#000000" stroke="#000000" points="2395.2606,-196.932 2405.1832,-193.2183 2395.1105,-189.9336 2395.2606,-196.932"/>
<text text-anchor="middle" x="1836.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- cytogenomic_file -->
<g id="node3" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="324.5404" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="324.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node26" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="911.5404" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="911.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M348.7024,-348.5659C366.3173,-336.8593 391.2562,-322.29 415.5404,-315 436.4273,-308.7298 733.3721,-289.9285 857.5579,-282.2851"/>
<polygon fill="#000000" stroke="#000000" points="857.8453,-285.7741 867.6118,-281.6675 857.416,-278.7873 857.8453,-285.7741"/>
<text text-anchor="middle" x="487.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- consent_group -->
<g id="node22" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="3197.5404" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="3197.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge34" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2525.4324,-185.1005C2655.0685,-169.6508 2968.9219,-132.2463 3117.2876,-114.5644"/>
<polygon fill="#000000" stroke="#000000" points="3117.7327,-118.0362 3127.2482,-113.3773 3116.9043,-111.0854 3117.7327,-118.0362"/>
<text text-anchor="middle" x="2926.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3713.5404" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3713.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3711.9254,-347.9701C3710.5606,-337.9461 3708.0674,-325.4285 3703.5404,-315 3691.7517,-287.8436 3689.3645,-277.131 3664.5404,-261 3604.7521,-222.1488 3578.3225,-236.5987 3507.5404,-228 3319.9121,-205.2068 2744.2401,-195.6237 2540.1871,-192.8832"/>
<polygon fill="#000000" stroke="#000000" points="2539.9302,-189.3796 2529.8846,-192.7464 2539.8372,-196.3789 2539.9302,-189.3796"/>
<text text-anchor="middle" x="3737.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node20" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3972.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3972.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3752.5018,-354.0126C3813.243,-335.2365 3923.8898,-300.6448 3926.5404,-297 3935.9506,-284.0599 3931.4794,-276.2186 3926.5404,-261 3917.896,-234.3641 3898.1848,-236.6359 3889.5404,-210 3884.6013,-194.7814 3886.1287,-189.632 3889.5404,-174 3902.0503,-116.6809 3914.1054,-104.1567 3944.5404,-54 3946.8046,-50.2685 3949.3921,-46.4748 3952.0585,-42.8187"/>
<polygon fill="#000000" stroke="#000000" points="3955.0226,-44.7038 3958.3086,-34.6314 3949.4586,-40.4562 3955.0226,-44.7038"/>
<text text-anchor="middle" x="3932.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3661.5293,-364.3911C3451.6016,-357.9133 2646.219,-333.2155 1983.5404,-315 1669.7791,-306.3754 1591.2016,-308.7099 1277.5404,-297 1166.6531,-292.8603 1036.9649,-286.0057 965.5711,-282.0575"/>
<polygon fill="#000000" stroke="#000000" points="965.6484,-278.5565 955.4698,-281.4967 965.2604,-285.5457 965.6484,-278.5565"/>
<text text-anchor="middle" x="2549.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx -->
<g id="node6" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="815.5404" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="815.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge28" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M842.9788,-188.0828C871.544,-184.108 917.6062,-177.988 957.5404,-174 2161.1714,-53.8009 3644.9349,-23.5395 3925.5747,-18.744"/>
<polygon fill="#000000" stroke="#000000" points="3925.8611,-22.2397 3935.8006,-18.5715 3925.7429,-15.2407 3925.8611,-22.2397"/>
<text text-anchor="middle" x="2084.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M791.538,-201.5347C771.0048,-211.096 746.6527,-226.7034 759.5404,-243 771.8166,-258.5234 819.5043,-268.048 858.2335,-273.368"/>
<polygon fill="#000000" stroke="#000000" points="858.0002,-276.8673 868.3699,-274.6948 858.9088,-269.9265 858.0002,-276.8673"/>
<text text-anchor="middle" x="783.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="4018.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="4018.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4009.0091,-86.9735C4002.5519,-74.7609 3993.9078,-58.4123 3986.656,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="3989.6704,-42.9101 3981.902,-35.7057 3983.4821,-46.182 3989.6704,-42.9101"/>
<text text-anchor="middle" x="4048.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- laboratory_test -->
<g id="node8" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1215.5404" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1215.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1264.0162,-351.3724C1276.2661,-346.0467 1288.7166,-339.0408 1298.5404,-330 1324.1451,-306.436 1307.1417,-281.1093 1335.5404,-261 1413.7207,-205.64 1453.1893,-237.2233 1548.5404,-228 1712.3197,-212.1576 2208.0551,-198.4901 2395.079,-193.7642"/>
<polygon fill="#000000" stroke="#000000" points="2395.4422,-197.2563 2405.351,-193.5058 2395.2661,-190.2585 2395.4422,-197.2563"/>
<text text-anchor="middle" x="1401.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1146.9294,-356.118C1117.9906,-350.5453 1084.3923,-342.1851 1055.5404,-330 1044.2979,-325.2519 1043.6153,-320.1268 1032.5404,-315 1009.6708,-304.4133 982.9344,-296.0741 960.4187,-290.0992"/>
<polygon fill="#000000" stroke="#000000" points="961.2834,-286.7077 950.7264,-287.6023 959.537,-293.4864 961.2834,-286.7077"/>
<text text-anchor="middle" x="1121.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1854.5404" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1854.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1881.0899,-263.3452C1902.7576,-251.4065 1934.5804,-235.7392 1964.5404,-228 2043.8182,-207.5211 2275.778,-197.7493 2394.9799,-193.9711"/>
<polygon fill="#000000" stroke="#000000" points="2395.2224,-197.4653 2405.1087,-193.6559 2395.0046,-190.4687 2395.2224,-197.4653"/>
<text text-anchor="middle" x="2008.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_surgery -->
<g id="node10" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2024.5404" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2024.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2037.7275,-261.1554C2047.3667,-249.579 2061.516,-235.3318 2077.5404,-228 2105.702,-215.1149 2291.2969,-202.337 2395.9866,-196.0394"/>
<polygon fill="#000000" stroke="#000000" points="2396.3933,-199.5215 2406.1671,-195.4321 2395.9763,-192.5339 2396.3933,-199.5215"/>
<text text-anchor="middle" x="2156.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_admin -->
<g id="node11" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="4169.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="4169.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4150.967,-87.4419C4138.4283,-76.437 4121.0308,-62.7319 4103.5404,-54 4076.3411,-40.4211 4043.3231,-31.3899 4017.2402,-25.7692"/>
<polygon fill="#000000" stroke="#000000" points="4017.7506,-22.3008 4007.2497,-23.7085 4016.3365,-29.1565 4017.7506,-22.3008"/>
<text text-anchor="middle" x="4183.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M123.8981,-347.9585C134.8156,-336.452 150.5156,-322.3638 167.5404,-315 380.3943,-222.9331 455.2736,-278.2859 686.5404,-261 861.7893,-247.9011 909.3813,-278.2847 1081.5404,-243 1100.1404,-239.1878 1102.9053,-231.6372 1121.5404,-228 1246.4197,-203.6263 2132.4161,-194.6722 2394.6167,-192.5392"/>
<polygon fill="#000000" stroke="#000000" points="2394.8167,-196.0378 2404.7882,-192.4574 2394.7603,-189.0381 2394.8167,-196.0378"/>
<text text-anchor="middle" x="772.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M111.8702,-347.7395C114.7792,-330.1836 118.5404,-302.8697 118.5404,-279 118.5404,-279 118.5404,-279 118.5404,-105 118.5404,-54.937 3488.0381,-22.4322 3925.8535,-18.42"/>
<polygon fill="#000000" stroke="#000000" points="3925.9702,-21.9192 3935.9378,-18.3279 3925.9062,-14.9195 3925.9702,-21.9192"/>
<text text-anchor="middle" x="204.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M134.404,-348.3667C153.2313,-336.5662 179.8311,-321.9667 205.5404,-315 290.9934,-291.844 515.1242,-301.5828 603.5404,-297 692.5371,-292.3872 795.9464,-286.1674 857.4449,-282.3777"/>
<polygon fill="#000000" stroke="#000000" points="857.9213,-285.8551 867.6865,-281.7452 857.4897,-278.8684 857.9213,-285.8551"/>
<text text-anchor="middle" x="291.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_funding -->
<g id="node13" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="4335.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="4335.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4310.5591,-87.7695C4292.6949,-76.3151 4267.6432,-61.9639 4243.5404,-54 4202.9021,-40.5725 4085.0209,-28.1969 4018.9013,-22.0553"/>
<polygon fill="#000000" stroke="#000000" points="4019.0317,-18.5527 4008.7536,-21.124 4018.3919,-25.5234 4019.0317,-18.5527"/>
<text text-anchor="middle" x="4339.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node14" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="934.5404" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="934.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M912.1025,-348.2721C907.0099,-342.9925 902.2948,-336.7844 899.5404,-330 896.5427,-322.6164 897.0022,-314.3135 898.9037,-306.5853"/>
<polygon fill="#000000" stroke="#000000" points="902.2949,-307.4748 902.0645,-296.8824 895.6391,-305.3065 902.2949,-307.4748"/>
<text text-anchor="middle" x="966.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1015.5404" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1015.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1064.3975,-189.1251C1417.9802,-168.3191 3580.8967,-41.0457 3926.1037,-20.7325"/>
<polygon fill="#000000" stroke="#000000" points="3926.4665,-24.2173 3936.2436,-20.1358 3926.0552,-17.2294 3926.4665,-24.2173"/>
<text text-anchor="middle" x="2828.0404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M972.7525,-201.0373C946.4683,-207.554 916.3753,-217.0975 908.5404,-228 903.8092,-234.5836 902.8391,-242.9677 903.5474,-251.0272"/>
<polygon fill="#000000" stroke="#000000" points="900.0961,-251.6099 905.1854,-260.9024 907.0017,-250.4644 900.0961,-251.6099"/>
<text text-anchor="middle" x="949.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1435.5404" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1435.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1466.4017,-351.1443C1474.4173,-345.681 1482.0529,-338.6605 1486.5404,-330 1489.6075,-324.0808 1488.346,-321.4175 1486.5404,-315 1484.001,-305.9749 1478.0797,-306.0251 1475.5404,-297 1471.2068,-281.598 1465.0056,-273.0424 1475.5404,-261 1505.7865,-226.4255 2171.6385,-201.6411 2395.1352,-194.2714"/>
<polygon fill="#000000" stroke="#000000" points="2395.5593,-197.7595 2405.4392,-193.9337 2395.3299,-190.7632 2395.5593,-197.7595"/>
<text text-anchor="middle" x="1520.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge42" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1385.1993,-358.7811C1344.3204,-352.4894 1285.3313,-342.4324 1234.5404,-330 1212.8305,-324.686 1208.3692,-319.8018 1186.5404,-315 1110.6162,-298.2986 1021.0787,-288.3445 965.2972,-283.27"/>
<polygon fill="#000000" stroke="#000000" points="965.5563,-279.7793 955.2853,-282.3788 964.9355,-286.7518 965.5563,-279.7793"/>
<text text-anchor="middle" x="1279.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- generic_file -->
<g id="node17" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="3849.5404" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="3849.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3843.4814,-347.7884C3834.4662,-323.7307 3815.1092,-281.9629 3783.5404,-261 3708.124,-210.9207 3672.6397,-236.8128 3582.5404,-228 3379.2577,-208.1166 2754.0568,-196.5597 2540.1757,-193.1061"/>
<polygon fill="#000000" stroke="#000000" points="2540.0569,-189.6038 2530.002,-192.9429 2539.9446,-196.6029 2540.0569,-189.6038"/>
<text text-anchor="middle" x="3869.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3900.4751,-354.6252C3931.1648,-344.8642 3967.8236,-327.3833 3986.5404,-297 3996.8549,-280.2561 3991.4407,-212.1561 3978.5404,-174 3969.9699,-148.6505 3953.94,-148.7156 3946.5404,-123 3938.9296,-96.5507 3948.5539,-65.9728 3958.1741,-44.6617"/>
<polygon fill="#000000" stroke="#000000" points="3961.3656,-46.1008 3962.532,-35.5703 3955.0533,-43.075 3961.3656,-46.1008"/>
<text text-anchor="middle" x="4039.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3803.0123,-353.2518C3793.6506,-351.1354 3783.8325,-349.2315 3774.5404,-348 3254.8791,-279.1284 3119.632,-325.9128 2595.5404,-315 2009.8349,-302.8042 1863.084,-315.3912 1277.5404,-297 1166.6305,-293.5165 1036.9505,-286.4239 965.5642,-282.2574"/>
<polygon fill="#000000" stroke="#000000" points="965.6519,-278.7566 955.464,-281.6646 965.2417,-285.7446 965.6519,-278.7566"/>
<text text-anchor="middle" x="3655.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="547.5404" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="547.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M552.6938,-347.9083C556.9204,-336.5343 564.1082,-322.6168 575.5404,-315 598.4352,-299.7461 768.1649,-287.5185 857.2639,-282.0717"/>
<polygon fill="#000000" stroke="#000000" points="857.6829,-285.5528 867.4539,-281.4568 857.2612,-278.5655 857.6829,-285.5528"/>
<text text-anchor="middle" x="667.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_status -->
<g id="node19" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="4501.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="4501.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4476.681,-88.1592C4457.9783,-76.4169 4431.2536,-61.5513 4405.5404,-54 4334.1371,-33.0308 4115.5789,-22.9997 4019.1203,-19.5024"/>
<polygon fill="#000000" stroke="#000000" points="4019.1935,-16.0029 4009.0756,-19.1459 4018.9451,-22.9985 4019.1935,-16.0029"/>
<text text-anchor="middle" x="4497.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- genetic_analysis -->
<g id="node21" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2569.5404" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2569.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2656.139,-362.842C2884.1326,-354.1101 3485.5245,-328.2117 3514.5404,-297 3525.4343,-285.2816 3520.4317,-275.8759 3514.5404,-261 3507.1309,-242.2907 3501.8647,-236.316 3483.5404,-228 3440.7278,-208.5707 2765.1798,-196.5428 2539.9668,-193.0572"/>
<polygon fill="#000000" stroke="#000000" points="2539.9584,-189.5568 2529.9058,-192.9026 2539.8507,-196.5559 2539.9584,-189.5568"/>
<text text-anchor="middle" x="3590.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2484.4663,-361.5359C2188.3787,-345.9994 1207.8769,-294.5496 965.8889,-281.8518"/>
<polygon fill="#000000" stroke="#000000" points="965.7606,-278.3404 955.5909,-281.3115 965.3937,-285.3307 965.7606,-278.3404"/>
<text text-anchor="middle" x="1909.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge3" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3268.7158,-97.01C3425.5597,-79.403 3797.2979,-37.6724 3926.969,-23.1158"/>
<polygon fill="#000000" stroke="#000000" points="3927.4152,-26.5877 3936.9623,-21.9939 3926.6342,-19.6314 3927.4152,-26.5877"/>
<text text-anchor="middle" x="3694.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- survival -->
<g id="node23" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2189.5404" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2189.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2209.4903,-262.4623C2224.3267,-251.0266 2245.554,-236.4093 2266.5404,-228 2308.0135,-211.3816 2357.3666,-202.4007 2396.7896,-197.5651"/>
<polygon fill="#000000" stroke="#000000" points="2397.3191,-201.0272 2406.8473,-196.3942 2396.5096,-194.0741 2397.3191,-201.0272"/>
<text text-anchor="middle" x="2306.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2355.5404" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2355.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2350.6128,-260.8574C2348.8659,-250.3076 2348.76,-237.3014 2355.5404,-228 2362.1429,-218.9425 2383.6717,-211.0341 2406.114,-204.9545"/>
<polygon fill="#000000" stroke="#000000" points="2407.2845,-208.2671 2416.0917,-202.3778 2405.5342,-201.4895 2407.2845,-208.2671"/>
<text text-anchor="middle" x="2435.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="4676.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="4676.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4645.2373,-88.0545C4621.8113,-76.2601 4588.5941,-61.3751 4557.5404,-54 4455.6739,-29.8071 4139.5559,-21.2467 4019.4701,-18.8194"/>
<polygon fill="#000000" stroke="#000000" points="4019.2111,-15.3137 4009.1442,-18.6161 4019.0733,-22.3123 4019.2111,-15.3137"/>
<text text-anchor="middle" x="4670.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M952.3358,-271.7624C1028.5235,-258.2937 1187.0574,-230.512 1212.5404,-228 1444.2027,-205.1635 2162.9369,-195.3733 2394.7041,-192.7564"/>
<polygon fill="#000000" stroke="#000000" points="2395.0816,-196.2525 2405.0418,-192.6408 2395.0033,-189.2529 2395.0816,-196.2525"/>
<text text-anchor="middle" x="1249.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M874.0651,-269.4449C850.6109,-262.6306 823.5528,-252.9465 816.5404,-243 811.9279,-236.4576 810.4479,-228.1771 810.4635,-220.2015"/>
<polygon fill="#000000" stroke="#000000" points="813.966,-220.2937 811.2076,-210.0642 806.9848,-219.7811 813.966,-220.2937"/>
<text text-anchor="middle" x="853.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M948.9532,-269.2178C964.3447,-263.6364 981.3765,-255.2424 993.5404,-243 999.9886,-236.5102 1004.679,-227.8259 1008.0288,-219.4651"/>
<polygon fill="#000000" stroke="#000000" points="1011.3592,-220.5445 1011.3704,-209.9497 1004.7547,-218.2251 1011.3592,-220.5445"/>
<text text-anchor="middle" x="1041.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_response -->
<g id="node27" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2578.5404" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2578.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2558.6408,-261.3059C2547.1348,-251.2741 2532.2611,-238.6395 2518.5404,-228 2512.7111,-223.4798 2506.3764,-218.8184 2500.2172,-214.4105"/>
<polygon fill="#000000" stroke="#000000" points="2502.1767,-211.5095 2491.9909,-208.5939 2498.1353,-217.2251 2502.1767,-211.5095"/>
<text text-anchor="middle" x="2619.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node28" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2830.5404" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2830.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2794.7258,-261.5735C2770.3845,-250.4076 2737.1643,-236.4705 2706.5404,-228 2650.8489,-212.5958 2585.9174,-203.3472 2537.8007,-198.0891"/>
<polygon fill="#000000" stroke="#000000" points="2538.1114,-194.6025 2527.7977,-197.0269 2537.3721,-201.5634 2538.1114,-194.6025"/>
<text text-anchor="middle" x="2849.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- treatment_other -->
<g id="node29" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="3064.5404" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3064.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3035.569,-261.8809C3014.2132,-250.1637 2984.0416,-235.4489 2955.5404,-228 2879.1474,-208.0345 2656.3909,-198.0826 2540.1086,-194.129"/>
<polygon fill="#000000" stroke="#000000" points="2539.9893,-190.6231 2529.878,-193.7873 2539.7555,-197.6192 2539.9893,-190.6231"/>
<text text-anchor="middle" x="3065.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- radiology_file -->
<g id="node30" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="3243.5404" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="3243.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3216.6272,-262.2C3196.0734,-250.3142 3166.5987,-235.2505 3138.5404,-228 3081.8624,-213.3539 2701.5699,-199.5438 2539.9682,-194.2623"/>
<polygon fill="#000000" stroke="#000000" points="2539.7543,-190.7536 2529.6458,-193.9268 2539.5268,-197.7499 2539.7543,-190.7536"/>
<text text-anchor="middle" x="3236.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pathology_file -->
<g id="node31" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="757.5404" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="757.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M758.1315,-347.6779C759.4489,-336.7939 762.9011,-323.5003 771.5404,-315 784.1588,-302.5846 825.3851,-292.9203 859.8573,-286.7453"/>
<polygon fill="#000000" stroke="#000000" points="860.5773,-290.1728 869.8343,-285.0193 859.384,-283.2752 860.5773,-290.1728"/>
<text text-anchor="middle" x="832.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_arm -->
<g id="node32" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="4841.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="4841.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M4816.993,-88.3833C4797.8823,-76.4254 4770.2079,-61.187 4743.5404,-54 4673.8987,-35.2313 4176.0491,-22.5688 4019.5201,-19.0172"/>
<polygon fill="#000000" stroke="#000000" points="4019.3565,-15.5127 4009.2803,-18.7868 4019.199,-22.5109 4019.3565,-15.5127"/>
<text text-anchor="middle" x="4828.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
