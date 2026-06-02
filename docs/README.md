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
<svg width="3483pt" height="479pt"
 viewBox="0.00 0.00 3483.09 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3479.0923,-475 3479.0923,4 -4,4"/>
<!-- family_relationship -->
<g id="node1" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2102" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2102" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node16" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1659" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1659" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2066.4006,-262.13C2040.7266,-250.6893 2004.9348,-236.2059 1972,-228 1890.8872,-207.7902 1795.0735,-198.8802 1731.0173,-194.981"/>
<polygon fill="#000000" stroke="#000000" points="1731.2034,-191.486 1721.0164,-194.3973 1730.7955,-198.4741 1731.2034,-191.486"/>
<text text-anchor="middle" x="2098.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="88" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="88" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2724" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2724" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M93.4336,-87.0222C97.9834,-75.3864 105.7435,-61.1229 118,-54 146.7978,-37.2642 2329.0584,-20.8468 2677.3619,-18.3318"/>
<polygon fill="#000000" stroke="#000000" points="2677.6178,-21.8301 2687.5923,-18.2581 2677.5673,-14.8303 2677.6178,-21.8301"/>
<text text-anchor="middle" x="166.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_status -->
<g id="node3" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="236" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="236" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M224.1004,-87.2328C218.3695,-76.2845 214.4047,-62.7199 223,-54 245.3992,-31.2761 2336.5008,-19.9253 2677.293,-18.2257"/>
<polygon fill="#000000" stroke="#000000" points="2677.5617,-21.7245 2687.5442,-18.1748 2677.527,-14.7246 2677.5617,-21.7245"/>
<text text-anchor="middle" x="279.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1720" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1720" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1732.6552,-435.36C1741.5874,-424.1766 1754.511,-410.3019 1769,-402 1912.9473,-319.5213 1970.4525,-352.7619 2132,-315 2167.0657,-306.8034 2188.5422,-325.1503 2211,-297 2220.9782,-284.4926 2216.6437,-275.9716 2211,-261 2204.1129,-242.7297 2199.5019,-236.6555 2182,-228 2142.6422,-208.5358 1865.4445,-197.9601 1731.3377,-193.9324"/>
<polygon fill="#000000" stroke="#000000" points="1731.2537,-190.4285 1721.1544,-193.631 1731.0465,-197.4255 1731.2537,-190.4285"/>
<text text-anchor="middle" x="2176.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node20" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2194" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2194" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1741.6757,-436.4419C1758.3227,-424.6796 1782.3902,-409.6644 1806,-402 1866.5631,-382.3395 2047.8551,-372.1273 2139.577,-368.0988"/>
<polygon fill="#000000" stroke="#000000" points="2139.9303,-371.587 2149.7706,-367.6604 2139.6294,-364.5934 2139.9303,-371.587"/>
<text text-anchor="middle" x="1850.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node5" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="248" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="248" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M280.5584,-264.6242C312.1687,-250.9435 358.0678,-231.8827 377,-228 495.1899,-203.7608 1332.2315,-194.7603 1586.1522,-192.57"/>
<polygon fill="#000000" stroke="#000000" points="1586.402,-196.0681 1596.3717,-192.4828 1586.3422,-189.0683 1586.402,-196.0681"/>
<text text-anchor="middle" x="420.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sequencing_file -->
<g id="node6" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1876" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1876" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1886.0385,-434.8695C1893.3531,-423.4791 1904.3537,-409.5579 1918,-402 1954.9915,-381.5126 2070.4021,-372.212 2139.7194,-368.3779"/>
<polygon fill="#000000" stroke="#000000" points="2140.2136,-371.8566 2150.0133,-367.8298 2139.8414,-364.8665 2140.2136,-371.8566"/>
<text text-anchor="middle" x="1984.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2854" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2854" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2856.9055,-434.9279C2864.0376,-385.0873 2878.4233,-242.6495 2829,-141 2823.5391,-129.7685 2774.9503,-74.7357 2745.8197,-42.2111"/>
<polygon fill="#000000" stroke="#000000" points="2748.1547,-39.5727 2738.871,-34.4675 2742.9448,-44.2479 2748.1547,-39.5727"/>
<text text-anchor="middle" x="2900.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2846.8579,-434.9382C2842.5608,-424.9042 2836.643,-412.3873 2830,-402 2802.8052,-359.4771 2798.0125,-344.4233 2757,-315 2670.5581,-252.9845 2638.1254,-249.8179 2534,-228 2456.6102,-211.7842 1927.2043,-198.1506 1731.5098,-193.6104"/>
<polygon fill="#000000" stroke="#000000" points="1731.4085,-190.1072 1721.3304,-193.3755 1731.2469,-197.1054 1731.4085,-190.1072"/>
<text text-anchor="middle" x="2817.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2817.7717,-439.8709C2777.9491,-425.5288 2718.1148,-404.2763 2707,-402 2620.5914,-384.3039 2361.9793,-372.4791 2248.4504,-368.0039"/>
<polygon fill="#000000" stroke="#000000" points="2248.3804,-364.4986 2238.2516,-367.6063 2248.1076,-371.4933 2248.3804,-364.4986"/>
<text text-anchor="middle" x="2792.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2237" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2237" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2209.8246,-435.5851C2203.8775,-430.375 2198.3606,-424.122 2195,-417 2191.7263,-410.0622 2190.5536,-401.9801 2190.4349,-394.3225"/>
<polygon fill="#000000" stroke="#000000" points="2193.9336,-394.4201 2190.8279,-384.2907 2186.939,-394.146 2193.9336,-394.4201"/>
<text text-anchor="middle" x="2266.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2896" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2896" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2870.4917,-88.068C2854.1425,-77.5819 2832.2613,-64.2154 2812,-54 2796.2542,-46.0613 2778.3257,-38.4792 2762.7781,-32.3386"/>
<polygon fill="#000000" stroke="#000000" points="2764.0347,-29.072 2753.446,-28.7112 2761.4986,-35.5964 2764.0347,-29.072"/>
<text text-anchor="middle" x="2894.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- radiology_file -->
<g id="node11" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="393" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="393" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M422.7697,-262.5282C446.2294,-250.478 480.1805,-235.0531 512,-228 616.2748,-204.8864 1350.6507,-195.2354 1586.3613,-192.7109"/>
<polygon fill="#000000" stroke="#000000" points="1586.577,-196.2089 1596.5393,-192.603 1586.5027,-189.2093 1586.577,-196.2089"/>
<text text-anchor="middle" x="571" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- genetic_analysis -->
<g id="node12" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2690" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2690" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2756.9388,-441.234C2782.5184,-435.2582 2807.3949,-427.1045 2815,-417 2819.009,-411.6734 2818.8246,-407.4604 2815,-402 2788.1402,-363.6522 2656.4903,-355.1499 2617,-330 2560.4882,-294.0097 2568.8396,-251.2395 2506,-228 2434.4975,-201.5568 1923.9378,-194.3356 1731.8386,-192.5432"/>
<polygon fill="#000000" stroke="#000000" points="1731.595,-189.041 1721.5635,-192.4497 1731.5312,-196.0407 1731.595,-189.041"/>
<text text-anchor="middle" x="2687" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2631.1589,-439.5505C2610.402,-433.83 2587.2123,-426.302 2567,-417 2555.9137,-411.8979 2555.5046,-406.0722 2544,-402 2490.864,-383.1919 2332.4424,-372.7921 2248.1529,-368.4521"/>
<polygon fill="#000000" stroke="#000000" points="2248.1694,-364.9486 2238.0059,-367.9405 2247.8169,-371.9397 2248.1694,-364.9486"/>
<text text-anchor="middle" x="2637" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study_funding -->
<g id="node13" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3062" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3062" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3032.9564,-88.3145C3011.9461,-76.9607 2982.5259,-62.5054 2955,-54 2892.8095,-34.7832 2817.884,-25.5153 2770.5851,-21.2728"/>
<polygon fill="#000000" stroke="#000000" points="2770.6076,-17.7619 2760.345,-20.3943 2770.0092,-24.7363 2770.6076,-17.7619"/>
<text text-anchor="middle" x="3053" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2460" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2460" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2408.6993,-436.865C2393.0707,-431.2843 2376.0515,-424.5199 2361,-417 2350.0827,-411.5456 2349.1855,-406.8808 2338,-402 2308.4451,-389.1039 2273.3778,-380.2137 2245.2484,-374.4944"/>
<polygon fill="#000000" stroke="#000000" points="2245.7084,-371.0181 2235.2219,-372.5293 2244.362,-377.8874 2245.7084,-371.0181"/>
<text text-anchor="middle" x="2452.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_surgery -->
<g id="node15" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="583" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="583" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M604.7207,-261.2964C620.6374,-249.4628 643.3356,-234.8525 666,-228 753.1731,-201.6433 1372.1807,-194.2735 1586.3208,-192.5006"/>
<polygon fill="#000000" stroke="#000000" points="1586.5407,-195.999 1596.512,-192.4179 1586.4839,-188.9992 1586.5407,-195.999"/>
<text text-anchor="middle" x="744.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- consent_group -->
<g id="node25" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2250" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2250" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1714.5998,-183.8153C1820.8057,-168.1809 2052.686,-134.0462 2173.4466,-116.2693"/>
<polygon fill="#000000" stroke="#000000" points="2173.9789,-119.7287 2183.3626,-114.8096 2172.9594,-112.8034 2173.9789,-119.7287"/>
<text text-anchor="middle" x="2039.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2395" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2395" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge29" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2416.5776,-267.5458C2421.5561,-265.1734 2426.8922,-262.8396 2432,-261 2463.8455,-249.5307 2476.6245,-259.8155 2506,-243 2596.4647,-191.215 2673.6571,-90.8658 2706.7491,-43.6878"/>
<polygon fill="#000000" stroke="#000000" points="2709.7726,-45.4694 2712.5895,-35.2559 2704.0182,-41.4836 2709.7726,-45.4694"/>
<text text-anchor="middle" x="2650" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2375.0158,-266.3082C2354.5507,-254.0461 2321.3801,-236.1657 2290,-228 2186.4669,-201.0588 1874.5581,-194.2731 1731.7817,-192.5689"/>
<polygon fill="#000000" stroke="#000000" points="1731.4258,-189.0647 1721.3865,-192.4503 1731.3459,-196.0643 1731.4258,-189.0647"/>
<text text-anchor="middle" x="2353" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1566" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1566" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1578.9075,-434.8484C1586.3835,-424.7863 1596.2262,-412.2712 1606,-402 1655.0835,-350.4186 1690.0166,-357.8445 1727,-297 1743.2088,-270.3335 1757.0047,-254.1662 1740,-228 1734.4026,-219.387 1726.2173,-212.818 1717.1741,-207.8127"/>
<polygon fill="#000000" stroke="#000000" points="1718.4332,-204.5332 1707.9091,-203.3108 1715.3739,-210.8293 1718.4332,-204.5332"/>
<text text-anchor="middle" x="1779.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1584.7943,-435.2345C1598.4281,-423.5348 1617.93,-409.1103 1638,-402 1684.4394,-385.5477 2009.1037,-372.4814 2139.7408,-367.8318"/>
<polygon fill="#000000" stroke="#000000" points="2140.0476,-371.3232 2149.918,-367.4726 2139.8007,-364.3276 2140.0476,-371.3232"/>
<text text-anchor="middle" x="1703.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- publication -->
<g id="node19" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3220" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3220" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge44" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3194.1195,-88.4875C3174.3524,-76.7485 3146.002,-61.7424 3119,-54 3054.6911,-35.5603 2860.4462,-24.373 2770.5591,-20.0518"/>
<polygon fill="#000000" stroke="#000000" points="2770.5416,-16.5472 2760.3874,-19.5708 2770.2109,-23.5393 2770.5416,-16.5472"/>
<text text-anchor="middle" x="3207" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2210.0535,-348.8941C2234.9179,-320.348 2276.6439,-262.7145 2244,-228 2226.6986,-209.6011 1884.2945,-198.0859 1731.5186,-193.8449"/>
<polygon fill="#000000" stroke="#000000" points="1731.3865,-190.34 1721.2942,-193.5641 1731.1943,-197.3374 1731.3865,-190.34"/>
<text text-anchor="middle" x="2291.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2227.6255,-354.2617C2246.1866,-347.5651 2269.554,-338.7764 2290,-330 2315.3543,-319.1167 2343.4388,-305.3846 2364.1782,-294.912"/>
<polygon fill="#000000" stroke="#000000" points="2365.8241,-298.0017 2373.154,-290.3516 2362.6533,-291.7609 2365.8241,-298.0017"/>
<text text-anchor="middle" x="2358.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node32" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2490" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2490" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2237.4809,-362.638C2279.7358,-358.3865 2345.2197,-349.1652 2399,-330 2419.5836,-322.6648 2440.9789,-310.915 2457.8485,-300.5414"/>
<polygon fill="#000000" stroke="#000000" points="2460.1224,-303.2457 2466.721,-294.9566 2456.3935,-297.3216 2460.1224,-303.2457"/>
<text text-anchor="middle" x="2466.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node21" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="748" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="748" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M776.3913,-264.1373C801.1566,-251.9823 838.4352,-235.6052 873,-228 941.4203,-212.9456 1404.9096,-198.9014 1586.3643,-193.9154"/>
<polygon fill="#000000" stroke="#000000" points="1586.7075,-197.4075 1596.608,-193.6354 1586.5161,-190.4101 1586.7075,-197.4075"/>
<text text-anchor="middle" x="912.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node22" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="943" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="943" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M947.5786,-260.9716C951.5112,-249.4708 958.4303,-235.384 970,-228 995.6493,-211.6301 1414.7727,-198.5638 1586.4943,-193.872"/>
<polygon fill="#000000" stroke="#000000" points="1586.8017,-197.3651 1596.7031,-193.595 1586.6118,-190.3677 1586.8017,-197.3651"/>
<text text-anchor="middle" x="1072" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- generic_file -->
<g id="node23" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="167" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="167" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M106.2368,-446.1032C58.4873,-436.9041 0,-415.5276 0,-366 0,-366 0,-366 0,-105 0,-72.4018 39.806,-66.2205 100,-54 231.2616,-27.3514 2336.0462,-19.2825 2677.3967,-18.1467"/>
<polygon fill="#000000" stroke="#000000" points="2677.4457,-21.6467 2687.434,-18.1136 2677.4225,-14.6467 2677.4457,-21.6467"/>
<text text-anchor="middle" x="53" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M162.4002,-435.032C153.9115,-397.2384 140.5327,-309.0541 186,-261 203.9287,-242.0512 277.2025,-251.098 302,-243 315.7941,-238.4954 316.9482,-231.6213 331,-228 392.053,-212.2659 1317.8956,-197.1428 1586.4819,-193.0686"/>
<polygon fill="#000000" stroke="#000000" points="1586.5676,-196.5678 1596.5135,-192.9169 1586.4617,-189.5686 1586.5676,-196.5678"/>
<text text-anchor="middle" x="212" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M231.8371,-449.9015C403.4844,-441.7285 883.9788,-419.0444 1284,-402 1608.7863,-388.1612 1998.8585,-373.3301 2139.8487,-368.0271"/>
<polygon fill="#000000" stroke="#000000" points="2140.0992,-371.5203 2149.9607,-367.6471 2139.8363,-364.5252 2140.0992,-371.5203"/>
<text text-anchor="middle" x="1337" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_radiation -->
<g id="node24" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1195" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1195" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1183.5352,-260.8919C1178.282,-250.0885 1174.8364,-236.8043 1183,-228 1196.5099,-213.4297 1456.9837,-200.4837 1586.7666,-194.9072"/>
<polygon fill="#000000" stroke="#000000" points="1587.1737,-198.3932 1597.0156,-194.4705 1586.8756,-191.3995 1587.1737,-198.3932"/>
<text text-anchor="middle" x="1266" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge32" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2311.9672,-93.6263C2409.0485,-75.8076 2594.6605,-41.7395 2679.5907,-26.1511"/>
<polygon fill="#000000" stroke="#000000" points="2680.4748,-29.5474 2689.6786,-24.2995 2679.2111,-22.6624 2680.4748,-29.5474"/>
<text text-anchor="middle" x="2578.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- pathology_file -->
<g id="node26" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2053" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2053" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge33" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2052.4658,-434.8148C2053.125,-423.9824 2055.7931,-410.6948 2064,-402 2074.9876,-390.3592 2111.3112,-380.8851 2142.7785,-374.5831"/>
<polygon fill="#000000" stroke="#000000" points="2143.6317,-377.9831 2152.7863,-372.6498 2142.3039,-371.1102 2143.6317,-377.9831"/>
<text text-anchor="middle" x="2125" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node27" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3388" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3388" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge14" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3354.9871,-88.2526C3330.1037,-76.4757 3294.7756,-61.526 3262,-54 3169.1011,-32.6683 2883.5612,-22.4941 2770.6492,-19.2247"/>
<polygon fill="#000000" stroke="#000000" points="2770.6857,-15.7244 2760.5902,-18.9386 2770.4866,-22.7216 2770.6857,-15.7244"/>
<text text-anchor="middle" x="3377.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- medical_history -->
<g id="node28" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1441" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1441" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1442.4582,-260.8662C1444.3269,-249.7716 1448.5413,-236.1818 1458,-228 1477.252,-211.3471 1538.1552,-202.0491 1587.9219,-197.0946"/>
<polygon fill="#000000" stroke="#000000" points="1588.4089,-200.5641 1598.0318,-196.1315 1587.7449,-193.5957 1588.4089,-200.5641"/>
<text text-anchor="middle" x="1526" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_other -->
<g id="node29" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="1631" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1631" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1610.3582,-261.1836C1601.6529,-251.4449 1594.8078,-239.1314 1601,-228 1604.3289,-222.0157 1609.1099,-216.8988 1614.5178,-212.5627"/>
<polygon fill="#000000" stroke="#000000" points="1616.6164,-215.3659 1622.7936,-206.7582 1612.5968,-209.635 1616.6164,-215.3659"/>
<text text-anchor="middle" x="1670.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- treatment_response -->
<g id="node30" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1879" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1879" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1844.4364,-261.909C1822.7476,-251.4884 1794.0502,-238.2494 1768,-228 1750.0053,-220.9201 1729.9924,-214.0353 1712.0764,-208.2148"/>
<polygon fill="#000000" stroke="#000000" points="1712.9562,-204.8213 1702.3649,-205.0962 1710.8159,-211.4861 1712.9562,-204.8213"/>
<text text-anchor="middle" x="1885" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- clinical_measure_file -->
<g id="node31" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1328" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1328" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1222.7452,-448.5921C949.6006,-436.2388 233.6273,-397.6867 152,-330 115.9876,-300.1379 94.2801,-262.3873 126,-228 216.2464,-130.1645 2335.6534,-34.7571 2677.611,-19.9758"/>
<polygon fill="#000000" stroke="#000000" points="2677.8226,-23.4701 2687.6626,-19.5425 2677.5211,-16.4766 2677.8226,-23.4701"/>
<text text-anchor="middle" x="212" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1323.9169,-434.7785C1316.7338,-397.6542 1306.1919,-312.429 1347,-261 1376.4605,-223.872 1505.5951,-205.567 1588.219,-197.4985"/>
<polygon fill="#000000" stroke="#000000" points="1588.6794,-200.9707 1598.3042,-196.5418 1588.0183,-194.002 1588.6794,-200.9707"/>
<text text-anchor="middle" x="1408" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1356.496,-435.3964C1377.1799,-423.61 1406.2831,-409.0149 1434,-402 1501.7422,-384.855 1976.7519,-371.457 2139.4686,-367.3257"/>
<polygon fill="#000000" stroke="#000000" points="2139.8186,-370.8181 2149.7272,-367.067 2139.6421,-363.8203 2139.8186,-370.8181"/>
<text text-anchor="middle" x="1520" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge3" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2539.0153,-276.2027C2593.8978,-272.1421 2678.3889,-262.8155 2703,-243 2761.0777,-196.239 2744.4958,-94.898 2732.099,-45.7902"/>
<polygon fill="#000000" stroke="#000000" points="2735.414,-44.6358 2729.4689,-35.8662 2728.6476,-46.4291 2735.414,-44.6358"/>
<text text-anchor="middle" x="2784.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2464.1914,-263.4121C2442.7494,-251.3416 2411.0071,-235.4619 2381,-228 2319.2335,-212.6406 1902.0062,-199.0183 1731.4403,-194.0244"/>
<polygon fill="#000000" stroke="#000000" points="1731.3987,-190.5218 1721.301,-193.7292 1731.1949,-197.5188 1731.3987,-190.5218"/>
<text text-anchor="middle" x="2461.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
</g>
</svg>
</div>
