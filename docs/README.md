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
<svg width="3837pt" height="392pt"
 viewBox="0.00 0.00 3836.54 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3832.5404,-388 3832.5404,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2942.5404" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2942.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2871.5404" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2871.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2937.3049,-260.7432C2933.7265,-250.4076 2928.2265,-237.6576 2920.5404,-228 2915.0598,-221.1136 2907.9516,-214.8942 2900.8574,-209.6379"/>
<polygon fill="#000000" stroke="#000000" points="2902.8443,-206.7565 2892.6341,-203.9275 2898.8516,-212.5062 2902.8443,-206.7565"/>
<text text-anchor="middle" x="2966.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1810.5404" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1810.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2907.2052,-267.9903C2898.8306,-265.5431 2889.9016,-263.0653 2881.5404,-261 2841.9385,-251.2178 2830.7654,-254.198 2791.5404,-243 2773.2831,-237.7879 2770.1542,-231.7442 2751.5404,-228 2667.462,-211.0873 2089.0129,-197.7136 1883.1109,-193.44"/>
<polygon fill="#000000" stroke="#000000" points="1883.0757,-189.9387 1873.0056,-193.2314 1882.9312,-196.9372 1883.0757,-189.9387"/>
<text text-anchor="middle" x="2828.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node25" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3306.5404" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3306.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge29" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2980.8068,-269.8539C3046.6167,-254.1246 3181.2651,-221.9422 3255.1686,-204.2784"/>
<polygon fill="#000000" stroke="#000000" points="3256.2677,-207.6144 3265.1801,-201.8856 3254.6404,-200.8062 3256.2677,-207.6144"/>
<text text-anchor="middle" x="3182.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="626.5404" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="626.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M640.0125,-261.0889C650.0215,-249.3224 664.7975,-234.8779 681.5404,-228 730.3829,-207.9357 1496.3668,-196.1487 1738.0632,-192.915"/>
<polygon fill="#000000" stroke="#000000" points="1738.1973,-196.4136 1748.1499,-192.781 1738.1043,-189.4143 1738.1973,-196.4136"/>
<text text-anchor="middle" x="761.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="849.5404" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="849.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M844.2512,-260.5647C842.3388,-249.6382 842.3487,-236.3395 850.5404,-228 866.054,-212.2065 1516.5421,-197.8409 1737.7714,-193.4038"/>
<polygon fill="#000000" stroke="#000000" points="1738.0493,-196.8991 1747.9774,-193.2001 1737.9095,-189.9005 1738.0493,-196.8991"/>
<text text-anchor="middle" x="933.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2867.541,-210.2866C2866.2913,-220.6321 2866.5413,-233.3821 2872.5404,-243 2878.2404,-252.1384 2887.0652,-259.0621 2896.5507,-264.2686"/>
<polygon fill="#000000" stroke="#000000" points="2895.2433,-267.5247 2905.767,-268.7505 2898.3047,-261.2296 2895.2433,-267.5247"/>
<text text-anchor="middle" x="2896.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2424.5404" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2424.5404" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge26" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2844.7015,-186.0941C2819.5301,-180.0895 2781.1392,-169.7234 2749.5404,-156 2723.0426,-144.492 2714.5268,-142.8529 2693.5404,-123 2666.7656,-97.6715 2678.5417,-73.9332 2647.5404,-54 2619.0488,-35.6805 2527.466,-25.6923 2470.9132,-21.1333"/>
<polygon fill="#000000" stroke="#000000" points="2471.0259,-17.6315 2460.7843,-20.3444 2470.4823,-24.6104 2471.0259,-17.6315"/>
<text text-anchor="middle" x="2717.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node5" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1025.5404" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1025.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1020.3637,-261.0835C1018.3744,-250.0755 1018.2602,-236.5007 1026.5404,-228 1051.1335,-202.7519 1548.2791,-194.7988 1737.9129,-192.6778"/>
<polygon fill="#000000" stroke="#000000" points="1738.1019,-196.1761 1748.0629,-192.5666 1738.0251,-189.1765 1738.1019,-196.1761"/>
<text text-anchor="middle" x="1070.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3111.5404" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="3111.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3104.7178,-347.9404C3099.6493,-336.8754 3091.6778,-323.2907 3080.5404,-315 3066.6358,-304.6495 3026.6599,-294.8521 2993.2907,-288.0991"/>
<polygon fill="#000000" stroke="#000000" points="2993.6716,-284.6068 2983.1831,-286.1038 2992.3159,-291.4742 2993.6716,-284.6068"/>
<text text-anchor="middle" x="3160.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2110.5404" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2110.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2094.5591,-261.9752C2082.7159,-250.4616 2065.564,-235.9547 2047.5404,-228 2018.3416,-215.1133 1939.0581,-204.7458 1880.1853,-198.5046"/>
<polygon fill="#000000" stroke="#000000" points="1880.4951,-195.018 1870.1863,-197.4631 1879.7699,-201.9803 1880.4951,-195.018"/>
<text text-anchor="middle" x="2112.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_other -->
<g id="node8" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2263.5404" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2263.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2234.333,-261.8893C2213.177,-250.3352 2183.4982,-235.8151 2155.5404,-228 2105.7297,-214.0763 1967.4438,-202.6302 1881.8352,-196.6053"/>
<polygon fill="#000000" stroke="#000000" points="1881.8846,-193.1004 1871.6657,-195.8977 1881.3986,-200.0835 1881.8846,-193.1004"/>
<text text-anchor="middle" x="2265.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- study_funding -->
<g id="node9" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1689.5404" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1689.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1712.9996,-87.6912C1730.4091,-75.8822 1755.2439,-61.1355 1779.5404,-54 1836.3703,-37.3099 2238.607,-23.6512 2377.5066,-19.3857"/>
<polygon fill="#000000" stroke="#000000" points="2377.9268,-22.8747 2387.8155,-19.0716 2377.7135,-15.8779 2377.9268,-22.8747"/>
<text text-anchor="middle" x="1841.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_arm -->
<g id="node10" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1844.5404" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1844.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1869.4222,-88.6006C1888.7719,-76.7565 1916.7469,-61.5655 1943.5404,-54 2024.2783,-31.2025 2273.2931,-22.038 2377.7071,-19.1315"/>
<polygon fill="#000000" stroke="#000000" points="2378.0392,-22.6239 2387.9406,-18.8539 2377.8493,-15.6265 2378.0392,-22.6239"/>
<text text-anchor="middle" x="1992.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="3328.5404" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="3328.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3301.3775,-348.5016C3282.3135,-337.0797 3255.81,-322.8749 3230.5404,-315 3188.0125,-301.7468 3066.8552,-289.6285 2995.9635,-283.3991"/>
<polygon fill="#000000" stroke="#000000" points="2996.1497,-279.9021 2985.8842,-282.5233 2995.5437,-286.8759 2996.1497,-279.9021"/>
<text text-anchor="middle" x="3358.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2565.5404" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2565.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2591.9341,-349.9563C2612.7645,-338.1361 2642.9775,-322.812 2671.5404,-315 2761.8974,-290.2872 2789.4844,-314.3438 2881.5404,-297 2887.0336,-295.965 2892.7397,-294.6355 2898.3597,-293.1684"/>
<polygon fill="#000000" stroke="#000000" points="2899.6136,-296.453 2908.3181,-290.4128 2897.7468,-289.7065 2899.6136,-296.453"/>
<text text-anchor="middle" x="2716.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2586.5099,-349.0586C2595.577,-339.5762 2603.1746,-327.2285 2598.5404,-315 2580.2417,-266.7151 2568.0707,-250.3875 2521.5404,-228 2465.126,-200.8569 2052.6454,-194.1285 1883.0526,-192.5026"/>
<polygon fill="#000000" stroke="#000000" points="1883.0002,-189.002 1872.9682,-192.4092 1882.9353,-196.0017 1883.0002,-189.002"/>
<text text-anchor="middle" x="2636.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group -->
<g id="node14" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2001.5404" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2001.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1844.2477,-176.6464C1875.4749,-162.4225 1922.1495,-141.1623 1956.5488,-125.4935"/>
<polygon fill="#000000" stroke="#000000" points="1958.253,-128.5633 1965.9026,-121.2329 1955.3513,-122.193 1958.253,-128.5633"/>
<text text-anchor="middle" x="1968.0404" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge43" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2019.5022,-87.458C2032.5453,-75.8607 2051.2278,-61.4668 2070.5404,-54 2125.5196,-32.7434 2295.2509,-23.1731 2378.0955,-19.6783"/>
<polygon fill="#000000" stroke="#000000" points="2378.3844,-23.1695 2388.2327,-19.2628 2378.0977,-16.1754 2378.3844,-23.1695"/>
<text text-anchor="middle" x="2134.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_surgery -->
<g id="node15" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1945.5404" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1945.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1918.5456,-261.6033C1897.2579,-247.8846 1867.4411,-228.6694 1844.5279,-213.9031"/>
<polygon fill="#000000" stroke="#000000" points="1846.4181,-210.9574 1836.1164,-208.4823 1842.6261,-216.8414 1846.4181,-210.9574"/>
<text text-anchor="middle" x="1965.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- treatment_radiation -->
<g id="node16" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="403.5404" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="403.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M426.1302,-261.2304C442.6619,-249.3657 466.1934,-234.7454 489.5404,-228 549.7578,-210.6021 1470.0546,-196.6706 1737.9208,-192.9682"/>
<polygon fill="#000000" stroke="#000000" points="1737.9762,-196.4679 1747.9271,-192.8305 1737.8798,-189.4685 1737.9762,-196.4679"/>
<text text-anchor="middle" x="572.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- study_status -->
<g id="node17" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2168.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2168.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2182.6878,-87.088C2192.6163,-75.7898 2206.8776,-61.8893 2222.5404,-54 2249.2532,-40.5448 2327.8423,-29.2512 2378.7533,-23.0731"/>
<polygon fill="#000000" stroke="#000000" points="2379.3396,-26.5281 2388.8555,-21.87 2378.5118,-19.5772 2379.3396,-26.5281"/>
<text text-anchor="middle" x="2279.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1528.5404" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1528.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1609.2871,-362.9571C1806.7448,-355.4305 2299.1611,-336.1092 2315.5404,-330 2325.6209,-326.2402 2324.436,-318.6952 2334.5404,-315 2391.6519,-294.1143 2821.5056,-306.6833 2881.5404,-297 2887.2667,-296.0764 2893.2115,-294.7739 2899.044,-293.2869"/>
<polygon fill="#000000" stroke="#000000" points="2899.9743,-296.6611 2908.6951,-290.6445 2898.1258,-289.9095 2899.9743,-296.6611"/>
<text text-anchor="middle" x="2400.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1453.6597,-358.4509C1342.4996,-346.4807 1144.5877,-321.9364 1123.5404,-297 1113.2204,-284.7731 1112.9487,-272.9924 1123.5404,-261 1163.7099,-215.518 1570.1445,-198.8171 1738.3029,-193.8224"/>
<polygon fill="#000000" stroke="#000000" points="1738.4114,-197.3208 1748.3051,-193.5308 1738.2073,-190.3237 1738.4114,-197.3208"/>
<text text-anchor="middle" x="1189.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node19" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1392.5404" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1392.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1390.28,-260.8776C1389.9839,-249.7875 1391.7644,-236.1985 1400.5404,-228 1424.6231,-205.502 1626.932,-196.7341 1738.0764,-193.5913"/>
<polygon fill="#000000" stroke="#000000" points="1738.3108,-197.0863 1748.2109,-193.3131 1738.1186,-190.0889 1738.3108,-197.0863"/>
<text text-anchor="middle" x="1502.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_personnel -->
<g id="node20" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2343.5404" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2343.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2339.3545,-86.5937C2338.0425,-76.2082 2338.2925,-63.4582 2344.5404,-54 2352.8615,-41.4032 2366.733,-33.164 2380.609,-27.7966"/>
<polygon fill="#000000" stroke="#000000" points="2381.8267,-31.0791 2390.148,-24.5212 2379.5533,-24.4585 2381.8267,-31.0791"/>
<text text-anchor="middle" x="2414.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- genetic_analysis -->
<g id="node21" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2725.5404" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2725.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2741.9979,-348.1787C2753.4144,-336.9188 2769.5695,-323.0269 2786.5404,-315 2825.3876,-296.6259 2839.7692,-307.0937 2881.5404,-297 2886.6418,-295.7673 2891.9517,-294.3718 2897.2169,-292.9165"/>
<polygon fill="#000000" stroke="#000000" points="2898.5593,-296.1736 2907.2202,-290.0712 2896.6442,-289.4406 2898.5593,-296.1736"/>
<text text-anchor="middle" x="2856.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2675.3955,-351.0824C2665.9276,-345.9354 2657.2231,-339.0841 2651.5404,-330 2648.0047,-324.3481 2648.1373,-320.7327 2651.5404,-315 2660.0685,-300.634 2676.0122,-311.366 2684.5404,-297 2692.7078,-283.2416 2694.4199,-273.5855 2684.5404,-261 2646.4011,-212.4149 2610.6658,-236.8765 2549.5404,-228 2422.433,-209.5418 2042.9369,-197.9531 1882.9461,-193.7653"/>
<polygon fill="#000000" stroke="#000000" points="1882.8177,-190.2609 1872.7302,-193.5002 1882.636,-197.2586 1882.8177,-190.2609"/>
<text text-anchor="middle" x="2761.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1613.5404" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1613.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1608.6889,-260.9647C1606.9413,-250.1887 1606.9706,-236.9078 1614.5404,-228 1630.5221,-209.1935 1689.5664,-200.1677 1738.7113,-195.862"/>
<polygon fill="#000000" stroke="#000000" points="1739.0317,-199.3476 1748.7103,-195.0377 1738.4565,-192.3713 1739.0317,-199.3476"/>
<text text-anchor="middle" x="1673.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node24" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2518.5404" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2518.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2508.8141,-87.0768C2502.54,-76.6049 2493.6727,-63.6034 2483.5404,-54 2476.3656,-47.1998 2467.6986,-41.0481 2459.2427,-35.8318"/>
<polygon fill="#000000" stroke="#000000" points="2460.9746,-32.7901 2450.5787,-30.7465 2457.4312,-38.827 2460.9746,-32.7901"/>
<text text-anchor="middle" x="2553.0404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3345.3802,-203.2546C3370.4462,-212.4037 3395.7631,-226.4748 3380.5404,-243 3355.0372,-270.6853 3108.5841,-277.0797 2996.9772,-278.5565"/>
<polygon fill="#000000" stroke="#000000" points="2996.8855,-275.0573 2986.9296,-278.681 2996.9722,-282.0568 2996.8855,-275.0573"/>
<text text-anchor="middle" x="3425.0404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3257.2391,-190.101C3141.4937,-184.9378 2855.8635,-167.8935 2772.5404,-123 2753.9521,-112.9849 2758.4153,-99.6911 2741.5404,-87 2713.4075,-65.8421 2703.2933,-63.9925 2669.5404,-54 2602.1909,-34.0612 2521.0182,-24.9095 2471.0975,-20.8973"/>
<polygon fill="#000000" stroke="#000000" points="2471.1741,-17.393 2460.9355,-20.1172 2470.6382,-24.3725 2471.1741,-17.393"/>
<text text-anchor="middle" x="2813.0404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pathology_file -->
<g id="node26" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="3538.5404" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="3538.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3508.0279,-349.3718C3497.3481,-343.411 3485.3318,-336.5444 3474.5404,-330 3464.1053,-323.6717 3463.1084,-318.8882 3451.5404,-315 3409.3154,-300.8074 3119.2288,-286.6935 2996.8335,-281.296"/>
<polygon fill="#000000" stroke="#000000" points="2996.7128,-277.7874 2986.5693,-280.8465 2996.4065,-284.7807 2996.7128,-277.7874"/>
<text text-anchor="middle" x="3535.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- synonym -->
<g id="node27" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3718.5404" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3718.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3679.1272,-353.9832C3660.6245,-347.7621 3638.5184,-339.4816 3619.5404,-330 3608.6231,-324.5456 3608.1384,-318.7978 3596.5404,-315 3540.3432,-296.5983 3143.6952,-284.3331 2996.9515,-280.3811"/>
<polygon fill="#000000" stroke="#000000" points="2996.9158,-276.879 2986.826,-280.1109 2996.729,-283.8765 2996.9158,-276.879"/>
<text text-anchor="middle" x="3662.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3718.3705,-347.7777C3717.2429,-336.6478 3713.8432,-323.0519 3704.5404,-315 3674.9931,-289.4258 3045.5023,-231.0078 3006.5404,-228 2786.3677,-211.0028 2106.9883,-197.4077 1883.0011,-193.2873"/>
<polygon fill="#000000" stroke="#000000" points="1883.062,-189.7879 1872.9995,-193.104 1882.9337,-196.7867 1883.062,-189.7879"/>
<text text-anchor="middle" x="3666.0404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge42" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3726.865,-348.1C3734.1375,-330.8051 3743.5404,-303.6732 3743.5404,-279 3743.5404,-279 3743.5404,-279 3743.5404,-105 3743.5404,-39.8789 2706.3497,-21.8395 2471.4502,-18.589"/>
<polygon fill="#000000" stroke="#000000" points="2471.2413,-15.0859 2461.1946,-18.4495 2471.1461,-22.0853 2471.2413,-15.0859"/>
<text text-anchor="middle" x="3786.0404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node28" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="108.5404" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="108.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M215.8834,-363.2723C518.4247,-355.5915 1403.9121,-333.1588 2139.5404,-315 2304.4275,-310.9298 2718.5955,-322.5602 2881.5404,-297 2887.2707,-296.1011 2893.2178,-294.8132 2899.0514,-293.3338"/>
<polygon fill="#000000" stroke="#000000" points="2899.9788,-296.7088 2908.7036,-290.6981 2898.1348,-289.956 2899.9788,-296.7088"/>
<text text-anchor="middle" x="2225.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M103.9158,-347.9582C99.0968,-324.482 95.041,-283.78 117.5404,-261 170.2619,-207.6209 378.6596,-232.6645 453.5404,-228 706.7315,-212.2282 1493.7437,-197.524 1737.6898,-193.2455"/>
<polygon fill="#000000" stroke="#000000" points="1737.9251,-196.742 1747.8623,-193.0676 1737.8026,-189.7431 1737.9251,-196.742"/>
<text text-anchor="middle" x="203.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M92.4518,-348.1027C79.1867,-331.4504 62.5404,-305.3116 62.5404,-279 62.5404,-279 62.5404,-279 62.5404,-105 62.5404,-44.8385 2045.7729,-21.8825 2377.6891,-18.4618"/>
<polygon fill="#000000" stroke="#000000" points="2377.9494,-21.9595 2387.913,-18.3573 2377.8777,-14.9598 2377.9494,-21.9595"/>
<text text-anchor="middle" x="148.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node29" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2925.5404" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2925.5404" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge36" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2889.7166,-90.0463C2860.1497,-78.3439 2816.8216,-62.6497 2777.5404,-54 2669.6096,-30.2336 2539.5917,-22.0979 2471.4491,-19.357"/>
<polygon fill="#000000" stroke="#000000" points="2471.1826,-15.8444 2461.0568,-18.9619 2470.9165,-22.8394 2471.1826,-15.8444"/>
<text text-anchor="middle" x="2882.5404" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node30" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2920.5404" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2920.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2925.0988,-347.9735C2928.1076,-336.0751 2932.1091,-320.2508 2935.5204,-306.7606"/>
<polygon fill="#000000" stroke="#000000" points="2938.9293,-307.5563 2937.9878,-297.0034 2932.143,-305.8401 2938.9293,-307.5563"/>
<text text-anchor="middle" x="3005.0404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- generic_file -->
<g id="node31" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2109.5404" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2109.5404" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2174.4125,-362.9578C2246.8744,-358.7634 2367.4135,-349.4015 2469.5404,-330 2493.591,-325.431 2498.3839,-318.9716 2522.5404,-315 2680.18,-289.0826 2724.0474,-323.7945 2881.5404,-297 2887.0511,-296.0625 2892.7677,-294.7918 2898.3934,-293.3564"/>
<polygon fill="#000000" stroke="#000000" points="2899.6349,-296.6455 2908.3572,-290.6313 2897.7881,-289.8935 2899.6349,-296.6455"/>
<text text-anchor="middle" x="2575.5404" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2043.9968,-363.7832C1946.5133,-358.952 1770.5812,-343.8125 1731.5404,-297 1708.3689,-269.2159 1744.2243,-235.56 1774.8658,-213.9701"/>
<polygon fill="#000000" stroke="#000000" points="1777.021,-216.737 1783.3166,-208.2155 1773.081,-210.951 1777.021,-216.737"/>
<text text-anchor="middle" x="1784.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2109.4689,-347.7658C2110.4821,-336.4834 2113.8451,-322.7231 2123.5404,-315 2160.4224,-285.6202 2510.4556,-326.1235 2547.5404,-297 2591.5483,-262.4397 2649.2142,-97.1102 2613.5404,-54 2595.8464,-32.6176 2521.4829,-23.8257 2471.4787,-20.2886"/>
<polygon fill="#000000" stroke="#000000" points="2471.416,-16.7769 2461.2072,-19.6109 2470.9551,-23.7617 2471.416,-16.7769"/>
<text text-anchor="middle" x="2664.5404" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- medical_history -->
<g id="node32" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2453.5404" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2453.5404" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2423.3457,-262.1018C2400.735,-250.331 2368.6446,-235.4547 2338.5404,-228 2254.2873,-207.1364 2006.7947,-197.4598 1882.9105,-193.8218"/>
<polygon fill="#000000" stroke="#000000" points="1882.8587,-190.3189 1872.7619,-193.5292 1882.6569,-197.316 1882.8587,-190.3189"/>
<text text-anchor="middle" x="2449.5404" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
</g>
</svg>
</div>
