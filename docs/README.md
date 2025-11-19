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
<svg width="2970pt" height="392pt"
 viewBox="0.00 0.00 2969.79 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 2965.7947,-388 2965.7947,4 -4,4"/>
<!-- medical_history -->
<g id="node1" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2064.7947" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2064.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1493.7947" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1493.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2011.8233,-264.748C1967.4932,-253.298 1902.4201,-237.5955 1844.7947,-228 1748.6148,-211.9846 1636.3437,-201.9676 1565.1738,-196.6811"/>
<polygon fill="#000000" stroke="#000000" points="1565.207,-193.1743 1554.9783,-195.9353 1564.6963,-200.1556 1565.207,-193.1743"/>
<text text-anchor="middle" x="1985.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="59.7947" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="59.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="758.7947" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="758.7947" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M54.5469,-86.6051C52.6501,-75.6937 52.6618,-62.3968 60.7947,-54 83.4406,-30.6193 558.6129,-21.1401 711.7106,-18.6856"/>
<polygon fill="#000000" stroke="#000000" points="712.2228,-22.1781 722.1664,-18.5209 712.1125,-15.1789 712.2228,-22.1781"/>
<text text-anchor="middle" x="109.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1709.7947" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1709.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1767.1938,-353.103C1789.1084,-346.9177 1810.3895,-338.913 1816.7947,-330 1825.9427,-317.2703 1841.884,-267.0116 1799.7947,-228 1782.9245,-212.3634 1650.5788,-201.487 1565.551,-196.0332"/>
<polygon fill="#000000" stroke="#000000" points="1565.6277,-192.5312 1555.4273,-195.395 1565.1873,-199.5173 1565.6277,-192.5312"/>
<text text-anchor="middle" x="1892.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="729.7947" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="729.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1633.1876,-359.4569C1516.3548,-349.4458 1306.6598,-331.3371 1302.7947,-330 1291.2613,-326.01 1291.4072,-318.7534 1279.7947,-315 1199.353,-289 984.0871,-303.4534 899.7947,-297 860.3722,-293.9818 815.9433,-289.2304 782.3942,-285.3671"/>
<polygon fill="#000000" stroke="#000000" points="782.6865,-281.8776 772.3493,-284.1995 781.8783,-288.8308 782.6865,-281.8776"/>
<text text-anchor="middle" x="1368.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- consent_group -->
<g id="node29" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="758.7947" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="758.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge40" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1432.9876,-187.4063C1318.1842,-178.3127 1061.8237,-156.0003 847.7947,-123 840.9906,-121.9509 833.9178,-120.7359 826.8661,-119.4421"/>
<polygon fill="#000000" stroke="#000000" points="827.0592,-115.9168 816.5834,-117.5004 825.7603,-122.7952 827.0592,-115.9168"/>
<text text-anchor="middle" x="1145.2947" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genetic_analysis -->
<g id="node5" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="2022.7947" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="2022.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2072.1827,-351.0546C2122.0521,-333.3333 2187.867,-301.0836 2158.7947,-261 2131.0683,-222.7721 2104.1711,-236.9081 2057.7947,-228 1965.7398,-210.3179 1696.9003,-198.9758 1566.4596,-194.3601"/>
<polygon fill="#000000" stroke="#000000" points="1566.2893,-190.8521 1556.1729,-193.9999 1566.0443,-197.8478 1566.2893,-190.8521"/>
<text text-anchor="middle" x="2235.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1941.9011,-358.9614C1899.8369,-355.4229 1847.5694,-351.2155 1800.7947,-348 1659.1257,-338.2612 1621.5133,-355.3705 1481.7947,-330 1459.8036,-326.0068 1455.8297,-318.7437 1433.7947,-315 1316.738,-295.1124 1018.2414,-305.2563 899.7947,-297 860.3526,-294.2507 815.9245,-289.4884 782.3806,-285.5526"/>
<polygon fill="#000000" stroke="#000000" points="782.6803,-282.0637 772.3375,-284.3609 781.8553,-289.0149 782.6803,-282.0637"/>
<text text-anchor="middle" x="1551.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M765.6073,-268.451C807.6391,-256.5325 879.6322,-237.5543 942.7947,-228 1033.1198,-214.3369 1294.3508,-201.0644 1421.9497,-195.1738"/>
<polygon fill="#000000" stroke="#000000" points="1422.1873,-198.6667 1432.0162,-194.7117 1421.8662,-191.6741 1422.1873,-198.6667"/>
<text text-anchor="middle" x="979.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- cell_line -->
<g id="node12" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="502.7947" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="502.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge32" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M693.4584,-268.6439C682.9764,-265.8955 671.483,-263.1094 660.7947,-261 631.5341,-255.2253 551.9857,-260.445 527.7947,-243 519.8067,-237.2395 514.2463,-228.2113 510.4352,-219.3418"/>
<polygon fill="#000000" stroke="#000000" points="513.7092,-218.104 506.9542,-209.9419 507.1449,-220.535 513.7092,-218.104"/>
<text text-anchor="middle" x="564.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node16" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="613.7947" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="613.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge33" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M692.6151,-269.0918C658.0258,-259.6978 611.4153,-246.5138 608.7947,-243 603.8582,-236.3809 603.1584,-227.8578 604.272,-219.6813"/>
<polygon fill="#000000" stroke="#000000" points="607.7421,-220.1973 606.4702,-209.6791 600.9052,-218.6948 607.7421,-220.1973"/>
<text text-anchor="middle" x="645.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- generic_file -->
<g id="node7" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="194.7947" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="194.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge25" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M208.0857,-348.2629C217.0971,-337.3266 229.8698,-323.7641 243.7947,-315 308.7407,-274.1244 332.8596,-277.5385 407.7947,-261 475.0857,-246.1486 494.8884,-259.4983 561.7947,-243 579.8258,-238.5538 582.6076,-231.7574 600.7947,-228 680.0461,-211.6267 1223.1829,-198.0315 1421.5026,-193.5603"/>
<polygon fill="#000000" stroke="#000000" points="1421.6112,-197.0588 1431.5302,-193.3354 1421.4542,-190.0606 1421.6112,-197.0588"/>
<text text-anchor="middle" x="460.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge23" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M216.4348,-348.8772C232.8102,-336.9947 256.4046,-322.0772 279.7947,-315 360.9235,-290.4528 577.0006,-309.7667 660.7947,-297 668.5396,-295.82 676.6717,-294.1235 684.5264,-292.238"/>
<polygon fill="#000000" stroke="#000000" points="685.4399,-295.6172 694.2772,-289.7731 683.7243,-288.8307 685.4399,-295.6172"/>
<text text-anchor="middle" x="332.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge24" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M187.136,-348.0349C180.4453,-330.693 171.7947,-303.5282 171.7947,-279 171.7947,-279 171.7947,-279 171.7947,-105 171.7947,-50.4664 573.344,-26.6266 712.2114,-20.0126"/>
<polygon fill="#000000" stroke="#000000" points="712.6927,-23.494 722.5182,-19.5305 712.3656,-16.5016 712.6927,-23.494"/>
<text text-anchor="middle" x="224.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_status -->
<g id="node8" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2558.7947" cy="-366" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2558.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- treatment_response -->
<g id="node9" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="2656.7947" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="2656.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2592.7148,-264.7494C2536.0001,-252.7658 2450.8252,-236.2995 2375.7947,-228 2219.7413,-210.7382 1748.475,-198.0465 1566.5455,-193.6673"/>
<polygon fill="#000000" stroke="#000000" points="1566.3628,-190.162 1556.2819,-193.4217 1566.1953,-197.16 1566.3628,-190.162"/>
<text text-anchor="middle" x="2558.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="330.7947" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="330.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M346.0011,-348.4062C356.9665,-336.9418 372.7821,-322.7253 389.7947,-315 442.1029,-291.2471 462.8485,-313.771 517.7947,-297 552.7758,-286.3229 557.1237,-272.6449 591.7947,-261 630.8772,-247.8734 643.9757,-256.8867 682.7947,-243 696.0874,-238.2448 697.1843,-231.7503 710.7947,-228 778.0772,-209.4603 1240.3258,-197.5166 1421.3324,-193.5028"/>
<polygon fill="#000000" stroke="#000000" points="1421.6304,-196.9972 1431.551,-193.278 1421.4764,-189.9989 1421.6304,-196.9972"/>
<text text-anchor="middle" x="634.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M354.0252,-349.5914C372.1272,-337.7425 398.3756,-322.5495 423.7947,-315 525.0595,-284.9242 556.6013,-314.4025 660.7947,-297 668.3512,-295.7379 676.2863,-294.0342 683.9754,-292.1761"/>
<polygon fill="#000000" stroke="#000000" points="685.0529,-295.5139 693.8894,-289.6687 683.3364,-288.7276 685.0529,-295.5139"/>
<text text-anchor="middle" x="466.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M337.4544,-347.9469C343.2724,-330.5412 350.7947,-303.3321 350.7947,-279 350.7947,-279 350.7947,-279 350.7947,-105 350.7947,-68.3332 606.0992,-35.2364 712.7954,-23.0056"/>
<polygon fill="#000000" stroke="#000000" points="713.4035,-26.4592 722.945,-21.8539 712.6141,-19.5038 713.4035,-26.4592"/>
<text text-anchor="middle" x="393.2947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge16" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M464.0635,-203.2297C430.1434,-213.1535 386.0453,-226.3109 384.7947,-228 380.8276,-233.3579 380.2366,-238.135 384.7947,-243 405.8064,-265.4266 630.4562,-256.0992 660.7947,-261 668.3578,-262.2217 676.2963,-263.9046 683.9869,-265.7543"/>
<polygon fill="#000000" stroke="#000000" points="683.349,-269.203 693.9016,-268.2572 685.0625,-262.4159 683.349,-269.203"/>
<text text-anchor="middle" x="425.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge15" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M501.5681,-173.9124C501.0283,-150.7632 503.721,-110.814 525.7947,-87 551.279,-59.5065 653.6705,-36.9324 713.9075,-25.6974"/>
<polygon fill="#000000" stroke="#000000" points="714.7106,-29.1086 723.9155,-23.8627 713.4483,-22.2234 714.7106,-29.1086"/>
<text text-anchor="middle" x="566.2947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- family_relationship -->
<g id="node13" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1008.7947" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1008.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1012.0931,-260.8932C1015.1704,-249.5127 1020.986,-235.5938 1031.7947,-228 1062.8487,-206.1825 1299.1296,-196.969 1421.2237,-193.6325"/>
<polygon fill="#000000" stroke="#000000" points="1421.3401,-197.1307 1431.243,-193.3649 1421.1531,-190.1332 1421.3401,-197.1307"/>
<text text-anchor="middle" x="1111.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2361.7947" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2361.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2358.1569,-347.898C2352.3413,-323.9645 2338.5442,-282.3369 2309.7947,-261 2250.8005,-217.2165 1755.1117,-199.1536 1566.3707,-193.8201"/>
<polygon fill="#000000" stroke="#000000" points="1566.3629,-190.3186 1556.2692,-193.5386 1566.1678,-197.3159 1566.3629,-190.3186"/>
<text text-anchor="middle" x="2423.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2262.9044,-358.4632C2219.068,-355.169 2166.864,-351.31 2119.7947,-348 1898.5224,-332.4398 1843.3834,-325.0997 1621.7947,-315 1301.139,-300.385 1220.1011,-317.916 899.7947,-297 860.2067,-294.4149 815.611,-289.6218 782.0307,-285.6314"/>
<polygon fill="#000000" stroke="#000000" points="782.3272,-282.1419 771.9806,-284.4221 781.4908,-289.0918 782.3272,-282.1419"/>
<text text-anchor="middle" x="1956.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge13" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2441.8346,-353.7233C2556.6985,-335.9283 2756.1756,-304.2932 2770.7947,-297 2781.2035,-291.8072 2789.7947,-290.6322 2789.7947,-279 2789.7947,-279 2789.7947,-279 2789.7947,-105 2789.7947,-53.635 1109.3128,-23.7305 805.5627,-18.7447"/>
<polygon fill="#000000" stroke="#000000" points="805.399,-15.2417 795.3431,-18.5779 805.2846,-22.2408 805.399,-15.2417"/>
<text text-anchor="middle" x="2875.7947" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- pathology_file -->
<g id="node15" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1107.7947" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1107.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1078.2787,-349.2783C1067.9364,-343.3094 1056.287,-336.4616 1045.7947,-330 1035.4031,-323.6005 1034.2585,-319.1856 1022.7947,-315 1011.6712,-310.9386 863.8547,-293.9736 782.5422,-284.8564"/>
<polygon fill="#000000" stroke="#000000" points="782.8171,-281.3654 772.4899,-283.7312 782.0385,-288.3219 782.8171,-281.3654"/>
<text text-anchor="middle" x="1106.7947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M637.8605,-201.1822C652.5483,-207.4533 671.236,-216.6706 685.7947,-228 695.0264,-235.184 703.7617,-244.5406 710.9789,-253.275"/>
<polygon fill="#000000" stroke="#000000" points="708.4425,-255.7094 717.4,-261.3674 713.926,-251.3583 708.4425,-255.7094"/>
<text text-anchor="middle" x="724.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge28" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M610.382,-173.9309C607.184,-151.5199 605.1978,-113.0894 622.7947,-87 644.0356,-55.5078 684.1847,-37.6422 715.3765,-28.0208"/>
<polygon fill="#000000" stroke="#000000" points="716.5274,-31.3312 725.1536,-25.1799 714.5742,-24.6093 716.5274,-31.3312"/>
<text text-anchor="middle" x="646.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- radiology_file -->
<g id="node17" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1200.7947" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1200.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1195.7607,-260.8049C1193.9443,-249.9687 1193.9655,-236.6807 1201.7947,-228 1216.332,-211.8816 1340.2998,-201.2964 1421.9686,-196.0027"/>
<polygon fill="#000000" stroke="#000000" points="1422.4456,-199.4796 1432.2035,-195.3525 1422.0017,-192.4936 1422.4456,-199.4796"/>
<text text-anchor="middle" x="1260.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- diagnosis -->
<g id="node18" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1434.7947" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1434.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1487.7453,-361.3137C1529.6237,-356.381 1583.2287,-346.9116 1596.7947,-330 1600.9662,-324.7997 1601.3391,-319.8778 1596.7947,-315 1558.2225,-273.5976 1381.3669,-338.4024 1342.7947,-297 1306.5824,-258.1306 1381.2173,-225.4347 1437.9149,-207.3053"/>
<polygon fill="#000000" stroke="#000000" points="1439.0417,-210.6203 1447.5499,-204.3067 1436.9615,-203.9364 1439.0417,-210.6203"/>
<text text-anchor="middle" x="1387.2947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1382.2097,-360.9076C1321.2611,-354.5399 1224.8301,-342.8963 1190.7947,-330 1179.3824,-325.6758 1179.3696,-318.8677 1167.7947,-315 1111.1819,-296.083 959.2624,-302.1434 899.7947,-297 860.4039,-293.5931 815.9737,-288.8575 782.4161,-285.0988"/>
<polygon fill="#000000" stroke="#000000" points="782.6974,-281.6084 772.3683,-283.9662 781.9133,-288.5644 782.6974,-281.6084"/>
<text text-anchor="middle" x="1235.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- exposure -->
<g id="node19" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1493.7947" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1493.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1493.7947,-260.9735C1493.7947,-249.1918 1493.7947,-233.5607 1493.7947,-220.1581"/>
<polygon fill="#000000" stroke="#000000" points="1497.2948,-220.0033 1493.7947,-210.0034 1490.2948,-220.0034 1497.2948,-220.0033"/>
<text text-anchor="middle" x="1537.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- sequencing_file -->
<g id="node20" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="483.7947" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="483.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M496.1996,-347.8977C505.026,-336.5192 517.9258,-322.6007 532.7947,-315 583.9475,-288.8517 604.4622,-308.2694 660.7947,-297 668.2226,-295.514 676.0415,-293.7101 683.6403,-291.8251"/>
<polygon fill="#000000" stroke="#000000" points="684.6279,-295.1853 693.4513,-289.3203 682.8963,-288.4028 684.6279,-295.1853"/>
<text text-anchor="middle" x="599.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node21" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="674.7947" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="674.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M670.2208,-347.962C668.6129,-337.6993 668.3629,-324.9493 673.7947,-315 677.611,-308.0098 683.43,-302.1745 689.8972,-297.3787"/>
<polygon fill="#000000" stroke="#000000" points="691.8871,-300.2593 698.3337,-291.8514 688.0509,-294.4041 691.8871,-300.2593"/>
<text text-anchor="middle" x="745.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- treatment -->
<g id="node22" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="1622.7947" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="1622.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge26" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1612.8296,-260.9326C1606.1075,-250.1445 1596.3661,-236.8621 1584.7947,-228 1574.1535,-219.8503 1561.4288,-213.3047 1548.9154,-208.1486"/>
<polygon fill="#000000" stroke="#000000" points="1550.0146,-204.821 1539.4255,-204.4729 1547.4863,-211.3485 1550.0146,-204.821"/>
<text text-anchor="middle" x="1645.7947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study_funding -->
<g id="node23" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="933.7947" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="933.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge30" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M922.3658,-86.9951C914.4758,-75.9519 903.0413,-62.371 889.7947,-54 864.0956,-37.7599 831.0671,-28.7472 804.604,-23.801"/>
<polygon fill="#000000" stroke="#000000" points="804.8963,-20.2995 794.4452,-22.0388 803.6999,-27.1965 804.8963,-20.2995"/>
<text text-anchor="middle" x="968.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- methylation_array_file -->
<g id="node24" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="897.7947" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="897.7947" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M869.3949,-348.5484C859.9495,-342.6974 849.3935,-336.1079 839.7947,-330 829.4984,-323.4483 827.5906,-320.6909 816.7947,-315 802.8135,-307.63 786.9831,-300.6918 772.6946,-294.9106"/>
<polygon fill="#000000" stroke="#000000" points="773.6767,-291.5349 763.0907,-291.1019 771.0961,-298.0419 773.6767,-291.5349"/>
<text text-anchor="middle" x="931.2947" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- study_admin -->
<g id="node25" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="1099.7947" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="1099.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge36" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1082.7285,-87.3663C1070.5081,-75.8839 1053.0457,-61.6626 1034.7947,-54 994.4054,-37.0428 872.7946,-26.048 805.2629,-21.0753"/>
<polygon fill="#000000" stroke="#000000" points="805.1353,-17.5571 794.9095,-20.329 804.6319,-24.539 805.1353,-17.5571"/>
<text text-anchor="middle" x="1117.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- publication -->
<g id="node26" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="1250.7947" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="1250.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge8" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1231.9465,-87.6189C1218.0679,-75.9373 1198.1433,-61.3761 1177.7947,-54 1110.3938,-29.5679 899.8215,-21.4354 805.4086,-18.9727"/>
<polygon fill="#000000" stroke="#000000" points="805.3787,-15.4709 795.2941,-18.719 805.2032,-22.4687 805.3787,-15.4709"/>
<text text-anchor="middle" x="1256.7947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- survival -->
<g id="node27" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1746.7947" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1746.7947" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1734.3652,-261.5709C1725.2764,-250.1799 1711.9294,-235.9836 1696.7947,-228 1673.8409,-215.8918 1611.7567,-205.9499 1562.2375,-199.6052"/>
<polygon fill="#000000" stroke="#000000" points="1562.5567,-196.1178 1552.1987,-198.3455 1561.6851,-203.0634 1562.5567,-196.1178"/>
<text text-anchor="middle" x="1756.2947" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_personnel -->
<g id="node28" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="1418.7947" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="1418.7947" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge21" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1390.4155,-87.8006C1369.4808,-76.0445 1339.873,-61.3162 1311.7947,-54 1216.6589,-29.2112 920.9857,-21.0578 805.5926,-18.7774"/>
<polygon fill="#000000" stroke="#000000" points="805.3893,-15.273 795.324,-18.5807 805.2551,-22.2717 805.3893,-15.273"/>
<text text-anchor="middle" x="1420.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge11" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M758.7947,-86.9735C758.7947,-75.1918 758.7947,-59.5607 758.7947,-46.1581"/>
<polygon fill="#000000" stroke="#000000" points="762.2948,-46.0033 758.7947,-36.0034 755.2948,-46.0034 762.2948,-46.0033"/>
<text text-anchor="middle" x="822.2947" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
</g>
</svg>
</div>
