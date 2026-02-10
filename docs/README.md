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
<svg width="4016pt" height="392pt"
 viewBox="0.00 0.00 4016.00 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 4011.9954,-388 4011.9954,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="3147.9954" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="3147.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- participant -->
<g id="node21" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="2252.9954" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="2252.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3112.0451,-266.9089C3073.8376,-254.6623 3011.4121,-236.3686 2955.9954,-228 2836.0992,-209.8942 2479.6685,-198.2268 2325.4485,-193.8955"/>
<polygon fill="#000000" stroke="#000000" points="2325.2371,-190.3883 2315.1435,-193.6085 2325.0422,-197.3856 2325.2371,-190.3883"/>
<text text-anchor="middle" x="3064.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- methylation_array_file -->
<g id="node2" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="407.9954" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="407.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="769.9954" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="769.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge44" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M413.5036,-347.8972C417.9532,-336.5184 425.414,-322.5998 436.9954,-315 459.7641,-300.059 627.5265,-287.7072 715.8867,-282.156"/>
<polygon fill="#000000" stroke="#000000" points="716.2309,-285.6414 725.9949,-281.5288 715.7973,-278.6549 716.2309,-285.6414"/>
<text text-anchor="middle" x="528.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- generic_file -->
<g id="node3" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="1193.9954" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="1193.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1148.8559,-352.8888C1126.3076,-346.2301 1098.6448,-337.896 1073.9954,-330 1054.3195,-323.6972 1050.0975,-319.7719 1029.9954,-315 959.7483,-298.3245 876.864,-288.5006 823.8917,-283.4347"/>
<polygon fill="#000000" stroke="#000000" points="823.9907,-279.9289 813.7087,-282.4844 823.3402,-286.8986 823.9907,-279.9289"/>
<text text-anchor="middle" x="1126.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="1227.9954" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="1227.9954" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge20" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1189.0354,-347.9625C1183.9349,-329.2651 1176.6452,-302.0653 1175.9954,-297 1164.1192,-204.4253 1146.3783,-175.5096 1175.9954,-87 1181.6571,-70.0803 1193.2834,-53.9876 1204.1094,-41.606"/>
<polygon fill="#000000" stroke="#000000" points="1206.8692,-43.7746 1211.0373,-34.0341 1201.7047,-39.0493 1206.8692,-43.7746"/>
<text text-anchor="middle" x="1215.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1259.8657,-365.061C1531.7906,-360.895 2555.147,-342.2528 2605.9954,-297 2629.0979,-276.4398 2635.7535,-250.9248 2614.9954,-228 2595.9634,-206.9814 2425.495,-197.7363 2325.4192,-194.0897"/>
<polygon fill="#000000" stroke="#000000" points="2325.4842,-190.5899 2315.3665,-193.7335 2325.2362,-197.5855 2325.4842,-190.5899"/>
<text text-anchor="middle" x="2679.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- synonym -->
<g id="node4" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="51.9954" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="51.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M84.1466,-351.6661C116.5382,-337.3339 162.9884,-317.1184 171.9954,-315 274.2877,-290.9411 587.6767,-282.4335 715.1782,-279.9167"/>
<polygon fill="#000000" stroke="#000000" points="715.551,-283.4103 725.4818,-279.7184 715.4163,-276.4116 715.551,-283.4103"/>
<text text-anchor="middle" x="214.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M83.1609,-351.5148C92.3033,-345.9344 101.5624,-338.7551 107.9954,-330 121.9132,-311.0583 121.9954,-302.5052 121.9954,-279 121.9954,-279 121.9954,-279 121.9954,-105 121.9954,-50.9887 971.3323,-24.8293 1181.4253,-19.1847"/>
<polygon fill="#000000" stroke="#000000" points="1181.6085,-22.6811 1191.5118,-18.9163 1181.4222,-15.6836 1181.6085,-22.6811"/>
<text text-anchor="middle" x="164.4954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M66.3552,-348.6145C76.7304,-337.2429 91.7328,-323.052 107.9954,-315 300.7253,-219.5745 370.035,-249.721 583.9954,-228 664.3146,-219.8461 1869.473,-198.6091 2180.3,-193.2449"/>
<polygon fill="#000000" stroke="#000000" points="2180.6039,-196.7403 2190.5421,-193.0683 2180.4832,-189.7413 2180.6039,-196.7403"/>
<text text-anchor="middle" x="283.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cytogenomic_file -->
<g id="node5" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="815.9954" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="815.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M786.9143,-348.9138C780.5417,-343.6974 774.6216,-337.3591 770.9954,-330 767.6046,-323.1187 766.3941,-315.0548 766.2765,-307.3966"/>
<polygon fill="#000000" stroke="#000000" points="769.7755,-307.4903 766.6916,-297.3543 762.7815,-307.2012 769.7755,-307.4903"/>
<text text-anchor="middle" x="842.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="3506.9954" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="3506.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge36" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3450.8802,-265.3872C3398.2936,-253.263 3317.3179,-236.2098 3245.9954,-228 3067.739,-207.4811 2523.4774,-196.5379 2325.7572,-193.1571"/>
<polygon fill="#000000" stroke="#000000" points="2325.5388,-189.653 2315.4809,-192.9829 2325.4201,-196.652 2325.5388,-189.653"/>
<text text-anchor="middle" x="3406.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- cell_line -->
<g id="node12" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="860.9954" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="860.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M803.6159,-267.0497C815.9968,-261.3182 829.3396,-253.3943 838.9954,-243 845.061,-236.4705 849.6143,-228.0084 852.9568,-219.8601"/>
<polygon fill="#000000" stroke="#000000" points="856.3311,-220.8219 856.4536,-210.2277 849.7513,-218.4332 856.3311,-220.8219"/>
<text text-anchor="middle" x="886.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M811.0418,-272.2104C843.1418,-266.2778 888.6099,-256.4934 926.9954,-243 941.4351,-237.9241 943.1253,-231.6268 957.9954,-228 1017.5624,-213.4718 1915.4644,-197.5703 2180.1162,-193.179"/>
<polygon fill="#000000" stroke="#000000" points="2180.44,-196.6742 2190.3807,-193.0092 2180.3241,-189.6752 2180.44,-196.6742"/>
<text text-anchor="middle" x="994.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node28" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="632.9954" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="632.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge26" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M733.0731,-269.0081C715.4217,-263.1558 694.5794,-254.6008 677.9954,-243 667.7723,-235.8488 658.3226,-225.9133 650.7492,-216.7098"/>
<polygon fill="#000000" stroke="#000000" points="653.2819,-214.2679 644.3532,-208.5643 647.7763,-218.591 653.2819,-214.2679"/>
<text text-anchor="middle" x="714.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_surgery -->
<g id="node8" class="node">
<title>treatment_surgery</title>
<ellipse fill="none" stroke="#000000" cx="3708.9954" cy="-279" rx="98.5829" ry="18"/>
<text text-anchor="middle" x="3708.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_surgery</text>
</g>
<!-- treatment_surgery&#45;&gt;participant -->
<g id="edge43" class="edge">
<title>treatment_surgery&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3654.6657,-263.9055C3608.3769,-251.7823 3539.8766,-235.5747 3478.9954,-228 3253.8451,-199.9872 2554.0087,-193.666 2325.7758,-192.3341"/>
<polygon fill="#000000" stroke="#000000" points="2325.6098,-188.8332 2315.59,-192.2761 2325.5699,-195.8331 2325.6098,-188.8332"/>
<text text-anchor="middle" x="3639.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_surgery</text>
</g>
<!-- study_arm -->
<g id="node9" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="758.9954" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="758.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M753.8226,-86.6768C751.9541,-75.7925 751.9691,-62.4988 759.9954,-54 774.3229,-38.8291 1065.4004,-24.8858 1181.135,-19.92"/>
<polygon fill="#000000" stroke="#000000" points="1181.6056,-23.4032 1191.4478,-19.4814 1181.3081,-16.4096 1181.6056,-23.4032"/>
<text text-anchor="middle" x="808.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- clinical_measure_file -->
<g id="node10" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="3231.9954" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="3231.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3143.2403,-355.6152C3033.7963,-343.3249 2841.9964,-323.4624 2676.9954,-315 1940.5865,-277.2319 1754.7326,-327.704 1017.9954,-297 950.8103,-294.2 873.5668,-288.1432 823.3798,-283.8296"/>
<polygon fill="#000000" stroke="#000000" points="823.6695,-280.3416 813.4045,-282.9645 823.0647,-287.3155 823.6695,-280.3416"/>
<text text-anchor="middle" x="2960.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge33" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3337.2042,-361.3855C3510.2542,-352.3724 3835.9954,-328.7934 3835.9954,-279 3835.9954,-279 3835.9954,-279 3835.9954,-105 3835.9954,-38.2864 1626.7529,-20.6788 1274.9599,-18.298"/>
<polygon fill="#000000" stroke="#000000" points="1274.8861,-14.7975 1264.8629,-18.2304 1274.8392,-21.7973 1274.8861,-14.7975"/>
<text text-anchor="middle" x="3921.9954" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge32" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3232.3107,-347.977C3231.7283,-324.8977 3227.2543,-285.0239 3204.9954,-261 3174.0458,-227.5963 3152.756,-236.3766 3107.9954,-228 2958.9228,-200.1023 2503.8287,-193.8052 2325.634,-192.3989"/>
<polygon fill="#000000" stroke="#000000" points="2325.6,-188.8986 2315.5736,-192.3224 2325.5467,-195.8984 2325.6,-188.8986"/>
<text text-anchor="middle" x="3309.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- study_funding -->
<g id="node11" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="1046.9954" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="1046.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1034.6102,-86.7651C1029.0892,-76.1826 1025.3597,-63.1744 1032.9954,-54 1051.4869,-31.7822 1129.6285,-23.2221 1181.2047,-19.9619"/>
<polygon fill="#000000" stroke="#000000" points="1181.68,-23.4402 1191.458,-19.3608 1181.2703,-16.4522 1181.68,-23.4402"/>
<text text-anchor="middle" x="1094.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M818.9541,-201.4636C793.8445,-208.0623 765.4237,-217.5347 757.9954,-228 753.1295,-234.8553 753.341,-243.4079 755.5981,-251.5389"/>
<polygon fill="#000000" stroke="#000000" points="752.3911,-252.9563 759.1619,-261.1053 758.9507,-250.5126 752.3911,-252.9563"/>
<text text-anchor="middle" x="798.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge6" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M858.7379,-173.7533C856.9466,-150.4321 857.7184,-110.2971 879.9954,-87 920.9093,-44.2126 1096.6018,-26.7775 1181.5908,-20.7464"/>
<polygon fill="#000000" stroke="#000000" points="1181.9986,-24.2267 1191.7355,-20.0502 1181.5193,-17.2432 1181.9986,-24.2267"/>
<text text-anchor="middle" x="920.4954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- genetic_analysis -->
<g id="node13" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2926.9954" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2926.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2856.5531,-355.1881C2836.0994,-352.415 2813.6967,-349.73 2792.9954,-348 2006.5224,-282.2757 1806.3109,-334.6578 1017.9954,-297 950.8285,-293.7914 873.5811,-287.8232 823.3882,-283.6417"/>
<polygon fill="#000000" stroke="#000000" points="823.6694,-280.153 813.4117,-282.8043 823.0839,-287.1285 823.6694,-280.153"/>
<text text-anchor="middle" x="2602.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2925.0468,-347.6287C2921.4881,-323.7877 2911.6479,-282.6828 2884.9954,-261 2842.2152,-226.1967 2481.0235,-203.6799 2324.6695,-195.4781"/>
<polygon fill="#000000" stroke="#000000" points="2324.8407,-191.9824 2314.6725,-194.9586 2324.4773,-198.973 2324.8407,-191.9824"/>
<text text-anchor="middle" x="2979.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1237.9954" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1237.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1272.0567,-265.1269C1303.8008,-252.9115 1352.7576,-235.8768 1396.9954,-228 1546.4818,-201.383 2001.9657,-194.3239 2180.3013,-192.5564"/>
<polygon fill="#000000" stroke="#000000" points="2180.4038,-196.0557 2190.3696,-192.4593 2180.3363,-189.056 2180.4038,-196.0557"/>
<text text-anchor="middle" x="1440.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="197.9954" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="197.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M224.1005,-348.8661C243.3962,-337.1417 270.7648,-322.4244 296.9954,-315 374.2593,-293.1309 608.2724,-283.69 715.3967,-280.4327"/>
<polygon fill="#000000" stroke="#000000" points="715.7741,-283.9231 725.6658,-280.1276 715.5662,-276.9262 715.7741,-283.9231"/>
<text text-anchor="middle" x="357.9954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_personnel -->
<g id="node17" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1271.9954" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1271.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge37" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1262.8786,-86.9735C1256.7021,-74.7609 1248.4338,-58.4123 1241.4973,-44.697"/>
<polygon fill="#000000" stroke="#000000" points="1244.5864,-43.0498 1236.95,-35.7057 1238.3399,-46.209 1244.5864,-43.0498"/>
<text text-anchor="middle" x="1322.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- family_relationship -->
<g id="node18" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1408.9954" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1408.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1442.234,-261.9659C1467.0848,-250.1275 1502.2733,-235.2263 1534.9954,-228 1656.3368,-201.203 2023.328,-194.3123 2180.3984,-192.5732"/>
<polygon fill="#000000" stroke="#000000" points="2180.4739,-196.0727 2190.4359,-192.4659 2180.3991,-189.0731 2180.4739,-196.0727"/>
<text text-anchor="middle" x="1614.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_chemotherapy -->
<g id="node19" class="node">
<title>treatment_chemotherapy</title>
<ellipse fill="none" stroke="#000000" cx="1655.9954" cy="-279" rx="129.1772" ry="18"/>
<text text-anchor="middle" x="1655.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_chemotherapy</text>
</g>
<!-- treatment_chemotherapy&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment_chemotherapy&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1674.1627,-261.0033C1687.1579,-249.359 1705.7011,-235.0931 1724.9954,-228 1766.6512,-212.6861 2046.2023,-199.9812 2180.816,-194.6706"/>
<polygon fill="#000000" stroke="#000000" points="2181.1796,-198.1591 2191.0351,-194.2706 2180.9058,-191.1645 2181.1796,-198.1591"/>
<text text-anchor="middle" x="1826.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_chemotherapy</text>
</g>
<!-- publication -->
<g id="node20" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1439.9954" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1439.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge31" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1429.0737,-87.2326C1421.2396,-75.9955 1409.6768,-62.1087 1395.9954,-54 1375.6084,-41.917 1315.8052,-30.9642 1273.3712,-24.3938"/>
<polygon fill="#000000" stroke="#000000" points="1273.6729,-20.8996 1263.261,-22.8597 1272.6227,-27.8204 1273.6729,-20.8996"/>
<text text-anchor="middle" x="1463.9954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- consent_group -->
<g id="node26" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1912.9954" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1912.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge29" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M2206.0768,-179.9944C2146.2104,-164.6756 2042.452,-138.1257 1975.8098,-121.0731"/>
<polygon fill="#000000" stroke="#000000" points="1976.4066,-117.6131 1965.8511,-118.5248 1974.6713,-124.3946 1976.4066,-117.6131"/>
<text text-anchor="middle" x="2153.4954" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- radiology_file -->
<g id="node22" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1876.9954" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1876.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1900.9866,-261.9528C1918.4525,-250.4286 1943.1318,-235.9183 1966.9954,-228 2005.7026,-215.1564 2111.0486,-204.0748 2182.4918,-197.7175"/>
<polygon fill="#000000" stroke="#000000" points="2183.1194,-201.1759 2192.7747,-196.8142 2182.5067,-194.2028 2183.1194,-201.1759"/>
<text text-anchor="middle" x="2025.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_status -->
<g id="node23" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="1590.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1590.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- study_status&#45;&gt;study -->
<g id="edge13" class="edge">
<title>study_status&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1572.0656,-87.6C1558.3696,-76.0679 1538.8491,-61.6935 1518.9954,-54 1475.483,-37.1386 1345.0429,-25.9642 1274.5015,-20.9792"/>
<polygon fill="#000000" stroke="#000000" points="1274.3494,-17.4603 1264.1313,-20.2605 1273.8653,-24.4436 1274.3494,-17.4603"/>
<text text-anchor="middle" x="1602.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_status</text>
</g>
<!-- treatment_radiation -->
<g id="node24" class="node">
<title>treatment_radiation</title>
<ellipse fill="none" stroke="#000000" cx="2072.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2072.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_radiation</text>
</g>
<!-- treatment_radiation&#45;&gt;participant -->
<g id="edge38" class="edge">
<title>treatment_radiation&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2079.4039,-260.8723C2084.2314,-249.7801 2091.9324,-236.1907 2102.9954,-228 2116.7085,-217.8472 2153.9325,-208.8825 2187.8653,-202.4384"/>
<polygon fill="#000000" stroke="#000000" points="2188.594,-205.8631 2197.792,-200.6051 2187.3226,-198.9795 2188.594,-205.8631"/>
<text text-anchor="middle" x="2185.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_radiation</text>
</g>
<!-- treatment_response -->
<g id="node25" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2299.9954" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2299.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2290.257,-260.9735C2283.703,-248.8418 2274.9442,-232.6287 2267.5653,-218.9698"/>
<polygon fill="#000000" stroke="#000000" points="2270.5538,-217.138 2262.7213,-210.0034 2264.3951,-220.4652 2270.5538,-217.138"/>
<text text-anchor="middle" x="2361.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge30" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1858.2102,-91.8705C1807.7772,-80.2511 1730.7459,-63.6792 1662.9954,-54 1522.4588,-33.9223 1354.6582,-23.9513 1274.7569,-20.047"/>
<polygon fill="#000000" stroke="#000000" points="1274.6927,-16.54 1264.5367,-19.5574 1274.3577,-23.532 1274.6927,-16.54"/>
<text text-anchor="middle" x="1808.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_other -->
<g id="node27" class="node">
<title>treatment_other</title>
<ellipse fill="none" stroke="#000000" cx="2509.9954" cy="-279" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2509.9954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_other</text>
</g>
<!-- treatment_other&#45;&gt;participant -->
<g id="edge39" class="edge">
<title>treatment_other&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2493.5527,-261.1473C2482.1424,-249.8742 2465.9887,-235.9793 2448.9954,-228 2426.5561,-217.4635 2367.8196,-207.4423 2320.4554,-200.6612"/>
<polygon fill="#000000" stroke="#000000" points="2320.9286,-197.1934 2310.5381,-199.2644 2319.9522,-204.125 2320.9286,-197.1934"/>
<text text-anchor="middle" x="2541.4954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_other</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M612.0565,-203.9381C596.6062,-214.264 580.0219,-229.5999 590.9954,-243 606.6187,-262.0782 669.3673,-271.2638 716.1898,-275.5346"/>
<polygon fill="#000000" stroke="#000000" points="715.9512,-279.0269 726.2145,-276.3972 716.5514,-272.0527 715.9512,-279.0269"/>
<text text-anchor="middle" x="614.9954" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge4" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M628.9447,-173.8071C624.9816,-150.9122 622.0958,-111.6142 641.9954,-87 673.5502,-47.9692 700.669,-63.2748 749.9954,-54 831.8352,-38.6117 1077.8377,-25.2823 1181.3213,-20.197"/>
<polygon fill="#000000" stroke="#000000" points="1181.6489,-23.6852 1191.4666,-19.7024 1181.308,-16.6936 1181.6489,-23.6852"/>
<text text-anchor="middle" x="665.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- diagnosis -->
<g id="node29" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1008.9954" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1008.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M977.398,-351.1714C964.6731,-344.95 949.9667,-337.4403 936.9954,-330 926.4092,-323.9279 925.1809,-319.8808 913.9954,-315 884.4405,-302.1039 849.3732,-293.2137 821.2438,-287.4944"/>
<polygon fill="#000000" stroke="#000000" points="821.7038,-284.0181 811.2173,-285.5293 820.3574,-290.8874 821.7038,-284.0181"/>
<text text-anchor="middle" x="981.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1016.7977,-347.997C1028.327,-323.7744 1052.3527,-281.3827 1086.9954,-261 1183.2113,-204.3897 1224.7689,-237.5331 1335.9954,-228 1649.452,-201.1339 2024.9282,-194.2948 2180.2521,-192.5719"/>
<polygon fill="#000000" stroke="#000000" points="2180.6447,-196.068 2190.6066,-192.4611 2180.5697,-189.0684 2180.6447,-196.068"/>
<text text-anchor="middle" x="1131.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node30" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="624.9954" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="624.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M622.0003,-347.9719C621.2641,-337.1986 622.3547,-323.918 629.9954,-315 641.513,-301.5571 682.8517,-291.9977 717.6467,-286.124"/>
<polygon fill="#000000" stroke="#000000" points="718.4126,-289.5457 727.7246,-284.4921 717.2936,-282.6357 718.4126,-289.5457"/>
<text text-anchor="middle" x="696.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_admin -->
<g id="node31" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3933.9954" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3933.9954" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge35" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3912.7109,-87.6456C3896.5784,-75.648 3873.2803,-60.6879 3849.9954,-54 3785.6095,-35.507 1621.9761,-20.5803 1274.7878,-18.3016"/>
<polygon fill="#000000" stroke="#000000" points="1274.609,-14.8004 1264.5863,-18.2348 1274.5631,-21.8003 1274.609,-14.8004"/>
<text text-anchor="middle" x="3938.4954" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- laboratory_test -->
<g id="node32" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="2701.9954" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="2701.9954" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge41" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2620.4613,-363.5704C2376.9403,-356.1178 1633.6724,-331.9478 1017.9954,-297 950.86,-293.1892 873.6057,-287.3516 823.4027,-283.3647"/>
<polygon fill="#000000" stroke="#000000" points="823.6708,-279.8751 813.424,-282.5683 823.1138,-286.8529 823.6708,-279.8751"/>
<text text-anchor="middle" x="1730.4954" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge42" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2718.6571,-348.3535C2737.3192,-326.3785 2762.5488,-288.3978 2742.9954,-261 2716.7863,-224.2762 2691.1109,-237.4539 2646.9954,-228 2587.3779,-215.224 2420.9665,-202.8548 2324.5515,-196.4724"/>
<polygon fill="#000000" stroke="#000000" points="2324.5075,-192.9621 2314.2995,-195.7989 2324.0485,-199.947 2324.5075,-192.9621"/>
<text text-anchor="middle" x="2815.4954" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
