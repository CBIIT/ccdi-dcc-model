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
<svg width="3096pt" height="392pt"
 viewBox="0.00 0.00 3096.34 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3092.3431,-388 3092.3431,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1263.3431" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1263.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1602.3431" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1602.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1248.0777,-260.7181C1241.1319,-250.1189 1236.1035,-237.1097 1244.3431,-228 1263.0859,-207.278 1430.4988,-197.9366 1529.6158,-194.1899"/>
<polygon fill="#000000" stroke="#000000" points="1530.008,-197.6779 1539.8727,-193.8129 1529.7508,-190.6827 1530.008,-197.6779"/>
<text text-anchor="middle" x="1327.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="653.3431" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="653.3431" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- pathology_file -->
<g id="node3" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="332.3431" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="332.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- sample -->
<g id="node19" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="748.3431" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="748.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M357.1828,-348.8637C375.2538,-337.2974 400.7631,-322.7735 425.3431,-315 474.1259,-299.5723 615.8944,-287.9361 694.4188,-282.4621"/>
<polygon fill="#000000" stroke="#000000" points="694.8625,-285.9399 704.5989,-281.7623 694.3824,-278.9564 694.8625,-285.9399"/>
<text text-anchor="middle" x="486.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- study_funding -->
<g id="node4" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="77.3431" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="77.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M87.8947,-87.0723C95.7911,-75.4588 107.7256,-61.2014 122.3431,-54 165.1798,-32.8963 485.0918,-22.4007 606.6587,-19.1422"/>
<polygon fill="#000000" stroke="#000000" points="606.8666,-22.6381 616.7709,-18.8757 606.6821,-15.6405 606.8666,-22.6381"/>
<text text-anchor="middle" x="184.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- publication -->
<g id="node5" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="235.3431" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="235.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge23" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M240.4599,-86.8528C244.671,-75.4554 251.8554,-61.5326 263.3431,-54 291.4948,-35.5408 509.4726,-24.0978 606.7422,-19.8621"/>
<polygon fill="#000000" stroke="#000000" points="607.0381,-23.3527 616.8791,-19.4278 606.7384,-16.3591 607.0381,-23.3527"/>
<text text-anchor="middle" x="314.3431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="1548.3431" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="1548.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1569.361,-349.3864C1583.8883,-338.4999 1604.0083,-324.5665 1623.3431,-315 1646.0177,-303.7811 1660.2355,-315.6367 1677.3431,-297 1698.446,-274.0109 1707.7372,-253.909 1690.3431,-228 1683.8674,-218.3542 1674.3007,-211.2911 1663.8322,-206.1197"/>
<polygon fill="#000000" stroke="#000000" points="1665.0218,-202.8206 1654.4554,-202.0448 1662.2318,-209.2405 1665.0218,-202.8206"/>
<text text-anchor="middle" x="1742.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1514.5149,-351.6837C1483.7883,-339.4375 1436.8983,-322.6193 1394.3431,-315 1280.3097,-294.5828 988.7338,-307.2709 873.3431,-297 848.9126,-294.8254 821.9643,-291.1142 799.3639,-287.6246"/>
<polygon fill="#000000" stroke="#000000" points="799.7329,-284.1396 789.3105,-286.0431 798.6451,-291.0546 799.7329,-284.1396"/>
<text text-anchor="middle" x="1494.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group -->
<g id="node26" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1417.3431" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1417.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge19" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1569.6947,-176.6464C1539.4485,-162.4225 1494.24,-141.1623 1460.9214,-125.4935"/>
<polygon fill="#000000" stroke="#000000" points="1462.4002,-122.3213 1451.8614,-121.2329 1459.4212,-128.6558 1462.4002,-122.3213"/>
<text text-anchor="middle" x="1570.8431" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- laboratory_test -->
<g id="node8" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="1178.3431" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="1178.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge35" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1196.0128,-348.3147C1204.5396,-337.6704 1211.1972,-324.405 1202.3431,-315 1156.8678,-266.695 949.8185,-345.305 904.3431,-297 893.3758,-285.3502 893.8942,-273.1169 904.3431,-261 944.6727,-214.2324 1359.3668,-198.257 1529.8048,-193.6397"/>
<polygon fill="#000000" stroke="#000000" points="1530.0355,-197.1349 1539.9391,-193.3708 1529.8497,-190.1374 1530.0355,-197.1349"/>
<text text-anchor="middle" x="969.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1127.488,-351.7961C1109.3682,-345.9832 1089.0693,-338.5895 1071.3431,-330 1060.3606,-324.6782 1059.8477,-319.0722 1048.3431,-315 974.6361,-288.9106 950.9429,-306.574 873.3431,-297 849.1893,-294.02 822.4809,-290.2401 799.9743,-286.9143"/>
<polygon fill="#000000" stroke="#000000" points="800.3597,-283.4332 789.9533,-285.4227 799.329,-290.3569 800.3597,-283.4332"/>
<text text-anchor="middle" x="1136.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- exposure -->
<g id="node9" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="1615.3431" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="1615.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1608.1461,-260.9604C1606.2119,-255.3023 1604.3726,-248.973 1603.3431,-243 1602.0754,-235.6446 1601.534,-227.6046 1601.3781,-220.1279"/>
<polygon fill="#000000" stroke="#000000" points="1604.878,-220.0637 1601.3789,-210.0634 1597.878,-220.0631 1604.878,-220.0637"/>
<text text-anchor="middle" x="1646.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- study_admin -->
<g id="node10" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="386.3431" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="386.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M374.5406,-87.0691C369.0821,-76.3324 365.3769,-63.056 373.3431,-54 388.4925,-36.7782 531.2024,-25.4935 606.8199,-20.6715"/>
<polygon fill="#000000" stroke="#000000" points="607.262,-24.1508 617.0243,-20.0341 606.8255,-17.1645 607.262,-24.1508"/>
<text text-anchor="middle" x="429.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="186.3431" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="186.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge16" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M210.8421,-349.9458C227.3385,-339.4321 249.759,-325.7078 270.3431,-315 287.9982,-305.8159 296.0995,-309.7938 311.3431,-297 361.6685,-254.7626 346.2074,-219.7697 393.3431,-174 429.4401,-138.9491 541.7481,-79.1203 585.3431,-54 596.0852,-47.8102 607.9763,-41.3767 618.7712,-35.6899"/>
<polygon fill="#000000" stroke="#000000" points="620.6773,-38.6429 627.9191,-30.9094 617.4353,-32.4389 620.6773,-38.6429"/>
<text text-anchor="middle" x="435.8431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M202.1648,-348.606C212.7156,-337.8065 227.3564,-324.2676 242.3431,-315 333.5314,-258.6102 362.2722,-249.3354 467.3431,-228 570.7999,-206.9924 1295.6789,-195.9368 1529.6899,-192.886"/>
<polygon fill="#000000" stroke="#000000" points="1529.8435,-196.3844 1539.7974,-192.7553 1529.7529,-189.385 1529.8435,-196.3844"/>
<text text-anchor="middle" x="383.8431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge18" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M218.4533,-351.7291C252.0125,-336.837 300.1302,-315.5589 302.3431,-315 375.0689,-296.6329 591.8753,-285.4904 693.9974,-281.1246"/>
<polygon fill="#000000" stroke="#000000" points="694.259,-284.6168 704.1028,-280.6988 693.9642,-277.623 694.259,-284.6168"/>
<text text-anchor="middle" x="344.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- cytogenomic_file -->
<g id="node12" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="765.3431" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="765.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge20" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M755.5716,-347.7992C753.0543,-342.2419 750.6799,-336.0086 749.3431,-330 747.7222,-322.7143 747.0602,-314.698 746.9014,-307.222"/>
<polygon fill="#000000" stroke="#000000" points="750.4017,-307.167 746.9644,-297.1452 743.4018,-307.1231 750.4017,-307.167"/>
<text text-anchor="middle" x="820.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node13" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="536.3431" cy="-192" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="536.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge39" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M539.9379,-174.0085C544.9572,-152.0174 555.6236,-114.3593 574.3431,-87 587.3029,-68.0588 606.6494,-51.0441 622.953,-38.6497"/>
<polygon fill="#000000" stroke="#000000" points="625.1806,-41.3558 631.1515,-32.6036 621.026,-35.722 625.1806,-41.3558"/>
<text text-anchor="middle" x="614.8431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge40" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M547.9411,-209.7527C556.2072,-220.9836 568.3127,-234.869 582.3431,-243 601.4946,-254.0988 655.269,-264.5603 696.4738,-271.3153"/>
<polygon fill="#000000" stroke="#000000" points="695.9544,-274.7767 706.3833,-272.9089 697.0659,-267.8655 695.9544,-274.7767"/>
<text text-anchor="middle" x="622.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- clinical_measure_file -->
<g id="node14" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="1829.3431" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="1829.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1937.676,-364.2896C2160.8132,-359.8091 2655.8435,-344.5702 2715.3431,-297 2737.6877,-279.1355 2734.3431,-264.108 2734.3431,-235.5 2734.3431,-235.5 2734.3431,-235.5 2734.3431,-105 2734.3431,-52.3169 1008.8347,-23.4411 700.2766,-18.6986"/>
<polygon fill="#000000" stroke="#000000" points="699.9555,-15.1934 689.9031,-18.5401 699.8485,-22.1926 699.9555,-15.1934"/>
<text text-anchor="middle" x="2820.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1827.3265,-347.6242C1823.865,-324.5361 1814.7348,-285.0341 1791.3431,-261 1759.1136,-227.8852 1709.724,-210.5695 1669.5158,-201.5671"/>
<polygon fill="#000000" stroke="#000000" points="1670.0147,-198.0953 1659.5072,-199.4529 1668.5679,-204.9442 1670.0147,-198.0953"/>
<text text-anchor="middle" x="1899.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1759.0723,-352.2243C1688.3599,-338.5872 1584.1108,-319.1589 1543.3431,-315 1246.996,-284.7682 1170.1545,-322.2714 873.3431,-297 848.8097,-294.9112 821.7462,-291.1911 799.0935,-287.673"/>
<polygon fill="#000000" stroke="#000000" points="799.4453,-284.1851 789.0208,-286.0773 798.35,-291.0989 799.4453,-284.1851"/>
<text text-anchor="middle" x="1719.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- family_relationship -->
<g id="node15" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="2119.3431" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="2119.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge29" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2051.4035,-265.7717C1995.6077,-255.0703 1914.4749,-239.8811 1843.3431,-228 1784.5202,-218.1749 1717.4005,-208.2539 1668.9592,-201.3221"/>
<polygon fill="#000000" stroke="#000000" points="1669.3096,-197.8367 1658.9155,-199.8894 1668.321,-204.7665 1669.3096,-197.8367"/>
<text text-anchor="middle" x="2005.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- study_arm -->
<g id="node16" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="779.3431" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="779.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge34" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M755.3469,-88.4312C734.7977,-74.2424 705.1209,-53.7513 683.0706,-38.5261"/>
<polygon fill="#000000" stroke="#000000" points="684.9495,-35.5702 674.7318,-32.7684 680.9721,-41.3305 684.9495,-35.5702"/>
<text text-anchor="middle" x="772.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sequencing_file -->
<g id="node17" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="956.3431" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="956.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M936.199,-348.3882C921.1504,-335.5362 901.6416,-319.5942 892.3431,-315 863.5363,-300.7669 828.63,-291.8584 800.3996,-286.4641"/>
<polygon fill="#000000" stroke="#000000" points="800.7894,-282.9777 790.3246,-284.6324 799.5373,-289.8648 800.7894,-282.9777"/>
<text text-anchor="middle" x="980.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- study_personnel -->
<g id="node18" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="944.3431" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="944.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge24" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M910.401,-88.3109C886.9595,-77.3215 854.8171,-63.2988 825.3431,-54 783.1066,-40.6747 733.4624,-30.8857 698.3939,-24.9073"/>
<polygon fill="#000000" stroke="#000000" points="698.8958,-21.4428 688.456,-23.2486 697.7433,-28.3473 698.8958,-21.4428"/>
<text text-anchor="middle" x="935.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M774.1275,-264.239C799.3819,-249.9078 835.1005,-230.0218 842.3431,-228 907.359,-209.8508 1353.0838,-197.733 1530.1018,-193.5857"/>
<polygon fill="#000000" stroke="#000000" points="1530.1865,-197.0848 1540.1024,-193.3532 1530.0237,-190.0867 1530.1865,-197.0848"/>
<text text-anchor="middle" x="878.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge14" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M704.5105,-276.3444C631.1903,-271.4514 490.1955,-259.9395 475.3431,-243 464.67,-230.827 476.579,-219.1036 492.6193,-209.9727"/>
<polygon fill="#000000" stroke="#000000" points="494.5799,-212.8982 501.8384,-205.1804 491.3512,-206.6873 494.5799,-212.8982"/>
<text text-anchor="middle" x="511.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="674.3431" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="674.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge13" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M741.9159,-260.7617C737.6902,-250.4323 731.4402,-237.6823 723.3431,-228 717.6971,-221.2485 710.5313,-215.0763 703.4345,-209.822"/>
<polygon fill="#000000" stroke="#000000" points="705.4338,-206.9493 695.2304,-204.096 701.4275,-212.6894 705.4338,-206.9493"/>
<text text-anchor="middle" x="769.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge21" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M670.7541,-173.9057C668.1085,-160.0253 664.5929,-140.3638 662.3431,-123 658.9999,-97.1968 656.5938,-67.6592 655.1153,-46.499"/>
<polygon fill="#000000" stroke="#000000" points="658.5899,-46.0039 654.4266,-36.2614 651.6057,-46.4737 658.5899,-46.0039"/>
<text text-anchor="middle" x="686.3431" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge22" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M668.3795,-209.8328C666.0231,-220.2728 665.1528,-233.2723 671.3431,-243 678.0279,-253.5046 688.6706,-260.9954 699.9362,-266.318"/>
<polygon fill="#000000" stroke="#000000" points="698.8959,-269.6764 709.4726,-270.2975 701.5918,-263.2163 698.8959,-269.6764"/>
<text text-anchor="middle" x="695.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- treatment -->
<g id="node21" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="2295.3431" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="2295.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge31" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2253.5745,-266.3258C2212.2697,-254.3487 2147.0542,-236.9254 2089.3431,-228 1943.229,-205.4024 1770.1844,-196.8865 1674.7095,-193.7534"/>
<polygon fill="#000000" stroke="#000000" points="1674.6931,-190.2512 1664.587,-193.432 1674.4708,-197.2477 1674.6931,-190.2512"/>
<text text-anchor="middle" x="2210.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- genetic_analysis -->
<g id="node22" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1366.3431" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1366.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge37" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1379.7833,-347.8804C1383.5249,-342.3254 1387.3729,-336.073 1390.3431,-330 1404.5454,-300.9615 1390.8112,-284.1787 1413.3431,-261 1445.5528,-227.8659 1494.9431,-210.5507 1535.1566,-201.5535"/>
<polygon fill="#000000" stroke="#000000" points="1536.105,-204.9305 1545.1666,-199.4407 1534.6593,-198.0814 1536.105,-204.9305"/>
<text text-anchor="middle" x="1483.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge38" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1317.1427,-351.0598C1296.472,-344.6977 1272.1983,-337.1151 1250.3431,-330 1230.6973,-323.6041 1226.627,-318.9279 1206.3431,-315 1060.8302,-286.8222 1020.8406,-311.577 873.3431,-297 848.9349,-294.5878 821.9895,-290.8466 799.3851,-287.3985"/>
<polygon fill="#000000" stroke="#000000" points="799.7474,-283.913 789.3295,-285.8407 798.6757,-290.8305 799.7474,-283.913"/>
<text text-anchor="middle" x="1320.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- radiology_file -->
<g id="node23" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="2444.3431" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="2444.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2401.6749,-264.263C2364.9592,-252.2729 2310.3209,-236.0641 2261.3431,-228 2150.3138,-209.7193 1821.7387,-198.2985 1674.7903,-193.9721"/>
<polygon fill="#000000" stroke="#000000" points="1674.6272,-190.466 1664.5294,-193.6729 1674.4231,-197.463 1674.6272,-190.466"/>
<text text-anchor="middle" x="2386.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- methylation_array_file -->
<g id="node24" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="542.3431" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="542.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M544.5899,-347.8634C546.9245,-336.7677 551.6771,-323.1777 561.3431,-315 581.0956,-298.2889 646.5952,-288.5551 694.5199,-283.5135"/>
<polygon fill="#000000" stroke="#000000" points="695.1631,-286.9664 704.7604,-282.4785 694.4592,-280.0019 695.1631,-286.9664"/>
<text text-anchor="middle" x="652.8431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- medical_history -->
<g id="node25" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="2621.3431" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="2621.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2578.9122,-263.235C2544.513,-251.2341 2494.5034,-235.5368 2449.3431,-228 2301.4004,-203.3099 1852.1496,-195.1151 1675.1396,-192.8"/>
<polygon fill="#000000" stroke="#000000" points="1674.934,-189.2972 1664.8899,-192.6686 1674.8442,-196.2966 1674.934,-189.2972"/>
<text text-anchor="middle" x="2579.3431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge28" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1348.8219,-95.9341C1267.8058,-85.3311 1128.8649,-67.5114 1009.3431,-54 898.3094,-41.4481 767.5497,-28.7617 699.6031,-22.3268"/>
<polygon fill="#000000" stroke="#000000" points="699.5349,-18.8049 689.25,-21.3487 698.8764,-25.7739 699.5349,-18.8049"/>
<text text-anchor="middle" x="1195.8431" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- generic_file -->
<g id="node27" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="2848.3431" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="2848.3431" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge25" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2899.3851,-354.6502C2937.2534,-342.8675 2982.3431,-320.1895 2982.3431,-279 2982.3431,-279 2982.3431,-279 2982.3431,-105 2982.3431,-45.7092 1028.88,-22.0479 700.0587,-18.4851"/>
<polygon fill="#000000" stroke="#000000" points="699.9633,-14.984 689.9262,-18.3761 699.8879,-21.9836 699.9633,-14.984"/>
<text text-anchor="middle" x="3035.3431" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2832.108,-348.2322C2800.9452,-315.7442 2728.9222,-248.2384 2651.3431,-228 2557.7243,-203.5772 1897.4702,-194.9002 1675.1805,-192.6522"/>
<polygon fill="#000000" stroke="#000000" points="1674.9648,-189.15 1664.9303,-192.55 1674.8949,-196.1496 1674.9648,-189.15"/>
<text text-anchor="middle" x="2828.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge26" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2783.9295,-362.1689C2620.8656,-352.6161 2178.4532,-327.6053 1809.3431,-315 1393.5086,-300.799 1288.0517,-330.7162 873.3431,-297 848.8019,-295.0048 821.7375,-291.2962 799.0861,-287.7615"/>
<polygon fill="#000000" stroke="#000000" points="799.4405,-284.2738 789.0142,-286.1564 798.3388,-291.1866 799.4405,-284.2738"/>
<text text-anchor="middle" x="2204.3431" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- survival -->
<g id="node28" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="1092.3431" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="1092.3431" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1108.2076,-261.8324C1120.192,-250.0918 1137.7151,-235.3688 1156.3431,-228 1190.132,-214.6339 1412.7713,-201.5754 1530.1612,-195.5146"/>
<polygon fill="#000000" stroke="#000000" points="1530.6866,-198.9924 1540.4944,-194.9852 1530.3284,-192.0016 1530.6866,-198.9924"/>
<text text-anchor="middle" x="1195.8431" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
</g>
</svg>
</div>
