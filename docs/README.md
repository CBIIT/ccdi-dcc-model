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
<svg width="3179pt" height="479pt"
 viewBox="0.00 0.00 3178.99 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3174.985,-475 3174.985,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1769.8927" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1769.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node24" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1611.8927" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1611.8927" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1759.4164,-435.1146C1752.1335,-424.1191 1741.4905,-410.5464 1728.8927,-402 1709.383,-388.7646 1684.8122,-380.2399 1663.2298,-374.8286"/>
<polygon fill="#000000" stroke="#000000" points="1663.7674,-371.3598 1653.2325,-372.4855 1662.17,-378.1751 1663.7674,-371.3598"/>
<text text-anchor="middle" x="1810.3927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1995.8927" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1995.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1347.8927" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1347.8927" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1949.8242,-262.8204C1914.6755,-251.172 1864.8136,-236.1318 1819.8927,-228 1745.1977,-214.4783 1532.5222,-201.7254 1419.8988,-195.6728"/>
<polygon fill="#000000" stroke="#000000" points="1419.8231,-192.1638 1409.6507,-195.1257 1419.4499,-199.1539 1419.8231,-192.1638"/>
<text text-anchor="middle" x="1965.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="81.8927" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="81.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M87.7578,-434.9194C104.4211,-387.2775 157.2034,-259.7835 253.8927,-228 302.3387,-212.0749 1038.8993,-197.5422 1275.3883,-193.266"/>
<polygon fill="#000000" stroke="#000000" points="1275.6646,-196.7617 1285.6,-193.0822 1275.5385,-189.7629 1275.6646,-196.7617"/>
<text text-anchor="middle" x="212.3927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M150.1677,-442.9347C233.9788,-431.0123 380.5489,-411.5662 506.8927,-402 714.6799,-386.2673 1364.9097,-371.3247 1557.5755,-367.1497"/>
<polygon fill="#000000" stroke="#000000" points="1557.8175,-370.6454 1567.7396,-366.9303 1557.6664,-363.647 1557.8175,-370.6454"/>
<text text-anchor="middle" x="572.3927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="347.8927" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="347.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2473.8927" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2473.8927" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M322.9274,-435.2172C259.2954,-389.6313 95.107,-270.2682 81.8927,-243 78.9854,-237.0007 77.402,-232.9273 81.8927,-228 246.0576,-47.8775 2106.1853,-21.5986 2426.9321,-18.3991"/>
<polygon fill="#000000" stroke="#000000" points="2427.2953,-21.8958 2437.2608,-18.2988 2427.2273,-14.8962 2427.2953,-21.8958"/>
<text text-anchor="middle" x="167.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M344.5894,-434.8439C339.0103,-398.5689 331.5179,-315.909 366.8927,-261 382.7463,-236.392 395.7752,-236.1422 423.8927,-228 504.6026,-204.6282 1071.2878,-195.4065 1275.0954,-192.8221"/>
<polygon fill="#000000" stroke="#000000" points="1275.4373,-196.3182 1285.3927,-192.6933 1275.3496,-189.3187 1275.4373,-196.3182"/>
<text text-anchor="middle" x="431.8927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M431.4673,-441.4749C519.6605,-429.7393 662.7963,-411.903 786.8927,-402 1076.658,-378.8766 1424.9479,-369.7989 1557.2842,-367.0232"/>
<polygon fill="#000000" stroke="#000000" points="1557.6294,-370.5169 1567.5551,-366.8114 1557.4851,-363.5184 1557.6294,-370.5169"/>
<text text-anchor="middle" x="872.8927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- genetic_analysis -->
<g id="node5" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="692.8927" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="692.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M667.2237,-435.7407C638.4625,-414.6826 593.4402,-376.125 574.8927,-330 552.1164,-273.3586 609.6224,-249.1453 666.8927,-228 722.7268,-207.385 1111.0182,-196.944 1275.0351,-193.4131"/>
<polygon fill="#000000" stroke="#000000" points="1275.5851,-196.9023 1285.5084,-193.1905 1275.4363,-189.9039 1275.5851,-196.9023"/>
<text text-anchor="middle" x="644.8927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M766.1686,-442.9775C862.4501,-429.9018 1026.4051,-407.9832 1086.8927,-402 1258.4306,-385.0322 1462.2938,-373.5205 1557.6545,-368.6392"/>
<polygon fill="#000000" stroke="#000000" points="1558.1045,-372.121 1567.9141,-368.1183 1557.7495,-365.13 1558.1045,-372.121"/>
<text text-anchor="middle" x="1156.8927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="716.8927" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="716.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M741.2452,-261.7788C759.289,-250.0122 784.9702,-235.2803 809.8927,-228 894.9978,-203.1393 1148.719,-195.3591 1274.9284,-192.9937"/>
<polygon fill="#000000" stroke="#000000" points="1275.3286,-196.4872 1285.2637,-192.8068 1275.202,-189.4883 1275.3286,-196.4872"/>
<text text-anchor="middle" x="868.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node7" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1933.8927" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1933.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1944.1292,-87.1011C1951.8142,-75.5005 1963.4736,-61.2466 1977.8927,-54 2017.4006,-34.1445 2311.2887,-23.014 2427.1413,-19.359"/>
<polygon fill="#000000" stroke="#000000" points="2427.5714,-22.8475 2437.4579,-19.0386 2427.354,-15.8508 2427.5714,-22.8475"/>
<text text-anchor="middle" x="2034.3927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_other -->
<g id="node8" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="462.8927" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="462.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M440.9712,-261.1543C430.6968,-250.7098 422.5569,-237.71 431.8927,-228 446.4591,-212.8499 1060.9628,-198.1848 1275.1643,-193.5244"/>
<polygon fill="#000000" stroke="#000000" points="1275.44,-197.0193 1285.3618,-193.3035 1275.2883,-190.0209 1275.44,-197.0193"/>
<text text-anchor="middle" x="501.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- treatment_surgery -->
<g id="node9" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1258.8927" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1258.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1254.141,-260.5478C1252.5571,-250.147 1252.5571,-237.397 1258.8927,-228 1265.4507,-218.2732 1275.13,-211.1736 1285.7187,-205.9919"/>
<polygon fill="#000000" stroke="#000000" points="1287.3981,-209.0797 1295.2023,-201.9142 1284.633,-202.6489 1287.3981,-209.0797"/>
<text text-anchor="middle" x="1337.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- family_relationship -->
<g id="node10" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1475.8927" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1475.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1457.0226,-261.1048C1445.6122,-250.7679 1430.491,-237.8953 1415.8927,-228 1407.6863,-222.4374 1398.5227,-217.0743 1389.6467,-212.2625"/>
<polygon fill="#000000" stroke="#000000" points="1391.0307,-209.0355 1380.5533,-207.4626 1387.763,-215.226 1391.0307,-209.0355"/>
<text text-anchor="middle" x="1514.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- consent_group -->
<g id="node11" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2100.8927" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2100.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge39" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2095.7791,-86.7322C2093.9329,-75.8687 2093.9506,-62.5774 2101.8927,-54 2123.6162,-30.539 2332.4254,-21.8639 2427.343,-19.1141"/>
<polygon fill="#000000" stroke="#000000" points="2427.6235,-22.6077 2437.5216,-18.8294 2427.4277,-15.6105 2427.6235,-22.6077"/>
<text text-anchor="middle" x="2165.3927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1787.8927" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1787.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1745.4732,-263.3843C1713.1123,-252.0274 1667.2136,-237.1051 1625.8927,-228 1556.2071,-212.6446 1475.1505,-203.0693 1418.6083,-197.6902"/>
<polygon fill="#000000" stroke="#000000" points="1418.6257,-194.1768 1408.3441,-196.7342 1417.9764,-201.1466 1418.6257,-194.1768"/>
<text text-anchor="middle" x="1747.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cytogenomic_file -->
<g id="node13" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1960.8927" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1960.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1939.1789,-435.454C1923.8217,-424.0109 1902.2426,-409.8003 1880.8927,-402 1842.5069,-387.9756 1732.6278,-376.4276 1665.7708,-370.4394"/>
<polygon fill="#000000" stroke="#000000" points="1665.6966,-366.9194 1655.4275,-369.5266 1665.0811,-373.8923 1665.6966,-366.9194"/>
<text text-anchor="middle" x="1982.3927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="861.8927" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="861.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M889.2032,-263.3055C911.0967,-251.5109 942.996,-236.0557 972.8927,-228 1028.2838,-213.0748 1183.849,-201.7002 1276.29,-196.0184"/>
<polygon fill="#000000" stroke="#000000" points="1276.642,-199.5036 1286.4114,-195.4036 1276.2175,-192.5165 1276.642,-199.5036"/>
<text text-anchor="middle" x="1016.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2244.8927" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2244.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2288.0923,-442.9083C2361.3303,-424.1336 2511.8376,-378.1888 2613.8927,-297 2688.6125,-237.5576 2710.4593,-213.8302 2739.8927,-123 2749.3463,-93.8268 2760.0709,-77.093 2739.8927,-54 2725.7,-37.757 2592.9054,-26.1788 2520.483,-21.0139"/>
<polygon fill="#000000" stroke="#000000" points="2520.477,-17.5051 2510.2571,-20.2987 2519.9885,-24.488 2520.477,-17.5051"/>
<text text-anchor="middle" x="2731.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2247.7696,-434.8504C2252.5107,-398.9401 2258.4659,-317.4227 2225.8927,-261 2213.3129,-239.2093 2203.6736,-236.2193 2179.8927,-228 2109.239,-203.5802 1609.7115,-195.1207 1420.3904,-192.7717"/>
<polygon fill="#000000" stroke="#000000" points="1420.3021,-189.2704 1410.2602,-192.6482 1420.2167,-196.2699 1420.3021,-189.2704"/>
<text text-anchor="middle" x="2290.3927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2207.0413,-440.4462C2169.5948,-428.5596 2110.4298,-411.2022 2057.8927,-402 1918.1469,-377.5226 1750.8003,-369.6477 1666.3581,-367.1444"/>
<polygon fill="#000000" stroke="#000000" points="1666.3277,-363.6422 1656.2328,-366.8584 1666.13,-370.6395 1666.3277,-363.6422"/>
<text text-anchor="middle" x="2167.3927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node17" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2330.8927" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2330.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2320.2037,-86.8021C2315.5262,-76.2328 2312.5752,-63.2254 2319.8927,-54 2333.2237,-37.1933 2387.6559,-27.4912 2428.0478,-22.4823"/>
<polygon fill="#000000" stroke="#000000" points="2428.4607,-25.958 2437.9808,-21.3085 2427.6391,-19.0063 2428.4607,-25.958"/>
<text text-anchor="middle" x="2368.3927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment_radiation -->
<g id="node18" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1037.8927" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1037.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1048.953,-260.8827C1056.9188,-249.4978 1068.7341,-235.5779 1082.8927,-228 1115.4047,-210.5992 1209.5973,-200.9321 1276.4086,-196.1009"/>
<polygon fill="#000000" stroke="#000000" points="1276.7389,-199.5864 1286.4693,-195.3947 1276.2487,-192.6036 1276.7389,-199.5864"/>
<text text-anchor="middle" x="1165.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- cell_line -->
<g id="node19" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2167.8927" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2167.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2175.2588,-261.0607C2192.759,-218.9778 2237.2082,-115.333 2261.8927,-87 2279.1402,-67.2033 2286.761,-64.3462 2310.8927,-54 2348.7904,-37.7518 2394.9125,-28.4443 2428.4104,-23.3815"/>
<polygon fill="#000000" stroke="#000000" points="2428.9802,-26.8356 2438.378,-21.9435 2427.9806,-19.9073 2428.9802,-26.8356"/>
<text text-anchor="middle" x="2268.3927" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2141.0057,-263.6773C2118.3108,-251.5902 2084.5466,-235.5525 2052.8927,-228 1992.6496,-213.6262 1587.9776,-199.5061 1420.3741,-194.2011"/>
<polygon fill="#000000" stroke="#000000" points="1420.269,-190.6961 1410.1637,-193.8795 1420.0486,-197.6927 1420.269,-190.6961"/>
<text text-anchor="middle" x="2135.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_status -->
<g id="node20" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2516.8927" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2516.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2507.9831,-86.9735C2501.947,-74.7609 2493.8666,-58.4123 2487.0878,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="2490.2124,-43.1197 2482.6438,-35.7057 2483.9371,-46.2213 2490.2124,-43.1197"/>
<text text-anchor="middle" x="2554.3927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node21" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2401.8927" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2401.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2343.8674,-262.8282C2322.7278,-256.7946 2298.676,-249.7642 2276.8927,-243 2256.7592,-236.7481 2252.6293,-231.7997 2231.8927,-228 2076.9394,-199.6069 1602.7605,-193.6017 1420.4024,-192.3362"/>
<polygon fill="#000000" stroke="#000000" points="1420.3999,-188.8362 1410.3767,-192.2694 1420.3531,-195.836 1420.3999,-188.8362"/>
<text text-anchor="middle" x="2378.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- publication -->
<g id="node22" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2667.8927" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2667.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge35" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2653.4405,-86.9635C2643.663,-75.9076 2629.8425,-62.3245 2614.8927,-54 2585.5027,-37.6347 2548.5422,-28.5544 2519.8366,-23.6081"/>
<polygon fill="#000000" stroke="#000000" points="2520.0934,-20.1044 2509.6636,-21.967 2518.9785,-27.015 2520.0934,-20.1044"/>
<text text-anchor="middle" x="2684.8927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge30" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1408.6638,-187.7063C1525.9459,-178.9755 1791.4778,-157.0472 2012.8927,-123 2019.6239,-121.9649 2026.6194,-120.7592 2033.5932,-119.4711"/>
<polygon fill="#000000" stroke="#000000" points="2034.5929,-122.8438 2043.7619,-117.5353 2033.2837,-115.9673 2034.5929,-122.8438"/>
<text text-anchor="middle" x="1917.3927" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1649.5189,-356.2037C1696.1862,-344.4564 1778.3406,-325.0911 1849.8927,-315 1964.5899,-298.8242 1996.0376,-318.3092 2109.8927,-297 2113.9733,-296.2363 2118.1707,-295.2817 2122.3525,-294.213"/>
<polygon fill="#000000" stroke="#000000" points="2123.3089,-297.5799 2132.0193,-291.5483 2121.4487,-290.8316 2123.3089,-297.5799"/>
<text text-anchor="middle" x="1886.3927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1612.6971,-347.8279C1613.7674,-314.3291 1613.9352,-244.7293 1597.8927,-228 1585.5442,-215.1228 1487.8591,-204.069 1418.3295,-197.7245"/>
<polygon fill="#000000" stroke="#000000" points="1418.5619,-194.2314 1408.2889,-196.823 1417.9358,-201.2034 1418.5619,-194.2314"/>
<text text-anchor="middle" x="1648.3927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node30" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2576.8927" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2576.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1654.7239,-361.2292C1745.7606,-351.2457 1965.2871,-328.0024 2149.8927,-315 2236.4373,-308.9044 2455.8191,-318.4182 2539.8927,-297 2542.0862,-296.4412 2544.3036,-295.7449 2546.5053,-294.9538"/>
<polygon fill="#000000" stroke="#000000" points="2548.0601,-298.0974 2555.9354,-291.0102 2545.3593,-291.6394 2548.0601,-298.0974"/>
<text text-anchor="middle" x="2186.3927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node25" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1382.8927" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1382.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge44" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1389.3969,-434.9006C1394.3752,-423.6734 1402.3656,-409.9241 1413.8927,-402 1436.8557,-386.2145 1508.0742,-376.1239 1558.4981,-370.7599"/>
<polygon fill="#000000" stroke="#000000" points="1559.0128,-374.2255 1568.6011,-369.7183 1558.2948,-367.2624 1559.0128,-374.2255"/>
<text text-anchor="middle" x="1505.3927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2632.8927" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2632.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2697.2794,-449.4104C2794.8426,-442.1835 2968.8927,-421.5118 2968.8927,-366 2968.8927,-366 2968.8927,-366 2968.8927,-105 2968.8927,-77.7581 2958.3923,-67.7802 2934.8927,-54 2899.7565,-33.3959 2630.5886,-22.8347 2520.5463,-19.3426"/>
<polygon fill="#000000" stroke="#000000" points="2520.5112,-15.8399 2510.407,-19.0266 2520.2931,-22.8365 2520.5112,-15.8399"/>
<text text-anchor="middle" x="3021.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2636.3167,-435.0146C2642.1979,-398.6899 2650.3346,-315.4084 2613.8927,-261 2596.5215,-235.0643 2582.0632,-236.01 2551.8927,-228 2442.9863,-199.0862 1664.0465,-193.3408 1420.4849,-192.2468"/>
<polygon fill="#000000" stroke="#000000" points="1420.3398,-188.7463 1410.3246,-192.2025 1420.3092,-195.7462 1420.3398,-188.7463"/>
<text text-anchor="middle" x="2690.8927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2574.3766,-444.7262C2493.492,-433.553 2342.8858,-413.6962 2213.8927,-402 2012.3201,-383.7227 1771.9024,-372.521 1666.246,-368.1309"/>
<polygon fill="#000000" stroke="#000000" points="1666.2813,-364.6295 1656.1457,-367.715 1665.9932,-371.6236 1666.2813,-364.6295"/>
<text text-anchor="middle" x="2404.8927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_funding -->
<g id="node27" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2863.8927" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2863.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2839.2404,-87.6711C2821.5967,-76.1716 2796.8252,-61.807 2772.8927,-54 2727.0557,-39.0476 2592.0771,-26.9549 2520.1874,-21.362"/>
<polygon fill="#000000" stroke="#000000" points="2520.2952,-17.86 2510.0567,-20.5844 2519.7594,-24.8395 2520.2952,-17.86"/>
<text text-anchor="middle" x="2868.8927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pathology_file -->
<g id="node28" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1592.8927" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1592.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1596.8295,-434.9735C1599.4026,-423.1918 1602.8163,-407.5607 1605.7433,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="1609.2467,-394.5199 1607.961,-384.0034 1602.4079,-393.0263 1609.2467,-394.5199"/>
<text text-anchor="middle" x="1663.8927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- survival -->
<g id="node29" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="262.8927" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="262.8927" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M257.6794,-261.0476C255.6755,-250.0253 255.5588,-236.448 263.8927,-228 281.6755,-209.9738 1035.2877,-196.8186 1275.2871,-193.08"/>
<polygon fill="#000000" stroke="#000000" points="1275.3627,-196.5794 1285.3073,-192.9247 1275.2542,-189.5802 1275.3627,-196.5794"/>
<text text-anchor="middle" x="303.3927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge41" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2571.7122,-260.9969C2568.2354,-250.7458 2562.9854,-237.9958 2555.8927,-228 2515.2683,-170.7475 2466.6342,-187.0478 2437.8927,-123 2425.9656,-96.4214 2440.6783,-64.6186 2454.7274,-43.0297"/>
<polygon fill="#000000" stroke="#000000" points="2457.6519,-44.9537 2460.4252,-34.7283 2451.8805,-40.9925 2457.6519,-44.9537"/>
<text text-anchor="middle" x="2482.8927" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2554.37,-268.0612C2534.741,-258.5001 2508.6807,-245.7289 2503.8927,-243 2493.2899,-236.957 2492.5341,-231.6628 2480.8927,-228 2430.3457,-212.0959 1662.6937,-197.468 1420.5111,-193.2288"/>
<polygon fill="#000000" stroke="#000000" points="1420.4638,-189.7276 1410.4042,-193.0526 1420.3417,-196.7265 1420.4638,-189.7276"/>
<text text-anchor="middle" x="2527.8927" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node31" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3083.8927" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3083.8927" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3057.2238,-87.8294C3037.5207,-76.0873 3009.5931,-61.3638 2982.8927,-54 2896.5416,-30.1848 2628.9915,-21.5305 2520.4024,-18.9456"/>
<polygon fill="#000000" stroke="#000000" points="2520.4797,-15.4465 2510.4014,-18.7141 2520.3177,-22.4446 2520.4797,-15.4465"/>
<text text-anchor="middle" x="3089.3927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node32" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1080.8927" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1080.8927" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1026.8056,-450.1498C939.6433,-445.0975 775.7179,-433.5241 754.8927,-417 717.2335,-387.1187 754.9939,-346.7462 718.8927,-315 690.2209,-289.7869 658.8962,-326.692 634.8927,-297 624.8339,-284.5573 624.992,-273.5688 634.8927,-261 674.0573,-211.2814 1101.7895,-197.0037 1275.3504,-193.2408"/>
<polygon fill="#000000" stroke="#000000" points="1275.491,-196.7387 1285.4149,-193.0282 1275.3432,-189.7403 1275.491,-196.7387"/>
<text text-anchor="middle" x="775.3927" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1124.1739,-441.756C1169.2783,-430.377 1242.139,-412.9441 1305.8927,-402 1393.7306,-386.9216 1496.8478,-376.2214 1558.1502,-370.5873"/>
<polygon fill="#000000" stroke="#000000" points="1558.716,-374.0504 1568.3586,-369.6604 1558.083,-367.079 1558.716,-374.0504"/>
<text text-anchor="middle" x="1350.3927" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
