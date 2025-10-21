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
<svg width="3444pt" height="392pt"
 viewBox="0.00 0.00 3444.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3440.1892,-388 3440.1892,4 -4,4"/>
<!-- cytogenomic_file -->
<g id="node1" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="211.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="211.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="902.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="902.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M224.4599,-347.9813C233.6351,-336.3272 247.2229,-322.0586 262.9954,-315 315.6943,-291.4159 703.5056,-282.4115 848.5006,-279.8468"/>
<polygon fill="#000000" stroke="#000000" points="848.5749,-283.3462 858.5127,-279.6732 848.4535,-276.3472 848.5749,-283.3462"/>
<text text-anchor="middle" x="334.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2366.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2366.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1790.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1790.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2319.0713,-265.1792C2277.1741,-253.5955 2214.5219,-237.4733 2158.9954,-228 2056.8571,-210.5743 1937.2238,-200.8113 1862.76,-195.9756"/>
<polygon fill="#000000" stroke="#000000" points="1862.7614,-192.4687 1852.5591,-195.3257 1862.3163,-199.4545 1862.7614,-192.4687"/>
<text text-anchor="middle" x="2286.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1221.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1221.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge32" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M51.9954,-347.6694C51.9954,-330.0629 51.9954,-302.7135 51.9954,-279 51.9954,-279 51.9954,-279 51.9954,-105 51.9954,-47.6657 957.2961,-23.8809 1175.2255,-18.9859"/>
<polygon fill="#000000" stroke="#000000" points="1175.4528,-22.4818 1185.3726,-18.7606 1175.2973,-15.4836 1175.4528,-22.4818"/>
<text text-anchor="middle" x="94.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M76.5528,-349.8932C96.3125,-337.8713 125.2637,-322.3114 152.9954,-315 219.6005,-297.4397 687.4637,-284.3363 848.608,-280.3003"/>
<polygon fill="#000000" stroke="#000000" points="848.8613,-283.7952 858.7712,-280.0477 848.6873,-276.7974 848.8613,-283.7952"/>
<text text-anchor="middle" x="195.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M67.4697,-348.3017C78.6256,-336.7906 94.7106,-322.5613 111.9954,-315 374.6884,-200.0838 1111.4822,-221.1167 1397.9954,-210 1510.1769,-205.6474 1640.3176,-199.4635 1719.108,-195.5944"/>
<polygon fill="#000000" stroke="#000000" points="1719.588,-199.0751 1729.4038,-195.0877 1719.2438,-192.0836 1719.588,-199.0751"/>
<text text-anchor="middle" x="361.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="770.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="770.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M778.1942,-86.7468C783.724,-75.3046 792.5413,-61.3718 804.9954,-54 836.2811,-35.4814 1073.4917,-23.9159 1175.5457,-19.7496"/>
<polygon fill="#000000" stroke="#000000" points="1175.7171,-23.2457 1185.5683,-19.3466 1175.4358,-16.2513 1175.7171,-23.2457"/>
<text text-anchor="middle" x="853.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pathology_file -->
<g id="node6" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="395.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="395.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M401.4231,-347.7724C405.8388,-336.3409 413.2919,-322.4105 424.9954,-315 460.0595,-292.7977 730.71,-283.3378 848.5109,-280.2428"/>
<polygon fill="#000000" stroke="#000000" points="848.8419,-283.7356 858.7487,-279.9798 848.662,-276.7379 848.8419,-283.7356"/>
<text text-anchor="middle" x="485.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- publication -->
<g id="node7" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="911.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="911.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge10" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M906.9409,-86.7864C905.1169,-75.9433 905.1372,-62.6545 912.9954,-54 930.3168,-34.9233 1093.5282,-24.2828 1175.4934,-20.102"/>
<polygon fill="#000000" stroke="#000000" points="1175.7334,-23.5945 1185.5467,-19.6008 1175.3848,-16.6032 1175.7334,-23.5945"/>
<text text-anchor="middle" x="963.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node8" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1034.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1034.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M966.0525,-354.7752C938.8951,-348.8384 912.2138,-340.5651 903.9954,-330 899.0805,-323.6816 897.5117,-315.4669 897.5388,-307.4827"/>
<polygon fill="#000000" stroke="#000000" points="901.0449,-307.5439 898.3466,-297.2984 894.0668,-306.9903 901.0449,-307.5439"/>
<text text-anchor="middle" x="973.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1045.2606,-347.7093C1060.1556,-323.1528 1090.2652,-280.3755 1128.9954,-261 1130.2114,-260.3916 1320.6459,-228.1668 1321.9954,-228 1462.2171,-210.6684 1627.123,-200.3203 1719.3012,-195.4325"/>
<polygon fill="#000000" stroke="#000000" points="1719.5528,-198.9243 1729.356,-194.9058 1719.1865,-191.9338 1719.5528,-198.9243"/>
<text text-anchor="middle" x="1198.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group -->
<g id="node9" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1328.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1328.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge29" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1307.5995,-87.6033C1290.7814,-73.9288 1267.2466,-54.793 1249.1092,-40.0458"/>
<polygon fill="#000000" stroke="#000000" points="1251.1661,-37.2073 1241.1991,-33.6143 1246.75,-42.6386 1251.1661,-37.2073"/>
<text text-anchor="middle" x="1344.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment -->
<g id="node10" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2657.9954" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2657.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2621.2589,-265.013C2587.6377,-252.8982 2536.2347,-236.0846 2489.9954,-228 2371.3759,-207.2602 2017.4535,-197.056 1863.6722,-193.5052"/>
<polygon fill="#000000" stroke="#000000" points="1863.4713,-189.9998 1853.3941,-193.271 1863.3117,-196.998 1863.4713,-189.9998"/>
<text text-anchor="middle" x="2596.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cell_line -->
<g id="node12" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1006.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1006.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M901.9723,-260.6401C902.3364,-250.0133 904.5408,-237.0025 911.9954,-228 922.1458,-215.7419 936.9435,-207.6526 951.8513,-202.3162"/>
<polygon fill="#000000" stroke="#000000" points="953.1589,-205.5727 961.616,-199.1908 951.025,-198.9058 953.1589,-205.5727"/>
<text text-anchor="middle" x="948.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M942.7486,-270.9607C1012.1842,-256.94 1149.25,-229.366 1159.9954,-228 1266.1223,-214.5089 1576.6735,-200.6834 1718.6555,-194.8603"/>
<polygon fill="#000000" stroke="#000000" points="1719.1434,-198.3434 1728.9923,-194.4383 1718.8578,-191.3492 1719.1434,-198.3434"/>
<text text-anchor="middle" x="1196.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="839.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="839.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M859.7043,-275.1208C817.9706,-270.3784 759.1192,-260.7039 744.9954,-243 726.2694,-219.5274 768.3084,-205.4468 802.3153,-198.2041"/>
<polygon fill="#000000" stroke="#000000" points="803.4092,-201.5552 812.5351,-196.1731 802.0447,-194.6895 803.4092,-201.5552"/>
<text text-anchor="middle" x="781.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1025.2553,-175.0965C1048.4016,-153.8881 1089.7781,-116.6982 1126.9954,-87 1148.2738,-70.0205 1173.2047,-51.9789 1192.1867,-38.604"/>
<polygon fill="#000000" stroke="#000000" points="1194.2757,-41.414 1200.455,-32.8078 1190.2575,-35.6821 1194.2757,-41.414"/>
<text text-anchor="middle" x="1167.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1002.8255,-209.9497C999.5356,-220.6935 993.9668,-233.9706 984.9954,-243 975.3023,-252.7556 962.518,-260.0676 949.9359,-265.4598"/>
<polygon fill="#000000" stroke="#000000" points="948.4266,-262.2927 940.4083,-269.2178 950.995,-268.8044 948.4266,-262.2927"/>
<text text-anchor="middle" x="1035.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="572.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="572.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M559.0871,-348.1351C552.5233,-337.4232 547.7457,-324.1498 555.9954,-315 575.1991,-293.7009 755.9241,-284.2125 848.658,-280.7172"/>
<polygon fill="#000000" stroke="#000000" points="848.8378,-284.213 858.7029,-280.349 848.5814,-277.2177 848.8378,-284.213"/>
<text text-anchor="middle" x="622.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node14" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2833.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2833.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2787.2371,-263.0183C2750.0021,-251.0655 2696.2968,-235.5373 2647.9954,-228 2497.7083,-204.548 2041.5538,-195.6006 1863.3874,-192.9427"/>
<polygon fill="#000000" stroke="#000000" points="1863.3803,-189.4423 1853.3299,-192.7949 1863.2774,-196.4415 1863.3803,-189.4423"/>
<text text-anchor="middle" x="2794.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node15" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1568.9954" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1568.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1569.0137,-347.8319C1567.9786,-336.5766 1564.6112,-322.8217 1554.9954,-315 1505.5937,-274.8157 1316.3053,-339.6272 1268.9954,-297 1197.5162,-232.5957 1207.9046,-103.4103 1216.7269,-46.282"/>
<polygon fill="#000000" stroke="#000000" points="1220.2205,-46.6065 1218.3908,-36.1709 1213.3134,-45.4698 1220.2205,-46.6065"/>
<text text-anchor="middle" x="1304.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1471.8026,-357.8588C1388.0688,-350.449 1273.824,-339.2828 1228.9954,-330 1207.109,-325.4679 1202.8401,-319.7291 1180.9954,-315 1117.5265,-301.2599 1100.3948,-305.3548 1035.9954,-297 1009.3066,-293.5376 979.6274,-289.5354 955.0887,-286.1854"/>
<polygon fill="#000000" stroke="#000000" points="955.2927,-282.6808 944.9106,-284.793 954.3439,-289.6162 955.2927,-282.6808"/>
<text text-anchor="middle" x="1314.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1664.5239,-357.3544C1752.3558,-347.5519 1874.2021,-328.6695 1909.9954,-297 1933.7313,-275.9987 1947.3496,-253.097 1927.9954,-228 1918.9216,-216.2338 1887.8886,-207.5543 1857.6491,-201.6692"/>
<polygon fill="#000000" stroke="#000000" points="1857.9276,-198.1613 1847.4572,-199.7801 1856.6518,-205.0441 1857.9276,-198.1613"/>
<text text-anchor="middle" x="2020.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- survival -->
<g id="node16" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2999.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2999.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2972.3535,-264.0235C2948.2251,-251.7974 2911.8654,-235.3797 2877.9954,-228 2779.6515,-206.5725 2091.0494,-195.8649 1863.6673,-192.8847"/>
<polygon fill="#000000" stroke="#000000" points="1863.5584,-189.3831 1853.5138,-192.7528 1863.4674,-196.3825 1863.5584,-189.3831"/>
<text text-anchor="middle" x="2961.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- generic_file -->
<g id="node17" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2475.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2475.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2541.0618,-363.2937C2696.389,-355.9675 3075.9954,-332.5819 3075.9954,-279 3075.9954,-279 3075.9954,-279 3075.9954,-105 3075.9954,-58.3249 1556.4621,-24.8563 1268.7114,-18.9368"/>
<polygon fill="#000000" stroke="#000000" points="1268.6826,-15.4356 1258.613,-18.73 1268.5392,-22.4341 1268.6826,-15.4356"/>
<text text-anchor="middle" x="3128.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2412.8239,-360.8583C2283.0948,-350.4937 1977.2189,-327.0556 1719.9954,-315 1416.2236,-300.7627 1339.1179,-321.4284 1035.9954,-297 1008.9667,-294.8218 979.0273,-290.9042 954.409,-287.2788"/>
<polygon fill="#000000" stroke="#000000" points="954.6166,-283.7709 944.2081,-285.7489 953.5783,-290.6935 954.6166,-283.7709"/>
<text text-anchor="middle" x="2021.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2476.3335,-347.9558C2475.7757,-324.8536 2471.3283,-284.9551 2448.9954,-261 2417.3684,-227.0758 2395.5141,-236.8973 2349.9954,-228 2258.927,-210.1993 1993.0067,-198.9329 1863.5214,-194.3503"/>
<polygon fill="#000000" stroke="#000000" points="1863.4243,-190.8449 1853.3079,-193.9927 1863.1793,-197.8406 1863.4243,-190.8449"/>
<text text-anchor="middle" x="2520.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_funding -->
<g id="node18" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1503.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1503.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1478.4826,-87.9407C1460.58,-76.7148 1435.6976,-62.5638 1411.9954,-54 1364.4599,-36.825 1307.1253,-27.4004 1267.9561,-22.5503"/>
<polygon fill="#000000" stroke="#000000" points="1268.2535,-19.0611 1257.9105,-21.3573 1267.428,-26.0122 1268.2535,-19.0611"/>
<text text-anchor="middle" x="1504.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node19" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="789.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="789.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M724.4208,-351.1579C701.5351,-342.9048 684.549,-331.0135 697.9954,-315 716.8781,-292.5123 794.4108,-284.068 848.5131,-280.8995"/>
<polygon fill="#000000" stroke="#000000" points="848.8636,-284.3857 858.6597,-280.3503 848.4851,-277.396 848.8636,-284.3857"/>
<text text-anchor="middle" x="789.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1302.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1302.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1251.7836,-359.5946C1208.7558,-353.6584 1145.8413,-343.6786 1091.9954,-330 1071.9707,-324.9131 1067.8171,-320.8278 1047.9954,-315 1016.3025,-305.6819 980.2558,-296.7251 952.0315,-290.0764"/>
<polygon fill="#000000" stroke="#000000" points="952.5436,-286.6019 942.0095,-287.7349 950.951,-293.4183 952.5436,-286.6019"/>
<text text-anchor="middle" x="1136.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1343.9014,-353.9548C1367.3288,-344.9669 1389.605,-331.4305 1375.9954,-315 1348.5825,-281.9054 1308.4082,-330.0946 1280.9954,-297 1270.789,-284.6781 1270.6386,-273.1958 1280.9954,-261 1308.9673,-228.0612 1585.9167,-205.5013 1719.5631,-196.4445"/>
<polygon fill="#000000" stroke="#000000" points="1719.9662,-199.9254 1729.7097,-195.7642 1719.4979,-192.9411 1719.9662,-199.9254"/>
<text text-anchor="middle" x="1325.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge33" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1737.8219,-182.4509C1665.4167,-169.3824 1531.7883,-145.0306 1417.9954,-123 1411.6982,-121.7809 1405.1546,-120.4946 1398.6019,-119.1932"/>
<polygon fill="#000000" stroke="#000000" points="1398.823,-115.6684 1388.3314,-117.1434 1397.4529,-122.533 1398.823,-115.6684"/>
<text text-anchor="middle" x="1641.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1431.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1431.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1454.3992,-262.4722C1471.2864,-250.8855 1495.4827,-236.0774 1518.9954,-228 1555.1502,-215.5796 1652.8961,-204.5819 1720.7856,-198.1055"/>
<polygon fill="#000000" stroke="#000000" points="1721.3647,-201.5666 1730.9924,-197.1443 1720.7083,-194.5974 1721.3647,-201.5666"/>
<text text-anchor="middle" x="1562.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_response -->
<g id="node23" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1607.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1607.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1607.2689,-260.6274C1607.8557,-249.7244 1610.5153,-236.4285 1618.9954,-228 1633.5382,-213.5458 1680.2286,-204.3454 1721.298,-198.8666"/>
<polygon fill="#000000" stroke="#000000" points="1721.845,-202.3252 1731.321,-197.5864 1720.9581,-195.3816 1721.845,-202.3252"/>
<text text-anchor="middle" x="1701.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M863.7148,-182.4288C892.9121,-170.2469 943.5879,-147.7873 983.9954,-123 1006.4241,-109.2414 1007.9059,-99.6184 1030.9954,-87 1079.4818,-60.5022 1140.1838,-40.5884 1179.9738,-29.1279"/>
<polygon fill="#000000" stroke="#000000" points="1180.9506,-32.489 1189.6192,-26.3975 1179.044,-25.7537 1180.9506,-32.489"/>
<text text-anchor="middle" x="1054.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M836.1816,-210.1741C834.9937,-220.4821 835.2437,-233.2321 840.9954,-243 845.5801,-250.7861 852.5501,-257.0512 860.1841,-262.0318"/>
<polygon fill="#000000" stroke="#000000" points="858.934,-265.3505 869.3474,-267.3028 862.4244,-259.2827 858.934,-265.3505"/>
<text text-anchor="middle" x="864.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_personnel -->
<g id="node25" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3190.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3190.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3164.8524,-87.6667C3145.1812,-75.6796 3117.0666,-60.7234 3089.9954,-54 2999.0362,-31.4093 1549.3559,-20.2639 1268.8017,-18.3131"/>
<polygon fill="#000000" stroke="#000000" points="1268.5883,-14.8117 1258.5644,-18.2424 1268.5399,-21.8115 1268.5883,-14.8117"/>
<text text-anchor="middle" x="3196.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- laboratory_test -->
<g id="node26" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1960.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1960.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1886.7954,-358.2533C1779.6473,-347.2918 1575.3148,-327.2307 1400.9954,-315 1238.9743,-303.6321 1197.7294,-311.905 1035.9954,-297 1008.9935,-294.5116 979.0565,-290.5658 954.4329,-287.002"/>
<polygon fill="#000000" stroke="#000000" points="954.6318,-283.4937 944.2293,-285.5034 953.6145,-290.4194 954.6318,-283.4937"/>
<text text-anchor="middle" x="1650.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2014.2873,-352.2389C2070.5968,-335.1234 2146.9206,-302.965 2112.9954,-261 2082.0401,-222.7087 1946.9655,-204.708 1861.8977,-197.0282"/>
<polygon fill="#000000" stroke="#000000" points="1862.0491,-193.5281 1851.7818,-196.1421 1861.4382,-200.5014 1862.0491,-193.5281"/>
<text text-anchor="middle" x="2186.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_admin -->
<g id="node27" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3365.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3365.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3341.6671,-87.9098C3323.0169,-75.876 3296.1243,-60.7541 3269.9954,-54 3170.0405,-28.1624 1565.7559,-19.5755 1269.0063,-18.2048"/>
<polygon fill="#000000" stroke="#000000" points="1268.625,-14.7032 1258.609,-18.1573 1268.5929,-21.7031 1268.625,-14.7032"/>
<text text-anchor="middle" x="3362.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node28" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1815.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1815.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1801.1083,-260.9864C1797.4267,-255.5325 1793.9728,-249.3075 1791.9954,-243 1789.7626,-235.878 1788.8915,-227.9176 1788.7277,-220.4429"/>
<polygon fill="#000000" stroke="#000000" points="1792.2289,-220.3951 1788.8986,-210.3373 1785.2299,-220.2766 1792.2289,-220.3951"/>
<text text-anchor="middle" x="1859.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
