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
<svg width="3814pt" height="392pt"
 viewBox="0.00 0.00 3814.19 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3810.1903,-388 3810.1903,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2853.3956" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2853.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node28" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2104.3956" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2104.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2812.6642,-262.2869C2782.0585,-250.5273 2738.8063,-235.5842 2699.3956,-228 2601.3434,-209.1308 2313.0275,-198.2531 2177.0038,-194.0407"/>
<polygon fill="#000000" stroke="#000000" points="2176.7913,-190.5326 2166.6889,-193.725 2176.5771,-197.5293 2176.7913,-190.5326"/>
<text text-anchor="middle" x="2838.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_personnel -->
<g id="node2" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2545.3956" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2545.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="3145.3956" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="3145.3956" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge19" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2540.1729,-86.6293C2538.2856,-75.7271 2538.2985,-62.4313 2546.3956,-54 2565.4509,-34.1585 2960.9323,-22.5494 3098.6245,-19.0968"/>
<polygon fill="#000000" stroke="#000000" points="3098.9396,-22.5902 3108.8499,-18.8436 3098.7663,-15.5923 3098.9396,-22.5902"/>
<text text-anchor="middle" x="2615.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="863.3956" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="863.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- cell_line -->
<g id="node7" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="49.3956" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="49.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M819.1119,-279.6418C656.1623,-282.1786 97.7384,-292.4863 67.3956,-315 60.0248,-320.469 55.6585,-329.1972 53.0769,-337.8983"/>
<polygon fill="#000000" stroke="#000000" points="49.6064,-337.3751 50.793,-347.9033 56.4308,-338.933 49.6064,-337.3751"/>
<text text-anchor="middle" x="103.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node23" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="863.3956" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="863.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M863.3956,-260.9735C863.3956,-249.1918 863.3956,-233.5607 863.3956,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="866.8957,-220.0033 863.3956,-210.0034 859.8957,-220.0034 866.8957,-220.0033"/>
<text text-anchor="middle" x="899.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M905.3698,-273.1203C983.3916,-262.4149 1156.1259,-239.7643 1302.3956,-228 1570.7567,-206.416 1890.7525,-196.9079 2031.6685,-193.5408"/>
<polygon fill="#000000" stroke="#000000" points="2031.993,-197.0342 2041.9077,-193.2994 2031.8279,-190.0361 2031.993,-197.0342"/>
<text text-anchor="middle" x="1338.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cytogenomic_file -->
<g id="node4" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="819.3956" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="819.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M793.7989,-348.6816C782.7314,-338.9861 773.8484,-326.5559 781.3956,-315 788.9156,-303.4858 801.0285,-295.6305 813.6626,-290.2803"/>
<polygon fill="#000000" stroke="#000000" points="815.2154,-293.4366 823.3581,-286.6582 812.7656,-286.8792 815.2154,-293.4366"/>
<text text-anchor="middle" x="852.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- pathology_file -->
<g id="node5" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="635.3956" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="635.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M637.2102,-347.8184C639.2967,-336.7047 643.7777,-323.1116 653.3956,-315 676.3738,-295.6206 754.8171,-286.3379 809.0384,-282.1427"/>
<polygon fill="#000000" stroke="#000000" points="809.4832,-285.6195 819.1987,-281.3936 808.9684,-278.6385 809.4832,-285.6195"/>
<text text-anchor="middle" x="714.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- radiology_file -->
<g id="node6" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1736.3956" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1736.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1742.9511,-260.8539C1748.0628,-249.4569 1756.3406,-235.5342 1768.3956,-228 1790.3039,-214.3077 1941.1406,-202.414 2033.109,-196.3263"/>
<polygon fill="#000000" stroke="#000000" points="2033.4438,-199.812 2043.1938,-195.6664 2032.9866,-192.8269 2033.4438,-199.812"/>
<text text-anchor="middle" x="1827.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M82.8997,-352.7449C121.0695,-337.6452 178.2389,-315.0341 178.3956,-315 298.2988,-288.8791 669.0972,-281.4837 809.1153,-279.5929"/>
<polygon fill="#000000" stroke="#000000" points="809.2327,-283.0918 819.186,-279.4611 809.141,-276.0924 809.2327,-283.0918"/>
<text text-anchor="middle" x="218.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge39" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M35.5149,-348.4696C23.6205,-331.6563 8.3956,-305.0479 8.3956,-279 8.3956,-279 8.3956,-279 8.3956,-105 8.3956,-64.5598 2708.8918,-24.268 3098.7263,-18.6623"/>
<polygon fill="#000000" stroke="#000000" points="3098.8584,-22.1608 3108.8071,-18.5176 3098.7579,-15.1615 3098.8584,-22.1608"/>
<text text-anchor="middle" x="48.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1881.3956" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1881.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1883.9757,-260.7939C1886.519,-249.6705 1891.5366,-236.0757 1901.3956,-228 1921.3423,-211.6612 1983.1341,-202.3107 2033.3532,-197.2576"/>
<polygon fill="#000000" stroke="#000000" points="2033.9328,-200.718 2043.5503,-196.2735 2033.2603,-193.7504 2033.9328,-200.718"/>
<text text-anchor="middle" x="1944.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1215.3956" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1215.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1172.0841,-355.0059C1150.8667,-348.8922 1125.247,-340.4062 1103.3956,-330 1092.3772,-324.7527 1091.7687,-319.4263 1080.3956,-315 1027.4042,-294.3763 962.6435,-285.5648 917.7324,-281.8016"/>
<polygon fill="#000000" stroke="#000000" points="917.8559,-278.3007 907.6136,-281.0109 917.3105,-285.2794 917.8559,-278.3007"/>
<text text-anchor="middle" x="1147.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1267.5241,-360.5426C1341.4554,-352.5514 1468.6236,-337.7742 1475.3956,-330 1479.7745,-324.9731 1479.3627,-320.3579 1475.3956,-315 1459.0818,-292.9667 1432.7094,-319.0333 1416.3956,-297 1406.8747,-284.1411 1406.3045,-273.4165 1416.3956,-261 1454.7452,-213.8131 1863.3488,-198.0972 2032.1101,-193.5944"/>
<polygon fill="#000000" stroke="#000000" points="2032.242,-197.0923 2042.1472,-193.3324 2032.0592,-190.0947 2032.242,-197.0923"/>
<text text-anchor="middle" x="1460.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- publication -->
<g id="node11" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="3274.3956" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="3274.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge33" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3249.5231,-88.2255C3228.4522,-74.0149 3198.1692,-53.5915 3175.688,-38.4297"/>
<polygon fill="#000000" stroke="#000000" points="3177.4352,-35.3866 3167.1875,-32.6968 3173.5212,-41.1901 3177.4352,-35.3866"/>
<text text-anchor="middle" x="3268.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- treatment -->
<g id="node12" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2010.3956" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2010.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1998.4875,-261.1348C1993.1357,-250.6834 1989.4164,-237.6832 1996.3956,-228 2002.6591,-219.3099 2022.982,-211.5246 2044.335,-205.4358"/>
<polygon fill="#000000" stroke="#000000" points="2045.4406,-208.7623 2054.1715,-202.7605 2043.6034,-202.0077 2045.4406,-208.7623"/>
<text text-anchor="middle" x="2043.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- methylation_array_file -->
<g id="node13" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="425.3956" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="425.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M431.5567,-347.7935C436.4285,-336.371 444.4297,-322.4426 456.3956,-315 471.1512,-305.8223 701.8282,-289.5991 809.1935,-282.4958"/>
<polygon fill="#000000" stroke="#000000" points="809.7481,-285.967 819.4964,-281.8171 809.2879,-278.9821 809.7481,-285.967"/>
<text text-anchor="middle" x="547.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node14" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3425.3956" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3425.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge20" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3397.2591,-88.3932C3377.2513,-77.225 3349.4163,-62.9593 3323.3956,-54 3279.7122,-38.9591 3227.717,-29.3419 3191.238,-23.8674"/>
<polygon fill="#000000" stroke="#000000" points="3191.3113,-20.3413 3180.9117,-22.366 3190.3041,-27.2685 3191.3113,-20.3413"/>
<text text-anchor="middle" x="3413.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- genetic_analysis -->
<g id="node15" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="204.3956" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="204.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M229.4198,-348.5058C247.6462,-336.771 273.4173,-322.1926 298.3956,-315 393.1548,-287.7137 686.4704,-281.0851 808.8728,-279.4943"/>
<polygon fill="#000000" stroke="#000000" points="809.1746,-282.9909 819.1306,-279.3676 809.0881,-275.9915 809.1746,-282.9909"/>
<text text-anchor="middle" x="368.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M138.002,-354.2033C99.7221,-346.7265 58.0519,-337.1524 52.3956,-330 48.2603,-324.7709 47.9414,-319.9603 52.3956,-315 172.9091,-180.796 679.4419,-240.2828 859.3956,-228 1089.6586,-212.2833 1801.5899,-197.7459 2031.7896,-193.3494"/>
<polygon fill="#000000" stroke="#000000" points="2032.1273,-196.8437 2042.0588,-193.1539 2031.994,-189.8449 2032.1273,-196.8437"/>
<text text-anchor="middle" x="212.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- synonym -->
<g id="node16" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="3022.3956" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="3022.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2970.6277,-363.9139C2676.5636,-352.0642 1218.9224,-293.3265 917.8573,-281.1946"/>
<polygon fill="#000000" stroke="#000000" points="917.7721,-277.6884 907.6392,-280.7829 917.4901,-284.6828 917.7721,-277.6884"/>
<text text-anchor="middle" x="2113.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge25" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3064.3812,-355.1079C3100.0134,-343.034 3145.3956,-319.6726 3145.3956,-279 3145.3956,-279 3145.3956,-279 3145.3956,-105 3145.3956,-85.5475 3145.3956,-63.6484 3145.3956,-46.6877"/>
<polygon fill="#000000" stroke="#000000" points="3148.8957,-46.3305 3145.3956,-36.3306 3141.8957,-46.3306 3148.8957,-46.3305"/>
<text text-anchor="middle" x="3187.8956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3023.8595,-347.8158C3023.9735,-337.7436 3022.9336,-325.2291 3018.3956,-315 2995.4429,-263.2629 2978.4684,-247.668 2925.3956,-228 2856.3475,-202.4117 2364.7186,-194.6818 2176.997,-192.6481"/>
<polygon fill="#000000" stroke="#000000" points="2176.9852,-189.1478 2166.9486,-192.5415 2176.9109,-196.1474 2176.9852,-189.1478"/>
<text text-anchor="middle" x="3051.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- family_relationship -->
<g id="node17" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2328.3956" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2328.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2286.2629,-262.636C2247.8608,-247.7209 2191.2128,-225.7192 2151.3664,-210.2431"/>
<polygon fill="#000000" stroke="#000000" points="2152.4612,-206.9137 2141.8724,-206.5557 2149.9268,-213.4388 2152.4612,-206.9137"/>
<text text-anchor="middle" x="2308.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- medical_history -->
<g id="node18" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2531.3956" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2531.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2494.3552,-262.7865C2466.7553,-251.356 2427.8678,-236.6057 2392.3956,-228 2319.8694,-210.4049 2234.8649,-201.1192 2176.0961,-196.4175"/>
<polygon fill="#000000" stroke="#000000" points="2176.0432,-192.903 2165.8026,-195.6194 2175.502,-199.882 2176.0432,-192.903"/>
<text text-anchor="middle" x="2506.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sequencing_file -->
<g id="node19" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1010.3956" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1010.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M980.0623,-349.1439C969.6311,-343.2216 957.9298,-336.4372 947.3956,-330 936.982,-323.6365 934.7644,-321.4363 924.3956,-315 915.866,-309.7053 906.5728,-304.1264 897.8706,-298.983"/>
<polygon fill="#000000" stroke="#000000" points="899.4672,-295.8616 889.0727,-293.8108 895.9196,-301.8961 899.4672,-295.8616"/>
<text text-anchor="middle" x="1013.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- laboratory_test -->
<g id="node20" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1466.3956" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1466.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1390.9752,-358.809C1329.0508,-352.2376 1246.6543,-341.7722 1215.3956,-330 1203.9747,-325.6988 1203.8869,-319.1095 1192.3956,-315 1143.2059,-297.4089 997.9073,-286.6448 917.8486,-281.8844"/>
<polygon fill="#000000" stroke="#000000" points="917.6612,-278.3676 907.4744,-281.2795 917.2536,-285.3558 917.6612,-278.3676"/>
<text text-anchor="middle" x="1280.8956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1486.0856,-348.2241C1491.279,-342.774 1496.5107,-336.4915 1500.3956,-330 1516.9957,-302.2624 1498.6097,-281.7509 1523.3956,-261 1561.8057,-228.8429 1886.0046,-205.2737 2032.7454,-196.1515"/>
<polygon fill="#000000" stroke="#000000" points="2033.2319,-199.6282 2042.9977,-195.5197 2032.8013,-192.6415 2033.2319,-199.6282"/>
<text text-anchor="middle" x="1588.8956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study_funding -->
<g id="node21" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="3591.3956" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="3591.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3560.5445,-88.4796C3537.4753,-76.8966 3504.8028,-62.0898 3474.3956,-54 3422.1841,-40.1091 3269.1426,-27.1999 3191.5847,-21.326"/>
<polygon fill="#000000" stroke="#000000" points="3191.8443,-17.8358 3181.6105,-20.5779 3191.3207,-24.8161 3191.8443,-17.8358"/>
<text text-anchor="middle" x="3579.3956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- clinical_measure_file -->
<g id="node22" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3201.3956" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3201.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3125.3841,-353.0838C3111.4521,-351.093 3097.013,-349.2777 3083.3956,-348 2323.729,-276.7201 2130.0738,-319.2742 1367.3956,-297 1203.6998,-292.2192 1010.1604,-284.8156 917.771,-281.1739"/>
<polygon fill="#000000" stroke="#000000" points="917.6777,-277.6676 907.5473,-280.77 917.4013,-284.6621 917.6777,-277.6676"/>
<text text-anchor="middle" x="2956.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge30" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3252.0895,-349.9815C3277.063,-339.2369 3304.8707,-322.3192 3319.3956,-297 3327.3573,-283.1215 3324.9063,-276.0211 3319.3956,-261 3291.7012,-185.5096 3247.8176,-189.3523 3202.3956,-123 3185.1226,-97.7677 3168.841,-66.7759 3158.1371,-45.0256"/>
<polygon fill="#000000" stroke="#000000" points="3161.1436,-43.2042 3153.6281,-35.7365 3154.8463,-46.261 3161.1436,-43.2042"/>
<text text-anchor="middle" x="3375.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3188.9869,-348.094C3171.5708,-324.3825 3137.5822,-283.0057 3098.3956,-261 3041.9011,-229.2748 3020.5965,-236.7388 2956.3956,-228 2806.7371,-207.629 2354.407,-196.8614 2176.9515,-193.3296"/>
<polygon fill="#000000" stroke="#000000" points="2176.9989,-189.8299 2166.9319,-193.1321 2176.8609,-196.8286 2176.9989,-189.8299"/>
<text text-anchor="middle" x="3229.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M837.002,-198.2009C821.3871,-203.3742 802.863,-212.485 793.3956,-228 783.9052,-243.5527 799.0817,-255.8083 817.7002,-264.4037"/>
<polygon fill="#000000" stroke="#000000" points="816.449,-267.6744 827.0237,-268.3276 819.1644,-261.2225 816.449,-267.6744"/>
<text text-anchor="middle" x="817.3956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M891.3738,-191.6753C1104.3223,-189.1045 2465.6363,-170.8716 2641.3956,-123 2674.0115,-114.1164 2676.9357,-99.369 2708.3956,-87 2762.27,-65.8184 2777.5021,-64.6881 2834.3956,-54 2927.564,-36.4973 3038.1355,-26.1338 3099.1523,-21.3058"/>
<polygon fill="#000000" stroke="#000000" points="3099.5325,-24.7869 3109.2315,-20.5231 3098.9905,-17.8079 3099.5325,-24.7869"/>
<text text-anchor="middle" x="2732.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- study_arm -->
<g id="node24" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="3746.3956" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="3746.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3720.9704,-88.5847C3701.2084,-76.7323 3672.6593,-61.5378 3645.3956,-54 3560.8669,-30.6298 3299.5406,-21.7444 3192.1775,-19.0216"/>
<polygon fill="#000000" stroke="#000000" points="3192.0598,-15.5177 3181.9765,-18.7698 3191.887,-22.5156 3192.0598,-15.5177"/>
<text text-anchor="middle" x="3730.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- consent_group -->
<g id="node25" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="2844.3956" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="2844.3956" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge2" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2839.3517,-86.796C2837.5316,-75.9565 2837.5524,-62.668 2845.3956,-54 2862.09,-35.55 3018.8246,-24.6737 3098.851,-20.2791"/>
<polygon fill="#000000" stroke="#000000" points="3099.3486,-23.7575 3109.1465,-19.7263 3098.9732,-16.7676 3099.3486,-23.7575"/>
<text text-anchor="middle" x="2908.8956" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- generic_file -->
<g id="node26" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2104.3956" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2104.3956" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2040.7184,-361.5359C1824.0282,-346.3449 1117.5938,-296.8205 916.9693,-282.7558"/>
<polygon fill="#000000" stroke="#000000" points="917.1888,-279.2627 906.9685,-282.0547 916.6992,-286.2455 917.1888,-279.2627"/>
<text text-anchor="middle" x="1611.3956" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge22" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2168.286,-361.85C2365.4044,-348.9237 2951.7893,-309.5037 2967.3956,-297 2989.7217,-279.1124 2986.3956,-264.108 2986.3956,-235.5 2986.3956,-235.5 2986.3956,-235.5 2986.3956,-105 2986.3956,-52.9654 3052.741,-31.8534 3099.7186,-23.4266"/>
<polygon fill="#000000" stroke="#000000" points="3100.4202,-26.8581 3109.7129,-21.7693 3099.275,-19.9524 3100.4202,-26.8581"/>
<text text-anchor="middle" x="3039.3956" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2104.3956,-347.7078C2104.3956,-317.3436 2104.3956,-256.3226 2104.3956,-220.3464"/>
<polygon fill="#000000" stroke="#000000" points="2107.8957,-220.0471 2104.3956,-210.0471 2100.8957,-220.0471 2107.8957,-220.0471"/>
<text text-anchor="middle" x="2157.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- survival -->
<g id="node27" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2682.3956" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2682.3956" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2657.4013,-263.3603C2636.976,-251.4302 2606.9182,-235.767 2578.3956,-228 2504.8451,-207.9714 2290.6208,-198.1025 2177.0464,-194.1599"/>
<polygon fill="#000000" stroke="#000000" points="2176.8245,-190.6504 2166.7112,-193.8079 2176.5862,-197.6464 2176.8245,-190.6504"/>
<text text-anchor="middle" x="2655.8956" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge18" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2166.7171,-190.7754C2300.3332,-187.7493 2610.5705,-178.4708 2713.3956,-156 2743.8403,-149.3468 2776.5049,-136.6427 2801.6009,-125.5791"/>
<polygon fill="#000000" stroke="#000000" points="2803.1397,-128.7248 2810.8282,-121.4352 2800.272,-122.3392 2803.1397,-128.7248"/>
<text text-anchor="middle" x="2811.8956" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
