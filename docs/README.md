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
<svg width="3014pt" height="479pt"
 viewBox="0.00 0.00 3014.34 479.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 475)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-475 3010.3431,-475 3010.3431,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="151" cy="-453" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="151" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1840" cy="-366" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1840" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M202.026,-449.3846C329.5826,-440.4328 672.6505,-416.8857 959,-402 1271.5088,-385.7544 1646.694,-372.4985 1785.1848,-367.8167"/>
<polygon fill="#000000" stroke="#000000" points="1785.6451,-371.3032 1795.5215,-367.4683 1785.4093,-364.3072 1785.6451,-371.3032"/>
<text text-anchor="middle" x="1001.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node14" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1456" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1456" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M146.4259,-435.0562C137.9865,-397.3091 124.6968,-309.2088 170,-261 204.225,-224.5799 233.6591,-259.0192 281,-243 294.3728,-238.4749 295.3626,-231.6511 309,-228 412.1722,-200.378 1147.2927,-193.7715 1383.2741,-192.3544"/>
<polygon fill="#000000" stroke="#000000" points="1383.4846,-195.8533 1393.4639,-192.2946 1383.4435,-188.8534 1383.4846,-195.8533"/>
<text text-anchor="middle" x="185.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node26" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2254" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2254" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge23" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M103.2227,-445.8949C58.9844,-436.2906 0,-414.4083 0,-366 0,-366 0,-366 0,-105 0,-47.7348 1882.7185,-22.4738 2206.7874,-18.5498"/>
<polygon fill="#000000" stroke="#000000" points="2207.2643,-22.0444 2217.2215,-18.4244 2207.1801,-15.0449 2207.2643,-22.0444"/>
<text text-anchor="middle" x="42.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2036" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2036" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1987.8995,-262.9185C1951.5324,-251.3994 1900.1519,-236.4798 1854,-228 1741.5121,-207.3319 1608.861,-198.3541 1528.6585,-194.5811"/>
<polygon fill="#000000" stroke="#000000" points="1528.3284,-191.0626 1518.1795,-194.1038 1528.0098,-198.0553 1528.3284,-191.0626"/>
<text text-anchor="middle" x="1997" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- cell_line -->
<g id="node10" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2208" cy="-279" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2208" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1879.89,-358.2105C1939.1585,-346.3915 2053.8227,-322.5817 2150,-297 2153.6266,-296.0354 2157.366,-294.991 2161.1167,-293.9078"/>
<polygon fill="#000000" stroke="#000000" points="2162.4088,-297.1753 2171.0016,-290.9774 2160.4192,-290.464 2162.4088,-297.1753"/>
<text text-anchor="middle" x="2109.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1839.6515,-347.8583C1837.9025,-316.0306 1828.9711,-251.3005 1786,-228 1743.0194,-204.6943 1612.0487,-196.4677 1528.6057,-193.5696"/>
<polygon fill="#000000" stroke="#000000" points="1528.5325,-190.0654 1518.4226,-193.2341 1528.3019,-197.0616 1528.5325,-190.0654"/>
<text text-anchor="middle" x="1867.5" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node24" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2359" cy="-279" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2359" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1884.3425,-364.9189C2017.7655,-361.4523 2407.4952,-349.6764 2426,-330 2430.5672,-325.1436 2429.4211,-320.7219 2426,-315 2421.9035,-308.1486 2406.7316,-299.7388 2391.8597,-292.7709"/>
<polygon fill="#000000" stroke="#000000" points="2393.294,-289.5783 2382.7402,-288.6456 2390.4088,-295.9561 2393.294,-289.5783"/>
<text text-anchor="middle" x="2465.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pathology_file -->
<g id="node4" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1782" cy="-453" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1782" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1778.3234,-434.905C1777.1812,-424.6233 1777.4312,-411.8733 1783,-402 1787.0025,-394.9036 1793.0427,-389.0048 1799.7165,-384.1768"/>
<polygon fill="#000000" stroke="#000000" points="1801.8622,-386.9593 1808.4032,-378.6246 1798.0923,-381.0611 1801.8622,-386.9593"/>
<text text-anchor="middle" x="1844" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node5" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1572" cy="-453" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1572" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1574.068,-434.9578C1576.3317,-423.7542 1581.0725,-410.0096 1591,-402 1620.0618,-378.5527 1721.3783,-370.367 1785.4682,-367.5161"/>
<polygon fill="#000000" stroke="#000000" points="1785.9603,-370.9989 1795.8069,-367.0879 1785.6706,-364.0049 1785.9603,-370.9989"/>
<text text-anchor="middle" x="1682.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_other -->
<g id="node6" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2530" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2530" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2502.9718,-261.8124C2482.6622,-249.8977 2453.6925,-234.9682 2426,-228 2339.9265,-206.3414 1738.5946,-195.9499 1528.359,-192.9491"/>
<polygon fill="#000000" stroke="#000000" points="1528.397,-189.4494 1518.3485,-192.8076 1528.298,-196.4487 1528.397,-189.4494"/>
<text text-anchor="middle" x="2533.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- exposure -->
<g id="node7" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="232" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="232" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M262.5254,-264.2183C292.4106,-249.8703 334.6401,-229.9708 343,-228 443.5382,-204.2991 1151.8998,-195.0808 1383.1634,-192.6822"/>
<polygon fill="#000000" stroke="#000000" points="1383.5209,-196.1788 1393.4845,-192.5764 1383.4491,-189.1792 1383.5209,-196.1788"/>
<text text-anchor="middle" x="386.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- clinical_measure_file -->
<g id="node8" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="924" cy="-453" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="924" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M975.4891,-437.0913C1019.7297,-423.6827 1080.19,-406.0495 1105,-402 1235.9832,-380.6208 1638.4734,-370.2317 1785.5,-367.0756"/>
<polygon fill="#000000" stroke="#000000" points="1785.7136,-370.572 1795.6372,-366.8608 1785.5653,-363.5735 1785.7136,-370.572"/>
<text text-anchor="middle" x="1191" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M927.6695,-434.8567C936.2259,-397.1184 961.0102,-309.6403 1015,-261 1067.9702,-213.2782 1272.6286,-198.5109 1383.5506,-193.9792"/>
<polygon fill="#000000" stroke="#000000" points="1383.802,-197.4722 1393.6576,-193.584 1383.5284,-190.4775 1383.802,-197.4722"/>
<text text-anchor="middle" x="1058" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M853.9406,-439.2467C669.6179,-402.9659 184.292,-306.775 170,-297 141.6172,-277.5877 112.0423,-253.6001 135,-228 278.4574,-68.0307 1909.0637,-25.4174 2207.3104,-18.9403"/>
<polygon fill="#000000" stroke="#000000" points="2207.4306,-22.4387 2217.3532,-18.725 2207.2805,-15.4403 2207.4306,-22.4387"/>
<text text-anchor="middle" x="221" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_admin -->
<g id="node9" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1680" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1680" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1702.3359,-87.8132C1718.9326,-76.0633 1742.6501,-61.3371 1766,-54 1847.473,-28.3992 2101.9749,-20.8056 2207.4689,-18.7253"/>
<polygon fill="#000000" stroke="#000000" points="2207.5682,-22.2241 2217.5001,-18.5353 2207.4356,-15.2254 2207.5682,-22.2241"/>
<text text-anchor="middle" x="1822.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- cell_line&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>cell_line&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2179.3383,-263.994C2154.7664,-251.9248 2118.046,-235.7469 2084,-228 1980.3096,-204.4062 1670.937,-195.8757 1528.836,-193.1444"/>
<polygon fill="#000000" stroke="#000000" points="1528.5519,-189.6385 1518.4879,-192.9501 1528.4204,-196.6373 1528.5519,-189.6385"/>
<text text-anchor="middle" x="2169.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge43" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2218.6734,-261.2954C2239.1598,-226.1588 2283.3494,-144.4788 2299,-69 2300.3535,-62.4722 2301.8879,-60.0087 2299,-54 2296.0299,-47.8202 2291.4251,-42.3692 2286.2737,-37.6997"/>
<polygon fill="#000000" stroke="#000000" points="2288.4498,-34.9583 2278.4619,-31.4235 2284.0655,-40.4153 2288.4498,-34.9583"/>
<text text-anchor="middle" x="2316.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- treatment_surgery -->
<g id="node11" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="402" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="402" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M415.1671,-261.1158C424.9665,-249.3616 439.4656,-234.9208 456,-228 498.5919,-210.1724 1160.2736,-197.1246 1383.273,-193.2149"/>
<polygon fill="#000000" stroke="#000000" points="1383.6188,-196.7095 1393.5563,-193.0356 1383.4967,-189.7105 1383.6188,-196.7095"/>
<text text-anchor="middle" x="534.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2031" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2031" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2032.8258,-86.8317C2034.9168,-75.7233 2039.3985,-62.1311 2049,-54 2072.3312,-34.2416 2154.3898,-24.8746 2207.3426,-20.7944"/>
<polygon fill="#000000" stroke="#000000" points="2207.8022,-24.2702 2217.5191,-20.0474 2207.2897,-17.289 2207.8022,-24.2702"/>
<text text-anchor="middle" x="2118.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="567" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="567" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M586.5522,-262.3592C601.898,-250.3888 624.3834,-235.1452 647,-228 716.0341,-206.1903 1197.7246,-196.1709 1383.3216,-193.0881"/>
<polygon fill="#000000" stroke="#000000" points="1383.5845,-196.5844 1393.5257,-192.9207 1383.4696,-189.5853 1383.5845,-196.5844"/>
<text text-anchor="middle" x="686.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- consent_group -->
<g id="node29" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1847" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1847" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1505.5204,-180.9814C1575.1393,-165.4907 1702.1395,-137.2324 1780.1007,-119.8855"/>
<polygon fill="#000000" stroke="#000000" points="1781.2944,-123.2056 1790.2954,-117.6171 1779.774,-116.3727 1781.2944,-123.2056"/>
<text text-anchor="middle" x="1724.5" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="2199" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="2199" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge20" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2193.8939,-86.9499C2192.0251,-76.6832 2191.5251,-63.9332 2197,-54 2201.3856,-46.0431 2208.3524,-39.6017 2215.9317,-34.4882"/>
<polygon fill="#000000" stroke="#000000" points="2218.197,-37.2125 2224.9927,-29.0842 2214.6114,-31.2005 2218.197,-37.2125"/>
<text text-anchor="middle" x="2248" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- genetic_analysis -->
<g id="node16" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2366" cy="-453" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2366" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2310.2376,-439.0945C2290.7392,-433.3511 2268.9878,-425.9255 2250,-417 2238.9553,-411.8083 2238.5243,-406.0161 2227,-402 2167.0259,-381.0996 1985.9973,-371.471 1894.3737,-367.8383"/>
<polygon fill="#000000" stroke="#000000" points="1894.3185,-364.3336 1884.1907,-367.4447 1894.048,-371.3284 1894.3185,-364.3336"/>
<text text-anchor="middle" x="2320" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2382.7821,-435.3123C2390.0949,-425.3954 2395.8179,-412.8709 2390,-402 2362.7791,-351.1372 2314.8267,-377.4385 2282,-330 2264.0867,-304.1132 2284.2036,-286.6835 2266,-261 2250.172,-238.6682 2240.0967,-236.2581 2214,-228 2149.8513,-207.7007 1705.4021,-196.8744 1528.4497,-193.3287"/>
<polygon fill="#000000" stroke="#000000" points="1528.519,-189.8294 1518.4515,-193.1304 1528.3801,-196.8281 1528.519,-189.8294"/>
<text text-anchor="middle" x="2352" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1384" cy="-453" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1384" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1409.6206,-437.0708C1429.8474,-425.3123 1459.1991,-410.0152 1487,-402 1541.6909,-386.2323 1701.3596,-374.4701 1785.9533,-369.1466"/>
<polygon fill="#000000" stroke="#000000" points="1786.3696,-372.6276 1796.1333,-368.5143 1785.9356,-365.6411 1786.3696,-372.6276"/>
<text text-anchor="middle" x="1531.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1341.4345,-441.6184C1319.9706,-434.9296 1297.1898,-426.0334 1291,-417 1287.2317,-411.5005 1287.2866,-407.5367 1291,-402 1359.4992,-299.8676 1473.8606,-395.8625 1547,-297 1565.2866,-272.282 1569.5134,-253.2718 1552,-228 1546.8031,-220.5008 1530.3737,-213.2348 1512.5413,-207.2177"/>
<polygon fill="#000000" stroke="#000000" points="1513.1438,-203.7352 1502.5525,-204.0098 1511.0034,-210.3999 1513.1438,-203.7352"/>
<text text-anchor="middle" x="1573.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="718" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="718" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M721.5902,-260.7731C724.8639,-249.3419 730.9465,-235.4116 742,-228 768.3107,-210.3582 1206.8603,-197.9569 1383.3174,-193.6593"/>
<polygon fill="#000000" stroke="#000000" points="1383.6328,-197.1528 1393.5453,-193.4122 1383.4636,-190.1549 1383.6328,-197.1528"/>
<text text-anchor="middle" x="810" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- generic_file -->
<g id="node19" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2558" cy="-453" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2558" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2512.8605,-439.8888C2490.3122,-433.2301 2462.6495,-424.896 2438,-417 2418.3242,-410.6972 2414.2622,-406.0382 2394,-402 2299.5119,-383.1686 2014.7299,-371.7942 1894.5005,-367.7146"/>
<polygon fill="#000000" stroke="#000000" points="1894.5278,-364.2137 1884.4161,-367.3765 1894.2932,-371.2097 1894.5278,-364.2137"/>
<text text-anchor="middle" x="2491" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2556.6185,-434.5862C2553.3358,-404.666 2542.3618,-345.7506 2506,-315 2480.814,-293.7006 2462.1201,-314.2412 2434,-297 2399.3543,-275.7578 2410.6443,-245.5714 2374,-228 2336.1265,-209.8392 1738.8791,-197.1884 1528.5789,-193.278"/>
<polygon fill="#000000" stroke="#000000" points="1528.625,-189.7784 1518.562,-193.0929 1528.4956,-196.7772 1528.625,-189.7784"/>
<text text-anchor="middle" x="2572" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge36" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2598.4521,-438.8053C2628.7526,-425.293 2665,-401.6735 2665,-366 2665,-366 2665,-366 2665,-105 2665,-68.0312 2407.2033,-35.0499 2299.9529,-22.9284"/>
<polygon fill="#000000" stroke="#000000" points="2300.0817,-19.421 2289.7546,-21.7875 2299.3034,-26.3776 2300.0817,-19.421"/>
<text text-anchor="middle" x="2718" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2401" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2401" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge39" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2378.561,-88.2685C2364.1709,-77.8601 2344.8964,-64.5049 2327,-54 2315.3647,-47.1703 2302.2543,-40.4274 2290.3875,-34.6567"/>
<polygon fill="#000000" stroke="#000000" points="2291.7202,-31.4144 2281.1891,-30.254 2288.6981,-37.7284 2291.7202,-31.4144"/>
<text text-anchor="middle" x="2398.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- radiology_file -->
<g id="node21" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="895" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="895" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M885.4883,-260.766C881.283,-249.9152 878.903,-236.6254 887,-228 903.7525,-210.1541 1234.4062,-198.3915 1383.8092,-193.9673"/>
<polygon fill="#000000" stroke="#000000" points="1383.9215,-197.4656 1393.8146,-193.674 1383.7163,-190.4686 1383.9215,-197.4656"/>
<text text-anchor="middle" x="946" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- laboratory_test -->
<g id="node22" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1230" cy="-453" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1230" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1251.7899,-435.519C1267.7393,-423.7903 1290.448,-409.2139 1313,-402 1399.6951,-374.268 1668.8157,-367.898 1785.3189,-366.4355"/>
<polygon fill="#000000" stroke="#000000" points="1785.4832,-369.9339 1795.4412,-366.316 1785.4005,-362.9344 1785.4832,-369.9339"/>
<text text-anchor="middle" x="1378.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1234.1059,-434.6938C1235.3673,-429.0249 1236.7516,-422.7564 1238,-417 1253.0202,-347.7424 1227.1825,-316.6979 1271,-261 1298.8431,-225.6077 1346.826,-208.3692 1386.9473,-199.9729"/>
<polygon fill="#000000" stroke="#000000" points="1387.8144,-203.3699 1396.9612,-198.0231 1386.4765,-196.4989 1387.8144,-203.3699"/>
<text text-anchor="middle" x="1310.5" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- family_relationship -->
<g id="node23" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1124" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1124" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1107.1504,-260.8576C1099.4008,-250.3079 1093.5963,-237.3017 1102,-228 1120.4989,-207.5244 1285.6235,-198.0938 1383.6856,-194.2649"/>
<polygon fill="#000000" stroke="#000000" points="1383.9753,-197.7565 1393.8352,-193.8792 1383.7094,-190.7616 1383.9753,-197.7565"/>
<text text-anchor="middle" x="1181.5" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>pdx&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2345.5796,-262.8783C2334.4854,-250.8482 2317.5833,-235.2845 2299,-228 2228.3993,-200.3249 1720.4881,-193.8672 1528.892,-192.4097"/>
<polygon fill="#000000" stroke="#000000" points="1528.668,-188.908 1518.6425,-192.3342 1528.6164,-195.9078 1528.668,-188.908"/>
<text text-anchor="middle" x="2346" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge9" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2384.8721,-271.9853C2399.2526,-268.2901 2417.5202,-263.9299 2434,-261 2467.9232,-254.9688 2565.0943,-268.7389 2588,-243 2592.432,-238.0198 2590.1823,-234.2994 2588,-228 2555.7804,-134.9957 2535.3062,-104.7973 2451,-54 2426.1865,-39.0491 2350.1991,-28.308 2300.1772,-22.6314"/>
<polygon fill="#000000" stroke="#000000" points="2300.2491,-19.1181 2289.9249,-21.4973 2299.4794,-26.0757 2300.2491,-19.1181"/>
<text text-anchor="middle" x="2581" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sequencing_file -->
<g id="node25" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1959" cy="-453" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1959" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1942.4675,-435.2881C1932.2464,-424.891 1918.5326,-411.8941 1905,-402 1896.5651,-395.833 1886.9605,-389.9645 1877.771,-384.823"/>
<polygon fill="#000000" stroke="#000000" points="1879.2366,-381.6361 1868.7784,-379.9397 1875.896,-387.7876 1879.2366,-381.6361"/>
<text text-anchor="middle" x="1988.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node27" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="2150" cy="-453" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="2150" y="-449.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2118.2967,-436.0492C2107.3748,-430.1192 2095.101,-423.3543 2084,-417 2072.7543,-410.5629 2071.1646,-406.4635 2059,-402 2004.9702,-382.1751 1939.436,-373.229 1894.215,-369.2158"/>
<polygon fill="#000000" stroke="#000000" points="1894.2891,-365.7099 1884.0324,-368.365 1893.7062,-372.6856 1894.2891,-365.7099"/>
<text text-anchor="middle" x="2155.5" y="-405.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node28" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1409" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1409" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1366.2258,-261.8091C1350.4865,-252.8808 1338.5565,-241.1021 1348,-228 1354.2635,-219.3099 1374.5864,-211.5246 1395.9394,-205.4358"/>
<polygon fill="#000000" stroke="#000000" points="1397.0449,-208.7623 1405.7758,-202.7605 1395.2078,-202.0077 1397.0449,-208.7623"/>
<text text-anchor="middle" x="1450" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge19" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1862.4341,-87.2086C1873.572,-75.6559 1889.652,-61.4152 1907,-54 1959.9405,-31.3711 2125.6295,-22.4979 2207.4031,-19.4295"/>
<polygon fill="#000000" stroke="#000000" points="2207.5526,-22.9265 2217.4195,-19.067 2207.2994,-15.931 2207.5526,-22.9265"/>
<text text-anchor="middle" x="1970.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- study_status -->
<g id="node30" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2763" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2763" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2741.2227,-87.8844C2725.0308,-76.1689 2701.8715,-61.4547 2679,-54 2609.783,-31.4396 2396.1661,-22.2975 2300.8057,-19.2705"/>
<polygon fill="#000000" stroke="#000000" points="2300.6968,-15.7655 2290.5936,-18.9554 2300.4809,-22.7622 2300.6968,-15.7655"/>
<text text-anchor="middle" x="2766.5" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- study_funding -->
<g id="node31" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2929" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2929" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2902.4831,-88.0183C2882.5599,-76.2059 2854.1457,-61.3143 2827,-54 2728.205,-27.38 2419.3446,-20.3033 2300.8904,-18.5444"/>
<polygon fill="#000000" stroke="#000000" points="2300.7453,-15.0421 2290.6965,-18.3993 2300.6456,-22.0414 2300.7453,-15.0421"/>
<text text-anchor="middle" x="2927" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_radiation -->
<g id="node32" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1699" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1699" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1662.7396,-262.0889C1639.3994,-251.5469 1608.2517,-238.1122 1580,-228 1558.2272,-220.2068 1533.8658,-212.8485 1512.5379,-206.8402"/>
<polygon fill="#000000" stroke="#000000" points="1513.2275,-203.3992 1502.6553,-204.0907 1511.3513,-210.143 1513.2275,-203.3992"/>
<text text-anchor="middle" x="1699" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
</g>
</svg>
</div>
