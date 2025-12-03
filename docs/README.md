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
<svg width="3958pt" height="392pt"
 viewBox="0.00 0.00 3958.09 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3954.0923,-388 3954.0923,4 -4,4"/>
<!-- study_personnel -->
<g id="node1" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="87.0923" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="87.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study -->
<g id="node20" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="680.0923" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="680.0923" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M81.8717,-86.6313C79.9852,-75.7299 79.9981,-62.4341 88.0923,-54 106.897,-34.4055 496.8813,-22.655 633.3952,-19.1296"/>
<polygon fill="#000000" stroke="#000000" points="633.6301,-22.6248 643.5375,-18.8708 633.4515,-15.6271 633.6301,-22.6248"/>
<text text-anchor="middle" x="157.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="2191.0923" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="2191.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node26" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1935.0923" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1935.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2172.8894,-262.2489C2159.5202,-250.8643 2140.3948,-236.399 2121.0923,-228 2084.7212,-212.174 2041.3413,-203.2697 2005.6273,-198.2777"/>
<polygon fill="#000000" stroke="#000000" points="2005.6618,-194.7519 1995.2893,-196.9109 2004.7442,-201.6915 2005.6618,-194.7519"/>
<text text-anchor="middle" x="2184.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="317.0923" cy="-366" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="317.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample -->
<g id="node13" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="814.0923" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="814.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M341.0308,-356.5549C371.6236,-344.8865 426.4527,-325.317 475.0923,-315 574.1521,-293.9884 692.2263,-284.9821 759.6497,-281.3193"/>
<polygon fill="#000000" stroke="#000000" points="760.2218,-284.7943 770.0252,-280.7764 759.8559,-277.8039 760.2218,-284.7943"/>
<text text-anchor="middle" x="499.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge36" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M295.922,-353.91C273.4343,-339.3111 241.0923,-312.4929 241.0923,-279 241.0923,-279 241.0923,-279 241.0923,-105 241.0923,-72.8551 280.3437,-69.3964 342.0923,-54 396.2063,-40.5072 554.6685,-27.3138 633.8915,-21.3332"/>
<polygon fill="#000000" stroke="#000000" points="634.3556,-24.8083 644.0665,-20.5719 633.8332,-17.8278 634.3556,-24.8083"/>
<text text-anchor="middle" x="265.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1798.0923" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1798.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1745.011,-351.4963C1690.9511,-336.7757 1614.0779,-316.0037 1607.0923,-315 1445.3708,-291.7633 1033.3168,-323.4656 872.0923,-297 867.0837,-296.1778 861.9079,-295.0284 856.8047,-293.7037"/>
<polygon fill="#000000" stroke="#000000" points="857.7184,-290.325 847.1439,-290.9806 855.8192,-297.0624 857.7184,-290.325"/>
<text text-anchor="middle" x="1733.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1802.711,-347.8769C1809.9894,-319.7443 1823.8395,-268.0488 1829.0923,-261 1844.9356,-239.7395 1869.416,-223.184 1890.8608,-211.6251"/>
<polygon fill="#000000" stroke="#000000" points="1892.5621,-214.6856 1899.8316,-206.9781 1889.3423,-208.4701 1892.5621,-214.6856"/>
<text text-anchor="middle" x="1899.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- pathology_file -->
<g id="node5" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="814.0923" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="814.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M814.0923,-347.9735C814.0923,-336.1918 814.0923,-320.5607 814.0923,-307.1581"/>
<polygon fill="#000000" stroke="#000000" points="817.5924,-307.0033 814.0923,-297.0034 810.5924,-307.0034 817.5924,-307.0033"/>
<text text-anchor="middle" x="875.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_arm -->
<g id="node6" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="329.0923" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="329.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M336.0102,-86.8663C341.3481,-75.4745 349.8995,-61.553 362.0923,-54 384.6834,-40.0056 551.1137,-26.8219 633.7741,-21.0532"/>
<polygon fill="#000000" stroke="#000000" points="634.1675,-24.5344 643.9027,-20.3542 633.6855,-17.551 634.1675,-24.5344"/>
<text text-anchor="middle" x="410.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- study_funding -->
<g id="node7" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="484.0923" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="484.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge9" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M470.6231,-86.7958C464.5564,-76.2242 460.3088,-63.2167 468.0923,-54 478.6868,-41.4547 574.85,-29.1496 633.9634,-22.6799"/>
<polygon fill="#000000" stroke="#000000" points="634.6163,-26.1299 644.1839,-21.5789 633.8665,-19.1702 634.6163,-26.1299"/>
<text text-anchor="middle" x="530.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- treatment_response -->
<g id="node8" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2362.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2362.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2325.0374,-262.1174C2298.5584,-250.7473 2261.7966,-236.3539 2228.0923,-228 2153.9105,-209.6135 2066.7315,-200.4322 2006.8687,-195.9707"/>
<polygon fill="#000000" stroke="#000000" points="2006.9869,-192.4702 1996.7613,-195.2429 2006.4841,-199.4522 2006.9869,-192.4702"/>
<text text-anchor="middle" x="2356.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- synonym -->
<g id="node9" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="470.0923" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="470.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M493.5731,-349.8221C511.531,-338.2539 537.3364,-323.3149 562.0923,-315 597.9079,-302.9704 698.2948,-290.9508 761.0223,-284.294"/>
<polygon fill="#000000" stroke="#000000" points="761.5507,-287.7579 771.1307,-283.2331 760.82,-280.7961 761.5507,-287.7579"/>
<text text-anchor="middle" x="604.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge40" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M484.7894,-348.3825C494.6645,-337.4938 508.5019,-323.9395 523.0923,-315 543.9458,-302.223 559.3985,-315.7571 575.0923,-297 635.7191,-224.5389 564.3576,-170.7466 608.0923,-87 618.0327,-67.9654 635.242,-51.1783 650.3433,-38.9291"/>
<polygon fill="#000000" stroke="#000000" points="652.7209,-41.5134 658.4565,-32.6053 648.4176,-35.9924 652.7209,-41.5134"/>
<text text-anchor="middle" x="641.5923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge41" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M474.8927,-347.6445C478.4517,-337.0193 484.2445,-324.0085 493.0923,-315 556.4776,-250.4631 589.1232,-249.075 677.0923,-228 792.0308,-200.4638 1611.3795,-193.7576 1862.2672,-192.3413"/>
<polygon fill="#000000" stroke="#000000" points="1862.3887,-195.8408 1872.3691,-192.2854 1862.3499,-188.8409 1862.3887,-195.8408"/>
<text text-anchor="middle" x="603.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1615.0923" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1615.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1580.9688,-351.8899C1549.4363,-339.6022 1500.9723,-322.5998 1457.0923,-315 1200.785,-270.609 1128.6464,-339.9413 872.0923,-297 867.2764,-296.1939 862.3048,-295.0904 857.3915,-293.8235"/>
<polygon fill="#000000" stroke="#000000" points="858.0301,-290.3676 847.4564,-291.0362 856.1392,-297.1074 858.0301,-290.3676"/>
<text text-anchor="middle" x="1558.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1623.7925,-347.76C1629.2758,-337.4299 1637.0258,-324.6799 1646.0923,-315 1653.2357,-307.3732 1713.7433,-265.6684 1723.0923,-261 1772.5666,-236.295 1832.8491,-217.6742 1876.4665,-206.0412"/>
<polygon fill="#000000" stroke="#000000" points="1877.5582,-209.3733 1886.3429,-203.4504 1875.782,-202.6024 1877.5582,-209.3733"/>
<text text-anchor="middle" x="1767.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node11" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="2756.0923" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="2756.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2694.1387,-263.134C2646.1507,-251.49 2577.8335,-236.3125 2517.0923,-228 2334.9664,-203.0758 2118.3954,-195.3973 2007.8725,-193.0392"/>
<polygon fill="#000000" stroke="#000000" points="2007.9054,-189.5392 1997.8357,-192.8335 2007.7619,-196.5377 2007.9054,-189.5392"/>
<text text-anchor="middle" x="2705.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- treatment_other -->
<g id="node12" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2990.0923" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2990.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2946.2455,-263.3568C2910.4049,-251.34 2858.1505,-235.5613 2811.0923,-228 2657.2203,-203.276 2189.0112,-195.0712 2007.7963,-192.7776"/>
<polygon fill="#000000" stroke="#000000" points="2007.6143,-189.2752 1997.5716,-192.6506 2007.5273,-196.2746 2007.6143,-189.2752"/>
<text text-anchor="middle" x="2944.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M770.5103,-282.1632C649.4771,-290.9479 318.0923,-315 318.0923,-315 312.2864,-321.1211 310.6631,-329.7491 310.9135,-338.1705"/>
<polygon fill="#000000" stroke="#000000" points="307.4386,-338.5919 311.993,-348.1579 314.3981,-337.8397 307.4386,-338.5919"/>
<text text-anchor="middle" x="354.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node22" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="781.0923" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="781.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M772.468,-272.8107C739.2586,-266.9211 696.6165,-256.8925 686.0923,-243 670.9604,-223.0253 697.6312,-209.9952 726.5236,-202.1088"/>
<polygon fill="#000000" stroke="#000000" points="727.5104,-205.4696 736.3499,-199.6289 725.7974,-198.6824 727.5104,-205.4696"/>
<text text-anchor="middle" x="722.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M835.6488,-263.2763C855.7901,-248.6562 883.1893,-228.9791 886.0923,-228 932.2196,-212.442 1632.4138,-197.7708 1862.4637,-193.3487"/>
<polygon fill="#000000" stroke="#000000" points="1862.8025,-196.8429 1872.7336,-193.1521 1862.6685,-189.8442 1862.8025,-196.8429"/>
<text text-anchor="middle" x="922.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node14" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1024.0923" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1024.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M992.2789,-348.645C981.9309,-342.8567 970.4477,-336.28 960.0923,-330 949.6572,-323.6717 948.2155,-320.0212 937.0923,-315 909.7709,-302.6668 900.8547,-305.4434 872.0923,-297 867.8229,-295.7467 863.3848,-294.4174 858.9498,-293.0713"/>
<polygon fill="#000000" stroke="#000000" points="859.8988,-289.7015 849.3122,-290.1204 857.8493,-296.3948 859.8988,-289.7015"/>
<text text-anchor="middle" x="1051.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- publication -->
<g id="node15" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="680.0923" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="680.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge22" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M680.0923,-86.9735C680.0923,-75.1918 680.0923,-59.5607 680.0923,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="683.5924,-46.0033 680.0923,-36.0034 676.5924,-46.0034 683.5924,-46.0033"/>
<text text-anchor="middle" x="731.0923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- cytogenomic_file -->
<g id="node16" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="630.0923" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="630.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M639.0031,-347.8619C645.3587,-336.7656 654.9259,-323.1755 667.0923,-315 682.7407,-304.4846 727.0392,-294.4457 762.949,-287.6535"/>
<polygon fill="#000000" stroke="#000000" points="763.628,-291.0874 772.8242,-285.8262 762.3543,-284.2042 763.628,-291.0874"/>
<text text-anchor="middle" x="738.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- study_admin -->
<g id="node17" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="831.0923" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="831.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge5" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M818.7773,-86.7768C810.6233,-75.9301 799.0646,-62.6408 786.0923,-54 767.4117,-41.5569 744.0132,-33.0141 723.9552,-27.3849"/>
<polygon fill="#000000" stroke="#000000" points="724.6768,-23.9554 714.1138,-24.7765 722.8833,-30.7217 724.6768,-23.9554"/>
<text text-anchor="middle" x="858.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_status -->
<g id="node18" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="3775.0923" cy="-366" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3775.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="3148.0923" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="3148.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3118.261,-263.9123C3092.475,-251.7055 3053.8264,-235.3756 3018.0923,-228 2919.9379,-207.7408 2234.7575,-196.2647 2007.8703,-192.9873"/>
<polygon fill="#000000" stroke="#000000" points="2007.7867,-189.4858 1997.7375,-192.842 2007.6863,-196.4851 2007.7867,-189.4858"/>
<text text-anchor="middle" x="3108.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- treatment_surgery -->
<g id="node21" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="3318.0923" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="3318.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3276.9116,-262.5641C3244.6233,-250.5331 3198.2502,-235.1167 3156.0923,-228 3043.2887,-208.9576 2253.2008,-196.4402 2007.6988,-192.9767"/>
<polygon fill="#000000" stroke="#000000" points="2007.5088,-189.4738 1997.4606,-192.833 2007.4105,-196.4731 2007.5088,-189.4738"/>
<text text-anchor="middle" x="3292.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M778.4573,-210.0592C777.7189,-220.0924 778.0247,-232.6094 782.0923,-243 783.6697,-247.0297 785.9171,-250.9013 788.499,-254.5141"/>
<polygon fill="#000000" stroke="#000000" points="785.9317,-256.9034 794.973,-262.4267 791.3494,-252.4707 785.9317,-256.9034"/>
<text text-anchor="middle" x="822.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge24" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M820.7091,-181.2089C850.0888,-171.0842 888.6226,-152.9219 910.0923,-123 928.1217,-97.8727 939.2663,-77.4404 919.0923,-54 906.7182,-39.6225 792.58,-27.5946 726.6141,-21.7704"/>
<polygon fill="#000000" stroke="#000000" points="726.7287,-18.2672 716.4635,-20.8895 726.1234,-25.241 726.7287,-18.2672"/>
<text text-anchor="middle" x="968.5923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- medical_history -->
<g id="node23" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1128.0923" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1128.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1150.1381,-261.391C1166.2765,-249.602 1189.2578,-235.0061 1212.0923,-228 1273.0242,-209.3048 1691.3675,-197.6333 1862.4327,-193.5931"/>
<polygon fill="#000000" stroke="#000000" points="1862.6865,-197.0882 1872.6018,-193.3551 1862.5226,-190.0902 1862.6865,-197.0882"/>
<text text-anchor="middle" x="1280.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- generic_file -->
<g id="node24" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2503.0923" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2503.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2440.7703,-360.3007C2319.0836,-349.4239 2041.2815,-325.8266 1807.0923,-315 1599.4977,-305.4029 1077.2514,-330.1263 872.0923,-297 867.0816,-296.1909 861.9044,-295.0496 856.8005,-293.7297"/>
<polygon fill="#000000" stroke="#000000" points="857.7131,-290.3506 847.1389,-291.0115 855.8172,-297.089 857.7131,-290.3506"/>
<text text-anchor="middle" x="2109.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2568.1897,-363.1362C2772.983,-353.8659 3392.5557,-323.7274 3426.0923,-297 3448.4645,-279.1702 3445.0923,-264.108 3445.0923,-235.5 3445.0923,-235.5 3445.0923,-235.5 3445.0923,-105 3445.0923,-34.0714 1089.3754,-19.9587 726.7179,-18.2063"/>
<polygon fill="#000000" stroke="#000000" points="726.5907,-14.7058 716.5741,-18.158 726.5573,-21.7057 726.5907,-14.7058"/>
<text text-anchor="middle" x="3498.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2502.2321,-347.8341C2499.5443,-315.3372 2488.4883,-248.7138 2443.0923,-228 2404.5213,-210.4004 2138.5764,-198.9645 2007.6255,-194.3358"/>
<polygon fill="#000000" stroke="#000000" points="2007.4069,-190.8261 1997.2908,-193.9747 2007.1624,-197.8218 2007.4069,-190.8261"/>
<text text-anchor="middle" x="2546.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- treatment_radiation -->
<g id="node25" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="1336.0923" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1336.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1342.4308,-260.9332C1347.4877,-249.4157 1355.787,-235.3247 1368.0923,-228 1409.5807,-203.3039 1719.2942,-195.3256 1862.6603,-192.939"/>
<polygon fill="#000000" stroke="#000000" points="1862.7472,-196.4381 1872.6892,-192.7767 1862.6338,-189.439 1862.7472,-196.4381"/>
<text text-anchor="middle" x="1451.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- consent_group -->
<g id="node29" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1464.0923" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1464.0923" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1882.4336,-182.2732C1797.694,-166.6207 1630.9398,-135.819 1535.5461,-118.1985"/>
<polygon fill="#000000" stroke="#000000" points="1536.1627,-114.7532 1525.6933,-116.3785 1534.8912,-121.6368 1536.1627,-114.7532"/>
<text text-anchor="middle" x="1777.5923" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- family_relationship -->
<g id="node27" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1559.0923" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1559.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1545.6562,-261.064C1539.3483,-250.3254 1534.8364,-237.0489 1543.0923,-228 1564.1487,-204.9212 1755.1132,-196.4449 1862.525,-193.4852"/>
<polygon fill="#000000" stroke="#000000" points="1862.747,-196.9806 1872.6503,-193.2157 1862.5607,-189.9831 1862.747,-196.9806"/>
<text text-anchor="middle" x="1622.5923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- sequencing_file -->
<g id="node28" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1241.0923" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1241.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1204.7452,-349.7222C1192.3083,-343.8462 1178.4266,-336.9433 1166.0923,-330 1155.4575,-324.0134 1154.6686,-318.8634 1143.0923,-315 1028.5907,-276.7867 990.7728,-319.0406 872.0923,-297 867.2915,-296.1084 862.3296,-294.9504 857.4218,-293.6514"/>
<polygon fill="#000000" stroke="#000000" points="858.0693,-290.1968 847.4932,-290.8274 856.1542,-296.9297 858.0693,-290.1968"/>
<text text-anchor="middle" x="1232.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge42" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1392.7873,-97.0873C1234.3874,-79.5098 856.887,-37.6188 725.8406,-23.0767"/>
<polygon fill="#000000" stroke="#000000" points="726.0704,-19.5808 715.7454,-21.9564 725.2983,-26.5381 726.0704,-19.5808"/>
<text text-anchor="middle" x="1181.5923" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- radiology_file -->
<g id="node30" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2051.0923" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2051.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2028.1744,-261.8116C2010.2645,-248.3792 1985.2058,-229.5852 1965.5998,-214.8807"/>
<polygon fill="#000000" stroke="#000000" points="1967.6679,-212.0567 1957.5678,-208.8567 1963.4678,-217.6567 1967.6679,-212.0567"/>
<text text-anchor="middle" x="2058.0923" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- clinical_measure_file -->
<g id="node31" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3578.0923" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3578.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3472.7241,-361.3941C3238.0848,-351.3131 2654.6972,-327.2208 2166.0923,-315 2022.3455,-311.4047 1014.1061,-319.5416 872.0923,-297 867.0795,-296.2043 861.9009,-295.0714 856.7963,-293.7561"/>
<polygon fill="#000000" stroke="#000000" points="857.7077,-290.3768 847.1338,-291.0429 855.8152,-297.1161 857.7077,-290.3768"/>
<text text-anchor="middle" x="2718.0923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3641.099,-351.3249C3699.7229,-335.786 3778.0923,-309.3394 3778.0923,-279 3778.0923,-279 3778.0923,-279 3778.0923,-105 3778.0923,-25.1648 1113.8733,-18.5819 726.7688,-18.0467"/>
<polygon fill="#000000" stroke="#000000" points="726.5017,-14.5465 716.4971,-18.0332 726.4925,-21.5465 726.5017,-14.5465"/>
<text text-anchor="middle" x="3864.0923" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3560.2581,-348.2271C3527.194,-316.6796 3452.6572,-251.9639 3375.0923,-228 3309.3392,-207.6854 2291.7091,-195.6868 2008.017,-192.7249"/>
<polygon fill="#000000" stroke="#000000" points="2007.8747,-189.2234 1997.8389,-192.6193 2007.802,-196.223 2007.8747,-189.2234"/>
<text text-anchor="middle" x="3585.0923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- laboratory_test -->
<g id="node32" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1445.0923" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1445.0923" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1388.1126,-353.0605C1366.8884,-347.28 1342.9109,-339.5811 1322.0923,-330 1311.0059,-324.8979 1310.7145,-318.7231 1299.0923,-315 1208.6466,-286.0262 965.6718,-313.2105 872.0923,-297 867.2811,-296.1666 862.3125,-295.0456 857.4008,-293.7684"/>
<polygon fill="#000000" stroke="#000000" points="858.0422,-290.3129 847.4677,-290.9694 856.1436,-297.0505 858.0422,-290.3129"/>
<text text-anchor="middle" x="1387.5923" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1454.6958,-347.6785C1458.9356,-336.7947 1461.3197,-323.5011 1453.0923,-315 1410.57,-271.0634 945.6145,-340.9366 903.0923,-297 891.9651,-285.5027 892.4791,-272.9733 903.0923,-261 934.912,-225.1023 1632.8394,-201.0528 1862.5309,-194.0875"/>
<polygon fill="#000000" stroke="#000000" points="1862.8956,-197.5782 1872.7856,-193.7784 1862.6847,-190.5813 1862.8956,-197.5782"/>
<text text-anchor="middle" x="968.5923" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
