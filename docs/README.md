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
<svg width="3373pt" height="392pt"
 viewBox="0.00 0.00 3373.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3369.3431,-388 3369.3431,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1956" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1448" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1448" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1910.7917,-263.7331C1875.1215,-252.2531 1823.8966,-237.0103 1778,-228 1689.7831,-210.6816 1586.546,-201.1021 1519.3485,-196.2605"/>
<polygon fill="#000000" stroke="#000000" points="1519.513,-192.7635 1509.2917,-195.552 1519.0209,-199.7462 1519.513,-192.7635"/>
<text text-anchor="middle" x="1905" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- consent_group -->
<g id="node2" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1271" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1271" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- study -->
<g id="node13" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1072" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1072" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge38" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1237.6868,-88.588C1216.4662,-78.3034 1188.3041,-64.9662 1163,-54 1146.0884,-46.6709 1127.1683,-39.0886 1110.979,-32.7839"/>
<polygon fill="#000000" stroke="#000000" points="1111.8833,-29.381 1101.294,-29.0371 1109.3576,-35.9095 1111.8833,-29.381"/>
<text text-anchor="middle" x="1258.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2417" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2417" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node32" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2791" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2791" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2422.6452,-347.9567C2427.2569,-336.4494 2435.0053,-322.361 2447,-315 2502.2209,-281.1115 2674.4325,-309.528 2738,-297 2741.6468,-296.2813 2745.3871,-295.3755 2749.1114,-294.3546"/>
<polygon fill="#000000" stroke="#000000" points="2750.284,-297.657 2758.8577,-291.4327 2748.2738,-290.9518 2750.284,-297.657"/>
<text text-anchor="middle" x="2538.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node4" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="419" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="419" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M439.5598,-87.7293C454.8932,-75.9387 476.9195,-61.1984 499,-54 548.3714,-37.9046 897.0584,-24.1583 1025.0418,-19.6021"/>
<polygon fill="#000000" stroke="#000000" points="1025.4305,-23.0907 1035.3007,-19.2398 1025.1834,-16.095 1025.4305,-23.0907"/>
<text text-anchor="middle" x="555.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1199" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1199" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1175.4111,-348.6126C1158.2033,-336.928 1133.8189,-322.3659 1110,-315 1011.338,-284.4893 815.553,-338.3311 884,-261 900.2217,-242.6728 1230.3362,-211.2859 1377.8463,-198.108"/>
<polygon fill="#000000" stroke="#000000" points="1378.4944,-201.5643 1388.1446,-197.1911 1377.8736,-194.5918 1378.4944,-201.5643"/>
<text text-anchor="middle" x="949.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge44" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1275.5423,-359.4912C1408.9512,-348.4132 1692.7865,-326.0248 1933,-315 2111.7454,-306.7963 2561.7955,-328.1324 2738,-297 2741.7111,-296.3443 2745.5141,-295.4742 2749.2961,-294.4697"/>
<polygon fill="#000000" stroke="#000000" points="2750.5803,-297.7399 2759.1801,-291.5517 2748.5983,-291.0264 2750.5803,-297.7399"/>
<text text-anchor="middle" x="1998.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_surgery -->
<g id="node6" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2158" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2158" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2111.3567,-262.9798C2075.1605,-251.2539 2023.4848,-236.0415 1977,-228 1891.3113,-213.1764 1643.9575,-200.6243 1520.2445,-195.0652"/>
<polygon fill="#000000" stroke="#000000" points="1520.2565,-191.5624 1510.1104,-194.6131 1519.9444,-198.5554 1520.2565,-191.5624"/>
<text text-anchor="middle" x="2120.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_status -->
<g id="node7" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="577" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="577" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M593.0751,-87.3463C604.8349,-75.6978 621.8484,-61.2886 640,-54 708.9851,-26.2999 928.7565,-19.9134 1025.5141,-18.4411"/>
<polygon fill="#000000" stroke="#000000" points="1025.638,-21.9397 1035.5876,-18.2989 1025.5392,-14.9404 1025.638,-21.9397"/>
<text text-anchor="middle" x="696.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="728" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="728" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge21" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M740.0265,-86.8082C748.6199,-75.3918 761.2446,-61.4648 776,-54 818.5965,-32.4502 953.4466,-23.266 1025.5178,-19.815"/>
<polygon fill="#000000" stroke="#000000" points="1025.8491,-23.3035 1035.6773,-19.3467 1025.5267,-16.311 1025.8491,-23.3035"/>
<text text-anchor="middle" x="827" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node9" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="893" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="893" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M810.7381,-359.5899C769.5325,-354.4902 725.7288,-345.5267 713,-330 699.7834,-313.8784 695.9548,-288.2871 726,-261 803.7498,-190.3878 855.5701,-239.203 960,-228 1000.2575,-223.6813 1251.1831,-205.8305 1376.6866,-196.997"/>
<polygon fill="#000000" stroke="#000000" points="1377.2367,-200.4671 1386.9664,-196.2739 1376.7454,-193.4843 1377.2367,-200.4671"/>
<text text-anchor="middle" x="796" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M974.1575,-359.114C1014.4085,-355.7221 1063.7596,-351.5982 1108,-348 1293.7425,-332.8929 1339.8484,-323.7215 1526,-315 1660.5339,-308.6969 2605.2857,-319.9351 2738,-297 2741.7136,-296.3582 2745.5183,-295.4978 2749.3013,-294.4998"/>
<polygon fill="#000000" stroke="#000000" points="2750.5812,-297.7716 2759.1871,-291.5919 2748.6058,-291.0561 2750.5812,-297.7716"/>
<text text-anchor="middle" x="1596" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="869" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="869" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M873.1249,-86.8025C876.5872,-75.6825 882.6791,-62.0883 893,-54 913.2961,-38.0943 980.0922,-27.8654 1026.0866,-22.522"/>
<polygon fill="#000000" stroke="#000000" points="1026.5895,-25.9876 1036.1362,-21.3931 1025.808,-19.0313 1026.5895,-25.9876"/>
<text text-anchor="middle" x="941.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2681" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2681" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2647.0796,-266.1616C2630.8023,-259.699 2611.1556,-251.453 2594,-243 2582.0331,-237.1036 2580.8296,-231.6574 2568,-228 2467.9321,-199.4735 1752.8815,-193.4839 1520.6459,-192.2859"/>
<polygon fill="#000000" stroke="#000000" points="1520.6297,-188.7858 1510.6122,-192.2356 1520.5945,-195.7858 1520.6297,-188.7858"/>
<text text-anchor="middle" x="2633.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1416.3559,-176.4461C1387.6666,-162.3446 1345.1534,-141.4483 1313.5065,-125.893"/>
<polygon fill="#000000" stroke="#000000" points="1314.9945,-122.7245 1304.476,-121.4543 1311.9066,-129.0066 1314.9945,-122.7245"/>
<text text-anchor="middle" x="1420.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_personnel -->
<g id="node14" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1034" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1034" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1008.5341,-87.7657C997.5062,-78.0957 988.6193,-65.663 996,-54 1003.4657,-42.2027 1015.9582,-34.1958 1028.6804,-28.7936"/>
<polygon fill="#000000" stroke="#000000" points="1030.2448,-31.9448 1038.3744,-25.1507 1027.7824,-25.3922 1030.2448,-31.9448"/>
<text text-anchor="middle" x="1065.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- generic_file -->
<g id="node15" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="84" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="84" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M83.1309,-347.6431C83.0803,-324.2027 86.7284,-283.939 110,-261 156.1441,-215.5154 187.7024,-235.9966 252,-228 459.5504,-202.1871 984.0605,-219.3665 1193,-210 1255.5294,-207.1969 1326.556,-202.0192 1377.7395,-197.9341"/>
<polygon fill="#000000" stroke="#000000" points="1378.3392,-201.3973 1388.0263,-197.1065 1377.7778,-194.4198 1378.3392,-201.3973"/>
<text text-anchor="middle" x="163" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M53.1985,-350.0985C29.2249,-335.2752 0,-310.7031 0,-279 0,-279 0,-279 0,-105 0,-52.7794 818.8086,-25.3849 1025.2065,-19.309"/>
<polygon fill="#000000" stroke="#000000" points="1025.5158,-22.8016 1035.4095,-19.0114 1025.3116,-15.8046 1025.5158,-22.8016"/>
<text text-anchor="middle" x="53" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M132.5966,-353.8544C143.2171,-351.5782 154.4402,-349.4587 165,-348 425.1615,-312.0612 492.5064,-323.5276 755,-315 865.1131,-311.4228 2629.3843,-315.4477 2738,-297 2741.7154,-296.369 2745.5214,-295.516 2749.3053,-294.5229"/>
<polygon fill="#000000" stroke="#000000" points="2750.5818,-297.796 2759.1924,-291.6228 2748.6116,-291.079 2750.5818,-297.796"/>
<text text-anchor="middle" x="808" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_response -->
<g id="node16" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="434" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="434" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M428.7595,-261.0207C426.7448,-249.9877 426.6262,-236.4085 435,-228 449.8619,-213.0765 1171.9619,-210.9918 1193,-210 1255.5227,-207.0526 1326.5501,-201.8896 1377.7355,-197.8468"/>
<polygon fill="#000000" stroke="#000000" points="1378.3318,-201.3105 1388.0227,-197.0283 1377.7766,-194.3326 1378.3318,-201.3105"/>
<text text-anchor="middle" x="518" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cell_line -->
<g id="node17" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2791" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2791" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge34" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2742.1649,-189.048C2653.8409,-183.5689 2461.7016,-171.0081 2300,-156 1837.5237,-113.0759 1279.0156,-44.0563 1117.6609,-23.7776"/>
<polygon fill="#000000" stroke="#000000" points="1117.9711,-20.2891 1107.6123,-22.5132 1117.0971,-27.2344 1117.9711,-20.2891"/>
<text text-anchor="middle" x="2002.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2789.025,-210.4051C2788.2106,-220.0991 2787.5503,-232.1886 2788,-243 2788.1012,-245.4321 2788.2406,-247.9542 2788.4044,-250.4832"/>
<polygon fill="#000000" stroke="#000000" points="2784.9332,-250.9974 2789.1791,-260.7043 2791.9132,-250.4683 2784.9332,-250.9974"/>
<text text-anchor="middle" x="2828.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- synonym -->
<g id="node18" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="226" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="226" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M221.5557,-347.8042C217.058,-324.5381 213.4831,-284.4626 235,-261 292.9293,-197.8322 339.7001,-236.3605 425,-228 764.7988,-194.6953 851.9492,-226.0249 1193,-210 1255.5232,-207.0622 1326.5505,-201.8983 1377.7357,-197.8526"/>
<polygon fill="#000000" stroke="#000000" points="1378.3323,-201.3163 1388.0229,-197.0335 1377.7767,-194.3384 1378.3323,-201.3163"/>
<text text-anchor="middle" x="277.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M186.0858,-354.4357C133.8565,-337.3261 52.7746,-302.7482 87,-261 235.2252,-80.1944 966.9013,-290.5118 1130,-123 1151.4493,-100.9703 1150.4328,-80.5935 1135,-54 1129.6334,-44.7524 1120.9003,-37.6797 1111.6229,-32.3561"/>
<polygon fill="#000000" stroke="#000000" points="1113.151,-29.2065 1102.6534,-27.7741 1109.9666,-35.4402 1113.151,-29.2065"/>
<text text-anchor="middle" x="1067.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M277.183,-362.6603C423.8996,-353.241 858.6035,-326.4095 1220,-315 1388.5945,-309.6774 2571.7424,-325.4757 2738,-297 2741.7145,-296.3638 2745.5199,-295.5073 2749.3034,-294.5118"/>
<polygon fill="#000000" stroke="#000000" points="2750.5816,-297.7843 2759.1899,-291.6079 2748.6088,-291.068 2750.5816,-297.7843"/>
<text text-anchor="middle" x="1262.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- pdx -->
<g id="node19" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3016" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3016" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2988.2874,-188.6142C2873.0432,-174.615 2420.3156,-120.424 2047,-87 1690.3669,-55.0696 1259.2578,-28.8997 1118.7241,-20.6864"/>
<polygon fill="#000000" stroke="#000000" points="1118.5253,-17.169 1108.3386,-20.0813 1118.118,-24.1571 1118.5253,-17.169"/>
<text text-anchor="middle" x="2426" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3041.8926,-198.8315C3069.6419,-207.3647 3107.4956,-223.2715 3090,-243 3085.9528,-247.5637 2928.8419,-264.6118 2844.0314,-273.5121"/>
<polygon fill="#000000" stroke="#000000" points="2843.6435,-270.0335 2834.0622,-274.5557 2844.3723,-276.9954 2843.6435,-270.0335"/>
<text text-anchor="middle" x="3118" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pathology_file -->
<g id="node20" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2627" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2627" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2628.8741,-347.8882C2630.9844,-336.8024 2635.4694,-323.2141 2645,-315 2676.8904,-287.5146 2697.3069,-307.7944 2738,-297 2741.3418,-296.1136 2744.7783,-295.1258 2748.2188,-294.0821"/>
<polygon fill="#000000" stroke="#000000" points="2749.3744,-297.3875 2757.8498,-291.03 2747.2597,-290.7146 2749.3744,-297.3875"/>
<text text-anchor="middle" x="2706" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- exposure -->
<g id="node21" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="610" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="610" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M604.7801,-261.0411C602.7736,-250.0162 602.6565,-236.4385 611,-228 633.7443,-204.9969 1160.6928,-211.6392 1193,-210 1255.4081,-206.8335 1326.3046,-201.7052 1377.474,-197.7309"/>
<polygon fill="#000000" stroke="#000000" points="1378.0628,-201.1956 1387.7596,-196.9269 1377.5172,-194.2169 1378.0628,-201.1956"/>
<text text-anchor="middle" x="654.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3125" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3125" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3124.7399,-347.8803C3123.5763,-336.7913 3120.1704,-323.2025 3111,-315 3072.768,-280.8031 3039.9096,-325.1048 2997,-297 2966.5742,-277.0718 2984.68,-245.8673 2953,-228 2921.485,-210.2258 1817.8313,-196.2587 1520.922,-192.8169"/>
<polygon fill="#000000" stroke="#000000" points="1520.7432,-189.3147 1510.7034,-192.6989 1520.6623,-196.3142 1520.7432,-189.3147"/>
<text text-anchor="middle" x="3083" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3145.9393,-348.2525C3162.5527,-332.0898 3183,-306.5925 3183,-279 3183,-279 3183,-279 3183,-105 3183,-51.504 1429.0288,-23.2477 1118.6528,-18.6663"/>
<polygon fill="#000000" stroke="#000000" points="1118.6907,-15.1666 1108.6404,-18.5194 1118.5879,-22.1658 1118.6907,-15.1666"/>
<text text-anchor="middle" x="3269" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3034.9932,-355.7704C3003.8392,-350.3665 2969.184,-342.2152 2939,-330 2927.6872,-325.4218 2927.0973,-320.0781 2916,-315 2892.0119,-304.023 2863.8892,-295.5681 2840.3997,-289.6191"/>
<polygon fill="#000000" stroke="#000000" points="2841.1882,-286.2088 2830.642,-287.2229 2839.5187,-293.0069 2841.1882,-286.2088"/>
<text text-anchor="middle" x="3025" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2811" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2811" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2786.6738,-348.5809C2781.1444,-343.299 2776.0163,-337.0125 2773,-330 2769.6766,-322.2735 2770.8829,-313.7098 2773.8559,-305.8408"/>
<polygon fill="#000000" stroke="#000000" points="2777.0716,-307.2274 2778.1727,-296.6899 2770.7407,-304.2408 2777.0716,-307.2274"/>
<text text-anchor="middle" x="2844.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_funding -->
<g id="node24" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3288" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3288" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3264.7048,-87.6574C3247.1101,-75.6657 3221.8268,-60.7077 3197,-54 3093.3711,-26.0014 1421.7749,-19.1568 1118.8731,-18.1442"/>
<polygon fill="#000000" stroke="#000000" points="1118.6917,-14.6436 1108.6801,-18.1106 1118.6685,-21.6436 1118.6917,-14.6436"/>
<text text-anchor="middle" x="3293" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_radiation -->
<g id="node25" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1129" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1144.0272,-260.8849C1154.5468,-249.5009 1169.6093,-235.5812 1186,-228 1218.9796,-212.746 1311.3353,-202.5926 1377.0363,-197.0639"/>
<polygon fill="#000000" stroke="#000000" points="1377.6596,-200.5245 1387.3388,-196.2162 1377.0855,-193.5481 1377.6596,-200.5245"/>
<text text-anchor="middle" x="1269" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- family_relationship -->
<g id="node26" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1352" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1352" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1352.3331,-260.6787C1353.4202,-250.0656 1356.3959,-237.0555 1364,-228 1371.1868,-219.4415 1380.778,-212.8673 1390.9064,-207.8333"/>
<polygon fill="#000000" stroke="#000000" points="1392.6052,-210.9078 1400.3055,-203.6306 1389.7478,-204.5175 1392.6052,-210.9078"/>
<text text-anchor="middle" x="1443.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node27" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1599" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1599" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1572.9608,-261.2585C1553.0415,-247.7322 1528.1387,-230.9373 1523,-228 1512.9138,-222.2347 1501.7613,-216.5382 1491.2085,-211.4365"/>
<polygon fill="#000000" stroke="#000000" points="1492.6651,-208.2536 1482.1311,-207.1195 1489.6587,-214.5752 1492.6651,-208.2536"/>
<text text-anchor="middle" x="1647" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- treatment_other -->
<g id="node28" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2362" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2362" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2321.9013,-262.8949C2290.1931,-250.9584 2244.5055,-235.5106 2203,-228 2073.5661,-204.5784 1683.8519,-195.7629 1520.8826,-193.0406"/>
<polygon fill="#000000" stroke="#000000" points="1520.5372,-189.5345 1510.4812,-192.87 1520.4224,-196.5336 1520.5372,-189.5345"/>
<text text-anchor="middle" x="2329.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- diagnosis -->
<g id="node29" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1895" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1895" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1848.2987,-356.4502C1820.2151,-349.8157 1788.0243,-340.3357 1778,-330 1745.2709,-296.2542 1785.6274,-258.6702 1750,-228 1732.8576,-213.2428 1603.3597,-202.1121 1519.5963,-196.3647"/>
<polygon fill="#000000" stroke="#000000" points="1519.5785,-192.8556 1509.3654,-195.6737 1519.1068,-199.8397 1519.5785,-192.8556"/>
<text text-anchor="middle" x="1809.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1939.7555,-355.3752C1993.2292,-343.194 2085.5699,-323.7804 2166,-315 2292.4229,-301.1987 2612.8677,-319.6965 2738,-297 2741.7081,-296.3274 2745.509,-295.4455 2749.2895,-294.4332"/>
<polygon fill="#000000" stroke="#000000" points="2750.579,-297.7015 2759.1714,-291.503 2748.5889,-290.9904 2750.579,-297.7015"/>
<text text-anchor="middle" x="2210.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node30" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2541" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2541" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2503.2251,-263.5084C2469.5118,-249.9669 2422.542,-231.8768 2403,-228 2317.477,-211.0339 1728.5349,-197.6582 1520.5478,-193.4153"/>
<polygon fill="#000000" stroke="#000000" points="1520.4131,-189.912 1510.3441,-193.2083 1520.271,-196.9105 1520.4131,-189.912"/>
<text text-anchor="middle" x="2505" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node31" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2200" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2200" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2224.8743,-348.5818C2243.3051,-336.7199 2269.5384,-321.9549 2295,-315 2390.0438,-289.0386 2641.1376,-315.0271 2738,-297 2741.6542,-296.3199 2745.3997,-295.4412 2749.1275,-294.4384"/>
<polygon fill="#000000" stroke="#000000" points="2750.2878,-297.7451 2758.8793,-291.5454 2748.2968,-291.0341 2750.2878,-297.7451"/>
<text text-anchor="middle" x="2361.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2760.9728,-265.6873C2727.5533,-250.9213 2677.6023,-229.0227 2673,-228 2560.9591,-203.1022 1767.5064,-194.6001 1520.9282,-192.543"/>
<polygon fill="#000000" stroke="#000000" points="1520.6736,-189.0409 1510.6451,-192.4583 1520.6159,-196.0406 1520.6736,-189.0409"/>
<text text-anchor="middle" x="2743.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2831.0375,-271.3418C2846.8935,-266.1364 2863.5632,-257.4492 2873,-243 2884.4412,-225.4818 2865.2375,-212.9231 2842.5496,-204.6518"/>
<polygon fill="#000000" stroke="#000000" points="2843.6383,-201.3254 2833.0445,-201.4754 2841.4196,-207.9645 2843.6383,-201.3254"/>
<text text-anchor="middle" x="2912.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2834.043,-274.8977C2867.7519,-270.4196 2915.116,-261.2811 2953,-243 2967.6856,-235.9134 2981.9842,-224.7932 2993.2373,-214.7428"/>
<polygon fill="#000000" stroke="#000000" points="2995.8971,-217.0499 3000.8551,-207.6867 2991.1403,-211.9145 2995.8971,-217.0499"/>
<text text-anchor="middle" x="3011.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
