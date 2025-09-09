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
<svg width="2992pt" height="392pt"
 viewBox="0.00 0.00 2992.04 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2988.0444,-388 2988.0444,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="176" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="176" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1374" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1374" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M171.6356,-347.8766C167.2241,-324.6888 163.7424,-284.6978 185,-261 235.8108,-204.3565 277.4056,-236.7014 353,-228 536.9086,-206.8309 1099.7546,-196.2486 1301.2772,-193.0632"/>
<polygon fill="#000000" stroke="#000000" points="1301.5133,-196.56 1311.4573,-192.9037 1301.4036,-189.5608 1301.5133,-196.56"/>
<text text-anchor="middle" x="227.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2169" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2169" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M226.8965,-361.667C271.6804,-357.8991 338.6511,-352.3734 397,-348 611.1231,-331.9508 664.4608,-323.8999 879,-315 1016.2299,-309.3072 1979.5894,-319.9872 2115,-297 2118.9428,-296.3307 2122.9884,-295.4232 2127.0059,-294.3695"/>
<polygon fill="#000000" stroke="#000000" points="2128.2361,-297.6567 2136.8596,-291.5016 2126.2799,-290.9356 2128.2361,-297.6567"/>
<text text-anchor="middle" x="921.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node21" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1653" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1653" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M135.1797,-354.6093C83.1875,-338.8678 0,-308.9947 0,-279 0,-279 0,-279 0,-105 0,-77.4857 44.1173,-64.5929 89,-54 164.5723,-36.1639 1353.4857,-21.463 1606.0623,-18.5318"/>
<polygon fill="#000000" stroke="#000000" points="1606.4015,-22.0283 1616.3604,-18.4129 1606.3206,-15.0287 1606.4015,-22.0283"/>
<text text-anchor="middle" x="42.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1085" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1085" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1030.6014,-363.9792C938.027,-360.0173 757.795,-349.8341 737,-330 714.7506,-308.7786 711.8978,-284.2655 732,-261 768.7318,-218.4879 1141.6372,-200.2443 1301.676,-194.3303"/>
<polygon fill="#000000" stroke="#000000" points="1302.0377,-197.8195 1311.9039,-193.9584 1301.7833,-190.8241 1302.0377,-197.8195"/>
<text text-anchor="middle" x="776.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1135.8687,-359.4358C1224.0771,-348.3256 1411.2062,-325.9571 1570,-315 1690.8897,-306.6584 1995.7243,-318.3822 2115,-297 2118.9364,-296.2943 2122.9777,-295.362 2126.9924,-294.2922"/>
<polygon fill="#000000" stroke="#000000" points="2128.2327,-297.5758 2136.842,-291.4008 2126.2611,-290.8592 2128.2327,-297.5758"/>
<text text-anchor="middle" x="1614.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="105" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="105" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M95.8609,-86.6339C91.874,-75.7334 89.7553,-62.4378 98,-54 125.0343,-26.3326 1350.1028,-19.3502 1606.3244,-18.1914"/>
<polygon fill="#000000" stroke="#000000" points="1606.4306,-21.691 1616.4149,-18.1465 1606.3994,-14.6911 1606.4306,-21.691"/>
<text text-anchor="middle" x="160" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="935" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="935" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M945.7788,-260.9293C953.6998,-249.4101 965.5731,-235.3187 980,-228 1007.9368,-213.8278 1196.1302,-201.5731 1301.9966,-195.6997"/>
<polygon fill="#000000" stroke="#000000" points="1302.4968,-199.1776 1312.2897,-195.1343 1302.1128,-192.1881 1302.4968,-199.1776"/>
<text text-anchor="middle" x="1063" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1115" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1115" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1129.9846,-261.6042C1140.7803,-250.2282 1156.3322,-236.036 1173,-228 1196.0305,-216.8964 1256.9185,-206.8766 1305.6919,-200.2442"/>
<polygon fill="#000000" stroke="#000000" points="1306.4491,-203.6742 1315.8978,-198.8811 1305.5224,-196.7358 1306.4491,-203.6742"/>
<text text-anchor="middle" x="1220" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- consent_group -->
<g id="node16" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1667" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1667" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1417.5487,-179.0692C1468.3792,-163.9761 1552.6449,-138.9553 1608.9875,-122.2256"/>
<polygon fill="#000000" stroke="#000000" points="1610.2308,-125.5075 1618.8209,-119.3057 1608.2383,-118.7971 1610.2308,-125.5075"/>
<text text-anchor="middle" x="1588.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node7" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2134" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2134" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2131.244,-210.1076C2130.4678,-220.1559 2130.7761,-232.672 2135,-243 2136.7309,-247.2322 2139.2101,-251.2597 2142.0521,-254.985"/>
<polygon fill="#000000" stroke="#000000" points="2139.4955,-257.3787 2148.7033,-262.6195 2144.7735,-252.7804 2139.4955,-257.3787"/>
<text text-anchor="middle" x="2159" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge2" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2106.045,-189.6969C2034.8167,-183.2918 1848.9664,-163.0459 1804,-123 1779.8598,-101.5014 1804.3949,-76.3073 1781,-54 1768.9021,-42.4644 1729.5263,-32.4591 1697.6083,-25.9446"/>
<polygon fill="#000000" stroke="#000000" points="1698.0406,-22.4624 1687.5514,-23.9546 1696.6818,-29.3292 1698.0406,-22.4624"/>
<text text-anchor="middle" x="1828" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node8" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1345" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1345" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1356.7334,-86.8877C1365.1299,-75.5049 1377.4875,-61.5854 1392,-54 1428.2883,-35.0327 1541.4723,-24.9878 1606.25,-20.6621"/>
<polygon fill="#000000" stroke="#000000" points="1606.8439,-24.1311 1616.5969,-19.9923 1606.3917,-17.1457 1606.8439,-24.1311"/>
<text text-anchor="middle" x="1461.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2134.7786,-267.3934C2128.2262,-265.2277 2121.411,-263.0137 2115,-261 2088.0322,-252.5293 2080.8761,-251.757 2054,-243 2035.1537,-236.8593 2031.4275,-231.932 2012,-228 1905.7467,-206.4951 1589.8952,-196.8436 1446.3917,-193.4805"/>
<polygon fill="#000000" stroke="#000000" points="1446.4407,-189.9808 1436.3626,-193.2492 1446.2792,-196.979 1446.4407,-189.9808"/>
<text text-anchor="middle" x="2090.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2179.9808,-261.3643C2184.8077,-251.2358 2188.3077,-238.4858 2183,-228 2178.991,-220.0799 2172.3284,-213.4785 2165.1882,-208.1841"/>
<polygon fill="#000000" stroke="#000000" points="2166.986,-205.1767 2156.7172,-202.5686 2163.1183,-211.0112 2166.986,-205.1767"/>
<text text-anchor="middle" x="2221.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node19" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2500" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2500" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2212.6815,-276.1381C2278.4413,-271.3334 2399.3931,-260.4243 2439,-243 2453.2345,-236.7378 2466.7538,-226.1107 2477.4308,-216.173"/>
<polygon fill="#000000" stroke="#000000" points="2479.9434,-218.6118 2484.6726,-209.131 2475.0633,-213.5933 2479.9434,-218.6118"/>
<text text-anchor="middle" x="2499.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- radiology_file -->
<g id="node10" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2033" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2033" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1982.9092,-265.7337C1931.5282,-252.3036 1855.0068,-232.8441 1825,-228 1692.4676,-206.605 1535.8765,-197.7316 1446.4248,-194.1966"/>
<polygon fill="#000000" stroke="#000000" points="1446.5139,-190.6976 1436.3869,-193.8113 1446.2453,-197.6924 1446.5139,-190.6976"/>
<text text-anchor="middle" x="1949" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1510" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1510" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1520.9273,-86.7975C1528.2462,-75.9586 1538.7645,-62.6702 1551,-54 1568.3534,-41.7032 1590.3165,-33.2407 1609.4139,-27.6266"/>
<polygon fill="#000000" stroke="#000000" points="1610.3961,-30.9864 1619.0998,-24.9452 1608.5284,-24.2401 1610.3961,-30.9864"/>
<text text-anchor="middle" x="1599.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="515" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="515" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M514.2327,-347.7136C514.3177,-323.9668 518.3515,-282.9658 543,-261 599.0145,-211.082 1109.2671,-196.7625 1301.3333,-193.1213"/>
<polygon fill="#000000" stroke="#000000" points="1301.6733,-196.6157 1311.6067,-192.9311 1301.5436,-189.6169 1301.6733,-196.6157"/>
<text text-anchor="middle" x="629" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M610.6926,-357.4887C746.1947,-345.7988 1001.7988,-325.0797 1220,-315 1319.3586,-310.4102 2016.9849,-313.9188 2115,-297 2118.9409,-296.3197 2122.9853,-295.4048 2127.0019,-294.3462"/>
<polygon fill="#000000" stroke="#000000" points="2128.2352,-297.6324 2136.8544,-291.4713 2126.2743,-290.9126 2128.2352,-297.6324"/>
<text text-anchor="middle" x="1306" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M412.5975,-359.831C321.0699,-351.9255 196.7797,-334.4608 166,-297 155.8425,-284.6377 155.7163,-273.2574 166,-261 261.8276,-146.781 1366.3328,-43.2753 1606.919,-21.9896"/>
<polygon fill="#000000" stroke="#000000" points="1607.4157,-25.4595 1617.0699,-21.0951 1606.8012,-18.4865 1607.4157,-25.4595"/>
<text text-anchor="middle" x="505" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1976" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1976" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1990.2328,-348.2541C2000.1973,-337.0261 2014.4667,-323.1413 2030,-315 2064.2025,-297.0737 2077.7346,-307.1218 2115,-297 2118.5464,-296.0367 2122.202,-294.9735 2125.8602,-293.8597"/>
<polygon fill="#000000" stroke="#000000" points="2126.9922,-297.1727 2135.4765,-290.827 2124.8868,-290.4968 2126.9922,-297.1727"/>
<text text-anchor="middle" x="2096.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="379" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="379" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M364.3637,-260.9721C357.4477,-250.1988 352.3931,-236.9182 361,-228 377.3139,-211.096 1071.5856,-197.3388 1301.1576,-193.2448"/>
<polygon fill="#000000" stroke="#000000" points="1301.473,-196.7398 1311.4093,-193.0629 1301.3488,-189.7409 1301.473,-196.7398"/>
<text text-anchor="middle" x="440.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- laboratory_test -->
<g id="node15" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1793" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1793" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1731.0645,-354.1152C1706.4591,-348.0238 1682.2647,-339.8117 1675,-330 1671.0329,-324.6421 1670.7238,-320.1146 1675,-315 1703.9658,-280.3548 1746.0342,-331.6452 1775,-297 1785.2628,-284.725 1784.9414,-273.5367 1775,-261 1754.5963,-235.2696 1552.2729,-210.5145 1443.0684,-198.8928"/>
<polygon fill="#000000" stroke="#000000" points="1443.4335,-195.412 1433.1214,-197.8432 1442.6988,-202.3734 1443.4335,-195.412"/>
<text text-anchor="middle" x="1847.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1814.5081,-348.5632C1830.2563,-336.8554 1852.6885,-322.2858 1875,-315 1976.6822,-281.7958 2010.1301,-318.0732 2115,-297 2118.8678,-296.2228 2122.8425,-295.2502 2126.7967,-294.1622"/>
<polygon fill="#000000" stroke="#000000" points="2127.9283,-297.4771 2136.5109,-291.2651 2125.9277,-290.769 2127.9283,-297.4771"/>
<text text-anchor="middle" x="1940.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge30" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1659.2004,-87.0075C1657.1049,-81.3513 1655.113,-75.0113 1654,-69 1652.6412,-61.6609 1652.0687,-53.6264 1651.9121,-46.1499"/>
<polygon fill="#000000" stroke="#000000" points="1655.4121,-46.0884 1651.9289,-36.0825 1648.4121,-46.0766 1655.4121,-46.0884"/>
<text text-anchor="middle" x="1717.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- cytogenomic_file -->
<g id="node17" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2167" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2167" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2167.3248,-347.5864C2167.505,-337.8901 2167.7441,-325.8011 2168,-315 2168.0575,-312.574 2168.1205,-310.0561 2168.1861,-307.5299"/>
<polygon fill="#000000" stroke="#000000" points="2171.6907,-307.4044 2168.4624,-297.3134 2164.6932,-307.2151 2171.6907,-307.4044"/>
<text text-anchor="middle" x="2239.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1931" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1931" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1897.3978,-89.1406C1873.2126,-78.1761 1839.5939,-63.8465 1809,-54 1772.0356,-42.1031 1728.9562,-32.4697 1697.4449,-26.1723"/>
<polygon fill="#000000" stroke="#000000" points="1697.7145,-22.6585 1687.2274,-24.1661 1696.3657,-29.5273 1697.7145,-22.6585"/>
<text text-anchor="middle" x="1905.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2459.7219,-202.5867C2398.3536,-218.7167 2281.6927,-249.3799 2216.3557,-266.553"/>
<polygon fill="#000000" stroke="#000000" points="2215.1082,-263.262 2206.3265,-269.1891 2216.8877,-270.032 2215.1082,-263.262"/>
<text text-anchor="middle" x="2394.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2462.2023,-180.299C2375.403,-153.8566 2154.7565,-89.0706 1966,-54 1872.2054,-36.5731 1760.9327,-26.1822 1699.5325,-21.3289"/>
<polygon fill="#000000" stroke="#000000" points="1699.6308,-17.8261 1689.39,-20.5419 1699.0892,-24.8051 1699.6308,-17.8261"/>
<text text-anchor="middle" x="2298.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- generic_file -->
<g id="node20" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2805" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2805" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2804.722,-347.9003C2803.5512,-336.8192 2800.1441,-323.2318 2791,-315 2779.9323,-305.0365 2276.8148,-229.5128 2262,-228 2104.4797,-211.9151 1628.7481,-198.4818 1446.3003,-193.7874"/>
<polygon fill="#000000" stroke="#000000" points="1446.3575,-190.2878 1436.2712,-193.5305 1446.1782,-197.2855 1446.3575,-190.2878"/>
<text text-anchor="middle" x="2755" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2754.7819,-354.3804C2732.826,-348.4317 2707.0953,-340.2588 2685,-330 2673.9309,-324.8606 2673.5636,-318.9014 2662,-315 2582.1432,-288.0571 2334.6156,-281.2659 2223.7141,-279.5641"/>
<polygon fill="#000000" stroke="#000000" points="2223.4681,-276.0603 2213.4184,-279.4148 2223.3666,-283.0595 2223.4681,-276.0603"/>
<text text-anchor="middle" x="2738" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge33" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2813.3246,-348.1C2820.5972,-330.8051 2830,-303.6732 2830,-279 2830,-279 2830,-279 2830,-105 2830,-47.2931 1918.288,-23.7731 1699.6912,-18.9632"/>
<polygon fill="#000000" stroke="#000000" points="1699.5897,-15.4603 1689.5159,-18.7419 1699.4374,-22.4586 1699.5897,-15.4603"/>
<text text-anchor="middle" x="2883" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- methylation_array_file -->
<g id="node22" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2390" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2390" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2362.6331,-348.4577C2353.517,-342.6008 2343.3136,-336.0306 2334,-330 2323.756,-323.3669 2322.1775,-319.8993 2311,-315 2282.0598,-302.315 2247.764,-293.4633 2220.1274,-287.7119"/>
<polygon fill="#000000" stroke="#000000" points="2220.7625,-284.2696 2210.2691,-285.7319 2219.3841,-291.1326 2220.7625,-284.2696"/>
<text text-anchor="middle" x="2425.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- survival -->
<g id="node23" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1239" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1239" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1253.2417,-261.7009C1262.7838,-250.9392 1276.1058,-237.4068 1290,-228 1300.4706,-220.9111 1312.5627,-214.7469 1324.2521,-209.6188"/>
<polygon fill="#000000" stroke="#000000" points="1325.6395,-212.8323 1333.5017,-205.7304 1322.9268,-206.3794 1325.6395,-212.8323"/>
<text text-anchor="middle" x="1329.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pathology_file -->
<g id="node24" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2600" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2600" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2571.4823,-349.1859C2561.4776,-343.2089 2550.1947,-336.3797 2540,-330 2529.6546,-323.5261 2528.5034,-319.0755 2517,-315 2464.2386,-296.3072 2307.062,-285.87 2223.1713,-281.4905"/>
<polygon fill="#000000" stroke="#000000" points="2223.2353,-277.9893 2213.0696,-280.9739 2222.8778,-284.9801 2223.2353,-277.9893"/>
<text text-anchor="middle" x="2601" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1390" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1390" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1380.8396,-260.7422C1378.4797,-255.1833 1376.2536,-248.9634 1375,-243 1373.4645,-235.6958 1372.8317,-227.6732 1372.6736,-220.197"/>
<polygon fill="#000000" stroke="#000000" points="1376.1738,-220.1401 1372.7216,-210.1235 1369.1739,-220.1067 1376.1738,-220.1401"/>
<text text-anchor="middle" x="1443" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- publication -->
<g id="node26" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2921" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2921" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge9" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2901.7008,-87.7682C2887.0178,-75.8315 2865.7001,-60.8939 2844,-54 2788.6527,-36.4166 1913.7984,-21.978 1699.9073,-18.699"/>
<polygon fill="#000000" stroke="#000000" points="1699.6991,-15.1955 1689.6469,-18.5425 1699.5923,-22.1947 1699.6991,-15.1955"/>
<text text-anchor="middle" x="2924" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- exposure -->
<g id="node27" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1546" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1546" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1537.7479,-260.9335C1531.8064,-249.8658 1522.7685,-236.2806 1511,-228 1498.6222,-219.2907 1466.4763,-210.6341 1436.4329,-203.9929"/>
<polygon fill="#000000" stroke="#000000" points="1436.8695,-200.5067 1426.3565,-201.8208 1435.3944,-207.3495 1436.8695,-200.5067"/>
<text text-anchor="middle" x="1568.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- genetic_analysis -->
<g id="node28" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1605" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1605" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1613.9894,-347.6184C1626.8904,-318.2767 1645.9899,-260.827 1616,-228 1604.4526,-215.3601 1511.4671,-204.3625 1444.1997,-197.9519"/>
<polygon fill="#000000" stroke="#000000" points="1444.3411,-194.4499 1434.0581,-197.0013 1443.6878,-201.4194 1444.3411,-194.4499"/>
<text text-anchor="middle" x="1701" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1629.5908,-348.6014C1647.8172,-336.7489 1673.7707,-321.9872 1699,-315 1788.1743,-290.3035 2024.0057,-313.793 2115,-297 2118.9328,-296.2742 2122.9716,-295.3281 2126.9846,-294.2494"/>
<polygon fill="#000000" stroke="#000000" points="2128.2305,-297.5311 2136.8319,-291.3451 2126.2502,-290.817 2128.2305,-297.5311"/>
<text text-anchor="middle" x="1769" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
</g>
</svg>
</div>
