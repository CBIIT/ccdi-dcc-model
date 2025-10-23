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
<svg width="2880pt" height="392pt"
 viewBox="0.00 0.00 2880.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2876.1938,-388 2876.1938,4 -4,4"/>
<!-- consent_group -->
<g id="node1" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="632" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="632" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- study -->
<g id="node18" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="632" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="632" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge24" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M632,-86.9735C632,-75.1918 632,-59.5607 632,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="635.5001,-46.0033 632,-36.0034 628.5001,-46.0034 635.5001,-46.0033"/>
<text text-anchor="middle" x="695.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- methylation_array_file -->
<g id="node2" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2443" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2443" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node16" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2164" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2164" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2407.6995,-348.7637C2378.3259,-334.4614 2340.7232,-316.262 2337,-315 2297.3339,-301.5549 2250.7735,-292.2117 2215.9533,-286.4192"/>
<polygon fill="#000000" stroke="#000000" points="2216.4339,-282.9515 2206.0029,-284.8071 2215.3144,-289.8614 2216.4339,-282.9515"/>
<text text-anchor="middle" x="2459.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_funding -->
<g id="node3" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="105" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="105" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M91.9925,-86.9559C85.9242,-76.1766 81.676,-62.8952 90,-54 106.824,-36.0214 457.0251,-23.4147 585.3785,-19.3828"/>
<polygon fill="#000000" stroke="#000000" points="585.7788,-22.8721 595.6652,-19.0631 585.5613,-15.8755 585.7788,-22.8721"/>
<text text-anchor="middle" x="152" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- family_relationship -->
<g id="node4" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1195" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1195" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1179" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1179" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1185.8396,-260.7422C1183.4797,-255.1833 1181.2536,-248.9634 1180,-243 1178.4645,-235.6958 1177.8317,-227.6732 1177.6736,-220.197"/>
<polygon fill="#000000" stroke="#000000" points="1181.1738,-220.1401 1177.7216,-210.1235 1174.1739,-220.1067 1181.1738,-220.1401"/>
<text text-anchor="middle" x="1259.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1865" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1865" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1875.4428,-347.9246C1883.146,-336.4033 1894.7449,-322.3114 1909,-315 1949.0999,-294.4329 2066.9059,-306.3125 2111,-297 2114.5862,-296.2426 2118.2663,-295.3176 2121.9346,-294.2909"/>
<polygon fill="#000000" stroke="#000000" points="2122.9886,-297.6288 2131.545,-291.3807 2120.9598,-290.9292 2122.9886,-297.6288"/>
<text text-anchor="middle" x="1980.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- generic_file -->
<g id="node6" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="78" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="78" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M91.2163,-348.2251C110.0751,-324.2672 147.0968,-282.1811 189,-261 262.7578,-223.7172 289.868,-237.1955 372,-228 513.1068,-212.2017 935.8779,-198.8726 1106.4557,-193.9905"/>
<polygon fill="#000000" stroke="#000000" points="1106.6931,-197.4852 1116.5894,-193.7019 1106.4938,-190.488 1106.6931,-197.4852"/>
<text text-anchor="middle" x="242" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M133.5868,-356.2561C207.9022,-343.7678 343.8694,-322.7992 461,-315 643.9391,-302.8188 1930.2725,-327.8658 2111,-297 2114.7148,-296.3656 2118.5204,-295.5103 2122.304,-294.5156"/>
<polygon fill="#000000" stroke="#000000" points="2123.5817,-297.7883 2132.1908,-291.613 2121.6098,-291.0717 2123.5817,-297.7883"/>
<text text-anchor="middle" x="514" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge34" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M49.3986,-349.5577C27.1374,-334.3961 0,-309.6315 0,-279 0,-279 0,-279 0,-105 0,-81.2545 45.1116,-64.3657 82,-54 176.0236,-27.5792 469.7954,-20.4039 584.9872,-18.5809"/>
<polygon fill="#000000" stroke="#000000" points="585.2962,-22.0767 595.242,-18.4254 585.19,-15.0775 585.2962,-22.0767"/>
<text text-anchor="middle" x="53" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_response -->
<g id="node7" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1864" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1864" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1804.2207,-264.0587C1755.8974,-252.5237 1685.96,-237.0511 1624,-228 1493.235,-208.8978 1339.2623,-199.2716 1250.999,-194.9723"/>
<polygon fill="#000000" stroke="#000000" points="1250.9852,-191.4678 1240.8295,-194.4865 1250.6511,-198.4598 1250.9852,-191.4678"/>
<text text-anchor="middle" x="1786" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- genetic_analysis -->
<g id="node8" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1158" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1158" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1094.5922,-353.4431C1034.4315,-341.9348 941.3783,-325.1833 860,-315 835.0043,-311.8721 651.0907,-315.5061 634,-297 623.1447,-285.2457 623.4342,-273.0152 634,-261 664.7792,-225.9985 966.338,-204.2182 1107.1916,-195.8767"/>
<polygon fill="#000000" stroke="#000000" points="1107.6792,-199.3543 1117.4576,-195.2757 1107.2701,-192.3662 1107.6792,-199.3543"/>
<text text-anchor="middle" x="704" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1229.2903,-355.5045C1313.2205,-343.5897 1456.9151,-324.5696 1581,-315 1698.4968,-305.9385 1995.0725,-318.1761 2111,-297 2114.7073,-296.3228 2118.5076,-295.4377 2122.2877,-294.4232"/>
<polygon fill="#000000" stroke="#000000" points="2123.5787,-297.691 2132.169,-291.4896 2121.5864,-290.9805 2123.5787,-297.691"/>
<text text-anchor="middle" x="1651" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2044" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2044" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2006.9163,-265.1433C1972.6854,-253.0283 1920.1669,-236.1372 1873,-228 1755.3258,-207.6991 1404.6825,-197.2686 1251.7151,-193.5821"/>
<polygon fill="#000000" stroke="#000000" points="1251.5698,-190.0778 1241.4892,-193.3387 1251.4031,-197.0758 1251.5698,-190.0778"/>
<text text-anchor="middle" x="1982" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="253" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="253" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M262.7195,-347.9413C276.5669,-324.0567 304.3009,-282.4845 340,-261 401.8378,-223.7847 427.4249,-237.2678 499,-228 614.7549,-213.0117 956.513,-199.7268 1106.7539,-194.435"/>
<polygon fill="#000000" stroke="#000000" points="1106.9305,-197.9311 1116.8018,-194.083 1106.6853,-190.9354 1106.9305,-197.9311"/>
<text text-anchor="middle" x="382.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M290.4253,-353.4876C298.1444,-351.3237 306.276,-349.3417 314,-348 377.3778,-336.9912 827.7146,-317.3087 892,-315 1027.3719,-310.1383 1977.5184,-320.0618 2111,-297 2114.7136,-296.3584 2118.5183,-295.4981 2122.3014,-294.5001"/>
<polygon fill="#000000" stroke="#000000" points="2123.5812,-297.772 2132.1872,-291.5923 2121.6059,-291.0565 2123.5812,-297.772"/>
<text text-anchor="middle" x="934.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M242.4662,-348.3702C223.0371,-313.3825 186.0737,-233.4246 215,-174 254.5296,-92.7926 294.1311,-84.8952 379,-54 416.0229,-40.5224 523.456,-28.4174 585.7772,-22.268"/>
<polygon fill="#000000" stroke="#000000" points="586.1324,-25.75 595.7461,-21.2971 585.4539,-18.783 586.1324,-25.75"/>
<text text-anchor="middle" x="257.5" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1122.3135,-184.4553C1035.4794,-172.6777 864.4084,-148.605 720,-123 713.5007,-121.8476 706.7448,-120.5842 699.9949,-119.278"/>
<polygon fill="#000000" stroke="#000000" points="700.6276,-115.8355 690.1403,-117.3416 699.2778,-122.7041 700.6276,-115.8355"/>
<text text-anchor="middle" x="971.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- laboratory_test -->
<g id="node12" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1618" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1618" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1583.1982,-349.5003C1575.9025,-344.3284 1569.1649,-337.8638 1565,-330 1561.8798,-324.1086 1562.4488,-321.1592 1565,-315 1569.3296,-304.5475 1578.6704,-307.4525 1583,-297 1594.7406,-268.6558 1602.3793,-250.0037 1581,-228 1558.5673,-204.9122 1361.2005,-196.4206 1251.6027,-193.4667"/>
<polygon fill="#000000" stroke="#000000" points="1251.6907,-189.9679 1241.6028,-193.2059 1251.5082,-196.9655 1251.6907,-189.9679"/>
<text text-anchor="middle" x="1659.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1666.1981,-351.3616C1684.787,-345.307 1706.0885,-337.8645 1725,-330 1738.7644,-324.276 1740.5828,-318.7903 1755,-315 1908.2178,-274.7189 1955.3956,-326.758 2111,-297 2114.6508,-296.3018 2118.3939,-295.4104 2122.1201,-294.3992"/>
<polygon fill="#000000" stroke="#000000" points="2123.2862,-297.7038 2131.8694,-291.4926 2121.2862,-290.9956 2123.2862,-297.7038"/>
<text text-anchor="middle" x="1820.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_personnel -->
<g id="node13" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="448" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="448" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M458.3282,-86.89C465.552,-75.805 476.1848,-62.2168 489,-54 518.1105,-35.3351 556.3125,-26.3443 585.9077,-22.0152"/>
<polygon fill="#000000" stroke="#000000" points="586.5387,-25.4621 595.9879,-20.6701 585.6128,-18.5236 586.5387,-25.4621"/>
<text text-anchor="middle" x="558.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node14" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2659" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2659" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2666.5192,-348.1711C2669.74,-337.4728 2671.2974,-324.201 2664,-315 2611.2449,-248.4834 2376.1695,-239.0929 2292,-228 2089.8612,-201.3595 1465.2769,-194.18 1251.5775,-192.4775"/>
<polygon fill="#000000" stroke="#000000" points="1251.4395,-188.9764 1241.4124,-192.3982 1251.3848,-195.9762 1251.4395,-188.9764"/>
<text text-anchor="middle" x="2687.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2623.2139,-352.2639C2608.0606,-346.0401 2590.3877,-338.2352 2575,-330 2564.24,-324.2414 2563.5248,-319.0147 2552,-315 2491.8697,-294.0532 2310.374,-284.4464 2218.5139,-280.8285"/>
<polygon fill="#000000" stroke="#000000" points="2218.4316,-277.3229 2208.3047,-280.4366 2218.1631,-284.3177 2218.4316,-277.3229"/>
<text text-anchor="middle" x="2619.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node15" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2056" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2056" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2054.5137,-347.6258C2054.6328,-336.994 2056.5798,-323.9828 2064,-315 2065.0139,-313.7726 2094.0129,-303.4006 2120.5205,-294.1034"/>
<polygon fill="#000000" stroke="#000000" points="2121.8342,-297.3518 2130.1173,-290.7456 2119.5224,-290.7446 2121.8342,-297.3518"/>
<text text-anchor="middle" x="2130.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2133.5795,-265.8151C2101.43,-252.1242 2052.7062,-232.1322 2033,-228 1957.6896,-212.2082 1443.8134,-198.3739 1251.4692,-193.6915"/>
<polygon fill="#000000" stroke="#000000" points="1251.5396,-190.1923 1241.4578,-193.449 1251.37,-197.1902 1251.5396,-190.1923"/>
<text text-anchor="middle" x="2110.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node24" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2504" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2504" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2201.685,-269.3571C2263.1525,-253.6286 2385.0177,-222.4455 2453.768,-204.8535"/>
<polygon fill="#000000" stroke="#000000" points="2454.6924,-208.2298 2463.5126,-202.36 2452.9571,-201.4483 2454.6924,-208.2298"/>
<text text-anchor="middle" x="2390.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node29" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2164" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2164" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2192.1328,-264.9861C2200.3886,-259.3644 2208.4233,-252.0415 2213,-243 2219.7778,-229.61 2208.9137,-217.3802 2195.7088,-208.2552"/>
<polygon fill="#000000" stroke="#000000" points="2197.191,-205.0544 2186.8551,-202.7261 2193.4831,-210.9917 2197.191,-205.0544"/>
<text text-anchor="middle" x="2251.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- clinical_measure_file -->
<g id="node17" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="432" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="432" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M428.6458,-347.764C425.3978,-323.6786 424.0928,-281.8795 449,-261 498.7089,-219.3294 931.9826,-200.2749 1106.5608,-194.238"/>
<polygon fill="#000000" stroke="#000000" points="1106.806,-197.7317 1116.6808,-193.8926 1106.5672,-190.7358 1106.806,-197.7317"/>
<text text-anchor="middle" x="535" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M530.8218,-358.5463C684.9697,-347.2167 992.0621,-325.8372 1253,-315 1348.2722,-311.0432 2017.0886,-313.5257 2111,-297 2114.7116,-296.3469 2118.5149,-295.4785 2122.297,-294.4752"/>
<polygon fill="#000000" stroke="#000000" points="2123.5805,-297.7458 2132.1814,-291.5591 2121.5997,-291.0319 2123.5805,-297.7458"/>
<text text-anchor="middle" x="1339" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M370.5682,-351.0498C342.3932,-340.7889 311.6216,-323.9822 295,-297 286.6082,-283.3773 292.478,-276.8 295,-261 301.4135,-220.8201 322.6676,-115.1987 352,-87 385.3254,-54.9627 516.2722,-33.2414 586.659,-23.624"/>
<polygon fill="#000000" stroke="#000000" points="587.1395,-27.0909 596.5857,-22.293 586.2093,-20.153 587.1395,-27.0909"/>
<text text-anchor="middle" x="399" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="836" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="836" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M859.7644,-262.8374C877.932,-251.2769 904.0236,-236.341 929,-228 987.0757,-208.6053 1056.1726,-199.6577 1106.9908,-195.5307"/>
<polygon fill="#000000" stroke="#000000" points="1107.5216,-199.0004 1117.2241,-194.7446 1106.9854,-192.0209 1107.5216,-199.0004"/>
<text text-anchor="middle" x="972.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="789" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="789" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M783.9473,-87.0236C779.9634,-75.9918 773.3237,-62.4128 763,-54 749.6198,-43.0964 708.7203,-32.8934 676.1415,-26.1538"/>
<polygon fill="#000000" stroke="#000000" points="676.8323,-22.7228 666.3376,-24.1765 675.4482,-29.5846 676.8323,-22.7228"/>
<text text-anchor="middle" x="822.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node21" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="930" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="930" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge31" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M916.043,-87.4373C905.9184,-75.9867 891.2018,-61.774 875,-54 841.1056,-37.7365 738.6472,-26.7997 678.1367,-21.5662"/>
<polygon fill="#000000" stroke="#000000" points="678.3369,-18.0707 668.0775,-20.7153 677.7468,-25.0458 678.3369,-18.0707"/>
<text text-anchor="middle" x="948" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1081" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1081" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge38" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1060.6317,-87.7008C1045.6945,-76.0578 1024.3703,-61.5091 1003,-54 944.3184,-33.3805 764.5731,-23.4286 678.6676,-19.7502"/>
<polygon fill="#000000" stroke="#000000" points="678.5611,-16.2427 668.4238,-19.3223 678.269,-23.2367 678.5611,-16.2427"/>
<text text-anchor="middle" x="1088.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pathology_file -->
<g id="node23" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="2233" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="2233" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2223.0296,-347.8268C2217.16,-337.758 2209.2787,-325.2433 2201,-315 2197.6357,-310.8373 2193.8275,-306.6577 2189.9657,-302.6956"/>
<polygon fill="#000000" stroke="#000000" points="2192.1529,-299.9368 2182.5757,-295.406 2187.2371,-304.9203 2192.1529,-299.9368"/>
<text text-anchor="middle" x="2272" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2485.3361,-208.8329C2471.3912,-220.4115 2451.3085,-235.0783 2431,-243 2393.2562,-257.7226 2284.3326,-269.0047 2217.8455,-274.7609"/>
<polygon fill="#000000" stroke="#000000" points="2217.2235,-271.3011 2207.5565,-275.637 2217.8174,-278.2759 2217.2235,-271.3011"/>
<text text-anchor="middle" x="2498.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge18" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2458.856,-184.4563C2342.3476,-165.256 2021.8455,-114.1394 1753,-87 1518.623,-63.3401 1459.1225,-68.4827 1224,-54 1020.7649,-41.4815 778.2648,-26.8218 678.4332,-20.7988"/>
<polygon fill="#000000" stroke="#000000" points="678.571,-17.3009 668.3784,-20.1923 678.1495,-24.2882 678.571,-17.3009"/>
<text text-anchor="middle" x="2080.5" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="992" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="992" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1004.0661,-260.9207C1012.3618,-249.8479 1024.3241,-236.2618 1038,-228 1060.0471,-214.681 1086.897,-206.2609 1111.2274,-200.9501"/>
<polygon fill="#000000" stroke="#000000" points="1112.0251,-204.3595 1121.1214,-198.9274 1110.623,-197.5014 1112.0251,-204.3595"/>
<text text-anchor="middle" x="1106" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_status -->
<g id="node26" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2802" cy="-366" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2802" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- survival -->
<g id="node27" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1361" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1361" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1357.5492,-260.9121C1354.5071,-249.8358 1348.9456,-236.2491 1339,-228 1324.7274,-216.162 1283.5576,-207.0507 1246.5564,-200.956"/>
<polygon fill="#000000" stroke="#000000" points="1246.6823,-197.4321 1236.2565,-199.3172 1245.5823,-204.3451 1246.6823,-197.4321"/>
<text text-anchor="middle" x="1389.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- radiology_file -->
<g id="node28" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1501" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1501" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1482.9711,-261.4429C1470.1085,-249.9948 1451.8187,-235.7828 1433,-228 1400.7385,-214.6577 1312.7342,-204.156 1249.3589,-198.0194"/>
<polygon fill="#000000" stroke="#000000" points="1249.304,-194.4985 1239.0174,-197.0354 1248.6408,-201.467 1249.304,-194.4985"/>
<text text-anchor="middle" x="1518" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2162.1791,-210.2957C2161.6947,-215.9642 2161.2398,-222.2351 2161,-228 2160.6979,-235.2639 2160.8968,-243.1048 2161.3068,-250.4084"/>
<polygon fill="#000000" stroke="#000000" points="2157.8303,-250.8658 2162.025,-260.5949 2164.813,-250.3735 2157.8303,-250.8658"/>
<text text-anchor="middle" x="2185" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge16" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2136.6269,-187.6055C2018.7533,-168.8242 1542.6165,-94.4184 1149,-54 975.9494,-36.2303 769.3924,-24.7672 678.6498,-20.2205"/>
<polygon fill="#000000" stroke="#000000" points="678.5865,-16.7131 668.4252,-19.713 678.2394,-23.7045 678.5865,-16.7131"/>
<text text-anchor="middle" x="1725" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
</g>
</svg>
</div>
