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
<svg width="2958pt" height="479pt"
 viewBox="0.00 0.00 2958.41 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 2954.4108,-475 2954.4108,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1550.4108" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1550.4108" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node9" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1627.4108" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1627.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge39" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1565.9929,-174.3943C1577.0869,-161.8595 1592.1725,-144.8147 1604.6163,-130.7548"/>
<polygon fill="#000000" stroke="#000000" points="1607.5809,-132.6862 1611.5876,-122.8782 1602.339,-128.0468 1607.5809,-132.6862"/>
<text text-anchor="middle" x="1643.9108" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2036.4108" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2036.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node27" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1859.4108" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1859.4108" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2025.3439,-434.9652C2017.674,-423.9102 2006.5065,-410.3272 1993.4108,-402 1969.095,-386.5383 1938.2456,-377.6659 1912.2776,-372.6007"/>
<polygon fill="#000000" stroke="#000000" points="1912.685,-369.1176 1902.2211,-370.7784 1911.4368,-376.0054 1912.685,-369.1176"/>
<text text-anchor="middle" x="2070.4108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_status -->
<g id="node3" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="175.4108" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="175.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2143.4108" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2143.4108" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M188.0206,-87.2873C197.5905,-75.4495 211.8928,-60.8378 228.4108,-54 272.9383,-35.5673 1808.0015,-20.9903 2096.8171,-18.4075"/>
<polygon fill="#000000" stroke="#000000" points="2096.98,-21.9063 2106.9484,-18.3172 2096.9176,-14.9066 2096.98,-21.9063"/>
<text text-anchor="middle" x="284.9108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_other -->
<g id="node4" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="363.4108" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="363.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M397.9972,-262.4521C424.9501,-250.4462 463.674,-235.1143 499.4108,-228 594.4815,-209.0739 1255.155,-196.7734 1477.5455,-193.131"/>
<polygon fill="#000000" stroke="#000000" points="1477.8585,-196.6264 1487.8002,-192.9641 1477.7446,-189.6274 1477.8585,-196.6264"/>
<text text-anchor="middle" x="568.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="323.4108" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="323.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M332.0695,-87.1562C338.8262,-75.4206 349.4161,-60.9853 363.4108,-54 403.3221,-34.0787 1819.3737,-20.8063 2096.604,-18.3957"/>
<polygon fill="#000000" stroke="#000000" points="2096.7588,-21.8946 2106.7281,-18.3081 2096.6982,-14.8948 2096.7588,-21.8946"/>
<text text-anchor="middle" x="411.9108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1638.4108" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1638.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1620.6027,-261.3943C1607.5158,-248.4561 1589.5687,-230.7129 1575.0982,-216.4068"/>
<polygon fill="#000000" stroke="#000000" points="1577.4642,-213.8242 1567.8921,-209.2827 1572.5428,-218.8022 1577.4642,-213.8242"/>
<text text-anchor="middle" x="1658.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="478.4108" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="478.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M468.7739,-86.6459C464.5215,-75.75 462.1359,-62.4549 470.4108,-54 499.6439,-24.1311 1828.7925,-18.8706 2096.6619,-18.1133"/>
<polygon fill="#000000" stroke="#000000" points="2096.8337,-21.6129 2106.824,-18.0853 2096.8144,-14.6129 2096.8337,-21.6129"/>
<text text-anchor="middle" x="532.4108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- medical_history -->
<g id="node8" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1815.4108" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1815.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1788.8357,-261.8746C1770.5271,-250.7659 1745.2848,-236.777 1721.4108,-228 1688.0084,-215.72 1649.3131,-207.1351 1617.1888,-201.4373"/>
<polygon fill="#000000" stroke="#000000" points="1617.4531,-197.9315 1607.0048,-199.6878 1616.2679,-204.8305 1617.4531,-197.9315"/>
<text text-anchor="middle" x="1821.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge3" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1691.2001,-94.2448C1797.2609,-76.3625 2007.2547,-40.9566 2098.8928,-25.5059"/>
<polygon fill="#000000" stroke="#000000" points="2099.6689,-28.9246 2108.9478,-23.8106 2098.505,-22.022 2099.6689,-28.9246"/>
<text text-anchor="middle" x="1978.9108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- generic_file -->
<g id="node10" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="210.4108" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="210.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M206.8325,-434.9114C202.2969,-407.8902 196.7095,-355.7978 211.4108,-315 228.3302,-268.0468 237.6316,-250.0383 282.4108,-228 336.2155,-201.5198 1216.6011,-194.0382 1477.8724,-192.3961"/>
<polygon fill="#000000" stroke="#000000" points="1478.0309,-195.8953 1488.009,-192.3334 1477.9875,-188.8954 1478.0309,-195.8953"/>
<text text-anchor="middle" x="264.4108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M178.4261,-437.198C107.3349,-400.1169 -52.2196,-304.8472 17.4108,-228 89.9392,-147.9545 1791.4038,-39.6671 2096.7183,-20.8453"/>
<polygon fill="#000000" stroke="#000000" points="2097.2192,-24.3212 2106.9854,-20.2137 2096.7893,-17.3344 2097.2192,-24.3212"/>
<text text-anchor="middle" x="70.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M274.0028,-448.2928C406.4641,-438.6043 721.6575,-416.1567 986.4108,-402 1296.0624,-385.4425 1667.8523,-372.3729 1805.091,-367.7787"/>
<polygon fill="#000000" stroke="#000000" points="1805.4566,-371.2685 1815.3343,-367.437 1805.2231,-364.2724 1805.4566,-371.2685"/>
<text text-anchor="middle" x="1039.4108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- exposure -->
<g id="node11" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1971.4108" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1971.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1951.6609,-262.2485C1936.6878,-250.5505 1915.0563,-235.7013 1893.4108,-228 1845.0979,-210.8107 1707.8815,-200.5073 1622.3594,-195.5705"/>
<polygon fill="#000000" stroke="#000000" points="1622.3775,-192.066 1612.1956,-194.9949 1621.9817,-199.0548 1622.3775,-192.066"/>
<text text-anchor="middle" x="1965.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_surgery -->
<g id="node12" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2407.4108" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2407.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2369.7556,-262.2664C2341.1869,-250.4146 2300.6149,-235.3642 2263.4108,-228 2142.5526,-204.0772 1779.4044,-195.5995 1623.1748,-193.0055"/>
<polygon fill="#000000" stroke="#000000" points="1622.7944,-189.499 1612.7389,-192.8359 1622.6806,-196.4981 1622.7944,-189.499"/>
<text text-anchor="middle" x="2393.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- cell_line -->
<g id="node13" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2203.4108" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2203.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2182.5496,-262.6432C2164.2981,-248.4904 2139.87,-229.9868 2134.4108,-228 2087.51,-210.931 1768.4262,-198.8525 1622.7157,-194.1621"/>
<polygon fill="#000000" stroke="#000000" points="1622.6368,-190.6579 1612.5303,-193.8371 1622.4136,-197.6543 1622.6368,-190.6579"/>
<text text-anchor="middle" x="2194.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2246.7822,-270.1505C2263.2204,-266.9855 2282.1351,-263.5697 2299.4108,-261 2335.4566,-255.6382 2437.9845,-270.0445 2462.4108,-243 2490.5625,-211.8306 2490.3246,-84.4638 2461.4108,-54 2443.075,-34.6813 2273.7938,-24.1055 2189.9804,-20.0139"/>
<polygon fill="#000000" stroke="#000000" points="2190.1118,-16.5163 2179.9563,-19.5356 2189.7781,-23.5083 2190.1118,-16.5163"/>
<text text-anchor="middle" x="2522.9108" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2209.4108" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2209.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2195.7356,-86.9735C2186.1676,-74.3612 2173.2532,-57.3377 2162.6487,-43.359"/>
<polygon fill="#000000" stroke="#000000" points="2165.2272,-40.967 2156.3949,-35.1154 2159.6504,-45.1977 2165.2272,-40.967"/>
<text text-anchor="middle" x="2248.9108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cytogenomic_file -->
<g id="node15" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1668.4108" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1668.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1679.7607,-434.8681C1687.6192,-423.7743 1699.0482,-410.1846 1712.4108,-402 1740.5712,-384.7518 1776.512,-375.7624 1805.8064,-371.0799"/>
<polygon fill="#000000" stroke="#000000" points="1806.4847,-374.5179 1815.8674,-369.5968 1805.4638,-367.5927 1806.4847,-374.5179"/>
<text text-anchor="middle" x="1783.9108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2384.4108" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2384.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge41" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2367.8558,-87.4954C2356.2023,-76.2221 2339.6588,-62.1921 2322.4108,-54 2280.1422,-33.9242 2227.1006,-25.0309 2189.7655,-21.0991"/>
<polygon fill="#000000" stroke="#000000" points="2189.9657,-17.6021 2179.6736,-20.1165 2189.2873,-24.5692 2189.9657,-17.6021"/>
<text text-anchor="middle" x="2400.9108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1506.4108" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1506.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1466.2444,-440.6397C1440.8039,-432.4076 1412.0288,-422.1835 1408.4108,-417 1404.5951,-411.5333 1404.1434,-407.1219 1408.4108,-402 1545.5124,-237.4439 1670.6328,-347.0255 1882.4108,-315 1915.824,-309.9472 2010.9742,-322.27 2033.4108,-297 2054.6097,-273.124 2040.6015,-244.7369 2013.4108,-228 1981.0213,-208.0631 1744.8304,-197.9579 1622.8758,-194.0225"/>
<polygon fill="#000000" stroke="#000000" points="1622.9744,-190.5239 1612.8684,-193.7051 1622.7524,-197.5204 1622.9744,-190.5239"/>
<text text-anchor="middle" x="1926.9108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1530.7257,-436.8194C1549.304,-425.2498 1575.9646,-410.3103 1601.4108,-402 1669.3232,-379.821 1751.6614,-371.3061 1804.7631,-368.0371"/>
<polygon fill="#000000" stroke="#000000" points="1805.1977,-371.518 1814.9807,-367.4507 1804.7966,-364.5295 1805.1977,-371.518"/>
<text text-anchor="middle" x="1645.9108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node19" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="132.4108" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="132.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M127.1751,-261.0254C125.1622,-249.9943 125.044,-236.4154 133.4108,-228 157.3246,-203.9473 1191.5275,-194.6199 1477.6977,-192.4967"/>
<polygon fill="#000000" stroke="#000000" points="1477.9871,-195.9947 1487.9611,-192.4212 1477.9356,-188.9949 1477.9871,-195.9947"/>
<text text-anchor="middle" x="172.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1859.4108" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1859.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1859.4108,-434.9735C1859.4108,-423.1918 1859.4108,-407.5607 1859.4108,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="1862.9109,-394.0033 1859.4108,-384.0034 1855.9109,-394.0034 1862.9109,-394.0033"/>
<text text-anchor="middle" x="1925.9108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pdx -->
<g id="node21" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2108.4108" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2108.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2098.5304,-262.0859C2090.6446,-250.3071 2078.4433,-235.428 2063.4108,-228 2024.9418,-208.9914 1754.9595,-198.2306 1622.8643,-194.0496"/>
<polygon fill="#000000" stroke="#000000" points="1622.9319,-190.5501 1612.8275,-193.7362 1622.7134,-197.5467 1622.9319,-190.5501"/>
<text text-anchor="middle" x="2106.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge32" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2129.3825,-267.0454C2134.4812,-264.6372 2140.0213,-262.4139 2145.4108,-261 2177.4966,-252.5828 2420.6731,-267.1525 2443.4108,-243 2550.3853,-129.369 2205.5272,-248.9767 2113.4108,-123 2096.1225,-99.3569 2110.6265,-66.0099 2124.8468,-43.282"/>
<polygon fill="#000000" stroke="#000000" points="2127.8313,-45.1138 2130.4196,-34.84 2121.9894,-41.2573 2127.8313,-45.1138"/>
<text text-anchor="middle" x="2174.4108" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- laboratory_test -->
<g id="node22" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1352.4108" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1352.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1349.8306,-434.9085C1346.7956,-406.4779 1345.1002,-350.8877 1371.4108,-315 1382.4602,-299.9286 1393.8462,-307.343 1409.4108,-297 1447.6832,-271.5672 1449.052,-254.7568 1486.4108,-228 1493.946,-222.6032 1502.363,-217.3682 1510.5534,-212.6384"/>
<polygon fill="#000000" stroke="#000000" points="1512.2983,-215.6727 1519.2994,-207.7206 1508.8674,-209.5711 1512.2983,-215.6727"/>
<text text-anchor="middle" x="1436.9108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1373.0701,-435.3642C1387.9771,-423.724 1409.1451,-409.3172 1430.4108,-402 1498.2428,-378.6599 1705.5536,-370.0812 1805.0337,-367.2497"/>
<polygon fill="#000000" stroke="#000000" points="1805.2794,-370.7443 1815.1792,-366.9702 1805.0866,-363.747 1805.2794,-370.7443"/>
<text text-anchor="middle" x="1495.9108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2246.4108" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2246.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2204.011,-436.2448C2190.2587,-430.4925 2175.0396,-423.7855 2161.4108,-417 2149.4684,-411.0541 2148.0468,-406.2787 2135.4108,-402 2095.413,-388.4564 1981.3826,-376.6258 1913.0512,-370.4821"/>
<polygon fill="#000000" stroke="#000000" points="1913.1757,-366.9794 1902.9053,-369.5814 1912.5566,-373.952 1913.1757,-366.9794"/>
<text text-anchor="middle" x="2252.9108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node24" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2553.4108" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2553.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2552.2499,-434.6583C2550.7079,-424.0379 2547.2197,-411.0274 2539.4108,-402 2463.2413,-313.9446 2393.5131,-365.5588 2299.4108,-297 2266.3275,-272.897 2275.2759,-245.7883 2238.4108,-228 2184.1042,-201.7958 1788.4613,-194.5367 1622.9242,-192.6356"/>
<polygon fill="#000000" stroke="#000000" points="1622.8729,-189.1349 1612.8345,-192.5231 1622.7948,-196.1344 1622.8729,-189.1349"/>
<text text-anchor="middle" x="2450.4108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2561.8747,-434.7683C2569.1274,-417.4595 2578.4108,-390.516 2578.4108,-366 2578.4108,-366 2578.4108,-366 2578.4108,-105 2578.4108,-55.5048 2526.8221,-68.2109 2479.4108,-54 2426.368,-38.1011 2268.8497,-26.0746 2189.779,-20.8546"/>
<polygon fill="#000000" stroke="#000000" points="2189.8259,-17.3504 2179.6196,-20.193 2189.3709,-24.3356 2189.8259,-17.3504"/>
<text text-anchor="middle" x="2664.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2463.404,-442.7704C2432.25,-437.3665 2397.5948,-429.2152 2367.4108,-417 2356.098,-412.4218 2355.9721,-405.9084 2344.4108,-402 2266.0525,-375.5104 2023.5432,-368.481 1914.0481,-366.6407"/>
<polygon fill="#000000" stroke="#000000" points="1913.9317,-363.1385 1903.877,-366.4783 1913.8199,-370.1376 1913.9317,-363.1385"/>
<text text-anchor="middle" x="2453.4108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2669.4108" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2669.4108" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge27" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2649.6932,-87.839C2634.9693,-76.1015 2613.781,-61.3796 2592.4108,-54 2519.0557,-28.6687 2289.5571,-20.9769 2190.123,-18.7992"/>
<polygon fill="#000000" stroke="#000000" points="2190.1389,-15.2988 2180.0676,-18.5881 2189.992,-22.2973 2190.1389,-15.2988"/>
<text text-anchor="middle" x="2672.4108" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node26" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="773.4108" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="773.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M723.4459,-438.0167C596.4298,-399.8733 270.9253,-301.7612 267.4108,-297 257.9087,-284.1271 257.1801,-273.3017 267.4108,-261 318.8579,-199.1383 365.4199,-236.6679 445.4108,-228 646.4208,-206.2184 1264.9435,-195.9063 1477.6635,-192.9375"/>
<polygon fill="#000000" stroke="#000000" points="1477.834,-196.4356 1487.7846,-192.7975 1477.7371,-189.4363 1477.834,-196.4356"/>
<text text-anchor="middle" x="433.4108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge42" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M849.436,-443.8897C944.5019,-432.7474 1112.2923,-413.9046 1256.4108,-402 1458.4573,-385.3104 1699.2034,-373.2985 1804.9923,-368.4165"/>
<polygon fill="#000000" stroke="#000000" points="1805.2761,-371.9073 1815.1051,-367.9526 1804.9552,-364.9146 1805.2761,-371.9073"/>
<text text-anchor="middle" x="1326.4108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1815.0071,-364.9862C1724.3091,-361.8458 1522.9806,-349.0362 1483.4108,-297 1463.0082,-270.1696 1492.2911,-237.0845 1518.318,-215.3087"/>
<polygon fill="#000000" stroke="#000000" points="1520.6404,-217.9323 1526.2321,-208.9332 1516.249,-212.4811 1520.6404,-217.9323"/>
<text text-anchor="middle" x="1519.9108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1903.1506,-362.8804C1950.5819,-358.6631 2028.1247,-349.3234 2092.4108,-330 2118.2409,-322.2359 2145.8019,-309.599 2166.9989,-298.8472"/>
<polygon fill="#000000" stroke="#000000" points="2168.6839,-301.9162 2175.965,-294.2196 2165.4735,-295.6958 2168.6839,-301.9162"/>
<text text-anchor="middle" x="2165.9108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1894.887,-355.1629C1936.3664,-342.2648 2006.9243,-319.6167 2066.4108,-297 2069.4511,-295.8441 2072.5948,-294.5967 2075.7308,-293.3169"/>
<polygon fill="#000000" stroke="#000000" points="2077.1294,-296.5258 2085.0049,-289.4387 2074.4288,-290.0677 2077.1294,-296.5258"/>
<text text-anchor="middle" x="2051.9108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node28" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2765.4108" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2765.4108" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2765.6505,-434.8377C2766.1364,-383.8655 2766.1368,-242.2596 2751.4108,-228 2731.0641,-208.2977 1880.4054,-196.11 1623.2736,-192.871"/>
<polygon fill="#000000" stroke="#000000" points="1622.97,-189.367 1612.9269,-192.7414 1622.8823,-196.3664 1622.97,-189.367"/>
<text text-anchor="middle" x="2806.9108" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2800.1053,-439.5827C2828.9877,-425.8807 2865.4108,-401.5533 2865.4108,-366 2865.4108,-366 2865.4108,-366 2865.4108,-105 2865.4108,-36.7433 2350.209,-21.723 2190.2226,-18.7043"/>
<polygon fill="#000000" stroke="#000000" points="2190.2694,-15.2046 2180.2075,-18.5223 2190.1422,-22.2035 2190.2694,-15.2046"/>
<text text-anchor="middle" x="2907.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2724.8892,-441.4606C2680.6832,-429.3981 2607.6383,-410.9985 2543.4108,-402 2422.2028,-385.0183 2053.6662,-372.0699 1913.9225,-367.6483"/>
<polygon fill="#000000" stroke="#000000" points="1913.9736,-364.1483 1903.8686,-367.3325 1913.7537,-371.1449 1913.9736,-364.1483"/>
<text text-anchor="middle" x="2665.9108" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_radiation -->
<g id="node29" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="573.4108" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="573.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M602.5981,-261.6044C624.1257,-249.7534 654.5658,-234.9922 683.4108,-228 759.4645,-209.5642 1283.2179,-197.3393 1477.8185,-193.3882"/>
<polygon fill="#000000" stroke="#000000" points="1478.0163,-196.885 1487.9437,-193.1841 1477.8751,-189.8865 1478.0163,-196.885"/>
<text text-anchor="middle" x="766.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node30" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="825.4108" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="825.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M837.2253,-260.9776C845.9687,-249.3219 859.0039,-235.0529 874.4108,-228 928.0993,-203.4228 1314.0748,-195.2476 1477.5548,-192.8684"/>
<polygon fill="#000000" stroke="#000000" points="1478.0461,-196.3619 1487.9953,-192.72 1477.9465,-189.3626 1478.0461,-196.3619"/>
<text text-anchor="middle" x="976.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- family_relationship -->
<g id="node31" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1072.4108" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1072.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1075.7122,-260.8974C1078.7907,-249.5188 1084.6067,-235.6002 1095.4108,-228 1125.875,-206.5698 1357.0269,-197.1994 1477.642,-193.734"/>
<polygon fill="#000000" stroke="#000000" points="1478.0011,-197.2254 1487.8989,-193.4459 1477.8045,-190.2281 1478.0011,-197.2254"/>
<text text-anchor="middle" x="1174.9108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_response -->
<g id="node32" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1295.4108" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1295.4108" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1272.2106,-261.0899C1261.7271,-250.8699 1253.4771,-238.1199 1262.4108,-228 1276.5419,-211.9925 1398.217,-201.4004 1478.8289,-196.0701"/>
<polygon fill="#000000" stroke="#000000" points="1479.1826,-199.5546 1488.9353,-195.415 1478.7298,-192.5692 1479.1826,-199.5546"/>
<text text-anchor="middle" x="1345.4108" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
</g>
</svg>
</div>
