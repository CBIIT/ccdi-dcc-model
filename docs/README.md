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
<svg width="3505pt" height="392pt"
 viewBox="0.00 0.00 3505.14 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3501.1355,-388 3501.1355,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2706.0433" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2706.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node19" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1848.0433" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1848.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2661.7333,-262.618C2627.6132,-250.783 2579.0027,-235.5957 2535.0433,-228 2418.7019,-207.8974 2072.3071,-197.3733 1920.587,-193.6228"/>
<polygon fill="#000000" stroke="#000000" points="1920.5248,-190.1203 1910.4423,-193.3749 1920.3538,-197.1182 1920.5248,-190.1203"/>
<text text-anchor="middle" x="2680.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- publication -->
<g id="node2" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="96.0433" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="96.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2860.0433" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2860.0433" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge14" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M90.7722,-86.99C88.7452,-75.9448 88.6246,-62.3635 97.0433,-54 122.161,-29.0469 2452.4817,-19.4953 2813.3323,-18.1654"/>
<polygon fill="#000000" stroke="#000000" points="2813.4425,-21.6651 2823.4296,-18.1284 2813.4168,-14.6651 2813.4425,-21.6651"/>
<text text-anchor="middle" x="148.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1326.0433" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1326.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1318.9894,-260.7179C1316.1002,-249.849 1315.0528,-236.5571 1323.0433,-228 1338.2508,-211.714 1635.256,-199.3407 1775.6655,-194.3766"/>
<polygon fill="#000000" stroke="#000000" points="1776.0344,-197.8659 1785.9057,-194.0179 1775.7893,-190.8702 1776.0344,-197.8659"/>
<text text-anchor="middle" x="1370.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1278.0433" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1278.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1324.9067,-356.7411C1355.9753,-349.8761 1393.2846,-340.01 1406.0433,-330 1433.7578,-308.2562 1417.6319,-283.1247 1445.0433,-261 1494.8405,-220.8068 1674.4093,-203.0026 1776.2433,-195.988"/>
<polygon fill="#000000" stroke="#000000" points="1776.7087,-199.4647 1786.4519,-195.303 1776.24,-192.4804 1776.7087,-199.4647"/>
<text text-anchor="middle" x="1489.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node27" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="818.0433" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="818.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1229.4432,-357.5736C1201.8958,-351.8049 1167.2127,-342.8446 1138.0433,-330 1126.8741,-325.0817 1126.5651,-319.0231 1115.0433,-315 1034.5443,-286.8924 1008.5768,-308.145 924.0433,-297 905.7887,-294.5933 885.8641,-291.3689 868.2667,-288.3142"/>
<polygon fill="#000000" stroke="#000000" points="868.6601,-284.8297 858.2047,-286.5427 867.4463,-291.7237 868.6601,-284.8297"/>
<text text-anchor="middle" x="1182.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- cell_line -->
<g id="node6" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="246.0433" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="246.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge33" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M235.0547,-348.4091C225.455,-331.3379 213.0433,-304.3621 213.0433,-279 213.0433,-279 213.0433,-279 213.0433,-105 213.0433,-37.2187 2460.0359,-20.485 2813.4953,-18.272"/>
<polygon fill="#000000" stroke="#000000" points="2813.6536,-21.7712 2823.6318,-18.2093 2813.6103,-14.7713 2813.6536,-21.7712"/>
<text text-anchor="middle" x="253.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M274.7518,-351.1945C299.3523,-339.2475 336.0883,-323.1366 370.0433,-315 443.4041,-297.4207 661.5256,-285.8593 763.8775,-281.2539"/>
<polygon fill="#000000" stroke="#000000" points="764.1679,-284.7445 774.0026,-280.804 763.8571,-277.7514 764.1679,-284.7445"/>
<text text-anchor="middle" x="410.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- pdx -->
<g id="node7" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="790.0433" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="790.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge23" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M818.1276,-189.6393C1041.6315,-170.852 2530.981,-45.6603 2813.7415,-21.892"/>
<polygon fill="#000000" stroke="#000000" points="2814.3737,-25.3513 2824.0454,-21.0259 2813.7873,-18.3759 2814.3737,-25.3513"/>
<text text-anchor="middle" x="2054.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M763.9511,-199.1913C738.6269,-207.5359 705.9294,-222.7792 720.0433,-243 726.2958,-251.9579 748.3873,-260.4614 770.0159,-266.9524"/>
<polygon fill="#000000" stroke="#000000" points="769.2842,-270.3839 779.8622,-269.7876 771.2211,-263.6572 769.2842,-270.3839"/>
<text text-anchor="middle" x="744.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- exposure -->
<g id="node8" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1722.0433" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1722.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1729.7917,-260.8624C1735.2104,-250.0479 1743.3851,-236.7624 1754.0433,-228 1764.5851,-219.3332 1777.4427,-212.604 1790.2222,-207.4368"/>
<polygon fill="#000000" stroke="#000000" points="1791.8111,-210.5787 1799.9399,-203.7836 1789.3479,-204.0264 1791.8111,-210.5787"/>
<text text-anchor="middle" x="1797.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- consent_group -->
<g id="node9" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2207.0433" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2207.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge30" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2275.6915,-95.8539C2409.534,-78.0219 2702.0941,-39.0438 2814.6572,-24.0468"/>
<polygon fill="#000000" stroke="#000000" points="2815.2127,-27.5038 2824.6628,-22.7138 2814.2882,-20.5652 2815.2127,-27.5038"/>
<text text-anchor="middle" x="2635.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="2732.0433" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2732.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge31" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2727.421,-86.7222C2725.8632,-76.1245 2726.0111,-63.1154 2733.0433,-54 2743.1798,-40.8604 2782.4933,-31.066 2814.7272,-25.0371"/>
<polygon fill="#000000" stroke="#000000" points="2815.6732,-28.4233 2824.8981,-23.2125 2814.4371,-21.5333 2815.6732,-28.4233"/>
<text text-anchor="middle" x="2789.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- medical_history -->
<g id="node11" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1878.0433" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1878.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1859.7839,-261.0395C1855.4495,-255.6773 1851.4026,-249.4863 1849.0433,-243 1846.4919,-235.9858 1845.5121,-228.0622 1845.3456,-220.5884"/>
<polygon fill="#000000" stroke="#000000" points="1848.8475,-220.5398 1845.5727,-210.4638 1841.8492,-220.3827 1848.8475,-220.5398"/>
<text text-anchor="middle" x="1917.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- clinical_measure_file -->
<g id="node12" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2889.0433" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2889.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2964.0479,-352.9014C3032.4919,-338.752 3123.0433,-313.511 3123.0433,-279 3123.0433,-279 3123.0433,-279 3123.0433,-105 3123.0433,-77.2551 3110.5986,-68.6602 3087.0433,-54 3057.7026,-35.7392 2964.1391,-25.7081 2906.6968,-21.1302"/>
<polygon fill="#000000" stroke="#000000" points="2906.6544,-17.6166 2896.4151,-20.3381 2906.1167,-24.5959 2906.6544,-17.6166"/>
<text text-anchor="middle" x="3209.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2880.9855,-347.8179C2865.0142,-314.6394 2825.7352,-246.0288 2767.0433,-228 2687.2024,-203.4748 2123.9535,-194.9909 1920.8424,-192.7098"/>
<polygon fill="#000000" stroke="#000000" points="1920.6171,-189.2072 1910.579,-192.5964 1920.5397,-196.2068 1920.6171,-189.2072"/>
<text text-anchor="middle" x="2936.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2784.6825,-360.8746C2576.9208,-350.8204 2096.7881,-328.3323 1693.0433,-315 1351.3581,-303.717 1264.3469,-329.7028 924.0433,-297 905.5599,-295.2238 885.4356,-292.11 867.7366,-288.9665"/>
<polygon fill="#000000" stroke="#000000" points="868.0925,-285.4737 857.6267,-287.122 866.8361,-292.3601 868.0925,-285.4737"/>
<text text-anchor="middle" x="2173.0433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- generic_file -->
<g id="node13" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1902.0433" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1902.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge19" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1964.2118,-360.2081C2004.3792,-356.535 2057.7832,-351.7805 2105.0433,-348 2184.4359,-341.6491 2761.7562,-351.2785 2820.0433,-297 2890.1867,-231.6804 2876.4086,-102.9804 2866.0677,-46.1305"/>
<polygon fill="#000000" stroke="#000000" points="2869.4588,-45.2301 2864.1345,-36.0703 2862.5845,-46.5511 2869.4588,-45.2301"/>
<text text-anchor="middle" x="2925.0433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1902.0851,-347.8028C1901.0597,-336.5356 1897.6943,-322.7783 1888.0433,-315 1859.1066,-291.6783 1579.606,-323.9774 1554.0433,-297 1485.336,-224.4903 1667.9433,-201.9629 1775.6141,-195.0321"/>
<polygon fill="#000000" stroke="#000000" points="1776.0217,-198.5138 1785.789,-194.4089 1775.5937,-191.5269 1776.0217,-198.5138"/>
<text text-anchor="middle" x="1607.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1836.2551,-364.5995C1752.5773,-361.8608 1603.9365,-353.7837 1479.0433,-330 1456.2521,-325.6598 1451.9344,-318.7774 1429.0433,-315 1207.453,-278.434 1147.4648,-319.8498 924.0433,-297 905.5711,-295.1108 885.4493,-291.9719 867.7492,-288.8398"/>
<polygon fill="#000000" stroke="#000000" points="868.1023,-285.3468 857.6382,-287.006 866.853,-292.2345 868.1023,-285.3468"/>
<text text-anchor="middle" x="1532.0433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3035.0433" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3035.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3013.6431,-88.0199C2999.3484,-77.2522 2979.7952,-63.5942 2961.0433,-54 2942.2196,-44.3691 2920.2165,-36.1974 2901.561,-30.086"/>
<polygon fill="#000000" stroke="#000000" points="2902.4556,-26.6977 2891.8649,-26.9941 2900.3288,-33.3668 2902.4556,-26.6977"/>
<text text-anchor="middle" x="3034.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- synonym -->
<g id="node15" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2166.0433" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2166.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2218.1965,-364.1536C2356.0456,-359.1295 2727.8368,-344.6073 2850.0433,-330 2929.0661,-320.5544 2975.2172,-358.2416 3026.0433,-297 3062.742,-252.7807 2935.6604,-101.9945 2882.4238,-42.4615"/>
<polygon fill="#000000" stroke="#000000" points="2884.7181,-39.7787 2875.4267,-34.6874 2879.5151,-44.4616 2884.7181,-39.7787"/>
<text text-anchor="middle" x="3050.5433" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2165.6198,-347.6919C2164.0676,-324.3044 2157.8343,-284.0978 2134.0433,-261 2103.3737,-231.2242 1990.55,-210.8883 1916.1105,-200.3769"/>
<polygon fill="#000000" stroke="#000000" points="1916.2597,-196.8642 1905.874,-198.9589 1915.2992,-203.798 1916.2597,-196.8642"/>
<text text-anchor="middle" x="2197.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2116.354,-360.6352C2078.2677,-356.6766 2024.3846,-351.4072 1977.0433,-348 1895.1576,-342.1066 1686.1438,-355.3041 1608.0433,-330 1596.4334,-326.2385 1596.6929,-318.6364 1585.0433,-315 1514.909,-293.1078 997.1644,-304.1679 924.0433,-297 905.5633,-295.1884 885.4398,-292.0669 867.7405,-288.9269"/>
<polygon fill="#000000" stroke="#000000" points="868.0955,-285.434 857.6302,-287.0857 866.8413,-292.3208 868.0955,-285.434"/>
<text text-anchor="middle" x="1650.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node16" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2369.0433" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2369.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2319.3934,-263.3285C2281.5562,-251.9428 2227.9741,-237.0089 2180.0433,-228 2091.0249,-211.2685 1987.0097,-201.551 1919.4554,-196.5179"/>
<polygon fill="#000000" stroke="#000000" points="1919.5754,-193.0174 1909.3469,-195.7795 1919.0653,-199.9988 1919.5754,-193.0174"/>
<text text-anchor="middle" x="2321.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- methylation_array_file -->
<g id="node17" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="429.0433" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="429.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M439.6917,-347.7421C447.4104,-336.2979 458.9474,-322.3646 473.0433,-315 522.2317,-289.3006 679.4251,-281.9459 763.6055,-279.8422"/>
<polygon fill="#000000" stroke="#000000" points="763.829,-283.338 773.7445,-279.6054 763.6655,-276.3399 763.829,-283.338"/>
<text text-anchor="middle" x="564.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- survival -->
<g id="node18" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2535.0433" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2535.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2505.9193,-264.5553C2480.0983,-252.4902 2441.0125,-236.0132 2405.0433,-228 2314.7946,-207.8944 2049.5832,-197.7594 1920.4058,-193.9023"/>
<polygon fill="#000000" stroke="#000000" points="1920.315,-190.3982 1910.2164,-193.6026 1920.1092,-197.3951 1920.315,-190.3982"/>
<text text-anchor="middle" x="2491.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge16" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1896.0871,-180.3571C1959.5513,-164.9772 2071.5471,-137.8361 2142.3927,-120.6674"/>
<polygon fill="#000000" stroke="#000000" points="2143.6417,-123.9661 2152.536,-118.2093 2141.993,-117.163 2143.6417,-123.9661"/>
<text text-anchor="middle" x="2098.5433" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="843.0433" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="843.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M828.1562,-347.9864C824.4746,-342.5325 821.0207,-336.3075 819.0433,-330 816.8104,-322.878 815.9394,-314.9176 815.7755,-307.4429"/>
<polygon fill="#000000" stroke="#000000" points="819.2768,-307.3951 815.9465,-297.3373 812.2778,-307.2766 819.2768,-307.3951"/>
<text text-anchor="middle" x="885.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="76.0433" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="76.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M84.918,-348.0393C91.7119,-336.4111 102.2585,-322.1496 116.0433,-315 172.8971,-285.5121 608.5618,-280.1779 763.5374,-279.2131"/>
<polygon fill="#000000" stroke="#000000" points="763.7882,-282.7118 773.7675,-279.1532 763.7472,-275.7119 763.7882,-282.7118"/>
<text text-anchor="middle" x="177.0433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- laboratory_test -->
<g id="node22" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1460.0433" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1460.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1505.8987,-351.0735C1523.1,-345.0636 1542.6794,-337.7268 1560.0433,-330 1572.9415,-324.2604 1574.4345,-318.7564 1588.0433,-315 1629.217,-303.6348 1939.1196,-324.2117 1972.0433,-297 1996.0971,-277.1193 2004.1002,-252.7115 1985.0433,-228 1975.9695,-216.2338 1944.9365,-207.5543 1914.697,-201.6692"/>
<polygon fill="#000000" stroke="#000000" points="1914.9755,-198.1613 1904.5051,-199.7801 1913.6997,-205.0441 1914.9755,-198.1613"/>
<text text-anchor="middle" x="2060.5433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1403.046,-353.0361C1339.7981,-338.7282 1244.3224,-317.3894 1227.0433,-315 1093.4108,-296.521 1058.0752,-312.3151 924.0433,-297 905.6723,-294.9008 885.6473,-291.7311 867.999,-288.6336"/>
<polygon fill="#000000" stroke="#000000" points="868.3736,-285.1451 857.9131,-286.8268 867.1392,-292.0354 868.3736,-285.1451"/>
<text text-anchor="middle" x="1359.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- cytogenomic_file -->
<g id="node23" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="652.0433" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="652.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M654.1504,-347.5453C656.3511,-336.6114 660.8494,-323.3118 670.0433,-315 684.1631,-302.2347 729.2073,-292.4418 765.929,-286.3152"/>
<polygon fill="#000000" stroke="#000000" points="766.7182,-289.7332 776.033,-284.685 765.6032,-282.8226 766.7182,-289.7332"/>
<text text-anchor="middle" x="741.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1177.0433" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1177.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1178.0968,-260.9645C1179.7868,-249.6142 1183.9541,-235.702 1194.0433,-228 1216.8405,-210.5968 1609.989,-198.263 1775.5157,-193.8188"/>
<polygon fill="#000000" stroke="#000000" points="1775.7046,-197.3151 1785.6078,-193.5501 1775.5182,-190.3176 1775.7046,-197.3151"/>
<text text-anchor="middle" x="1253.0433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_funding -->
<g id="node25" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3228.0433" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3228.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge29" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3203.3677,-87.7417C3185.7134,-76.2745 3160.9388,-61.9195 3137.0433,-54 3095.3147,-40.1701 2973.76,-27.8731 2906.3751,-21.8741"/>
<polygon fill="#000000" stroke="#000000" points="2906.3139,-18.3554 2896.0458,-20.9662 2905.7009,-25.3285 2906.3139,-18.3554"/>
<text text-anchor="middle" x="3233.0433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- study_personnel -->
<g id="node26" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="3410.0433" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="3410.0433" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3380.481,-87.9598C3358.7046,-76.2808 3327.9695,-61.5792 3299.0433,-54 3225.8856,-34.8314 3003.712,-23.7928 2906.4623,-19.7641"/>
<polygon fill="#000000" stroke="#000000" points="2906.4769,-16.2619 2896.3426,-19.3516 2906.1917,-23.2561 2906.4769,-16.2619"/>
<text text-anchor="middle" x="3409.5433" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge35" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M773.5574,-280.1982C642.5783,-283.9363 266.3352,-296.2659 248.0433,-315 242.1459,-321.0399 240.3608,-329.647 240.444,-338.0744"/>
<polygon fill="#000000" stroke="#000000" points="236.9611,-338.424 241.3212,-348.08 243.9344,-337.8125 236.9611,-338.424"/>
<text text-anchor="middle" x="284.5433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge36" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M801.8786,-261.9738C797.5279,-256.3569 793.3829,-249.7961 791.0433,-243 788.6137,-235.9427 787.6755,-228.0044 787.51,-220.5302"/>
<polygon fill="#000000" stroke="#000000" points="791.0116,-220.4823 787.7156,-210.4132 784.013,-220.34 791.0116,-220.4823"/>
<text text-anchor="middle" x="827.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M838.5436,-262.885C856.8236,-248.677 881.5253,-229.9331 887.0433,-228 969.8939,-198.9743 1565.2759,-193.3427 1775.0951,-192.2571"/>
<polygon fill="#000000" stroke="#000000" points="1775.4051,-195.7557 1785.3876,-192.2059 1775.3702,-188.7558 1775.4051,-195.7557"/>
<text text-anchor="middle" x="923.5433" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- genetic_analysis -->
<g id="node28" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1061.0433" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1061.0433" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1136.9029,-356.9274C1161.5059,-354.0245 1188.9276,-350.8309 1214.0433,-348 1251.1344,-343.8193 1356.104,-357.7717 1381.0433,-330 1385.4976,-325.0398 1385.6567,-319.8125 1381.0433,-315 1348.2584,-280.8006 987.8281,-331.1994 955.0433,-297 943.9709,-285.45 944.5865,-273.1102 955.0433,-261 1020.8099,-184.8346 1078.916,-238.0477 1179.0433,-228 1395.4553,-206.2832 1652.6564,-197.0845 1775.5928,-193.7033"/>
<polygon fill="#000000" stroke="#000000" points="1775.737,-197.2008 1785.6387,-193.4318 1775.5478,-190.2033 1775.737,-197.2008"/>
<text text-anchor="middle" x="1025.0433" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1018.7833,-350.0945C1004.6241,-344.2983 988.917,-337.3498 975.0433,-330 964.259,-324.2869 963.1857,-319.9783 952.0433,-315 925.4432,-303.1154 894.0681,-294.4251 868.367,-288.5635"/>
<polygon fill="#000000" stroke="#000000" points="868.9755,-285.1137 858.4564,-286.378 867.468,-291.9495 868.9755,-285.1137"/>
<text text-anchor="middle" x="1045.0433" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
</g>
</svg>
</div>
