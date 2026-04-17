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
<svg width="3647pt" height="479pt"
 viewBox="0.00 0.00 3646.74 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3642.7422,-475 3642.7422,4 -4,4"/>
<!-- consent_group -->
<g id="node1" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1967.7422" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1967.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- study -->
<g id="node29" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2882.7422" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2882.7422" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge44" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2024.0916,-92.3264C2079.2589,-80.4377 2165.842,-63.157 2241.7422,-54 2463.154,-27.2878 2730.0355,-20.3398 2836.0525,-18.579"/>
<polygon fill="#000000" stroke="#000000" points="2836.1575,-22.0779 2846.1008,-18.4198 2836.0466,-15.0788 2836.1575,-22.0779"/>
<text text-anchor="middle" x="2305.2422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1080.7422" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1080.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1592.7422" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1592.7422" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1071.2486,-260.7829C1067.0501,-249.9385 1064.6709,-236.6494 1072.7422,-228 1087.7815,-211.8836 1381.2443,-199.4429 1520.5307,-194.4208"/>
<polygon fill="#000000" stroke="#000000" points="1520.8226,-197.9127 1530.6913,-194.0577 1520.5726,-190.9171 1520.8226,-197.9127"/>
<text text-anchor="middle" x="1140.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- family_relationship -->
<g id="node3" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1958.7422" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1958.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1931.7785,-261.6453C1909.928,-247.7148 1881.8038,-230.1357 1875.7422,-228 1837.786,-214.6266 1733.9793,-203.7252 1663.2204,-197.5464"/>
<polygon fill="#000000" stroke="#000000" points="1663.2955,-194.04 1653.0321,-196.6693 1662.6951,-201.0142 1663.2955,-194.04"/>
<text text-anchor="middle" x="1980.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- survival -->
<g id="node4" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2124.7422" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2124.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2106.6234,-262.2808C2091.7592,-248.9648 2071.6144,-231.9267 2061.7422,-228 2025.854,-213.7255 1786.8835,-200.8886 1664.5815,-195.1599"/>
<polygon fill="#000000" stroke="#000000" points="1664.7023,-191.6619 1654.5506,-194.6938 1664.3773,-198.6543 1664.7023,-191.6619"/>
<text text-anchor="middle" x="2122.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- clinical_measure_file -->
<g id="node5" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2316.7422" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2316.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2320.3199,-434.9866C2328.4669,-388.0893 2342.3233,-263.3971 2267.7422,-228 2214.4775,-202.7199 1828.8766,-194.9454 1665.5382,-192.771"/>
<polygon fill="#000000" stroke="#000000" points="1665.1512,-189.2658 1655.1067,-192.6357 1665.0604,-196.2652 1665.1512,-189.2658"/>
<text text-anchor="middle" x="2411.7422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- sample -->
<g id="node18" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1799.7422" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1799.7422" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge42" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2235.8123,-440.8566C2202.8695,-435.006 2164.642,-427.0486 2130.7422,-417 2113.7295,-411.9571 2110.9195,-406.4502 2093.7422,-402 2011.7972,-380.7702 1913.6726,-371.9576 1854.0598,-368.3713"/>
<polygon fill="#000000" stroke="#000000" points="1853.9345,-364.8584 1843.7505,-367.7802 1853.5337,-371.8469 1853.9345,-364.8584"/>
<text text-anchor="middle" x="2216.7422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge41" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2420.0801,-447.3289C2509.4155,-441.5779 2631.2848,-431.4591 2677.7422,-417 2936.0571,-336.6038 3073.1922,-355.9595 3210.7422,-123 3226.3358,-96.5901 3230.5518,-76.5301 3209.7422,-54 3191.0724,-33.7865 3015.2066,-23.6052 2929.3933,-19.8066"/>
<polygon fill="#000000" stroke="#000000" points="2929.2852,-16.2988 2919.1436,-19.3643 2928.9834,-23.2923 2929.2852,-16.2988"/>
<text text-anchor="middle" x="3218.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment_other -->
<g id="node6" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2431.7422" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2431.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2392.0322,-262.9185C2358.1957,-249.4983 2312.0716,-231.9488 2292.7422,-228 2174.5918,-203.8627 1819.8127,-195.5217 1665.6207,-192.9856"/>
<polygon fill="#000000" stroke="#000000" points="1665.3701,-189.4812 1655.315,-192.8198 1665.2574,-196.4803 1665.3701,-189.4812"/>
<text text-anchor="middle" x="2407.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- genetic_analysis -->
<g id="node7" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="87.7422" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="87.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M88.0874,-434.8311C89.5359,-406.2943 96.1341,-350.5614 124.7422,-315 177.4478,-249.484 211.3293,-249.0275 292.7422,-228 352.37,-212.5992 1254.868,-197.2972 1520.0186,-193.115"/>
<polygon fill="#000000" stroke="#000000" points="1520.3571,-196.6102 1530.3008,-192.9534 1520.247,-189.6111 1520.3571,-196.6102"/>
<text text-anchor="middle" x="194.7422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M168.6546,-445.8918C296.1532,-434.9278 551.659,-413.9139 768.7422,-402 1141.9749,-381.5163 1591.89,-370.5045 1745.3925,-367.1348"/>
<polygon fill="#000000" stroke="#000000" points="1745.5782,-370.6317 1755.4996,-366.9146 1745.4257,-363.6333 1745.5782,-370.6317"/>
<text text-anchor="middle" x="838.7422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2473.7422" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2473.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge24" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2462.3079,-86.92C2457.0661,-76.1272 2453.6219,-62.8443 2461.7422,-54 2486.6541,-26.867 2731.6274,-20.1497 2836.0165,-18.5147"/>
<polygon fill="#000000" stroke="#000000" points="2836.3124,-22.0108 2846.2597,-18.3636 2836.2091,-15.0116 2836.3124,-22.0108"/>
<text text-anchor="middle" x="2512.7422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- generic_file -->
<g id="node9" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="3171.7422" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="3171.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3173.0906,-434.9785C3173.7824,-411.5248 3171.1694,-370.8476 3147.7422,-348 2955.2366,-160.2566 2821.7531,-259.7991 2554.7422,-228 2382.7342,-207.5151 1858.5381,-196.6008 1665.2883,-193.1891"/>
<polygon fill="#000000" stroke="#000000" points="1665.2965,-189.6888 1655.2368,-193.0132 1665.1739,-196.6877 1665.2965,-189.6888"/>
<text text-anchor="middle" x="3178.7422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3107.408,-448.9205C2873.3678,-434.0798 2069.6895,-383.1176 1853.6005,-369.4152"/>
<polygon fill="#000000" stroke="#000000" points="1853.663,-365.9122 1843.4616,-368.7723 1853.22,-372.8982 1853.663,-365.9122"/>
<text text-anchor="middle" x="2620.7422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge17" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3184.3026,-434.861C3191.5841,-424.8028 3201.1812,-412.2874 3210.7422,-402 3250.3922,-359.3376 3263.8163,-352.0656 3308.7422,-315 3349.3349,-281.5095 3372.5124,-286.076 3402.7422,-243 3451.292,-173.8189 3494.4016,-100.372 3423.7422,-54 3382.9748,-27.2454 3053.7639,-20.2165 2929.7605,-18.509"/>
<polygon fill="#000000" stroke="#000000" points="2929.4986,-15.0054 2919.4532,-18.3729 2929.4061,-22.0047 2929.4986,-15.0054"/>
<text text-anchor="middle" x="3465.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2662.7422" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2662.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2674.3147,-87.2031C2682.5701,-75.9535 2694.6732,-62.064 2708.7422,-54 2730.2818,-41.6542 2793.5235,-30.6013 2837.5109,-24.0962"/>
<polygon fill="#000000" stroke="#000000" points="2838.0167,-27.5596 2847.4108,-22.6604 2837.0119,-20.6321 2838.0167,-27.5596"/>
<text text-anchor="middle" x="2765.2422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2810.7422" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2810.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2817.2424,-86.8221C2821.4924,-76.5128 2827.7424,-63.7628 2835.7422,-54 2840.2942,-48.4448 2845.8628,-43.2402 2851.554,-38.6085"/>
<polygon fill="#000000" stroke="#000000" points="2854.049,-41.1073 2859.8757,-32.2586 2849.8026,-35.5424 2854.049,-41.1073"/>
<text text-anchor="middle" x="2884.2422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1641.3825,-180.7155C1708.048,-165.2491 1827.9951,-137.4213 1902.4309,-120.1522"/>
<polygon fill="#000000" stroke="#000000" points="1903.2225,-123.5616 1912.1728,-117.8921 1901.6405,-116.7427 1903.2225,-123.5616"/>
<text text-anchor="middle" x="1853.2422" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_surgery -->
<g id="node13" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="385.7422" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="385.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M393.5753,-260.9847C399.6918,-249.3321 409.4013,-235.0639 422.7422,-228 471.2387,-202.3214 1270.9993,-194.3457 1519.6034,-192.4809"/>
<polygon fill="#000000" stroke="#000000" points="1519.9971,-195.9782 1529.9709,-192.4043 1519.9453,-188.9784 1519.9971,-195.9782"/>
<text text-anchor="middle" x="501.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- treatment_radiation -->
<g id="node14" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="606.7422" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="606.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M591.592,-261.0125C584.4044,-250.2545 579.0823,-236.9757 587.7422,-228 603.9158,-211.2367 1291.9216,-197.3982 1520.0806,-193.2627"/>
<polygon fill="#000000" stroke="#000000" points="1520.3354,-196.7588 1530.2706,-193.0789 1520.2091,-189.7599 1520.3354,-196.7588"/>
<text text-anchor="middle" x="670.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- laboratory_test -->
<g id="node15" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="470.7422" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="470.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M431.593,-437.0904C360.3994,-405.8839 222.0066,-333.3594 277.7422,-261 312.805,-215.4793 345.8794,-236.2556 402.7422,-228 512.8309,-212.0168 1279.3228,-197.4567 1520.3614,-193.2294"/>
<polygon fill="#000000" stroke="#000000" points="1520.4819,-196.728 1530.4192,-193.0537 1520.3596,-189.729 1520.4819,-196.728"/>
<text text-anchor="middle" x="341.2422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M546.6919,-446.1719C665.4622,-435.6542 902.4209,-415.3139 1103.7422,-402 1342.8182,-386.1893 1628.4794,-373.2982 1745.6053,-368.2702"/>
<polygon fill="#000000" stroke="#000000" points="1745.9025,-371.7607 1755.7438,-367.8365 1745.6034,-364.7671 1745.9025,-371.7607"/>
<text text-anchor="middle" x="1169.2422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_response -->
<g id="node16" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="872.7422" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="872.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M876.694,-260.7571C880.1936,-249.3191 886.5497,-235.3873 897.7422,-228 923.4016,-211.0643 1347.7251,-198.2989 1520.4562,-193.7804"/>
<polygon fill="#000000" stroke="#000000" points="1520.5684,-197.2788 1530.4741,-193.5203 1520.3866,-190.2812 1520.5684,-197.2788"/>
<text text-anchor="middle" x="980.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- pathology_file -->
<g id="node17" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1799.7422" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1799.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1799.7422,-434.9735C1799.7422,-423.1918 1799.7422,-407.5607 1799.7422,-394.1581"/>
<polygon fill="#000000" stroke="#000000" points="1803.2423,-394.0033 1799.7422,-384.0034 1796.2423,-394.0034 1803.2423,-394.0033"/>
<text text-anchor="middle" x="1860.7422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1755.3539,-364.1358C1624.4558,-358.1876 1246.8844,-337.6233 1210.7422,-297 1200.107,-285.0462 1200.4832,-273.2781 1210.7422,-261 1249.4379,-214.6886 1420.9594,-199.4047 1520.5158,-194.4013"/>
<polygon fill="#000000" stroke="#000000" points="1520.6896,-197.8971 1530.5102,-193.9214 1520.3537,-190.9052 1520.6896,-197.8971"/>
<text text-anchor="middle" x="1247.2422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2239.7422" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2239.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1832.1828,-353.5904C1864.8833,-341.6373 1917.0572,-324.0724 1963.7422,-315 2059.1755,-296.4543 2086.3036,-315.5182 2181.7422,-297 2185.8176,-296.2092 2190.0114,-295.2359 2194.1909,-294.1549"/>
<polygon fill="#000000" stroke="#000000" points="2195.1549,-297.5197 2203.8543,-291.4722 2193.2824,-290.7748 2195.1549,-297.5197"/>
<text text-anchor="middle" x="2000.2422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node30" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2564.7422" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2564.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1841.5799,-360.0777C1917.2782,-349.5559 2082.0893,-327.5342 2221.7422,-315 2357.4319,-302.8215 2395.9389,-331.4658 2527.7422,-297 2529.9321,-296.4273 2532.1468,-295.7207 2534.3466,-294.9219"/>
<polygon fill="#000000" stroke="#000000" points="2535.9092,-298.0618 2543.7721,-290.9607 2533.1971,-291.6085 2535.9092,-298.0618"/>
<text text-anchor="middle" x="2258.2422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_status -->
<g id="node19" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2958.7422" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2958.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2951.9549,-86.7409C2947.5258,-76.4045 2941.0258,-63.6545 2932.7422,-54 2927.6664,-48.084 2921.4286,-42.619 2915.1017,-37.8275"/>
<polygon fill="#000000" stroke="#000000" points="2916.6993,-34.6692 2906.5197,-31.732 2912.6459,-40.3762 2916.6993,-34.6692"/>
<text text-anchor="middle" x="2998.2422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- diagnosis -->
<g id="node20" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1019.7422" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1019.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M976.5668,-441.9035C886.1555,-416.6026 690.7014,-349.8905 758.7422,-261 792.884,-216.3962 825.2653,-236.8017 880.7422,-228 1002.1785,-208.7334 1363.992,-197.6883 1519.916,-193.7083"/>
<polygon fill="#000000" stroke="#000000" points="1520.4241,-197.1967 1530.3325,-193.4451 1520.2472,-190.1989 1520.4241,-197.1967"/>
<text text-anchor="middle" x="800.2422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1067.641,-444.337C1131.0593,-433.1361 1246.4641,-413.6846 1345.7422,-402 1489.7195,-385.0545 1660.3472,-373.9154 1745.5937,-368.958"/>
<polygon fill="#000000" stroke="#000000" points="1746.0244,-372.4391 1755.8066,-368.37 1745.622,-365.4507 1746.0244,-372.4391"/>
<text text-anchor="middle" x="1390.2422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1365.7422" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1365.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1381.9426,-261.3111C1393.1774,-250.1071 1409.0689,-236.2277 1425.7422,-228 1455.8509,-213.1424 1491.9867,-204.3854 1522.9319,-199.2389"/>
<polygon fill="#000000" stroke="#000000" points="1523.8734,-202.6341 1533.2111,-197.6284 1522.7898,-195.7185 1523.8734,-202.6341"/>
<text text-anchor="middle" x="1484.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- exposure -->
<g id="node22" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1510.7422" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1510.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1526.9428,-261.8116C1538.9935,-249.026 1555.6227,-231.3829 1569.1484,-217.0324"/>
<polygon fill="#000000" stroke="#000000" points="1571.9827,-219.1282 1576.2946,-209.4505 1566.8888,-214.327 1571.9827,-219.1282"/>
<text text-anchor="middle" x="1600.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_funding -->
<g id="node23" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3124.7422" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3124.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3106.6328,-87.2971C3094.1526,-76.0872 3076.6446,-62.2066 3058.7422,-54 3017.3266,-35.0147 2965.8687,-25.9743 2929.3147,-21.7111"/>
<polygon fill="#000000" stroke="#000000" points="2929.2693,-18.1855 2918.9493,-20.5832 2928.5121,-25.1445 2929.2693,-18.1855"/>
<text text-anchor="middle" x="3143.7422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2216.3302,-263.0786C2194.5583,-248.3047 2165.247,-228.5104 2163.7422,-228 2117.697,-212.3826 1808.0572,-199.5954 1664.9778,-194.4451"/>
<polygon fill="#000000" stroke="#000000" points="1665.0885,-190.9469 1654.9698,-194.0875 1664.8385,-197.9424 1665.0885,-190.9469"/>
<text text-anchor="middle" x="2226.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2283.6522,-270.4304C2299.9845,-267.3317 2318.6887,-263.8876 2335.7422,-261 2362.1121,-256.5349 2437.3019,-263.2767 2454.7422,-243 2459.0895,-237.9457 2456.2862,-234.4854 2454.7422,-228 2442.6353,-177.1466 2413.8492,-173.8534 2401.7422,-123 2398.0366,-107.435 2394.096,-101.0548 2401.7422,-87 2414.6441,-63.2844 2427.1915,-62.7208 2452.7422,-54 2522.6869,-30.1269 2740.2528,-21.6682 2836.333,-19.0446"/>
<polygon fill="#000000" stroke="#000000" points="2836.4347,-22.5432 2846.3388,-18.7805 2836.25,-15.5456 2836.4347,-22.5432"/>
<text text-anchor="middle" x="2455.2422" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1983.7422" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1983.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1967.5243,-435.1584C1956.6641,-424.1804 1941.512,-410.6107 1925.7422,-402 1902.5048,-389.3119 1874.3563,-380.7201 1850.5637,-375.1223"/>
<polygon fill="#000000" stroke="#000000" points="1851.1839,-371.6746 1840.6606,-372.9034 1849.6534,-378.5052 1851.1839,-371.6746"/>
<text text-anchor="middle" x="2018.2422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_personnel -->
<g id="node26" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3344.7422" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3344.7422" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge25" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3317.5863,-87.8137C3297.8762,-76.2239 3270.1452,-61.6924 3243.7422,-54 3185.9107,-37.1511 3012.9717,-25.383 2929.216,-20.5091"/>
<polygon fill="#000000" stroke="#000000" points="2929.4002,-17.0141 2919.2161,-19.9354 2928.9992,-24.0026 2929.4002,-17.0141"/>
<text text-anchor="middle" x="3350.2422" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- methylation_array_file -->
<g id="node27" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1405.7422" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1405.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1419.8191,-434.9717C1429.8923,-423.4709 1444.502,-409.3841 1460.7422,-402 1510.1493,-379.5356 1662.7617,-370.7817 1745.3417,-367.6235"/>
<polygon fill="#000000" stroke="#000000" points="1745.6751,-371.1137 1755.5396,-367.2483 1745.4176,-364.1184 1745.6751,-371.1137"/>
<text text-anchor="middle" x="1552.2422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node28" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1711.7422" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1711.7422" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1690.2135,-261.0188C1677.9776,-251.0101 1662.2471,-238.4915 1647.7422,-228 1641.2405,-223.2973 1634.1613,-218.4621 1627.3122,-213.922"/>
<polygon fill="#000000" stroke="#000000" points="1629.1039,-210.9116 1618.8206,-208.3611 1625.2689,-216.7677 1629.1039,-210.9116"/>
<text text-anchor="middle" x="1769.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2543.6322,-267.1034C2531.566,-260.2138 2516.2021,-251.2891 2502.7422,-243 2492.3507,-236.6005 2491.3674,-231.714 2479.7422,-228 2403.2178,-203.5518 1862.9683,-195.0474 1665.1188,-192.7332"/>
<polygon fill="#000000" stroke="#000000" points="1665.1532,-189.2334 1655.1136,-192.618 1665.0726,-196.233 1665.1532,-189.2334"/>
<text text-anchor="middle" x="2526.7422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge33" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2560.6396,-261.0021C2553.3167,-223.9184 2542.371,-138.1926 2583.7422,-87 2615.0838,-48.218 2760.4647,-29.259 2836.3483,-21.8693"/>
<polygon fill="#000000" stroke="#000000" points="2836.9492,-25.3281 2846.5754,-20.9025 2836.2904,-18.3592 2836.9492,-25.3281"/>
<text text-anchor="middle" x="2581.7422" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- synonym -->
<g id="node31" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3329.7422" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3329.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3322.1622,-434.9641C3308.9188,-405.5873 3278.8135,-347.4354 3235.7422,-315 3174.4416,-268.8369 3146.7088,-277.3953 3071.7422,-261 2944.154,-233.0962 2910.0131,-237.3208 2779.7422,-228 2561.3685,-212.3755 1888.3763,-197.8985 1665.3678,-193.4186"/>
<polygon fill="#000000" stroke="#000000" points="1665.1602,-189.9138 1655.0921,-193.2128 1665.02,-196.9124 1665.1602,-189.9138"/>
<text text-anchor="middle" x="3295.2422" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3287.3173,-442.4693C3274.367,-439.6151 3260.0364,-436.8158 3246.7422,-435 2969.8832,-397.1849 2083.4333,-373.0303 1854.2463,-367.3126"/>
<polygon fill="#000000" stroke="#000000" points="1854.2331,-363.8113 1844.1493,-367.062 1854.0594,-370.8091 1854.2331,-363.8113"/>
<text text-anchor="middle" x="3081.2422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3376.1552,-444.6954C3441.7661,-431.6132 3553.7422,-403.7558 3553.7422,-366 3553.7422,-366 3553.7422,-366 3553.7422,-105 3553.7422,-51.9173 3497.1415,-67.2623 3445.7422,-54 3348.5058,-28.9105 3045.8068,-20.9166 2929.1945,-18.7287"/>
<polygon fill="#000000" stroke="#000000" points="2929.2173,-15.2286 2919.1553,-18.5462 2929.09,-22.2275 2929.2173,-15.2286"/>
<text text-anchor="middle" x="3596.2422" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sequencing_file -->
<g id="node32" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1622.7422" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1622.7422" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1632.7511,-434.9332C1639.7718,-423.8653 1650.1406,-410.2801 1662.7422,-402 1687.7095,-385.5948 1719.8311,-376.6526 1746.6949,-371.7848"/>
<polygon fill="#000000" stroke="#000000" points="1747.4211,-375.2121 1756.7074,-370.1116 1746.2672,-368.3078 1747.4211,-375.2121"/>
<text text-anchor="middle" x="1729.2422" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
</g>
</svg>
</div>
