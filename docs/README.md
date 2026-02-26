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
<svg width="3835pt" height="392pt"
 viewBox="0.00 0.00 3835.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3831.3431,-388 3831.3431,4 -4,4"/>
<!-- sequencing_file -->
<g id="node1" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2265" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2265" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node9" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2873" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2873" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2290.0491,-348.8248C2308.9123,-336.9162 2335.9026,-321.9891 2362,-315 2460.3892,-288.6507 2719.8507,-315.57 2820,-297 2823.6547,-296.3223 2827.4004,-295.4453 2831.1285,-294.4437"/>
<polygon fill="#000000" stroke="#000000" points="2832.288,-297.7506 2840.8806,-291.5525 2830.2982,-291.0393 2832.288,-297.7506"/>
<text text-anchor="middle" x="2428.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2672" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2672" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node29" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3033" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3033" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2687.1551,-87.2918C2698.0977,-75.7762 2713.907,-61.5457 2731,-54 2775.6589,-34.2853 2913.3587,-24.2687 2986.3957,-20.2258"/>
<polygon fill="#000000" stroke="#000000" points="2986.8863,-23.7046 2996.6837,-19.6722 2986.5101,-16.7147 2986.8863,-23.7046"/>
<text text-anchor="middle" x="2779.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment_other -->
<g id="node3" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="1143" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1143" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- participant -->
<g id="node31" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1664" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1664" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1167.7762,-261.6582C1185.8173,-249.9952 1211.317,-235.44 1236,-228 1300.5168,-208.5533 1487.2585,-198.6219 1591.4917,-194.4629"/>
<polygon fill="#000000" stroke="#000000" points="1591.767,-197.9549 1601.6224,-194.0665 1591.4932,-190.9603 1591.767,-197.9549"/>
<text text-anchor="middle" x="1305.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- study_personnel -->
<g id="node4" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2837" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2837" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2832.1514,-86.9671C2830.4048,-76.1921 2830.4343,-62.9112 2838,-54 2856.7084,-31.9646 2934.7823,-23.3476 2986.2863,-20.0267"/>
<polygon fill="#000000" stroke="#000000" points="2986.7521,-23.5051 2996.5248,-19.413 2986.3333,-16.5177 2986.7521,-23.5051"/>
<text text-anchor="middle" x="2907.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node5" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="156" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="156" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M193.4221,-353.4696C201.1415,-351.307 209.274,-349.3301 217,-348 484.5711,-301.934 555.6275,-323.5615 827,-315 937.6717,-311.5084 2710.8362,-315.5383 2820,-297 2823.7154,-296.369 2827.5214,-295.5162 2831.3053,-294.5231"/>
<polygon fill="#000000" stroke="#000000" points="2832.5818,-297.7962 2841.1925,-291.6231 2830.6116,-291.0792 2832.5818,-297.7962"/>
<text text-anchor="middle" x="869.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M107.0686,-359.4906C61.319,-350.3314 0,-328.7716 0,-279 0,-279 0,-279 0,-105 0,-88.9998 139.4403,-69.9267 367,-54 637.9392,-35.0372 2652.927,-20.5857 2986.3359,-18.3123"/>
<polygon fill="#000000" stroke="#000000" points="2986.622,-21.8106 2996.598,-18.2426 2986.5744,-14.8107 2986.622,-21.8106"/>
<text text-anchor="middle" x="42.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M157.5733,-347.629C160.5741,-324.1733 169.226,-283.8932 194,-261 234.624,-223.4601 259.2875,-236.1299 314,-228 440.2991,-209.2329 1329.1785,-196.3377 1591.3712,-192.9103"/>
<polygon fill="#000000" stroke="#000000" points="1591.5872,-196.4078 1601.5408,-192.778 1591.4961,-189.4084 1591.5872,-196.4078"/>
<text text-anchor="middle" x="236.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2482" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2482" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2487.9829,-347.9287C2492.8133,-336.4092 2500.8362,-322.3178 2513,-315 2571.5591,-279.7707 2752.9292,-310.1066 2820,-297 2823.648,-296.2871 2827.389,-295.3854 2831.1139,-294.3673"/>
<polygon fill="#000000" stroke="#000000" points="2832.2847,-297.6704 2840.8611,-291.4498 2830.2774,-290.9643 2832.2847,-297.6704"/>
<text text-anchor="middle" x="2604.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node7" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1377" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1377" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1375.6393,-260.9261C1375.8536,-249.8554 1378.18,-236.2697 1387,-228 1401.8123,-214.1119 1515.8009,-202.9874 1592.8596,-196.9547"/>
<polygon fill="#000000" stroke="#000000" points="1593.3018,-200.4311 1603.0033,-196.1731 1592.764,-193.4517 1593.3018,-200.4311"/>
<text text-anchor="middle" x="1489" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_admin -->
<g id="node8" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3282" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3282" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3258.4917,-87.8083C3242.2348,-76.6708 3219.7039,-62.6747 3198,-54 3159.1397,-38.4681 3112.3196,-29.0647 3078.4963,-23.7843"/>
<polygon fill="#000000" stroke="#000000" points="3078.8484,-20.298 3068.4398,-22.2757 3077.8099,-27.2206 3078.8484,-20.298"/>
<text text-anchor="middle" x="3283.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2944" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2944" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge34" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2898.3408,-264.2139C2906.6899,-258.4134 2915.4923,-251.177 2922,-243 2927.5497,-236.0268 2931.9597,-227.4413 2935.3296,-219.3166"/>
<polygon fill="#000000" stroke="#000000" points="2938.6745,-220.3658 2938.9309,-209.7741 2932.1254,-217.8941 2938.6745,-220.3658"/>
<text text-anchor="middle" x="2966.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node21" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3075" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3075" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2914.0094,-272.1973C2941.3013,-266.6698 2977.4349,-257.3904 3007,-243 3021.8775,-235.7586 3036.7673,-225.077 3048.8047,-215.3578"/>
<polygon fill="#000000" stroke="#000000" points="3051.1957,-217.9217 3056.6474,-208.8371 3046.7203,-212.5391 3051.1957,-217.9217"/>
<text text-anchor="middle" x="3066.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2842.9721,-265.6902C2809.552,-250.9269 2759.6005,-229.031 2755,-228 2656.3672,-205.895 1964.4032,-195.6309 1736.5553,-192.8242"/>
<polygon fill="#000000" stroke="#000000" points="1736.4244,-189.3224 1726.3824,-192.7001 1736.3389,-196.3219 1736.4244,-189.3224"/>
<text text-anchor="middle" x="2826.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- publication -->
<g id="node10" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge42" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3409.6962,-88.1215C3392.4291,-76.5207 3367.8526,-61.8463 3344,-54 3295.982,-38.2045 3153.5634,-26.3576 3079.2699,-21.0599"/>
<polygon fill="#000000" stroke="#000000" points="3079.4766,-17.5659 3069.2558,-20.3561 3078.9858,-24.5486 3079.4766,-17.5659"/>
<text text-anchor="middle" x="3428" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- laboratory_test -->
<g id="node11" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="917" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="917" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M992.7276,-359.1352C1122.3133,-347.706 1394.9818,-325.0421 1626,-315 1758.5566,-309.2379 2689.2588,-319.6092 2820,-297 2823.7135,-296.3578 2827.5181,-295.4971 2831.3012,-294.4989"/>
<polygon fill="#000000" stroke="#000000" points="2832.5812,-297.7707 2841.1869,-291.5907 2830.6056,-291.0552 2832.5812,-297.7707"/>
<text text-anchor="middle" x="1691.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M853.8396,-354.3817C828.4982,-348.3207 803.5014,-340.0582 796,-330 783.61,-313.387 782.0154,-286.4674 809,-261 865.3251,-207.8417 1394.6943,-195.5142 1591.1148,-192.7608"/>
<polygon fill="#000000" stroke="#000000" points="1591.3823,-196.2576 1601.3338,-192.622 1591.2872,-189.2582 1591.3823,-196.2576"/>
<text text-anchor="middle" x="874.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- generic_file -->
<g id="node12" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="292" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="292" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M355.8692,-361.7391C511.1215,-351.5794 920.7048,-325.9632 1263,-315 1435.9229,-309.4615 2649.4672,-326.1819 2820,-297 2823.7146,-296.3644 2827.5201,-295.5082 2831.3036,-294.513"/>
<polygon fill="#000000" stroke="#000000" points="2832.5816,-297.7855 2841.1902,-291.6095 2830.6091,-291.0692 2832.5816,-297.7855"/>
<text text-anchor="middle" x="1316" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M246.1751,-352.8959C195.5229,-335.2699 121,-298.6131 121,-235.5 121,-235.5 121,-235.5 121,-105 121,-30.1487 2612.2911,-19.3335 2986.252,-18.1317"/>
<polygon fill="#000000" stroke="#000000" points="2986.4566,-21.6312 2996.4456,-18.0997 2986.4346,-14.6312 2986.4566,-21.6312"/>
<text text-anchor="middle" x="174" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M286.6805,-347.8553C281.0996,-324.6444 275.7855,-284.6285 297,-261 360.4122,-190.3723 413.4936,-236.8275 508,-228 719.6805,-208.2276 1372.1639,-196.5333 1591.3392,-193.0821"/>
<polygon fill="#000000" stroke="#000000" points="1591.5011,-196.5801 1601.4451,-192.924 1591.3915,-189.581 1591.5011,-196.5801"/>
<text text-anchor="middle" x="350" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2917.7114,-198.2657C2902.1372,-203.4641 2883.619,-212.5786 2874,-228 2869.8756,-234.6123 2868.4686,-242.705 2868.3981,-250.479"/>
<polygon fill="#000000" stroke="#000000" points="2864.9188,-250.9365 2869.0007,-260.7134 2871.9067,-250.525 2864.9188,-250.9365"/>
<text text-anchor="middle" x="2898" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2952.7435,-174.4996C2963.1924,-153.6275 2981.243,-117.7021 2997,-87 3004.1777,-73.0144 3012.2668,-57.4895 3018.9564,-44.713"/>
<polygon fill="#000000" stroke="#000000" points="3022.2171,-46.0313 3023.7609,-35.5495 3016.0176,-42.7808 3022.2171,-46.0313"/>
<text text-anchor="middle" x="3021" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1357" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1357" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1409.4475,-360.6792C1517.1599,-349.9866 1771.1571,-325.9783 1985,-315 2170.3546,-305.4843 2637.2192,-329.2186 2820,-297 2823.7114,-296.3458 2827.5146,-295.4767 2831.2966,-294.4729"/>
<polygon fill="#000000" stroke="#000000" points="2832.5804,-297.7433 2841.1809,-291.556 2830.5991,-291.0296 2832.5804,-297.7433"/>
<text text-anchor="middle" x="2029.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1320.0833,-352.6899C1285.4216,-340.7771 1231.8774,-323.8645 1184,-315 1082.454,-296.1987 890.1314,-338.8392 958,-261 999.0947,-213.8682 1419.3574,-198.0913 1591.2863,-193.5836"/>
<polygon fill="#000000" stroke="#000000" points="1591.5999,-197.0768 1601.5068,-193.3213 1591.4202,-190.0791 1591.5999,-197.0768"/>
<text text-anchor="middle" x="1002.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_radiation -->
<g id="node15" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="517" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="517" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M511.693,-260.5472C509.7739,-249.614 509.783,-236.3145 518,-228 536.9223,-208.8532 1342.552,-196.3547 1591.4931,-192.9443"/>
<polygon fill="#000000" stroke="#000000" points="1591.5693,-196.4437 1601.5207,-192.8077 1591.4739,-189.4443 1591.5693,-196.4437"/>
<text text-anchor="middle" x="601" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- exposure -->
<g id="node16" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="693" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="693" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M687.7979,-261.0586C685.7985,-250.0408 685.6826,-236.4642 694,-228 709.6963,-212.0268 1368.4643,-197.7529 1591.2485,-193.3746"/>
<polygon fill="#000000" stroke="#000000" points="1591.5939,-196.8686 1601.5235,-193.1736 1591.4569,-189.8699 1591.5939,-196.8686"/>
<text text-anchor="middle" x="737.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node17" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2692" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2692" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2693.7937,-347.7935C2695.8719,-336.6699 2700.3514,-323.0751 2710,-315 2747.9899,-283.2055 2771.9379,-309.0064 2820,-297 2823.4029,-296.1499 2826.8997,-295.1818 2830.3965,-294.1457"/>
<polygon fill="#000000" stroke="#000000" points="2831.6735,-297.4135 2840.1725,-291.0876 2829.5836,-290.7328 2831.6735,-297.4135"/>
<text text-anchor="middle" x="2771" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- consent_group -->
<g id="node18" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2062" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2062" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge39" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2134.029,-97.41C2233.5675,-87.0256 2418.8203,-68.0747 2577,-54 2726.8158,-40.6695 2904.5504,-27.3588 2986.8888,-21.3352"/>
<polygon fill="#000000" stroke="#000000" points="2987.2018,-24.8217 2996.9204,-20.6029 2986.6921,-17.8403 2987.2018,-24.8217"/>
<text text-anchor="middle" x="2640.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- genetic_analysis -->
<g id="node19" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1890" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1890" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1950.3249,-352.8313C2009.1249,-340.6211 2101.229,-323.1498 2182,-315 2323.1177,-300.7612 2680.4019,-322.0859 2820,-297 2823.7092,-296.3335 2827.5109,-295.4558 2831.2919,-294.4462"/>
<polygon fill="#000000" stroke="#000000" points="2832.5795,-297.7153 2841.1745,-291.5204 2830.5923,-291.0032 2832.5795,-297.7153"/>
<text text-anchor="middle" x="2252" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1824.4214,-353.9448C1802.2765,-348.4073 1777.8899,-340.6383 1757,-330 1736.1558,-319.3849 1726.1016,-318.0978 1716,-297 1705.6338,-275.3496 1716.334,-266.9949 1717,-243 1717.185,-236.3359 1720.1202,-233.8914 1717,-228 1714.1318,-222.5844 1710.0433,-217.8324 1705.3928,-213.7093"/>
<polygon fill="#000000" stroke="#000000" points="1707.2089,-210.6901 1697.1517,-207.3578 1702.9358,-216.2345 1707.2089,-210.6901"/>
<text text-anchor="middle" x="1786" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- radiology_file -->
<g id="node20" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1598" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1598" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1594.1122,-260.7818C1592.8996,-250.4591 1593.1496,-237.7091 1599,-228 1602.9364,-221.4673 1608.5217,-216.0318 1614.7843,-211.5352"/>
<polygon fill="#000000" stroke="#000000" points="1617.0424,-214.2504 1623.6527,-205.9706 1613.3219,-208.3209 1617.0424,-214.2504"/>
<text text-anchor="middle" x="1658" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3110.5747,-204.6985C3131.72,-214.1733 3152.0876,-228.0218 3139,-243 3135.5061,-246.9987 3002.0787,-263.5604 2925.5583,-272.7632"/>
<polygon fill="#000000" stroke="#000000" points="2925.1244,-269.29 2915.6125,-273.9564 2925.9583,-276.2402 2925.1244,-269.29"/>
<text text-anchor="middle" x="3183.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3070.6635,-174.0343C3063.3383,-143.6874 3048.4638,-82.0644 3039.7599,-46.0052"/>
<polygon fill="#000000" stroke="#000000" points="3043.1246,-45.0282 3037.3759,-36.1286 3036.3201,-46.6707 3043.1246,-45.0282"/>
<text text-anchor="middle" x="3098.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node22" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1913" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1913" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1877.5888,-266.6274C1834.6293,-251.6175 1761.9512,-226.2239 1713.4744,-209.2862"/>
<polygon fill="#000000" stroke="#000000" points="1714.4122,-205.9065 1703.8174,-205.9121 1712.1033,-212.5147 1714.4122,-205.9065"/>
<text text-anchor="middle" x="1843.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2876" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2876" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2851.6738,-348.5809C2846.1444,-343.299 2841.0163,-337.0125 2838,-330 2833.8841,-320.4311 2837.9123,-310.7916 2844.5037,-302.5088"/>
<polygon fill="#000000" stroke="#000000" points="2847.2021,-304.746 2851.4266,-295.0298 2842.065,-299.9909 2847.2021,-304.746"/>
<text text-anchor="middle" x="2909.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment_response -->
<g id="node24" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2084" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2084" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2029.9693,-263.5602C1990.5639,-252.6559 1935.7535,-238.2228 1887,-228 1834.8341,-217.0617 1775.2029,-207.5908 1730.7371,-201.1122"/>
<polygon fill="#000000" stroke="#000000" points="1731.0304,-197.6184 1720.6328,-199.6535 1730.0301,-204.5465 1731.0304,-197.6184"/>
<text text-anchor="middle" x="2030" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- family_relationship -->
<g id="node25" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2307" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2307" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2257.9453,-263.1764C2219.9004,-251.5549 2165.6343,-236.387 2117,-228 1983.9344,-205.0527 1826.3117,-196.6976 1736.4465,-193.6801"/>
<polygon fill="#000000" stroke="#000000" points="1736.4714,-190.1792 1726.3636,-193.3545 1736.2454,-197.1755 1736.4714,-190.1792"/>
<text text-anchor="middle" x="2265.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node26" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3190" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3190" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3099.9932,-355.7704C3068.8392,-350.3665 3034.184,-342.2152 3004,-330 2992.6872,-325.4218 2991.99,-320.3064 2981,-315 2961.6758,-305.6695 2939.3165,-297.7779 2919.9725,-291.7831"/>
<polygon fill="#000000" stroke="#000000" points="2920.7485,-288.3614 2910.1637,-288.8234 2918.7263,-295.063 2920.7485,-288.3614"/>
<text text-anchor="middle" x="3090" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3209.1269,-348.115C3221.4173,-335.2458 3236.2947,-316.7372 3243,-297 3248.1468,-281.8504 3246.3872,-276.6374 3243,-261 3231.2546,-206.7759 3196.3643,-141.3189 3143,-87 3121.6163,-65.2338 3092.0948,-47.1955 3069.0184,-35.0277"/>
<polygon fill="#000000" stroke="#000000" points="3070.3799,-31.7924 3059.8854,-30.3383 3067.1825,-38.0195 3070.3799,-31.7924"/>
<text text-anchor="middle" x="3312" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3189.703,-347.9213C3188.5246,-336.8487 3185.1161,-323.2627 3176,-315 3140.9186,-283.2027 3112.6332,-319.5488 3071,-297 3034.2206,-277.08 3045.1083,-245.242 3007,-228 2948.8441,-201.6876 2007.9013,-194.0506 1736.65,-192.3907"/>
<polygon fill="#000000" stroke="#000000" points="1736.5427,-188.8901 1726.5218,-192.3296 1736.5004,-195.89 1736.5427,-188.8901"/>
<text text-anchor="middle" x="3157" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment_surgery -->
<g id="node27" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2524" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2524" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2479.3451,-262.8787C2444.3745,-251.0169 2394.2401,-235.6745 2349,-228 2232.9356,-208.3108 1887.5828,-197.5615 1736.323,-193.6871"/>
<polygon fill="#000000" stroke="#000000" points="1736.2945,-190.1853 1726.209,-193.4309 1736.1171,-197.1831 1736.2945,-190.1853"/>
<text text-anchor="middle" x="2491.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- medical_history -->
<g id="node28" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2726" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2726" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2680.671,-263.749C2636.129,-248.769 2574.6973,-228.1281 2574,-228 2492.75,-213.078 1937.6787,-198.5271 1736.5653,-193.6864"/>
<polygon fill="#000000" stroke="#000000" points="1736.4814,-190.1835 1726.4004,-193.4427 1736.3136,-197.1815 1736.4814,-190.1835"/>
<text text-anchor="middle" x="2684" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_status -->
<g id="node30" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="3584" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3584" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge38" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3557.7286,-88.1525C3537.9934,-76.4068 3509.8552,-61.5399 3483,-54 3408.118,-32.976 3178.859,-22.9126 3079.6097,-19.4516"/>
<polygon fill="#000000" stroke="#000000" points="3079.6873,-15.9523 3069.5736,-19.1088 3079.4483,-22.9482 3079.6873,-15.9523"/>
<text text-anchor="middle" x="3576.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge44" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1714.004,-181.0695C1785.0804,-165.5327 1915.4923,-137.0255 1994.9087,-119.6657"/>
<polygon fill="#000000" stroke="#000000" points="1995.7882,-123.0562 2004.81,-117.5013 1994.2933,-116.2176 1995.7882,-123.0562"/>
<text text-anchor="middle" x="1937.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node32" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3750" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3750" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3720.8538,-88.2688C3698.6408,-76.4182 3666.8837,-61.3683 3637,-54 3531.578,-28.0064 3202.556,-20.5183 3079.8009,-18.5987"/>
<polygon fill="#000000" stroke="#000000" points="3079.6555,-15.0962 3069.6038,-18.4448 3079.5498,-22.0954 3079.6555,-15.0962"/>
<text text-anchor="middle" x="3740" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
</g>
</svg>
</div>
