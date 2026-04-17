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
<svg width="3676pt" height="392pt"
 viewBox="0.00 0.00 3675.89 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3671.887,-388 3671.887,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1982.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1982.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8382,-87.0071C79.8181,-75.9687 79.6986,-62.3886 88.0923,-54 104.949,-37.1534 1645.2398,-21.2891 1935.2859,-18.4497"/>
<polygon fill="#000000" stroke="#000000" points="1935.4956,-21.9479 1945.4609,-18.3504 1935.4272,-14.9483 1935.4956,-21.9479"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- laboratory_test -->
<g id="node2" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2742.0923" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2742.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1891.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1891.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2760.2189,-348.3003C2780.1781,-326.6032 2807.0818,-289.2414 2788.0923,-261 2766.4016,-228.7413 2745.0663,-236.3118 2707.0923,-228 2635.6736,-212.3678 2149.7816,-198.5593 1963.5385,-193.7807"/>
<polygon fill="#000000" stroke="#000000" points="1963.3877,-190.2758 1953.3016,-193.5194 1963.209,-197.2735 1963.3877,-190.2758"/>
<text text-anchor="middle" x="2859.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample -->
<g id="node32" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="487.0923" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="487.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2663.5265,-360.7667C2500.3401,-350.1258 2112.7486,-326.0417 1787.0923,-315 1648.6019,-310.3043 676.6432,-320.5688 540.0923,-297 536.3786,-296.359 532.5738,-295.4992 528.7907,-294.5014"/>
<polygon fill="#000000" stroke="#000000" points="529.486,-291.0578 518.9048,-291.5941 527.511,-297.7734 529.486,-291.0578"/>
<text text-anchor="middle" x="2194.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="258.0923" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="258.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M252.4315,-347.8706C247.4862,-330.4097 241.0923,-303.162 241.0923,-279 241.0923,-279 241.0923,-279 241.0923,-105 241.0923,-61.3017 1659.0163,-25.6197 1935.63,-19.0745"/>
<polygon fill="#000000" stroke="#000000" points="1935.8143,-22.5712 1945.729,-18.8365 1935.6493,-15.5732 1935.8143,-22.5712"/>
<text text-anchor="middle" x="283.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M259.3785,-347.8063C262.6375,-317.0918 274.0854,-255.6095 314.0923,-228 329.7709,-217.1799 1510.4943,-197.9581 1818.3524,-193.1261"/>
<polygon fill="#000000" stroke="#000000" points="1818.5577,-196.6235 1828.5016,-192.9671 1818.448,-189.6243 1818.5577,-196.6235"/>
<text text-anchor="middle" x="326.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M284.4129,-350.353C303.7457,-339.3484 330.9182,-324.8806 356.0923,-315 382.5291,-304.6238 413.078,-296.0443 438.022,-289.8667"/>
<polygon fill="#000000" stroke="#000000" points="439.0933,-293.2085 447.9876,-287.4517 437.4446,-286.4054 439.0933,-293.2085"/>
<text text-anchor="middle" x="398.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1512.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1512.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge16" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1506.919,-86.6764C1505.0503,-75.7919 1505.0653,-62.4981 1513.0923,-54 1527.4514,-38.7981 1819.1503,-24.8734 1935.1319,-19.9163"/>
<polygon fill="#000000" stroke="#000000" points="1935.6238,-23.3987 1945.4667,-19.4785 1935.3275,-16.4049 1935.6238,-23.3987"/>
<text text-anchor="middle" x="1564.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- clinical_measure_file -->
<g id="node6" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3227.0923" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3227.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3289.4551,-351.1533C3324.8275,-338.6131 3362.0923,-316.5024 3362.0923,-279 3362.0923,-279 3362.0923,-279 3362.0923,-105 3362.0923,-36.6614 2269.9595,-21.0599 2028.8318,-18.4482"/>
<polygon fill="#000000" stroke="#000000" points="2028.6851,-14.9465 2018.6485,-18.3402 2028.6108,-21.9461 2028.6851,-14.9465"/>
<text text-anchor="middle" x="3448.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3206.6481,-348.1194C3177.8787,-324.0389 3122.8207,-281.8113 3068.0923,-261 2971.9777,-224.4511 2941.5002,-237.2972 2839.0923,-228 2669.3711,-212.5917 2154.5639,-198.57 1963.4906,-193.7619"/>
<polygon fill="#000000" stroke="#000000" points="1963.3616,-190.2576 1953.277,-193.5059 1963.1861,-197.2554 1963.3616,-190.2576"/>
<text text-anchor="middle" x="3223.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3141.1049,-354.9012C3039.8799,-342.4164 2866.6003,-322.8582 2717.0923,-315 2596.3104,-308.6517 659.3414,-317.2041 540.0923,-297 536.3766,-296.3705 532.5705,-295.5186 528.7864,-294.5262"/>
<polygon fill="#000000" stroke="#000000" points="529.4799,-291.0822 518.8991,-291.6272 527.5104,-297.7994 529.4799,-291.0822"/>
<text text-anchor="middle" x="2999.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment_surgery -->
<g id="node7" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="2516.0923" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="2516.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2456.5164,-264.5325C2407.5314,-253.1121 2336.1697,-237.5602 2273.0923,-228 2165.309,-211.664 2039.2213,-201.5023 1962.279,-196.2967"/>
<polygon fill="#000000" stroke="#000000" points="1962.4295,-192.7991 1952.2186,-195.6254 1961.9634,-199.7836 1962.4295,-192.7991"/>
<text text-anchor="middle" x="2432.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- sequencing_file -->
<g id="node8" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="411.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="411.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M426.8395,-347.9735C437.9611,-335.2422 453.0092,-318.0161 465.2845,-303.9642"/>
<polygon fill="#000000" stroke="#000000" points="468.1979,-305.9492 472.1409,-296.1154 462.926,-301.3439 468.1979,-305.9492"/>
<text text-anchor="middle" x="520.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- radiology_file -->
<g id="node9" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2706.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2706.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2661.8799,-264.4475C2623.5191,-252.4865 2566.2617,-236.2198 2515.0923,-228 2410.8294,-211.2513 2104.4231,-199.1613 1963.5061,-194.3272"/>
<polygon fill="#000000" stroke="#000000" points="1963.3567,-190.8201 1953.2435,-193.9779 1963.1186,-197.8161 1963.3567,-190.8201"/>
<text text-anchor="middle" x="2644.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1576.0923" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1576.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1629.8924,-362.361C1757.6718,-353.2499 2071.4098,-327.9525 2107.0923,-297 2130.7989,-276.4358 2142.5034,-251.8385 2122.0923,-228 2111.5994,-215.7452 2025.0367,-204.8263 1960.9412,-198.311"/>
<polygon fill="#000000" stroke="#000000" points="1961.1608,-194.8156 1950.8622,-197.3037 1960.4645,-201.7809 1961.1608,-194.8156"/>
<text text-anchor="middle" x="2176.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1525.3826,-359.0142C1441.0426,-347.6969 1266.5271,-325.5588 1118.0923,-315 989.9095,-305.8818 666.5396,-319.9137 540.0923,-297 536.3841,-296.328 532.5831,-295.4466 528.8025,-294.4345"/>
<polygon fill="#000000" stroke="#000000" points="529.503,-290.9917 518.9206,-291.5047 527.5132,-297.7029 529.503,-290.9917"/>
<text text-anchor="middle" x="1327.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node11" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="628.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="628.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M618.6219,-347.7497C612.1642,-336.8928 602.6894,-323.6023 591.0923,-315 590.4166,-314.4988 558.985,-303.6456 530.855,-293.9865"/>
<polygon fill="#000000" stroke="#000000" points="531.6932,-290.5739 521.0985,-290.6387 529.4212,-297.1949 531.6932,-290.5739"/>
<text text-anchor="middle" x="697.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- consent_group -->
<g id="node20" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1891.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1891.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1891.0923,-173.9735C1891.0923,-162.1918 1891.0923,-146.5607 1891.0923,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1894.5924,-133.0033 1891.0923,-123.0034 1887.5924,-133.0034 1894.5924,-133.0033"/>
<text text-anchor="middle" x="1941.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pdx -->
<g id="node13" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="391.0923" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="391.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M418.512,-187.8828C447.0621,-183.7467 493.1122,-177.4987 533.0923,-174 766.0324,-153.6154 1364.119,-202.2994 1584.0923,-123 1609.1786,-113.9565 1608.0672,-98.5717 1632.0923,-87 1733.0654,-38.3662 1866.1736,-24.0111 1935.532,-19.7741"/>
<polygon fill="#000000" stroke="#000000" points="1935.9105,-23.2583 1945.6966,-19.1983 1935.5146,-16.2695 1935.9105,-23.2583"/>
<text text-anchor="middle" x="1656.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M365.4109,-199.2737C339.5088,-207.8943 305.4244,-223.5701 321.0923,-243 328.3633,-252.0169 389.2374,-263.526 435.1792,-271.0718"/>
<polygon fill="#000000" stroke="#000000" points="434.8863,-274.5699 445.3171,-272.7131 436.005,-267.6599 434.8863,-274.5699"/>
<text text-anchor="middle" x="345.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment_response -->
<g id="node14" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="654.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="654.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M711.1515,-263.8175C727.7524,-258.3451 745.5819,-251.4014 761.0923,-243 770.5525,-237.8758 769.9869,-231.6926 780.0923,-228 828.7901,-210.2051 1578.8359,-196.9147 1818.2429,-193.1084"/>
<polygon fill="#000000" stroke="#000000" points="1818.6342,-196.6027 1828.5776,-192.9449 1818.5234,-189.6036 1818.6342,-196.6027"/>
<text text-anchor="middle" x="863.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="591.0923" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="591.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge44" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M640.6955,-191.2236C842.8413,-187.9414 1596.0042,-174.5161 1643.0923,-156 1686.4766,-138.9403 1680.9593,-108.9388 1722.0923,-87 1791.7733,-49.8348 1882.8442,-31.662 1936.6427,-23.6069"/>
<polygon fill="#000000" stroke="#000000" points="1937.1677,-27.0675 1946.5643,-22.1732 1936.1665,-20.1394 1937.1677,-27.0675"/>
<text text-anchor="middle" x="1762.5923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M548.3044,-201.0373C522.0202,-207.554 491.9272,-217.0975 484.0923,-228 479.3611,-234.5836 478.391,-242.9677 479.0993,-251.0272"/>
<polygon fill="#000000" stroke="#000000" points="475.648,-251.6099 480.7373,-260.9024 482.5537,-250.4644 475.648,-251.6099"/>
<text text-anchor="middle" x="524.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_radiation -->
<g id="node16" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="881.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="881.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M914.122,-261.8603C925.5311,-255.9152 938.3863,-249.189 950.0923,-243 962.5729,-236.4014 964.4697,-231.7059 978.0923,-228 1058.1137,-206.2312 1616.6006,-196.0053 1818.4879,-192.9898"/>
<polygon fill="#000000" stroke="#000000" points="1818.7435,-196.4865 1828.6907,-192.839 1818.64,-189.4872 1818.7435,-196.4865"/>
<text text-anchor="middle" x="1061.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- exposure -->
<g id="node17" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1057.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1057.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1089.267,-264.4765C1117.7587,-252.361 1160.8055,-235.8541 1200.0923,-228 1316.6109,-204.7059 1665.6933,-195.9155 1818.3202,-193.1234"/>
<polygon fill="#000000" stroke="#000000" points="1818.589,-196.6192 1828.5246,-192.9403 1818.4634,-189.6204 1818.589,-196.6192"/>
<text text-anchor="middle" x="1243.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node18" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2058.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2058.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2050.4474,-86.8239C2045.5658,-76.5152 2038.5658,-63.7652 2030.0923,-54 2025.211,-48.3746 2019.3121,-43.0833 2013.3447,-38.3783"/>
<polygon fill="#000000" stroke="#000000" points="2015.364,-35.5181 2005.2541,-32.3494 2011.1813,-41.1311 2015.364,-35.5181"/>
<text text-anchor="middle" x="2097.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node19" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2224.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2224.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge27" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2205.9829,-87.2971C2193.5027,-76.0872 2175.9946,-62.2066 2158.0923,-54 2116.6767,-35.0147 2065.2187,-25.9743 2028.6647,-21.7111"/>
<polygon fill="#000000" stroke="#000000" points="2028.6194,-18.1855 2018.2994,-20.5832 2027.8621,-25.1445 2028.6194,-18.1855"/>
<text text-anchor="middle" x="2244.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge35" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1889.8166,-86.7942C1890.0103,-76.2221 1891.9619,-63.2145 1899.0923,-54 1908.8698,-41.3645 1923.9813,-33.0866 1938.6442,-27.6982"/>
<polygon fill="#000000" stroke="#000000" points="1939.7563,-31.0169 1948.1545,-24.5577 1937.5614,-24.3699 1939.7563,-31.0169"/>
<text text-anchor="middle" x="1962.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- genetic_analysis -->
<g id="node21" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2182.0923" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2182.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2200.0016,-348.0695C2219.326,-326.4671 2245.0685,-289.5237 2227.0923,-261 2199.386,-217.0372 2053.2965,-200.9477 1963.1124,-195.1594"/>
<polygon fill="#000000" stroke="#000000" points="1963.1402,-191.6546 1952.9445,-194.5351 1962.7112,-198.6415 1963.1402,-191.6546"/>
<text text-anchor="middle" x="2304.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2099.7709,-359.6545C1953.9953,-348.6719 1640.8522,-326.2218 1376.0923,-315 1283.2652,-311.0655 631.5923,-313.1274 540.0923,-297 536.3809,-296.3458 532.5777,-295.4768 528.7956,-294.473"/>
<polygon fill="#000000" stroke="#000000" points="529.4931,-291.0297 518.9114,-291.5561 527.5118,-297.7434 529.4931,-291.0297"/>
<text text-anchor="middle" x="1713.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment_other -->
<g id="node22" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="1215.0923" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1215.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1246.4021,-262.0829C1269.8315,-250.3027 1303.0499,-235.423 1334.0923,-228 1424.0181,-206.4965 1689.388,-197.0477 1818.667,-193.6305"/>
<polygon fill="#000000" stroke="#000000" points="1818.9586,-197.1242 1828.8645,-193.366 1818.777,-190.1266 1818.9586,-197.1242"/>
<text text-anchor="middle" x="1403.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="851.0923" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="851.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M836.3646,-348.0332C825.6835,-336.4022 810.1631,-322.14 793.0923,-315 741.0931,-293.2509 595.3419,-308.1544 540.0923,-297 536.4488,-296.2644 532.7109,-295.3468 528.9882,-294.318"/>
<polygon fill="#000000" stroke="#000000" points="529.8289,-290.916 519.2444,-291.3835 527.8102,-297.6186 529.8289,-290.916"/>
<text text-anchor="middle" x="888.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- family_relationship -->
<g id="node24" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1420.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1420.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1444.6837,-261.4805C1462.2995,-249.8936 1487.0627,-235.5028 1511.0923,-228 1566.7277,-210.6289 1725.3225,-200.1329 1819.115,-195.2655"/>
<polygon fill="#000000" stroke="#000000" points="1819.5724,-198.7468 1829.3811,-194.7418 1819.2157,-191.7559 1819.5724,-198.7468"/>
<text text-anchor="middle" x="1590.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pathology_file -->
<g id="node25" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1035.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1035.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1016.9401,-348.3495C1003.5263,-336.5409 984.1749,-321.9387 964.0923,-315 874.9556,-284.2025 632.7916,-314.3395 540.0923,-297 536.4387,-296.3166 532.6937,-295.4356 528.9661,-294.4312"/>
<polygon fill="#000000" stroke="#000000" points="529.7974,-291.0271 519.2148,-291.5357 527.8048,-297.7375 529.7974,-291.0271"/>
<text text-anchor="middle" x="1053.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2982.0923" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2982.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2992.3835,-347.8948C2999.3066,-337.0925 3009.3072,-323.8084 3021.0923,-315 3039.0092,-301.6085 3050.1094,-310.3028 3068.0923,-297 3095.9673,-276.3795 3116.0923,-270.1731 3116.0923,-235.5 3116.0923,-235.5 3116.0923,-235.5 3116.0923,-105 3116.0923,-49.5386 2242.3878,-24.4106 2028.7844,-19.096"/>
<polygon fill="#000000" stroke="#000000" points="2028.6213,-15.591 2018.5381,-18.8437 2028.4489,-22.5889 2028.6213,-15.591"/>
<text text-anchor="middle" x="3169.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2978.2208,-347.9672C2972.108,-324.112 2957.8361,-282.5729 2929.0923,-261 2865.0906,-212.9653 2831.6036,-237.0277 2752.0923,-228 2600.1621,-210.7498 2141.9268,-198.0953 1963.3964,-193.6953"/>
<polygon fill="#000000" stroke="#000000" points="1963.4025,-190.1945 1953.3197,-193.4484 1963.2309,-197.1924 1963.4025,-190.1945"/>
<text text-anchor="middle" x="3011.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2923.0859,-358.014C2895.7493,-354.5348 2862.8083,-350.654 2833.0923,-348 2580.7828,-325.4653 2517.2581,-323.6581 2264.0923,-315 2168.3652,-311.7262 634.512,-313.1029 540.0923,-297 536.3773,-296.3664 532.5716,-295.5117 528.7879,-294.5175"/>
<polygon fill="#000000" stroke="#000000" points="529.4821,-291.0736 518.9011,-291.6155 527.5106,-297.7903 529.4821,-291.0736"/>
<text text-anchor="middle" x="2660.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node27" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1667.0923" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1667.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1668.1556,-260.8723C1669.791,-249.7801 1673.7363,-236.1908 1683.0923,-228 1703.159,-210.4325 1767.6422,-201.2041 1819.5502,-196.511"/>
<polygon fill="#000000" stroke="#000000" points="1820.0849,-199.978 1829.7472,-195.6318 1819.4835,-193.0039 1820.0849,-199.978"/>
<text text-anchor="middle" x="1785.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- medical_history -->
<g id="node28" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1899.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1899.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1894.9164,-260.7781C1893.7891,-255.1126 1892.711,-248.8249 1892.0923,-243 1891.3255,-235.7816 1890.9472,-227.9571 1890.7873,-220.6546"/>
<polygon fill="#000000" stroke="#000000" points="1894.2854,-220.4266 1890.6894,-210.4607 1887.2857,-220.4939 1894.2854,-220.4266"/>
<text text-anchor="middle" x="1960.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node29" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2050.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2050.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2046.5402,-261.032C2043.4577,-250.0035 2037.8893,-236.4251 2028.0923,-228 2016.7428,-218.2398 1985.2066,-209.6214 1955.2494,-203.2659"/>
<polygon fill="#000000" stroke="#000000" points="1955.6817,-199.7817 1945.182,-201.199 1954.2738,-206.6387 1955.6817,-199.7817"/>
<text text-anchor="middle" x="2078.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_status -->
<g id="node30" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="3460.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3460.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge3" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3438.7835,-87.7293C3422.6389,-75.7733 3399.3363,-60.8285 3376.0923,-54 3310.1443,-34.626 2263.8641,-21.2917 2028.7508,-18.5309"/>
<polygon fill="#000000" stroke="#000000" points="2028.5318,-15.0282 2018.4916,-18.4112 2028.45,-22.0278 2028.5318,-15.0282"/>
<text text-anchor="middle" x="3463.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- study_arm -->
<g id="node31" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3608.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3608.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge38" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3587.1285,-87.9645C3570.9747,-75.9585 3547.5085,-60.8476 3524.0923,-54 3450.6523,-32.5239 2278.8766,-20.6973 2028.8085,-18.4111"/>
<polygon fill="#000000" stroke="#000000" points="2028.6407,-14.9095 2018.6093,-18.3185 2028.5771,-21.9092 2028.6407,-14.9095"/>
<text text-anchor="middle" x="3603.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M519.9074,-266.8624C526.5283,-264.6957 533.485,-262.6171 540.0923,-261 591.1958,-248.4928 607.3171,-260.0422 657.0923,-243 670.0796,-238.5533 670.8565,-231.6412 684.0923,-228 793.006,-198.038 1574.0672,-193.0094 1818.2995,-192.1682"/>
<polygon fill="#000000" stroke="#000000" points="1818.4994,-195.6677 1828.4877,-192.1345 1818.4762,-188.6677 1818.4994,-195.6677"/>
<text text-anchor="middle" x="720.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge41" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M449.617,-269.4449C426.1628,-262.6306 399.1047,-252.9465 392.0923,-243 387.4798,-236.4576 385.9998,-228.1771 386.0154,-220.2015"/>
<polygon fill="#000000" stroke="#000000" points="389.5179,-220.2937 386.7595,-210.0642 382.5367,-219.7811 389.5179,-220.2937"/>
<text text-anchor="middle" x="428.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge42" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M520.6443,-267.1336C539.9567,-259.7647 561.8049,-250.3344 569.0923,-243 575.5405,-236.5102 580.2309,-227.8259 583.5807,-219.4651"/>
<polygon fill="#000000" stroke="#000000" points="586.9111,-220.5445 586.9223,-209.9497 580.3066,-218.2251 586.9111,-220.5445"/>
<text text-anchor="middle" x="616.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
