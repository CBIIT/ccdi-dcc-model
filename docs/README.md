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
<svg width="2785pt" height="392pt"
 viewBox="0.00 0.00 2785.09 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2781.0923,-388 2781.0923,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1200.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1200.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.7881,-86.5499C79.8701,-75.6178 79.8793,-62.3185 88.0923,-54 107.0992,-34.749 944.9042,-21.6159 1153.4586,-18.6412"/>
<polygon fill="#000000" stroke="#000000" points="1153.5266,-22.1407 1163.4759,-18.4992 1153.4273,-15.1414 1153.5266,-22.1407"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- consent_group -->
<g id="node2" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1065.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1065.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge21" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1056.9957,-86.7495C1053.641,-76.1615 1051.9826,-63.1529 1059.0923,-54 1070.8149,-38.9083 1117.9196,-29.0818 1154.4964,-23.5677"/>
<polygon fill="#000000" stroke="#000000" points="1155.0974,-27.0173 1164.4956,-22.126 1154.0984,-20.089 1155.0974,-27.0173"/>
<text text-anchor="middle" x="1122.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_arm -->
<g id="node3" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="718.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="718.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge22" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M712.9133,-86.671C711.0424,-75.7845 711.0572,-62.4905 719.0923,-54 733.8988,-38.3543 1035.721,-24.5996 1153.5481,-19.8058"/>
<polygon fill="#000000" stroke="#000000" points="1153.85,-23.2966 1163.7008,-19.3964 1153.5679,-16.3023 1153.85,-23.2966"/>
<text text-anchor="middle" x="767.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- pdx -->
<g id="node4" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2074.0923" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2074.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge15" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2046.6446,-188.1724C2018.072,-184.2698 1972.004,-178.2072 1932.0923,-174 1797.6942,-159.8328 1446.4633,-184.436 1326.0923,-123 1307.2856,-113.4013 1310.6273,-101.3 1295.0923,-87 1275.1934,-68.683 1250.4025,-50.8183 1231.1357,-37.8572"/>
<polygon fill="#000000" stroke="#000000" points="1232.9765,-34.8783 1222.7094,-32.2632 1229.1048,-40.7101 1232.9765,-34.8783"/>
<text text-anchor="middle" x="1350.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample -->
<g id="node21" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1978.0923" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1978.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2099.3818,-200.0773C2123.3612,-209.0664 2153.7099,-224.7529 2139.0923,-243 2125.6923,-259.7271 2072.9351,-269.2002 2031.4176,-274.1841"/>
<polygon fill="#000000" stroke="#000000" points="2030.944,-270.7153 2021.4055,-275.3268 2031.7379,-277.6701 2030.944,-270.7153"/>
<text text-anchor="middle" x="2166.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1535.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1535.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1540.3624,-347.9269C1544.7393,-336.4066 1552.2091,-322.315 1564.0923,-315 1598.2928,-293.9471 1885.6436,-304.5299 1925.0923,-297 1928.7433,-296.3031 1932.4865,-295.4126 1936.2129,-294.4019"/>
<polygon fill="#000000" stroke="#000000" points="1937.3785,-297.7067 1945.9623,-291.4963 1935.3792,-290.9983 1937.3785,-297.7067"/>
<text text-anchor="middle" x="1655.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="108.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="108.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1194.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1194.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M119.0152,-261.1021C127.2979,-249.3416 139.8438,-234.8989 155.0923,-228 193.7737,-210.4993 876.678,-211.8869 919.0923,-210 988.7256,-206.9022 1068.1631,-201.5009 1123.6959,-197.4211"/>
<polygon fill="#000000" stroke="#000000" points="1124.0645,-200.9035 1133.7791,-196.6755 1123.5482,-193.9226 1124.0645,-200.9035"/>
<text text-anchor="middle" x="214.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node7" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="287.0923" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="287.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M282.4532,-347.6206C277.7447,-324.1559 273.9424,-283.866 296.0923,-261 331.0394,-224.9231 904.6256,-210.853 919.0923,-210 988.4488,-205.9105 1067.605,-200.6688 1123.1277,-196.8979"/>
<polygon fill="#000000" stroke="#000000" points="1123.4731,-200.3826 1133.2123,-196.2115 1122.9977,-193.3987 1123.4731,-200.3826"/>
<text text-anchor="middle" x="382.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M271.0037,-348.1027C257.7386,-331.4504 241.0923,-305.3116 241.0923,-279 241.0923,-279 241.0923,-279 241.0923,-105 241.0923,-58.6258 961.7346,-27.2755 1153.6226,-19.7497"/>
<polygon fill="#000000" stroke="#000000" points="1153.8131,-23.245 1163.6694,-19.3586 1153.5408,-16.2503 1153.8131,-23.245"/>
<text text-anchor="middle" x="327.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M378.0249,-356.0181C492.2717,-343.9382 694.4229,-324.0897 868.0923,-315 985.3932,-308.8606 1809.3683,-317.1287 1925.0923,-297 1928.8051,-296.3542 1932.6094,-295.491 1936.3921,-294.491"/>
<polygon fill="#000000" stroke="#000000" points="1937.6733,-297.7624 1946.2774,-291.5802 1935.6959,-291.0475 1937.6733,-297.7624"/>
<text text-anchor="middle" x="954.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge20" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1138.6793,-183.608C1119.7589,-178.3606 1099.7092,-169.8381 1085.0923,-156 1078.5397,-149.7966 1074.097,-141.1864 1071.1003,-132.8055"/>
<polygon fill="#000000" stroke="#000000" points="1074.4499,-131.7903 1068.2069,-123.2302 1067.7491,-133.8151 1074.4499,-131.7903"/>
<text text-anchor="middle" x="1135.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- pathology_file -->
<g id="node9" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1745.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1745.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1746.3269,-347.8963C1748.0997,-336.6675 1752.2912,-322.9178 1762.0923,-315 1790.44,-292.099 1889.5178,-304.9063 1925.0923,-297 1928.6703,-296.2048 1932.3446,-295.2532 1936.009,-294.2085"/>
<polygon fill="#000000" stroke="#000000" points="1937.0751,-297.5425 1945.6131,-291.2692 1935.0266,-290.8489 1937.0751,-297.5425"/>
<text text-anchor="middle" x="1823.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="855.0923" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="855.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M850.8158,-347.9546C846.4995,-324.8511 843.1206,-284.9512 864.0923,-261 897.4726,-222.8774 1036.656,-204.7593 1123.254,-197.0247"/>
<polygon fill="#000000" stroke="#000000" points="1123.6232,-200.5059 1133.2831,-196.1542 1123.0179,-193.5321 1123.6232,-200.5059"/>
<text text-anchor="middle" x="906.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge31" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M848.4267,-347.9278C846.651,-342.2683 844.9805,-335.9465 844.0923,-330 841.6574,-313.6992 837.7821,-282.0834 845.0923,-261 876.8912,-169.2882 901.2003,-147.5197 977.0923,-87 1028.859,-45.7188 1105.3782,-29.0253 1153.9714,-22.3495"/>
<polygon fill="#000000" stroke="#000000" points="1154.4265,-25.8199 1163.8978,-21.0718 1153.5328,-18.8772 1154.4265,-25.8199"/>
<text text-anchor="middle" x="928.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M899.446,-356.2522C957.0932,-344.0693 1061.0436,-323.7565 1151.0923,-315 1322.3311,-298.3485 1755.6833,-327.0099 1925.0923,-297 1928.8031,-296.3426 1932.6059,-295.4714 1936.3877,-294.4661"/>
<polygon fill="#000000" stroke="#000000" points="1937.6725,-297.7362 1946.2715,-291.5469 1935.6897,-291.0228 1937.6725,-297.7362"/>
<text text-anchor="middle" x="1193.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- medical_history -->
<g id="node11" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="562.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="562.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M568.7551,-260.8874C574.0248,-249.35 582.5972,-235.254 595.0923,-228 626.274,-209.8975 883.1026,-212.1775 919.0923,-210 988.4424,-205.8041 1067.5995,-200.5767 1123.1242,-196.8381"/>
<polygon fill="#000000" stroke="#000000" points="1123.4673,-200.323 1133.2091,-196.1579 1122.9962,-193.3389 1123.4673,-200.323"/>
<text text-anchor="middle" x="663.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1929.0923" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1929.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1903.399,-348.6178C1892.3023,-338.903 1883.4221,-326.4747 1891.0923,-315 1893.9154,-310.7766 1914.5116,-302.166 1934.9541,-294.4249"/>
<polygon fill="#000000" stroke="#000000" points="1936.4374,-297.6073 1944.5839,-290.8333 1933.9912,-291.0486 1936.4374,-297.6073"/>
<text text-anchor="middle" x="1962.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- sequencing_file -->
<g id="node13" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="2120.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="2120.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2089.7589,-349.1439C2079.3278,-343.2216 2067.6265,-336.4372 2057.0923,-330 2046.6786,-323.6365 2044.3363,-321.6331 2034.0923,-315 2026.409,-310.025 2018.1202,-304.6829 2010.3358,-299.6769"/>
<polygon fill="#000000" stroke="#000000" points="2012.1254,-296.6666 2001.8205,-294.2052 2008.3413,-302.5556 2012.1254,-296.6666"/>
<text text-anchor="middle" x="2123.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- treatment -->
<g id="node14" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="723.0923" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="723.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M726.7565,-260.8818C730.0615,-249.4965 736.1511,-235.5765 747.0923,-228 754.7187,-222.7189 998.8762,-205.3391 1123.0508,-196.8088"/>
<polygon fill="#000000" stroke="#000000" points="1123.4938,-200.2868 1133.231,-196.1109 1123.015,-193.3032 1123.4938,-200.2868"/>
<text text-anchor="middle" x="794.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- cell_line -->
<g id="node15" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1874.0923" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1874.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge33" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1824.8136,-190.7372C1705.2022,-187.3754 1402.0811,-176.9971 1303.0923,-156 1261.8233,-147.2462 1240.4265,-155.9585 1214.0923,-123 1196.9475,-101.5425 1195.0421,-69.3851 1196.4302,-46.3152"/>
<polygon fill="#000000" stroke="#000000" points="1199.9374,-46.3754 1197.29,-36.1167 1192.9621,-45.7873 1199.9374,-46.3754"/>
<text text-anchor="middle" x="1254.5923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1867.7278,-210.1045C1865.2293,-220.6407 1864.3504,-233.6461 1871.0923,-243 1885.8844,-263.523 1901.115,-252.9322 1925.0923,-261 1928.1777,-262.0382 1931.3632,-263.1129 1934.5697,-264.1967"/>
<polygon fill="#000000" stroke="#000000" points="1933.5791,-267.5565 1944.1734,-267.4486 1935.8242,-260.9262 1933.5791,-267.5565"/>
<text text-anchor="middle" x="1911.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- diagnosis -->
<g id="node16" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1165.0923" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1165.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1168.141,-347.7078C1173.2017,-317.3436 1183.3718,-256.3226 1189.3679,-220.3464"/>
<polygon fill="#000000" stroke="#000000" points="1192.8927,-220.4865 1191.0844,-210.0471 1185.988,-219.3356 1192.8927,-220.4865"/>
<text text-anchor="middle" x="1226.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1193.189,-350.4903C1216.895,-338.292 1252.14,-322.1958 1285.0923,-315 1424.0951,-284.6461 1785.0558,-322.1583 1925.0923,-297 1928.8015,-296.3336 1932.6032,-295.4561 1936.3842,-294.4466"/>
<polygon fill="#000000" stroke="#000000" points="1937.6718,-297.7156 1946.2669,-291.5208 1935.6847,-291.0036 1937.6718,-297.7156"/>
<text text-anchor="middle" x="1329.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- laboratory_test -->
<g id="node18" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1319.0923" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1319.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1315.1958,-347.7128C1312.8137,-337.8361 1309.3945,-325.5412 1305.0923,-315 1294.7176,-289.5806 1292.487,-282.2415 1275.0923,-261 1260.9395,-243.7175 1242.0845,-227.3668 1226.1272,-214.9237"/>
<polygon fill="#000000" stroke="#000000" points="1228.1601,-212.0724 1218.087,-208.7887 1223.9138,-217.6374 1228.1601,-212.0724"/>
<text text-anchor="middle" x="1362.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1343.5644,-348.7926C1362.0085,-336.868 1388.4313,-321.935 1414.0923,-315 1523.7831,-285.3557 1813.3287,-317.4883 1925.0923,-297 1928.7483,-296.3298 1932.495,-295.458 1936.2237,-294.4598"/>
<polygon fill="#000000" stroke="#000000" points="1937.3808,-297.7676 1945.9769,-291.5742 1935.3948,-291.0552 1937.3808,-297.7676"/>
<text text-anchor="middle" x="1479.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_admin -->
<g id="node19" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1453.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1453.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1418.578,-89.1815C1394.3938,-78.4426 1361.1504,-64.3653 1331.0923,-54 1302.0574,-43.9876 1268.6666,-34.8467 1242.8633,-28.2812"/>
<polygon fill="#000000" stroke="#000000" points="1243.5682,-24.8495 1233.0167,-25.8067 1241.8621,-31.6385 1243.5682,-24.8495"/>
<text text-anchor="middle" x="1424.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node20" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1058.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1058.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1032.698,-261.4112C1021.364,-251.4135 1012.3265,-238.7777 1021.0923,-228 1034.1743,-211.9154 1081.6689,-202.78 1123.5907,-197.7396"/>
<polygon fill="#000000" stroke="#000000" points="1124.0059,-201.215 1133.5451,-196.6048 1123.213,-194.26 1124.0059,-201.215"/>
<text text-anchor="middle" x="1100.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2013.3834,-267.8427C2026.8714,-262.1552 2041.5316,-254.0527 2052.0923,-243 2058.4124,-236.3854 2063.0697,-227.6688 2066.4285,-219.3168"/>
<polygon fill="#000000" stroke="#000000" points="2069.7501,-220.4222 2069.7969,-209.8275 2063.1533,-218.0806 2069.7501,-220.4222"/>
<text text-anchor="middle" x="2098.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1945.3035,-266.7521C1938.6804,-264.5944 1931.7162,-262.5474 1925.0923,-261 1865.7193,-247.1299 1847.7043,-259.7975 1789.0923,-243 1773.605,-238.5615 1771.7207,-231.9124 1756.0923,-228 1665.4817,-205.3166 1397.0447,-196.439 1266.7152,-193.3951"/>
<polygon fill="#000000" stroke="#000000" points="1266.5142,-189.8896 1256.4369,-193.1604 1266.3544,-196.8878 1266.5142,-189.8896"/>
<text text-anchor="middle" x="1825.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1973.9223,-261.0503C1970.6325,-250.3065 1965.0637,-237.0294 1956.0923,-228 1947.013,-218.8622 1935.2217,-211.8683 1923.4248,-206.5879"/>
<polygon fill="#000000" stroke="#000000" points="1924.5938,-203.2841 1914.0144,-202.7121 1921.928,-209.7567 1924.5938,-203.2841"/>
<text text-anchor="middle" x="2002.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study_funding -->
<g id="node22" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1619.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1619.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1583.7227,-88.8812C1557.1281,-77.421 1519.5068,-62.592 1485.0923,-54 1402.6432,-33.4157 1303.6879,-24.2844 1246.7269,-20.4791"/>
<polygon fill="#000000" stroke="#000000" points="1246.7967,-16.9765 1236.5931,-19.829 1246.3485,-23.9622 1246.7967,-16.9765"/>
<text text-anchor="middle" x="1592.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- genetic_analysis -->
<g id="node23" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2346.0923" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2346.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2353.967,-347.8806C2357.1753,-337.5907 2358.9253,-324.8407 2353.0923,-315 2312.0183,-245.7049 2271.7634,-249.3562 2194.0923,-228 2171.7567,-221.8587 1492.1223,-200.9505 1266.2649,-194.1537"/>
<polygon fill="#000000" stroke="#000000" points="1266.2773,-190.6526 1256.1766,-193.8504 1266.0669,-197.6494 1266.2773,-190.6526"/>
<text text-anchor="middle" x="2410.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge24" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2283.4486,-353.3353C2260.7461,-347.6393 2235.251,-339.9253 2213.0923,-330 2201.9545,-325.0112 2201.4569,-319.4479 2190.0923,-315 2138.758,-294.9087 2076.1102,-286.0176 2032.2794,-282.0905"/>
<polygon fill="#000000" stroke="#000000" points="2032.3736,-278.5862 2022.1162,-281.2385 2031.7888,-285.5617 2032.3736,-278.5862"/>
<text text-anchor="middle" x="2283.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment_response -->
<g id="node24" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1573.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1573.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1494.2681,-267.0163C1458.5475,-260.9293 1415.9304,-252.7486 1378.0923,-243 1357.6771,-237.7403 1353.3083,-233.9796 1333.0923,-228 1306.6079,-220.1663 1277.0125,-212.3703 1251.9595,-206.0466"/>
<polygon fill="#000000" stroke="#000000" points="1252.7917,-202.647 1242.2407,-203.6096 1251.089,-209.4368 1252.7917,-202.647"/>
<text text-anchor="middle" x="1461.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- survival -->
<g id="node25" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1744.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1744.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1708.4499,-266.802C1701.4249,-264.6659 1694.0685,-262.6142 1687.0923,-261 1634.5505,-248.8426 1617.5004,-262.1694 1567.0923,-243 1555.6852,-238.6621 1555.5969,-232.0722 1544.0923,-228 1494.5178,-210.4526 1353.2985,-200.224 1266.1391,-195.4072"/>
<polygon fill="#000000" stroke="#000000" points="1266.2242,-191.9068 1256.0494,-194.8604 1265.8453,-198.8965 1266.2242,-191.9068"/>
<text text-anchor="middle" x="1606.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- exposure -->
<g id="node26" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1863.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1863.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1823.9547,-266.6944C1816.4174,-264.5931 1808.548,-262.5817 1801.0923,-261 1743.1716,-248.7127 1724.5746,-263.6759 1669.0923,-243 1657.6565,-238.7384 1657.643,-231.9395 1646.0923,-228 1577.9741,-204.7675 1376.5665,-196.357 1267.0291,-193.4475"/>
<polygon fill="#000000" stroke="#000000" points="1266.8097,-189.9408 1256.7231,-193.1828 1266.6299,-196.9385 1266.8097,-189.9408"/>
<text text-anchor="middle" x="1712.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- publication -->
<g id="node27" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1777.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1777.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge3" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1747.224,-88.9494C1723.7113,-77.1256 1689.737,-61.7999 1658.0923,-54 1581.054,-35.0113 1347.1229,-23.7935 1246.7003,-19.7372"/>
<polygon fill="#000000" stroke="#000000" points="1246.6844,-16.2339 1236.5531,-19.3334 1246.406,-23.2284 1246.6844,-16.2339"/>
<text text-anchor="middle" x="1752.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- generic_file -->
<g id="node28" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2537.0923" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2537.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2534.0172,-347.8935C2528.7237,-323.1331 2515.2851,-279.6582 2484.0923,-261 2389.045,-204.1467 2347.4581,-237.2547 2237.0923,-228 2141.285,-219.9661 1487.3424,-200.5063 1266.6543,-194.0905"/>
<polygon fill="#000000" stroke="#000000" points="1266.5742,-190.5868 1256.4768,-193.7949 1266.3709,-197.5838 1266.5742,-190.5868"/>
<text text-anchor="middle" x="2568.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2588.1342,-354.6502C2626.0025,-342.8675 2671.0923,-320.1895 2671.0923,-279 2671.0923,-279 2671.0923,-279 2671.0923,-105 2671.0923,-31.8998 1498.213,-19.9791 1247.0666,-18.2644"/>
<polygon fill="#000000" stroke="#000000" points="1246.8442,-14.763 1236.8213,-18.1967 1246.7979,-21.7628 1246.8442,-14.763"/>
<text text-anchor="middle" x="2724.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2492.9779,-352.5067C2448.566,-339.1028 2383.0301,-319.8647 2357.0923,-315 2242.6213,-293.5305 2106.1691,-284.5605 2032.232,-281.0546"/>
<polygon fill="#000000" stroke="#000000" points="2032.3728,-277.5575 2022.2229,-280.5955 2032.0519,-284.5501 2032.3728,-277.5575"/>
<text text-anchor="middle" x="2466.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
</g>
</svg>
</div>
