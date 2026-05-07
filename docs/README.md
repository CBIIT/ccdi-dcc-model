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
<svg width="3467pt" height="479pt"
 viewBox="0.00 0.00 3466.99 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3462.9885,-475 3462.9885,4 -4,4"/>
<!-- study_status -->
<g id="node1" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="70.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="70.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2434.1938" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2434.1938" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M80.1373,-87.092C87.7619,-75.3268 99.4683,-60.8828 114.1938,-54 167.5857,-29.0444 2063.2273,-19.6267 2387.2992,-18.1975"/>
<polygon fill="#000000" stroke="#000000" points="2387.7438,-21.6957 2397.7284,-18.1519 2387.7132,-14.6958 2387.7438,-21.6957"/>
<text text-anchor="middle" x="170.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="927.1938" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="927.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node27" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1755.1938" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1755.1938" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M909.9879,-261.2094C901.7138,-250.5255 895.3216,-237.2555 904.1938,-228 930.9264,-200.1126 1481.1719,-193.7655 1682.3513,-192.3748"/>
<polygon fill="#000000" stroke="#000000" points="1682.5476,-195.8737 1692.5239,-192.3067 1682.5006,-188.8739 1682.5476,-195.8737"/>
<text text-anchor="middle" x="987.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment_surgery -->
<g id="node3" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1187.1938" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1187.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1181.0859,-260.6938C1178.709,-249.8159 1178.1931,-236.5229 1186.1938,-228 1202.9463,-210.1541 1533.6,-198.3915 1683.003,-193.9673"/>
<polygon fill="#000000" stroke="#000000" points="1683.1153,-197.4656 1693.0084,-193.674 1682.9101,-190.4686 1683.1153,-197.4656"/>
<text text-anchor="middle" x="1264.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- medical_history -->
<g id="node4" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2116.1938" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2116.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2107.2177,-260.8061C2100.5713,-249.3888 2090.3892,-235.4616 2077.1938,-228 2035.9308,-204.6669 1909.4308,-196.4532 1827.8132,-193.5643"/>
<polygon fill="#000000" stroke="#000000" points="1827.709,-190.059 1817.5974,-193.2221 1827.4746,-197.0551 1827.709,-190.059"/>
<text text-anchor="middle" x="2163.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1686.1938" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1686.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node26" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1686.1938" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1686.1938" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1686.1938,-434.9735C1686.1938,-423.1918 1686.1938,-407.5607 1686.1938,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="1689.6939,-394.0033 1686.1938,-384.0034 1682.6939,-394.0034 1689.6939,-394.0033"/>
<text text-anchor="middle" x="1757.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node6" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="236.1938" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="236.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge41" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M230.9323,-86.9996C228.9091,-75.9582 228.7891,-62.3776 237.1938,-54 256.9269,-34.3303 2071.8605,-20.5698 2387.6172,-18.3236"/>
<polygon fill="#000000" stroke="#000000" points="2387.8164,-21.8224 2397.7913,-18.2515 2387.7668,-14.8226 2387.8164,-21.8224"/>
<text text-anchor="middle" x="299.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node7" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2094.1938" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2094.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2064.638,-435.5076C2043.9394,-424.0883 2015.2508,-409.8843 1988.1938,-402 1942.9247,-388.8089 1813.8299,-376.5014 1739.9057,-370.2651"/>
<polygon fill="#000000" stroke="#000000" points="1740.1118,-366.7702 1729.8553,-369.426 1739.5293,-373.746 1740.1118,-366.7702"/>
<text text-anchor="middle" x="2119.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="500.1938" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="500.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge44" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M444.2747,-437.5616C410.9928,-424.5923 375.1938,-402.2231 375.1938,-366 375.1938,-366 375.1938,-366 375.1938,-105 375.1938,-52.9005 2080.6514,-23.5716 2387.27,-18.7197"/>
<polygon fill="#000000" stroke="#000000" points="2387.6384,-22.2144 2397.5821,-18.5574 2387.5282,-15.2153 2387.6384,-22.2144"/>
<text text-anchor="middle" x="461.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M570.2502,-439.1977C633.8766,-427.2503 730.4501,-410.5806 815.1938,-402 974.6888,-385.8505 1466.6801,-371.7763 1631.6398,-367.402"/>
<polygon fill="#000000" stroke="#000000" points="1632.1213,-370.8906 1642.0255,-367.128 1631.9366,-363.893 1632.1213,-370.8906"/>
<text text-anchor="middle" x="901.1938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M496.5751,-434.8812C490.3396,-398.3135 481.5903,-314.6121 519.1938,-261 524.0738,-254.0424 579.9359,-230.0075 588.1938,-228 693.9668,-202.2868 1443.883,-194.3784 1682.4846,-192.4991"/>
<polygon fill="#000000" stroke="#000000" points="1682.8106,-195.9967 1692.7831,-192.4192 1682.7562,-188.997 1682.8106,-195.9967"/>
<text text-anchor="middle" x="583.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- genetic_analysis -->
<g id="node9" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="789.1938" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="789.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M852.0416,-440.3239C912.7411,-428.5627 1007.3903,-411.4879 1090.1938,-402 1289.0315,-379.2166 1526.9491,-370.3224 1631.9026,-367.3264"/>
<polygon fill="#000000" stroke="#000000" points="1632.0402,-370.824 1641.9387,-367.0464 1631.8449,-363.8268 1632.0402,-370.824"/>
<text text-anchor="middle" x="1160.1938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M777.4917,-434.7936C761.8578,-408.0612 737.8104,-356.8292 753.1938,-315 770.715,-267.3576 781.5377,-250.1881 827.1938,-228 865.427,-209.4193 1470.6094,-197.0185 1682.5582,-193.2273"/>
<polygon fill="#000000" stroke="#000000" points="1682.7148,-196.7251 1692.651,-193.048 1682.5903,-189.7263 1682.7148,-196.7251"/>
<text text-anchor="middle" x="823.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2049.1938" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2049.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2065.9037,-87.2595C2077.8943,-75.7295 2095.0766,-61.495 2113.1938,-54 2161.6954,-33.935 2310.9038,-23.9652 2387.6052,-20.0554"/>
<polygon fill="#000000" stroke="#000000" points="2388.1145,-23.5345 2397.9289,-19.5435 2387.7678,-16.5431 2388.1145,-23.5345"/>
<text text-anchor="middle" x="2169.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- laboratory_test -->
<g id="node11" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1263.1938" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1263.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1300.7797,-436.9636C1329.0148,-425.5449 1368.9022,-410.7318 1405.1938,-402 1482.848,-383.3163 1575.0559,-373.8502 1632.1057,-369.4257"/>
<polygon fill="#000000" stroke="#000000" points="1632.6278,-372.8964 1642.3375,-368.6571 1632.1034,-365.9161 1632.6278,-372.8964"/>
<text text-anchor="middle" x="1470.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1184.5452,-447.9592C1139.1952,-443.2295 1088.4082,-434.1775 1074.1938,-417 1061.8602,-402.0955 966.6371,-412.4409 1079.1938,-261 1106.358,-224.4516 1131.5192,-236.8241 1176.1938,-228 1271.0465,-209.2647 1549.3025,-198.3825 1682.506,-194.1122"/>
<polygon fill="#000000" stroke="#000000" points="1682.7315,-197.6069 1692.6156,-193.7919 1682.5097,-190.6104 1682.7315,-197.6069"/>
<text text-anchor="middle" x="1109.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- consent_group -->
<g id="node12" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2216.1938" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2216.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge26" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2220.9285,-86.9766C2224.8081,-75.7807 2231.451,-62.0376 2242.1938,-54 2264.6934,-37.166 2338.5157,-27.0412 2387.789,-21.9934"/>
<polygon fill="#000000" stroke="#000000" points="2388.2967,-25.4603 2397.9035,-20.9927 2387.6074,-18.4943 2388.2967,-25.4603"/>
<text text-anchor="middle" x="2305.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_other -->
<g id="node13" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2707.1938" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2707.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2675.2627,-262.1918C2649.237,-248.8201 2614.3932,-231.7502 2599.1938,-228 2525.4833,-209.813 2018.8388,-197.4946 1827.8405,-193.4497"/>
<polygon fill="#000000" stroke="#000000" points="1827.6947,-189.946 1817.6233,-193.2349 1827.5475,-196.9444 1827.6947,-189.946"/>
<text text-anchor="middle" x="2702.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="628.1938" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="628.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M605.695,-261.1882C595.1352,-250.7557 586.7355,-237.7566 596.1938,-228 615.1648,-208.4306 1431.8996,-196.2029 1682.7096,-192.9042"/>
<polygon fill="#000000" stroke="#000000" points="1682.8561,-196.4027 1692.8095,-192.7722 1682.7646,-189.4033 1682.8561,-196.4027"/>
<text text-anchor="middle" x="675.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2376.1938" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2376.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge33" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2372.5172,-86.905C2371.375,-76.6233 2371.625,-63.8733 2377.1938,-54 2381.6571,-46.0865 2388.6545,-39.6621 2396.2388,-34.5514"/>
<polygon fill="#000000" stroke="#000000" points="2398.5029,-37.276 2405.295,-29.1448 2394.9146,-31.2657 2398.5029,-37.276"/>
<text text-anchor="middle" x="2428.1938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- generic_file -->
<g id="node16" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2468.1938" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2468.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2524.2558,-443.505C2561.9877,-436.8247 2612.7716,-427.2718 2657.1938,-417 2813.2807,-380.9079 2990.1938,-439.2054 2990.1938,-279 2990.1938,-279 2990.1938,-279 2990.1938,-105 2990.1938,-53.6318 2614.9679,-27.9484 2481.0143,-20.4163"/>
<polygon fill="#000000" stroke="#000000" points="2480.8526,-16.9021 2470.6745,-19.8441 2480.4658,-23.8914 2480.8526,-16.9021"/>
<text text-anchor="middle" x="3043.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2418.5944,-440.9975C2367.8193,-429.1847 2286.47,-411.5674 2215.1938,-402 2042.8809,-378.8706 1836.8871,-370.2746 1740.6994,-367.3568"/>
<polygon fill="#000000" stroke="#000000" points="1740.728,-363.8562 1730.6292,-367.0601 1740.5218,-370.8532 1740.728,-363.8562"/>
<text text-anchor="middle" x="2353.1938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2467.9176,-434.8372C2466.9603,-383.8636 2462.9819,-242.2544 2448.1938,-228 2426.1218,-206.7247 2000.9451,-196.5214 1827.7139,-193.2344"/>
<polygon fill="#000000" stroke="#000000" points="1827.7304,-189.7342 1817.6666,-193.0461 1827.5992,-196.7329 1827.7304,-189.7342"/>
<text text-anchor="middle" x="2516.1938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- survival -->
<g id="node17" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1352.1938" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1352.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1347.0586,-260.7121C1345.2042,-249.8411 1345.2209,-236.5489 1353.1938,-228 1375.1783,-204.427 1573.2456,-196.1424 1682.911,-193.3471"/>
<polygon fill="#000000" stroke="#000000" points="1683.0044,-196.8459 1692.9153,-193.101 1682.8322,-189.8481 1683.0044,-196.8459"/>
<text text-anchor="middle" x="1392.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2890.1938" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2890.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2937.0879,-444.9903C3004.0849,-432.1951 3119.1938,-404.5954 3119.1938,-366 3119.1938,-366 3119.1938,-366 3119.1938,-105 3119.1938,-40.5475 2635.7742,-22.9867 2481.1501,-19.0183"/>
<polygon fill="#000000" stroke="#000000" points="2481.1065,-15.5163 2471.0223,-18.7659 2480.932,-22.5141 2481.1065,-15.5163"/>
<text text-anchor="middle" x="3161.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2841.2168,-446.8771C2754.4771,-436.2389 2568.1016,-414.305 2410.1938,-402 2160.2659,-382.5244 1860.9357,-371.5608 1740.4007,-367.6542"/>
<polygon fill="#000000" stroke="#000000" points="1740.43,-364.1535 1730.3228,-367.3306 1740.2052,-371.1499 1740.43,-364.1535"/>
<text text-anchor="middle" x="2610.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2899.0326,-435.2359C2915.0913,-400.3472 2945.1069,-321.0474 2919.1938,-261 2910.7227,-241.3703 2903.9358,-236.206 2884.1938,-228 2835.435,-207.7328 2069.3939,-196.0843 1827.6772,-192.8997"/>
<polygon fill="#000000" stroke="#000000" points="1827.6347,-189.3989 1817.5897,-192.7677 1827.543,-196.3983 1827.6347,-189.3989"/>
<text text-anchor="middle" x="2971.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node20" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1502.1938" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1502.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1518.4117,-435.1584C1529.2719,-424.1804 1544.4239,-410.6107 1560.1938,-402 1583.4312,-389.3119 1611.5797,-380.7201 1635.3723,-375.1223"/>
<polygon fill="#000000" stroke="#000000" points="1636.2826,-378.5052 1645.2754,-372.9034 1634.752,-371.6746 1636.2826,-378.5052"/>
<text text-anchor="middle" x="1621.1938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2861.1938" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2861.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2875.2535,-261.6353C2881.7718,-251.3614 2886.7742,-238.3719 2880.1938,-228 2789.8186,-85.5544 2574.2059,-37.9674 2479.791,-23.6117"/>
<polygon fill="#000000" stroke="#000000" points="2480.0983,-20.1195 2469.6968,-22.1341 2479.0844,-27.0457 2480.0983,-20.1195"/>
<text text-anchor="middle" x="2852.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2834.1581,-263.7075C2823.2257,-257.4186 2810.534,-249.9837 2799.1938,-243 2788.8022,-236.6005 2787.8288,-231.6831 2776.1938,-228 2686.6202,-199.6452 2045.8791,-193.5658 1827.717,-192.3126"/>
<polygon fill="#000000" stroke="#000000" points="1827.671,-188.8124 1817.6516,-192.2565 1827.6319,-195.8123 1827.671,-188.8124"/>
<text text-anchor="middle" x="2839.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- diagnosis -->
<g id="node22" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="983.1938" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="983.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1037.118,-450.0742C1088.6665,-446.1616 1168.0957,-437.1975 1234.1938,-417 1248.8316,-412.5271 1250.4342,-406.0528 1265.1938,-402 1332.763,-383.4464 1533.9337,-372.5361 1631.6784,-368.1937"/>
<polygon fill="#000000" stroke="#000000" points="1632.102,-371.6786 1641.9396,-367.7452 1631.7963,-364.6853 1632.102,-371.6786"/>
<text text-anchor="middle" x="1309.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M977.2336,-434.9409C966.3693,-404.9903 940.3932,-345.3409 897.1938,-315 865.9492,-293.0556 837.1972,-326.692 813.1938,-297 803.1349,-284.5573 804.2099,-274.2397 813.1938,-261 835.4836,-228.1509 857.3696,-236.2814 896.1938,-228 971.9337,-211.8443 1489.4208,-198.2233 1682.6375,-193.6451"/>
<polygon fill="#000000" stroke="#000000" points="1682.7784,-197.1428 1692.6931,-193.408 1682.6134,-190.1448 1682.7784,-197.1428"/>
<text text-anchor="middle" x="958.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node23" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1884.1938" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1884.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1877.9939,-260.7804C1873.4708,-249.935 1866.3436,-236.6459 1856.1938,-228 1844.6799,-218.1922 1830.3007,-210.9837 1816.0348,-205.7125"/>
<polygon fill="#000000" stroke="#000000" points="1816.8076,-202.2782 1806.2131,-202.3646 1814.5491,-208.9039 1816.8076,-202.2782"/>
<text text-anchor="middle" x="1971.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2412.1938" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2412.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2430.3252,-264.9607C2436.9432,-258.9065 2443.8602,-251.3067 2448.1938,-243 2484.5266,-173.3566 2472.278,-147.246 2479.1938,-69 2479.7807,-62.3592 2482.0817,-60.0087 2479.1938,-54 2476.2236,-47.8202 2471.6188,-42.3692 2466.4675,-37.6997"/>
<polygon fill="#000000" stroke="#000000" points="2468.6435,-34.9583 2458.6557,-31.4235 2464.2592,-40.4153 2468.6435,-34.9583"/>
<text text-anchor="middle" x="2499.1938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2406.3188,-261.1761C2401.5011,-249.609 2393.4505,-235.3643 2381.1938,-228 2334.816,-200.1344 1982.9358,-193.8378 1828.0234,-192.4151"/>
<polygon fill="#000000" stroke="#000000" points="1827.6934,-188.9122 1817.6631,-192.3246 1827.6321,-195.912 1827.6934,-188.9122"/>
<text text-anchor="middle" x="2420.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3234.1938" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3234.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3207.5668,-87.6744C3187.884,-75.8573 3159.9634,-61.1078 3133.1938,-54 3070.6054,-37.3817 2627.5956,-23.4781 2481.0972,-19.2906"/>
<polygon fill="#000000" stroke="#000000" points="2480.7618,-15.7798 2470.6665,-18.9946 2480.5631,-22.7769 2480.7618,-15.7798"/>
<text text-anchor="middle" x="3239.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1730.3346,-364.8351C1886.2577,-360.624 2410.7591,-345.6135 2578.1938,-330 2678.827,-320.6158 2704.6327,-319.3793 2803.1938,-297 2807.0172,-296.1319 2810.9537,-295.1361 2814.8898,-294.0681"/>
<polygon fill="#000000" stroke="#000000" points="2815.9517,-297.4049 2824.6082,-291.2962 2814.0317,-290.6734 2815.9517,-297.4049"/>
<text text-anchor="middle" x="2746.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1730.3259,-363.6138C1862.3891,-356.1533 2252.8866,-331.6799 2375.1938,-297 2377.1524,-296.4446 2379.1336,-295.7898 2381.1079,-295.0646"/>
<polygon fill="#000000" stroke="#000000" points="2382.9309,-298.0945 2390.7872,-290.9861 2380.2128,-291.6438 2382.9309,-298.0945"/>
<text text-anchor="middle" x="2314.6938" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1642.5024,-362.8122C1558.9266,-355.0733 1389.4471,-330.519 1445.1938,-261 1474.6221,-224.3014 1602.5439,-205.87 1684.5863,-197.6585"/>
<polygon fill="#000000" stroke="#000000" points="1684.9882,-201.136 1694.6021,-196.6837 1684.3101,-194.1689 1684.9882,-201.136"/>
<text text-anchor="middle" x="1481.6938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge34" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1808.3744,-182.4877C1880.7877,-169.4609 2014.4252,-145.1562 2128.1938,-123 2134.4216,-121.7871 2140.8927,-120.5051 2147.3725,-119.2066"/>
<polygon fill="#000000" stroke="#000000" points="2148.4168,-122.5666 2157.5283,-117.1599 2147.0339,-115.7045 2148.4168,-122.5666"/>
<text text-anchor="middle" x="2076.6938" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node28" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3399.1938" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3399.1938" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3377.6291,-88.0845C3361.0387,-76.1398 3336.9934,-61.053 3313.1938,-54 3233.3189,-30.3292 2651.1159,-20.8571 2480.8448,-18.5751"/>
<polygon fill="#000000" stroke="#000000" points="2480.7452,-15.0736 2470.6999,-18.4411 2480.6528,-22.0729 2480.7452,-15.0736"/>
<text text-anchor="middle" x="3393.6938" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment_radiation -->
<g id="node29" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1632.1938" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1632.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1650.4122,-261.1517C1661.4344,-250.8311 1676.0513,-237.9589 1690.1938,-228 1697.8619,-222.6002 1706.4172,-217.3639 1714.7371,-212.6337"/>
<polygon fill="#000000" stroke="#000000" points="1716.5664,-215.6217 1723.6197,-207.7159 1713.1757,-209.4976 1716.5664,-215.6217"/>
<text text-anchor="middle" x="1773.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- sequencing_file -->
<g id="node30" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1877.1938" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1877.1938" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1865.8439,-434.8681C1857.9854,-423.7743 1846.5564,-410.1846 1833.1938,-402 1805.0334,-384.7518 1769.0925,-375.7624 1739.7981,-371.0799"/>
<polygon fill="#000000" stroke="#000000" points="1740.1407,-367.5927 1729.7372,-369.5968 1739.1198,-374.5179 1740.1407,-367.5927"/>
<text text-anchor="middle" x="1917.6938" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node31" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2293.1938" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2293.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2278.6888,-261.3062C2267.9973,-249.6394 2252.3745,-235.2247 2235.1938,-228 2198.62,-212.6203 1952.153,-200.2474 1827.3349,-194.884"/>
<polygon fill="#000000" stroke="#000000" points="1827.2437,-191.3771 1817.1038,-194.4484 1826.9458,-198.3707 1827.2437,-191.3771"/>
<text text-anchor="middle" x="2318.1938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node32" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2549.1938" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2549.1938" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2532.5013,-261.6508C2519.9144,-249.8223 2501.5557,-235.0688 2482.1938,-228 2421.9204,-205.9949 1999.6924,-196.2466 1827.7702,-193.1574"/>
<polygon fill="#000000" stroke="#000000" points="1827.6129,-189.6542 1817.5525,-192.9764 1827.4889,-196.6531 1827.6129,-189.6542"/>
<text text-anchor="middle" x="2551.6938" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
</g>
</svg>
</div>
