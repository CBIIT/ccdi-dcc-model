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
<svg width="3053pt" height="392pt"
 viewBox="0.00 0.00 3053.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3049.1926,-388 3049.1926,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="832.1926" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="832.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node17" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1564.1926" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1564.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M859.0941,-263.7375C881.7976,-251.6862 915.5664,-235.6674 947.1926,-228 1048.4811,-203.4438 1351.3397,-195.4259 1491.5226,-192.9868"/>
<polygon fill="#000000" stroke="#000000" points="1491.7961,-196.4828 1501.7355,-192.814 1491.6776,-189.4838 1491.7961,-196.4828"/>
<text text-anchor="middle" x="986.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- methylation_array_file -->
<g id="node2" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="597.1926" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="597.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="597.1926" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="597.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M597.1926,-347.9735C597.1926,-336.1918 597.1926,-320.5607 597.1926,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="600.6927,-307.0033 597.1926,-297.0034 593.6927,-307.0034 600.6927,-307.0033"/>
<text text-anchor="middle" x="688.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node3" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="114.1926" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="114.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1207.1926" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1207.1926" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge38" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M108.9786,-87.0469C106.9744,-76.0243 106.8577,-62.447 115.1926,-54 133.8228,-35.1195 953.9737,-21.7435 1160.4139,-18.6717"/>
<polygon fill="#000000" stroke="#000000" points="1160.6709,-22.1684 1170.618,-18.5208 1160.5673,-15.1691 1160.6709,-22.1684"/>
<text text-anchor="middle" x="166.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx -->
<g id="node8" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="238.1926" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="238.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M553.3268,-281.2815C467.6519,-286.0851 284.3837,-298.1998 261.1926,-315 253.4202,-320.6305 248.2212,-329.5127 244.767,-338.2975"/>
<polygon fill="#000000" stroke="#000000" points="241.3766,-337.4027 241.5643,-347.9959 248.0236,-339.5978 241.3766,-337.4027"/>
<text text-anchor="middle" x="297.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="537.1926" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="537.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M564.5136,-266.6112C554.2721,-261.0194 544.1083,-253.3016 538.1926,-243 534.3118,-236.2419 532.9808,-228.1036 532.9053,-220.3326"/>
<polygon fill="#000000" stroke="#000000" points="536.412,-220.3024 533.459,-210.1275 529.4223,-219.9232 536.412,-220.3024"/>
<text text-anchor="middle" x="574.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M604.911,-261.2709C611.0276,-249.5879 620.7834,-235.1683 634.1926,-228 671.7837,-207.9045 1279.4401,-196.4758 1491.7026,-193.0815"/>
<polygon fill="#000000" stroke="#000000" points="1491.8658,-196.5795 1501.809,-192.9212 1491.7547,-189.5803 1491.8658,-196.5795"/>
<text text-anchor="middle" x="670.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="972.1926" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="972.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M996.2668,-261.8145C1014.1086,-250.0651 1039.511,-235.3391 1064.1926,-228 1142.1096,-204.8313 1372.5505,-196.3063 1491.4305,-193.3905"/>
<polygon fill="#000000" stroke="#000000" points="1491.6205,-196.887 1501.5342,-193.1496 1491.4536,-189.889 1491.6205,-196.887"/>
<text text-anchor="middle" x="1123.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- family_relationship -->
<g id="node6" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1164.1926" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1164.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1173.1395,-260.754C1179.7735,-249.3148 1189.9529,-235.3827 1203.1926,-228 1227.8316,-214.2609 1394.7942,-202.1201 1492.8045,-196.0697"/>
<polygon fill="#000000" stroke="#000000" points="1493.1736,-199.5538 1502.9416,-195.4504 1492.7467,-192.5668 1493.1736,-199.5538"/>
<text text-anchor="middle" x="1282.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1340.1926" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1340.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1351.0779,-261.1707C1358.8966,-249.9074 1370.456,-236.0148 1384.1926,-228 1403.1776,-216.923 1453.9645,-207.331 1496.7694,-200.8398"/>
<polygon fill="#000000" stroke="#000000" points="1497.5114,-204.2681 1506.8899,-199.3392 1496.4847,-197.3438 1497.5114,-204.2681"/>
<text text-anchor="middle" x="1431.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M260.2193,-354.5077C265.0814,-352.1907 270.2557,-349.8895 275.1926,-348 302.3891,-337.5908 310.8068,-339.9004 338.1926,-330 353.7251,-324.3848 356.3522,-319.6766 372.1926,-315 429.5108,-298.078 497.5362,-288.5912 543.6699,-283.6573"/>
<polygon fill="#000000" stroke="#000000" points="544.1608,-287.1253 553.7475,-282.6147 543.4404,-280.1625 544.1608,-287.1253"/>
<text text-anchor="middle" x="396.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M235.9006,-348.0386C233.8591,-330.4704 231.1926,-302.9417 231.1926,-279 231.1926,-279 231.1926,-279 231.1926,-105 231.1926,-57.7582 966.2332,-26.9903 1160.5453,-19.682"/>
<polygon fill="#000000" stroke="#000000" points="1160.8511,-23.1731 1170.7136,-19.3025 1160.5899,-16.178 1160.8511,-23.1731"/>
<text text-anchor="middle" x="255.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="374.1926" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="374.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M395.9254,-348.3943C410.5056,-337.3698 430.5673,-323.6608 450.1926,-315 480.5119,-301.6199 516.6385,-292.6855 545.4902,-287.064"/>
<polygon fill="#000000" stroke="#000000" points="546.1866,-290.4945 555.3706,-285.212 544.8969,-283.6144 546.1866,-290.4945"/>
<text text-anchor="middle" x="521.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node10" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="807.1926" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="807.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M802.5732,-347.819C798.7409,-336.5583 792.1075,-322.8024 781.1926,-315 735.173,-282.1033 710.3803,-309.4227 655.1926,-297 650.5511,-295.9552 645.7438,-294.7195 640.9734,-293.3926"/>
<polygon fill="#000000" stroke="#000000" points="641.878,-290.0107 631.2981,-290.5728 639.9194,-296.7311 641.878,-290.0107"/>
<text text-anchor="middle" x="856.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sequencing_file -->
<g id="node11" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="83.1926" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="83.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M88.6177,-347.7682C93.0323,-336.335 100.4852,-322.4042 112.1926,-315 147.8587,-292.4435 423.6109,-283.1622 542.7067,-280.1784"/>
<polygon fill="#000000" stroke="#000000" points="542.7998,-283.6773 552.7111,-279.9334 542.6284,-276.6794 542.7998,-283.6773"/>
<text text-anchor="middle" x="178.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1501.1926" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1501.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1488.9175,-260.9631C1483.5758,-250.7008 1479.8258,-237.9508 1486.1926,-228 1491.4425,-219.7948 1499.0907,-213.4332 1507.5716,-208.5084"/>
<polygon fill="#000000" stroke="#000000" points="1509.3282,-211.5415 1516.6455,-203.8794 1506.1471,-205.306 1509.3282,-211.5415"/>
<text text-anchor="middle" x="1554.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- laboratory_test -->
<g id="node14" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1706.1926" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1706.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1634.4015,-357.2044C1536.5994,-345.5759 1355.9371,-325.3526 1201.1926,-315 1080.0641,-306.8963 774.9042,-317.1721 655.1926,-297 650.3777,-296.1887 645.4066,-295.0818 640.4936,-293.8128"/>
<polygon fill="#000000" stroke="#000000" points="641.1327,-290.357 630.5589,-291.0233 639.2404,-297.0964 641.1327,-290.357"/>
<text text-anchor="middle" x="1447.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1730.5,-348.7695C1749.291,-335.746 1773.9363,-319.3856 1785.1926,-315 1829.3099,-297.8115 1859.6721,-333.1978 1890.1926,-297 1900.5063,-284.7678 1900.0164,-273.6291 1890.1926,-261 1859.4851,-221.5236 1721.545,-203.8964 1635.2315,-196.6124"/>
<polygon fill="#000000" stroke="#000000" points="1635.4835,-193.1214 1625.2316,-195.7951 1634.9133,-200.0981 1635.4835,-193.1214"/>
<text text-anchor="middle" x="1962.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M490.9537,-198.6346C455.3347,-205.7189 415.1365,-219.2759 434.1926,-243 447.8152,-259.9595 501.5135,-269.4082 543.6011,-274.3228"/>
<polygon fill="#000000" stroke="#000000" points="543.4211,-277.8242 553.746,-275.4477 544.1926,-270.8669 543.4211,-277.8242"/>
<text text-anchor="middle" x="474.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M560.8987,-176.0255C596.7734,-152.645 667.7345,-109.4532 734.1926,-87 884.5374,-36.2052 1074.1967,-22.7953 1160.5473,-19.2611"/>
<polygon fill="#000000" stroke="#000000" points="1160.6977,-22.758 1170.5562,-18.8772 1160.4294,-15.7632 1160.6977,-22.758"/>
<text text-anchor="middle" x="774.6926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- exposure -->
<g id="node16" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1657.1926" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1657.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1647.4397,-261.1049C1641.1561,-250.6428 1632.2882,-237.642 1622.1926,-228 1616.6539,-222.7102 1610.2154,-217.7969 1603.6844,-213.4072"/>
<polygon fill="#000000" stroke="#000000" points="1605.1143,-210.169 1594.797,-207.7596 1601.3599,-216.077 1605.1143,-210.169"/>
<text text-anchor="middle" x="1677.6926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- consent_group -->
<g id="node29" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1564.1926" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1564.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge39" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1564.1926,-173.9735C1564.1926,-162.1918 1564.1926,-146.5607 1564.1926,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1567.6927,-133.0033 1564.1926,-123.0034 1560.6927,-133.0034 1567.6927,-133.0033"/>
<text text-anchor="middle" x="1614.6926" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="894.1926" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="894.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge40" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M913.792,-87.518C927.7097,-76.1034 947.3744,-61.9007 967.1926,-54 1001.5288,-40.3116 1101.545,-28.4752 1161.0751,-22.3827"/>
<polygon fill="#000000" stroke="#000000" points="1161.7386,-25.8336 1171.3371,-21.3482 1161.0365,-18.8689 1161.7386,-25.8336"/>
<text text-anchor="middle" x="1023.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- genetic_analysis -->
<g id="node19" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1388.1926" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1388.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1310.7383,-357.3621C1283.9592,-354.3841 1253.7582,-351.035 1226.1926,-348 1152.8673,-339.9268 1130.657,-354.8289 1061.1926,-330 1049.7006,-325.8924 1049.8058,-318.7512 1038.1926,-315 957.1124,-288.8102 739.112,-311.7461 655.1926,-297 650.3835,-296.155 645.4161,-295.0266 640.5053,-293.745"/>
<polygon fill="#000000" stroke="#000000" points="641.1478,-290.2897 630.573,-290.941 639.2459,-297.0263 641.1478,-290.2897"/>
<text text-anchor="middle" x="1131.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1470.7914,-359.701C1557.7477,-351.2468 1686.5122,-332.9374 1719.1926,-297 1739.9026,-274.2261 1744.4382,-252.0242 1725.1926,-228 1713.4804,-213.3797 1671.7006,-204.3011 1633.639,-198.9182"/>
<polygon fill="#000000" stroke="#000000" points="1633.9256,-195.4254 1623.5485,-197.5624 1632.9933,-202.363 1633.9256,-195.4254"/>
<text text-anchor="middle" x="1807.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1042.1926" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1042.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1060.3364,-87.8383C1072.5498,-76.9961 1089.431,-63.3233 1106.1926,-54 1124.5329,-43.7986 1146.3074,-35.6005 1164.9345,-29.6197"/>
<polygon fill="#000000" stroke="#000000" points="1166.1202,-32.9165 1174.6344,-26.6111 1164.0464,-26.2307 1166.1202,-32.9165"/>
<text text-anchor="middle" x="1154.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_personnel -->
<g id="node21" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1207.1926" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1207.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1207.1926,-86.9735C1207.1926,-75.1918 1207.1926,-59.5607 1207.1926,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="1210.6927,-46.0033 1207.1926,-36.0034 1203.6927,-46.0034 1210.6927,-46.0033"/>
<text text-anchor="middle" x="1276.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_status -->
<g id="node22" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2849.1926" cy="-366" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2849.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_funding -->
<g id="node23" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1389.1926" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1389.1926" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1379.5622,-86.8881C1372.7681,-75.8022 1362.6673,-62.2139 1350.1926,-54 1334.1372,-43.4285 1287.7085,-32.8714 1252.067,-25.9497"/>
<polygon fill="#000000" stroke="#000000" points="1252.3451,-22.4399 1241.8672,-24.0097 1251.0371,-29.3166 1252.3451,-22.4399"/>
<text text-anchor="middle" x="1428.1926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node24" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2228.1926" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2228.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2132.2578,-357.5665C1995.7481,-345.9198 1737.5495,-325.1972 1517.1926,-315 1325.8001,-306.1431 844.3152,-327.6951 655.1926,-297 650.1826,-296.1869 645.0058,-295.043 639.9022,-293.7216"/>
<polygon fill="#000000" stroke="#000000" points="640.8151,-290.3426 630.2408,-291.0019 638.9182,-297.0807 640.8151,-290.3426"/>
<text text-anchor="middle" x="1857.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2330.5062,-359.9469C2426.5187,-350.2868 2548.4123,-325.3202 2498.1926,-261 2340.6709,-59.2499 1466.8874,-24.4757 1253.9773,-18.9695"/>
<polygon fill="#000000" stroke="#000000" points="1253.8502,-15.4653 1243.766,-18.715 1253.6757,-22.4632 1253.8502,-15.4653"/>
<text text-anchor="middle" x="2521.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2227.94,-347.872C2226.7793,-336.7797 2223.3739,-323.1903 2214.1926,-315 2175.2599,-280.2694 2147.6065,-313.7405 2098.1926,-297 2066.5461,-286.2788 2063.6371,-272.3 2032.1926,-261 1960.2412,-235.1432 1745.3973,-210.3994 1633.5701,-198.8267"/>
<polygon fill="#000000" stroke="#000000" points="1633.7111,-195.3229 1623.4056,-197.7818 1632.9952,-202.2862 1633.7111,-195.3229"/>
<text text-anchor="middle" x="2184.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- diagnosis -->
<g id="node25" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1162.1926" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1162.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1108.9345,-361.8235C1065.1204,-357.2534 1001.8873,-348.0269 949.1926,-330 935.835,-325.4303 934.7617,-318.8973 921.1926,-315 807.3044,-282.2895 771.6797,-318.7082 655.1926,-297 650.3924,-296.1055 645.4308,-294.9455 640.5233,-293.6454"/>
<polygon fill="#000000" stroke="#000000" points="641.1711,-290.1908 630.5949,-290.8201 639.2551,-296.9235 641.1711,-290.1908"/>
<text text-anchor="middle" x="993.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1211.8258,-358.3498C1267.4651,-349.536 1350.578,-335.555 1355.1926,-330 1359.4526,-324.8719 1359.8428,-319.777 1355.1926,-315 1303.3239,-261.717 738.0613,-350.283 686.1926,-297 675.0321,-285.5352 675.7724,-273.1416 686.1926,-261 717.6729,-224.3192 853.1129,-232.983 901.1926,-228 1115.1044,-205.8299 1369.3488,-196.8539 1491.5336,-193.6157"/>
<polygon fill="#000000" stroke="#000000" points="1491.9706,-197.1056 1501.8763,-193.347 1491.7888,-190.1079 1491.9706,-197.1056"/>
<text text-anchor="middle" x="730.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node26" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2559.1926" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2559.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2508.8751,-361.2862C2465.7361,-357.3555 2401.915,-351.8029 2346.1926,-348 2192.5642,-337.5153 2152.1149,-355.1241 2000.1926,-330 1976.0399,-326.0058 1971.417,-318.5341 1947.1926,-315 1663.0615,-273.548 938.7809,-342.0165 655.1926,-297 650.1798,-296.2043 645.0013,-295.0713 639.8966,-293.756"/>
<polygon fill="#000000" stroke="#000000" points="640.8081,-290.3767 630.2342,-291.0428 638.9156,-297.116 640.8081,-290.3767"/>
<text text-anchor="middle" x="2042.6926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2598.6901,-354.0112C2654.4486,-336.8989 2751.0631,-306.4882 2765.1926,-297 2795.1482,-276.8844 2818.1926,-271.5829 2818.1926,-235.5 2818.1926,-235.5 2818.1926,-235.5 2818.1926,-105 2818.1926,-64.7489 1518.6211,-26.6197 1253.9169,-19.2708"/>
<polygon fill="#000000" stroke="#000000" points="1253.9605,-15.7708 1243.8675,-18.9928 1253.7668,-22.7681 1253.9605,-15.7708"/>
<text text-anchor="middle" x="2860.6926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2553.5927,-347.7758C2545.358,-324.0978 2527.6802,-283.1728 2498.1926,-261 2449.8598,-224.6568 2426.0309,-236.7329 2366.1926,-228 2226.6458,-207.6344 1806.5684,-196.9709 1636.6745,-193.3966"/>
<polygon fill="#000000" stroke="#000000" points="1636.6509,-189.8955 1626.5802,-193.1864 1636.5051,-196.894 1636.6509,-189.8955"/>
<text text-anchor="middle" x="2571.6926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- generic_file -->
<g id="node27" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2695.1926" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2695.1926" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2648.2283,-353.4074C2638.9908,-351.3058 2629.3303,-349.3677 2620.1926,-348 2384.5875,-312.7352 2323.2584,-323.8352 2085.1926,-315 1926.4005,-309.1068 812.1459,-321.8065 655.1926,-297 650.1793,-296.2076 645.0004,-295.0768 639.8956,-293.7627"/>
<polygon fill="#000000" stroke="#000000" points="640.8067,-290.3832 630.2329,-291.0508 638.9151,-297.1228 640.8067,-290.3832"/>
<text text-anchor="middle" x="2528.1926" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2743.6909,-353.7543C2814.8487,-335.0942 2939.1926,-299.5472 2939.1926,-279 2939.1926,-279 2939.1926,-279 2939.1926,-105 2939.1926,-69.8335 3118.974,-92.2749 2394.1926,-54 1950.9177,-30.5912 1413.6584,-21.0935 1254.0418,-18.6654"/>
<polygon fill="#000000" stroke="#000000" points="1253.6946,-15.1598 1243.6431,-18.5091 1253.5894,-22.159 1253.6946,-15.1598"/>
<text text-anchor="middle" x="2992.1926" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2687.2346,-347.798C2675.7089,-323.751 2651.9875,-281.9954 2618.1926,-261 2546.1335,-216.2326 2514.5345,-237.115 2430.1926,-228 2277.1984,-211.4656 1815.8946,-198.3721 1636.5829,-193.7754"/>
<polygon fill="#000000" stroke="#000000" points="1636.5493,-190.2735 1626.4633,-193.5174 1636.3708,-197.2713 1636.5493,-190.2735"/>
<text text-anchor="middle" x="2708.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_response -->
<g id="node28" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2384.1926" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2384.1926" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2318.6531,-264.9393C2261.9075,-253.2858 2177.4943,-237.1942 2103.1926,-228 1937.0033,-207.4355 1740.4307,-198.0444 1636.705,-194.2445"/>
<polygon fill="#000000" stroke="#000000" points="1636.7757,-190.7449 1626.6563,-193.8833 1636.5241,-197.7404 1636.7757,-190.7449"/>
<text text-anchor="middle" x="2279.1926" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge25" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1545.5818,-87.3537C1532.3178,-75.8658 1513.4837,-61.6429 1494.1926,-54 1451.5067,-37.0884 1323.3649,-25.9685 1253.6307,-20.9951"/>
<polygon fill="#000000" stroke="#000000" points="1253.5924,-17.4839 1243.3726,-20.2778 1253.1041,-24.4669 1253.5924,-17.4839"/>
<text text-anchor="middle" x="1584.6926" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
</g>
</svg>
</div>
