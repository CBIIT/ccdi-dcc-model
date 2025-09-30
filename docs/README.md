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
<svg width="3212pt" height="392pt"
 viewBox="0.00 0.00 3211.89 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3207.887,-388 3207.887,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1707.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1707.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8475,-87.0163C79.831,-75.9816 79.7122,-62.4022 88.0923,-54 116.5939,-25.4234 1397.2837,-19.1456 1660.2129,-18.1571"/>
<polygon fill="#000000" stroke="#000000" points="1660.5669,-21.6559 1670.5539,-18.119 1660.541,-14.6559 1660.5669,-21.6559"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1958.0923" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1958.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="957.0923" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="957.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1905.3113,-361.0012C1853.8157,-355.536 1773.4686,-345.4421 1705.0923,-330 1683.2906,-325.0763 1679.1378,-318.6812 1657.0923,-315 1375.5451,-267.9861 1296.6855,-343.7373 1015.0923,-297 1010.0852,-296.169 1004.9103,-295.0139 999.8076,-293.6862"/>
<polygon fill="#000000" stroke="#000000" points="1000.7221,-290.3076 990.1473,-290.9597 998.8207,-297.0444 1000.7221,-290.3076"/>
<text text-anchor="middle" x="1749.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant -->
<g id="node23" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1852.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1852.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2010.8091,-361.1715C2052.1136,-356.1684 2104.7524,-346.6748 2118.0923,-330 2122.2569,-324.7942 2120.9245,-321.0351 2118.0923,-315 2116.0978,-310.75 2057.1851,-263.2998 2053.0923,-261 2007.9797,-235.6502 1951.9658,-217.366 1910.5369,-206.0143"/>
<polygon fill="#000000" stroke="#000000" points="1911.4329,-202.631 1900.8673,-203.4178 1909.6174,-209.3915 1911.4329,-202.631"/>
<text text-anchor="middle" x="2142.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node3" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="998.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="998.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M999.2397,-347.7427C999.1689,-337.6476 997.8828,-325.1346 993.0923,-315 990.9841,-310.54 988.084,-306.3136 984.8375,-302.4309"/>
<polygon fill="#000000" stroke="#000000" points="987.2302,-299.8662 977.8299,-294.9791 982.1308,-304.6617 987.2302,-299.8662"/>
<text text-anchor="middle" x="1064.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1189.0923" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1189.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1175.0153,-347.9456C1165.1166,-336.5873 1150.862,-322.6734 1135.0923,-315 1086.5985,-291.4034 1067.6641,-309.0271 1015.0923,-297 1010.4545,-295.939 1005.6496,-294.6927 1000.8805,-293.3595"/>
<polygon fill="#000000" stroke="#000000" points="1001.7873,-289.9782 991.207,-290.5323 999.8236,-296.6971 1001.7873,-289.9782"/>
<text text-anchor="middle" x="1228.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node6" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="816.0923" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="816.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M914.4371,-283.7917C876.3305,-289.055 824.6358,-298.9613 812.0923,-315 807.0911,-321.3947 806.1713,-329.7248 807.0558,-337.7929"/>
<polygon fill="#000000" stroke="#000000" points="803.6377,-338.5519 808.97,-347.7071 810.5107,-337.2249 803.6377,-338.5519"/>
<text text-anchor="middle" x="848.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node14" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="909.0923" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="909.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M930.1835,-264.7084C922.2697,-259.0681 914.5467,-251.8045 910.0923,-243 906.5741,-236.0462 905.3565,-227.8467 905.2736,-220.0797"/>
<polygon fill="#000000" stroke="#000000" points="908.7779,-220.0682 905.7543,-209.914 901.7857,-219.7375 908.7779,-220.0682"/>
<text text-anchor="middle" x="946.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M968.506,-261.4313C977.2385,-249.6613 990.4241,-235.0716 1006.0923,-228 1041.0553,-212.2201 1581.5028,-198.2381 1779.8314,-193.614"/>
<polygon fill="#000000" stroke="#000000" points="1779.9456,-197.1124 1789.8617,-193.3813 1779.7832,-190.1143 1779.9456,-197.1124"/>
<text text-anchor="middle" x="1042.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M847.7768,-352.1564C860.9013,-345.9708 876.0687,-338.2237 889.0923,-330 898.1893,-324.2557 899.5336,-321.5193 908.0923,-315 914.0964,-310.4265 920.569,-305.5995 926.78,-301.0174"/>
<polygon fill="#000000" stroke="#000000" points="929.0301,-303.7074 935.0188,-294.9676 924.8869,-298.0652 929.0301,-303.7074"/>
<text text-anchor="middle" x="948.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M780.5562,-353.3938C773.213,-351.2371 765.4674,-349.2818 758.0923,-348 735.3012,-344.0389 358.0921,-346.7071 342.0923,-330 316.5094,-303.2863 369.8497,-316.161 386.0923,-297 404.2189,-275.6165 400.0923,-263.5326 400.0923,-235.5 400.0923,-235.5 400.0923,-235.5 400.0923,-105 400.0923,-40.5038 1426.7324,-21.9931 1660.2299,-18.6172"/>
<polygon fill="#000000" stroke="#000000" points="1660.4781,-22.1141 1670.4273,-18.4721 1660.3785,-15.1148 1660.4781,-22.1141"/>
<text text-anchor="middle" x="440.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2458.0923" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2458.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2413.2283,-267.4599C2404.2573,-265.2439 2394.8883,-262.9944 2386.0923,-261 2314.4325,-244.7521 2296.7599,-238.8871 2224.0923,-228 2120.0588,-212.4137 1998.5968,-202.1305 1923.5056,-196.6847"/>
<polygon fill="#000000" stroke="#000000" points="1923.4489,-193.1718 1913.2243,-195.9484 1922.9487,-200.1539 1923.4489,-193.1718"/>
<text text-anchor="middle" x="2352.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="277.0923" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="277.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M303.3638,-350.2733C324.8137,-338.294 356.3372,-322.6071 386.0923,-315 482.7564,-290.287 779.3432,-282.1911 902.5478,-279.8508"/>
<polygon fill="#000000" stroke="#000000" points="902.9356,-283.3444 912.8693,-279.6606 902.8065,-276.3456 902.9356,-283.3444"/>
<text text-anchor="middle" x="428.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M264.9043,-348.2188C254.4604,-331.2283 241.0923,-304.5001 241.0923,-279 241.0923,-279 241.0923,-279 241.0923,-105 241.0923,-32.1474 1409.9849,-20.0321 1660.2776,-18.273"/>
<polygon fill="#000000" stroke="#000000" points="1660.5122,-21.7715 1670.4881,-18.2034 1660.4645,-14.7717 1660.5122,-21.7715"/>
<text text-anchor="middle" x="283.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M293.9949,-348.85C306.2736,-337.4325 323.8707,-323.0924 342.0923,-315 550.2393,-222.5596 620.5533,-251.4631 847.0923,-228 1028.0282,-209.2601 1580.2743,-197.1759 1779.4788,-193.3284"/>
<polygon fill="#000000" stroke="#000000" points="1779.6145,-196.8265 1789.5455,-193.1352 1779.4801,-189.8278 1779.6145,-196.8265"/>
<text text-anchor="middle" x="537.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- survival -->
<g id="node9" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2582.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2582.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2547.3059,-266.5534C2511.6225,-254.391 2454.253,-236.5035 2403.0923,-228 2312.976,-213.0216 2051.6429,-200.3922 1923.9782,-194.9162"/>
<polygon fill="#000000" stroke="#000000" points="1924.0463,-191.416 1913.9064,-194.4872 1923.7483,-198.4097 1924.0463,-191.416"/>
<text text-anchor="middle" x="2506.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1413.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1413.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1420.4189,-86.9565C1426.0026,-75.6028 1434.832,-61.6898 1447.0923,-54 1481.7209,-32.2804 1595.5026,-23.3227 1660.4915,-19.9068"/>
<polygon fill="#000000" stroke="#000000" points="1660.6715,-23.4022 1670.4833,-19.405 1660.3203,-16.411 1660.6715,-23.4022"/>
<text text-anchor="middle" x="1509.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- family_relationship -->
<g id="node12" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2748.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2748.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2698.6204,-263.3064C2658.9102,-251.4297 2601.4973,-235.8645 2550.0923,-228 2431.2281,-209.8149 2078.0393,-198.2097 1924.6017,-193.896"/>
<polygon fill="#000000" stroke="#000000" points="1924.4404,-190.3902 1914.3467,-193.6102 1924.2453,-197.3875 1924.4404,-190.3902"/>
<text text-anchor="middle" x="2700.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_admin -->
<g id="node13" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1579.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1579.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1574.47,-86.7222C1572.9122,-76.1245 1573.0602,-63.1154 1580.0923,-54 1590.2289,-40.8604 1629.5424,-31.066 1661.7763,-25.0371"/>
<polygon fill="#000000" stroke="#000000" points="1662.7222,-28.4233 1671.9471,-23.2125 1661.4862,-21.5333 1662.7222,-28.4233"/>
<text text-anchor="middle" x="1636.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M885.0893,-201.6832C865.3297,-211.12 842.334,-226.4345 854.0923,-243 860.8559,-252.5289 885.0231,-261.2345 908.2482,-267.6973"/>
<polygon fill="#000000" stroke="#000000" points="907.5261,-271.127 918.0906,-270.3256 909.3322,-264.364 907.5261,-271.127"/>
<text text-anchor="middle" x="878.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge38" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M937.0435,-190.8635C1065.4633,-185.4505 1595.3035,-160.962 1658.0923,-123 1684.9041,-106.7896 1697.2287,-71.4384 1702.7697,-46.237"/>
<polygon fill="#000000" stroke="#000000" points="1706.2592,-46.6303 1704.7515,-36.1433 1699.3904,-45.2816 1706.2592,-46.6303"/>
<text text-anchor="middle" x="1713.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- laboratory_test -->
<g id="node15" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1686.0923" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1686.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1626.164,-353.729C1596.0007,-347.2458 1558.9546,-338.816 1526.0923,-330 1504.5049,-324.2087 1500.1175,-318.8005 1478.0923,-315 1275.158,-279.9829 1218.0608,-331.8177 1015.0923,-297 1010.2797,-296.1744 1005.3103,-295.0585 1000.3981,-293.7842"/>
<polygon fill="#000000" stroke="#000000" points="1001.0387,-290.3286 990.4644,-290.9886 999.1423,-297.0668 1001.0387,-290.3286"/>
<text text-anchor="middle" x="1591.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1724.8226,-349.9862C1738.8796,-343.9684 1754.8114,-336.9078 1769.0923,-330 1781.8012,-323.8526 1783.7851,-319.7148 1797.0923,-315 1837.1869,-300.7943 1860.0603,-326.093 1891.0923,-297 1913.9204,-275.5982 1919.7379,-255.6526 1905.0923,-228 1902.224,-222.5844 1898.1356,-217.8324 1893.4851,-213.7093"/>
<polygon fill="#000000" stroke="#000000" points="1895.3012,-210.6901 1885.244,-207.3578 1891.028,-216.2345 1895.3012,-210.6901"/>
<text text-anchor="middle" x="1978.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- genetic_analysis -->
<g id="node16" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1450.0923" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1450.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1400.084,-351.1538C1380.5819,-345.0452 1358.1384,-337.6198 1338.0923,-330 1322.6536,-324.1316 1320.1398,-318.9075 1304.0923,-315 1179.0524,-284.5533 1141.6703,-320.2376 1015.0923,-297 1010.2897,-296.1183 1005.3266,-294.9666 1000.4182,-293.6713"/>
<polygon fill="#000000" stroke="#000000" points="1001.0645,-290.2165 990.4888,-290.8515 999.1522,-296.9503 1001.0645,-290.2165"/>
<text text-anchor="middle" x="1408.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1523.166,-356.0052C1570.5983,-348.7672 1624.8976,-338.7572 1632.0923,-330 1636.3243,-324.8489 1636.7334,-319.7859 1632.0923,-315 1586.7427,-268.236 1091.4419,-343.764 1046.0923,-297 1034.9536,-285.5139 1035.4638,-272.9597 1046.0923,-261 1094.3009,-206.7533 1590.1017,-195.1234 1779.286,-192.6559"/>
<polygon fill="#000000" stroke="#000000" points="1779.4569,-196.1541 1789.4122,-192.5288 1779.369,-189.1546 1779.4569,-196.1541"/>
<text text-anchor="middle" x="1116.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- medical_history -->
<g id="node17" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1280.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1280.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1301.0293,-261.2934C1316.1333,-249.6207 1337.5745,-235.2042 1359.0923,-228 1434.9267,-202.6103 1661.6438,-195.1086 1779.3561,-192.906"/>
<polygon fill="#000000" stroke="#000000" points="1779.7734,-196.3992 1789.7091,-192.7208 1779.6481,-189.4004 1779.7734,-196.3992"/>
<text text-anchor="middle" x="1427.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- treatment_response -->
<g id="node18" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1488.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1488.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1491.46,-260.9904C1494.5665,-249.651 1500.3887,-235.7412 1511.0923,-228 1532.3922,-212.595 1686.6294,-201.3101 1780.2226,-195.7934"/>
<polygon fill="#000000" stroke="#000000" points="1780.7022,-199.2715 1790.4824,-195.1973 1780.2962,-192.2833 1780.7022,-199.2715"/>
<text text-anchor="middle" x="1594.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- methylation_array_file -->
<g id="node19" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="463.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="463.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M466.7468,-347.8677C470.0476,-336.4764 476.1363,-322.5551 487.0923,-315 520.6083,-291.8879 786.006,-282.9546 902.5411,-280.1222"/>
<polygon fill="#000000" stroke="#000000" points="902.761,-283.618 912.6753,-279.8822 902.5952,-276.62 902.761,-283.618"/>
<text text-anchor="middle" x="578.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- exposure -->
<g id="node20" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1664.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1664.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1670.4687,-260.8287C1675.2835,-249.7192 1682.9823,-236.1268 1694.0923,-228 1708.8807,-217.1825 1749.5236,-208.0532 1785.8828,-201.6947"/>
<polygon fill="#000000" stroke="#000000" points="1786.727,-205.1015 1795.9993,-199.9756 1785.5543,-198.2004 1786.727,-205.1015"/>
<text text-anchor="middle" x="1737.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- consent_group -->
<g id="node21" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1852.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1852.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge31" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1823.7906,-88.019C1799.5676,-73.4852 1764.7003,-52.5648 1739.3909,-37.3792"/>
<polygon fill="#000000" stroke="#000000" points="1740.912,-34.2102 1730.5363,-32.0664 1737.3105,-40.2127 1740.912,-34.2102"/>
<text text-anchor="middle" x="1852.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1809.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1809.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1793.0625,-261.0004C1786.1569,-250.9859 1780.9238,-238.4677 1787.0923,-228 1790.9645,-221.429 1796.5152,-215.9729 1802.7626,-211.4673"/>
<polygon fill="#000000" stroke="#000000" points="1805.0189,-214.183 1811.6214,-205.897 1801.2928,-208.2572 1805.0189,-214.183"/>
<text text-anchor="middle" x="1846.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1852.0923,-173.9735C1852.0923,-162.1918 1852.0923,-146.5607 1852.0923,-133.1581"/>
<polygon fill="#000000" stroke="#000000" points="1855.5924,-133.0033 1852.0923,-123.0034 1848.5924,-133.0034 1855.5924,-133.0033"/>
<text text-anchor="middle" x="1902.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_measure_file -->
<g id="node24" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2210.0923" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2210.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2116.3918,-356.8823C2086.2841,-353.9918 2052.7842,-350.8167 2022.0923,-348 1931.0134,-339.6414 1903.5373,-359.8746 1817.0923,-330 1805.5576,-326.0137 1805.7494,-318.6124 1794.0923,-315 1711.3934,-289.3727 1100.5372,-310.9654 1015.0923,-297 1010.0832,-296.1813 1004.907,-295.034 999.8036,-293.7106"/>
<polygon fill="#000000" stroke="#000000" points="1000.717,-290.3317 990.1425,-290.9887 998.8187,-297.0694 1000.717,-290.3317"/>
<text text-anchor="middle" x="1903.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2318.2302,-364.2909C2520.7787,-359.9621 2940.9825,-345.2114 2985.0923,-297 2995.8927,-285.1953 2995.2065,-273.3976 2985.0923,-261 2944.6435,-211.4196 1974.0406,-59.1534 1752.0337,-24.8936"/>
<polygon fill="#000000" stroke="#000000" points="1752.451,-21.4167 1742.0345,-23.3523 1751.3845,-28.335 1752.451,-21.4167"/>
<text text-anchor="middle" x="2897.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2211.8342,-347.6217C2212.9653,-324.1583 2211.0536,-283.8697 2188.0923,-261 2151.4636,-224.5174 2009.9637,-205.7824 1922.6938,-197.5028"/>
<polygon fill="#000000" stroke="#000000" points="1922.8727,-194.0045 1912.5927,-196.5681 1922.2276,-200.9747 1922.8727,-194.0045"/>
<text text-anchor="middle" x="2294.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- publication -->
<g id="node25" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2939.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2939.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2919.7911,-87.7743C2905.1072,-75.8406 2883.7891,-60.9042 2862.0923,-54 2808.5126,-36.9504 1962.7933,-22.1508 1753.609,-18.7386"/>
<polygon fill="#000000" stroke="#000000" points="1753.6213,-15.2384 1743.5658,-18.5756 1753.5077,-22.2375 1753.6213,-15.2384"/>
<text text-anchor="middle" x="2942.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2884.0923" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2884.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2820.3767,-361.5255C2673.7611,-351.4141 2301.1111,-326.7687 1989.0923,-315 1880.9285,-310.9203 1121.9556,-314.2126 1015.0923,-297 1010.0813,-296.1929 1004.9039,-295.0528 999.7999,-293.7335"/>
<polygon fill="#000000" stroke="#000000" points="1000.7123,-290.3544 990.1381,-291.016 998.8169,-297.0929 1000.7123,-290.3544"/>
<text text-anchor="middle" x="2362.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2946.1882,-359.7751C2995.4556,-350.9986 3056.0923,-329.8649 3056.0923,-279 3056.0923,-279 3056.0923,-279 3056.0923,-105 3056.0923,-70.339 3029.4033,-66.5452 2997.0923,-54 2938.113,-31.1004 1978.6222,-20.582 1753.9119,-18.4259"/>
<polygon fill="#000000" stroke="#000000" points="1753.8062,-14.9249 1743.7733,-18.3296 1753.7396,-21.9246 1753.8062,-14.9249"/>
<text text-anchor="middle" x="3109.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2884.0252,-347.9057C2883.0083,-325.1149 2878.0437,-285.9269 2857.0923,-261 2834.1828,-233.7436 2818.7473,-236.1722 2784.0923,-228 2701.5133,-208.5266 2129.4599,-196.8093 1924.746,-193.2006"/>
<polygon fill="#000000" stroke="#000000" points="1924.7561,-189.7004 1914.6963,-193.0248 1924.6335,-196.6993 1924.7561,-189.7004"/>
<text text-anchor="middle" x="2928.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- pathology_file -->
<g id="node27" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="673.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="673.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M670.9508,-348.0022C670.7022,-336.9619 672.4909,-323.3815 681.0923,-315 696.6896,-299.8014 827.1815,-288.1565 903.02,-282.597"/>
<polygon fill="#000000" stroke="#000000" points="903.6182,-286.0631 913.3407,-281.8532 903.115,-279.0812 903.6182,-286.0631"/>
<text text-anchor="middle" x="742.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_arm -->
<g id="node28" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3144.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3144.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3125.671,-87.7495C3111.6227,-75.8036 3091.1586,-60.8626 3070.0923,-54 3006.2939,-33.217 1986.0544,-21.0061 1753.8635,-18.4881"/>
<polygon fill="#000000" stroke="#000000" points="1753.7596,-14.9869 1743.7225,-18.3789 1753.6841,-21.9865 1753.7596,-14.9869"/>
<text text-anchor="middle" x="3146.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
