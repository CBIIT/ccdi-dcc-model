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
<svg width="3705pt" height="392pt"
 viewBox="0.00 0.00 3705.14 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3701.1367,-388 3701.1367,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node15" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3037.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3037.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8189,-86.9876C79.7909,-75.9415 79.6701,-62.36 88.0923,-54 114.9884,-27.3021 2616.3815,-19.1903 2990.4984,-18.126"/>
<polygon fill="#000000" stroke="#000000" points="2990.7037,-21.6256 3000.6938,-18.0973 2990.6839,-14.6256 2990.7037,-21.6256"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- medical_history -->
<g id="node2" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2684.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2684.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2123.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2123.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2657.5713,-261.6306C2638.2973,-249.9546 2611.1302,-235.3952 2585.0923,-228 2513.9845,-207.8042 2306.9067,-198.0527 2195.704,-194.1575"/>
<polygon fill="#000000" stroke="#000000" points="2195.6909,-190.655 2185.5766,-193.8096 2195.4506,-197.6509 2195.6909,-190.655"/>
<text text-anchor="middle" x="2690.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- exposure -->
<g id="node3" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="2840.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="2840.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2820.7634,-262.1862C2805.8336,-250.2934 2784.0711,-235.2269 2762.0923,-228 2709.5335,-210.718 2351.9603,-198.5361 2195.8032,-193.9794"/>
<polygon fill="#000000" stroke="#000000" points="2195.4613,-190.4682 2185.3643,-193.6774 2195.2589,-197.4652 2195.4613,-190.4682"/>
<text text-anchor="middle" x="2835.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- radiology_file -->
<g id="node4" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2985.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2985.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2959.0277,-262.1441C2939.1018,-250.2299 2910.4851,-235.155 2883.0923,-228 2817.8144,-210.9495 2372.6764,-198.1851 2195.5621,-193.7252"/>
<polygon fill="#000000" stroke="#000000" points="2195.3862,-190.2198 2185.3018,-193.4686 2195.2111,-197.2177 2195.3862,-190.2198"/>
<text text-anchor="middle" x="2980.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- genetic_analysis -->
<g id="node5" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1407.0923" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1407.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1471.6292,-353.6464C1507.448,-346.1356 1545.839,-336.7282 1551.0923,-330 1555.195,-324.7453 1555.3593,-320.1222 1551.0923,-315 1522.7478,-280.9753 1481.4367,-331.0247 1453.0923,-297 1442.8513,-284.7068 1442.7655,-273.2212 1453.0923,-261 1509.8243,-193.8606 1560.8429,-238.666 1648.0923,-228 1790.5164,-210.5891 1958.0624,-200.2427 2051.2633,-195.3821"/>
<polygon fill="#000000" stroke="#000000" points="2051.6196,-198.8685 2061.4262,-194.8586 2051.2593,-191.8778 2051.6196,-198.8685"/>
<text text-anchor="middle" x="1523.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample -->
<g id="node27" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="1092.0923" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="1092.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1354.6622,-351.4996C1336.6526,-345.7452 1316.6234,-338.4648 1299.0923,-330 1288.1023,-324.6936 1287.4004,-319.5896 1276.0923,-315 1234.0501,-297.9363 1183.2383,-288.7816 1145.6723,-283.9821"/>
<polygon fill="#000000" stroke="#000000" points="1145.7953,-280.4715 1135.4464,-282.741 1144.9518,-287.4205 1145.7953,-280.4715"/>
<text text-anchor="middle" x="1369.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- generic_file -->
<g id="node6" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="244.0923" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="244.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M261.3986,-348.4695C286.8236,-323.9781 336.9328,-280.3543 389.0923,-261 513.1947,-214.9505 553.0279,-236.9981 685.0923,-228 753.6575,-223.3284 1767.7839,-200.0675 2050.4396,-193.645"/>
<polygon fill="#000000" stroke="#000000" points="2050.6625,-197.141 2060.5804,-193.4147 2050.5035,-190.1428 2050.6625,-197.141"/>
<text text-anchor="middle" x="442.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M243.0933,-347.6758C242.2206,-330.0738 241.0923,-302.7276 241.0923,-279 241.0923,-279 241.0923,-279 241.0923,-105 241.0923,-33.2582 2624.4684,-19.8293 2990.2316,-18.1909"/>
<polygon fill="#000000" stroke="#000000" points="2990.4756,-21.69 3000.4601,-18.1458 2990.4447,-14.69 2990.4756,-21.69"/>
<text text-anchor="middle" x="294.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M271.7528,-349.6687C293.5776,-337.6939 325.2208,-322.3021 355.0923,-315 420.7319,-298.9543 878.8077,-284.9036 1037.8482,-280.4591"/>
<polygon fill="#000000" stroke="#000000" points="1037.9852,-283.9567 1047.8841,-280.1803 1037.7908,-276.9594 1037.9852,-283.9567"/>
<text text-anchor="middle" x="408.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1963.0923" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1963.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1980.8725,-261.6166C1992.6589,-250.8214 2008.8864,-237.2832 2025.0923,-228 2038.7681,-220.1661 2054.4599,-213.5006 2069.2203,-208.1136"/>
<polygon fill="#000000" stroke="#000000" points="2070.4836,-211.3795 2078.755,-204.7588 2068.1602,-204.7763 2070.4836,-211.3795"/>
<text text-anchor="middle" x="2072.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- family_relationship -->
<g id="node8" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2139.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2139.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2129.9319,-260.7422C2127.572,-255.1833 2125.3459,-248.9634 2124.0923,-243 2122.5568,-235.6958 2121.924,-227.6732 2121.7659,-220.197"/>
<polygon fill="#000000" stroke="#000000" points="2125.2661,-220.1401 2121.8139,-210.1235 2118.2662,-220.1067 2125.2661,-220.1401"/>
<text text-anchor="middle" x="2203.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- cytogenomic_file -->
<g id="node9" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="770.0923" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="770.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M775.9892,-347.941C780.6763,-336.5808 788.4131,-322.6663 800.0923,-315 838.071,-290.0703 964.2553,-282.404 1037.7276,-280.0466"/>
<polygon fill="#000000" stroke="#000000" points="1037.8393,-283.545 1047.7304,-279.748 1037.6303,-276.5481 1037.8393,-283.545"/>
<text text-anchor="middle" x="871.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- consent_group -->
<g id="node23" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2606.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2606.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2176.1634,-182.4406C2263.0261,-166.7945 2435.6734,-135.6966 2533.6974,-118.0401"/>
<polygon fill="#000000" stroke="#000000" points="2534.5957,-121.4347 2543.8169,-116.2173 2533.3548,-114.5455 2534.5957,-121.4347"/>
<text text-anchor="middle" x="2444.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node11" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1575.0923" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1575.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1578.6122,-347.9211C1584.144,-324.4039 1597.1481,-283.6565 1624.0923,-261 1667.0841,-224.8495 1690.8258,-238.0389 1746.0923,-228 1851.126,-208.9211 1974.5764,-199.5621 2050.8329,-195.2681"/>
<polygon fill="#000000" stroke="#000000" points="2051.4797,-198.738 2061.273,-194.6954 2051.0962,-191.7485 2051.4797,-198.738"/>
<text text-anchor="middle" x="1668.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1540.6581,-351.9381C1507.2468,-338.5044 1458.7908,-319.6346 1439.0923,-315 1337.4511,-291.0863 1215.3372,-283.0547 1146.4209,-280.3593"/>
<polygon fill="#000000" stroke="#000000" points="1146.3598,-276.8548 1136.238,-279.985 1146.1026,-283.8501 1146.3598,-276.8548"/>
<text text-anchor="middle" x="1527.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node12" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="961.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="961.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M950.9802,-347.8297C946.588,-337.2702 943.8969,-324.2634 951.0923,-315 962.0595,-300.8808 1003.9958,-291.37 1039.3067,-285.6876"/>
<polygon fill="#000000" stroke="#000000" points="1040.1814,-289.0944 1049.5337,-284.116 1039.1181,-282.1756 1040.1814,-289.0944"/>
<text text-anchor="middle" x="1017.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node13" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3173.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3173.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3146.8701,-88.2255C3124.4206,-73.8644 3092.0524,-53.1583 3068.2784,-37.95"/>
<polygon fill="#000000" stroke="#000000" points="3069.9361,-34.8556 3059.6262,-32.4151 3066.164,-40.7523 3069.9361,-34.8556"/>
<text text-anchor="middle" x="3169.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_arm -->
<g id="node14" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3321.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3321.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3296.6555,-88.3957C3278.9113,-77.0802 3253.9305,-62.6373 3230.0923,-54 3181.5977,-36.429 3122.9965,-27.0519 3083.1824,-22.3213"/>
<polygon fill="#000000" stroke="#000000" points="3083.5628,-18.8421 3073.2312,-21.1892 3082.7715,-25.7972 3083.5628,-18.8421"/>
<text text-anchor="middle" x="3309.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3476.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3476.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3445.6053,-88.2275C3423.1796,-76.6781 3391.5927,-62.0215 3362.0923,-54 3310.7543,-40.0407 3160.371,-27.2241 3083.4977,-21.36"/>
<polygon fill="#000000" stroke="#000000" points="3083.3916,-17.8421 3073.1564,-20.5793 3082.8645,-24.8222 3083.3916,-17.8421"/>
<text text-anchor="middle" x="3465.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx -->
<g id="node17" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="1255.0923" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="1255.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge8" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1282.7256,-189.3018C1484.9021,-169.5607 2735.2661,-47.4712 2991.3123,-22.4701"/>
<polygon fill="#000000" stroke="#000000" points="2991.7686,-25.9423 3001.3811,-21.4869 2991.0883,-18.9754 2991.7686,-25.9423"/>
<text text-anchor="middle" x="2348.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1251.5602,-209.9914C1248.4857,-221.0292 1242.9186,-234.6092 1233.0923,-243 1219.5401,-254.5724 1178.1055,-264.3228 1143.6345,-270.745"/>
<polygon fill="#000000" stroke="#000000" points="1142.8809,-267.3244 1133.6634,-272.5482 1144.1266,-274.2127 1142.8809,-267.3244"/>
<text text-anchor="middle" x="1269.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- publication -->
<g id="node18" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3634.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3634.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge40" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3608.1163,-88.5976C3587.9382,-76.752 3558.8135,-61.5603 3531.0923,-54 3447.593,-31.2275 3189.9707,-22.0092 3083.6838,-19.1094"/>
<polygon fill="#000000" stroke="#000000" points="3083.6709,-15.608 3073.5813,-18.8405 3083.4846,-22.6055 3083.6709,-15.608"/>
<text text-anchor="middle" x="3620.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- methylation_array_file -->
<g id="node19" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1178.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1178.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1117.3509,-350.6482C1107.7996,-345.5967 1099.1097,-338.8928 1093.0923,-330 1088.6062,-323.3703 1087.1634,-315.0641 1087.1741,-307.0918"/>
<polygon fill="#000000" stroke="#000000" points="1090.6755,-307.1955 1087.8917,-296.973 1083.693,-306.7003 1090.6755,-307.1955"/>
<text text-anchor="middle" x="1184.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- survival -->
<g id="node20" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2305.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2305.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2301.6414,-260.9121C2298.5994,-249.8358 2293.0379,-236.2491 2283.0923,-228 2268.8197,-216.162 2227.6499,-207.0507 2190.6487,-200.956"/>
<polygon fill="#000000" stroke="#000000" points="2190.7745,-197.4321 2180.3488,-199.3172 2189.6746,-204.3451 2190.7745,-197.4321"/>
<text text-anchor="middle" x="2334.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pathology_file -->
<g id="node21" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="586.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="586.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M605.5371,-348.3533C619.6085,-336.708 639.6698,-322.2998 660.0923,-315 728.1966,-290.6568 937.541,-282.5743 1037.6588,-280.0576"/>
<polygon fill="#000000" stroke="#000000" points="1037.9541,-283.5515 1047.8666,-279.8108 1037.7849,-276.5536 1037.9541,-283.5515"/>
<text text-anchor="middle" x="721.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="1063.0923" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="1063.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1108.8128,-185.0517C1233.0773,-166.4057 1587.5834,-114.8009 1884.0923,-87 2312.9818,-46.787 2833.9427,-25.4767 2990.4682,-19.6606"/>
<polygon fill="#000000" stroke="#000000" points="2990.8108,-23.1505 3000.675,-19.2842 2990.5527,-16.1552 2990.8108,-23.1505"/>
<text text-anchor="middle" x="1924.5923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1016.7917,-198.4781C981.4456,-205.4364 941.6822,-218.8965 960.0923,-243 970.0556,-256.0444 1007.732,-265.4966 1040.2957,-271.4335"/>
<polygon fill="#000000" stroke="#000000" points="1039.7481,-274.8907 1050.2012,-273.1631 1040.9523,-267.9951 1039.7481,-274.8907"/>
<text text-anchor="middle" x="1000.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge20" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2665.5685,-92.9944C2753.3072,-75.2838 2915.4167,-42.561 2993.2047,-26.859"/>
<polygon fill="#000000" stroke="#000000" points="2994.0482,-30.2594 3003.1579,-24.8499 2992.6631,-23.3978 2994.0482,-30.2594"/>
<text text-anchor="middle" x="2910.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- laboratory_test -->
<g id="node24" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="410.0923" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="410.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M423.2498,-348.075C432.5405,-336.7714 445.9902,-322.8697 461.0923,-315 657.6301,-212.5844 731.6466,-250.798 952.0923,-228 1060.7391,-216.764 1811.5226,-199.0375 2050.329,-193.6236"/>
<polygon fill="#000000" stroke="#000000" points="2050.7179,-197.1158 2060.6362,-193.3904 2050.5595,-190.1176 2050.7179,-197.1158"/>
<text text-anchor="middle" x="653.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M433.0485,-348.4697C449.8213,-336.7179 473.6421,-322.134 497.0923,-315 547.9323,-299.5335 900.2209,-285.7108 1037.5017,-280.8507"/>
<polygon fill="#000000" stroke="#000000" points="1037.9133,-284.3385 1047.7841,-280.4892 1037.6673,-277.3428 1037.9133,-284.3385"/>
<text text-anchor="middle" x="562.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- clinical_measure_file -->
<g id="node25" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1810.0923" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1810.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1809.5211,-347.6574C1808.2113,-336.7658 1804.76,-323.4712 1796.0923,-315 1772.5026,-291.9451 1744.3915,-322.9988 1724.0923,-297 1714.2457,-284.3887 1713.7875,-273.2398 1724.0923,-261 1765.0063,-212.4034 1947.0176,-198.0331 2050.5095,-193.7839"/>
<polygon fill="#000000" stroke="#000000" points="2050.7226,-197.2783 2060.5789,-193.3922 2050.4504,-190.2836 2050.7226,-197.2783"/>
<text text-anchor="middle" x="1810.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1915.4737,-361.6314C2233.9305,-348.3091 3165.2431,-308.411 3176.0923,-297 3187.1169,-285.4044 3185.2525,-274.1183 3176.0923,-261 3138.418,-207.047 3074.7665,-263.953 3037.0923,-210 3002.6832,-160.7231 3016.7438,-85.6156 3028.0672,-45.5076"/>
<polygon fill="#000000" stroke="#000000" points="3031.4378,-46.4519 3030.9282,-35.8693 3024.7272,-44.4598 3031.4378,-46.4519"/>
<text text-anchor="middle" x="3123.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1733.6512,-353.1931C1699.8783,-347.0246 1659.8118,-339.008 1624.0923,-330 1602.4201,-324.5346 1598.0468,-319.1896 1576.0923,-315 1534.8168,-307.1233 1263.9919,-289.6635 1146.4167,-282.3378"/>
<polygon fill="#000000" stroke="#000000" points="1146.3982,-278.83 1136.2003,-281.7027 1145.9639,-285.8165 1146.3982,-278.83"/>
<text text-anchor="middle" x="1710.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- treatment_response -->
<g id="node26" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2476.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2476.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2448.473,-261.3819C2429.4228,-250.0593 2403.1159,-236.017 2378.0923,-228 2318.1171,-208.7853 2246.9399,-199.8165 2195.0458,-195.6357"/>
<polygon fill="#000000" stroke="#000000" points="2195.1711,-192.1352 2184.9332,-194.8618 2194.6369,-199.1147 2195.1711,-192.1352"/>
<text text-anchor="middle" x="2498.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge23" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1135.381,-275.078C1177.4934,-270.4113 1242.8749,-260.8914 1297.0923,-243 1311.2485,-238.3285 1312.665,-231.7519 1327.0923,-228 1395.9122,-210.1029 1867.6749,-197.7316 2050.7182,-193.5549"/>
<polygon fill="#000000" stroke="#000000" points="2050.8674,-197.0525 2060.7855,-193.3268 2050.7088,-190.0543 2050.8674,-197.0525"/>
<text text-anchor="middle" x="1363.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge22" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M1112.4293,-262.7312C1130.9371,-247.9352 1155.4764,-228.3451 1156.0923,-228 1175.9277,-216.884 1199.8471,-208.0741 1219.2052,-201.9521"/>
<polygon fill="#000000" stroke="#000000" points="1220.3273,-205.2691 1228.8667,-198.9978 1218.2803,-198.575 1220.3273,-205.2691"/>
<text text-anchor="middle" x="1192.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M1075.3354,-262.0607C1070.8238,-256.4473 1066.5238,-249.8667 1064.0923,-243 1061.6009,-235.9642 1060.6416,-228.0334 1060.4756,-220.5593"/>
<polygon fill="#000000" stroke="#000000" points="1063.9773,-220.5111 1060.6921,-210.4385 1056.9789,-220.3613 1063.9773,-220.5111"/>
<text text-anchor="middle" x="1100.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node28" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3094.0923" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3094.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3094.2064,-347.7711C3093.2575,-315.8051 3085.8992,-250.8632 3043.0923,-228 3005.9407,-208.1573 2406.1805,-196.5834 2195.5379,-193.1149"/>
<polygon fill="#000000" stroke="#000000" points="2195.5618,-189.6149 2185.506,-192.951 2195.4474,-196.614 2195.5618,-189.6149"/>
<text text-anchor="middle" x="3129.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge35" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3136.3801,-355.3564C3165.7953,-345.5047 3202.8782,-327.6245 3221.0923,-297 3233.9637,-275.3583 3232.1978,-200.2698 3213.0923,-174 3179.2479,-127.4643 3136.6169,-161.7643 3094.0923,-123 3081.6004,-111.6128 3061.9107,-72.1651 3049.2516,-45.0024"/>
<polygon fill="#000000" stroke="#000000" points="3052.2951,-43.2439 3044.9321,-35.6257 3045.9372,-46.1727 3052.2951,-43.2439"/>
<text text-anchor="middle" x="3267.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3042.1926,-363.9562C2774.9623,-353.4246 1560.1683,-305.4484 1392.0923,-297 1305.8849,-292.6667 1205.8175,-286.4173 1145.8021,-282.5377"/>
<polygon fill="#000000" stroke="#000000" points="1146.0044,-279.0436 1135.7988,-281.889 1145.5513,-286.0289 1146.0044,-279.0436"/>
<text text-anchor="middle" x="2211.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
</g>
</svg>
</div>
