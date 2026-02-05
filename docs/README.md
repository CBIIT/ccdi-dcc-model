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
<svg width="3605pt" height="392pt"
 viewBox="0.00 0.00 3605.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3601,-388 3601,4 -4,4"/>
<!-- pdx -->
<g id="node1" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="33" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="33" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node13" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="482" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="482" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M57.9056,-357.7732C92.5499,-346.6085 157.4137,-326.7116 214,-315 287.6355,-299.7597 374.0438,-289.4972 428.4139,-283.9498"/>
<polygon fill="#000000" stroke="#000000" points="428.9146,-287.4173 438.515,-282.9359 428.2154,-280.4523 428.9146,-287.4173"/>
<text text-anchor="middle" x="238" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node19" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1202" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1202" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M22.3769,-349.0566C12.73,-332.0255 0,-304.6852 0,-279 0,-279 0,-279 0,-105 0,-46.0096 933.1112,-23.4315 1155.0457,-18.8957"/>
<polygon fill="#000000" stroke="#000000" points="1155.4429,-22.3885 1165.3702,-18.6873 1155.3016,-15.3899 1155.4429,-22.3885"/>
<text text-anchor="middle" x="24" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pathology_file -->
<g id="node2" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="352" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="352" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge44" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M372.8492,-348.4998C389.1117,-334.909 409.6501,-317.8976 414,-315 423.4479,-308.7065 434.1168,-302.6242 444.1549,-297.3063"/>
<polygon fill="#000000" stroke="#000000" points="445.8715,-300.3589 453.1431,-292.6534 442.6534,-294.1425 445.8715,-300.3589"/>
<text text-anchor="middle" x="475" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- treatment_radiation -->
<g id="node3" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="2959" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2959" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- participant -->
<g id="node25" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1542" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1542" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2910.5986,-262.9874C2871.7304,-250.9326 2815.496,-235.2834 2765,-228 2651.5869,-211.6417 1860.4961,-197.2837 1614.694,-193.1755"/>
<polygon fill="#000000" stroke="#000000" points="1614.5002,-189.6719 1604.4433,-193.0048 1614.3836,-196.6709 1614.5002,-189.6719"/>
<text text-anchor="middle" x="2918" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- survival -->
<g id="node4" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="592" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="592" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M616.7685,-263.3491C637.3695,-251.242 667.9197,-235.3439 697,-228 770.6971,-209.3887 1278.0041,-197.3323 1469.2562,-193.4032"/>
<polygon fill="#000000" stroke="#000000" points="1469.5604,-196.8978 1479.4869,-193.1946 1469.4176,-189.8993 1469.5604,-196.8978"/>
<text text-anchor="middle" x="736.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2319" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2319" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2241.6399,-359.9142C2098.6457,-348.9248 1783.2551,-325.9004 1517,-315 1407.9619,-310.536 642.503,-315.7707 535,-297 531.2876,-296.3518 527.4836,-295.4869 523.7011,-294.4858"/>
<polygon fill="#000000" stroke="#000000" points="524.3976,-291.0423 513.8161,-291.5733 522.4192,-297.7569 524.3976,-291.0423"/>
<text text-anchor="middle" x="1868.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2329.8248,-347.8442C2341.675,-325.3436 2356.6696,-286.8209 2338,-261 2310.5775,-223.0734 2284.0015,-236.6188 2238,-228 2120.2198,-205.9327 1768.0371,-196.462 1614.6878,-193.3059"/>
<polygon fill="#000000" stroke="#000000" points="1614.5063,-189.8016 1604.4375,-193.0983 1614.3645,-196.8002 1614.5063,-189.8016"/>
<text text-anchor="middle" x="2411.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- methylation_array_file -->
<g id="node6" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="562" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="562" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M557.205,-347.9989C553.7287,-337.4993 548.1833,-324.4961 540,-315 534.3837,-308.4827 527.2887,-302.7668 520.0053,-297.9218"/>
<polygon fill="#000000" stroke="#000000" points="521.7939,-294.9128 511.446,-292.6386 518.1171,-300.8694 521.7939,-294.9128"/>
<text text-anchor="middle" x="640.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node7" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="732" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="732" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M752.2375,-261.6388C767.3477,-249.8043 789.0876,-235.0489 811,-228 872.4543,-208.231 1297.0035,-197.1623 1469.4404,-193.4387"/>
<polygon fill="#000000" stroke="#000000" points="1469.7645,-196.9326 1479.6874,-193.2196 1469.6148,-189.9342 1469.7645,-196.9326"/>
<text text-anchor="middle" x="870" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_status -->
<g id="node8" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="780" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="780" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M799.4911,-87.4807C813.5837,-75.8938 833.6513,-61.5031 854,-54 908.1729,-34.0251 1073.8153,-23.8639 1155.4833,-19.9568"/>
<polygon fill="#000000" stroke="#000000" points="1155.6602,-23.4525 1165.486,-19.4895 1155.3335,-16.4601 1155.6602,-23.4525"/>
<text text-anchor="middle" x="910.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_surgery -->
<g id="node9" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="922" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="922" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M925.973,-260.789C929.4815,-249.3646 935.8396,-235.4358 947,-228 968.4154,-213.7316 1315.8293,-199.9002 1469.6648,-194.4424"/>
<polygon fill="#000000" stroke="#000000" points="1470.0856,-197.9298 1479.956,-194.0795 1469.8388,-190.9342 1470.0856,-197.9298"/>
<text text-anchor="middle" x="1025.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="946" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="946" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M956.8092,-87.038C964.5957,-75.7187 976.1479,-61.8135 990,-54 1017.6642,-38.3956 1102.2126,-27.6304 1155.8047,-22.1653"/>
<polygon fill="#000000" stroke="#000000" points="1156.4797,-25.6155 1166.0843,-21.1431 1155.787,-18.6499 1156.4797,-25.6155"/>
<text text-anchor="middle" x="1052" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2751" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2751" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2700.1508,-361.9265C2572.2299,-351.8712 2226.6514,-325.8985 1938,-315 1782.2093,-309.1179 688.6513,-323.3934 535,-297 531.2858,-296.362 527.4806,-295.5042 523.6973,-294.5079"/>
<polygon fill="#000000" stroke="#000000" points="524.3921,-291.0641 513.811,-291.6027 522.4185,-297.7802 524.3921,-291.0641"/>
<text text-anchor="middle" x="2270.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2797.047,-357.4027C2883.5906,-341.0694 3062.7854,-306.3479 3073,-297 3094.1044,-277.6862 3092,-264.108 3092,-235.5 3092,-235.5 3092,-235.5 3092,-105 3092,-57.3699 1539.6583,-24.6153 1248.6897,-18.8942"/>
<polygon fill="#000000" stroke="#000000" points="1248.5523,-15.3909 1238.4857,-18.6945 1248.4152,-22.3896 1248.5523,-15.3909"/>
<text text-anchor="middle" x="3134.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2751.2916,-347.9989C2750.6836,-324.9433 2746.1818,-285.095 2724,-261 2693.7269,-228.1158 2672.9449,-236.1655 2629,-228 2530.0426,-209.6125 1841.849,-196.8808 1614.6205,-193.1394"/>
<polygon fill="#000000" stroke="#000000" points="1614.5299,-189.6375 1604.4739,-192.9733 1614.4152,-196.6366 1614.5299,-189.6375"/>
<text text-anchor="middle" x="2785.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1124" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1124" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1113.5605,-260.866C1108.8496,-250.0529 1105.939,-236.7675 1114,-228 1137.485,-202.4567 1353.0789,-195.0262 1469.0096,-192.873"/>
<polygon fill="#000000" stroke="#000000" points="1469.2896,-196.3686 1479.226,-192.6921 1469.1656,-189.3697 1469.2896,-196.3686"/>
<text text-anchor="middle" x="1182" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M439.1072,-283.5308C402.653,-287.3236 348.9192,-292.7777 302,-297 252.0421,-301.4958 121.7347,-292.3106 77,-315 65.7071,-320.7277 56.0955,-330.7343 48.7633,-340.3754"/>
<polygon fill="#000000" stroke="#000000" points="45.8373,-338.4512 42.9217,-348.637 51.5529,-342.4926 45.8373,-338.4512"/>
<text text-anchor="middle" x="113.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M513.01,-266.0589C527.3208,-259.6957 544.3474,-251.5615 559,-243 568.9032,-237.2136 569.1448,-231.704 580,-228 663.1708,-199.6209 1259.0218,-193.5734 1468.9983,-192.3189"/>
<polygon fill="#000000" stroke="#000000" points="1469.3189,-195.8172 1479.2984,-192.2593 1469.2783,-188.8173 1469.3189,-195.8172"/>
<text text-anchor="middle" x="616.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node32" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="499" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="499" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M482.242,-260.8916C482.6673,-251.0674 483.6784,-238.7654 486,-228 486.584,-225.2921 487.3225,-222.5115 488.1497,-219.7537"/>
<polygon fill="#000000" stroke="#000000" points="491.5476,-220.6299 491.4169,-210.0358 484.9125,-218.3991 491.5476,-220.6299"/>
<text text-anchor="middle" x="522.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1278" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1278" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1272.4991,-86.6383C1268.7488,-76.2677 1262.9988,-63.5177 1255,-54 1249.6159,-47.5935 1242.8188,-41.8432 1235.9044,-36.9169"/>
<polygon fill="#000000" stroke="#000000" points="1237.4489,-33.7414 1227.1809,-31.1301 1233.5793,-39.5746 1237.4489,-33.7414"/>
<text text-anchor="middle" x="1312.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1763" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1763" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1711.383,-359.7929C1616.9853,-348.7139 1410.1114,-325.6951 1235,-315 1079.6824,-305.5138 688.188,-324.3306 535,-297 531.29,-296.3381 527.4877,-295.4636 523.7063,-294.4562"/>
<polygon fill="#000000" stroke="#000000" points="524.4051,-291.0131 513.8231,-291.5337 522.4201,-297.7258 524.4051,-291.0131"/>
<text text-anchor="middle" x="1468.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1816.6665,-362.1481C1935.5016,-353.074 2212.5476,-328.7093 2240,-297 2250.4726,-284.9035 2244.9479,-276.2157 2240,-261 2234.3918,-243.7536 2231.9353,-236.6576 2216,-228 2164.2693,-199.895 1778.4103,-193.7307 1614.8899,-192.3793"/>
<polygon fill="#000000" stroke="#000000" points="1614.4738,-188.876 1604.4465,-192.297 1614.4186,-195.8758 1614.4738,-188.876"/>
<text text-anchor="middle" x="2289.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_personnel -->
<g id="node16" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1443" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1443" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1421.0211,-87.5121C1406.0283,-76.393 1385.2822,-62.5327 1365,-54 1326.9925,-38.0103 1280.8827,-28.674 1247.4173,-23.5345"/>
<polygon fill="#000000" stroke="#000000" points="1247.863,-20.0625 1237.4604,-22.0715 1246.8454,-26.9881 1247.863,-20.0625"/>
<text text-anchor="middle" x="1461.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1456" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1456" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1464.7392,-261.1765C1470.4212,-250.7398 1478.5251,-237.7405 1488,-228 1492.909,-222.9534 1498.6386,-218.2257 1504.4959,-213.9618"/>
<polygon fill="#000000" stroke="#000000" points="1506.8246,-216.6086 1513.0881,-208.0634 1502.8628,-210.8375 1506.8246,-216.6086"/>
<text text-anchor="middle" x="1531.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1627" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1627" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1609.3879,-260.9735C1596.9151,-248.2072 1580.0266,-230.9214 1566.2771,-216.8484"/>
<polygon fill="#000000" stroke="#000000" points="1568.5014,-214.1166 1559.0095,-209.4097 1563.4944,-219.0085 1568.5014,-214.1166"/>
<text text-anchor="middle" x="1668.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node20" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="785" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="785" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M773.1027,-348.1542C764.3224,-336.5772 751.2771,-322.3299 736,-315 655.1352,-276.2014 622.751,-315.5528 535,-297 531.4139,-296.2418 527.734,-295.3163 524.0658,-294.2892"/>
<polygon fill="#000000" stroke="#000000" points="525.0407,-290.9275 514.4555,-291.3784 523.0115,-297.627 525.0407,-290.9275"/>
<text text-anchor="middle" x="827.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- consent_group -->
<g id="node21" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1121" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1121" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge9" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1117.7023,-86.5343C1116.853,-76.1291 1117.603,-63.3791 1124,-54 1132.1825,-42.003 1145.4241,-33.9242 1158.6928,-28.5185"/>
<polygon fill="#000000" stroke="#000000" points="1160.0809,-31.7382 1168.2873,-25.037 1157.6931,-25.158 1160.0809,-31.7382"/>
<text text-anchor="middle" x="1187.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_response -->
<g id="node22" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1850" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1850" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1822.3022,-261.6209C1803.218,-250.402 1776.9025,-236.3856 1752,-228 1706.66,-212.7324 1653.5316,-203.7029 1612.0573,-198.5053"/>
<polygon fill="#000000" stroke="#000000" points="1612.3945,-195.0207 1602.047,-197.2964 1611.5552,-201.9702 1612.3945,-195.0207"/>
<text text-anchor="middle" x="1868" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1618" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1618" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1596.1197,-87.7923C1580.1277,-76.1925 1557.4052,-61.6577 1535,-54 1483.13,-36.2717 1327.0479,-25.1302 1248.3843,-20.4891"/>
<polygon fill="#000000" stroke="#000000" points="1248.4591,-16.9877 1238.2734,-19.9033 1248.0542,-23.976 1248.4591,-16.9877"/>
<text text-anchor="middle" x="1622.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- genetic_analysis -->
<g id="node24" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1205" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1205" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1149.918,-351.9024C1130.8308,-346.1618 1109.5738,-338.7871 1091,-330 1079.9682,-324.781 1079.6377,-318.6744 1068,-315 954.9873,-279.3178 651.5849,-318.2847 535,-297 531.2927,-296.3232 527.4923,-295.4383 523.7121,-294.424"/>
<polygon fill="#000000" stroke="#000000" points="524.4134,-290.9813 513.8309,-291.4907 522.4213,-297.6918 524.4134,-290.9813"/>
<text text-anchor="middle" x="1161" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1219.6269,-348.0089C1223.6822,-342.4575 1227.8352,-336.1748 1231,-330 1245.7439,-301.2328 1230.1744,-282.8467 1254,-261 1285.7595,-231.8783 1399.3951,-211.3113 1474.0746,-200.581"/>
<polygon fill="#000000" stroke="#000000" points="1474.9283,-203.9954 1484.3411,-199.1324 1473.9502,-197.064 1474.9283,-203.9954"/>
<text text-anchor="middle" x="1324" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge40" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1491.2176,-181.5058C1415.8771,-165.9366 1274.3169,-136.6831 1189.7561,-119.2085"/>
<polygon fill="#000000" stroke="#000000" points="1190.236,-115.7338 1179.7346,-117.1376 1188.8194,-122.589 1190.236,-115.7338"/>
<text text-anchor="middle" x="1406.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node26" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="976" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="976" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M957.2334,-348.3873C943.3932,-336.5966 923.481,-322.0001 903,-315 825.5248,-288.5199 615.4308,-312.3131 535,-297 531.3486,-296.3048 527.6052,-295.4155 523.8787,-294.4057"/>
<polygon fill="#000000" stroke="#000000" points="524.712,-291.002 514.129,-291.5014 522.7136,-297.7107 524.712,-291.002"/>
<text text-anchor="middle" x="997.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node27" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2102" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2102" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2061.2743,-261.818C2032.1912,-250.3086 1991.8519,-235.8719 1955,-228 1891.8001,-214.4999 1714.034,-202.2249 1613.5371,-196.0995"/>
<polygon fill="#000000" stroke="#000000" points="1613.6571,-192.6005 1603.4641,-195.4904 1613.2345,-199.5877 1613.6571,-192.6005"/>
<text text-anchor="middle" x="2110" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- treatment_other -->
<g id="node28" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2628" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2628" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2576.4636,-264.3172C2531.784,-252.2747 2465.1808,-235.9616 2406,-228 2253.9317,-207.5422 1793.8663,-196.8024 1614.6038,-193.3044"/>
<polygon fill="#000000" stroke="#000000" points="1614.5515,-189.8029 1604.4857,-193.1089 1614.4161,-196.8016 1614.5515,-189.8029"/>
<text text-anchor="middle" x="2555.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- publication -->
<g id="node29" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1769" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1769" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge43" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1747.0138,-88.0703C1730.4003,-76.2837 1706.5115,-61.4017 1683,-54 1602.9769,-28.8078 1353.558,-20.9972 1248.9345,-18.7923"/>
<polygon fill="#000000" stroke="#000000" points="1248.7491,-15.2879 1238.6802,-18.5845 1248.6072,-22.2865 1248.7491,-15.2879"/>
<text text-anchor="middle" x="1766" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- generic_file -->
<g id="node30" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="192" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="192" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M227.4668,-350.6494C239.961,-344.7501 253.8995,-337.5954 266,-330 275.1124,-324.2802 275.1961,-319.4314 285,-315 310.1412,-303.6361 379.8272,-292.5258 429.1625,-285.7225"/>
<polygon fill="#000000" stroke="#000000" points="429.92,-289.1518 439.3579,-284.3375 428.9777,-282.2155 429.92,-289.1518"/>
<text text-anchor="middle" x="338" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M215.219,-348.9535C230.1423,-338.423 250.1909,-325.05 269,-315 287.2731,-305.2364 298.6675,-312.8581 312,-297 330.0396,-275.5431 326,-263.5326 326,-235.5 326,-235.5 326,-235.5 326,-105 326,-62.9049 974.9935,-28.8202 1155.7611,-20.1429"/>
<polygon fill="#000000" stroke="#000000" points="1155.9292,-23.6389 1165.7511,-19.6664 1155.5957,-16.6469 1155.9292,-23.6389"/>
<text text-anchor="middle" x="379" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M207.1652,-348.2358C235.7079,-316.3921 301.0495,-250.7912 373,-228 425.2689,-211.4432 1221.7233,-197.1947 1469.2027,-193.1483"/>
<polygon fill="#000000" stroke="#000000" points="1469.5815,-196.6427 1479.5231,-192.9803 1469.4675,-189.6436 1469.5815,-196.6427"/>
<text text-anchor="middle" x="358" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node31" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3225" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3225" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3124.9685,-358.8727C2957.771,-347.2988 2610.9041,-324.7331 2317,-315 2218.0492,-311.7231 632.5987,-313.628 535,-297 531.2849,-296.3671 527.4792,-295.5128 523.6954,-294.5188"/>
<polygon fill="#000000" stroke="#000000" points="524.3895,-291.075 513.8085,-291.6173 522.4183,-297.7917 524.3895,-291.075"/>
<text text-anchor="middle" x="2727" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3288.0067,-351.3249C3346.6307,-335.786 3425,-309.3394 3425,-279 3425,-279 3425,-279 3425,-105 3425,-48.5511 1570.1364,-22.6365 1249.071,-18.5737"/>
<polygon fill="#000000" stroke="#000000" points="1248.7728,-15.0698 1238.7296,-18.4437 1248.6848,-22.0692 1248.7728,-15.0698"/>
<text text-anchor="middle" x="3511" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3206.1189,-348.0134C3170.3856,-315.4874 3088.9031,-248.3732 3005,-228 2936.9799,-211.4835 1901.6746,-196.7225 1615.0561,-192.9366"/>
<polygon fill="#000000" stroke="#000000" points="1614.8216,-189.4334 1604.7764,-192.8013 1614.7294,-196.4327 1614.8216,-189.4334"/>
<text text-anchor="middle" x="3228" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M460.2749,-203.3298C426.6855,-213.2462 383.235,-226.3279 382,-228 365.5789,-250.2336 398.0463,-263.4852 430.2723,-270.883"/>
<polygon fill="#000000" stroke="#000000" points="429.7023,-274.34 440.2114,-272.9944 431.157,-267.4928 429.7023,-274.34"/>
<text text-anchor="middle" x="422.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M513.3715,-174.5541C534.1895,-150.5786 575.1805,-108.0303 620,-87 714.9866,-42.4302 1034.6596,-24.8904 1155.346,-19.7556"/>
<polygon fill="#000000" stroke="#000000" points="1155.5352,-23.2509 1165.3809,-19.3379 1155.244,-16.257 1155.5352,-23.2509"/>
<text text-anchor="middle" x="660.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
</g>
</svg>
</div>
