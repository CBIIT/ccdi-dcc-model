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
<svg width="3028pt" height="392pt"
 viewBox="0.00 0.00 3028.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3024.3431,-388 3024.3431,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="804.3431" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="804.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1437.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1437.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M795.7938,-260.7144C792.1071,-249.8442 790.2592,-236.5521 798.3431,-228 817.5285,-207.7034 1200.8317,-197.0806 1364.3951,-193.4571"/>
<polygon fill="#000000" stroke="#000000" points="1364.9237,-196.9465 1374.8448,-193.2285 1364.7706,-189.9481 1364.9237,-196.9465"/>
<text text-anchor="middle" x="845.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1546.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1546.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2324.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2324.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1564.1849,-348.7612C1577.8128,-336.821 1597.7088,-321.8822 1618.3431,-315 1687.1975,-292.035 2199.9002,-309.8145 2271.3431,-297 2275.0525,-296.3347 2278.8544,-295.4578 2282.6355,-294.4488"/>
<polygon fill="#000000" stroke="#000000" points="2283.9228,-297.718 2292.5183,-291.5238 2281.9361,-291.0058 2283.9228,-297.718"/>
<text text-anchor="middle" x="1662.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1542.4561,-347.9776C1539.1643,-336.9275 1533.3308,-323.3453 1523.3431,-315 1498.0313,-293.8503 1473.3197,-321.5974 1451.3431,-297 1432.8547,-276.3067 1431.2973,-243.5291 1433.1351,-220.1017"/>
<polygon fill="#000000" stroke="#000000" points="1436.625,-220.3791 1434.1698,-210.0727 1429.662,-219.6606 1436.625,-220.3791"/>
<text text-anchor="middle" x="1495.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2312.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2312.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M72.0809,-86.9988C70.0574,-75.9572 69.9374,-62.3765 78.3431,-54 98.4218,-33.9913 1945.8606,-20.4983 2265.4904,-18.3127"/>
<polygon fill="#000000" stroke="#000000" points="2265.8093,-21.8107 2275.7852,-18.2426 2265.7616,-14.8108 2265.8093,-21.8107"/>
<text text-anchor="middle" x="140.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- sequencing_file -->
<g id="node4" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2651.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2651.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2628.2104,-348.5777C2611.6118,-337.0353 2588.224,-322.6579 2565.3431,-315 2496.6455,-292.008 2474.7743,-309.0662 2403.3431,-297 2393.1485,-295.2779 2382.2957,-293.0609 2372.003,-290.7751"/>
<polygon fill="#000000" stroke="#000000" points="2372.4699,-287.2919 2361.9422,-288.4822 2370.9144,-294.1169 2372.4699,-287.2919"/>
<text text-anchor="middle" x="2663.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- family_relationship -->
<g id="node5" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1820.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1820.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1757.9552,-264.8283C1685.7287,-248.4218 1567.6363,-221.5966 1496.7162,-205.4868"/>
<polygon fill="#000000" stroke="#000000" points="1497.1328,-201.9924 1486.6059,-203.1902 1495.5822,-208.8185 1497.1328,-201.9924"/>
<text text-anchor="middle" x="1730.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- genetic_analysis -->
<g id="node6" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1706.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1706.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1706.9703,-347.9207C1708.407,-336.5518 1712.2946,-322.6355 1722.3431,-315 1746.6407,-296.5371 2241.3203,-302.466 2271.3431,-297 2275.0508,-296.325 2278.8514,-295.4414 2282.6317,-294.4279"/>
<polygon fill="#000000" stroke="#000000" points="2283.922,-297.696 2292.5132,-291.4959 2281.9307,-290.9852 2283.922,-297.696"/>
<text text-anchor="middle" x="1792.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1638.6995,-354.457C1620.5005,-349.1098 1601.6411,-341.3218 1586.3431,-330 1556.7173,-308.0744 1566.3756,-287.0908 1540.3431,-261 1521.5384,-242.1532 1496.8589,-225.4101 1476.372,-213.1379"/>
<polygon fill="#000000" stroke="#000000" points="1477.9828,-210.0252 1467.585,-207.9911 1474.4448,-216.0653 1477.9828,-210.0252"/>
<text text-anchor="middle" x="1631.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- cell_line -->
<g id="node9" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1883.3431" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1883.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2292.2181,-291.5222C2285.4194,-293.7144 2278.2189,-295.7048 2271.3431,-297 2249.4829,-301.1177 1886.7149,-298.9209 1871.3431,-315 1865.2235,-321.4012 1865.4942,-330.3099 1868.1798,-338.8931"/>
<polygon fill="#000000" stroke="#000000" points="1865,-340.3643 1872.026,-348.2944 1871.4788,-337.7137 1865,-340.3643"/>
<text text-anchor="middle" x="1907.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2454.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2454.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge38" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2347.5845,-263.4461C2369.6027,-248.7109 2402.7069,-226.5566 2426.2071,-210.8295"/>
<polygon fill="#000000" stroke="#000000" points="2428.3364,-213.616 2434.7004,-205.1455 2424.4431,-207.7986 2428.3364,-213.616"/>
<text text-anchor="middle" x="2432.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2296.9266,-264.6303C2272.1701,-252.438 2234.3602,-235.7311 2199.3431,-228 2133.2559,-213.4091 1686.8956,-199.1672 1509.6649,-194.0193"/>
<polygon fill="#000000" stroke="#000000" points="1509.7494,-190.5204 1499.6524,-193.7299 1509.547,-197.5175 1509.7494,-190.5204"/>
<text text-anchor="middle" x="2280.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_response -->
<g id="node8" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2043.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2043.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1985.3688,-263.999C1939.3016,-252.587 1873.0774,-237.3078 1814.3431,-228 1708.7514,-211.2665 1585.2014,-201.2664 1509.1053,-196.197"/>
<polygon fill="#000000" stroke="#000000" points="1508.8971,-192.6759 1498.6895,-195.5142 1508.4391,-199.6609 1508.8971,-192.6759"/>
<text text-anchor="middle" x="1973.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1908.5729,-350.2674C1929.1918,-338.2848 1959.5373,-322.5963 1988.3431,-315 2110.209,-282.8632 2147.711,-321.4776 2271.3431,-297 2274.9893,-296.2781 2278.7291,-295.3701 2282.4532,-294.3477"/>
<polygon fill="#000000" stroke="#000000" points="2283.6268,-297.6498 2292.199,-291.4234 2281.615,-290.9451 2283.6268,-297.6498"/>
<text text-anchor="middle" x="2028.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge1" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1918.865,-353.3106C1926.2094,-351.1603 1933.959,-349.2286 1941.3431,-348 1975.5539,-342.3077 2541.176,-354.8743 2565.3431,-330 2613.1299,-280.8149 2563.293,-149.8496 2514.3431,-87 2496.592,-64.2082 2485.0942,-64.9064 2458.3431,-54 2425.5816,-40.643 2386.5911,-31.3391 2357.1478,-25.5403"/>
<polygon fill="#000000" stroke="#000000" points="2357.6362,-22.0704 2347.1574,-23.6344 2356.3244,-28.9464 2357.6362,-22.0704"/>
<text text-anchor="middle" x="2614.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- consent_group -->
<g id="node10" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2326.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2326.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge3" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2318.5435,-87.0075C2316.4481,-81.3513 2314.4561,-75.0113 2313.3431,-69 2311.9843,-61.6609 2311.4118,-53.6264 2311.2552,-46.1499"/>
<polygon fill="#000000" stroke="#000000" points="2314.7552,-46.0884 2311.272,-36.0825 2307.7552,-46.0766 2314.7552,-46.0884"/>
<text text-anchor="middle" x="2376.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_personnel -->
<g id="node11" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1998.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1998.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2010.403,-86.8737C2019.0106,-75.485 2031.6384,-61.5642 2046.3431,-54 2083.663,-34.8024 2200.1418,-24.7981 2265.9179,-20.5539"/>
<polygon fill="#000000" stroke="#000000" points="2266.2575,-24.0396 2276.0193,-19.9216 2265.8202,-17.0532 2266.2575,-24.0396"/>
<text text-anchor="middle" x="2115.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2214.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2214.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2181.9608,-265.5076C2151.2445,-253.379 2103.4987,-236.2442 2060.3431,-228 1956.8499,-208.2291 1650.9734,-197.7195 1509.9986,-193.8113"/>
<polygon fill="#000000" stroke="#000000" points="1509.8225,-190.3053 1499.7305,-193.5303 1509.6309,-197.3027 1509.8225,-190.3053"/>
<text text-anchor="middle" x="2155.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- medical_history -->
<g id="node14" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="519.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="519.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M524.938,-260.8738C529.528,-249.3305 537.2709,-235.2331 549.3431,-228 584.079,-207.188 1159.1319,-196.2989 1364.8675,-193.0551"/>
<polygon fill="#000000" stroke="#000000" points="1365.0229,-196.5532 1374.9669,-192.8973 1364.9135,-189.554 1365.0229,-196.5532"/>
<text text-anchor="middle" x="617.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2166.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2166.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge7" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2176.198,-87.2149C2183.0817,-76.2594 2193.1979,-62.6936 2205.3431,-54 2223.8331,-40.7649 2247.5396,-32.1322 2267.9372,-26.6485"/>
<polygon fill="#000000" stroke="#000000" points="2268.805,-30.0393 2277.6474,-24.2031 2267.0954,-23.2513 2268.805,-30.0393"/>
<text text-anchor="middle" x="2256.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2475.0436,-204.4913C2489.69,-214.8937 2504.9866,-230.0451 2494.3431,-243 2468.1713,-274.8557 2443.6684,-252.4196 2403.3431,-261 2393.4368,-263.1079 2382.8538,-265.4539 2372.7583,-267.7373"/>
<polygon fill="#000000" stroke="#000000" points="2371.842,-264.3563 2362.8684,-269.9888 2373.3959,-271.1817 2371.842,-264.3563"/>
<text text-anchor="middle" x="2521.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge28" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2458.3237,-173.9136C2463.5526,-144.9865 2469.0047,-88.1066 2440.3431,-54 2429.5553,-41.1627 2389.7898,-31.3019 2357.4097,-25.1735"/>
<polygon fill="#000000" stroke="#000000" points="2357.6675,-21.663 2347.2024,-23.3158 2356.4141,-28.5498 2357.6675,-21.663"/>
<text text-anchor="middle" x="2486.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="675.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="675.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M679.9139,-260.9594C683.8431,-249.4533 690.7614,-235.3652 702.3431,-228 729.9709,-210.4308 1184.758,-197.913 1364.7955,-193.6241"/>
<polygon fill="#000000" stroke="#000000" points="1365.0503,-197.1192 1374.9647,-193.3837 1364.8848,-190.1211 1365.0503,-197.1192"/>
<text text-anchor="middle" x="745.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- methylation_array_file -->
<g id="node18" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2066.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2066.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2068.2865,-347.7996C2070.4991,-336.5311 2075.2298,-322.7735 2085.3431,-315 2118.2674,-289.6931 2230.7458,-305.7352 2271.3431,-297 2274.9265,-296.229 2278.6044,-295.2944 2282.2714,-294.2612"/>
<polygon fill="#000000" stroke="#000000" points="2283.3298,-297.5977 2291.8796,-291.3405 2281.2939,-290.9003 2283.3298,-297.5977"/>
<text text-anchor="middle" x="2176.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- generic_file -->
<g id="node19" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2889.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2889.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2842.4974,-353.2822C2820.1537,-346.8776 2793.1622,-338.6454 2769.3431,-330 2753.4347,-324.2259 2750.8229,-318.8518 2734.3431,-315 2590.8812,-281.4684 2549.2471,-317.4384 2403.3431,-297 2392.8918,-295.536 2381.7813,-293.3841 2371.2957,-291.0733"/>
<polygon fill="#000000" stroke="#000000" points="2372.0046,-287.6451 2361.4758,-288.8264 2370.4432,-294.4688 2372.0046,-287.6451"/>
<text text-anchor="middle" x="2822.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge36" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2897.6678,-348.1C2904.9403,-330.8051 2914.3431,-303.6732 2914.3431,-279 2914.3431,-279 2914.3431,-279 2914.3431,-105 2914.3431,-71.3365 2889.3195,-67.1796 2858.3431,-54 2813.0602,-34.7334 2483.3679,-23.0706 2359.345,-19.325"/>
<polygon fill="#000000" stroke="#000000" points="2359.137,-15.8173 2349.0371,-19.0176 2358.9283,-22.8142 2359.137,-15.8173"/>
<text text-anchor="middle" x="2967.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2889.0994,-347.862C2887.9423,-336.7657 2884.5375,-323.1756 2875.3431,-315 2865.3909,-306.1505 2414.4732,-245.2275 2401.3431,-243 2365.6776,-236.9494 2357.2875,-232.08 2321.3431,-228 2164.8151,-210.2327 1691.5849,-197.8253 1509.6662,-193.5953"/>
<polygon fill="#000000" stroke="#000000" points="1509.7431,-190.0962 1499.6649,-193.3642 1509.5813,-197.0944 1509.7431,-190.0962"/>
<text text-anchor="middle" x="2830.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node20" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="898.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="898.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M992.8832,-357.0536C1059.0545,-350.1499 1141.3019,-340.1006 1174.3431,-330 1188.599,-325.642 1189.8642,-318.5472 1204.3431,-315 1319.5098,-286.7853 2154.523,-317.3097 2271.3431,-297 2275.056,-296.3545 2278.8603,-295.4915 2282.6431,-294.4917"/>
<polygon fill="#000000" stroke="#000000" points="2283.9241,-297.7631 2292.5284,-291.5811 2281.947,-291.0481 2283.9241,-297.7631"/>
<text text-anchor="middle" x="1290.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M794.0806,-360.9149C636.3639,-352.1416 352.128,-331.6855 321.3431,-297 310.7223,-285.0334 310.9446,-273.1602 321.3431,-261 452.4701,-107.6582 1977.9925,-32.7999 2265.7017,-19.9988"/>
<polygon fill="#000000" stroke="#000000" points="2265.9604,-23.4909 2275.7961,-19.5526 2265.6513,-16.4977 2265.9604,-23.4909"/>
<text text-anchor="middle" x="646.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M892.5173,-347.8257C886.3204,-324.5829 880.0565,-284.5325 901.3431,-261 932.0256,-227.0805 1226.9467,-204.801 1365.7636,-196.1089"/>
<polygon fill="#000000" stroke="#000000" points="1366.121,-199.5935 1375.8854,-195.4819 1365.6882,-192.6069 1366.121,-199.5935"/>
<text text-anchor="middle" x="987.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2276.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2276.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2272.9578,-347.605C2271.9848,-337.4669 2272.3057,-324.9566 2277.3431,-315 2280.2664,-309.2221 2284.5973,-304.1077 2289.4659,-299.6803"/>
<polygon fill="#000000" stroke="#000000" points="2291.8216,-302.2777 2297.4343,-293.2916 2287.4429,-296.8162 2291.8216,-302.2777"/>
<text text-anchor="middle" x="2338.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node22" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2460.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2460.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2441.524,-348.1565C2429.927,-337.7128 2414.4325,-324.713 2399.3431,-315 2388.6217,-308.0986 2376.3758,-301.676 2364.9318,-296.2226"/>
<polygon fill="#000000" stroke="#000000" points="2366.1034,-292.9081 2355.5585,-291.8805 2363.1611,-299.2596 2366.1034,-292.9081"/>
<text text-anchor="middle" x="2489.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1499.1751,-189.1189C1633.998,-182.3018 1964.316,-162.6919 2238.3431,-123 2245.083,-122.0237 2252.0844,-120.8567 2259.0618,-119.5925"/>
<polygon fill="#000000" stroke="#000000" points="2260.0523,-122.9677 2269.2341,-117.6815 2258.7598,-116.0881 2260.0523,-122.9677"/>
<text text-anchor="middle" x="2135.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1328.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1328.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1311.5426,-261.3902C1303.7296,-251.0294 1297.6788,-238.0346 1305.3431,-228 1313.9201,-216.7707 1343.0344,-208.2034 1371.7447,-202.2492"/>
<polygon fill="#000000" stroke="#000000" points="1372.7172,-205.6248 1381.8487,-200.252 1371.3598,-198.7576 1372.7172,-205.6248"/>
<text text-anchor="middle" x="1364.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_arm -->
<g id="node25" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2652.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2652.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2633.0806,-87.9282C2618.9382,-76.3924 2598.7169,-61.8783 2578.3431,-54 2539.2513,-38.8837 2423.7681,-27.2366 2358.5455,-21.6466"/>
<polygon fill="#000000" stroke="#000000" points="2358.7874,-18.1546 2348.5287,-20.8018 2358.1991,-25.1299 2358.7874,-18.1546"/>
<text text-anchor="middle" x="2654.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_admin -->
<g id="node26" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2800.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2800.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2775.9365,-87.9601C2757.8666,-76.2813 2732.1762,-61.5797 2707.3431,-54 2643.357,-34.4696 2448.945,-23.8473 2358.9584,-19.8618"/>
<polygon fill="#000000" stroke="#000000" points="2358.9179,-16.3568 2348.7754,-19.4194 2358.614,-23.3502 2358.9179,-16.3568"/>
<text text-anchor="middle" x="2797.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node27" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="331.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="331.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M382.0389,-361.6502C503.3918,-351.4392 820.2142,-325.971 1085.3431,-315 1217.0234,-309.5511 2141.4788,-319.4643 2271.3431,-297 2275.0566,-296.3576 2278.8612,-295.4968 2282.6442,-294.4985"/>
<polygon fill="#000000" stroke="#000000" points="2283.9243,-297.7703 2292.53,-291.5901 2281.9487,-291.0548 2283.9243,-297.7703"/>
<text text-anchor="middle" x="1127.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M291.7667,-354.1797C258.5013,-341.5124 216.3431,-317.8042 216.3431,-279 216.3431,-279 216.3431,-279 216.3431,-105 216.3431,-51.9378 1954.2892,-23.3733 2265.0714,-18.6896"/>
<polygon fill="#000000" stroke="#000000" points="2265.5732,-22.1825 2275.5196,-18.533 2265.4683,-15.1833 2265.5732,-22.1825"/>
<text text-anchor="middle" x="258.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M326.8957,-347.8013C322.3945,-324.532 318.8159,-284.4531 340.3431,-261 398.5964,-197.5352 445.6746,-237.0631 531.3431,-228 692.3746,-210.9642 1179.7281,-198.0592 1364.8996,-193.6483"/>
<polygon fill="#000000" stroke="#000000" points="1365.1594,-197.1432 1375.0736,-193.4073 1364.9935,-190.1452 1365.1594,-197.1432"/>
<text text-anchor="middle" x="382.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- laboratory_test -->
<g id="node28" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1249.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1249.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1296.6379,-351.1264C1338.0255,-338.8761 1400.0134,-322.3673 1455.3431,-315 1635.1338,-291.0604 2092.7274,-328.5307 2271.3431,-297 2275.0544,-296.3449 2278.8574,-295.4751 2282.6394,-294.4709"/>
<polygon fill="#000000" stroke="#000000" points="2283.9235,-297.7412 2292.5235,-291.5533 2281.9417,-291.0276 2283.9235,-297.7412"/>
<text text-anchor="middle" x="1520.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1171.4846,-360.1217C1129.0441,-355.1221 1082.5266,-346.0812 1069.3431,-330 1065.1165,-324.8444 1067.0397,-321.2561 1069.3431,-315 1080.2362,-285.4143 1088.2721,-277.1596 1115.3431,-261 1157.7127,-235.7082 1289.3449,-213.1526 1370.5988,-201.1424"/>
<polygon fill="#000000" stroke="#000000" points="1371.3487,-204.57 1380.7371,-199.6599 1370.3358,-197.6437 1371.3487,-204.57"/>
<text text-anchor="middle" x="1180.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
