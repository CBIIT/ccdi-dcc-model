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
<svg width="3354pt" height="392pt"
 viewBox="0.00 0.00 3354.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3350,-388 3350,4 -4,4"/>
<!-- radiology_file -->
<g id="node1" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="406" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="406" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1434" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1434" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M394.911,-260.7477C389.8775,-249.8901 386.6933,-236.5995 395,-228 411.7868,-210.6215 1127.8227,-197.1222 1361.257,-193.1764"/>
<polygon fill="#000000" stroke="#000000" points="1361.4042,-196.6745 1371.3439,-193.0068 1361.2865,-189.6755 1361.4042,-196.6745"/>
<text text-anchor="middle" x="454" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- generic_file -->
<g id="node2" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="84" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="84" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1013" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1013" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M53.1985,-350.0985C29.2249,-335.2752 0,-310.7031 0,-279 0,-279 0,-279 0,-105 0,-62.9905 19.2252,-72.2542 124,-54 288.0041,-25.4267 806.0731,-19.4482 965.7066,-18.2722"/>
<polygon fill="#000000" stroke="#000000" points="966.1589,-21.7692 976.1339,-18.1986 966.1094,-14.7694 966.1589,-21.7692"/>
<text text-anchor="middle" x="53" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2790" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2790" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M148.4885,-362.6025C222.3075,-358.7739 346.854,-352.4989 454,-348 869.0045,-330.5746 972.7528,-325.1049 1388,-315 1537.8579,-311.3533 2589.2681,-322.4157 2737,-297 2740.714,-296.361 2744.5191,-295.5026 2748.3024,-294.5058"/>
<polygon fill="#000000" stroke="#000000" points="2749.5814,-297.778 2758.1885,-291.6 2747.6073,-291.0621 2749.5814,-297.778"/>
<text text-anchor="middle" x="1441" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M79.5722,-347.8193C75.0922,-324.5695 71.5366,-284.5115 93,-261 149.3098,-199.3168 194.9297,-236.6561 278,-228 489.4571,-205.9659 1142.0867,-195.7516 1361.3191,-192.8795"/>
<polygon fill="#000000" stroke="#000000" points="1361.474,-196.3779 1371.4277,-192.7483 1361.3831,-189.3785 1361.474,-196.3779"/>
<text text-anchor="middle" x="146" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="718" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="718" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M744.1846,-261.4714C763.2316,-249.7203 790.1139,-235.1367 816,-228 867.3684,-213.8379 1210.029,-200.0133 1361.8372,-194.5024"/>
<polygon fill="#000000" stroke="#000000" points="1362.1262,-197.9944 1371.9934,-194.1358 1361.8736,-190.9989 1362.1262,-197.9944"/>
<text text-anchor="middle" x="895.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_funding -->
<g id="node5" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="105" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="105" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M113.8525,-86.9963C120.6365,-75.3488 131.1804,-61.0821 145,-54 181.7484,-35.1676 790.9896,-22.2081 966.2098,-18.8574"/>
<polygon fill="#000000" stroke="#000000" points="966.4645,-22.3533 976.3963,-18.6642 966.3316,-15.3546 966.4645,-22.3533"/>
<text text-anchor="middle" x="207" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1493" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1493" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1538.601,-355.9264C1596.486,-343.6525 1699.5817,-323.5027 1789,-315 1998.7585,-295.0544 2529.4476,-333.3103 2737,-297 2740.7122,-296.3506 2744.516,-295.4848 2748.2984,-294.4832"/>
<polygon fill="#000000" stroke="#000000" points="2749.5808,-297.7542 2758.1833,-291.5697 2747.6017,-291.0397 2749.5808,-297.7542"/>
<text text-anchor="middle" x="1833.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1444.3634,-357.6287C1414.7499,-351.4295 1380.9427,-341.9908 1372,-330 1353.6661,-305.4172 1361.0247,-289.6354 1372,-261 1378.6346,-243.6899 1391.838,-227.9961 1404.3615,-215.9648"/>
<polygon fill="#000000" stroke="#000000" points="1406.9945,-218.2996 1412.0066,-208.9653 1402.2675,-213.1367 1406.9945,-218.2996"/>
<text text-anchor="middle" x="1416.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2529" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2529" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2485.9151,-263.3257C2450.6906,-251.2911 2399.3197,-235.5036 2353,-228 2190.5896,-201.6902 1694.11,-194.4102 1506.6707,-192.5715"/>
<polygon fill="#000000" stroke="#000000" points="1506.6756,-189.0715 1496.6425,-192.4755 1506.6085,-196.0712 1506.6756,-189.0715"/>
<text text-anchor="middle" x="2484" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2759.9728,-265.687C2726.5534,-250.9208 2676.6025,-229.022 2672,-228 2558.6379,-202.8269 1755.0635,-194.5036 1506.8502,-192.5179"/>
<polygon fill="#000000" stroke="#000000" points="1506.5293,-189.0154 1496.502,-192.4362 1506.474,-196.0151 1506.5293,-189.0154"/>
<text text-anchor="middle" x="2742.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node30" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2790" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2790" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2788.1791,-260.7043C2787.6947,-255.0358 2787.2398,-248.7649 2787,-243 2786.6979,-235.7361 2786.8968,-227.8952 2787.3068,-220.5916"/>
<polygon fill="#000000" stroke="#000000" points="2790.813,-220.6265 2788.025,-210.4051 2783.8303,-220.1342 2790.813,-220.6265"/>
<text text-anchor="middle" x="2823.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node31" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2982" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2982" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2830.8103,-272.0601C2857.0107,-266.5487 2891.2079,-257.3396 2919,-243 2932.7865,-235.8867 2946.3822,-225.4422 2957.3948,-215.8546"/>
<polygon fill="#000000" stroke="#000000" points="2959.8276,-218.3739 2964.9229,-209.0847 2955.1469,-213.1689 2959.8276,-218.3739"/>
<text text-anchor="middle" x="2977.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node9" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2220" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2220" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2236.9035,-348.0908C2249.2523,-336.3251 2267.0845,-321.8809 2286,-315 2380.2591,-280.7113 2638.3846,-315.3166 2737,-297 2740.6545,-296.3212 2744.4001,-295.4434 2748.128,-294.4413"/>
<polygon fill="#000000" stroke="#000000" points="2749.2879,-297.7481 2757.88,-291.5492 2747.2976,-291.0369 2749.2879,-297.7481"/>
<text text-anchor="middle" x="2377.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2680" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2680" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2647.5088,-265.5553C2611.1749,-250.5325 2557.2056,-228.2584 2556,-228 2454.0747,-206.1541 1738.8744,-195.6789 1506.6397,-192.8267"/>
<polygon fill="#000000" stroke="#000000" points="1506.6481,-189.3267 1496.6062,-192.7046 1506.5628,-196.3262 1506.6481,-189.3267"/>
<text text-anchor="middle" x="2629.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="287" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="287" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M276.9504,-86.7445C272.4644,-75.8856 269.8158,-62.5948 278,-54 301.7642,-29.0433 807.7133,-20.5809 966.0594,-18.5383"/>
<polygon fill="#000000" stroke="#000000" points="966.4587,-22.0336 976.4137,-18.4076 966.3703,-15.0342 966.4587,-22.0336"/>
<text text-anchor="middle" x="347.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2443" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2443" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2455.5049,-348.0703C2464.698,-336.4559 2478.2908,-322.1983 2494,-315 2543.2261,-292.4436 2683.9386,-307.7931 2737,-297 2740.6424,-296.2591 2744.3795,-295.3378 2748.1018,-294.3065"/>
<polygon fill="#000000" stroke="#000000" points="2749.2814,-297.6065 2757.8448,-291.368 2747.2601,-290.9047 2749.2814,-297.6065"/>
<text text-anchor="middle" x="2565.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- exposure -->
<g id="node13" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="261" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="261" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M269.168,-260.9764C275.5049,-249.3201 285.4919,-235.0509 299,-228 346.0854,-203.4226 1118.3915,-194.7118 1361.4009,-192.572"/>
<polygon fill="#000000" stroke="#000000" points="1361.5718,-196.0707 1371.541,-192.4838 1361.5109,-189.071 1361.5718,-196.0707"/>
<text text-anchor="middle" x="342.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- synonym -->
<g id="node14" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="515" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="515" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge44" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M464.1266,-361.7288C353.5493,-351.9303 99.1603,-326.403 74,-297 63.5974,-284.8433 64.301,-273.7251 74,-261 130.4501,-186.9376 790.4428,-59.4334 968.8056,-26.1421"/>
<polygon fill="#000000" stroke="#000000" points="969.4502,-29.5823 978.6406,-24.3108 968.1689,-22.7005 969.4502,-29.5823"/>
<text text-anchor="middle" x="334.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M566.9657,-364.9213C742.8114,-361.1416 1314.7426,-347.7587 1498,-330 1540.546,-325.8771 1550.4133,-318.6787 1593,-315 1719.6552,-304.0594 2611.7396,-318.7039 2737,-297 2740.7133,-296.3566 2744.5178,-295.4951 2748.3007,-294.4962"/>
<polygon fill="#000000" stroke="#000000" points="2749.5811,-297.7679 2758.1863,-291.5872 2747.605,-291.0526 2749.5811,-297.7679"/>
<text text-anchor="middle" x="1635.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M510.4868,-348.0665C505.7911,-324.7102 501.8715,-284.1405 524,-261 552.8702,-230.8094 1151.8993,-203.5284 1361.9713,-194.8567"/>
<polygon fill="#000000" stroke="#000000" points="1362.1275,-198.3533 1371.9753,-194.4457 1361.84,-191.3592 1362.1275,-198.3533"/>
<text text-anchor="middle" x="566.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node15" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="965" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="965" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M969.7362,-260.8289C973.7134,-249.4213 980.6225,-235.4963 992,-228 1022.0635,-208.1922 1244.1611,-198.1109 1361.6207,-194.1172"/>
<polygon fill="#000000" stroke="#000000" points="1361.7395,-197.6152 1371.6171,-193.7834 1361.5058,-190.6191 1361.7395,-197.6152"/>
<text text-anchor="middle" x="1094" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- publication -->
<g id="node16" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="809" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="809" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge26" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M817.693,-86.995C824.0165,-75.8066 833.6293,-62.065 846,-54 865.7394,-41.1309 925.3137,-30.3679 967.6671,-24.0545"/>
<polygon fill="#000000" stroke="#000000" points="968.369,-27.4893 977.7603,-22.5849 967.3604,-20.5623 968.369,-27.4893"/>
<text text-anchor="middle" x="897" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment_response -->
<g id="node17" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1217" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1217" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1205.5558,-260.629C1200.5298,-249.9983 1197.3153,-236.9872 1205,-228 1215.3651,-215.8781 1300.6991,-204.9649 1364.1837,-198.4114"/>
<polygon fill="#000000" stroke="#000000" points="1364.5748,-201.8898 1374.1701,-197.3975 1363.8677,-194.9256 1364.5748,-201.8898"/>
<text text-anchor="middle" x="1288" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sequencing_file -->
<g id="node18" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2634" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2634" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2635.54,-347.9594C2637.4413,-336.9019 2641.6613,-323.3185 2651,-315 2680.1596,-289.0259 2699.3318,-307.2978 2737,-297 2740.335,-296.0883 2743.7666,-295.0823 2747.2037,-294.0259"/>
<polygon fill="#000000" stroke="#000000" points="2748.3678,-297.3284 2756.8287,-290.9515 2746.2378,-290.6603 2748.3678,-297.3284"/>
<text text-anchor="middle" x="2717.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- laboratory_test -->
<g id="node19" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1997" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1997" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2029.4309,-349.394C2054.734,-337.3573 2091.1526,-322.0122 2125,-315 2258.2298,-287.3987 2603.1006,-321.1446 2737,-297 2740.7088,-296.3312 2744.5102,-295.452 2748.291,-294.4414"/>
<polygon fill="#000000" stroke="#000000" points="2749.5794,-297.7102 2758.1734,-291.514 2747.5911,-290.9985 2749.5794,-297.7102"/>
<text text-anchor="middle" x="2190.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1936.0097,-353.9353C1919.5377,-348.5758 1902.5436,-340.9119 1889,-330 1861.2221,-307.6196 1875.0842,-284.2151 1848,-261 1797.805,-217.9755 1610.7649,-201.2769 1506.0956,-195.2002"/>
<polygon fill="#000000" stroke="#000000" points="1506.1021,-191.6951 1495.9213,-194.6278 1505.7089,-198.684 1506.1021,-191.6951"/>
<text text-anchor="middle" x="1933.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="950" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="950" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M948.8851,-86.7328C949.0968,-76.3938 950.8468,-63.6438 957,-54 961.8258,-46.4366 968.8739,-40.1501 976.3529,-35.0614"/>
<polygon fill="#000000" stroke="#000000" points="978.5204,-37.8384 985.2231,-29.6332 974.8666,-31.8676 978.5204,-37.8384"/>
<text text-anchor="middle" x="1005.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- consent_group -->
<g id="node21" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1107" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1107" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge1" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1089.0426,-87.3263C1078.8694,-77.4138 1065.8452,-64.8889 1054,-54 1049.2405,-49.6247 1044.1046,-45.0236 1039.1314,-40.628"/>
<polygon fill="#000000" stroke="#000000" points="1041.3514,-37.9196 1031.5276,-33.9519 1036.733,-43.1798 1041.3514,-37.9196"/>
<text text-anchor="middle" x="1132.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3122" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3122" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3140.4797,-348.1568C3155.426,-331.7401 3174,-305.9226 3174,-279 3174,-279 3174,-279 3174,-105 3174,-50.181 1374.6791,-22.9662 1059.753,-18.6228"/>
<polygon fill="#000000" stroke="#000000" points="1059.6485,-15.1211 1049.6015,-18.4836 1059.5525,-22.1204 1059.6485,-15.1211"/>
<text text-anchor="middle" x="3260" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3031.9932,-355.7704C3000.8392,-350.3665 2966.184,-342.2152 2936,-330 2924.6872,-325.4218 2924.0863,-320.1021 2913,-315 2889.583,-304.2231 2862.1694,-295.8274 2839.1728,-289.8649"/>
<polygon fill="#000000" stroke="#000000" points="2839.8326,-286.4219 2829.2809,-287.3779 2838.1257,-293.2106 2839.8326,-286.4219"/>
<text text-anchor="middle" x="3022" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3121.7614,-347.8562C3120.6064,-336.7576 3117.2019,-323.1671 3108,-315 3067.6652,-279.2013 3036.1518,-321.2867 2988,-297 2949.2774,-277.4692 2958.8639,-245.081 2919,-228 2853.5842,-199.9704 1796.5783,-193.5119 1506.907,-192.2652"/>
<polygon fill="#000000" stroke="#000000" points="1506.5374,-188.7637 1496.5227,-192.2213 1506.5078,-195.7636 1506.5374,-188.7637"/>
<text text-anchor="middle" x="3074" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge35" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1372.0398,-189.4923C1282.4407,-185.2266 1125.4496,-175.1025 1108,-156 1102.4565,-149.9314 1100.8012,-141.5596 1100.9433,-133.3523"/>
<polygon fill="#000000" stroke="#000000" points="1104.4432,-133.5219 1101.9273,-123.2302 1097.4761,-132.8446 1104.4432,-133.5219"/>
<text text-anchor="middle" x="1158.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node24" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2811" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2811" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2798.7907,-348.0569C2795.6443,-342.5068 2792.6751,-336.2129 2791,-330 2789.057,-322.7935 2788.285,-314.8043 2788.1235,-307.3289"/>
<polygon fill="#000000" stroke="#000000" points="2791.6243,-307.279 2788.2434,-297.2382 2784.6248,-307.1959 2791.6243,-307.279"/>
<text text-anchor="middle" x="2852" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- treatment_surgery -->
<g id="node25" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1740" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1740" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1686.3487,-263.7462C1630.725,-247.9316 1544.2367,-223.3418 1488.3546,-207.4538"/>
<polygon fill="#000000" stroke="#000000" points="1489.2092,-204.0581 1478.6332,-204.6898 1487.2948,-210.7912 1489.2092,-204.0581"/>
<text text-anchor="middle" x="1683.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- genetic_analysis -->
<g id="node26" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1795" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1795" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1829.8148,-349.4581C1857.1773,-337.3702 1896.6179,-321.9288 1933,-315 2108.5562,-281.5663 2561.0148,-328.0962 2737,-297 2740.7111,-296.3443 2744.5141,-295.4741 2748.296,-294.4696"/>
<polygon fill="#000000" stroke="#000000" points="2749.5803,-297.7398 2758.1801,-291.5515 2747.5983,-291.0263 2749.5803,-297.7398"/>
<text text-anchor="middle" x="2003" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1774.6532,-348.3343C1759.9591,-336.6802 1739.069,-322.2694 1718,-315 1670.3739,-298.5676 1534.3397,-324.3061 1492,-297 1477.6752,-287.7615 1457.9544,-247.404 1445.5959,-219.5032"/>
<polygon fill="#000000" stroke="#000000" points="1448.7563,-217.9942 1441.5525,-210.2253 1442.3392,-220.7908 1448.7563,-217.9942"/>
<text text-anchor="middle" x="1562" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_status -->
<g id="node27" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1359" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1359" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1326.6184,-88.9826C1302.4579,-77.6495 1268.3501,-62.9353 1237,-54 1176.7314,-36.8225 1104.8524,-27.0911 1059.0752,-22.1854"/>
<polygon fill="#000000" stroke="#000000" points="1059.1788,-18.6774 1048.8707,-21.1256 1058.4556,-25.64 1059.1788,-18.6774"/>
<text text-anchor="middle" x="1334.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- study_admin -->
<g id="node28" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1517" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1517" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1485.7936,-88.8599C1461.6636,-77.1516 1427.0709,-62.017 1395,-54 1332.5892,-38.3986 1146.9013,-25.8463 1059.4854,-20.6232"/>
<polygon fill="#000000" stroke="#000000" points="1059.516,-17.119 1049.327,-20.0228 1059.103,-24.1068 1059.516,-17.119"/>
<text text-anchor="middle" x="1495.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_radiation -->
<g id="node29" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="2129" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2129" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2069.7173,-264.1466C2021.38,-252.5825 1951.1788,-237.027 1889,-228 1754.5961,-208.4875 1596.2109,-198.9659 1506.2015,-194.8035"/>
<polygon fill="#000000" stroke="#000000" points="1506.2529,-191.3023 1496.1047,-194.3458 1505.9359,-198.2951 1506.2529,-191.3023"/>
<text text-anchor="middle" x="2051" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge18" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2761.9295,-191.5821C2557.0524,-188.4305 1298.1046,-167.2995 1232,-123 1203.9184,-104.1813 1226.635,-74.8157 1200,-54 1178.5826,-37.2619 1107.5268,-27.1735 1059.4367,-22.0981"/>
<polygon fill="#000000" stroke="#000000" points="1059.5535,-18.592 1049.2505,-21.0612 1058.8446,-25.556 1059.5535,-18.592"/>
<text text-anchor="middle" x="1256" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2816.7431,-197.4564C2833.4546,-202.3969 2853.6953,-211.5275 2864,-228 2874.2974,-244.4608 2857.098,-256.9694 2836.701,-265.4785"/>
<polygon fill="#000000" stroke="#000000" points="2835.2872,-262.2717 2827.1917,-269.1065 2837.7824,-268.8119 2835.2872,-262.2717"/>
<text text-anchor="middle" x="2891" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge9" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2934.8856,-186.2625C2904.182,-182.5892 2863.2366,-177.8142 2827,-174 2262.7164,-114.604 2121.5787,-99.4388 1556,-54 1372.1876,-39.2325 1153.0159,-26.0565 1059.2543,-20.6296"/>
<polygon fill="#000000" stroke="#000000" points="1059.4319,-17.1341 1049.2469,-20.0522 1059.0287,-24.1225 1059.4319,-17.1341"/>
<text text-anchor="middle" x="2375.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3020.8474,-203.1226C3045.6965,-212.1564 3070.7323,-226.1396 3056,-243 3052.5061,-246.9987 2919.0787,-263.5604 2842.5583,-272.7632"/>
<polygon fill="#000000" stroke="#000000" points="2842.1244,-269.29 2832.6125,-273.9564 2842.9583,-276.2402 2842.1244,-269.29"/>
<text text-anchor="middle" x="3100.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_other -->
<g id="node32" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2339" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2339" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2290.8094,-263.9145C2250.4304,-251.9685 2191.0417,-236.0051 2138,-228 2017.9321,-209.8793 1660.995,-198.2201 1506.556,-193.8932"/>
<polygon fill="#000000" stroke="#000000" points="1506.3297,-190.3857 1496.2364,-193.6066 1506.1353,-197.383 1506.3297,-190.3857"/>
<text text-anchor="middle" x="2279.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
</g>
</svg>
</div>
