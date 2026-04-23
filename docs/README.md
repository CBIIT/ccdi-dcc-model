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
<svg width="3296pt" height="479pt"
 viewBox="0.00 0.00 3296.44 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3292.4354,-475 3292.4354,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1255.3431" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1255.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1234.3431" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1234.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge44" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1243.1338,-435.0569C1239.9874,-429.5068 1237.0182,-423.2129 1235.3431,-417 1233.4002,-409.7935 1232.6281,-401.8043 1232.4667,-394.3289"/>
<polygon fill="#000000" stroke="#000000" points="1235.9674,-394.279 1232.5865,-384.2382 1228.9679,-394.1959 1235.9674,-394.279"/>
<text text-anchor="middle" x="1296.3431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="671.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="671.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge43" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.1223,-86.6311C70.2356,-75.7295 70.2485,-62.4337 78.3431,-54 97.1805,-34.3735 487.823,-22.6437 624.5673,-19.1266"/>
<polygon fill="#000000" stroke="#000000" points="624.8189,-22.6214 634.7267,-18.8684 624.641,-15.6237 624.8189,-22.6214"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1183.3431" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1183.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1162.3987,-266.9385C1157.2989,-264.5346 1151.7514,-262.3401 1146.3431,-261 1116.9381,-253.7138 622.4079,-264.772 601.3431,-243 546.7139,-186.5367 613.4428,-88.1647 650.1921,-42.5385"/>
<polygon fill="#000000" stroke="#000000" points="653.0253,-44.6035 656.6691,-34.655 647.6166,-40.1598 653.0253,-44.6035"/>
<text text-anchor="middle" x="614.3431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1508.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1508.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1188.8849,-260.948C1193.3488,-249.5906 1200.8127,-235.6769 1212.3431,-228 1230.7062,-215.7741 1355.8512,-203.8684 1437.4335,-197.2771"/>
<polygon fill="#000000" stroke="#000000" points="1437.961,-200.7462 1447.6505,-196.4609 1437.4035,-193.7684 1437.961,-200.7462"/>
<text text-anchor="middle" x="1236.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="314.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="314.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M305.9232,-86.8342C302.2852,-76.009 300.4431,-62.7223 308.3431,-54 329.2162,-30.9545 531.6912,-22.0811 624.8559,-19.1982"/>
<polygon fill="#000000" stroke="#000000" points="624.9665,-22.6966 634.8572,-18.8988 624.7569,-15.6997 624.9665,-22.6966"/>
<text text-anchor="middle" x="364.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2286.3431" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2286.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2195.3067,-443.096C2132.366,-436.1261 2046.7194,-426.3992 1971.3431,-417 1921.944,-410.8401 1909.8962,-406.7659 1860.3431,-402 1649.3457,-381.7067 1397.1582,-371.4568 1288.5116,-367.7125"/>
<polygon fill="#000000" stroke="#000000" points="1288.565,-364.2124 1278.4518,-367.3703 1288.327,-371.2083 1288.565,-364.2124"/>
<text text-anchor="middle" x="2057.3431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge38" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2382.5396,-444.6374C2519.2477,-431.4343 2753.3431,-403.3698 2753.3431,-366 2753.3431,-366 2753.3431,-366 2753.3431,-105 2753.3431,-52.2916 1027.0055,-23.4366 718.2991,-18.698"/>
<polygon fill="#000000" stroke="#000000" points="717.973,-15.1927 707.9207,-18.5396 717.8661,-22.1919 717.973,-15.1927"/>
<text text-anchor="middle" x="2839.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2287.0194,-434.7957C2287.5591,-389.6372 2281.7208,-272.8839 2210.3431,-228 2184.0236,-211.4497 1754.6443,-198.4336 1580.6819,-193.8147"/>
<polygon fill="#000000" stroke="#000000" points="1580.6838,-190.3137 1570.595,-193.5487 1580.4992,-197.3112 1580.6838,-190.3137"/>
<text text-anchor="middle" x="2360.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2119.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2119.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2088.4677,-261.6376C2066.1149,-249.9648 2034.7804,-235.4065 2005.3431,-228 1926.9819,-208.2842 1698.3425,-198.1729 1580.4688,-194.1473"/>
<polygon fill="#000000" stroke="#000000" points="1580.5629,-190.6486 1570.451,-193.8107 1580.3278,-197.6446 1580.5629,-190.6486"/>
<text text-anchor="middle" x="2126.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_other -->
<g id="node7" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2362.3431" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2362.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2335.7241,-261.6445C2316.0451,-249.8129 2288.1258,-235.0585 2261.3431,-228 2196.78,-210.9847 1756.7007,-198.2217 1580.7827,-193.7431"/>
<polygon fill="#000000" stroke="#000000" points="1580.6745,-190.2394 1570.5892,-193.4854 1580.4975,-197.2372 1580.6745,-190.2394"/>
<text text-anchor="middle" x="2367.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1196.1703,-356.6287C1182.4423,-351.2176 1168.3747,-342.8388 1160.3431,-330 1155.0889,-321.6009 1157.6729,-311.7984 1162.6833,-303.0443"/>
<polygon fill="#000000" stroke="#000000" points="1165.6024,-304.9756 1168.3019,-294.7305 1159.8026,-301.056 1165.6024,-304.9756"/>
<text text-anchor="middle" x="1196.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="393.3431" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="393.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1190.1632,-365.3904C1070.2109,-363.032 728.8377,-351.6372 451.3431,-297 447.27,-296.198 443.0776,-295.2169 438.8992,-294.1307"/>
<polygon fill="#000000" stroke="#000000" points="439.8097,-290.7512 429.2373,-291.4406 437.932,-297.4947 439.8097,-290.7512"/>
<text text-anchor="middle" x="679.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1235.8836,-347.8457C1238.5086,-321.2061 1244.7279,-273.3429 1256.3431,-261 1281.6979,-234.0569 1377.0615,-213.4341 1442.9182,-202.0167"/>
<polygon fill="#000000" stroke="#000000" points="1443.5432,-205.4608 1452.8136,-200.3316 1442.3679,-198.5601 1443.5432,-205.4608"/>
<text text-anchor="middle" x="1292.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="638.3431" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="638.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M663.9724,-435.5747C682.6208,-423.8723 708.9513,-409.3044 734.3431,-402 816.6661,-378.3183 1068.0344,-369.7704 1179.791,-367.0847"/>
<polygon fill="#000000" stroke="#000000" points="1179.9245,-370.5826 1189.84,-366.85 1179.761,-363.5845 1179.9245,-370.5826"/>
<text text-anchor="middle" x="805.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node11" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2596.3431" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2596.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2555.0597,-261.9094C2524.2931,-250.043 2480.9331,-235.1314 2441.3431,-228 2357.7045,-212.934 1785.0029,-198.3936 1580.6241,-193.6277"/>
<polygon fill="#000000" stroke="#000000" points="1580.6709,-190.128 1570.5923,-193.3948 1580.5083,-197.1261 1580.6709,-190.128"/>
<text text-anchor="middle" x="2599.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- publication -->
<g id="node12" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="518.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="518.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge41" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M507.3236,-87.2768C502.238,-76.6183 498.8122,-63.3512 506.3431,-54 521.0275,-35.7664 581.6006,-26.2723 625.0956,-21.7096"/>
<polygon fill="#000000" stroke="#000000" points="625.5902,-25.1778 635.1947,-20.7054 624.8975,-18.2122 625.5902,-25.1778"/>
<text text-anchor="middle" x="557.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="508.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="508.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M535.7577,-264.0888C559.6878,-251.9036 595.7492,-235.5092 629.3431,-228 706.9072,-210.6623 1239.4565,-197.7187 1435.826,-193.4858"/>
<polygon fill="#000000" stroke="#000000" points="1436.1166,-196.9805 1446.0393,-193.267 1435.9666,-189.9821 1436.1166,-196.9805"/>
<text text-anchor="middle" x="668.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M394.0841,-261.0019C396.4201,-224.6541 406.1157,-141.3327 446.3431,-87 462.6308,-65.0012 472.978,-64.2881 498.3431,-54 539.6131,-37.2609 589.7084,-27.9299 625.3489,-22.9878"/>
<polygon fill="#000000" stroke="#000000" points="626.0041,-26.4317 635.4584,-21.6497 625.0856,-19.4922 626.0041,-26.4317"/>
<text text-anchor="middle" x="458.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M418.6114,-263.2972C439.6212,-251.16 470.7615,-235.2467 500.3431,-228 590.2371,-205.9785 1219.109,-195.7772 1435.4424,-192.8917"/>
<polygon fill="#000000" stroke="#000000" points="1435.7822,-196.3876 1445.7351,-192.7558 1435.6897,-189.3882 1435.7822,-196.3876"/>
<text text-anchor="middle" x="540.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- consent_group -->
<g id="node20" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1075.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1075.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge31" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1456.972,-181.6783C1379.397,-166.0917 1232.1834,-136.5129 1145.0169,-118.9991"/>
<polygon fill="#000000" stroke="#000000" points="1145.4471,-115.5157 1134.9535,-116.9771 1144.0681,-122.3785 1145.4471,-115.5157"/>
<text text-anchor="middle" x="1367.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_radiation -->
<g id="node16" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="679.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="679.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M693.3821,-260.9077C703.6141,-249.2207 718.5772,-234.9431 735.3431,-228 798.887,-201.6851 1255.3714,-194.4345 1435.5108,-192.5865"/>
<polygon fill="#000000" stroke="#000000" points="1435.7199,-196.0847 1445.6844,-192.4849 1435.6499,-189.085 1435.7199,-196.0847"/>
<text text-anchor="middle" x="818.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- radiology_file -->
<g id="node17" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="875.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="875.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M887.9376,-261.2579C897.335,-249.5689 911.2854,-235.1476 927.3431,-228 972.6788,-207.8203 1290.4504,-197.4144 1435.9288,-193.6635"/>
<polygon fill="#000000" stroke="#000000" points="1436.1917,-197.158 1446.0994,-193.4048 1436.0136,-190.1603 1436.1917,-197.158"/>
<text text-anchor="middle" x="986.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_status -->
<g id="node18" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="707.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="707.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M699.8839,-86.9735C694.879,-74.8784 688.1954,-58.7263 682.5542,-45.0934"/>
<polygon fill="#000000" stroke="#000000" points="685.7273,-43.6076 678.6696,-35.7057 679.2591,-46.2841 685.7273,-43.6076"/>
<text text-anchor="middle" x="747.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- synonym -->
<g id="node19" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="316.3431" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="316.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M360.7871,-443.6237C417.9964,-431.9333 520.6076,-412.244 609.3431,-402 819.3189,-377.7595 1070.9588,-369.573 1179.7825,-367.0382"/>
<polygon fill="#000000" stroke="#000000" points="1179.9436,-370.5355 1189.8618,-366.8102 1179.7852,-363.5373 1179.9436,-370.5355"/>
<text text-anchor="middle" x="651.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M281.6486,-439.5827C252.7662,-425.8807 216.3431,-401.5533 216.3431,-366 216.3431,-366 216.3431,-366 216.3431,-105 216.3431,-80.9802 261.3982,-65.1694 299.3431,-54 359.1701,-36.3895 538.9045,-24.9277 624.7335,-20.3103"/>
<polygon fill="#000000" stroke="#000000" points="625.1666,-23.7923 634.9675,-19.7683 624.7963,-16.8021 625.1666,-23.7923"/>
<text text-anchor="middle" x="258.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M312.052,-434.8461C304.3768,-397.471 292.8084,-311.2301 335.3431,-261 371.6423,-218.1336 401.7964,-236.3499 457.3431,-228 646.4302,-199.576 1229.7129,-193.5648 1435.5249,-192.3185"/>
<polygon fill="#000000" stroke="#000000" points="1435.6426,-195.818 1445.6219,-192.2594 1435.6016,-188.8181 1435.6426,-195.818"/>
<text text-anchor="middle" x="352.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge42" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1017.4598,-92.535C935.5658,-74.8994 787.7304,-43.0636 714.6488,-27.3257"/>
<polygon fill="#000000" stroke="#000000" points="715.3602,-23.8988 704.8475,-25.215 713.8865,-30.7419 715.3602,-23.8988"/>
<text text-anchor="middle" x="960.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- methylation_array_file -->
<g id="node21" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="861.3431" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="861.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M869.625,-434.8023C875.8317,-423.3834 885.4695,-409.4559 898.3431,-402 922.1497,-388.2123 1091.4551,-375.3023 1180.2621,-369.3859"/>
<polygon fill="#000000" stroke="#000000" points="1180.6701,-372.8667 1190.4182,-368.7164 1180.2096,-365.8819 1180.6701,-372.8667"/>
<text text-anchor="middle" x="989.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1078.3431" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1078.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1080.1074,-434.6135C1082.1009,-423.7053 1086.3393,-410.4087 1095.3431,-402 1108.1526,-390.0372 1148.8293,-380.3545 1182.8937,-374.0565"/>
<polygon fill="#000000" stroke="#000000" points="1183.5282,-377.4987 1192.755,-372.2915 1182.2948,-370.6082 1183.5282,-377.4987"/>
<text text-anchor="middle" x="1161.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node23" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1428.3431" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1428.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1406.0119,-436.3827C1387.2213,-422.497 1362.5948,-404.5616 1357.3431,-402 1334.2616,-390.7414 1306.9905,-382.3171 1283.9994,-376.4598"/>
<polygon fill="#000000" stroke="#000000" points="1284.6476,-373.015 1274.1012,-374.0273 1282.9769,-379.8128 1284.6476,-373.015"/>
<text text-anchor="middle" x="1422.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1479.6188,-446.6911C1509.7947,-443.0668 1548.7128,-438.5455 1583.3431,-435 1605.8694,-432.6937 1769.8771,-432.5443 1786.3431,-417 1819.6626,-385.5457 1769.6178,-348.0615 1801.3431,-315 1831.0969,-283.9931 1868.0226,-329.3213 1896.3431,-297 1916.5723,-273.9131 1920.0293,-250.6783 1899.3431,-228 1878.3426,-204.9771 1687.8643,-196.4768 1580.7258,-193.4989"/>
<polygon fill="#000000" stroke="#000000" points="1580.7167,-189.9975 1570.6263,-193.2276 1580.5287,-196.9949 1580.7167,-189.9975"/>
<text text-anchor="middle" x="1845.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- generic_file -->
<g id="node24" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2791.3431" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2791.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2728.8445,-447.2666C2613.3189,-436.8503 2358.5068,-414.7229 2143.3431,-402 1819.5695,-382.8548 1430.3017,-371.2595 1288.9689,-367.4212"/>
<polygon fill="#000000" stroke="#000000" points="1288.9199,-363.9187 1278.8291,-367.1477 1288.731,-370.9162 1288.9199,-363.9187"/>
<text text-anchor="middle" x="2409.3431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2849.8041,-444.6464C2894.4415,-434.5783 2948.3431,-412.7432 2948.3431,-366 2948.3431,-366 2948.3431,-366 2948.3431,-105 2948.3431,-47.0922 1042.5224,-22.3227 718.0383,-18.5252"/>
<polygon fill="#000000" stroke="#000000" points="718.0717,-15.0254 708.0316,-18.4088 717.9902,-22.0249 718.0717,-15.0254"/>
<text text-anchor="middle" x="3001.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2791.7026,-434.8023C2791.4766,-388.0241 2783.2863,-264.6889 2705.3431,-228 2654.4075,-204.0239 1832.5949,-194.8472 1580.9791,-192.5914"/>
<polygon fill="#000000" stroke="#000000" points="1580.8788,-189.0905 1570.8481,-192.5016 1580.8167,-196.0902 1580.8788,-189.0905"/>
<text text-anchor="middle" x="2830.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_arm -->
<g id="node25" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3036.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3036.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3017.9435,-87.6825C3003.906,-75.7032 2983.4459,-60.7499 2962.3431,-54 2906.9392,-36.2787 1039.1828,-20.8796 718.0996,-18.3603"/>
<polygon fill="#000000" stroke="#000000" points="717.7896,-14.8578 707.7625,-18.2794 717.7348,-21.8576 717.7896,-14.8578"/>
<text text-anchor="middle" x="3038.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- laboratory_test -->
<g id="node26" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1914.3431" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1914.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1854.6249,-440.6099C1797.7117,-429.1798 1709.502,-412.4458 1632.3431,-402 1509.8804,-385.421 1365.1533,-374.4846 1288.4315,-369.3649"/>
<polygon fill="#000000" stroke="#000000" points="1288.2752,-365.8471 1278.0664,-368.6811 1287.8143,-372.8319 1288.2752,-365.8471"/>
<text text-anchor="middle" x="1790.8431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1925.3696,-434.8773C1932.1284,-424.5863 1941.3784,-411.8363 1951.3431,-402 1993.7475,-360.142 2086.3533,-364.6039 2053.3431,-315 2041.8651,-297.7521 2027.747,-308.2401 2010.3431,-297 1972.5683,-272.6036 1977.4545,-246.2204 1936.3431,-228 1904.6617,-213.9589 1693.3198,-201.3276 1579.9363,-195.4621"/>
<polygon fill="#000000" stroke="#000000" points="1580.1117,-191.9665 1569.9455,-194.9496 1579.753,-198.9573 1580.1117,-191.9665"/>
<text text-anchor="middle" x="2124.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- medical_history -->
<g id="node27" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1052.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1052.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1048.8723,-260.983C1047.8663,-249.935 1048.8376,-236.3532 1057.3431,-228 1083.6853,-202.1297 1314.6124,-194.8413 1435.3988,-192.7947"/>
<polygon fill="#000000" stroke="#000000" points="1435.7294,-196.2899 1445.6715,-192.6288 1435.6163,-189.2908 1435.7294,-196.2899"/>
<text text-anchor="middle" x="1125.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- genetic_analysis -->
<g id="node28" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1680.3431" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1680.3431" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1601.5726,-444.8635C1567.1574,-439.5598 1526.8586,-430.9282 1492.3431,-417 1481.0258,-412.4331 1480.7434,-406.3557 1469.3431,-402 1437.0627,-389.6666 1346.4707,-378.0655 1287.6593,-371.5154"/>
<polygon fill="#000000" stroke="#000000" points="1287.7517,-368.0046 1277.4291,-370.3911 1286.9869,-374.9627 1287.7517,-368.0046"/>
<text text-anchor="middle" x="1562.3431" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1745.9128,-440.9062C1765.889,-435.4725 1787.3152,-427.7751 1805.3431,-417 1868.2253,-379.416 1893.0989,-365.7709 1918.3431,-297 1928.9107,-268.2116 1939.0577,-250.6131 1918.3431,-228 1896.0818,-203.6983 1692.9691,-195.7265 1581.2335,-193.1691"/>
<polygon fill="#000000" stroke="#000000" points="1581.1188,-189.6658 1571.0443,-192.9451 1580.9649,-196.6641 1581.1188,-189.6658"/>
<text text-anchor="middle" x="1980.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- exposure -->
<g id="node29" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1391.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1391.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1406.3333,-261.6647C1415.9633,-251.1521 1429.1091,-237.9022 1442.3431,-228 1449.8642,-222.3724 1458.3727,-217.0638 1466.719,-212.3396"/>
<polygon fill="#000000" stroke="#000000" points="1468.5605,-215.3218 1475.6575,-207.4552 1465.2039,-209.1791 1468.5605,-215.3218"/>
<text text-anchor="middle" x="1485.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_response -->
<g id="node30" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1567.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1567.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1555.1183,-260.9735C1546.7566,-248.6435 1535.5357,-232.0975 1526.1802,-218.3021"/>
<polygon fill="#000000" stroke="#000000" points="1528.8599,-216.0176 1520.3504,-209.7057 1523.0665,-219.9465 1528.8599,-216.0176"/>
<text text-anchor="middle" x="1624.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment_surgery -->
<g id="node31" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1788.3431" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1788.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1766.7956,-261.2228C1752.0581,-249.9815 1731.5922,-236.0938 1711.3431,-228 1669.3029,-211.196 1619.2476,-202.2089 1579.3611,-197.4164"/>
<polygon fill="#000000" stroke="#000000" points="1579.5199,-193.912 1569.1881,-196.2579 1578.7278,-200.867 1579.5199,-193.912"/>
<text text-anchor="middle" x="1816.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_personnel -->
<g id="node32" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3201.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3201.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3173.1201,-87.8789C3151.5731,-75.8294 3120.6891,-60.7013 3091.3431,-54 2971.3541,-26.5999 1043.3804,-19.198 717.8469,-18.1412"/>
<polygon fill="#000000" stroke="#000000" points="717.8245,-14.6412 707.8133,-18.109 717.802,-21.6412 717.8245,-14.6412"/>
<text text-anchor="middle" x="3203.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
</g>
</svg>
</div>
