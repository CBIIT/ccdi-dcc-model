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
<svg width="3189pt" height="392pt"
 viewBox="0.00 0.00 3188.84 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3184.8391,-388 3184.8391,4 -4,4"/>
<!-- methylation_array_file -->
<g id="node1" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2565.7947" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2565.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node22" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2249.7947" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2249.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2525.4688,-349.0419C2512.1034,-343.2239 2497.2166,-336.5291 2483.7947,-330 2471.0994,-323.8244 2469.1395,-319.6069 2455.7947,-315 2405.7018,-297.707 2345.7618,-288.4305 2303.489,-283.6508"/>
<polygon fill="#000000" stroke="#000000" points="2303.7273,-280.1562 2293.4083,-282.5582 2302.973,-287.1154 2303.7273,-280.1562"/>
<text text-anchor="middle" x="2575.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1980.7947" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1980.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1993.4527,-347.7391C2002.4592,-336.2937 2015.6223,-322.3601 2030.7947,-315 2097.5636,-282.6105 2124.3361,-313.0287 2196.7947,-297 2200.3735,-296.2083 2204.0483,-295.2592 2207.7131,-294.2161"/>
<polygon fill="#000000" stroke="#000000" points="2208.7781,-297.5505 2217.3178,-291.2796 2206.7314,-290.8564 2208.7781,-297.5505"/>
<text text-anchor="middle" x="2097.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- exposure -->
<g id="node3" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="290.7947" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="290.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1379.7947" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1379.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M301.7415,-261.1545C310.0352,-249.418 322.5843,-234.9825 337.7947,-228 381.716,-207.8375 1077.7147,-196.2592 1307.1013,-192.9765"/>
<polygon fill="#000000" stroke="#000000" points="1307.3939,-196.4728 1317.3432,-192.831 1307.2945,-189.4735 1307.3939,-196.4728"/>
<text text-anchor="middle" x="381.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node20" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1825.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1825.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5446,-87.0111C52.5261,-75.9743 52.4069,-62.3944 60.7947,-54 92.0585,-22.7116 1502.8589,-18.5778 1779.1428,-18.068"/>
<polygon fill="#000000" stroke="#000000" points="1779.2388,-21.5679 1789.2325,-18.0501 1779.2263,-14.5679 1779.2388,-21.5679"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node5" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2431.7947" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2431.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2410.1642,-180.5985C2368.7165,-159.2031 2274.7552,-112.8673 2190.7947,-87 2078.6795,-52.4586 1941.5971,-32.1659 1871.6421,-23.3133"/>
<polygon fill="#000000" stroke="#000000" points="1871.7676,-19.802 1861.4119,-22.04 1870.903,-26.7484 1871.7676,-19.802"/>
<text text-anchor="middle" x="2308.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2455.7,-201.8398C2476.1124,-211.6272 2500.2064,-227.3972 2486.7947,-243 2474.9975,-256.7245 2369.8139,-268.4187 2303.597,-274.5053"/>
<polygon fill="#000000" stroke="#000000" points="2302.9689,-271.0477 2293.3244,-275.4335 2303.5988,-278.0193 2302.9689,-271.0477"/>
<text text-anchor="middle" x="2513.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node6" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="269.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="269.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M261.3167,-87.1131C257.4805,-76.117 255.4452,-62.5442 263.7947,-54 290.9521,-26.2095 1521.5343,-19.3244 1778.909,-18.1873"/>
<polygon fill="#000000" stroke="#000000" points="1779.0603,-21.6868 1789.0449,-18.1433 1779.0298,-14.6869 1779.0603,-21.6868"/>
<text text-anchor="middle" x="320.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cell_line -->
<g id="node7" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2231.7947" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2231.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2205.6557,-176.685C2157.6861,-149.084 2051.7911,-90.4794 1956.7947,-54 1928.2205,-43.0273 1894.9526,-33.9282 1869.0926,-27.6228"/>
<polygon fill="#000000" stroke="#000000" points="1869.754,-24.1824 1859.2143,-25.2617 1868.1266,-30.9906 1869.754,-24.1824"/>
<text text-anchor="middle" x="2146.2947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2230.318,-210.1676C2229.974,-220.0092 2230.287,-232.3089 2232.7947,-243 2233.4981,-245.9987 2234.4717,-249.0442 2235.6001,-252.0295"/>
<polygon fill="#000000" stroke="#000000" points="2232.4002,-253.4478 2239.5911,-261.2287 2238.8219,-250.6618 2232.4002,-253.4478"/>
<text text-anchor="middle" x="2273.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="446.7947" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="446.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M434.2063,-260.8405C428.3739,-250.0178 424.389,-236.7313 432.7947,-228 447.9235,-212.2852 1088.2376,-197.8949 1307.2369,-193.4246"/>
<polygon fill="#000000" stroke="#000000" points="1307.416,-196.9218 1317.3428,-193.2193 1307.2738,-189.9233 1307.416,-196.9218"/>
<text text-anchor="middle" x="500.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1650.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1650.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1663.2728,-87.0392C1671.8085,-76.0137 1684.0412,-62.4358 1697.7947,-54 1722.9839,-38.5502 1754.9863,-29.55 1780.6901,-24.4124"/>
<polygon fill="#000000" stroke="#000000" points="1781.3772,-27.8446 1790.5626,-22.5646 1780.0893,-20.9641 1781.3772,-27.8446"/>
<text text-anchor="middle" x="1759.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- consent_group -->
<g id="node10" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1825.7947" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1825.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge40" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1825.7947,-86.9735C1825.7947,-75.1918 1825.7947,-59.5607 1825.7947,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1829.2948,-46.0033 1825.7947,-36.0034 1822.2948,-46.0034 1829.2948,-46.0033"/>
<text text-anchor="middle" x="1889.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="525.7947" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="525.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M535.5518,-348.0034C549.442,-324.1894 577.2241,-282.6967 612.7947,-261 671.0703,-225.4541 695.1772,-237.3506 762.7947,-228 866.0997,-213.7143 1168.2621,-200.3671 1307.7278,-194.7697"/>
<polygon fill="#000000" stroke="#000000" points="1308.0345,-198.2604 1317.8869,-194.3642 1307.7552,-191.2659 1308.0345,-198.2604"/>
<text text-anchor="middle" x="655.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M473.7277,-365.0228C395.8589,-362.7407 253.5306,-355.1542 209.7947,-330 185.2915,-315.9073 171.7947,-307.2668 171.7947,-279 171.7947,-279 171.7947,-279 171.7947,-105 171.7947,-80.4346 216.8497,-63.6683 254.7947,-54 330.4165,-34.7316 1526.1571,-21.1452 1779.045,-18.4791"/>
<polygon fill="#000000" stroke="#000000" points="1779.3897,-21.9757 1789.3525,-18.371 1779.3163,-14.9761 1779.3897,-21.9757"/>
<text text-anchor="middle" x="214.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M563.5819,-353.5914C571.2006,-351.447 579.2019,-349.446 586.7947,-348 748.1074,-317.2796 790.8045,-323.5291 954.7947,-315 1092.6229,-307.8315 2060.7919,-320.4783 2196.7947,-297 2200.5084,-296.3589 2204.3132,-295.499 2208.0963,-294.5012"/>
<polygon fill="#000000" stroke="#000000" points="2209.376,-297.7731 2217.9821,-291.5938 2207.4009,-291.0575 2209.376,-297.7731"/>
<text text-anchor="middle" x="997.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- laboratory_test -->
<g id="node12" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1124.7947" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1124.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1053.5026,-357.1087C972.8509,-344.2288 858.4877,-315.692 905.7947,-261 931.7891,-230.9476 1183.175,-207.3085 1308.9132,-197.2576"/>
<polygon fill="#000000" stroke="#000000" points="1309.5194,-200.7206 1319.212,-196.4423 1308.9669,-193.7425 1309.5194,-200.7206"/>
<text text-anchor="middle" x="971.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1193.7477,-356.1513C1280.3952,-344.2081 1433.7635,-324.4997 1565.7947,-315 1705.7123,-304.9329 2058.7309,-321.8324 2196.7947,-297 2200.5038,-296.3329 2204.3054,-295.4548 2208.0864,-294.445"/>
<polygon fill="#000000" stroke="#000000" points="2209.3742,-297.7139 2217.9689,-291.5187 2207.3867,-291.002 2209.3742,-297.7139"/>
<text text-anchor="middle" x="1631.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge25" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1432.1488,-182.0277C1501.7522,-168.7362 1628.5775,-144.4009 1736.7947,-123 1743.0869,-121.7557 1749.6272,-120.4522 1756.1778,-119.1398"/>
<polygon fill="#000000" stroke="#000000" points="1757.3309,-122.4781 1766.4458,-117.0773 1755.9523,-115.6152 1757.3309,-122.4781"/>
<text text-anchor="middle" x="1689.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1227.7947" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1227.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1247.4946,-262.5563C1260.8661,-251.878 1279.2427,-238.1167 1296.7947,-228 1307.9619,-221.5634 1320.4984,-215.5541 1332.3789,-210.3596"/>
<polygon fill="#000000" stroke="#000000" points="1333.9,-213.516 1341.7275,-206.3759 1331.1558,-207.0764 1333.9,-213.516"/>
<text text-anchor="middle" x="1336.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node15" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1585.7947" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1585.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1573.8083,-260.7866C1565.5445,-249.6602 1553.5876,-236.065 1539.7947,-228 1523.6187,-218.5416 1481.7791,-209.2925 1444.9426,-202.5379"/>
<polygon fill="#000000" stroke="#000000" points="1445.1722,-199.0232 1434.711,-200.7008 1443.935,-205.913 1445.1722,-199.0232"/>
<text text-anchor="middle" x="1616.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- treatment_response -->
<g id="node16" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2082.7947" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2082.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2012.4786,-265.6353C1984.3344,-259.6506 1951.7755,-251.9216 1922.7947,-243 1905.4413,-237.6579 1902.4999,-232.0255 1884.7947,-228 1804.5323,-209.7512 1571.4106,-198.9353 1452.0556,-194.4441"/>
<polygon fill="#000000" stroke="#000000" points="1452.0391,-190.9412 1441.9161,-194.0675 1451.7793,-197.9363 1452.0391,-190.9412"/>
<text text-anchor="middle" x="2005.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1824.7947" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1824.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1844.3366,-349.0935C1849.371,-343.5726 1854.1201,-337.0347 1856.7947,-330 1866.2067,-305.2446 1839.5333,-265.0811 1834.7947,-261 1778.7472,-212.7297 1565.7457,-198.189 1452.1569,-193.8379"/>
<polygon fill="#000000" stroke="#000000" points="1452.2724,-190.3399 1442.1509,-193.4711 1452.016,-197.3352 1452.2724,-190.3399"/>
<text text-anchor="middle" x="1899.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1850.8374,-350.0484C1873.2907,-336.611 1904.1798,-318.9595 1917.7947,-315 2037.1092,-280.3007 2074.9139,-321.1884 2196.7947,-297 2200.4406,-296.2764 2204.1801,-295.3673 2207.904,-294.3441"/>
<polygon fill="#000000" stroke="#000000" points="2209.0782,-297.646 2217.6496,-291.4186 2207.0655,-290.9416 2209.0782,-297.646"/>
<text text-anchor="middle" x="1962.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- generic_file -->
<g id="node18" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2809.7947" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2809.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2809.6197,-347.7836C2808.4901,-336.6561 2805.09,-323.0606 2795.7947,-315 2771.722,-294.1249 2257.7862,-250.402 2226.7947,-243 2207.5155,-238.3954 2204.2448,-231.8185 2184.7947,-228 2045.8105,-200.7142 1623.0554,-194.0701 1452.3916,-192.4847"/>
<polygon fill="#000000" stroke="#000000" points="1452.2836,-188.9837 1442.2525,-192.3937 1452.2207,-195.9834 1452.2836,-188.9837"/>
<text text-anchor="middle" x="2756.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge38" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2818.1193,-348.1C2825.3918,-330.8051 2834.7947,-303.6732 2834.7947,-279 2834.7947,-279 2834.7947,-279 2834.7947,-105 2834.7947,-56.041 2070.7797,-26.4111 1872.3994,-19.5428"/>
<polygon fill="#000000" stroke="#000000" points="1872.4159,-16.0414 1862.3016,-19.196 1872.1756,-23.0373 1872.4159,-16.0414"/>
<text text-anchor="middle" x="2887.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2759.5766,-354.3804C2737.6206,-348.4317 2711.89,-340.2588 2689.7947,-330 2678.7256,-324.8606 2678.3322,-318.9778 2666.7947,-315 2649.8868,-309.1706 2412.304,-291.012 2303.5058,-282.9382"/>
<polygon fill="#000000" stroke="#000000" points="2303.6219,-279.4373 2293.3907,-282.1891 2303.1049,-286.4182 2303.6219,-279.4373"/>
<text text-anchor="middle" x="2742.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment -->
<g id="node19" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1103.7947" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1103.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1123.4666,-261.9446C1137.6421,-250.5706 1157.7345,-236.2435 1177.7947,-228 1219.3194,-210.9359 1268.9157,-201.9482 1308.5723,-197.2205"/>
<polygon fill="#000000" stroke="#000000" points="1309.1455,-200.6781 1318.6906,-196.0802 1308.3615,-193.7222 1309.1455,-200.6781"/>
<text text-anchor="middle" x="1224.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cytogenomic_file -->
<g id="node21" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2171.7947" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2171.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2167.6603,-347.6274C2166.3655,-337.2532 2166.6155,-324.5032 2172.7947,-315 2177.1248,-308.3406 2191.4302,-300.9157 2206.5554,-294.5468"/>
<polygon fill="#000000" stroke="#000000" points="2208.0351,-297.7239 2215.997,-290.734 2205.4139,-291.2332 2208.0351,-297.7239"/>
<text text-anchor="middle" x="2244.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2290.8545,-272.0548C2327.5237,-265.2746 2377.9665,-254.3471 2394.7947,-243 2404.0458,-236.7621 2411.7987,-227.3987 2417.7787,-218.3906"/>
<polygon fill="#000000" stroke="#000000" points="2420.908,-219.9832 2423.1576,-209.63 2414.9426,-216.3206 2420.908,-219.9832"/>
<text text-anchor="middle" x="2446.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2284.0074,-267.3334C2304.5108,-258.3448 2324.6711,-244.6534 2313.7947,-228 2306.8851,-217.4204 2296.098,-209.9298 2284.5917,-204.6333"/>
<polygon fill="#000000" stroke="#000000" points="2285.8518,-201.3674 2275.2702,-200.8388 2283.2126,-207.8508 2285.8518,-201.3674"/>
<text text-anchor="middle" x="2354.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2216.62,-267.0607C2210.091,-264.902 2203.2604,-262.7758 2196.7947,-261 2159.558,-250.7729 2147.462,-257.7987 2111.7947,-243 2100.5224,-238.323 2100.4008,-231.7731 2088.7947,-228 2029.4961,-208.7224 1620.9094,-197.4268 1452.3078,-193.5399"/>
<polygon fill="#000000" stroke="#000000" points="1452.3578,-190.0402 1442.2805,-193.311 1452.198,-197.0384 1452.3578,-190.0402"/>
<text text-anchor="middle" x="2148.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node23" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="704.7947" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="704.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M701.3097,-347.9832C697.919,-324.5346 696.1442,-283.8632 718.7947,-261 759.6171,-219.7943 1144.1399,-200.7494 1307.2309,-194.4747"/>
<polygon fill="#000000" stroke="#000000" points="1307.787,-197.9562 1317.6472,-194.0798 1307.5217,-190.9613 1307.787,-197.9562"/>
<text text-anchor="middle" x="804.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M625.1515,-353.7415C612.3292,-351.7995 599.198,-349.8294 586.7947,-348 424.8052,-324.1071 136.0418,-395.9383 228.7947,-261 319.7278,-128.7091 1525.4688,-38.6754 1779.1549,-21.1324"/>
<polygon fill="#000000" stroke="#000000" points="1779.7548,-24.5995 1789.4911,-20.4215 1779.2744,-17.616 1779.7548,-24.5995"/>
<text text-anchor="middle" x="539.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M792.9173,-355.3771C897.6122,-343.2461 1077.6439,-323.9281 1232.7947,-315 1339.7475,-308.8455 2091.2647,-315.4448 2196.7947,-297 2200.507,-296.3511 2204.3109,-295.4858 2208.0934,-294.4845"/>
<polygon fill="#000000" stroke="#000000" points="2209.3755,-297.7555 2217.9783,-291.5714 2207.3967,-291.041 2209.3755,-297.7555"/>
<text text-anchor="middle" x="1318.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node24" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2355.7947" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2355.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2344.3773,-347.9668C2337.0998,-337.4559 2326.9593,-324.452 2315.7947,-315 2307.8006,-308.2321 2298.3327,-302.1698 2289.1007,-297.0356"/>
<polygon fill="#000000" stroke="#000000" points="2290.4855,-293.8085 2280.0105,-292.2192 2287.2081,-299.9939 2290.4855,-293.8085"/>
<text text-anchor="middle" x="2390.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2949.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2949.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2923.6194,-87.7947C2903.9321,-75.8712 2875.8116,-60.9385 2848.7947,-54 2753.6635,-29.5683 2059.9524,-20.4866 1872.4192,-18.4632"/>
<polygon fill="#000000" stroke="#000000" points="1872.3699,-14.9626 1862.3333,-18.356 1872.2954,-21.9622 1872.3699,-14.9626"/>
<text text-anchor="middle" x="2955.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- genetic_analysis -->
<g id="node26" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1596.7947" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1596.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1560.9315,-349.4029C1545.071,-339.8271 1532.1559,-327.2806 1542.7947,-315 1579.5465,-272.5768 1626.6333,-335.1596 1667.7947,-297 1690.6214,-275.838 1700.452,-251.2844 1679.7947,-228 1664.8663,-211.1731 1535.2613,-200.7334 1451.3548,-195.676"/>
<polygon fill="#000000" stroke="#000000" points="1451.5486,-192.1814 1441.3596,-195.0858 1451.1359,-199.1692 1451.5486,-192.1814"/>
<text text-anchor="middle" x="1760.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1639.9445,-350.307C1679.4329,-336.0645 1733.277,-316.9882 1743.7947,-315 1941.7805,-277.5739 1998.6874,-333.778 2196.7947,-297 2200.4492,-296.3215 2204.1949,-295.444 2207.9228,-294.442"/>
<polygon fill="#000000" stroke="#000000" points="2209.0826,-297.7488 2217.6749,-291.5502 2207.0925,-291.0376 2209.0826,-297.7488"/>
<text text-anchor="middle" x="1813.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- publication -->
<g id="node27" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3117.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3117.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3095.4067,-88.0059C3078.2013,-76.0212 3053.303,-60.9186 3028.7947,-54 2972.2842,-38.0474 2087.2412,-22.3496 1872.4757,-18.7622"/>
<polygon fill="#000000" stroke="#000000" points="1872.5267,-15.2626 1862.4698,-18.5957 1872.4102,-22.2617 1872.5267,-15.2626"/>
<text text-anchor="middle" x="3112.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- family_relationship -->
<g id="node28" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1393.7947" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1393.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1385.9951,-261.0075C1383.8996,-255.3513 1381.9076,-249.0113 1380.7947,-243 1379.4359,-235.6609 1378.8634,-227.6264 1378.7068,-220.1499"/>
<polygon fill="#000000" stroke="#000000" points="1382.2068,-220.0884 1378.7236,-210.0825 1375.2068,-220.0766 1382.2068,-220.0884"/>
<text text-anchor="middle" x="1460.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
