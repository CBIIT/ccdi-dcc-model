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
<svg width="3862pt" height="392pt"
 viewBox="0.00 0.00 3862.09 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3858.0923,-388 3858.0923,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node23" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="769.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="769.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8482,-86.6087C79.9529,-75.6988 79.9648,-62.402 88.0923,-54 110.1232,-31.225 571.6743,-21.3641 722.1294,-18.7468"/>
<polygon fill="#000000" stroke="#000000" points="722.4756,-22.2415 732.4143,-18.5708 722.3558,-15.2425 722.4756,-22.2415"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="3116.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="3116.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="3205.0923" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="3205.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3114.8467,-347.8174C3115.0511,-337.2535 3117.0033,-324.2464 3124.0923,-315 3129.2581,-308.262 3145.0194,-300.6443 3161.2825,-294.157"/>
<polygon fill="#000000" stroke="#000000" points="3162.7614,-297.3382 3170.8397,-290.4832 3160.2497,-290.8044 3162.7614,-297.3382"/>
<text text-anchor="middle" x="3190.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2282.0923" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2282.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2347.0349,-355.0304C2420.7447,-343.051 2544.6946,-324.3306 2652.0923,-315 2871.4115,-295.9458 2930.0696,-333.9483 3147.0923,-297 3151.9058,-296.1805 3156.876,-295.0684 3161.7885,-293.7964"/>
<polygon fill="#000000" stroke="#000000" points="3163.0432,-297.0794 3171.7226,-291.0034 3161.1486,-290.3407 3163.0432,-297.0794"/>
<text text-anchor="middle" x="2717.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- participant -->
<g id="node9" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1858.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1858.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2220.8503,-353.9462C2160.3872,-342.4348 2065.1865,-325.3513 1982.0923,-315 1957.0949,-311.886 1773.183,-315.5061 1756.0923,-297 1728.2372,-266.8382 1776.1569,-232.9301 1815.3086,-212.015"/>
<polygon fill="#000000" stroke="#000000" points="1817.245,-214.9536 1824.5122,-207.244 1814.0233,-208.739 1817.245,-214.9536"/>
<text text-anchor="middle" x="1821.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- generic_file -->
<g id="node4" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1084.0923" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1084.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1133.1437,-353.929C1143.6349,-351.6765 1154.6908,-349.5478 1165.0923,-348 1354.2396,-319.8541 1403.0489,-323.446 1594.0923,-315 1766.491,-307.3783 2976.6275,-323.8549 3147.0923,-297 3152.106,-296.2101 3157.2851,-295.0808 3162.3901,-293.7676"/>
<polygon fill="#000000" stroke="#000000" points="3163.3701,-297.1279 3172.0529,-291.0566 3161.4792,-290.3881 3163.3701,-297.1279"/>
<text text-anchor="middle" x="1647.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1082.9233,-347.9489C1082.4635,-324.4625 1085.4735,-283.7491 1109.0923,-261 1157.2127,-214.6514 1607.0642,-198.3108 1785.5884,-193.6203"/>
<polygon fill="#000000" stroke="#000000" points="1785.7672,-197.1169 1795.6736,-193.3602 1785.5867,-190.1193 1785.7672,-197.1169"/>
<text text-anchor="middle" x="1162.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1018.4443,-365.4409C866.0079,-363.6991 491.7413,-356.7492 369.0923,-330 309.2605,-316.951 241.0923,-340.2383 241.0923,-279 241.0923,-279 241.0923,-279 241.0923,-105 241.0923,-43.7617 309.5295,-68.2266 369.0923,-54 435.0607,-38.2434 631.7732,-25.6444 722.4136,-20.5036"/>
<polygon fill="#000000" stroke="#000000" points="722.8783,-23.9831 732.6664,-19.9283 722.486,-16.9941 722.8783,-23.9831"/>
<text text-anchor="middle" x="294.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- radiology_file -->
<g id="node5" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1969.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1969.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1947.1622,-261.8116C1930.2109,-248.5254 1906.5671,-229.9938 1887.8994,-215.3624"/>
<polygon fill="#000000" stroke="#000000" points="1890.0064,-212.5668 1879.9767,-209.1527 1885.6882,-218.0763 1890.0064,-212.5668"/>
<text text-anchor="middle" x="1979.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3170.3357,-267.807C3149.7714,-261.0051 3123.2909,-251.9338 3100.0923,-243 3084.2989,-236.918 3081.618,-231.6496 3065.0923,-228 2954.7902,-203.6405 2174.6784,-194.7808 1930.781,-192.5883"/>
<polygon fill="#000000" stroke="#000000" points="1930.6375,-189.087 1920.6068,-192.4979 1930.5752,-196.0867 1930.6375,-189.087"/>
<text text-anchor="middle" x="3136.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node11" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="3183.0923" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="3183.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge37" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M3190.0337,-261.8316C3186.0016,-256.2089 3182.1844,-249.6806 3180.0923,-243 3177.7961,-235.668 3177.3974,-227.4584 3177.8749,-219.8048"/>
<polygon fill="#000000" stroke="#000000" points="3181.3557,-220.1706 3178.9733,-209.8471 3174.3979,-219.403 3181.3557,-220.1706"/>
<text text-anchor="middle" x="3216.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node27" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="3539.0923" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="3539.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge38" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M3242.4341,-269.2732C3302.6665,-253.584 3421.3312,-222.6743 3488.8978,-205.0746"/>
<polygon fill="#000000" stroke="#000000" points="3490.0897,-208.381 3498.8845,-202.4733 3488.3252,-201.607 3490.0897,-208.381"/>
<text text-anchor="middle" x="3427.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- family_relationship -->
<g id="node7" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2161.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2161.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2126.933,-262.066C2103.5308,-251.0403 2071.5192,-237.0722 2042.0923,-228 2003.8727,-216.217 1959.9538,-207.4517 1924.611,-201.5217"/>
<polygon fill="#000000" stroke="#000000" points="1924.8439,-198.0131 1914.4092,-199.8483 1923.7107,-204.9208 1924.8439,-198.0131"/>
<text text-anchor="middle" x="2161.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pathology_file -->
<g id="node8" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="3293.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="3293.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3284.1488,-347.6344C3278.501,-337.2626 3270.501,-324.5126 3261.0923,-315 3255.2632,-309.1066 3248.305,-303.6898 3241.3079,-298.9452"/>
<polygon fill="#000000" stroke="#000000" points="3242.815,-295.7542 3232.5061,-293.3095 3239.0404,-301.6494 3242.815,-295.7542"/>
<text text-anchor="middle" x="3333.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- consent_group -->
<g id="node17" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="611.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="611.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1795.346,-191.3514C1545.3992,-188.6225 633.1186,-177.2224 612.0923,-156 606.1544,-150.0068 604.4974,-141.4116 604.7575,-132.9808"/>
<polygon fill="#000000" stroke="#000000" points="608.2446,-133.2892 605.8665,-122.9647 601.2872,-132.5187 608.2446,-133.2892"/>
<text text-anchor="middle" x="662.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_funding -->
<g id="node10" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="987.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="987.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge6" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M948.1182,-89.4461C908.2639,-73.541 846.7497,-48.9917 807.2093,-33.2119"/>
<polygon fill="#000000" stroke="#000000" points="808.2417,-29.8555 797.6567,-29.3996 805.6471,-36.3569 808.2417,-29.8555"/>
<text text-anchor="middle" x="953.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3209.8354,-197.4564C3226.5469,-202.3969 3246.7876,-211.5275 3257.0923,-228 3264.5739,-239.9598 3255.6592,-251.1812 3243.218,-260.0365"/>
<polygon fill="#000000" stroke="#000000" points="3241.2124,-257.1645 3234.67,-265.498 3244.9813,-263.0633 3241.2124,-257.1645"/>
<text text-anchor="middle" x="3283.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3155.1458,-191.6027C2888.5696,-187.8101 804.5591,-158.097 797.0923,-156 769.2794,-148.1888 755.4252,-148.0826 741.0923,-123 726.9232,-98.2041 739.3008,-66.0195 751.7847,-43.8539"/>
<polygon fill="#000000" stroke="#000000" points="754.9392,-45.3981 757.0643,-35.0185 748.9303,-41.8073 754.9392,-45.3981"/>
<text text-anchor="middle" x="765.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- medical_history -->
<g id="node12" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2364.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2364.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2332.2212,-262.0964C2308.7891,-250.4835 2275.8089,-235.8048 2245.0923,-228 2187.2767,-213.3097 2024.7218,-201.7391 1929.6832,-195.9863"/>
<polygon fill="#000000" stroke="#000000" points="1929.763,-192.4849 1919.5716,-195.3807 1929.3445,-199.4723 1929.763,-192.4849"/>
<text text-anchor="middle" x="2356.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- survival -->
<g id="node13" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2970.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2970.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2947.2752,-263.0423C2928.5653,-250.9323 2900.8891,-235.1824 2874.0923,-228 2783.8375,-203.8089 2147.6895,-195.0062 1930.534,-192.6863"/>
<polygon fill="#000000" stroke="#000000" points="1930.5502,-189.1864 1920.5138,-192.5807 1930.4763,-196.186 1930.5502,-189.1864"/>
<text text-anchor="middle" x="2949.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_status -->
<g id="node14" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1153.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1153.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge33" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1118.2367,-89.2961C1091.5891,-77.8936 1053.6719,-62.9529 1019.0923,-54 949.1944,-35.9031 865.7887,-26.1927 815.1675,-21.5672"/>
<polygon fill="#000000" stroke="#000000" points="815.457,-18.0792 805.187,-20.6825 814.8389,-25.0519 815.457,-18.0792"/>
<text text-anchor="middle" x="1120.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_surgery -->
<g id="node15" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="548.0923" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="548.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M565.2796,-261.0228C577.8282,-249.2259 595.9344,-234.7723 615.0923,-228 670.3921,-208.4514 1527.7665,-196.1473 1785.4174,-192.8773"/>
<polygon fill="#000000" stroke="#000000" points="1785.4643,-196.3771 1795.4194,-192.7511 1785.3759,-189.3777 1785.4643,-196.3771"/>
<text text-anchor="middle" x="693.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node16" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="794.0923" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="794.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M781.9951,-260.7973C776.4257,-249.9583 772.7074,-236.6699 781.0923,-228 798.5633,-209.9352 1545.8506,-196.8281 1785.1762,-193.0875"/>
<polygon fill="#000000" stroke="#000000" points="1785.5646,-196.582 1795.509,-192.9269 1785.4557,-189.5829 1785.5646,-196.582"/>
<text text-anchor="middle" x="883.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge18" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M592.9675,-87.2928C584.5236,-76.8975 577.9496,-63.9006 586.0923,-54 603.0505,-33.3807 674.0919,-24.3878 722.5057,-20.5986"/>
<polygon fill="#000000" stroke="#000000" points="723.0499,-24.0682 732.767,-19.846 722.5378,-17.0869 723.0499,-24.0682"/>
<text text-anchor="middle" x="649.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- exposure -->
<g id="node18" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="995.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="995.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M989.9036,-261.0718C987.9095,-250.0592 987.7945,-236.4835 996.0923,-228 1023.5012,-199.9776 1582.5992,-193.7119 1785.4113,-192.359"/>
<polygon fill="#000000" stroke="#000000" points="1785.6853,-195.8574 1795.6624,-192.2928 1785.64,-188.8575 1785.6853,-195.8574"/>
<text text-anchor="middle" x="1039.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node19" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="2672.0923" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="2672.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2713.4161,-354.1715C2735.4661,-347.5827 2762.9566,-338.9235 2787.0923,-330 2802.966,-324.1311 2805.6144,-318.8601 2822.0923,-315 2962.9449,-282.004 3004.7154,-322.6324 3147.0923,-297 3151.8978,-296.1348 3156.8629,-294.9936 3161.7724,-293.7045"/>
<polygon fill="#000000" stroke="#000000" points="3163.0354,-296.9846 3171.7031,-290.8919 3161.1278,-290.2495 3163.0354,-296.9846"/>
<text text-anchor="middle" x="2866.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2648.7948,-349.6812C2636.5511,-339.185 2625.9872,-325.5809 2636.0923,-315 2666.1292,-283.5484 2997.0553,-328.4516 3027.0923,-297 3038.1428,-285.4291 3033.3253,-275.736 3027.0923,-261 3018.8886,-241.6052 3012.4794,-236.2217 2993.0923,-228 2944.2217,-207.275 2174.0089,-195.9391 1930.972,-192.8652"/>
<polygon fill="#000000" stroke="#000000" points="1930.8726,-189.3637 1920.8294,-192.7378 1930.7847,-196.3632 1930.8726,-189.3637"/>
<text text-anchor="middle" x="3077.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node20" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="1226.0923" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="1226.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1276.1504,-360.9085C1315.5172,-357.0183 1371.7644,-351.7111 1421.0923,-348 1546.9498,-338.5314 1861.9647,-319.6477 1988.0923,-315 2116.7982,-310.2573 3019.9078,-317.2934 3147.0923,-297 3152.1044,-296.2003 3157.2826,-295.0648 3162.387,-293.7481"/>
<polygon fill="#000000" stroke="#000000" points="3163.3687,-297.1079 3172.0492,-291.0334 3161.4752,-290.3688 3163.3687,-297.1079"/>
<text text-anchor="middle" x="2030.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1221.7762,-347.9197C1217.417,-324.7784 1213.9917,-284.8377 1235.0923,-261 1271.087,-220.336 1629.7424,-201.1347 1785.9807,-194.6492"/>
<polygon fill="#000000" stroke="#000000" points="1786.1251,-198.1463 1795.9736,-194.2403 1785.8388,-191.1522 1786.1251,-198.1463"/>
<text text-anchor="middle" x="1277.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1187.4481,-353.9393C1178.2429,-351.5354 1168.3908,-349.3407 1159.0923,-348 1117.7302,-342.0363 442.1063,-352.8123 407.0923,-330 386.103,-316.3251 383.0923,-304.0511 383.0923,-279 383.0923,-279 383.0923,-279 383.0923,-105 383.0923,-52.3188 439.5592,-68.8902 490.0923,-54 569.6975,-30.5433 666.5473,-22.3651 722.6762,-19.5173"/>
<polygon fill="#000000" stroke="#000000" points="722.8459,-23.0133 732.6695,-19.0451 722.5154,-16.0211 722.8459,-23.0133"/>
<text text-anchor="middle" x="425.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_other -->
<g id="node21" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="1416.0923" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1416.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge34" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1403.1234,-260.9918C1397.0695,-250.226 1392.8231,-236.9462 1401.0923,-228 1413.9491,-214.0906 1660.4709,-200.9578 1785.9739,-195.1404"/>
<polygon fill="#000000" stroke="#000000" points="1786.435,-198.623 1796.2637,-194.6672 1786.1134,-191.6303 1786.435,-198.623"/>
<text text-anchor="middle" x="1470.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- study_admin -->
<g id="node22" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1311.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1311.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1278.2681,-89.0802C1252.4771,-77.3266 1215.3164,-62.0317 1181.0923,-54 1112.6913,-37.9477 908.0864,-25.3992 815.5045,-20.3788"/>
<polygon fill="#000000" stroke="#000000" points="815.4868,-16.8729 805.3136,-19.8321 815.1118,-23.8629 815.4868,-16.8729"/>
<text text-anchor="middle" x="1284.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- clinical_measure_file -->
<g id="node24" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1539.0923" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1539.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1637.7311,-358.4371C1789.2862,-347.1125 2088.5992,-325.9158 2343.0923,-315 2521.6395,-307.3417 2970.7108,-325.7635 3147.0923,-297 3152.1017,-296.1831 3157.2781,-295.0369 3162.3815,-293.7141"/>
<polygon fill="#000000" stroke="#000000" points="3163.3661,-297.0731 3172.0427,-290.993 3161.4683,-290.3352 3163.3661,-297.0731"/>
<text text-anchor="middle" x="2429.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1535.8368,-347.8531C1532.7954,-324.6398 1531.5052,-284.6213 1553.0923,-261 1584.2191,-226.94 1708.4774,-207.6902 1788.4684,-198.5994"/>
<polygon fill="#000000" stroke="#000000" points="1788.9256,-202.0702 1798.4784,-197.4883 1788.1533,-195.1129 1788.9256,-202.0702"/>
<text text-anchor="middle" x="1639.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1439.7689,-358.6485C1393.3888,-355.2816 1337.4241,-351.3128 1287.0923,-348 1193.0143,-341.8079 504.7249,-365.6414 440.0923,-297 429.1238,-285.3513 435.6678,-276.3761 440.0923,-261 447.4919,-235.2844 459.8137,-233.7757 472.0923,-210 499.2473,-157.4184 484.263,-131.6599 523.0923,-87 542.0471,-65.199 552.054,-64.1735 579.0923,-54 626.3975,-36.2007 683.7727,-26.8861 723.0144,-22.2325"/>
<polygon fill="#000000" stroke="#000000" points="723.5368,-25.6958 733.08,-21.0938 722.7499,-18.7402 723.5368,-25.6958"/>
<text text-anchor="middle" x="573.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node25" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="3477.0923" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="3477.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3454.888,-348.3001C3439.7267,-337.0914 3418.7201,-323.2111 3398.0923,-315 3352.9373,-297.0257 3298.2089,-287.9058 3258.5801,-283.3531"/>
<polygon fill="#000000" stroke="#000000" points="3258.9109,-279.8685 3248.5907,-282.2651 3258.1529,-286.8274 3258.9109,-279.8685"/>
<text text-anchor="middle" x="3496.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- genetic_analysis -->
<g id="node26" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="3715.0923" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="3715.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3657.3921,-352.3057C3637.2201,-346.5814 3614.7216,-339.1138 3595.0923,-330 3584.0232,-324.8606 3583.6064,-319.045 3572.0923,-315 3515.8063,-295.2262 3346.9639,-285.1635 3259.2813,-281.1524"/>
<polygon fill="#000000" stroke="#000000" points="3259.4063,-277.6546 3249.2599,-280.7042 3259.0935,-284.6476 3259.4063,-277.6546"/>
<text text-anchor="middle" x="3665.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3730.5372,-348.0606C3737.6274,-337.5828 3742.907,-324.581 3735.0923,-315 3674.2974,-240.4641 3406.6578,-238.9008 3311.0923,-228 3173.7155,-212.3299 2206.4678,-197.1031 1931.0869,-193.0474"/>
<polygon fill="#000000" stroke="#000000" points="1930.8607,-189.5438 1920.8104,-192.8965 1930.7579,-196.543 1930.8607,-189.5438"/>
<text text-anchor="middle" x="3784.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3577.9036,-203.2284C3602.9546,-212.3638 3628.2653,-226.4292 3613.0923,-243 3589.6814,-268.5675 3365.1934,-276.0724 3259.5509,-278.1972"/>
<polygon fill="#000000" stroke="#000000" points="3259.3354,-274.7006 3249.4044,-278.392 3259.4698,-281.6993 3259.3354,-274.7006"/>
<text text-anchor="middle" x="3657.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge8" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3490.4778,-188.7246C3427.9526,-184.6344 3315.9832,-177.7231 3220.0923,-174 3153.4608,-171.413 876.2337,-158.9805 820.0923,-123 793.667,-106.0643 780.5492,-71.19 774.309,-46.2806"/>
<polygon fill="#000000" stroke="#000000" points="777.6688,-45.2706 772.037,-36.2966 770.8433,-46.8239 777.6688,-45.2706"/>
<text text-anchor="middle" x="860.5923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- methylation_array_file -->
<g id="node28" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="2899.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="2899.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge43" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2905.24,-347.772C2910.1062,-336.3403 2918.106,-322.4099 2930.0923,-315 2971.2504,-289.5561 3099.5921,-306.2259 3147.0923,-297 3151.8241,-296.0809 3156.7156,-294.9161 3161.559,-293.6225"/>
<polygon fill="#000000" stroke="#000000" points="3162.7105,-296.9337 3171.3662,-290.824 3160.7896,-290.2024 3162.7105,-296.9337"/>
<text text-anchor="middle" x="3021.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- treatment_radiation -->
<g id="node29" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="2572.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2572.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2533.8081,-262.156C2505.2593,-250.4121 2464.9893,-235.5458 2428.0923,-228 2335.0459,-208.9711 2062.0862,-198.2627 1930.5681,-194.0775"/>
<polygon fill="#000000" stroke="#000000" points="1930.3057,-190.5676 1920.2007,-193.7518 1930.0858,-197.5642 1930.3057,-190.5676"/>
<text text-anchor="middle" x="2563.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- publication -->
<g id="node30" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1462.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1462.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1432.7941,-88.8004C1409.713,-76.8964 1376.3257,-61.5356 1345.0923,-54 1244.9908,-29.8489 934.3035,-21.2721 815.7284,-18.8295"/>
<polygon fill="#000000" stroke="#000000" points="815.5965,-15.3263 805.5283,-18.6249 815.456,-22.3249 815.5965,-15.3263"/>
<text text-anchor="middle" x="1439.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment_response -->
<g id="node31" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2799.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2799.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge44" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2760.0807,-262.2242C2730.4951,-250.3508 2688.5045,-235.292 2650.0923,-228 2513.5141,-202.0727 2099.3644,-194.6476 1930.7174,-192.6688"/>
<polygon fill="#000000" stroke="#000000" points="1930.733,-189.1688 1920.6936,-192.5542 1930.653,-196.1684 1930.733,-189.1688"/>
<text text-anchor="middle" x="2787.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_arm -->
<g id="node32" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="1603.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="1603.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1575.9676,-88.6718C1554.5562,-76.6987 1523.4919,-61.3076 1494.0923,-54 1428.6268,-37.7279 965.5173,-23.4922 815.715,-19.2692"/>
<polygon fill="#000000" stroke="#000000" points="815.5746,-15.7639 805.4805,-18.9825 815.3785,-22.7612 815.5746,-15.7639"/>
<text text-anchor="middle" x="1582.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
