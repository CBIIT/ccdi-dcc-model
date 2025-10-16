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
<svg width="3386pt" height="392pt"
 viewBox="0.00 0.00 3385.54 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3381.5369,-388 3381.5369,4 -4,4"/>
<!-- study_funding -->
<g id="node1" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2697.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2697.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.0741,-86.9921C70.0479,-75.9477 69.9274,-62.3665 78.3431,-54 102.0878,-30.3941 2300.6848,-19.7454 2650.6321,-18.1994"/>
<polygon fill="#000000" stroke="#000000" points="2650.6914,-21.6992 2660.6759,-18.1553 2650.6606,-14.6993 2650.6914,-21.6992"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- genetic_analysis -->
<g id="node2" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="698.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="698.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1427.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1427.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M617.1345,-358.9812C536.1809,-350.1025 420.019,-331.6114 392.3431,-297 382.3509,-284.5038 381.7379,-272.9804 392.3431,-261 424.2495,-224.9566 1125.0103,-200.9839 1354.9665,-194.0653"/>
<polygon fill="#000000" stroke="#000000" points="1355.3406,-197.5557 1365.2315,-193.7584 1355.1314,-190.5589 1355.3406,-197.5557"/>
<text text-anchor="middle" x="462.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2053.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2053.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M768.1536,-355.0263C849.2217,-342.8061 987.0864,-323.6387 1106.3431,-315 1303.2012,-300.7401 1799.4337,-328.0928 1994.3431,-297 1999.4987,-296.1776 2004.8302,-295.0156 2010.0838,-293.6733"/>
<polygon fill="#000000" stroke="#000000" points="2011.3257,-296.9609 2020.0237,-290.9115 2009.4517,-290.2164 2011.3257,-296.9609"/>
<text text-anchor="middle" x="1176.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- cell_line -->
<g id="node3" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2310.3431" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2310.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2271.2918,-354.8084C2251.6477,-348.569 2227.741,-340.0318 2207.3431,-330 2196.3919,-324.6141 2195.4713,-320.0102 2184.3431,-315 2158.6357,-303.4257 2128.375,-294.8115 2103.4178,-288.9164"/>
<polygon fill="#000000" stroke="#000000" points="2103.9583,-285.4498 2093.4299,-286.634 2102.3989,-292.2739 2103.9583,-285.4498"/>
<text text-anchor="middle" x="2247.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2338.227,-351.1354C2363.1196,-338.0372 2397.8189,-320.2466 2412.3431,-315 2445.3975,-303.0597 2459.944,-316.2574 2489.3431,-297 2588.9881,-231.7292 2658.5229,-101.5071 2685.2224,-45.0957"/>
<polygon fill="#000000" stroke="#000000" points="2688.5196,-46.306 2689.5656,-35.7629 2682.1731,-43.3525 2688.5196,-46.306"/>
<text text-anchor="middle" x="2648.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="262.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="262.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M262.8497,-347.7802C264.545,-324.1071 271.2016,-283.1875 296.3431,-261 355.0325,-209.2064 391.5673,-236.8281 469.3431,-228 640.6453,-208.5559 1162.0763,-197.0062 1354.7685,-193.3075"/>
<polygon fill="#000000" stroke="#000000" points="1354.8607,-196.8064 1364.7922,-193.1165 1354.7273,-189.8077 1354.8607,-196.8064"/>
<text text-anchor="middle" x="338.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M312.3965,-360.6557C416.3714,-349.8088 663.3814,-325.3626 871.3431,-315 995.9823,-308.7893 1871.0661,-316.3977 1994.3431,-297 1999.5004,-296.1885 2004.833,-295.0333 2010.0872,-293.6948"/>
<polygon fill="#000000" stroke="#000000" points="2011.3274,-296.983 2020.0278,-290.9369 2009.456,-290.2378 2011.3274,-296.983"/>
<text text-anchor="middle" x="913.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M246.7696,-348.7467C233.4247,-332.1293 216.3431,-305.6534 216.3431,-279 216.3431,-279 216.3431,-279 216.3431,-105 216.3431,-41.647 2310.3528,-21.2698 2650.8189,-18.3754"/>
<polygon fill="#000000" stroke="#000000" points="2650.8617,-21.8752 2660.8318,-18.291 2650.8027,-14.8755 2650.8617,-21.8752"/>
<text text-anchor="middle" x="258.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1749.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1749.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1716.7506,-265.6229C1688.4606,-254.397 1646.2084,-238.5487 1608.3431,-228 1570.28,-217.3961 1526.8843,-208.6542 1492.1275,-202.4411"/>
<polygon fill="#000000" stroke="#000000" points="1492.5562,-198.9629 1482.1007,-200.6758 1491.3423,-205.8568 1492.5562,-198.9629"/>
<text text-anchor="middle" x="1695.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1388.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1388.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1405.5399,-348.0493C1418.0928,-336.2646 1436.2004,-321.8147 1455.3431,-315 1511.795,-294.9035 1935.2322,-306.8275 1994.3431,-297 1999.4932,-296.1438 2004.8213,-294.9609 2010.0729,-293.6069"/>
<polygon fill="#000000" stroke="#000000" points="2011.3201,-296.8926 2020.0109,-290.8328 2009.4381,-290.1503 2011.3201,-296.8926"/>
<text text-anchor="middle" x="1546.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- consent_group -->
<g id="node19" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1781.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1781.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge40" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1475.0852,-180.2668C1537.6826,-164.8827 1647.7058,-137.8431 1717.4364,-120.7059"/>
<polygon fill="#000000" stroke="#000000" points="1718.546,-124.0374 1727.4217,-118.2519 1716.8754,-117.2397 1718.546,-124.0374"/>
<text text-anchor="middle" x="1676.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node8" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1611.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1611.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1624.1241,-347.9668C1633.5112,-336.3062 1647.3743,-322.0359 1663.3431,-315 1730.7542,-285.2988 1921.8068,-309.8416 1994.3431,-297 1999.4196,-296.1013 2004.6733,-294.904 2009.8579,-293.5523"/>
<polygon fill="#000000" stroke="#000000" points="2010.9937,-296.8689 2019.6784,-290.8004 2009.1049,-290.1286 2010.9937,-296.8689"/>
<text text-anchor="middle" x="1734.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- medical_history -->
<g id="node9" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1900.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1900.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1858.2302,-263.2103C1826.0922,-251.7634 1780.4861,-236.8047 1739.3431,-228 1657.9005,-210.571 1562.5707,-201.1242 1498.9202,-196.3391"/>
<polygon fill="#000000" stroke="#000000" points="1498.8212,-192.8226 1488.5923,-195.5827 1498.3099,-199.8039 1498.8212,-192.8226"/>
<text text-anchor="middle" x="1861.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- laboratory_test -->
<g id="node10" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1172.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1172.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1192.1711,-348.3155C1206.2616,-336.8106 1226.1907,-322.583 1246.3431,-315 1278.5909,-302.8657 1374.388,-319.6604 1400.3431,-297 1421.9574,-278.1294 1427.4041,-244.5008 1428.2738,-220.3815"/>
<polygon fill="#000000" stroke="#000000" points="1431.7735,-220.4196 1428.3968,-210.3773 1424.774,-220.3335 1431.7735,-220.4196"/>
<text text-anchor="middle" x="1487.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1203.4032,-349.2288C1227.4566,-337.19 1262.0174,-321.9181 1294.3431,-315 1446.5045,-282.4356 1840.7464,-321.9311 1994.3431,-297 1999.4964,-296.1635 2004.8265,-294.9929 2010.0793,-293.6457"/>
<polygon fill="#000000" stroke="#000000" points="2011.3235,-296.9325 2020.0185,-290.8788 2009.4461,-290.189 2011.3235,-296.9325"/>
<text text-anchor="middle" x="1359.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2823.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2823.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2799.3469,-88.4312C2778.7977,-74.2424 2749.1209,-53.7513 2727.0706,-38.5261"/>
<polygon fill="#000000" stroke="#000000" points="2728.9495,-35.5702 2718.7318,-32.7684 2724.9721,-41.3305 2728.9495,-35.5702"/>
<text text-anchor="middle" x="2815.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2988.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2988.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2954.0967,-88.3358C2930.4498,-77.3572 2898.0351,-63.3374 2868.3431,-54 2826.3296,-40.7878 2776.9771,-30.9836 2742.1193,-24.9709"/>
<polygon fill="#000000" stroke="#000000" points="2742.6847,-21.5169 2732.2413,-23.3015 2741.5182,-28.419 2742.6847,-21.5169"/>
<text text-anchor="middle" x="2977.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node13" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1958.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1958.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1918.6879,-353.4937C1910.6953,-351.3574 1902.3032,-349.3843 1894.3431,-348 1838.1571,-338.229 1691.1359,-351.5702 1638.3431,-330 1594.5652,-312.1131 1596.4604,-287.5761 1557.3431,-261 1529.5785,-242.1368 1496.0765,-224.4635 1470.0365,-211.7261"/>
<polygon fill="#000000" stroke="#000000" points="1471.3315,-208.4646 1460.805,-207.2636 1468.285,-214.767 1471.3315,-208.4646"/>
<text text-anchor="middle" x="1638.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1956.1636,-347.7939C1955.8755,-337.2216 1957.3129,-324.2141 1964.3431,-315 1970.1546,-307.3833 1988.6944,-299.3476 2007.3589,-292.8053"/>
<polygon fill="#000000" stroke="#000000" points="2008.7078,-296.044 2017.0638,-289.5303 2006.4696,-289.4115 2008.7078,-296.044"/>
<text text-anchor="middle" x="2008.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3156.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3156.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3129.3242,-88.5902C3108.7163,-76.9037 3079.2204,-61.9182 3051.3431,-54 2994.712,-37.9145 2826.1795,-25.8257 2743.7637,-20.6988"/>
<polygon fill="#000000" stroke="#000000" points="2743.8728,-17.199 2733.677,-20.0794 2743.4436,-24.1858 2743.8728,-17.199"/>
<text text-anchor="middle" x="3140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="594.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="594.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M621.1755,-263.4206C643.4488,-251.3551 676.3784,-235.4778 707.3431,-228 769.0412,-213.1002 1185.0528,-199.2091 1355.1168,-194.0838"/>
<polygon fill="#000000" stroke="#000000" points="1355.3356,-197.5789 1365.2262,-193.7808 1355.1258,-190.5821 1355.3356,-197.5789"/>
<text text-anchor="middle" x="750.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2097.4012,-280.735C2157.0157,-283.9102 2259.2732,-292.5422 2288.3431,-315 2295.828,-320.7824 2300.8069,-329.6207 2304.1013,-338.3243"/>
<polygon fill="#000000" stroke="#000000" points="2300.787,-339.4515 2307.1489,-347.9236 2307.4588,-337.3333 2300.787,-339.4515"/>
<text text-anchor="middle" x="2337.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2026.5823,-264.5785C2002.8264,-252.5283 1966.7937,-236.0601 1933.3431,-228 1853.1648,-208.6806 1619.469,-198.3606 1499.7997,-194.2127"/>
<polygon fill="#000000" stroke="#000000" points="1499.747,-190.709 1489.6334,-193.8657 1499.5081,-197.7049 1499.747,-190.709"/>
<text text-anchor="middle" x="2014.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2492.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2492.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2093.4652,-271.0487C2178.038,-254.2883 2373.5321,-215.5457 2455.3176,-199.3376"/>
<polygon fill="#000000" stroke="#000000" points="2456.4968,-202.6721 2465.6256,-197.2948 2455.136,-195.8056 2456.4968,-202.6721"/>
<text text-anchor="middle" x="2335.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1802.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1802.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1804.3053,-347.824C1806.5256,-336.5654 1811.2578,-322.8099 1821.3431,-315 1851.9034,-291.3347 1956.4608,-304.675 1994.3431,-297 1999.332,-295.9893 2004.5022,-294.7333 2009.6144,-293.3581"/>
<polygon fill="#000000" stroke="#000000" points="2010.6505,-296.7023 2019.3111,-290.5996 2008.735,-289.9695 2010.6505,-296.7023"/>
<text text-anchor="middle" x="1887.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge2" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1854.7549,-98.0275C2036.3443,-80.7805 2502.5902,-36.4973 2651.1422,-22.3881"/>
<polygon fill="#000000" stroke="#000000" points="2651.6565,-25.8551 2661.2807,-21.4251 2650.9945,-18.8864 2651.6565,-25.8551"/>
<text text-anchor="middle" x="2357.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- family_relationship -->
<g id="node20" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="765.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="765.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M779.0926,-260.9791C789.1245,-249.324 803.8157,-235.0552 820.3431,-228 868.3618,-207.5019 1204.6511,-197.1862 1355.0009,-193.5565"/>
<polygon fill="#000000" stroke="#000000" points="1355.1507,-197.054 1365.0645,-193.3168 1354.9839,-190.056 1355.1507,-197.054"/>
<text text-anchor="middle" x="899.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2470.83,-203.8366C2448.0706,-215.7826 2410.7602,-233.7481 2376.3431,-243 2326.933,-256.2822 2185.426,-268.8128 2107.1075,-274.9907"/>
<polygon fill="#000000" stroke="#000000" points="2106.6517,-271.5156 2096.9547,-275.7839 2107.1969,-278.4943 2106.6517,-271.5156"/>
<text text-anchor="middle" x="2443.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2492.9925,-173.6919C2494.6025,-151.3816 2500.0619,-113.4019 2518.3431,-87 2533.0809,-65.7157 2542.8681,-64.9153 2566.3431,-54 2593.9093,-41.1824 2626.9248,-32.1459 2652.9147,-26.3322"/>
<polygon fill="#000000" stroke="#000000" points="2653.8269,-29.7161 2662.864,-24.1861 2652.3508,-22.8734 2653.8269,-29.7161"/>
<text text-anchor="middle" x="2542.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment -->
<g id="node22" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="941.3431" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="941.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M958.6872,-261.6144C971.5148,-249.9307 990.0422,-235.3688 1009.3431,-228 1070.526,-204.6412 1252.0039,-196.3355 1354.5883,-193.4609"/>
<polygon fill="#000000" stroke="#000000" points="1354.9684,-196.952 1364.8704,-193.1835 1354.7796,-189.9546 1354.9684,-196.952"/>
<text text-anchor="middle" x="1056.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pathology_file -->
<g id="node23" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2107.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2107.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2079.5047,-348.8731C2072.9493,-343.5889 2066.6305,-337.2282 2062.3431,-330 2058.2609,-323.1176 2055.9293,-314.8566 2054.6245,-307.0072"/>
<polygon fill="#000000" stroke="#000000" points="2058.0998,-306.5913 2053.4398,-297.0763 2051.1491,-307.4205 2058.0998,-306.5913"/>
<text text-anchor="middle" x="2123.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1090.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1090.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1096.9255,-260.8965C1102.0484,-249.5175 1110.3288,-235.5989 1122.3431,-228 1141.7208,-215.744 1272.7529,-203.7053 1356.6488,-197.1249"/>
<polygon fill="#000000" stroke="#000000" points="1356.9365,-200.6132 1366.6357,-196.3499 1356.3948,-193.6342 1356.9365,-200.6132"/>
<text text-anchor="middle" x="1181.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment_response -->
<g id="node25" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1286.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1286.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1259.7781,-261.5404C1247.8966,-251.5844 1238.3685,-238.9473 1247.3431,-228 1261.214,-211.0803 1311.9858,-201.9542 1356.085,-197.1288"/>
<polygon fill="#000000" stroke="#000000" points="1356.6614,-200.588 1366.2483,-196.0778 1355.9413,-193.6251 1356.6614,-200.588"/>
<text text-anchor="middle" x="1330.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_admin -->
<g id="node26" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3307.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3307.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3278.4464,-88.3755C3256.4257,-76.5794 3224.948,-61.5509 3195.3431,-54 3110.702,-32.4117 2850.6798,-22.5026 2743.8768,-19.2635"/>
<polygon fill="#000000" stroke="#000000" points="2743.8287,-15.7606 2733.7291,-18.9619 2743.6207,-22.7575 2743.8287,-15.7606"/>
<text text-anchor="middle" x="3292.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- generic_file -->
<g id="node27" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2626.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2626.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2677.8672,-354.7156C2701.7381,-348.3399 2726.3661,-339.7088 2733.3431,-330 2737.2336,-324.5863 2737.9129,-319.8541 2733.3431,-315 2710.6055,-290.8475 2468.2761,-300.9702 2435.3431,-297 2264.9265,-276.4555 2225.7911,-248.2831 2055.3431,-228 1855.3403,-204.1999 1617.5624,-196.0076 1500.2484,-193.2873"/>
<polygon fill="#000000" stroke="#000000" points="1500.0363,-189.7817 1489.96,-193.0556 1499.8786,-196.7799 1500.0363,-189.7817"/>
<text text-anchor="middle" x="2488.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2569.6209,-356.8205C2530.7943,-350.2083 2478.2339,-340.6102 2432.3431,-330 2408.0746,-324.389 2402.8006,-319.7197 2378.3431,-315 2283.8992,-296.7745 2172.1041,-286.9044 2107.2975,-282.3133"/>
<polygon fill="#000000" stroke="#000000" points="2107.5278,-278.8209 2097.3098,-281.6213 2107.0439,-285.8042 2107.5278,-278.8209"/>
<text text-anchor="middle" x="2485.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge21" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2675.5073,-353.972C2707.0264,-345.8397 2743.0136,-335.5979 2748.3431,-330 2758.7492,-319.07 2754.5527,-311.9849 2756.3431,-297 2758.2413,-281.113 2762.0018,-275.9659 2756.3431,-261 2745.6522,-232.7249 2723.0558,-237.8674 2711.3431,-210 2688.4385,-155.5042 2690.5008,-84.6605 2693.964,-46.0718"/>
<polygon fill="#000000" stroke="#000000" points="2697.4504,-46.3811 2694.9584,-36.0836 2690.4848,-45.6876 2697.4504,-46.3811"/>
<text text-anchor="middle" x="2764.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node28" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2818.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2818.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2798.9909,-348.2415C2785.693,-337.0081 2767.1101,-323.1221 2748.3431,-315 2708.9048,-297.9315 2694.704,-308.6617 2653.3431,-297 2570.0823,-273.5246 2556.1527,-245.0526 2471.3431,-228 2376.9958,-209.0296 1721.4048,-196.7687 1500.1106,-193.1325"/>
<polygon fill="#000000" stroke="#000000" points="1499.9609,-189.6297 1489.9051,-192.9659 1499.8466,-196.6287 1499.9609,-189.6297"/>
<text text-anchor="middle" x="2739.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2741.5647,-353.2203C2702.5201,-346.576 2654.3489,-338.1561 2611.3431,-330 2578.8009,-323.8283 2571.1488,-319.5687 2538.3431,-315 2456.4191,-303.5909 2215.8021,-288.5583 2107.3915,-282.1317"/>
<polygon fill="#000000" stroke="#000000" points="2107.5116,-278.6328 2097.3226,-281.5371 2107.0988,-285.6206 2107.5116,-278.6328"/>
<text text-anchor="middle" x="2697.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2823.122,-347.9272C2831.4783,-312.4974 2845.3397,-232.2931 2817.3431,-174 2801.7469,-141.5264 2777.3798,-150.6963 2754.3431,-123 2734.5857,-99.2462 2718.5223,-67.586 2708.5433,-45.2625"/>
<polygon fill="#000000" stroke="#000000" points="2711.721,-43.7933 2704.5206,-36.0213 2705.3028,-46.5873 2711.721,-43.7933"/>
<text text-anchor="middle" x="2914.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
</g>
</svg>
</div>
