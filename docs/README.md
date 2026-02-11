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
<svg width="3788pt" height="392pt"
 viewBox="0.00 0.00 3787.54 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3783.5369,-388 3783.5369,4 -4,4"/>
<!-- treatment_surgery -->
<g id="node1" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1581.3431" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1581.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- participant -->
<g id="node31" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2012.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2012.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1567.3606,-261.0673C1560.7688,-250.3299 1555.988,-237.0535 1564.3431,-228 1576.8894,-214.4052 1816.7604,-201.1938 1940.2238,-195.2602"/>
<polygon fill="#000000" stroke="#000000" points="1940.5309,-198.7496 1950.3528,-194.7772 1940.1974,-191.7576 1940.5309,-198.7496"/>
<text text-anchor="middle" x="1642.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_funding -->
<g id="node2" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1493.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1493.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M83.8233,-87.0209C89.0527,-75.3844 97.6505,-61.1207 110.3431,-54 140.1267,-37.2911 1209.1167,-21.8499 1446.8228,-18.6182"/>
<polygon fill="#000000" stroke="#000000" points="1446.9152,-22.1174 1456.8668,-18.4822 1446.8203,-15.118 1446.9152,-22.1174"/>
<text text-anchor="middle" x="172.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node3" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2980.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2980.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node15" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="3227.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="3227.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2981.5549,-347.8679C2983.3183,-336.6274 2987.508,-322.8754 2997.3431,-315 3028.2045,-290.2879 3135.7119,-305.4107 3174.3431,-297 3177.9246,-296.2203 3181.6012,-295.2795 3185.2672,-294.2422"/>
<polygon fill="#000000" stroke="#000000" points="3186.3285,-297.5778 3194.874,-291.3148 3184.288,-290.8817 3186.3285,-297.5778"/>
<text text-anchor="middle" x="3088.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2417.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2417.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2449.2387,-351.2535C2477.4965,-338.9949 2520.2218,-322.4035 2559.3431,-315 2828.0246,-264.1533 2905.2293,-345.5064 3174.3431,-297 3178.052,-296.3315 3181.8534,-295.4525 3185.6343,-294.442"/>
<polygon fill="#000000" stroke="#000000" points="3186.9225,-297.7108 3195.5166,-291.5147 3184.9344,-290.9991 3186.9225,-297.7108"/>
<text text-anchor="middle" x="2603.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2377.9781,-353.3689C2360.7742,-347.2329 2340.6221,-339.1931 2323.3431,-330 2300.8102,-318.0116 2295.2599,-314.1351 2276.3431,-297 2260.6941,-282.8248 2263.075,-272.4633 2245.3431,-261 2194.7963,-228.3224 2128.2217,-210.6369 2079.1837,-201.3825"/>
<polygon fill="#000000" stroke="#000000" points="2079.7739,-197.9325 2069.3092,-199.5877 2078.522,-204.8196 2079.7739,-197.9325"/>
<text text-anchor="middle" x="2320.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_admin -->
<g id="node5" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="243.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="243.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M238.1172,-87.0351C236.1083,-76.0079 235.9907,-62.4297 244.3431,-54 265.9017,-32.242 1222.0883,-20.8503 1446.5387,-18.4732"/>
<polygon fill="#000000" stroke="#000000" points="1446.7044,-21.9718 1456.6671,-18.3669 1446.6308,-14.9722 1446.7044,-21.9718"/>
<text text-anchor="middle" x="300.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- laboratory_test -->
<g id="node6" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2252.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2252.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2282.8536,-349.1977C2306.4915,-337.1426 2340.477,-321.8639 2372.3431,-315 2546.6134,-277.4628 2998.7963,-328.0237 3174.3431,-297 3178.0542,-296.3442 3181.8572,-295.4739 3185.6391,-294.4693"/>
<polygon fill="#000000" stroke="#000000" points="3186.9235,-297.7396 3195.5232,-291.5512 3184.9413,-291.0261 3186.9235,-297.7396"/>
<text text-anchor="middle" x="2437.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2248.4081,-347.904C2245.0057,-336.6783 2238.9094,-322.9292 2228.3431,-315 2187.3162,-284.212 2159.8825,-320.6068 2114.3431,-297 2111.8861,-295.7263 2065.5251,-247.5482 2036.1606,-216.9023"/>
<polygon fill="#000000" stroke="#000000" points="2038.5428,-214.3294 2029.0984,-209.5279 2033.4872,-219.171 2038.5428,-214.3294"/>
<text text-anchor="middle" x="2179.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="683.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="683.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge41" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M632.1721,-362.3168C543.6585,-354.5267 371.3431,-332.4918 371.3431,-279 371.3431,-279 371.3431,-279 371.3431,-105 371.3431,-73.9165 412.6517,-66.3177 468.3431,-54 564.4311,-32.7474 1258.9379,-21.3542 1446.6705,-18.6408"/>
<polygon fill="#000000" stroke="#000000" points="1446.8183,-22.1391 1456.7671,-18.4962 1446.718,-15.1398 1446.8183,-22.1391"/>
<text text-anchor="middle" x="413.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M734.7261,-363.0158C892.0098,-354.0121 1380.8405,-327.0007 1786.3431,-315 1940.5108,-310.4374 3022.3361,-323.1218 3174.3431,-297 3178.0573,-296.3617 3181.8624,-295.5038 3185.6458,-294.5073"/>
<polygon fill="#000000" stroke="#000000" points="3186.9246,-297.7796 3195.532,-291.602 3184.9509,-291.0636 3186.9246,-297.7796"/>
<text text-anchor="middle" x="1828.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M678.7986,-348.0364C674.0682,-324.6467 670.1103,-284.0403 692.3431,-261 776.5956,-173.6874 842.3754,-237.423 963.3431,-228 1153.6148,-213.1785 1734.8046,-198.5101 1939.8166,-193.667"/>
<polygon fill="#000000" stroke="#000000" points="1939.9594,-197.1647 1949.8742,-193.4302 1939.7946,-190.1666 1939.9594,-197.1647"/>
<text text-anchor="middle" x="734.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node8" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2639.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2639.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2592.2941,-263.0254C2556.1011,-251.4038 2504.6157,-236.3053 2458.3431,-228 2328.1623,-204.6344 2173.8652,-196.4248 2085.1119,-193.5467"/>
<polygon fill="#000000" stroke="#000000" points="2084.9873,-190.0413 2074.8835,-193.2293 2084.7701,-197.0379 2084.9873,-190.0413"/>
<text text-anchor="middle" x="2602.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="486.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="486.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M476.2528,-86.7054C471.7514,-75.8318 469.1011,-62.5393 477.3431,-54 494.3901,-36.3383 1249.4221,-22.181 1446.6271,-18.78"/>
<polygon fill="#000000" stroke="#000000" points="1446.731,-22.2788 1456.6695,-18.6078 1446.6109,-15.2798 1446.731,-22.2788"/>
<text text-anchor="middle" x="546.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- consent_group -->
<g id="node11" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1413.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1413.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge8" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1413.5274,-86.904C1414.4809,-76.3708 1417.206,-63.3656 1424.3431,-54 1431.6274,-44.4412 1442.1794,-37.1789 1452.849,-31.7712"/>
<polygon fill="#000000" stroke="#000000" points="1454.5512,-34.8409 1462.1765,-27.4853 1451.6285,-28.4803 1454.5512,-34.8409"/>
<text text-anchor="middle" x="1487.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- exposure -->
<g id="node12" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="3112.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="3112.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3075.416,-265.7605C3058.9108,-259.4546 3039.3789,-251.4502 3022.3431,-243 3010.735,-237.2421 3009.7654,-231.6863 2997.3431,-228 2910.8392,-202.3296 2298.2343,-194.5216 2085.1682,-192.5678"/>
<polygon fill="#000000" stroke="#000000" points="2085.0567,-189.0667 2075.0255,-192.4764 2084.9936,-196.0664 2085.0567,-189.0667"/>
<text text-anchor="middle" x="3065.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_response -->
<g id="node13" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="542.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="542.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M527.1563,-260.9769C519.9549,-250.2056 514.6312,-236.9251 523.3431,-228 548.3339,-202.3977 1643.5564,-194.1541 1939.3655,-192.3925"/>
<polygon fill="#000000" stroke="#000000" points="1939.5688,-195.8914 1949.548,-192.3325 1939.5275,-188.8916 1939.5688,-195.8914"/>
<text text-anchor="middle" x="606.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- survival -->
<g id="node14" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2805.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2805.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2777.9201,-263.9482C2754.3896,-251.851 2719.1776,-235.6577 2686.3431,-228 2573.8121,-201.7552 2234.6513,-194.5819 2084.8314,-192.6713"/>
<polygon fill="#000000" stroke="#000000" points="2084.8515,-189.1714 2074.8091,-192.5478 2084.7652,-196.1709 2084.8515,-189.1714"/>
<text text-anchor="middle" x="2768.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3227.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3227.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3255.476,-264.9861C3263.7317,-259.3644 3271.7665,-252.0415 3276.3431,-243 3283.1209,-229.61 3272.2568,-217.3802 3259.0519,-208.2552"/>
<polygon fill="#000000" stroke="#000000" points="3260.5341,-205.0544 3250.1982,-202.7261 3256.8262,-210.9917 3260.5341,-205.0544"/>
<text text-anchor="middle" x="3314.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node28" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3419.3431" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3419.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3268.0894,-271.8754C3294.0335,-266.3079 3327.8134,-257.1056 3355.3431,-243 3369.2826,-235.8578 3383.0849,-225.4092 3394.2832,-215.8264"/>
<polygon fill="#000000" stroke="#000000" points="3396.7642,-218.3049 3401.9419,-209.0613 3392.13,-213.0585 3396.7642,-218.3049"/>
<text text-anchor="middle" x="3413.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3197.3153,-265.69C3163.8952,-250.9266 3113.9437,-229.0306 3109.3431,-228 3010.1665,-205.7825 2314.398,-195.5934 2085.2973,-192.8148"/>
<polygon fill="#000000" stroke="#000000" points="2085.1099,-189.3124 2075.0685,-192.6919 2085.0257,-196.3119 2085.1099,-189.3124"/>
<text text-anchor="middle" x="3179.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3199.4038,-189.1964C2999.8198,-169.1689 1791.2617,-47.8949 1539.3358,-22.6152"/>
<polygon fill="#000000" stroke="#000000" points="1539.3776,-19.1019 1529.0781,-21.5859 1538.6786,-26.0669 1539.3776,-19.1019"/>
<text text-anchor="middle" x="2556.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3225.3681,-210.4051C3224.5537,-220.0991 3223.8934,-232.1886 3224.3431,-243 3224.4443,-245.4321 3224.5837,-247.9542 3224.7475,-250.4832"/>
<polygon fill="#000000" stroke="#000000" points="3221.2764,-250.9974 3225.5222,-260.7043 3228.2564,-250.4683 3221.2764,-250.9974"/>
<text text-anchor="middle" x="3248.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node17" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1573.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1573.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge44" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1568.5481,-86.9989C1565.0718,-76.4993 1559.5265,-63.4961 1551.3431,-54 1545.1502,-46.8136 1537.1594,-40.6015 1529.1006,-35.4572"/>
<polygon fill="#000000" stroke="#000000" points="1530.7966,-32.3938 1520.411,-30.2985 1527.2232,-38.413 1530.7966,-32.3938"/>
<text text-anchor="middle" x="1612.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node18" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="915.3431" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="915.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M937.4043,-261.0371C953.3025,-249.2468 975.8381,-234.7952 998.3431,-228 1087.5673,-201.0597 1722.3009,-194.0588 1939.5937,-192.4415"/>
<polygon fill="#000000" stroke="#000000" points="1939.6474,-195.9413 1949.6216,-192.3685 1939.5963,-188.9415 1939.6474,-195.9413"/>
<text text-anchor="middle" x="1100.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- treatment_radiation -->
<g id="node19" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1167.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1167.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1183.3353,-261.1343C1195.0572,-249.3885 1212.0593,-234.9503 1230.3431,-228 1295.4958,-203.2334 1758.3858,-195.0425 1939.7314,-192.7655"/>
<polygon fill="#000000" stroke="#000000" points="1940.0132,-196.2624 1949.9693,-192.6395 1939.927,-189.2629 1940.0132,-196.2624"/>
<text text-anchor="middle" x="1313.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- treatment_other -->
<g id="node20" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="1377.3431" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1377.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1386.2389,-261.0797C1393.0422,-249.4694 1403.5913,-235.2129 1417.3431,-228 1462.5118,-204.3087 1790.9722,-195.7568 1939.6161,-193.0768"/>
<polygon fill="#000000" stroke="#000000" points="1940.0645,-196.5696 1950.0013,-192.8939 1939.9412,-189.5707 1940.0645,-196.5696"/>
<text text-anchor="middle" x="1486.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- cytogenomic_file -->
<g id="node21" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="3203.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="3203.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3191.2343,-347.6891C3186.2693,-337.8055 3182.6617,-325.5115 3187.3431,-315 3189.5204,-310.1112 3192.726,-305.6079 3196.3907,-301.5622"/>
<polygon fill="#000000" stroke="#000000" points="3199.0852,-303.8261 3203.8542,-294.3653 3194.2262,-298.7871 3199.0852,-303.8261"/>
<text text-anchor="middle" x="3258.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- genetic_analysis -->
<g id="node22" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2002.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2002.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2045.9155,-350.315C2082.1574,-338.1008 2135.3807,-322.0725 2183.3431,-315 2401.2454,-282.8682 2957.3641,-334.8674 3174.3431,-297 3178.0556,-296.3521 3181.8596,-295.4874 3185.6421,-294.4865"/>
<polygon fill="#000000" stroke="#000000" points="3186.924,-297.7576 3195.5272,-291.5741 3184.9457,-291.043 3186.924,-297.7576"/>
<text text-anchor="middle" x="2253.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1926.4557,-356.8721C1859.1608,-348.408 1770.6841,-336.2135 1765.3431,-330 1760.9975,-324.9444 1760.9723,-320.034 1765.3431,-315 1784.0311,-293.4766 1866.4315,-308.8777 1892.3431,-297 1903.1886,-292.0285 1953.8436,-246.1384 1985.7745,-216.6934"/>
<polygon fill="#000000" stroke="#000000" points="1988.485,-218.9542 1993.4535,-209.5966 1983.734,-213.8134 1988.485,-218.9542"/>
<text text-anchor="middle" x="2005.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sequencing_file -->
<g id="node23" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2593.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2593.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2618.1036,-348.8074C2636.7571,-336.8902 2663.4636,-321.9598 2689.3431,-315 2793.4945,-286.9905 3068.2773,-316.5472 3174.3431,-297 3177.9986,-296.3263 3181.7448,-295.4521 3185.4732,-294.4524"/>
<polygon fill="#000000" stroke="#000000" points="3186.6314,-297.7597 3195.2259,-291.5641 3184.6437,-291.0478 3186.6314,-297.7597"/>
<text text-anchor="middle" x="2755.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_arm -->
<g id="node24" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1714.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1714.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1702.437,-87.205C1693.9676,-75.9563 1681.5936,-62.0669 1667.3431,-54 1645.7833,-41.7954 1582.7791,-30.7337 1538.8252,-24.1854"/>
<polygon fill="#000000" stroke="#000000" points="1539.0534,-20.6816 1528.6525,-22.6992 1538.0415,-27.6081 1539.0534,-20.6816"/>
<text text-anchor="middle" x="1732.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- radiology_file -->
<g id="node25" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2447.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2447.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2405.5523,-264.0583C2372.2877,-252.679 2324.3419,-237.415 2281.3431,-228 2214.5365,-213.3721 2137.0124,-203.7589 2082.3996,-198.1763"/>
<polygon fill="#000000" stroke="#000000" points="2082.4342,-194.6623 2072.1349,-197.1469 2081.7357,-201.6274 2082.4342,-194.6623"/>
<text text-anchor="middle" x="2395.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="3473.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="3473.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3525.9087,-355.1098C3564.9074,-343.597 3611.3431,-321.0582 3611.3431,-279 3611.3431,-279 3611.3431,-279 3611.3431,-105 3611.3431,-51.3269 1851.5558,-23.2163 1540.1506,-18.6622"/>
<polygon fill="#000000" stroke="#000000" points="1540.1549,-15.162 1530.105,-18.5161 1540.053,-22.1612 1540.1549,-15.162"/>
<text text-anchor="middle" x="3664.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3423.125,-354.3804C3401.1691,-348.4317 3375.4384,-340.2588 3353.3431,-330 3342.274,-324.8606 3341.2944,-320.3859 3330.3431,-315 3312.4153,-306.183 3291.777,-298.5205 3273.7046,-292.5579"/>
<polygon fill="#000000" stroke="#000000" points="3274.5532,-289.1543 3263.9618,-289.4237 3272.4094,-295.818 3274.5532,-289.1543"/>
<text text-anchor="middle" x="3406.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3471.1074,-347.9159C3469.1955,-337.6379 3465.6955,-324.8879 3459.3431,-315 3426.7707,-264.2985 3411.7065,-249.3256 3355.3431,-228 3295.6421,-205.4115 2355.797,-195.1289 2084.896,-192.6249"/>
<polygon fill="#000000" stroke="#000000" points="2084.8126,-189.1241 2074.7809,-192.5322 2084.7483,-196.1238 2084.8126,-189.1241"/>
<text text-anchor="middle" x="3499.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node27" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1716.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1716.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1608.2878,-364.2101C1305.5877,-358.6717 468.685,-339.5609 428.3431,-297 365.3206,-230.5109 483.4101,-237.426 515.3431,-228 869.167,-123.5585 1309.2223,-47.8461 1448.7526,-25.1013"/>
<polygon fill="#000000" stroke="#000000" points="1449.3472,-28.5507 1458.6572,-23.4936 1448.2256,-21.6411 1449.3472,-28.5507"/>
<text text-anchor="middle" x="796.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1779.4747,-351.3511C1843.143,-336.6296 1933.19,-315.9728 1941.3431,-315 2077.3928,-298.7679 3039.3269,-320.3153 3174.3431,-297 3178.0568,-296.3587 3181.8615,-295.4986 3185.6446,-294.5008"/>
<polygon fill="#000000" stroke="#000000" points="3186.9244,-297.7727 3195.5305,-291.5932 3184.9492,-291.0571 3186.9244,-297.7727"/>
<text text-anchor="middle" x="2027.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1710.1604,-347.8347C1703.6301,-324.9688 1696.7375,-285.7015 1716.3431,-261 1744.0096,-226.1425 1863.7232,-207.2641 1942.1743,-198.4407"/>
<polygon fill="#000000" stroke="#000000" points="1942.9199,-201.8801 1952.4796,-197.3126 1942.158,-194.9217 1942.9199,-201.8801"/>
<text text-anchor="middle" x="1802.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge4" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3373.2886,-185.1901C3247.2919,-166.7802 2886.173,-115.4943 2584.3431,-87 2180.7066,-48.8946 1691.0131,-26.3375 1539.9507,-19.9137"/>
<polygon fill="#000000" stroke="#000000" points="1539.8041,-16.4045 1529.6652,-19.4791 1539.5085,-23.3983 1539.8041,-16.4045"/>
<text text-anchor="middle" x="2943.8431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3458.1905,-203.1226C3483.0397,-212.1564 3508.0754,-226.1396 3493.3431,-243 3486.4061,-250.9391 3356.3248,-265.6462 3280.6881,-273.5835"/>
<polygon fill="#000000" stroke="#000000" points="3279.9781,-270.1385 3270.3952,-274.6572 3280.7044,-277.1007 3279.9781,-270.1385"/>
<text text-anchor="middle" x="3537.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node29" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2956.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2956.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2915.8664,-263.156C2880.7381,-249.6867 2832.452,-231.9232 2812.3431,-228 2674.3557,-201.0792 2255.095,-194.2256 2085.1014,-192.5344"/>
<polygon fill="#000000" stroke="#000000" points="2085.0331,-189.0336 2074.9998,-192.437 2084.9656,-196.0333 2085.0331,-189.0336"/>
<text text-anchor="middle" x="2925.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_status -->
<g id="node30" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="3709.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3709.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3688.0524,-87.6675C3671.9168,-75.6807 3648.6174,-60.7246 3625.3431,-54 3521.8771,-24.1056 1844.3619,-18.8123 1540.3831,-18.0972"/>
<polygon fill="#000000" stroke="#000000" points="1540.162,-14.5968 1530.1539,-18.0737 1540.1458,-21.5968 1540.162,-14.5968"/>
<text text-anchor="middle" x="3713.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge38" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1953.9065,-185.4115C1858.7739,-174.3936 1664.6245,-150.6906 1501.3431,-123 1494.7321,-121.8788 1487.8591,-120.6265 1480.9988,-119.3186"/>
<polygon fill="#000000" stroke="#000000" points="1481.4729,-115.8453 1470.9886,-117.3716 1480.1363,-122.7165 1481.4729,-115.8453"/>
<text text-anchor="middle" x="1761.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node32" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2770.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2770.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2793.8056,-348.7023C2811.2167,-336.8986 2836.052,-322.1538 2860.3431,-315 2994.4337,-275.51 3037.1359,-323.7195 3174.3431,-297 3177.9916,-296.2895 3181.733,-295.3895 3185.4581,-294.3724"/>
<polygon fill="#000000" stroke="#000000" points="3186.6281,-297.6758 3195.2056,-291.4567 3184.622,-290.9694 3186.6281,-297.6758"/>
<text text-anchor="middle" x="2921.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
</g>
</svg>
</div>
