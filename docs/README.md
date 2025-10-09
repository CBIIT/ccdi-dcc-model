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
<svg width="2744pt" height="392pt"
 viewBox="0.00 0.00 2743.79 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2739.7947,-388 2739.7947,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2094.7947" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2094.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1407.7947" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1407.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2051.4388,-263.4614C2016.6088,-251.6713 1966.1864,-236.1469 1920.7947,-228 1838.2879,-213.1917 1600.8106,-200.7383 1480.0969,-195.1524"/>
<polygon fill="#000000" stroke="#000000" points="1479.9964,-191.6442 1469.8463,-194.6816 1479.6752,-198.6368 1479.9964,-191.6442"/>
<text text-anchor="middle" x="2051.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node14" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1407.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1407.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5628,-87.0291C52.5514,-75.9995 52.4335,-62.4209 60.7947,-54 84.181,-30.4467 1125.2995,-20.3573 1360.7887,-18.3743"/>
<polygon fill="#000000" stroke="#000000" points="1361.0987,-21.8719 1371.0692,-18.2886 1361.0403,-14.8721 1361.0987,-21.8719"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- consent_group -->
<g id="node15" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1407.7947" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1407.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1407.7947,-173.9735C1407.7947,-162.1918 1407.7947,-146.5607 1407.7947,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1411.2948,-133.0033 1407.7947,-123.0034 1404.2948,-133.0034 1411.2948,-133.0033"/>
<text text-anchor="middle" x="1458.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2255.7947" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2255.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2224.6567,-263.7084C2198.4424,-251.6397 2159.6004,-235.6117 2123.7947,-228 2002.6579,-202.2482 1637.1793,-194.7788 1480.4475,-192.7294"/>
<polygon fill="#000000" stroke="#000000" points="1480.4742,-189.2295 1470.4305,-192.6021 1480.3852,-196.2289 1480.4742,-189.2295"/>
<text text-anchor="middle" x="2218.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pathology_file -->
<g id="node5" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="828.7947" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="828.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node13" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="508.7947" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="508.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M816.2677,-348.1183C807.0647,-336.5253 793.4693,-322.2735 777.7947,-315 734.304,-294.8189 609.7586,-306.6491 562.7947,-297 558.9303,-296.206 554.9579,-295.2219 551.0053,-294.1264"/>
<polygon fill="#000000" stroke="#000000" points="551.8771,-290.7339 541.2933,-291.2181 549.869,-297.4397 551.8771,-290.7339"/>
<text text-anchor="middle" x="859.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="192.7947" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="192.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M201.9432,-347.7314C218.8383,-316.3141 258.2528,-253.0192 312.7947,-228 336.0567,-217.3294 1094.572,-199.1466 1335.2697,-193.6326"/>
<polygon fill="#000000" stroke="#000000" points="1335.4,-197.1306 1345.3173,-193.4029 1335.2399,-190.1325 1335.4,-197.1306"/>
<text text-anchor="middle" x="350.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M212.0411,-348.1875C225.5113,-336.7805 244.4876,-322.7171 263.7947,-315 317.9574,-293.3512 336.0899,-305.5103 393.7947,-297 414.6498,-293.9243 437.6037,-290.3664 457.4831,-287.23"/>
<polygon fill="#000000" stroke="#000000" points="458.2413,-290.6536 467.5711,-285.6331 457.1468,-283.7397 458.2413,-290.6536"/>
<text text-anchor="middle" x="349.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M185.802,-347.975C179.6931,-330.5896 171.7947,-303.3946 171.7947,-279 171.7947,-279 171.7947,-279 171.7947,-105 171.7947,-44.2202 1135.3974,-22.946 1360.9625,-18.7986"/>
<polygon fill="#000000" stroke="#000000" points="1361.2042,-22.2949 1371.139,-18.6139 1361.0771,-15.296 1361.2042,-22.2949"/>
<text text-anchor="middle" x="257.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="644.7947" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="644.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M686.0186,-263.8712C699.9892,-258.0873 715.4311,-250.9487 728.7947,-243 738.0415,-237.5 737.7308,-231.8041 747.7947,-228 801.5267,-207.6898 1174.9605,-197.1276 1335.1202,-193.4895"/>
<polygon fill="#000000" stroke="#000000" points="1335.4366,-196.9834 1345.3555,-193.2599 1335.2795,-189.9852 1335.4366,-196.9834"/>
<text text-anchor="middle" x="806.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="583.7947" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="583.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M578.8564,-209.8802C575.3293,-220.3369 569.7809,-233.3374 561.7947,-243 556.9228,-248.8945 550.8452,-254.2194 544.5609,-258.8556"/>
<polygon fill="#000000" stroke="#000000" points="542.2357,-256.2054 535.957,-264.7394 546.1872,-261.9835 542.2357,-256.2054"/>
<text text-anchor="middle" x="595.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge39" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M611.7535,-190.4589C717.9355,-184.3689 1095.9388,-160.4684 1209.7947,-123 1240.0618,-113.0395 1243.7978,-102.2145 1271.7947,-87 1305.6101,-68.6235 1344.8722,-48.8692 1372.4929,-35.2267"/>
<polygon fill="#000000" stroke="#000000" points="1374.3243,-38.2263 1381.7492,-30.6684 1371.2317,-31.9465 1374.3243,-38.2263"/>
<text text-anchor="middle" x="1295.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1123.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1123.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1118.7725,-86.8155C1116.9606,-75.9834 1116.9823,-62.6958 1124.7947,-54 1140.3049,-36.736 1284.8094,-25.4538 1361.1036,-20.6488"/>
<polygon fill="#000000" stroke="#000000" points="1361.6304,-24.123 1371.3958,-20.0138 1361.1993,-17.1363 1361.6304,-24.123"/>
<text text-anchor="middle" x="1186.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- exposure -->
<g id="node10" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="789.7947" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="789.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M822.1541,-264.575C836.7355,-258.0399 854.1554,-250.1838 869.7947,-243 884.0681,-236.4436 886.5942,-231.9572 901.7947,-228 981.6074,-207.222 1215.4727,-197.5777 1335.2591,-193.8975"/>
<polygon fill="#000000" stroke="#000000" points="1335.5456,-197.3906 1345.4356,-193.5908 1335.3346,-190.3937 1335.5456,-197.3906"/>
<text text-anchor="middle" x="945.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- laboratory_test -->
<g id="node11" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1688.7947" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1688.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1700.7015,-348.0884C1713.8477,-325.84 1730.9082,-287.5772 1712.7947,-261 1686.7725,-222.8187 1560.5092,-204.9062 1478.8145,-197.1889"/>
<polygon fill="#000000" stroke="#000000" points="1478.8654,-193.6791 1468.5882,-196.2539 1478.2279,-200.65 1478.8654,-193.6791"/>
<text text-anchor="middle" x="1785.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1634.9452,-352.2389C1584.0232,-339.9204 1505.2732,-322.6571 1435.7947,-315 1242.9212,-293.7437 753.9998,-330.0546 562.7947,-297 558.854,-296.3187 554.8097,-295.4031 550.7932,-294.3441"/>
<polygon fill="#000000" stroke="#000000" points="551.5209,-290.9105 540.9407,-291.4686 549.5596,-297.6302 551.5209,-290.9105"/>
<text text-anchor="middle" x="1592.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- synonym -->
<g id="node12" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1906.7947" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1906.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1903.0649,-348.02C1897.1452,-324.2247 1883.2305,-282.7532 1854.7947,-261 1797.3398,-217.0473 1591.0437,-200.6201 1479.9155,-194.8645"/>
<polygon fill="#000000" stroke="#000000" points="1479.9564,-191.3622 1469.7934,-194.3561 1479.6052,-198.3534 1479.9564,-191.3622"/>
<text text-anchor="middle" x="1925.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1865.5631,-354.9252C1817.1804,-342.5128 1734.3372,-323.0711 1661.7947,-315 1419.0376,-287.9907 803.5673,-338.0982 562.7947,-297 558.8525,-296.3271 554.8073,-295.4171 550.7901,-294.3619"/>
<polygon fill="#000000" stroke="#000000" points="551.5166,-290.9281 540.9368,-291.4917 549.5589,-297.6488 551.5166,-290.9281"/>
<text text-anchor="middle" x="1792.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1957.1708,-361.2755C2062.7261,-350.8673 2299.3307,-324.6764 2322.7947,-297 2333.1415,-284.7957 2330.5629,-274.9877 2322.7947,-261 2235.3558,-103.554 1627.0929,-37.5959 1453.7828,-21.8689"/>
<polygon fill="#000000" stroke="#000000" points="1453.9863,-18.3732 1443.7141,-20.9676 1453.3622,-25.3453 1453.9863,-18.3732"/>
<text text-anchor="middle" x="2314.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M543.0161,-267.3934C549.5685,-265.2277 556.3837,-263.0137 562.7947,-261 589.7625,-252.5293 597.6437,-253.7303 623.7947,-243 636.8556,-237.6408 638.1874,-231.7615 651.7947,-228 716.4435,-210.1291 1158.8933,-197.8641 1335.3586,-193.6312"/>
<polygon fill="#000000" stroke="#000000" points="1335.6688,-197.1249 1345.5826,-193.3878 1335.5021,-190.1269 1335.6688,-197.1249"/>
<text text-anchor="middle" x="688.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M494.2428,-261.9664C487.2021,-251.5673 481.6618,-238.3309 488.7947,-228 495.8534,-217.7766 523.9115,-207.9034 547.7198,-201.0907"/>
<polygon fill="#000000" stroke="#000000" points="548.8814,-204.4011 557.5896,-198.3663 547.0188,-197.6534 548.8814,-204.4011"/>
<text text-anchor="middle" x="525.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="410.7947" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="410.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M470.3802,-270.033C445.4327,-263.3433 416.2217,-253.5674 408.7947,-243 404.1891,-236.4471 403.0853,-228.1634 403.5844,-220.1882"/>
<polygon fill="#000000" stroke="#000000" points="407.083,-220.4422 405.0044,-210.0532 400.1507,-219.4709 407.083,-220.4422"/>
<text text-anchor="middle" x="445.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge10" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1407.7947,-86.9735C1407.7947,-75.1918 1407.7947,-59.5607 1407.7947,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1411.2948,-46.0033 1407.7947,-36.0034 1404.2948,-46.0034 1411.2948,-46.0033"/>
<text text-anchor="middle" x="1471.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_admin -->
<g id="node16" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1574.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1574.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1566.1574,-86.9776C1559.9866,-75.9274 1550.6802,-62.3453 1538.7947,-54 1513.7191,-36.3934 1480.3604,-27.3856 1453.5818,-22.7834"/>
<polygon fill="#000000" stroke="#000000" points="1454.0939,-19.321 1443.6718,-21.2265 1453.0074,-26.2362 1454.0939,-19.321"/>
<text text-anchor="middle" x="1609.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="960.7947" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="960.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M974.2993,-261.1496C984.1511,-249.5706 998.5757,-235.3227 1014.7947,-228 1043.2737,-215.142 1230.7287,-202.3285 1336.126,-196.0253"/>
<polygon fill="#000000" stroke="#000000" points="1336.598,-199.5036 1346.3732,-195.4176 1336.1835,-192.5159 1336.598,-199.5036"/>
<text text-anchor="middle" x="1094.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_response -->
<g id="node18" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1183.7947" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1183.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1178.8758,-260.9068C1177.1028,-250.109 1177.1292,-236.8255 1184.7947,-228 1194.9041,-216.3608 1276.7308,-205.4376 1338.3569,-198.7422"/>
<polygon fill="#000000" stroke="#000000" points="1338.8741,-202.207 1348.4455,-197.6639 1338.1301,-195.2466 1338.8741,-202.207"/>
<text text-anchor="middle" x="1267.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- generic_file -->
<g id="node19" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2495.7947" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2495.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2475.7329,-348.7648C2438.263,-317.7811 2353.81,-253.5262 2269.7947,-228 2195.3932,-205.3947 1674.5035,-195.775 1480.4368,-192.9481"/>
<polygon fill="#000000" stroke="#000000" points="1480.3874,-189.4471 1470.338,-192.8028 1480.2866,-196.4464 1480.3874,-189.4471"/>
<text text-anchor="middle" x="2456.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2433.8266,-359.8726C2317.3949,-348.653 2057.9376,-325.0411 1838.7947,-315 1697.1514,-308.5099 702.592,-320.6991 562.7947,-297 558.8518,-296.3316 554.806,-295.4247 550.7885,-294.3714"/>
<polygon fill="#000000" stroke="#000000" points="551.5143,-290.9375 540.9346,-291.5041 549.5585,-297.6587 551.5143,-290.9375"/>
<text text-anchor="middle" x="2126.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2546.8366,-354.6502C2584.7049,-342.8675 2629.7947,-320.1895 2629.7947,-279 2629.7947,-279 2629.7947,-279 2629.7947,-105 2629.7947,-69.6618 2601.8217,-66.5701 2568.7947,-54 2515.9435,-33.8847 1664.148,-21.3786 1454.2553,-18.5927"/>
<polygon fill="#000000" stroke="#000000" points="1454.2262,-15.0922 1444.181,-18.46 1454.1339,-22.0915 1454.2262,-15.0922"/>
<text text-anchor="middle" x="2682.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1012.7947" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1012.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M989.5667,-348.3927C972.5974,-336.6046 948.5016,-322.009 924.7947,-315 847.5559,-292.1642 641.9535,-311.8725 562.7947,-297 558.9174,-296.2715 554.9362,-295.3325 550.9778,-294.2664"/>
<polygon fill="#000000" stroke="#000000" points="551.8387,-290.8713 541.2572,-291.4017 549.8599,-297.5858 551.8387,-290.8713"/>
<text text-anchor="middle" x="1029.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2327.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2327.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge11" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2308.4697,-87.8485C2293.7739,-75.9518 2272.4514,-61.029 2250.7947,-54 2175.1266,-29.4407 1620.8752,-20.6396 1454.7351,-18.5371"/>
<polygon fill="#000000" stroke="#000000" points="1454.405,-15.0328 1444.3623,-18.4082 1454.318,-22.0323 1454.405,-15.0328"/>
<text text-anchor="middle" x="2330.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2495.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2495.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2467.0739,-87.8155C2445.5263,-75.9023 2414.8608,-60.9734 2385.7947,-54 2294.8318,-32.1766 1636.6162,-21.2592 1454.4257,-18.6341"/>
<polygon fill="#000000" stroke="#000000" points="1454.41,-15.1336 1444.3611,-18.4905 1454.3102,-22.1329 1454.41,-15.1336"/>
<text text-anchor="middle" x="2495.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node23" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="434.7947" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="434.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M435.5946,-347.5149C436.8612,-337.1032 439.8612,-324.3532 446.7947,-315 452.2341,-307.6624 459.6495,-301.5734 467.4612,-296.6201"/>
<polygon fill="#000000" stroke="#000000" points="469.438,-299.5209 476.365,-291.5041 465.9506,-293.4514 469.438,-299.5209"/>
<text text-anchor="middle" x="538.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M370.8731,-202.9408C349.3728,-209.7263 326.0033,-218.867 319.7947,-228 316.0467,-233.5133 315.5445,-237.8638 319.7947,-243 324.221,-248.3489 402.6376,-261.9378 457.0571,-270.8054"/>
<polygon fill="#000000" stroke="#000000" points="456.8226,-274.313 467.2537,-272.4577 457.9423,-267.4031 456.8226,-274.313"/>
<text text-anchor="middle" x="360.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M453.0003,-182.6111C561.9368,-158.6183 861.6824,-94.1271 1113.7947,-54 1201.0444,-40.113 1303.6022,-28.6512 1361.6236,-22.6142"/>
<polygon fill="#000000" stroke="#000000" points="1362.3377,-26.0591 1371.9254,-21.5507 1361.6188,-19.0961 1362.3377,-26.0591"/>
<text text-anchor="middle" x="960.2947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sequencing_file -->
<g id="node25" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="651.7947" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="651.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M648.0868,-347.5551C644.9709,-336.625 639.4226,-323.3258 629.7947,-315 606.472,-294.8315 592.3223,-305.8791 562.7947,-297 559.4278,-295.9875 555.9537,-294.9088 552.4673,-293.8018"/>
<polygon fill="#000000" stroke="#000000" points="553.2798,-290.3862 542.6879,-290.6388 551.1255,-297.0465 553.2798,-290.3862"/>
<text text-anchor="middle" x="707.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- diagnosis -->
<g id="node26" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1227.7947" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1227.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1243.2596,-348.4626C1252.4146,-338.3668 1264.4146,-325.6168 1275.7947,-315 1285.0324,-306.382 1288.3296,-305.3677 1297.7947,-297 1327.8736,-270.4084 1361.0325,-238.3581 1382.9984,-216.7175"/>
<polygon fill="#000000" stroke="#000000" points="1385.6256,-219.042 1390.2778,-209.5231 1380.7049,-214.0632 1385.6256,-219.042"/>
<text text-anchor="middle" x="1379.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1198.9373,-350.5374C1174.6041,-338.3671 1138.4597,-322.2856 1104.7947,-315 987.0105,-289.5098 681.4126,-318.2755 562.7947,-297 558.8583,-296.294 554.8171,-295.3613 550.8024,-294.2914"/>
<polygon fill="#000000" stroke="#000000" points="551.5338,-290.8585 540.9528,-291.3999 549.562,-297.575 551.5338,-290.8585"/>
<text text-anchor="middle" x="1194.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node27" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1655.7947" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1655.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1620.5257,-266.6274C1577.7387,-251.6175 1505.3525,-226.2239 1457.0704,-209.2862"/>
<polygon fill="#000000" stroke="#000000" points="1458.047,-205.9198 1447.4522,-205.9121 1455.7298,-212.5251 1458.047,-205.9198"/>
<text text-anchor="middle" x="1585.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- genetic_analysis -->
<g id="node28" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1418.7947" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1418.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1429.2517,-347.8765C1431.9284,-342.3214 1434.4336,-336.0699 1435.7947,-330 1444.3698,-291.7588 1431.2249,-247.2955 1420.2002,-219.3992"/>
<polygon fill="#000000" stroke="#000000" points="1423.3337,-217.8176 1416.2785,-209.9134 1416.8647,-220.492 1423.3337,-217.8176"/>
<text text-anchor="middle" x="1507.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1368.1892,-351.1683C1317.341,-336.2905 1246.0168,-315.501 1242.7947,-315 1093.4256,-291.7744 711.6734,-323.186 562.7947,-297 558.856,-296.3072 554.8131,-295.3837 550.7974,-294.3196"/>
<polygon fill="#000000" stroke="#000000" points="551.5268,-290.8863 540.9463,-291.4366 549.5607,-297.6045 551.5268,-290.8863"/>
<text text-anchor="middle" x="1361.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
</g>
</svg>
</div>
