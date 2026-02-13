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
<svg width="3056pt" height="392pt"
 viewBox="0.00 0.00 3056.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3051.9954,-388 3051.9954,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2400.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2400.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1679.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1679.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2383.0962,-262.1818C2369.2207,-250.2868 2348.8914,-235.2194 2327.9954,-228 2274.8164,-209.6271 1910.1432,-198.009 1752.4249,-193.7898"/>
<polygon fill="#000000" stroke="#000000" points="1752.4303,-190.2888 1742.341,-193.5226 1752.2448,-197.2864 1752.4303,-190.2888"/>
<text text-anchor="middle" x="2395.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node2" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="590.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="590.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M630.5946,-263.7778C666.5888,-250.216 717.1561,-231.923 737.9954,-228 822.367,-212.1171 1401.3005,-198.0851 1607.3676,-193.5405"/>
<polygon fill="#000000" stroke="#000000" points="1607.5603,-197.0372 1617.481,-193.3185 1607.4066,-190.0389 1607.5603,-197.0372"/>
<text text-anchor="middle" x="796.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- consent_group -->
<g id="node5" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1679.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1679.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1679.9954,-173.9735C1679.9954,-162.1918 1679.9954,-146.5607 1679.9954,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1683.4955,-133.0033 1679.9954,-123.0034 1676.4955,-133.0034 1683.4955,-133.0033"/>
<text text-anchor="middle" x="1730.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_other -->
<g id="node4" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="769.9954" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="769.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M806.2134,-262.5947C834.4114,-250.6645 874.8677,-235.3649 911.9954,-228 1043.6855,-201.8771 1442.6315,-194.5797 1607.5024,-192.652"/>
<polygon fill="#000000" stroke="#000000" points="1607.5862,-196.1513 1617.5457,-192.5378 1607.5066,-189.1518 1607.5862,-196.1513"/>
<text text-anchor="middle" x="981.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1866.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1866.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge38" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1675.1739,-86.9901C1673.4375,-76.2236 1673.4681,-62.9438 1680.9954,-54 1698.5436,-33.1494 1771.3107,-24.208 1820.4555,-20.4946"/>
<polygon fill="#000000" stroke="#000000" points="1820.8279,-23.9771 1830.5556,-19.7791 1820.3332,-16.9946 1820.8279,-23.9771"/>
<text text-anchor="middle" x="1744.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M59.8117,-348.0207C71.3572,-323.8255 95.4015,-281.4655 129.9954,-261 180.5762,-231.0767 205.1029,-261.1618 260.9954,-243 274.422,-238.6371 275.348,-231.6136 288.9954,-228 353.0483,-211.0399 1329.2545,-196.7053 1606.8641,-192.9558"/>
<polygon fill="#000000" stroke="#000000" points="1607.2712,-196.4507 1617.2231,-192.8164 1607.1769,-189.4514 1607.2712,-196.4507"/>
<text text-anchor="middle" x="172.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M39.8074,-348.2188C29.3636,-331.2283 15.9954,-304.5001 15.9954,-279 15.9954,-279 15.9954,-279 15.9954,-105 15.9954,-58.4003 1533.0699,-24.8706 1820.355,-18.9389"/>
<polygon fill="#000000" stroke="#000000" points="1820.5111,-22.4365 1830.437,-18.7316 1820.3672,-15.438 1820.5111,-22.4365"/>
<text text-anchor="middle" x="58.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node26" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="454.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="454.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M91.287,-354.078C98.4893,-351.986 105.9543,-349.8793 112.9954,-348 173.9249,-331.7372 188.937,-326.2091 250.9954,-315 315.3345,-303.3789 333.0761,-310.7439 396.9954,-297 401.6467,-295.9999 406.4604,-294.7931 411.2346,-293.4835"/>
<polygon fill="#000000" stroke="#000000" points="412.2803,-296.8246 420.9144,-290.6844 410.3357,-290.1001 412.2803,-296.8246"/>
<text text-anchor="middle" x="293.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="230.9954" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="230.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M224.7396,-347.6607C218.2493,-324.9709 211.4088,-286.2529 229.9954,-261 230.9094,-259.7582 334.4742,-228.2522 335.9954,-228 461.3313,-207.2207 1345.5611,-195.7473 1607.2232,-192.7804"/>
<polygon fill="#000000" stroke="#000000" points="1607.4138,-196.2786 1617.3737,-192.666 1607.3349,-189.279 1607.4138,-196.2786"/>
<text text-anchor="middle" x="315.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge10" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M220.2601,-347.8982C195.7596,-305.4594 139.5875,-201.0926 162.9954,-174 274.5203,-44.9193 1557.6783,-21.8853 1820.2379,-18.5143"/>
<polygon fill="#000000" stroke="#000000" points="1820.6066,-22.01 1830.5621,-18.3852 1820.5191,-15.0106 1820.6066,-22.01"/>
<text text-anchor="middle" x="248.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M289.6924,-350.7575C306.4428,-345.3162 324.3761,-338.4044 339.9954,-330 349.4698,-324.9021 349.6242,-320.2853 358.9954,-315 374.531,-306.2379 392.6127,-298.8196 408.8672,-293.0355"/>
<polygon fill="#000000" stroke="#000000" points="410.3956,-296.2111 418.7128,-289.6479 408.1181,-289.592 410.3956,-296.2111"/>
<text text-anchor="middle" x="444.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node8" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1912.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1912.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1903.4642,-86.9735C1897.0069,-74.7609 1888.3628,-58.4123 1881.111,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="1884.1254,-42.9101 1876.357,-35.7057 1877.9372,-46.182 1884.1254,-42.9101"/>
<text text-anchor="middle" x="1942.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="392.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="392.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge13" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M436.0049,-182.9214C533.5467,-162.6571 779.2242,-113.4462 986.9954,-87 1304.1107,-46.6358 1688.7236,-26.2386 1820.2769,-20.0691"/>
<polygon fill="#000000" stroke="#000000" points="1820.5747,-23.5592 1830.4016,-19.5991 1820.25,-16.5667 1820.5747,-23.5592"/>
<text text-anchor="middle" x="1027.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M363.0833,-206.5603C347.366,-216.2294 333.2079,-229.5733 342.9954,-243 343.5382,-243.7446 379.0911,-255.0994 409.9925,-264.86"/>
<polygon fill="#000000" stroke="#000000" points="409.222,-268.2869 419.8117,-267.9575 411.3279,-261.6112 409.222,-268.2869"/>
<text text-anchor="middle" x="383.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- genetic_analysis -->
<g id="node11" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2451.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2451.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2535.2012,-360.1491C2578.2808,-355.2023 2624.6255,-346.2058 2637.9954,-330 2656.903,-307.082 2640.829,-285.9796 2606.9954,-261 2553.4759,-221.4862 2526.9232,-236.8995 2460.9954,-228 2325.4518,-209.7032 1919.3075,-197.9037 1752.6121,-193.7108"/>
<polygon fill="#000000" stroke="#000000" points="1752.5455,-190.2082 1742.4612,-193.4575 1752.3708,-197.206 1752.5455,-190.2082"/>
<text text-anchor="middle" x="2711.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2372.9651,-358.1482C2336.9971,-354.7372 2293.8696,-350.8734 2254.9954,-348 1995.7331,-328.8363 1930.7969,-324.3486 1670.9954,-315 1541.9523,-310.3566 636.2906,-318.6703 508.9954,-297 505.0529,-296.3289 501.0075,-295.4201 496.9902,-294.3656"/>
<polygon fill="#000000" stroke="#000000" points="497.7164,-290.9318 487.1366,-291.4966 495.7594,-297.6527 497.7164,-290.9318"/>
<text text-anchor="middle" x="2061.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2713.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2713.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2738.7256,-349.8443C2768.5046,-328.456 2811.524,-290.0599 2785.9954,-261 2751.8266,-222.1048 1992.9695,-199.8309 1752.4389,-193.7295"/>
<polygon fill="#000000" stroke="#000000" points="1752.4838,-190.2296 1742.3988,-193.4766 1752.3074,-197.2274 1752.4838,-190.2296"/>
<text text-anchor="middle" x="2837.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2662.2826,-359.9466C2561.3011,-348.457 2330.7208,-323.8463 2135.9954,-315 1955.3928,-306.7953 687.2869,-326.9458 508.9954,-297 505.0515,-296.3376 501.005,-295.4348 496.987,-294.3841"/>
<polygon fill="#000000" stroke="#000000" points="497.712,-290.9501 487.1325,-291.5208 495.7588,-297.6721 497.712,-290.9501"/>
<text text-anchor="middle" x="2402.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1119.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1119.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1087.0857,-348.7089C1062.6736,-336.8262 1028.1847,-321.9812 995.9954,-315 784.3241,-269.0927 722.1136,-335.6373 508.9954,-297 505.0604,-296.2866 501.02,-295.3489 497.0059,-294.2757"/>
<polygon fill="#000000" stroke="#000000" points="497.7385,-290.843 487.1572,-291.3794 495.7635,-297.5586 497.7385,-290.843"/>
<text text-anchor="middle" x="1132.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_response -->
<g id="node14" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="979.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="979.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1011.7957,-261.8088C1035.1936,-250.0567 1068.1619,-235.3297 1098.9954,-228 1193.5029,-205.5337 1473.7065,-196.5083 1607.417,-193.4061"/>
<polygon fill="#000000" stroke="#000000" points="1607.6453,-196.902 1617.5632,-193.1756 1607.4863,-189.9038 1607.6453,-196.902"/>
<text text-anchor="middle" x="1181.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node15" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1231.9954" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1231.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1248.2861,-260.8987C1259.8247,-249.3662 1276.3396,-235.2715 1293.9954,-228 1348.937,-205.3725 1511.7123,-196.8326 1607.4369,-193.7115"/>
<polygon fill="#000000" stroke="#000000" points="1607.74,-197.2038 1617.6251,-193.3915 1607.5202,-190.2073 1607.74,-197.2038"/>
<text text-anchor="middle" x="1395.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2070.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2070.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2050.1483,-87.5351C2036.1551,-76.5685 2016.8876,-62.8709 1997.9954,-54 1970.4776,-41.0788 1937.4617,-32.0431 1911.4596,-26.2557"/>
<polygon fill="#000000" stroke="#000000" points="1912.0164,-22.7956 1901.5049,-24.1212 1910.5488,-29.64 1912.0164,-22.7956"/>
<text text-anchor="middle" x="2084.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- generic_file -->
<g id="node17" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2952.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2952.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2946.8269,-347.6889C2937.655,-323.5183 2917.9819,-281.6231 2885.9954,-261 2799.2022,-205.0407 2758.8494,-237.2495 2655.9954,-228 2480.6497,-212.2314 1947.5699,-198.357 1752.4989,-193.6794"/>
<polygon fill="#000000" stroke="#000000" points="1752.4373,-190.177 1742.3565,-193.4372 1752.2701,-197.175 1752.4373,-190.177"/>
<text text-anchor="middle" x="2972.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2979.9166,-349.4769C3011.3526,-328.1839 3055.9447,-290.4088 3029.9954,-261 2854.0053,-61.5475 2018.1705,-321.4006 1840.9954,-123 1821.5598,-101.236 1835.294,-67.2119 1849.0937,-43.8271"/>
<polygon fill="#000000" stroke="#000000" points="1852.1951,-45.4681 1854.5152,-35.1305 1846.2548,-41.7649 1852.1951,-45.4681"/>
<text text-anchor="middle" x="2994.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2893.6327,-358.1689C2799.8336,-346.2018 2611.5015,-323.8243 2450.9954,-315 2343.2646,-309.0772 615.4145,-314.776 508.9954,-297 505.0509,-296.3411 501.004,-295.4407 496.9858,-294.3917"/>
<polygon fill="#000000" stroke="#000000" points="497.7102,-290.9575 487.1309,-291.5306 495.7585,-297.68 497.7102,-290.9575"/>
<text text-anchor="middle" x="2682.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2252.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2252.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2225.054,-87.7906C2205.1358,-76.3459 2177.3276,-61.9977 2150.9954,-54 2107.6282,-40.8284 1981.9008,-28.152 1913.1807,-21.9508"/>
<polygon fill="#000000" stroke="#000000" points="1913.3388,-18.4511 1903.0671,-21.0478 1912.7162,-25.4234 1913.3388,-18.4511"/>
<text text-anchor="middle" x="2257.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm -->
<g id="node19" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2417.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2417.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2395.7166,-88.0917C2378.8915,-76.3159 2354.7182,-61.4378 2330.9954,-54 2254.1134,-29.8952 2015.3996,-21.4988 1913.674,-18.9654"/>
<polygon fill="#000000" stroke="#000000" points="1913.4834,-15.4599 1903.402,-18.718 1913.3148,-22.4579 1913.4834,-15.4599"/>
<text text-anchor="middle" x="2411.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment_surgery -->
<g id="node20" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="1477.9954" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="1477.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1488.0893,-261.0221C1495.2857,-249.8448 1505.9754,-236.1054 1518.9954,-228 1534.9976,-218.038 1577.1065,-208.8031 1614.2457,-202.1813"/>
<polygon fill="#000000" stroke="#000000" points="1615.312,-205.5483 1624.5632,-200.3844 1614.111,-198.6521 1615.312,-205.5483"/>
<text text-anchor="middle" x="1597.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_status -->
<g id="node21" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2565.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2565.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2539.9035,-88.2473C2519.9637,-76.3857 2491.3415,-61.3314 2463.9954,-54 2360.4526,-26.2404 2035.5574,-19.8409 1913.7425,-18.4039"/>
<polygon fill="#000000" stroke="#000000" points="1913.658,-14.9028 1903.6194,-18.2905 1913.5795,-21.9024 1913.658,-14.9028"/>
<text text-anchor="middle" x="2558.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- sequencing_file -->
<g id="node22" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="535.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="535.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M540.1813,-347.5937C541.4933,-337.2082 541.2433,-324.4582 534.9954,-315 530.399,-308.0419 515.0963,-300.4492 499.088,-294.0382"/>
<polygon fill="#000000" stroke="#000000" points="500.2466,-290.7339 489.6566,-290.4137 497.7355,-297.268 500.2466,-290.7339"/>
<text text-anchor="middle" x="607.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node23" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2723.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2723.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2697.0944,-88.1527C2676.5468,-76.2428 2647.0745,-61.1696 2618.9954,-54 2550.9842,-36.6343 2067.6143,-23.064 1913.8436,-19.1471"/>
<polygon fill="#000000" stroke="#000000" points="1913.8605,-15.6465 1903.7751,-18.8925 1913.6834,-22.6443 1913.8605,-15.6465"/>
<text text-anchor="middle" x="2714.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node24" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1679.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1679.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1679.9954,-260.9735C1679.9954,-249.1918 1679.9954,-233.5607 1679.9954,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1683.4955,-220.0033 1679.9954,-210.0034 1676.4955,-220.0034 1683.4955,-220.0033"/>
<text text-anchor="middle" x="1747.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- pathology_file -->
<g id="node25" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="712.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="712.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M705.4023,-347.8183C699.6329,-336.4063 690.5389,-322.4802 677.9954,-315 645.5574,-295.6559 545.9024,-305.0182 508.9954,-297 505.193,-296.1739 501.2828,-295.1761 497.3879,-294.079"/>
<polygon fill="#000000" stroke="#000000" points="498.3927,-290.7264 487.808,-291.1884 496.3706,-297.4279 498.3927,-290.7264"/>
<text text-anchor="middle" x="754.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M488.8567,-267.2528C495.5036,-265.0774 502.4456,-262.8959 508.9954,-261 541.094,-251.709 550.4279,-253.9607 581.9954,-243 597.2148,-237.7156 599.3097,-231.6762 614.9954,-228 710.8438,-205.5366 1383.5647,-195.5403 1607.6038,-192.8089"/>
<polygon fill="#000000" stroke="#000000" points="1607.6552,-196.3086 1617.6121,-192.688 1607.5706,-189.3091 1607.6552,-196.3086"/>
<text text-anchor="middle" x="651.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M420.9185,-267.2968C413.1273,-264.9373 404.8319,-262.6717 396.9954,-261 364.1617,-253.9958 269.2757,-268.1138 246.9954,-243 242.5711,-238.013 242.8106,-233.1896 246.9954,-228 270.6895,-198.6167 293.3847,-219.1897 329.9954,-210 334.712,-208.8161 339.6101,-207.5256 344.4977,-206.1972"/>
<polygon fill="#000000" stroke="#000000" points="345.751,-209.4819 354.4536,-203.4392 343.8821,-202.736 345.751,-209.4819"/>
<text text-anchor="middle" x="283.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node30" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="541.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="541.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M446.2782,-261.0655C442.5419,-250.5896 440.3755,-237.5878 446.9954,-228 454.0541,-217.7766 482.1122,-207.9034 505.9205,-201.0907"/>
<polygon fill="#000000" stroke="#000000" points="507.0821,-204.4011 515.7903,-198.3663 505.2195,-197.6534 507.0821,-204.4011"/>
<text text-anchor="middle" x="483.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_radiation -->
<g id="node27" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1887.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1887.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1868.53,-261.1227C1855.6172,-250.1305 1837.8217,-236.5583 1819.9954,-228 1796.4324,-216.6876 1768.8696,-208.6212 1744.4617,-203.032"/>
<polygon fill="#000000" stroke="#000000" points="1745.0894,-199.5865 1734.5715,-200.8609 1743.5885,-206.4237 1745.0894,-199.5865"/>
<text text-anchor="middle" x="1926.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- laboratory_test -->
<g id="node28" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2163.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2163.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2239.2995,-358.7295C2321.696,-350.4496 2443.2196,-337.1468 2450.9954,-330 2484.6024,-299.1111 2477.9599,-251.7766 2438.9954,-228 2410.0185,-210.318 1936.8516,-197.7947 1752.6081,-193.5672"/>
<polygon fill="#000000" stroke="#000000" points="1752.5503,-190.0651 1742.4732,-193.3364 1752.3909,-197.0633 1752.5503,-190.0651"/>
<text text-anchor="middle" x="2537.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2085.141,-360.9186C1924.1267,-350.7162 1545.903,-327.6376 1227.9954,-315 1068.2937,-308.6515 666.4267,-324.5739 508.9954,-297 505.0562,-296.3101 501.013,-295.3884 496.9971,-294.3256"/>
<polygon fill="#000000" stroke="#000000" points="497.7261,-290.8923 487.1456,-291.4444 495.7611,-297.6108 497.7261,-290.8923"/>
<text text-anchor="middle" x="1601.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- cytogenomic_file -->
<g id="node29" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="896.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="896.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M877.0128,-348.4435C862.3258,-336.6793 841.294,-322.0914 819.9954,-315 754.3136,-293.1312 576.9792,-310.0593 508.9954,-297 505.1211,-296.2558 501.1419,-295.3059 497.1848,-294.2327"/>
<polygon fill="#000000" stroke="#000000" points="498.0484,-290.8383 487.4663,-291.3576 496.0625,-297.5507 498.0484,-290.8383"/>
<text text-anchor="middle" x="920.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M569.6699,-188.3658C736.8679,-166.4092 1611.9544,-51.4922 1821.7556,-23.9409"/>
<polygon fill="#000000" stroke="#000000" points="1822.3465,-27.3935 1831.8056,-22.6211 1821.435,-20.4531 1822.3465,-27.3935"/>
<text text-anchor="middle" x="1359.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M537.37,-210.151C533.9539,-220.7037 528.4122,-233.7101 519.9954,-243 513.3099,-250.3789 504.7468,-256.581 496.0461,-261.6449"/>
<polygon fill="#000000" stroke="#000000" points="494.1494,-258.6909 487.0021,-266.5118 497.4666,-264.8551 494.1494,-258.6909"/>
<text text-anchor="middle" x="553.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node31" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2063.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2063.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2051.7336,-261.2393C2042.7198,-249.7003 2029.3933,-235.4634 2013.9954,-228 1969.3001,-206.3361 1836.2269,-197.5636 1752.1633,-194.1182"/>
<polygon fill="#000000" stroke="#000000" points="1752.294,-190.6207 1742.1639,-193.7239 1752.0182,-197.6153 1752.294,-190.6207"/>
<text text-anchor="middle" x="2077.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- family_relationship -->
<g id="node32" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2234.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2234.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2205.2614,-261.697C2183.7204,-250.0522 2153.4942,-235.5029 2124.9954,-228 2056.6485,-210.0063 1859.8527,-199.3799 1752.2989,-194.7557"/>
<polygon fill="#000000" stroke="#000000" points="1752.3156,-191.2534 1742.1764,-194.3269 1752.0193,-198.2471 1752.3156,-191.2534"/>
<text text-anchor="middle" x="2244.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
</g>
</svg>
</div>
