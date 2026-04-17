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
<svg width="3181pt" height="479pt"
 viewBox="0.00 0.00 3181.09 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3177.0923,-475 3177.0923,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2375.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2375.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge43" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8289,-86.9978C79.805,-75.9557 79.6849,-62.3749 88.0923,-54 108.6727,-33.4989 2003.9164,-20.3892 2328.1605,-18.2954"/>
<polygon fill="#000000" stroke="#000000" points="2328.6185,-21.7926 2338.5957,-18.2283 2328.5734,-14.7928 2328.6185,-21.7926"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- treatment_surgery -->
<g id="node2" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1941.0923" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1941.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1765.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1765.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1928.62,-261.0298C1920.0866,-250.0004 1907.8543,-236.4218 1894.0923,-228 1874.9166,-216.2652 1851.8243,-208.2593 1830.5092,-202.8394"/>
<polygon fill="#000000" stroke="#000000" points="1831.0784,-199.3769 1820.5385,-200.4545 1829.4499,-206.1849 1831.0784,-199.3769"/>
<text text-anchor="middle" x="1990.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2158.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2158.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2134.8911,-261.3643C2118.516,-249.8811 2095.5722,-235.6594 2073.0923,-228 2030.6626,-213.5432 1913.1093,-202.6616 1836.1186,-196.8211"/>
<polygon fill="#000000" stroke="#000000" points="1836.2374,-193.3203 1826.0042,-196.065 1835.7155,-200.3008 1836.2374,-193.3203"/>
<text text-anchor="middle" x="2184.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2350.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2350.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2328.5918,-261.5398C2312.8472,-249.8209 2290.4161,-235.2477 2268.0923,-228 2190.2137,-202.7158 1957.6084,-195.1608 1837.9572,-192.9253"/>
<polygon fill="#000000" stroke="#000000" points="1837.8509,-189.4229 1827.7897,-192.7431 1837.7254,-196.4218 1837.8509,-189.4229"/>
<text text-anchor="middle" x="2358.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1246.0923" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1246.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1242.1093,-434.857C1235.1109,-397.8775 1224.8918,-312.9054 1265.0923,-261 1291.1797,-227.3168 1313.5105,-237.2772 1355.0923,-228 1417.6282,-214.0478 1593.7609,-201.9763 1693.6391,-195.9978"/>
<polygon fill="#000000" stroke="#000000" points="1693.8771,-199.4899 1703.6521,-195.4035 1693.4623,-192.5022 1693.8771,-199.4899"/>
<text text-anchor="middle" x="1327.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1148.0727,-445.1559C932.2097,-427.0424 430.2621,-380.0092 372.0923,-330 336.6171,-299.5016 314.7608,-262.7416 346.0923,-228 483.5846,-75.5429 2036.7315,-26.9777 2328.1292,-19.1808"/>
<polygon fill="#000000" stroke="#000000" points="2328.4454,-22.6738 2338.3492,-18.9103 2328.2601,-15.6762 2328.4454,-22.6738"/>
<text text-anchor="middle" x="432.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sample -->
<g id="node30" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2266.0923" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2266.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1284.8218,-436.1752C1314.1985,-424.2769 1355.9032,-409.2082 1394.0923,-402 1474.0168,-386.9142 2033.3348,-371.8085 2211.6254,-367.3294"/>
<polygon fill="#000000" stroke="#000000" points="2211.9104,-370.8234 2221.8198,-367.0744 2211.7354,-363.8256 2211.9104,-370.8234"/>
<text text-anchor="middle" x="1480.0923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2766.0923" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2766.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2798.7267,-438.4978C2807.2126,-433.0445 2815.3073,-425.9407 2820.0923,-417 2840.7619,-378.3784 2800.8794,-251.7817 2764.0923,-228 2725.3555,-202.9579 2061.8149,-194.6798 1838.0749,-192.5935"/>
<polygon fill="#000000" stroke="#000000" points="1837.789,-189.0908 1827.7573,-192.4988 1837.7247,-196.0905 1837.789,-189.0908"/>
<text text-anchor="middle" x="2861.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2718.821,-443.7568C2685.9151,-437.0464 2641.1136,-427.359 2602.0923,-417 2580.4898,-411.2652 2575.935,-406.7383 2554.0923,-402 2473.4936,-384.5157 2378.2318,-374.673 2320.0023,-369.8475"/>
<polygon fill="#000000" stroke="#000000" points="2320.1753,-366.3502 2309.9255,-369.032 2319.6106,-373.3273 2320.1753,-366.3502"/>
<text text-anchor="middle" x="2646.5923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_other -->
<g id="node7" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="502.0923" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="502.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M526.3678,-261.5061C544.3742,-249.6075 570.0426,-234.8298 595.0923,-228 700.382,-199.2926 1452.7381,-193.4148 1692.1375,-192.2665"/>
<polygon fill="#000000" stroke="#000000" points="1692.487,-195.765 1702.4705,-192.2184 1692.4543,-188.7651 1692.487,-195.765"/>
<text text-anchor="middle" x="664.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="332.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="332.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge44" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M320.6933,-87.215C315.2377,-76.2596 311.5495,-62.6938 320.0923,-54 338.2916,-35.479 2023.7217,-20.8653 2328.2176,-18.3751"/>
<polygon fill="#000000" stroke="#000000" points="2328.4908,-21.8731 2338.4619,-18.2917 2328.4337,-14.8734 2328.4908,-21.8731"/>
<text text-anchor="middle" x="371.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- consent_group -->
<g id="node9" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1923.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1923.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge1" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1980.1773,-92.3317C2029.1384,-81.6193 2101.6201,-66.1241 2165.0923,-54 2221.8183,-43.1645 2287.4611,-32.1556 2330.0458,-25.2149"/>
<polygon fill="#000000" stroke="#000000" points="2330.7816,-28.6414 2340.0912,-23.5835 2329.6594,-21.7319 2330.7816,-28.6414"/>
<text text-anchor="middle" x="2228.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge28" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1794.0719,-176.0429C1819.2046,-162.204 1855.8113,-142.0471 1883.6176,-126.7361"/>
<polygon fill="#000000" stroke="#000000" points="1885.6093,-129.6349 1892.6809,-121.7455 1882.2329,-123.5031 1885.6093,-129.6349"/>
<text text-anchor="middle" x="1904.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1692.0923" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1692.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1715.669,-435.573C1732.871,-423.8699 1757.2536,-409.3017 1781.0923,-402 1860.1802,-377.7757 2102.3023,-369.5441 2211.5755,-367.0149"/>
<polygon fill="#000000" stroke="#000000" points="2211.8065,-370.5107 2221.7256,-366.7876 2211.6498,-363.5124 2211.8065,-370.5107"/>
<text text-anchor="middle" x="1852.5923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- synonym -->
<g id="node13" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="387.0923" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="387.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M382.4925,-435.032C374.0037,-397.2384 360.625,-309.0541 406.0923,-261 424.021,-242.0512 497.0562,-250.3273 522.0923,-243 537.9437,-238.3608 539.9835,-231.6467 556.0923,-228 666.4467,-203.0177 1447.9403,-194.5838 1692.2733,-192.5416"/>
<polygon fill="#000000" stroke="#000000" points="1692.495,-196.04 1702.4657,-192.4575 1692.4372,-189.0402 1692.495,-196.04"/>
<text text-anchor="middle" x="421.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M340.0933,-445.2005C297.4129,-435.1136 241.0923,-412.9149 241.0923,-366 241.0923,-366 241.0923,-366 241.0923,-105 241.0923,-87.5957 284.5716,-62.084 311.0923,-54 410.6708,-23.6465 2030.1422,-18.7355 2328.159,-18.0877"/>
<polygon fill="#000000" stroke="#000000" points="2328.6043,-21.5868 2338.5968,-18.0656 2328.5894,-14.5868 2328.6043,-21.5868"/>
<text text-anchor="middle" x="283.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M438.1961,-449.5627C571.7553,-440.6708 942.2745,-416.589 1251.0923,-402 1617.8221,-384.6752 2059.4474,-371.7174 2211.5351,-367.4837"/>
<polygon fill="#000000" stroke="#000000" points="2211.6566,-370.9818 2221.5557,-367.2058 2211.4625,-363.9845 2211.6566,-370.9818"/>
<text text-anchor="middle" x="1293.5923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pathology_file -->
<g id="node14" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2125.0923" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2125.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2124.9593,-434.7921C2125.8477,-423.9511 2128.7783,-410.6625 2137.0923,-402 2148.061,-390.5715 2183.897,-381.1103 2215.0222,-374.7597"/>
<polygon fill="#000000" stroke="#000000" points="2215.79,-378.1758 2224.9248,-372.8086 2214.4368,-371.3079 2215.79,-378.1758"/>
<text text-anchor="middle" x="2198.0923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_status -->
<g id="node15" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2301.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2301.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2296.5843,-86.7061C2295.0817,-76.3582 2295.0817,-63.6082 2301.0923,-54 2308.2774,-42.5143 2320.2932,-34.5981 2332.575,-29.1829"/>
<polygon fill="#000000" stroke="#000000" points="2333.9096,-32.4191 2341.9432,-25.5116 2331.3555,-25.9016 2333.9096,-32.4191"/>
<text text-anchor="middle" x="2357.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2449.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2449.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2440.0759,-87.0437C2434.4871,-76.8082 2426.7371,-64.0582 2418.0923,-54 2413.761,-48.9606 2408.6829,-44.0495 2403.5641,-39.5564"/>
<polygon fill="#000000" stroke="#000000" points="2405.5032,-36.6153 2395.588,-32.8817 2401.0107,-41.9836 2405.5032,-36.6153"/>
<text text-anchor="middle" x="2476.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="660.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="660.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M688.9563,-263.5678C713.2934,-251.4156 749.4398,-235.3436 783.0923,-228 870.982,-208.8208 1480.6527,-196.8077 1692.6424,-193.1716"/>
<polygon fill="#000000" stroke="#000000" points="1692.7948,-196.6696 1702.7337,-192.9997 1692.6755,-189.6706 1692.7948,-196.6696"/>
<text text-anchor="middle" x="826.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node18" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="861.0923" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="861.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M865.2934,-260.9491C868.9902,-249.4385 875.6305,-235.3492 887.0923,-228 920.7576,-206.4141 1488.4521,-196.0357 1692.654,-192.9882"/>
<polygon fill="#000000" stroke="#000000" points="1692.7336,-196.4875 1702.6808,-192.8401 1692.6302,-189.4883 1692.7336,-196.4875"/>
<text text-anchor="middle" x="989.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2736.0923" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2736.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2727.0524,-261.7207C2719.8514,-249.926 2708.5819,-235.1843 2694.0923,-228 2655.9667,-209.0964 2050.0357,-196.9047 1837.8199,-193.1972"/>
<polygon fill="#000000" stroke="#000000" points="1837.7737,-189.696 1827.7145,-193.0219 1837.6522,-196.695 1837.7737,-189.696"/>
<text text-anchor="middle" x="2736.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2750.9439,-263.6915C2755.9288,-257.6922 2761.0016,-250.4615 2764.0923,-243 2796.2417,-165.3843 2831.2615,-100.1959 2761.0923,-54 2733.2946,-35.6994 2518.0268,-24.1875 2421.5724,-19.8987"/>
<polygon fill="#000000" stroke="#000000" points="2421.6604,-16.3993 2411.5169,-19.4587 2421.3543,-23.3926 2421.6604,-16.3993"/>
<text text-anchor="middle" x="2824.0923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_response -->
<g id="node20" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1113.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1113.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1100.5533,-260.8877C1094.7394,-250.0827 1090.7567,-236.7983 1099.0923,-228 1119.2495,-206.7237 1524.1917,-196.5824 1692.6007,-193.2724"/>
<polygon fill="#000000" stroke="#000000" points="1692.6901,-196.7714 1702.6203,-193.0781 1692.5542,-189.7727 1692.6901,-196.7714"/>
<text text-anchor="middle" x="1182.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_funding -->
<g id="node21" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2693.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2693.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2667.9629,-87.7052C2650.3022,-76.3742 2625.7033,-62.1944 2602.0923,-54 2541.8132,-33.0797 2468.2708,-24.2484 2421.5535,-20.5661"/>
<polygon fill="#000000" stroke="#000000" points="2421.6628,-17.0647 2411.4314,-19.816 2421.1454,-24.0456 2421.6628,-17.0647"/>
<text text-anchor="middle" x="2695.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- genetic_analysis -->
<g id="node22" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1497.0923" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1497.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1519.9024,-435.348C1526.4303,-429.8061 1533.3315,-423.4437 1539.0923,-417 1594.961,-354.508 1583.639,-318.0093 1645.0923,-261 1667.256,-240.439 1696.6148,-223.4234 1720.745,-211.4338"/>
<polygon fill="#000000" stroke="#000000" points="1722.5742,-214.4369 1730.049,-206.9284 1719.5232,-208.1368 1722.5742,-214.4369"/>
<text text-anchor="middle" x="1671.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1528.9857,-436.103C1554.7435,-422.7786 1589.0866,-405.8245 1604.0923,-402 1662.1606,-387.2003 2063.8364,-372.656 2211.6541,-367.7454"/>
<polygon fill="#000000" stroke="#000000" points="2211.9711,-371.2369 2221.8501,-367.4086 2211.7399,-364.2407 2211.9711,-371.2369"/>
<text text-anchor="middle" x="1674.0923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- survival -->
<g id="node23" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1322.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1322.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1337.3292,-261.6579C1348.6847,-249.9947 1365.256,-235.4394 1383.0923,-228 1437.2204,-205.4235 1597.6139,-196.8726 1692.4797,-193.734"/>
<polygon fill="#000000" stroke="#000000" points="1692.6969,-197.229 1702.5803,-193.4121 1692.4739,-190.2325 1692.6969,-197.229"/>
<text text-anchor="middle" x="1422.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_radiation -->
<g id="node24" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1493.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1493.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1475.7787,-260.9681C1467.7839,-250.4576 1461.722,-237.4538 1470.0923,-228 1484.6824,-211.5212 1610.8823,-201.0161 1693.4263,-195.8424"/>
<polygon fill="#000000" stroke="#000000" points="1693.7491,-199.3292 1703.5157,-195.2228 1693.32,-192.3424 1693.7491,-199.3292"/>
<text text-anchor="middle" x="1553.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- generic_file -->
<g id="node25" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2946.0923" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2946.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2945.3026,-434.8019C2943.2703,-406.7143 2936.0113,-352.1658 2910.0923,-315 2871.3737,-259.4806 2849.3078,-249.3986 2785.0923,-228 2696.0438,-198.3263 2055.6436,-193.1113 1837.5834,-192.1951"/>
<polygon fill="#000000" stroke="#000000" points="1837.5367,-188.695 1827.5227,-192.1547 1837.5085,-195.695 1837.5367,-188.695"/>
<text text-anchor="middle" x="2971.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2992.528,-440.0581C3026.6506,-427.3872 3067.0923,-404.2925 3067.0923,-366 3067.0923,-366 3067.0923,-366 3067.0923,-105 3067.0923,-67.9295 3035.8168,-66.978 3001.0923,-54 2947.3639,-33.9195 2557.8075,-22.5023 2421.7994,-19.0941"/>
<polygon fill="#000000" stroke="#000000" points="2421.7797,-15.5927 2411.6962,-18.8441 2421.6065,-22.5905 2421.7797,-15.5927"/>
<text text-anchor="middle" x="3120.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2896.0605,-441.2532C2844.8524,-429.6416 2762.8355,-412.1797 2691.0923,-402 2558.657,-383.2087 2401.5112,-373.012 2320.4676,-368.6371"/>
<polygon fill="#000000" stroke="#000000" points="2320.1923,-365.1176 2310.0209,-368.0827 2319.8213,-372.1078 2320.1923,-365.1176"/>
<text text-anchor="middle" x="2828.0923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sequencing_file -->
<g id="node26" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2302.0923" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2302.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2280.1086,-435.6106C2274.8777,-430.2507 2269.9802,-423.918 2267.0923,-417 2264.137,-409.9207 2263.0672,-401.7928 2262.9453,-394.1366"/>
<polygon fill="#000000" stroke="#000000" points="2266.4436,-394.2425 2263.2785,-384.1315 2259.4475,-394.0094 2266.4436,-394.2425"/>
<text text-anchor="middle" x="2333.5923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node27" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2937.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2937.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2915.3358,-87.8198C2899.1541,-76.073 2875.9983,-61.3479 2853.0923,-54 2773.7024,-28.5331 2525.7633,-20.8778 2421.7531,-18.7534"/>
<polygon fill="#000000" stroke="#000000" points="2421.6255,-15.2503 2411.5588,-18.5535 2421.4883,-22.2489 2421.6255,-15.2503"/>
<text text-anchor="middle" x="2940.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node28" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1739.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1739.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1744.4795,-260.9735C1748.0353,-249.0751 1752.7645,-233.2508 1756.796,-219.7606"/>
<polygon fill="#000000" stroke="#000000" points="1760.202,-220.5869 1759.712,-210.0034 1753.4951,-218.5825 1760.202,-220.5869"/>
<text text-anchor="middle" x="1822.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- laboratory_test -->
<g id="node29" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2528.0923" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2528.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2596.619,-443.1211C2626.6329,-437.2568 2657.0852,-428.6582 2666.0923,-417 2669.0578,-413.1616 2683.4716,-297.9956 2657.0923,-261 2635.0009,-230.0182 2615.2267,-236.3028 2578.0923,-228 2507.0485,-212.1154 2023.4337,-198.4737 1837.6117,-193.7594"/>
<polygon fill="#000000" stroke="#000000" points="1837.4817,-190.2551 1827.3966,-193.5016 1837.3051,-197.2529 1837.4817,-190.2551"/>
<text text-anchor="middle" x="2737.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2478.1983,-438.692C2460.4183,-432.8689 2440.4967,-425.4955 2423.0923,-417 2412.125,-411.6467 2411.2347,-406.9783 2400.0923,-402 2373.4922,-390.1154 2342.1171,-381.4251 2316.416,-375.5635"/>
<polygon fill="#000000" stroke="#000000" points="2317.0245,-372.1137 2306.5054,-373.378 2315.517,-378.9495 2317.0245,-372.1137"/>
<text text-anchor="middle" x="2488.5923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2309.1656,-361.3105C2348.6218,-354.476 2404.8947,-337.7585 2432.0923,-297 2449.3289,-271.169 2445.7774,-246.8412 2421.0923,-228 2398.2102,-210.535 2003.3952,-198.2264 1837.5395,-193.8039"/>
<polygon fill="#000000" stroke="#000000" points="1837.5175,-190.3022 1827.4285,-193.5365 1837.3324,-197.2997 1837.5175,-190.3022"/>
<text text-anchor="middle" x="2478.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2309.9517,-363.115C2380.7336,-358.0499 2516.7976,-346.5064 2562.0923,-330 2573.5586,-325.8214 2573.8802,-319.8195 2585.0923,-315 2590.4216,-312.7092 2656.9002,-297.2122 2699.8543,-287.3115"/>
<polygon fill="#000000" stroke="#000000" points="2700.7278,-290.7021 2709.6878,-285.0479 2699.1575,-283.8805 2700.7278,-290.7021"/>
<text text-anchor="middle" x="2621.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node31" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2599.0923" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2599.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2309.9896,-363.1472C2351.4578,-359.294 2414.7765,-350.3771 2466.0923,-330 2477.4348,-325.496 2478.0878,-320.2764 2489.0923,-315 2500.3989,-309.5788 2526.8253,-300.8872 2550.9418,-293.4024"/>
<polygon fill="#000000" stroke="#000000" points="2552.2048,-296.6758 2560.7329,-290.3892 2550.1457,-289.9855 2552.2048,-296.6758"/>
<text text-anchor="middle" x="2525.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2559.3923,-268.1054C2539.0778,-261.89 2514.2405,-253.285 2493.0923,-243 2482.1173,-237.6626 2481.6979,-231.7748 2470.0923,-228 2411.1952,-208.8435 2005.7435,-197.4937 1837.7523,-193.5661"/>
<polygon fill="#000000" stroke="#000000" points="1837.5966,-190.0616 1827.5182,-193.3291 1837.4345,-197.0597 1837.5966,-190.0616"/>
<text text-anchor="middle" x="2533.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge20" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2599.1378,-260.7038C2598.1981,-217.8379 2589.5899,-110.2927 2529.0923,-54 2513.5133,-39.5039 2460.3401,-29.3639 2420.8106,-23.6195"/>
<polygon fill="#000000" stroke="#000000" points="2421.2209,-20.1429 2410.8316,-22.2193 2420.2482,-27.075 2421.2209,-20.1429"/>
<text text-anchor="middle" x="2624.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- methylation_array_file -->
<g id="node32" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1915.0923" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1915.0923" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge42" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1919.5461,-434.9537C1923.3309,-423.5988 1929.9738,-409.6856 1941.0923,-402 1962.8561,-386.9558 2125.267,-374.7318 2211.9425,-369.1984"/>
<polygon fill="#000000" stroke="#000000" points="2212.3626,-372.679 2222.1227,-368.5571 2211.9224,-365.6929 2212.3626,-372.679"/>
<text text-anchor="middle" x="2032.5923" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
