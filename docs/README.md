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
<svg width="3446pt" height="392pt"
 viewBox="0.00 0.00 3446.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3441.9954,-388 3441.9954,4 -4,4"/>
<!-- pathology_file -->
<g id="node1" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="3162.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="3162.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node26" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2915.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2915.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3150.1544,-348.0996C3141.0706,-336.8063 3127.8901,-322.9069 3112.9954,-315 3088.5751,-302.0365 3018.4623,-291.2857 2968.8564,-285.0017"/>
<polygon fill="#000000" stroke="#000000" points="2969.2726,-281.5266 2958.9174,-283.7672 2968.4098,-288.4732 2969.2726,-281.5266"/>
<text text-anchor="middle" x="3193.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_admin -->
<g id="node2" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="732.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="732.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1140.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1140.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M750.0452,-87.4736C762.4611,-75.8835 780.3135,-61.4918 798.9954,-54 851.4312,-32.9724 1013.2481,-23.3602 1094.0648,-19.7773"/>
<polygon fill="#000000" stroke="#000000" points="1094.603,-23.2575 1104.4433,-19.3307 1094.302,-16.264 1094.603,-23.2575"/>
<text text-anchor="middle" x="855.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2129.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2129.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node20" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1565.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1565.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2096.7541,-261.8852C2072.5311,-250.2502 2038.5649,-235.6338 2006.9954,-228 1939.0033,-211.5589 1744.552,-200.2905 1637.9868,-195.1561"/>
<polygon fill="#000000" stroke="#000000" points="1638.1108,-191.6581 1627.9556,-194.6784 1637.7778,-198.6502 1638.1108,-191.6581"/>
<text text-anchor="middle" x="2135.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment_radiation -->
<g id="node4" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="2533.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2533.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2474.5486,-264.1696C2424.367,-252.292 2350.4415,-236.2919 2284.9954,-228 2161.4687,-212.3494 1794.6702,-199.253 1638.1176,-194.2157"/>
<polygon fill="#000000" stroke="#000000" points="1638.2215,-190.7173 1628.1147,-193.8956 1637.9976,-197.7137 1638.2215,-190.7173"/>
<text text-anchor="middle" x="2457.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="496.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="496.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M487.887,-260.6637C483.9116,-249.7744 481.7942,-236.4801 489.9954,-228 507.45,-209.9517 1254.0436,-196.8334 1493.147,-193.0888"/>
<polygon fill="#000000" stroke="#000000" points="1493.5259,-196.5834 1503.4702,-192.928 1493.4168,-189.5843 1493.5259,-196.5834"/>
<text text-anchor="middle" x="548.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2538.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2538.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2561.0965,-348.5672C2577.2609,-336.8612 2600.2507,-322.2922 2622.9954,-315 2724.8545,-282.3428 2758.1854,-318.3694 2862.9954,-297 2866.6374,-296.2574 2870.3743,-295.3349 2874.0964,-294.3028"/>
<polygon fill="#000000" stroke="#000000" points="2875.2765,-297.6027 2883.8392,-291.3632 2873.2544,-290.9011 2875.2765,-297.6027"/>
<text text-anchor="middle" x="2689.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- genetic_analysis -->
<g id="node7" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2315.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2315.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2289.5662,-348.6258C2282.8479,-343.2659 2276.0959,-336.9294 2270.9954,-330 2241.2952,-289.65 2266.239,-253.3025 2222.9954,-228 2198.1125,-213.4406 1803.8307,-199.4545 1638.2896,-194.1932"/>
<polygon fill="#000000" stroke="#000000" points="1638.3037,-190.692 1628.1981,-193.8743 1638.0825,-197.6885 1638.3037,-190.692"/>
<text text-anchor="middle" x="2325.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2366.119,-351.2095C2384.0445,-345.3394 2404.2034,-338.0596 2421.9954,-330 2434.1474,-324.4952 2435.1865,-318.7292 2447.9954,-315 2536.6244,-289.1962 2772.2679,-314.0138 2862.9954,-297 2866.6487,-296.3149 2870.3935,-295.4327 2874.1208,-294.4276"/>
<polygon fill="#000000" stroke="#000000" points="2875.2827,-297.7337 2883.872,-291.5308 2873.2893,-291.0235 2875.2827,-297.7337"/>
<text text-anchor="middle" x="2517.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- laboratory_test -->
<g id="node8" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1775.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1775.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1696.4437,-361.5652C1604.6875,-354.593 1462.1665,-337.4165 1428.9954,-297 1397.9182,-259.1348 1462.3873,-226.8148 1513.0544,-208.397"/>
<polygon fill="#000000" stroke="#000000" points="1514.3839,-211.6395 1522.6495,-205.0115 1512.0547,-205.0384 1514.3839,-211.6395"/>
<text text-anchor="middle" x="1494.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1847.7991,-357.273C1946.5669,-345.6258 2129.971,-325.2773 2286.9954,-315 2414.7845,-306.6361 2736.9864,-319.8413 2862.9954,-297 2866.7036,-296.3278 2870.5045,-295.4462 2874.2851,-294.4341"/>
<polygon fill="#000000" stroke="#000000" points="2875.5745,-297.7025 2884.167,-291.5041 2873.5846,-290.9912 2875.5745,-297.7025"/>
<text text-anchor="middle" x="2352.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node9" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1254.9954" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1254.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1236.0232,-261.0807C1227.1981,-250.6101 1220.3585,-237.6087 1228.9954,-228 1246.3582,-208.6836 1400.0823,-198.8874 1493.808,-194.6679"/>
<polygon fill="#000000" stroke="#000000" points="1493.9682,-198.1643 1503.8049,-194.2287 1493.6609,-191.1711 1493.9682,-198.1643"/>
<text text-anchor="middle" x="1330.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_personnel -->
<g id="node10" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="907.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="907.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M909.7993,-86.8057C911.8816,-75.6869 916.3617,-62.093 925.9954,-54 950.8367,-33.1315 1038.8391,-24.0682 1094.2591,-20.3577"/>
<polygon fill="#000000" stroke="#000000" points="1094.7844,-23.8315 1104.5427,-19.7053 1094.3411,-16.8456 1094.7844,-23.8315"/>
<text text-anchor="middle" x="995.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M36.4219,-348.7467C23.0769,-332.1293 5.9954,-305.6534 5.9954,-279 5.9954,-279 5.9954,-279 5.9954,-105 5.9954,-49.49 880.4703,-24.3987 1094.2621,-19.0938"/>
<polygon fill="#000000" stroke="#000000" points="1094.6064,-22.5865 1104.5174,-18.842 1094.4345,-15.5886 1094.6064,-22.5865"/>
<text text-anchor="middle" x="48.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M61.0599,-348.1854C74.276,-324.1815 101.2108,-282.0422 136.9954,-261 210.5,-217.7775 241.1586,-236.5928 325.9954,-228 554.566,-204.8489 1263.3764,-195.2823 1493.2309,-192.7371"/>
<polygon fill="#000000" stroke="#000000" points="1493.5252,-196.2341 1503.4862,-192.6247 1493.4484,-189.2346 1493.5252,-196.2341"/>
<text text-anchor="middle" x="179.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M103.1773,-362.5323C247.438,-352.9255 669.7123,-325.9556 1020.9954,-315 1123.2839,-311.8099 2762.108,-314.1712 2862.9954,-297 2866.7106,-296.3677 2870.5164,-295.5138 2874.3002,-294.5201"/>
<polygon fill="#000000" stroke="#000000" points="2875.5772,-297.7931 2884.1872,-291.6191 2873.6063,-291.0763 2875.5772,-297.7931"/>
<text text-anchor="middle" x="1063.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- generic_file -->
<g id="node12" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="605.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="605.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge44" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M543.7462,-360.1102C422.1843,-347.7656 164.9954,-317.1411 164.9954,-279 164.9954,-279 164.9954,-279 164.9954,-105 164.9954,-57.7582 900.0359,-26.9903 1094.3481,-19.682"/>
<polygon fill="#000000" stroke="#000000" points="1094.6539,-23.1731 1104.5163,-19.3025 1094.3927,-16.178 1094.6539,-23.1731"/>
<text text-anchor="middle" x="217.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M601.5922,-347.8417C597.1388,-324.6161 593.6119,-284.5843 614.9954,-261 669.0394,-201.3936 713.067,-237.2264 792.9954,-228 927.3139,-212.4951 1328.2976,-199.1163 1493.5648,-194.1057"/>
<polygon fill="#000000" stroke="#000000" points="1493.741,-197.6021 1503.6309,-193.802 1493.5299,-190.6052 1493.741,-197.6021"/>
<text text-anchor="middle" x="667.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M668.1031,-360.1378C710.3383,-356.296 767.5033,-351.3785 817.9954,-348 1117.2406,-327.9769 1192.2253,-324.3035 1491.9954,-315 1644.2685,-310.2742 2712.8519,-322.814 2862.9954,-297 2866.7095,-296.3614 2870.5146,-295.5033 2874.2979,-294.5067"/>
<polygon fill="#000000" stroke="#000000" points="2875.5768,-297.7789 2884.1841,-291.6011 2873.6029,-291.0629 2875.5768,-297.7789"/>
<text text-anchor="middle" x="1544.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- medical_history -->
<g id="node13" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="814.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="814.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M802.4348,-260.8672C796.6128,-250.0544 792.6292,-236.7691 800.9954,-228 824.6547,-203.2011 1306.6383,-194.9947 1493.1669,-192.7411"/>
<polygon fill="#000000" stroke="#000000" points="1493.4665,-196.2379 1503.4243,-192.6196 1493.3835,-189.2384 1493.4665,-196.2379"/>
<text text-anchor="middle" x="868.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cell_line -->
<g id="node14" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2915.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2915.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge17" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2866.384,-191.3474C2604.6072,-187.8455 1392.9092,-170.8856 1314.9954,-156 1273.5577,-148.0833 1256.2765,-152.3736 1225.9954,-123 1202.2401,-99.9567 1219.227,-79.3875 1197.9954,-54 1192.0489,-46.8896 1184.3266,-40.7332 1176.4963,-35.6211"/>
<polygon fill="#000000" stroke="#000000" points="1178.0663,-32.4802 1167.6986,-30.2978 1174.4425,-38.4692 1178.0663,-32.4802"/>
<text text-anchor="middle" x="1266.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2914.0204,-210.4051C2913.2059,-220.0991 2912.5457,-232.1886 2912.9954,-243 2913.0965,-245.4321 2913.236,-247.9542 2913.3998,-250.4832"/>
<polygon fill="#000000" stroke="#000000" points="2909.9286,-250.9974 2914.1745,-260.7043 2916.9086,-250.4683 2909.9286,-250.9974"/>
<text text-anchor="middle" x="2953.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- survival -->
<g id="node16" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1958.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1958.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1944.3394,-261.7304C1933.3945,-250.1014 1917.379,-235.5572 1899.9954,-228 1854.4911,-208.2178 1721.9242,-198.8287 1638.1315,-194.7561"/>
<polygon fill="#000000" stroke="#000000" points="1638.065,-191.2492 1627.9112,-194.2739 1637.7351,-198.2414 1638.065,-191.2492"/>
<text text-anchor="middle" x="1963.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1471.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1471.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1436.7917,-88.8627C1411.2244,-77.6946 1375.5468,-63.2346 1342.9954,-54 1290.2361,-39.0327 1227.8788,-29.0478 1186.5483,-23.4657"/>
<polygon fill="#000000" stroke="#000000" points="1186.8843,-19.9797 1176.5122,-22.141 1185.9682,-26.9196 1186.8843,-19.9797"/>
<text text-anchor="middle" x="1448.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cytogenomic_file -->
<g id="node18" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2729.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2729.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2742.4391,-347.9813C2751.1213,-336.7873 2763.6872,-323.0446 2777.9954,-315 2811.6556,-296.0751 2825.7587,-307.2271 2862.9954,-297 2866.3293,-296.0844 2869.7601,-295.0755 2873.1967,-294.0172"/>
<polygon fill="#000000" stroke="#000000" points="2874.3621,-297.3192 2882.8207,-290.9393 2872.2298,-290.6518 2874.3621,-297.3192"/>
<text text-anchor="middle" x="2849.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_status -->
<g id="node19" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1637.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1637.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1606.5129,-88.8837C1582.1744,-77.1879 1547.2938,-62.0585 1514.9954,-54 1454.0252,-38.7878 1272.9871,-26.0822 1187.1443,-20.7266"/>
<polygon fill="#000000" stroke="#000000" points="1187.3588,-17.2333 1177.1621,-20.1103 1186.9274,-24.22 1187.3588,-17.2333"/>
<text text-anchor="middle" x="1617.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- consent_group -->
<g id="node27" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1093.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1093.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1504.0443,-189.3888C1379.853,-183.862 1111.0517,-170.3095 1096.9954,-156 1091.2267,-150.1274 1089.2465,-141.8095 1089.0661,-133.5912"/>
<polygon fill="#000000" stroke="#000000" points="1092.5707,-133.6107 1089.6504,-123.4263 1085.5822,-133.209 1092.5707,-133.6107"/>
<text text-anchor="middle" x="1147.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_measure_file -->
<g id="node21" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="935.9954" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="935.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M838.0371,-358.2374C644.8096,-342.6968 232.2443,-308.2871 221.9954,-297 211.2396,-285.1546 213.0412,-274.2598 221.9954,-261 294.8469,-153.1182 642.0874,-78.1945 769.9954,-54 885.361,-32.178 1023.5544,-23.205 1094.2693,-19.8293"/>
<polygon fill="#000000" stroke="#000000" points="1094.7857,-23.3093 1104.614,-19.3527 1094.4635,-16.3167 1094.7857,-23.3093"/>
<text text-anchor="middle" x="430.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M931.3607,-347.6249C926.657,-324.1648 922.8599,-283.8799 944.9954,-261 982.5753,-222.1563 1338.0072,-201.974 1493.6203,-194.9389"/>
<polygon fill="#000000" stroke="#000000" points="1494.1901,-198.4171 1504.0242,-194.4748 1493.8781,-191.4241 1494.1901,-198.4171"/>
<text text-anchor="middle" x="1030.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1037.8,-359.6925C1217.5929,-348.7943 1603.1566,-326.5043 1928.9954,-315 2032.7278,-311.3376 2760.7537,-314.9017 2862.9954,-297 2866.7075,-296.35 2870.5112,-295.4839 2874.2936,-294.482"/>
<polygon fill="#000000" stroke="#000000" points="2875.5761,-297.753 2884.1784,-291.5682 2873.5968,-291.0386 2875.5761,-297.753"/>
<text text-anchor="middle" x="2014.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_arm -->
<g id="node22" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1785.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1785.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1759.1034,-88.8123C1737.8798,-76.9147 1707.0967,-61.5567 1677.9954,-54 1585.9092,-30.0879 1300.5218,-21.4386 1187.6382,-18.9009"/>
<polygon fill="#000000" stroke="#000000" points="1187.6557,-15.4006 1177.5815,-18.6808 1187.5025,-22.3989 1187.6557,-15.4006"/>
<text text-anchor="middle" x="1767.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node23" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3206.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3206.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge41" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3179.0474,-189.4237C3135.3405,-185.4891 3048.1332,-178.0171 2973.9954,-174 2883.1955,-169.08 1420.0519,-162.1859 1337.9954,-123 1318.9419,-113.901 1324.0949,-99.3868 1306.9954,-87 1269.0382,-59.504 1218.489,-40.5228 1183.1835,-29.5286"/>
<polygon fill="#000000" stroke="#000000" points="1183.7857,-26.0541 1173.2005,-26.5058 1181.7571,-32.7537 1183.7857,-26.0541"/>
<text text-anchor="middle" x="1361.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3208.7527,-210.044C3208.7724,-221.1028 3206.7153,-234.6864 3197.9954,-243 3181.7992,-258.4415 3047.0235,-270.0719 2969.8066,-275.5414"/>
<polygon fill="#000000" stroke="#000000" points="2969.5025,-272.054 2959.77,-276.2406 2969.9891,-279.0371 2969.5025,-272.054"/>
<text text-anchor="middle" x="3229.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1668.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1668.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1648.1518,-261.3943C1632.6937,-248.3374 1611.442,-230.3869 1594.4257,-216.014"/>
<polygon fill="#000000" stroke="#000000" points="1596.3545,-213.0616 1586.4565,-209.2827 1591.8375,-218.4093 1596.3545,-213.0616"/>
<text text-anchor="middle" x="1703.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1926.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1926.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge2" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1899.9661,-88.4476C1878.981,-76.5234 1848.7156,-61.2991 1819.9954,-54 1759.2338,-38.5578 1331.7546,-23.9544 1188.0173,-19.4313"/>
<polygon fill="#000000" stroke="#000000" points="1187.8741,-15.9252 1177.7695,-19.1108 1187.6552,-22.9218 1187.8741,-15.9252"/>
<text text-anchor="middle" x="1910.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2956.0329,-271.3418C2971.8889,-266.1364 2988.5585,-257.4492 2997.9954,-243 3009.4366,-225.4818 2990.2329,-212.9231 2967.545,-204.6518"/>
<polygon fill="#000000" stroke="#000000" points="2968.6337,-201.3254 2958.0399,-201.4754 2966.415,-207.9645 2968.6337,-201.3254"/>
<text text-anchor="middle" x="3037.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2887.8063,-265.0877C2861.2415,-252.7544 2819.9564,-235.5621 2781.9954,-228 2670.3231,-205.7541 1883.8906,-195.4413 1638.7691,-192.7431"/>
<polygon fill="#000000" stroke="#000000" points="1638.5829,-189.2409 1628.5453,-192.6315 1638.5065,-196.2405 1638.5829,-189.2409"/>
<text text-anchor="middle" x="2868.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2956.7344,-271.7962C2989.7765,-265.5131 3037.3668,-255.4602 3077.9954,-243 3111.6816,-232.6689 3148.9989,-217.4883 3174.7938,-206.3759"/>
<polygon fill="#000000" stroke="#000000" points="3176.3103,-209.5331 3184.0842,-202.3347 3173.518,-203.1141 3176.3103,-209.5331"/>
<text text-anchor="middle" x="3157.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge4" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1077.2942,-86.9843C1070.0927,-76.9648 1064.6206,-64.4469 1070.9954,-54 1077.4464,-43.4282 1088.1023,-35.8299 1099.1777,-30.4246"/>
<polygon fill="#000000" stroke="#000000" points="1100.7149,-33.5729 1108.4965,-26.3828 1097.9295,-27.1509 1100.7149,-33.5729"/>
<text text-anchor="middle" x="1134.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- diagnosis -->
<g id="node28" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="3359.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="3359.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3369.9732,-347.9319C3374.3177,-337.4086 3377.006,-324.404 3369.9954,-315 3329.5273,-260.7167 3144.8737,-238.5656 3077.9954,-228 2935.3286,-205.4611 1920.9409,-195.072 1638.7055,-192.5975"/>
<polygon fill="#000000" stroke="#000000" points="1638.6106,-189.0967 1628.5805,-192.5094 1638.5496,-196.0964 1638.6106,-189.0967"/>
<text text-anchor="middle" x="3393.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3326.0052,-351.8518C3311.8501,-345.6173 3295.3913,-337.9158 3280.9954,-330 3270.3014,-324.1197 3269.4951,-319.0859 3257.9954,-315 3206.3381,-296.6461 3052.7975,-286.099 2970.1322,-281.6033"/>
<polygon fill="#000000" stroke="#000000" points="2970.1,-278.0967 2959.9279,-281.0595 2969.7274,-285.0868 2970.1,-278.0967"/>
<text text-anchor="middle" x="3325.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node29" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2952.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2952.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2939.9444,-347.9141C2936.3538,-342.36 2932.7063,-336.0997 2929.9954,-330 2926.8164,-322.8472 2924.2022,-314.8027 2922.1291,-307.2535"/>
<polygon fill="#000000" stroke="#000000" points="2925.4812,-306.2327 2919.6353,-297.3966 2918.695,-307.9496 2925.4812,-306.2327"/>
<text text-anchor="middle" x="3021.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node30" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1839.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1839.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1826.6399,-261.5071C1816.9255,-250.0877 1802.7556,-235.8836 1786.9954,-228 1761.0163,-215.0047 1690.0523,-204.9134 1635.4799,-198.7643"/>
<polygon fill="#000000" stroke="#000000" points="1635.819,-195.2806 1625.4953,-197.6622 1635.0509,-202.2383 1635.819,-195.2806"/>
<text text-anchor="middle" x="1852.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_surgery -->
<g id="node31" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2754.9954" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2754.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2703.7724,-263.4917C2661.5919,-251.4674 2599.9981,-235.6109 2544.9954,-228 2370.0684,-203.7948 1834.7541,-195.1708 1638.8242,-192.7769"/>
<polygon fill="#000000" stroke="#000000" points="1638.6785,-189.275 1628.6371,-192.6543 1638.5942,-196.2745 1638.6785,-189.275"/>
<text text-anchor="middle" x="2699.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- treatment_other -->
<g id="node32" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="317.9954" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="317.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M321.4635,-260.9489C324.6979,-249.4382 330.7829,-235.3489 341.9954,-228 366.176,-212.1515 1233.5341,-197.2362 1493.2446,-193.1176"/>
<polygon fill="#000000" stroke="#000000" points="1493.3814,-196.616 1503.3248,-192.9583 1493.2707,-189.6168 1493.3814,-196.616"/>
<text text-anchor="middle" x="411.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
</g>
</svg>
</div>
