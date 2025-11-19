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
<svg width="2776pt" height="392pt"
 viewBox="0.00 0.00 2775.64 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2771.6442,-388 2771.6442,4 -4,4"/>
<!-- generic_file -->
<g id="node1" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="65.6442" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="65.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1267.6442" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1267.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M79.1235,-348.2781C104.0447,-317.1163 160.7429,-253.4061 225.6442,-228 248.2087,-219.167 962.4542,-199.9135 1195.1495,-193.8602"/>
<polygon fill="#000000" stroke="#000000" points="1195.2986,-197.3576 1205.2043,-193.5991 1195.1168,-190.36 1195.2986,-197.3576"/>
<text text-anchor="middle" x="220.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="435.6442" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="435.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M93.4618,-349.6329C114.296,-338.1261 143.8723,-323.3475 171.6442,-315 242.1857,-293.797 327.1149,-285.0427 381.2396,-281.454"/>
<polygon fill="#000000" stroke="#000000" points="381.5472,-284.9417 391.3085,-280.8225 381.109,-277.9554 381.5472,-284.9417"/>
<text text-anchor="middle" x="224.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="944.6442" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="944.6442" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M65.6442,-347.6694C65.6442,-330.0629 65.6442,-302.7135 65.6442,-279 65.6442,-279 65.6442,-279 65.6442,-105 65.6442,-62.7622 716.8602,-28.7804 898.2469,-20.1346"/>
<polygon fill="#000000" stroke="#000000" points="898.4479,-23.6291 908.2711,-19.6598 898.1167,-16.6369 898.4479,-23.6291"/>
<text text-anchor="middle" x="118.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- consent_group -->
<g id="node14" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1089.6442" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1089.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge34" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1235.8213,-176.4461C1206.9699,-162.3446 1164.2165,-141.4483 1132.3908,-125.893"/>
<polygon fill="#000000" stroke="#000000" points="1133.8306,-122.7011 1123.3093,-121.4543 1130.7567,-128.9901 1133.8306,-122.7011"/>
<text text-anchor="middle" x="1239.1442" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1590.6442" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1590.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1616.7135,-348.9045C1646.1944,-327.4979 1687.1046,-290.1036 1662.6442,-261 1622.2643,-212.9549 1442.8156,-198.3595 1340.2294,-193.9287"/>
<polygon fill="#000000" stroke="#000000" points="1340.0755,-190.4196 1329.9406,-193.5072 1339.7889,-197.4137 1340.0755,-190.4196"/>
<text text-anchor="middle" x="1735.1442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1514.4729,-359.2051C1427.9264,-351.1925 1295.7607,-337.9603 1273.6442,-330 1262.1613,-325.867 1262.3004,-318.6154 1250.6442,-315 1169.7555,-289.9108 572.0334,-311.7877 488.6442,-297 484.9335,-296.342 481.1307,-295.4702 477.349,-294.4646"/>
<polygon fill="#000000" stroke="#000000" points="478.0472,-291.0214 467.4653,-291.5449 476.064,-297.7346 478.0472,-291.0214"/>
<text text-anchor="middle" x="1339.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- publication -->
<g id="node4" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="349.6442" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="349.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M369.0438,-87.7685C383.5466,-75.9968 404.4493,-61.2631 425.6442,-54 469.6541,-38.9185 778.9921,-24.7945 898.0738,-19.8555"/>
<polygon fill="#000000" stroke="#000000" points="898.4759,-23.342 908.3235,-19.4336 898.1879,-16.3479 898.4759,-23.342"/>
<text text-anchor="middle" x="476.6442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="507.6442" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="507.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M517.0939,-86.9525C524.1498,-75.4434 534.9274,-61.3545 548.6442,-54 578.8019,-37.8303 799.7933,-25.1125 897.9213,-20.1993"/>
<polygon fill="#000000" stroke="#000000" points="898.3285,-23.6835 908.1433,-19.6935 897.9825,-16.6921 898.3285,-23.6835"/>
<text text-anchor="middle" x="610.6442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M469.6708,-267.4513C500.5851,-256.9578 541.4214,-243.093 541.6442,-243 555.4004,-237.2564 557.2292,-231.7987 571.6442,-228 630.6638,-212.4471 1029.0267,-199.0468 1195.1372,-194.0679"/>
<polygon fill="#000000" stroke="#000000" points="1195.3689,-197.5626 1205.2602,-193.7663 1195.1603,-190.5657 1195.3689,-197.5626"/>
<text text-anchor="middle" x="608.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node10" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="502.6442" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="502.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M416.9681,-262.4176C407.7497,-252.1884 400.0687,-238.9719 407.6442,-228 414.7029,-217.7766 442.761,-207.9034 466.5693,-201.0907"/>
<polygon fill="#000000" stroke="#000000" points="467.7309,-204.4011 476.4391,-198.3663 465.8683,-197.6534 467.7309,-204.4011"/>
<text text-anchor="middle" x="444.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node27" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="302.6442" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="302.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M391.4884,-277.5262C338.2302,-274.7109 253.3716,-266.554 233.6442,-243 222.0019,-229.0994 237.0304,-216.8876 255.9991,-207.9012"/>
<polygon fill="#000000" stroke="#000000" points="257.4508,-211.0866 265.2176,-203.8805 254.6522,-204.6703 257.4508,-211.0866"/>
<text text-anchor="middle" x="270.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pathology_file -->
<g id="node7" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="225.6442" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="225.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M250.0575,-348.7708C266.3337,-337.9008 288.5392,-324.2225 309.6442,-315 334.1783,-304.279 362.7837,-295.807 386.5321,-289.782"/>
<polygon fill="#000000" stroke="#000000" points="387.5164,-293.1442 396.3866,-287.3502 385.8393,-286.348 387.5164,-293.1442"/>
<text text-anchor="middle" x="370.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- genetic_analysis -->
<g id="node8" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1297.6442" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1297.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1378.7244,-358.9961C1465.6606,-351.0893 1592.315,-338.2547 1599.6442,-330 1604.0704,-325.0148 1603.7871,-320.2231 1599.6442,-315 1577.8038,-287.4653 1554.3383,-312.1869 1522.6442,-297 1499.2321,-285.7817 1498.4081,-275.153 1476.6442,-261 1450.4751,-243.9824 1443.8074,-239.1321 1414.6442,-228 1398.6826,-221.9072 1361.0031,-212.7145 1327.7899,-205.1437"/>
<polygon fill="#000000" stroke="#000000" points="1328.1805,-201.6437 1317.6548,-202.8514 1326.6363,-208.4712 1328.1805,-201.6437"/>
<text text-anchor="middle" x="1592.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1227.8573,-354.9298C1192.4764,-348.7213 1148.9909,-340.1752 1110.6442,-330 1090.6745,-324.7011 1086.9716,-318.6957 1066.6442,-315 813.7759,-269.0268 741.5389,-342.8274 488.6442,-297 484.936,-296.328 481.135,-295.4466 477.3544,-294.4345"/>
<polygon fill="#000000" stroke="#000000" points="478.0549,-290.9917 467.4725,-291.5047 476.0651,-297.7029 478.0549,-290.9917"/>
<text text-anchor="middle" x="1180.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_personnel -->
<g id="node9" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="689.6442" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="689.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M680.851,-86.9532C676.9943,-76.1729 674.8909,-62.8914 682.6442,-54 696.5931,-38.0033 827.0779,-26.3338 898.4759,-21.0861"/>
<polygon fill="#000000" stroke="#000000" points="898.8382,-24.5691 908.5604,-20.3586 898.3345,-17.5873 898.8382,-24.5691"/>
<text text-anchor="middle" x="752.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M497.2587,-210.1398C493.6302,-220.4364 488.1302,-233.1864 480.6442,-243 476.7417,-248.1159 471.9599,-252.9333 466.987,-257.2795"/>
<polygon fill="#000000" stroke="#000000" points="464.6543,-254.6654 459.1139,-263.6963 469.0767,-260.0915 464.6543,-254.6654"/>
<text text-anchor="middle" x="513.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge40" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M530.6858,-190.2126C600.9677,-185.5425 783.1844,-172.207 841.6442,-156 875.1769,-146.7036 889.8102,-149.2579 912.6442,-123 931.3202,-101.5235 939.0964,-69.3693 942.3342,-46.3053"/>
<polygon fill="#000000" stroke="#000000" points="945.8412,-46.4553 943.5563,-36.1098 938.891,-45.6221 945.8412,-46.4553"/>
<text text-anchor="middle" x="955.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="849.6442" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="849.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M833.3114,-348.2157C821.3636,-336.5073 804.0798,-322.0802 785.6442,-315 723.9187,-291.2942 553.5253,-309.745 488.6442,-297 484.9969,-296.2835 481.2563,-295.3793 477.5318,-294.3595"/>
<polygon fill="#000000" stroke="#000000" points="478.369,-290.9567 467.7851,-291.4393 476.3599,-297.6622 478.369,-290.9567"/>
<text text-anchor="middle" x="877.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2247.6442" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2247.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2205.0536,-263.3889C2170.2321,-251.3906 2119.4463,-235.6209 2073.6442,-228 1933.7545,-204.7242 1510.9007,-195.7465 1340.2352,-193.0103"/>
<polygon fill="#000000" stroke="#000000" points="1340.1501,-189.5086 1330.0961,-192.8504 1340.0396,-196.5077 1340.1501,-189.5086"/>
<text text-anchor="middle" x="2204.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge26" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1061.3425,-88.019C1037.1195,-73.4852 1002.2522,-52.5648 976.9429,-37.3792"/>
<polygon fill="#000000" stroke="#000000" points="978.4639,-34.2102 968.0882,-32.0664 974.8624,-40.2127 978.4639,-34.2102"/>
<text text-anchor="middle" x="1089.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1851.6442" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1851.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1848.7283,-347.6419C1843.9321,-323.8156 1832.0216,-282.7269 1804.6442,-261 1768.7741,-232.5334 1476.3434,-207.4229 1338.7375,-197.0542"/>
<polygon fill="#000000" stroke="#000000" points="1338.9374,-193.5595 1328.7041,-196.3037 1338.4151,-200.54 1338.9374,-193.5595"/>
<text text-anchor="middle" x="1917.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1769.0584,-354.2225C1679.5086,-342.0036 1532.2617,-323.5152 1404.6442,-315 1201.501,-301.4454 689.1815,-332.1516 488.6442,-297 484.9322,-296.3493 481.1285,-295.4827 477.3462,-294.4805"/>
<polygon fill="#000000" stroke="#000000" points="478.0431,-291.0371 467.4615,-291.5662 476.0635,-297.7514 478.0431,-291.0371"/>
<text text-anchor="middle" x="1650.6442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1875.1356,-348.2847C1892.2975,-336.4457 1916.6671,-321.8336 1940.6442,-315 1995.7086,-299.3062 2410.1684,-331.7899 2455.6442,-297 2478.3657,-279.6175 2474.6442,-264.108 2474.6442,-235.5 2474.6442,-235.5 2474.6442,-235.5 2474.6442,-105 2474.6442,-28.7762 1248.2414,-19.3028 991.4441,-18.1547"/>
<polygon fill="#000000" stroke="#000000" points="991.345,-14.6543 981.3301,-18.1116 991.3151,-21.6543 991.345,-14.6543"/>
<text text-anchor="middle" x="2560.6442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1041.6442" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1041.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1053.3015,-348.3003C1062.0603,-336.6307 1075.177,-322.2152 1090.6442,-315 1144.3358,-289.9535 1306.6255,-328.753 1356.6442,-297 1370.76,-288.039 1396.6093,-241.4258 1386.6442,-228 1379.3474,-218.1692 1355.1501,-209.982 1330.4634,-203.912"/>
<polygon fill="#000000" stroke="#000000" points="1331.18,-200.4852 1320.6449,-201.6078 1329.5807,-207.3001 1331.18,-200.4852"/>
<text text-anchor="middle" x="1426.1442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1012.0639,-350.6388C1000.084,-344.34 986.1524,-336.9162 973.6442,-330 961.9693,-323.5446 960.4608,-318.7026 947.6442,-315 849.5761,-286.6687 589.0126,-315.6062 488.6442,-297 484.9895,-296.3225 481.2437,-295.4456 477.5156,-294.444"/>
<polygon fill="#000000" stroke="#000000" points="478.3458,-291.0397 467.7634,-291.5529 476.3562,-297.751 478.3458,-291.0397"/>
<text text-anchor="middle" x="1018.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node17" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2398.6442" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2398.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2370.9975,-264.0454C2346.8661,-251.8329 2310.5048,-235.423 2276.6442,-228 2186.1495,-208.1615 1556.9871,-196.5376 1340.5707,-193.0904"/>
<polygon fill="#000000" stroke="#000000" points="1340.3282,-189.5862 1330.2741,-192.9276 1340.2175,-196.5853 1340.3282,-189.5862"/>
<text text-anchor="middle" x="2360.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="597.6442" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="597.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M622.2307,-261.3478C642.3221,-246.9991 667.8518,-228.9721 670.6442,-228 718.9746,-211.1742 1046.9132,-198.9137 1195.1499,-194.1655"/>
<polygon fill="#000000" stroke="#000000" points="1195.6223,-197.6524 1205.5061,-193.8367 1195.4,-190.6559 1195.6223,-197.6524"/>
<text text-anchor="middle" x="750.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment -->
<g id="node19" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="773.6442" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="773.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M799.3824,-262.597C820.7774,-249.2765 849.7324,-232.0579 862.6442,-228 922.7254,-209.1177 1095.8118,-199.068 1195.1821,-194.7116"/>
<polygon fill="#000000" stroke="#000000" points="1195.6064,-198.1967 1205.4468,-194.2704 1195.3057,-191.2032 1195.6064,-198.1967"/>
<text text-anchor="middle" x="909.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="902.6442" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="902.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M926.381,-262.7539C944.5345,-251.1508 970.6205,-236.1982 995.6442,-228 1032.0268,-216.0805 1129.9643,-204.9357 1197.8083,-198.2924"/>
<polygon fill="#000000" stroke="#000000" points="1198.3899,-201.7526 1208.0062,-197.3054 1197.7155,-194.7851 1198.3899,-201.7526"/>
<text text-anchor="middle" x="1039.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node21" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1256.6442" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1256.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1229.6082,-88.3606C1210.023,-77.0286 1182.5439,-62.5803 1156.6442,-54 1101.1984,-35.6313 1034.3396,-26.2685 990.728,-21.7644"/>
<polygon fill="#000000" stroke="#000000" points="991.0013,-18.2745 980.7053,-20.7727 990.312,-25.2404 991.0013,-18.2745"/>
<text text-anchor="middle" x="1247.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_status -->
<g id="node22" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2199.6442" cy="-366" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2199.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- treatment_response -->
<g id="node23" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1078.6442" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1078.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1080.9427,-260.9241C1083.298,-249.8525 1088.0542,-236.2667 1097.6442,-228 1112.9165,-214.835 1158.5897,-205.6031 1198.7518,-199.7863"/>
<polygon fill="#000000" stroke="#000000" points="1199.4018,-203.2296 1208.8219,-198.3807 1198.4341,-196.2968 1199.4018,-203.2296"/>
<text text-anchor="middle" x="1180.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1274.6442" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1274.6442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1271.074,-260.7529C1270.108,-255.0864 1269.1819,-248.8045 1268.6442,-243 1267.9746,-235.7719 1267.6312,-227.9439 1267.4739,-220.6413"/>
<polygon fill="#000000" stroke="#000000" points="1270.9716,-220.4092 1267.3601,-210.4489 1263.9721,-220.4874 1270.9716,-220.4092"/>
<text text-anchor="middle" x="1327.6442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_arm -->
<g id="node25" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1404.6442" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1404.6442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1379.863,-88.5316C1360.9168,-76.815 1333.7041,-61.8178 1307.6442,-54 1249.5593,-36.5749 1075.2291,-25.0738 991.0855,-20.3852"/>
<polygon fill="#000000" stroke="#000000" points="991.2192,-16.8873 981.0425,-19.8341 990.8357,-23.8768 991.2192,-16.8873"/>
<text text-anchor="middle" x="1392.1442" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node26" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2059.6442" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2059.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2056.168,-347.6741C2050.5356,-323.4867 2036.9455,-281.5725 2007.6442,-261 1953.7396,-223.1535 1515.0734,-201.7847 1339.6997,-194.6847"/>
<polygon fill="#000000" stroke="#000000" points="1339.6699,-191.1808 1329.5377,-194.2774 1339.3895,-198.1752 1339.6699,-191.1808"/>
<text text-anchor="middle" x="2080.1442" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2015.2709,-356.6055C1953.8949,-344.1396 1839.4677,-322.7983 1740.6442,-315 1601.9498,-304.0555 625.7432,-320.6593 488.6442,-297 484.9305,-296.3591 481.1256,-295.4993 477.3425,-294.5017"/>
<polygon fill="#000000" stroke="#000000" points="478.0379,-291.058 467.4566,-291.5944 476.0629,-297.7736 478.0379,-291.058"/>
<text text-anchor="middle" x="1906.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2097.7971,-353.6953C2105.3142,-351.5686 2113.1842,-349.5476 2120.6442,-348 2182.2459,-335.2205 2682.6442,-341.9133 2682.6442,-279 2682.6442,-279 2682.6442,-279 2682.6442,-105 2682.6442,-18.0361 2381.339,-60.835 2294.6442,-54 2033.3166,-33.3969 1198.5035,-21.3197 991.453,-18.5935"/>
<polygon fill="#000000" stroke="#000000" points="991.2736,-15.091 981.2286,-18.4598 991.182,-22.0904 991.2736,-15.091"/>
<text text-anchor="middle" x="2725.1442" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M304.5508,-210.2377C306.5978,-221.0899 310.8426,-234.3799 319.6442,-243 329.4722,-252.6254 359.4151,-261.7908 386.4158,-268.4648"/>
<polygon fill="#000000" stroke="#000000" points="385.6472,-271.8796 396.1876,-270.8071 387.279,-265.0724 385.6472,-271.8796"/>
<text text-anchor="middle" x="360.1442" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M350.3002,-186.7276C464.3352,-173.8932 746.3886,-140.7788 785.6442,-123 808.0398,-112.857 807.6451,-101.2997 827.6442,-87 854.2315,-67.9895 886.3253,-49.3383 910.1696,-36.2298"/>
<polygon fill="#000000" stroke="#000000" points="912.0879,-39.1705 919.1968,-31.3147 908.7406,-33.0227 912.0879,-39.1705"/>
<text text-anchor="middle" x="868.1442" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- methylation_array_file -->
<g id="node28" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="435.6442" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="435.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M435.6442,-347.9735C435.6442,-336.1918 435.6442,-320.5607 435.6442,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="439.1443,-307.0033 435.6442,-297.0034 432.1443,-307.0034 439.1443,-307.0033"/>
<text text-anchor="middle" x="527.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node29" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="658.6442" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="658.6442" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M650.6387,-347.923C644.6219,-336.5552 635.2496,-322.6391 622.6442,-315 571.2539,-283.8567 547.1459,-310.7265 488.6442,-297 485.2295,-296.1988 481.7241,-295.2657 478.2215,-294.2538"/>
<polygon fill="#000000" stroke="#000000" points="479.0226,-290.8384 468.4353,-291.2377 476.9609,-297.5279 479.0226,-290.8384"/>
<text text-anchor="middle" x="710.1442" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
</g>
</svg>
</div>
