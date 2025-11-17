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
<svg width="3177pt" height="392pt"
 viewBox="0.00 0.00 3177.24 392.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 388)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-388 3173.2382,-388 3173.2382,4 -4,4"/>
<!-- publication -->
<g id="node1" class="node">
<title>publication</title>
<ellipse fill="none" stroke="#000000" cx="63.0444" cy="-105" rx="63.0888" ry="18"/>
<text text-anchor="middle" x="63.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<ellipse fill="none" stroke="#000000" cx="2461.0444" cy="-18" rx="36.2938" ry="18"/>
<text text-anchor="middle" x="2461.0444" y="-14.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge23" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M57.779,-86.9957C55.7543,-75.9528 55.634,-62.3719 64.0444,-54 85.6671,-32.4763 2080.2831,-20.1707 2413.9532,-18.2619"/>
<polygon fill="#000000" stroke="#000000" points="2414.2509,-21.7604 2424.2308,-18.2034 2414.211,-14.7605 2414.2509,-21.7604"/>
<text text-anchor="middle" x="115.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- sequencing_file -->
<g id="node2" class="node">
<title>sequencing_file</title>
<ellipse fill="none" stroke="#000000" cx="1300.0444" cy="-366" rx="83.3857" ry="18"/>
<text text-anchor="middle" x="1300.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<ellipse fill="none" stroke="#000000" cx="2033.0444" cy="-279" rx="44.393" ry="18"/>
<text text-anchor="middle" x="2033.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge39" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1320.5346,-348.5098C1335.8344,-336.6129 1357.849,-321.8358 1380.0444,-315 1507.5285,-275.7371 1848.7752,-320.7101 1980.0444,-297 1983.753,-296.3301 1987.5543,-295.4502 1991.335,-294.4391"/>
<polygon fill="#000000" stroke="#000000" points="1992.6237,-297.7077 2001.2172,-291.5108 1990.6349,-290.9962 1992.6237,-297.7077"/>
<text text-anchor="middle" x="1446.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- cytogenomic_file -->
<g id="node3" class="node">
<title>cytogenomic_file</title>
<ellipse fill="none" stroke="#000000" cx="1491.0444" cy="-366" rx="89.8845" ry="18"/>
<text text-anchor="middle" x="1491.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytogenomic_file</text>
</g>
<!-- cytogenomic_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>cytogenomic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1501.5345,-347.9453C1509.4034,-336.2751 1521.3304,-322.0021 1536.0444,-315 1580.6275,-293.7837 1931.5036,-306.0316 1980.0444,-297 1983.6987,-296.3201 1987.4441,-295.4415 1991.172,-294.4388"/>
<polygon fill="#000000" stroke="#000000" points="1992.3322,-297.7454 2000.9238,-291.5459 1990.3413,-291.0345 1992.3322,-297.7454"/>
<text text-anchor="middle" x="1607.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cytogenomic_file</text>
</g>
<!-- cell_line -->
<g id="node4" class="node">
<title>cell_line</title>
<ellipse fill="none" stroke="#000000" cx="2121.0444" cy="-366" rx="49.2915" ry="18"/>
<text text-anchor="middle" x="2121.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_line</text>
</g>
<!-- cell_line&#45;&gt;sample -->
<g id="edge37" class="edge">
<title>cell_line&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2078.2566,-356.9627C2051.9724,-350.446 2021.8793,-340.9025 2014.0444,-330 2008.6993,-322.5621 2010.1265,-313.4445 2013.9635,-304.9857"/>
<polygon fill="#000000" stroke="#000000" points="2017.0616,-306.6162 2018.8666,-296.1763 2010.9451,-303.212 2017.0616,-306.6162"/>
<text text-anchor="middle" x="2054.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- cell_line&#45;&gt;study -->
<g id="edge38" class="edge">
<title>cell_line&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2148.8648,-350.9518C2173.7125,-337.7238 2208.3814,-319.8455 2223.0444,-315 2266.7535,-300.556 2289.0408,-325.6853 2325.0444,-297 2371.4638,-260.0161 2351.3913,-227.5209 2377.0444,-174 2399.3347,-127.4949 2428.4568,-74.9939 2445.9018,-44.2967"/>
<polygon fill="#000000" stroke="#000000" points="2449.0047,-45.921 2450.9204,-35.5008 2442.9247,-42.452 2449.0047,-45.921"/>
<text text-anchor="middle" x="2417.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_cell_line</text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<ellipse fill="none" stroke="#000000" cx="1234.0444" cy="-192" rx="62.2891" ry="18"/>
<text text-anchor="middle" x="1234.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
</g>
<!-- consent_group -->
<g id="node19" class="node">
<title>consent_group</title>
<ellipse fill="none" stroke="#000000" cx="1783.0444" cy="-105" rx="79.0865" ry="18"/>
<text text-anchor="middle" x="1783.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1288.9448,-183.2999C1387.6987,-167.6504 1595.4232,-134.7323 1707.5091,-116.9701"/>
<polygon fill="#000000" stroke="#000000" points="1708.3917,-120.374 1717.7207,-115.3519 1707.2961,-113.4602 1708.3917,-120.374"/>
<text text-anchor="middle" x="1592.5444" y="-144.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- medical_history -->
<g id="node6" class="node">
<title>medical_history</title>
<ellipse fill="none" stroke="#000000" cx="1264.0444" cy="-279" rx="85.2851" ry="18"/>
<text text-anchor="middle" x="1264.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1245.785,-261.0395C1241.4506,-255.6773 1237.4037,-249.4863 1235.0444,-243 1232.4931,-235.9858 1231.5132,-228.0622 1231.3467,-220.5884"/>
<polygon fill="#000000" stroke="#000000" points="1234.8486,-220.5398 1231.5738,-210.4638 1227.8504,-220.3827 1234.8486,-220.5398"/>
<text text-anchor="middle" x="1303.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<ellipse fill="none" stroke="#000000" cx="348.0444" cy="-366" rx="54.6905" ry="18"/>
<text text-anchor="middle" x="348.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge33" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M312.7377,-352.1851C269.4667,-333.2504 205.3344,-297.4173 235.0444,-261 281.218,-204.4023 323.549,-236.9291 396.0444,-228 543.1523,-209.881 986.1977,-197.8142 1161.5034,-193.6315"/>
<polygon fill="#000000" stroke="#000000" points="1161.7423,-197.127 1171.6566,-193.391 1161.5765,-190.1289 1161.7423,-197.127"/>
<text text-anchor="middle" x="279.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge34" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M395.2498,-356.8293C460.5315,-344.6215 582.1993,-323.5767 687.0444,-315 830.2467,-303.2856 1838.4511,-321.4017 1980.0444,-297 1983.7583,-296.36 1987.5632,-295.5008 1991.3464,-294.5035"/>
<polygon fill="#000000" stroke="#000000" points="1992.6257,-297.7756 2001.2324,-291.5969 1990.6512,-291.0598 1992.6257,-297.7756"/>
<text text-anchor="middle" x="731.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;cell_line -->
<g id="edge19" class="edge">
<title>sample&#45;&gt;cell_line</title>
<path fill="none" stroke="#000000" d="M2065.5435,-291.3953C2077.2905,-297.148 2089.898,-304.97 2099.0444,-315 2105.0495,-321.5852 2109.586,-330.0628 2112.9317,-338.2081"/>
<polygon fill="#000000" stroke="#000000" points="2109.7261,-339.6339 2116.4408,-347.8292 2116.3024,-337.2353 2109.7261,-339.6339"/>
<text text-anchor="middle" x="2146.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2001.808,-266.1279C1970.5721,-253.9115 1920.8626,-236.2314 1876.0444,-228 1768.6198,-208.2702 1450.3236,-197.6687 1306.2877,-193.7681"/>
<polygon fill="#000000" stroke="#000000" points="1306.3137,-190.2676 1296.2236,-193.4988 1306.1264,-197.2651 1306.3137,-190.2676"/>
<text text-anchor="middle" x="1970.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- pdx -->
<g id="node20" class="node">
<title>pdx</title>
<ellipse fill="none" stroke="#000000" cx="2256.0444" cy="-192" rx="27.8951" ry="18"/>
<text text-anchor="middle" x="2256.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
</g>
<!-- sample&#45;&gt;pdx -->
<g id="edge17" class="edge">
<title>sample&#45;&gt;pdx</title>
<path fill="none" stroke="#000000" d="M2063.7323,-265.964C2088.7401,-255.4411 2125.0272,-240.3994 2157.0444,-228 2178.393,-219.7323 2202.5347,-210.9424 2221.6335,-204.1178"/>
<polygon fill="#000000" stroke="#000000" points="2222.8723,-207.392 2231.1197,-200.7413 2220.525,-200.7973 2222.8723,-207.392"/>
<text text-anchor="middle" x="2193.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- laboratory_test -->
<g id="node9" class="node">
<title>laboratory_test</title>
<ellipse fill="none" stroke="#000000" cx="902.0444" cy="-366" rx="81.7856" ry="18"/>
<text text-anchor="middle" x="902.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge24" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M888.5657,-347.9784C873.3481,-325.2645 853.2508,-286.1575 874.0444,-261 909.8368,-217.6959 1067.5095,-201.303 1161.9112,-195.2993"/>
<polygon fill="#000000" stroke="#000000" points="1162.202,-198.7881 1171.9694,-194.6836 1161.7742,-191.8012 1162.202,-198.7881"/>
<text text-anchor="middle" x="939.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M934.9917,-349.4203C960.9115,-337.312 998.3276,-321.8617 1033.0444,-315 1239.5323,-274.1882 1772.7112,-333.2741 1980.0444,-297 1983.7566,-296.3505 1987.5604,-295.4848 1991.3428,-294.4831"/>
<polygon fill="#000000" stroke="#000000" points="1992.6252,-297.7541 2001.2277,-291.5696 1990.6461,-291.0397 1992.6252,-297.7541"/>
<text text-anchor="middle" x="1098.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- family_relationship -->
<g id="node10" class="node">
<title>family_relationship</title>
<ellipse fill="none" stroke="#000000" cx="1643.0444" cy="-279" rx="100.1823" ry="18"/>
<text text-anchor="middle" x="1643.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1578.2371,-265.2146C1500.2011,-248.6152 1370.1805,-220.958 1294.2554,-204.8077"/>
<polygon fill="#000000" stroke="#000000" points="1294.8749,-201.3613 1284.3655,-202.704 1293.4185,-208.2081 1294.8749,-201.3613"/>
<text text-anchor="middle" x="1542.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<ellipse fill="none" stroke="#000000" cx="1866.0444" cy="-279" rx="104.7816" ry="18"/>
<text text-anchor="middle" x="1866.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge22" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1805.7438,-264.1247C1757.4234,-252.7051 1687.7438,-237.3554 1626.0444,-228 1514.8185,-211.1349 1384.5556,-201.0741 1305.7245,-196.0402"/>
<polygon fill="#000000" stroke="#000000" points="1305.6238,-192.527 1295.4238,-195.3924 1305.1844,-199.5132 1305.6238,-192.527"/>
<text text-anchor="middle" x="1789.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<ellipse fill="none" stroke="#000000" cx="2587.0444" cy="-105" rx="59.5901" ry="18"/>
<text text-anchor="middle" x="2587.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge15" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2563.0482,-88.4312C2542.499,-74.2424 2512.8222,-53.7513 2490.7718,-38.5261"/>
<polygon fill="#000000" stroke="#000000" points="2492.6507,-35.5702 2482.4331,-32.7684 2488.6734,-41.3305 2492.6507,-35.5702"/>
<text text-anchor="middle" x="2579.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- treatment -->
<g id="node14" class="node">
<title>treatment</title>
<ellipse fill="none" stroke="#000000" cx="391.0444" cy="-279" rx="57.6901" ry="18"/>
<text text-anchor="middle" x="391.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge40" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M393.535,-260.819C396.1247,-249.4073 401.3853,-235.4813 412.0444,-228 442.4478,-206.6608 966.2327,-196.2305 1161.4706,-193.0707"/>
<polygon fill="#000000" stroke="#000000" points="1161.6876,-196.5678 1171.6303,-192.908 1161.5755,-189.5686 1161.6876,-196.5678"/>
<text text-anchor="middle" x="459.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- exposure -->
<g id="node15" class="node">
<title>exposure</title>
<ellipse fill="none" stroke="#000000" cx="520.0444" cy="-279" rx="53.0913" ry="18"/>
<text text-anchor="middle" x="520.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge30" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M512.122,-261.177C508.5832,-250.2064 506.8281,-236.638 515.0444,-228 537.0798,-204.8337 983.3799,-195.7 1161.5289,-192.9679"/>
<polygon fill="#000000" stroke="#000000" points="1161.6497,-196.4666 1171.5957,-192.816 1161.544,-189.4674 1161.6497,-196.4666"/>
<text text-anchor="middle" x="558.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- generic_file -->
<g id="node16" class="node">
<title>generic_file</title>
<ellipse fill="none" stroke="#000000" cx="609.0444" cy="-366" rx="65.7887" ry="18"/>
<text text-anchor="middle" x="609.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">generic_file</text>
</g>
<!-- generic_file&#45;&gt;participant -->
<g id="edge28" class="edge">
<title>generic_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M604.7628,-347.9501C600.4408,-324.8416 597.0558,-284.9364 618.0444,-261 653.3721,-220.7106 1006.6042,-201.3463 1161.6831,-194.7347"/>
<polygon fill="#000000" stroke="#000000" points="1162.2085,-198.2158 1172.0528,-194.299 1161.9146,-191.2219 1162.2085,-198.2158"/>
<text text-anchor="middle" x="671.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>generic_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M658.18,-353.9283C711.278,-341.5076 798.5703,-322.8939 875.0444,-315 1119.3345,-289.7835 1738.0735,-338.9955 1980.0444,-297 1983.7575,-296.3556 1987.5619,-295.4933 1991.3447,-294.494"/>
<polygon fill="#000000" stroke="#000000" points="1992.6255,-297.7656 2001.2302,-291.5842 1990.6488,-291.0504 1992.6255,-297.7656"/>
<text text-anchor="middle" x="928.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- generic_file&#45;&gt;study -->
<g id="edge29" class="edge">
<title>generic_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M547.1223,-359.7965C428.319,-347.0546 180.0444,-316.0002 180.0444,-279 180.0444,-279 180.0444,-279 180.0444,-105 180.0444,-46.9907 2089.2131,-22.3054 2414.2672,-18.5229"/>
<polygon fill="#000000" stroke="#000000" points="2414.3326,-22.0225 2424.2915,-18.4071 2414.2516,-15.023 2414.3326,-22.0225"/>
<text text-anchor="middle" x="233.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_generic_file</text>
</g>
<!-- study_funding -->
<g id="node17" class="node">
<title>study_funding</title>
<ellipse fill="none" stroke="#000000" cx="2742.0444" cy="-105" rx="77.1866" ry="18"/>
<text text-anchor="middle" x="2742.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2711.0474,-88.3209C2689.4223,-77.2647 2659.6112,-63.1603 2632.0444,-54 2590.2495,-40.1117 2540.8676,-30.3982 2505.9435,-24.5908"/>
<polygon fill="#000000" stroke="#000000" points="2506.4764,-21.1316 2496.0449,-22.9849 2505.3554,-28.0412 2506.4764,-21.1316"/>
<text text-anchor="middle" x="2731.0444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- pathology_file -->
<g id="node18" class="node">
<title>pathology_file</title>
<ellipse fill="none" stroke="#000000" cx="1675.0444" cy="-366" rx="76.0865" ry="18"/>
<text text-anchor="middle" x="1675.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_file</text>
</g>
<!-- pathology_file&#45;&gt;sample -->
<g id="edge36" class="edge">
<title>pathology_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1676.8532,-347.936C1679.0086,-336.5736 1683.726,-322.6588 1694.0444,-315 1719.6119,-296.0228 1948.808,-303.1736 1980.0444,-297 1983.6908,-296.2793 1987.4308,-295.3721 1991.155,-294.3503"/>
<polygon fill="#000000" stroke="#000000" points="1992.3282,-297.6525 2000.901,-291.427 1990.317,-290.9477 1992.3282,-297.6525"/>
<text text-anchor="middle" x="1755.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pathology_file</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge31" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1847.408,-94.4212C1915.3246,-83.4621 2025.5406,-66.2552 2121.0444,-54 2226.1087,-40.518 2349.9102,-28.3389 2415.2729,-22.1974"/>
<polygon fill="#000000" stroke="#000000" points="2415.619,-25.6804 2425.2496,-21.2643 2414.9671,-18.7108 2415.619,-25.6804"/>
<text text-anchor="middle" x="2184.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2252.8741,-210.1075C2249.9345,-221.3379 2244.3818,-235.0878 2234.0444,-243 2211.7587,-260.0573 2136.6153,-255.7608 2109.0444,-261 2099.8487,-262.7474 2090.0861,-264.8613 2080.731,-267.0169"/>
<polygon fill="#000000" stroke="#000000" points="2079.7183,-263.6595 2070.7858,-269.357 2081.3216,-270.4734 2079.7183,-263.6595"/>
<text text-anchor="middle" x="2271.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- pdx&#45;&gt;study -->
<g id="edge11" class="edge">
<title>pdx&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2256.6938,-173.6919C2258.3038,-151.3816 2263.7631,-113.4019 2282.0444,-87 2296.7821,-65.7157 2306.5694,-64.9153 2330.0444,-54 2357.6106,-41.1824 2390.6261,-32.1459 2416.6159,-26.3322"/>
<polygon fill="#000000" stroke="#000000" points="2417.5281,-29.7161 2426.5653,-24.1861 2416.0521,-22.8734 2417.5281,-29.7161"/>
<text text-anchor="middle" x="2306.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- survival -->
<g id="node21" class="node">
<title>survival</title>
<ellipse fill="none" stroke="#000000" cx="781.0444" cy="-279" rx="48.1917" ry="18"/>
<text text-anchor="middle" x="781.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M773.5372,-260.7545C770.399,-249.8993 769.0869,-236.609 777.0444,-228 789.9012,-214.0906 1036.423,-200.9578 1161.926,-195.1404"/>
<polygon fill="#000000" stroke="#000000" points="1162.3872,-198.623 1172.2158,-194.6672 1162.0656,-191.6303 1162.3872,-198.623"/>
<text text-anchor="middle" x="816.5444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study_personnel -->
<g id="node22" class="node">
<title>study_personnel</title>
<ellipse fill="none" stroke="#000000" cx="2924.0444" cy="-105" rx="87.1846" ry="18"/>
<text text-anchor="middle" x="2924.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge32" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2890.1309,-88.3995C2865.0263,-76.8556 2829.6665,-62.132 2797.0444,-54 2743.3143,-40.6062 2586.1224,-27.3903 2507.2704,-21.3729"/>
<polygon fill="#000000" stroke="#000000" points="2507.3753,-17.8709 2497.1397,-20.6065 2506.8472,-24.851 2507.3753,-17.8709"/>
<text text-anchor="middle" x="2912.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- genetic_analysis -->
<g id="node23" class="node">
<title>genetic_analysis</title>
<ellipse fill="none" stroke="#000000" cx="1104.0444" cy="-366" rx="87.9851" ry="18"/>
<text text-anchor="middle" x="1104.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge20" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1041.9217,-353.1405C1014.4853,-344.7648 991.7323,-332.1726 1008.0444,-315 1034.8629,-286.7668 1328.0855,-321.8759 1358.0444,-297 1382.053,-277.0648 1390.1013,-252.7115 1371.0444,-228 1361.9706,-216.2338 1330.9377,-207.5543 1300.6981,-201.6692"/>
<polygon fill="#000000" stroke="#000000" points="1300.9767,-198.1613 1290.5062,-199.7801 1299.7008,-205.0441 1300.9767,-198.1613"/>
<text text-anchor="middle" x="1452.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge21" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1130.4785,-348.6986C1150.3606,-336.7273 1178.7595,-321.7769 1206.0444,-315 1373.0176,-273.5279 1810.6354,-327.0099 1980.0444,-297 1983.7552,-296.3426 1987.558,-295.4714 1991.3398,-294.4661"/>
<polygon fill="#000000" stroke="#000000" points="1992.6246,-297.7362 2001.2237,-291.5469 1990.6418,-291.0228 1992.6246,-297.7362"/>
<text text-anchor="middle" x="1276.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- radiology_file -->
<g id="node24" class="node">
<title>radiology_file</title>
<ellipse fill="none" stroke="#000000" cx="1087.0444" cy="-279" rx="73.387" ry="18"/>
<text text-anchor="middle" x="1087.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">radiology_file</text>
</g>
<!-- radiology_file&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>radiology_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1091.1905,-260.6103C1094.5496,-249.7009 1100.362,-236.4042 1110.0444,-228 1119.9519,-219.4005 1146.7212,-211.139 1172.8624,-204.7041"/>
<polygon fill="#000000" stroke="#000000" points="1173.899,-208.0552 1182.814,-202.3305 1172.2748,-201.2462 1173.899,-208.0552"/>
<text text-anchor="middle" x="1169.0444" y="-231.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_radiology_file</text>
</g>
<!-- study_admin -->
<g id="node25" class="node">
<title>study_admin</title>
<ellipse fill="none" stroke="#000000" cx="3099.0444" cy="-105" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="3099.0444" y="-101.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge26" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3069.8788,-88.3468C3047.6559,-76.536 3015.8949,-61.5017 2986.0444,-54 2896.1314,-31.404 2618.8146,-22.0092 2507.7472,-19.086"/>
<polygon fill="#000000" stroke="#000000" points="2507.6164,-15.5816 2497.5296,-18.8231 2507.4363,-22.5793 2507.6164,-15.5816"/>
<text text-anchor="middle" x="3083.5444" y="-57.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_status -->
<g id="node26" class="node">
<title>study_status</title>
<ellipse fill="none" stroke="#000000" cx="2763.0444" cy="-366" rx="70.3881" ry="18"/>
<text text-anchor="middle" x="2763.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
</g>
<!-- clinical_measure_file -->
<g id="node27" class="node">
<title>clinical_measure_file</title>
<ellipse fill="none" stroke="#000000" cx="2444.0444" cy="-366" rx="108.5808" ry="18"/>
<text text-anchor="middle" x="2444.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2498.3486,-350.296C2519.8198,-341.4577 2536.5328,-329.3191 2523.0444,-315 2500.0714,-290.6121 2254.9589,-303.2582 2222.0444,-297 2125.1162,-278.5707 2108.0942,-245.778 2011.0444,-228 1877.279,-203.4962 1473.0491,-195.266 1306.7284,-192.8702"/>
<polygon fill="#000000" stroke="#000000" points="1306.6475,-189.3688 1296.5991,-192.7273 1306.5487,-196.3681 1306.6475,-189.3688"/>
<text text-anchor="middle" x="2308.0444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>clinical_measure_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2365.4645,-353.509C2328.2139,-347.184 2283.1813,-338.953 2243.0444,-330 2217.8962,-324.3904 2212.0459,-321.2312 2187.0444,-315 2152.5227,-306.3961 2143.6879,-305.0998 2109.0444,-297 2100.0269,-294.8917 2090.4116,-292.6272 2081.1594,-290.4398"/>
<polygon fill="#000000" stroke="#000000" points="2081.8449,-287.0055 2071.3076,-288.1077 2080.2324,-293.8172 2081.8449,-287.0055"/>
<text text-anchor="middle" x="2329.0444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2500.5275,-350.5387C2517.9718,-344.5501 2533.9587,-337.3659 2539.0444,-330 2547.9598,-317.0874 2549.4867,-297.0906 2530.0444,-261 2514.2341,-231.6514 2489.483,-240.0472 2475.0444,-210 2449.375,-156.5811 2452.5499,-85.0427 2456.9256,-46.1184"/>
<polygon fill="#000000" stroke="#000000" points="2460.4173,-46.4001 2458.1686,-36.0467 2453.47,-45.5427 2460.4173,-46.4001"/>
<text text-anchor="middle" x="2561.0444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- synonym -->
<g id="node28" class="node">
<title>synonym</title>
<ellipse fill="none" stroke="#000000" cx="2623.0444" cy="-366" rx="51.9908" ry="18"/>
<text text-anchor="middle" x="2623.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2599.1028,-349.7901C2582.6577,-339.0788 2560.0798,-325.1892 2539.0444,-315 2436.9341,-265.5392 2410.5867,-248.7654 2299.0444,-228 2202.3097,-209.9913 1530.8264,-197.0517 1306.6896,-193.1934"/>
<polygon fill="#000000" stroke="#000000" points="1306.4171,-189.6884 1296.3586,-193.0166 1306.2972,-196.6873 1306.4171,-189.6884"/>
<text text-anchor="middle" x="2543.5444" y="-275.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2583.7741,-353.9971C2576.5696,-351.9134 2569.0983,-349.8304 2562.0444,-348 2545.8412,-343.7955 2431.6209,-317.3325 2415.0444,-315 2280.1383,-296.0174 2243.8369,-316.7734 2109.0444,-297 2099.4856,-295.5978 2089.3605,-293.5818 2079.7247,-291.4022"/>
<polygon fill="#000000" stroke="#000000" points="2080.4406,-287.9752 2069.9047,-289.0906 2078.8366,-294.7889 2080.4406,-287.9752"/>
<text text-anchor="middle" x="2526.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2632.4826,-348.2758C2650.3302,-312.069 2684.0666,-228.4472 2647.0444,-174 2612.3784,-123.018 2564.1916,-163.8819 2518.0444,-123 2494.512,-102.1525 2478.864,-69.1838 2470.0135,-45.7552"/>
<polygon fill="#000000" stroke="#000000" points="2473.2022,-44.279 2466.5274,-36.0511 2466.6144,-46.6456 2473.2022,-44.279"/>
<text text-anchor="middle" x="2703.5444" y="-188.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- methylation_array_file -->
<g id="node29" class="node">
<title>methylation_array_file</title>
<ellipse fill="none" stroke="#000000" cx="1885.0444" cy="-366" rx="115.8798" ry="18"/>
<text text-anchor="middle" x="1885.0444" y="-362.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge35" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1843.1913,-349.0423C1826.1679,-339.7443 1812.8394,-327.5723 1824.0444,-315 1847.2628,-288.9485 1945.9975,-304.6543 1980.0444,-297 1983.6205,-296.196 1987.2934,-295.2382 1990.9568,-294.1894"/>
<polygon fill="#000000" stroke="#000000" points="1992.0258,-297.5225 2000.5595,-291.2434 1989.9727,-290.8304 1992.0258,-297.5225"/>
<text text-anchor="middle" x="1915.5444" y="-318.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
</g>
</svg>
</div>
