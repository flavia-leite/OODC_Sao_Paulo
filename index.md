# Is the OODC achieving its geographic redistributive purposes?
by Flávia Leite


### INTRODUCTION
The **Outorga Onerosa do Direito de Construir (OODC)** - or the onerous grant of the right to build - is one of Brazil's main instruments of  municipal urban planning. The OODC was brought in by the 2001 Statute of the City (Estatuto da Cidade), the national law regulating the Brazilian Constitution’s articles on urban policy.The OODC regulates the payment by Developers of additional building rights. The resources generated with the OODC in each city are deposited into a reserve fund used to provide urban improvements of social interest across the municipality.


Although regulated at the national level in 2001, the OODC is still a poorly disseminated instrument among Brazilian cities. Currently, only 40% of the more than 5 thousand Brazilian municipalities have a specific legislation concerning the use of the OODC(IBGE, 2018). The map below shows the status of the OODC use in Brazil's 26 State capitals and the Federal District (Brazília). Out of the 27 cities, 20 have specific legislation codifying the implementation of the OODC, but only 16 of them implement the instrument.


<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_7b9002182da74dfa84a2c3e4259edad5 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_7b9002182da74dfa84a2c3e4259edad5" ></div>
        
</body>
<script>    
    
            var map_7b9002182da74dfa84a2c3e4259edad5 = L.map(
                "map_7b9002182da74dfa84a2c3e4259edad5",
                {
                    center: [-15.7975, -47.8919],
                    crs: L.CRS.EPSG3857,
                    zoom: 4,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_03cfb964936b4d74aa727ed1a0f5a7e5 = L.tileLayer(
                "https://cartodb-basemaps-{s}.global.ssl.fastly.net/light_all/{z}/{x}/{y}.png",
                {"attribution": "\u0026copy; \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors \u0026copy; \u003ca href=\"http://cartodb.com/attributions\"\u003eCartoDB\u003c/a\u003e, CartoDB \u003ca href =\"http://cartodb.com/attributions\"\u003eattributions\u003c/a\u003e", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
            var circle_marker_36040e61d24a4b719be0b2f440cc4c93 = L.circleMarker(
                [-10.57, -37.45],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_f6bfe4098d98423e965b08bf0a80fa6f = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_ade9ba6fb562448892d351f7ed99d5bd = $(`<div id="html_ade9ba6fb562448892d351f7ed99d5bd" style="width: 100.0%; height: 100.0%;"> - City: ARACAJU<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_f6bfe4098d98423e965b08bf0a80fa6f.setContent(html_ade9ba6fb562448892d351f7ed99d5bd);
        

        circle_marker_36040e61d24a4b719be0b2f440cc4c93.bindPopup(popup_f6bfe4098d98423e965b08bf0a80fa6f)
        ;

        
    
    
            var circle_marker_6d74aa787f3e4fa4ad5b4de1f7c19d82 = L.circleMarker(
                [1.99, -61.33],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_4f5e3a1e532043d9857b67009658d263 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_b1a421335c974e2eb40367e1338791d8 = $(`<div id="html_b1a421335c974e2eb40367e1338791d8" style="width: 100.0%; height: 100.0%;"> - City: BOA VISTA<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_4f5e3a1e532043d9857b67009658d263.setContent(html_b1a421335c974e2eb40367e1338791d8);
        

        circle_marker_6d74aa787f3e4fa4ad5b4de1f7c19d82.bindPopup(popup_4f5e3a1e532043d9857b67009658d263)
        ;

        
    
    
            var circle_marker_a655209c910045fc8eaaa89817a427f7 = L.circleMarker(
                [-20.51, -54.54],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_344d4ff51fea4737bd69e57f98e9af8c = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_28cc473084734e97b297f77ba4752e7d = $(`<div id="html_28cc473084734e97b297f77ba4752e7d" style="width: 100.0%; height: 100.0%;"> - City: CAMPO GRANDE<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_344d4ff51fea4737bd69e57f98e9af8c.setContent(html_28cc473084734e97b297f77ba4752e7d);
        

        circle_marker_a655209c910045fc8eaaa89817a427f7.bindPopup(popup_344d4ff51fea4737bd69e57f98e9af8c)
        ;

        
    
    
            var circle_marker_a1476ec73dd94d078b0b47bdfbe36537 = L.circleMarker(
                [1.41, -51.77],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_dff2de765aaa4a1ea48d70629e520334 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_d042a04da08d46eebe1b530433bbf021 = $(`<div id="html_d042a04da08d46eebe1b530433bbf021" style="width: 100.0%; height: 100.0%;"> - City: MACAPA<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_dff2de765aaa4a1ea48d70629e520334.setContent(html_d042a04da08d46eebe1b530433bbf021);
        

        circle_marker_a1476ec73dd94d078b0b47bdfbe36537.bindPopup(popup_dff2de765aaa4a1ea48d70629e520334)
        ;

        
    
    
            var circle_marker_0bec9ea073d24dcab41c51c886eedd8f = L.circleMarker(
                [-8.38, -37.86],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_d6f709832e6141c7833d9f55b3af3a6c = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_78883429d28345319420943b7459e0f9 = $(`<div id="html_78883429d28345319420943b7459e0f9" style="width: 100.0%; height: 100.0%;"> - City: RECIFE<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_d6f709832e6141c7833d9f55b3af3a6c.setContent(html_78883429d28345319420943b7459e0f9);
        

        circle_marker_0bec9ea073d24dcab41c51c886eedd8f.bindPopup(popup_d6f709832e6141c7833d9f55b3af3a6c)
        ;

        
    
    
            var circle_marker_1376df74f55447dd8a55576d612c48f5 = L.circleMarker(
                [-8.77, -70.55],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_097f9de5b1e14100bb7361ed9653d90b = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_fc85487e58ce4d818f0fa1edf33e2e37 = $(`<div id="html_fc85487e58ce4d818f0fa1edf33e2e37" style="width: 100.0%; height: 100.0%;"> - City: RIO BRANCO<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_097f9de5b1e14100bb7361ed9653d90b.setContent(html_fc85487e58ce4d818f0fa1edf33e2e37);
        

        circle_marker_1376df74f55447dd8a55576d612c48f5.bindPopup(popup_097f9de5b1e14100bb7361ed9653d90b)
        ;

        
    
    
            var circle_marker_69036620ccb644d0b3db2543f36a7472 = L.circleMarker(
                [-5.42, -45.44],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_e389256d956f4fe1bc5115ffe1300411 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_833f46dae75a4719a2f5485c829d5e3d = $(`<div id="html_833f46dae75a4719a2f5485c829d5e3d" style="width: 100.0%; height: 100.0%;"> - City: SAO LUIS<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_e389256d956f4fe1bc5115ffe1300411.setContent(html_833f46dae75a4719a2f5485c829d5e3d);
        

        circle_marker_69036620ccb644d0b3db2543f36a7472.bindPopup(popup_e389256d956f4fe1bc5115ffe1300411)
        ;

        
    
    
            var circle_marker_51242bd1c2fa4380bcaf39572f546b10 = L.circleMarker(
                [-18.1, -44.38],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_a30d60fc949841b79386dd9690630ee6 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_f4edd2929eb5478e978c12abc6961904 = $(`<div id="html_f4edd2929eb5478e978c12abc6961904" style="width: 100.0%; height: 100.0%;"> - City: BELO HORIZONTE<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_a30d60fc949841b79386dd9690630ee6.setContent(html_f4edd2929eb5478e978c12abc6961904);
        

        circle_marker_51242bd1c2fa4380bcaf39572f546b10.bindPopup(popup_a30d60fc949841b79386dd9690630ee6)
        ;

        
    
    
            var circle_marker_116b7913c9d948ae819b853e51733e8f = L.circleMarker(
                [-12.64, -55.42],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_c5c8c2dbb64141ba93cf8a6117a92188 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_eece0790e90f404f9a8c43fd09c6062e = $(`<div id="html_eece0790e90f404f9a8c43fd09c6062e" style="width: 100.0%; height: 100.0%;"> - City: CUIABA<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_c5c8c2dbb64141ba93cf8a6117a92188.setContent(html_eece0790e90f404f9a8c43fd09c6062e);
        

        circle_marker_116b7913c9d948ae819b853e51733e8f.bindPopup(popup_c5c8c2dbb64141ba93cf8a6117a92188)
        ;

        
    
    
            var circle_marker_3aa0a0475b674c93b1af1cc5cd675046 = L.circleMarker(
                [-9.62, -36.82],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_b14a3dbccc0841278758e9fb79212937 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_400926516f174988baf65d9992431474 = $(`<div id="html_400926516f174988baf65d9992431474" style="width: 100.0%; height: 100.0%;"> - City: MACEIO<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_b14a3dbccc0841278758e9fb79212937.setContent(html_400926516f174988baf65d9992431474);
        

        circle_marker_3aa0a0475b674c93b1af1cc5cd675046.bindPopup(popup_b14a3dbccc0841278758e9fb79212937)
        ;

        
    
    
            var circle_marker_a508cf85bef744e7bce1411f9cd285d9 = L.circleMarker(
                [-19.19, -40.34],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_7a70e22a80f7405ab0c3f8c920f82fa5 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_16516f01dc1944fdaedb9130aff854cc = $(`<div id="html_16516f01dc1944fdaedb9130aff854cc" style="width: 100.0%; height: 100.0%;"> - City: VITORIA<br> - OODC legislation?: nan<br> - OODC implemented?: No</div>`)[0];
            popup_7a70e22a80f7405ab0c3f8c920f82fa5.setContent(html_16516f01dc1944fdaedb9130aff854cc);
        

        circle_marker_a508cf85bef744e7bce1411f9cd285d9.bindPopup(popup_7a70e22a80f7405ab0c3f8c920f82fa5)
        ;

        
    
    
            var circle_marker_01919191227948cabb23615af8938093 = L.circleMarker(
                [-3.79, -52.48],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_f3d953a84da74bdaae9f0ed5f98c5cb6 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_d8cebb506d7f4816b04ce5a2bf50b0db = $(`<div id="html_d8cebb506d7f4816b04ce5a2bf50b0db" style="width: 100.0%; height: 100.0%;"> - City: BELEM<br> - OODC legislation?: 2008.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_f3d953a84da74bdaae9f0ed5f98c5cb6.setContent(html_d8cebb506d7f4816b04ce5a2bf50b0db);
        

        circle_marker_01919191227948cabb23615af8938093.bindPopup(popup_f3d953a84da74bdaae9f0ed5f98c5cb6)
        ;

        
    
    
            var circle_marker_ff68c6ddfb314e82869d92d064c4ff4e = L.circleMarker(
                [-5.2, -39.53],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_eb8f30c7b1474411bfc5c076768bac5e = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_abb09433f9084a85aa52a17f9bde9507 = $(`<div id="html_abb09433f9084a85aa52a17f9bde9507" style="width: 100.0%; height: 100.0%;"> - City: FORTALEZA<br> - OODC legislation?: 2009.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_eb8f30c7b1474411bfc5c076768bac5e.setContent(html_abb09433f9084a85aa52a17f9bde9507);
        

        circle_marker_ff68c6ddfb314e82869d92d064c4ff4e.bindPopup(popup_eb8f30c7b1474411bfc5c076768bac5e)
        ;

        
    
    
            var circle_marker_14f79372a64449c587e3d9ca2a78ad5e = L.circleMarker(
                [-7.28, -36.72],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_a46b0b0ca43d4359925a71357af354b8 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_ba68d8a12ab3478aa3dd029f18ee5bd3 = $(`<div id="html_ba68d8a12ab3478aa3dd029f18ee5bd3" style="width: 100.0%; height: 100.0%;"> - City: JOAO PESSOA<br> - OODC legislation?: 2011.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_a46b0b0ca43d4359925a71357af354b8.setContent(html_ba68d8a12ab3478aa3dd029f18ee5bd3);
        

        circle_marker_14f79372a64449c587e3d9ca2a78ad5e.bindPopup(popup_a46b0b0ca43d4359925a71357af354b8)
        ;

        
    
    
            var circle_marker_b2b2bc0770f64028a42c3a230b113dcc = L.circleMarker(
                [-5.81, -36.59],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_cebdcffae07b452b92396fcf54720f52 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_7064229b5c9044fb84279be8fdd5030c = $(`<div id="html_7064229b5c9044fb84279be8fdd5030c" style="width: 100.0%; height: 100.0%;"> - City: NATAL<br> - OODC legislation?: 2022.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_cebdcffae07b452b92396fcf54720f52.setContent(html_7064229b5c9044fb84279be8fdd5030c);
        

        circle_marker_b2b2bc0770f64028a42c3a230b113dcc.bindPopup(popup_cebdcffae07b452b92396fcf54720f52)
        ;

        
    
    
            var circle_marker_07e66d86199f4605926f767867444e50 = L.circleMarker(
                [-22.25, -42.66],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_70f09d2992584255b019da61d931fb2e = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_1215e9272f964326be86ca8fa095c415 = $(`<div id="html_1215e9272f964326be86ca8fa095c415" style="width: 100.0%; height: 100.0%;"> - City: RIO DE JANEIRO<br> - OODC legislation?: 2011.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_70f09d2992584255b019da61d931fb2e.setContent(html_1215e9272f964326be86ca8fa095c415);
        

        circle_marker_07e66d86199f4605926f767867444e50.bindPopup(popup_70f09d2992584255b019da61d931fb2e)
        ;

        
    
    
            var circle_marker_76d34d7c3b6544d8b538c9db932206e9 = L.circleMarker(
                [-13.29, -41.71],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_3f67465f3b644cd7a289b51dd1c3666e = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_7daf6138be3a4f2eaa97d0052e831c30 = $(`<div id="html_7daf6138be3a4f2eaa97d0052e831c30" style="width: 100.0%; height: 100.0%;"> - City: SALVADOR<br> - OODC legislation?: 2015.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_3f67465f3b644cd7a289b51dd1c3666e.setContent(html_7daf6138be3a4f2eaa97d0052e831c30);
        

        circle_marker_76d34d7c3b6544d8b538c9db932206e9.bindPopup(popup_3f67465f3b644cd7a289b51dd1c3666e)
        ;

        
    
    
            var circle_marker_ade91d96a5ba47c589a8db47f2ae40b1 = L.circleMarker(
                [-6.6, -42.28],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_c46e594ed01c4fea831fa140a0b7afb6 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_fdb146434a1742bab3d6d7cbddbc42a3 = $(`<div id="html_fdb146434a1742bab3d6d7cbddbc42a3" style="width: 100.0%; height: 100.0%;"> - City: TERESINA<br> - OODC legislation?: 2019.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_c46e594ed01c4fea831fa140a0b7afb6.setContent(html_fdb146434a1742bab3d6d7cbddbc42a3);
        

        circle_marker_ade91d96a5ba47c589a8db47f2ae40b1.bindPopup(popup_c46e594ed01c4fea831fa140a0b7afb6)
        ;

        
    
    
            var circle_marker_99ac00659fe24c4bb219b92a41fd3f35 = L.circleMarker(
                [-15.83, -47.86],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_ad78bb5266fe4428921c95eea6ead8a1 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_0ed11b5e5c42467c9428598a400390c6 = $(`<div id="html_0ed11b5e5c42467c9428598a400390c6" style="width: 100.0%; height: 100.0%;"> - City: BRASILIA<br> - OODC legislation?: 1996.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_ad78bb5266fe4428921c95eea6ead8a1.setContent(html_0ed11b5e5c42467c9428598a400390c6);
        

        circle_marker_99ac00659fe24c4bb219b92a41fd3f35.bindPopup(popup_ad78bb5266fe4428921c95eea6ead8a1)
        ;

        
    
    
            var circle_marker_7f4929bceeaa4e8b9797e5179e9fc308 = L.circleMarker(
                [-24.89, -51.55],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_daa883df1f39421b873ec2355c7eaf1a = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_ff2705cc44de4fc4bbb15554cdfb382d = $(`<div id="html_ff2705cc44de4fc4bbb15554cdfb382d" style="width: 100.0%; height: 100.0%;"> - City: CURITIBA<br> - OODC legislation?: 2020.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_daa883df1f39421b873ec2355c7eaf1a.setContent(html_ff2705cc44de4fc4bbb15554cdfb382d);
        

        circle_marker_7f4929bceeaa4e8b9797e5179e9fc308.bindPopup(popup_daa883df1f39421b873ec2355c7eaf1a)
        ;

        
    
    
            var circle_marker_9b55a657cee54275b0f48dda4bfe8612 = L.circleMarker(
                [-27.45, -50.95],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_f0f24868daaa42bc8cbf4aff5bd47434 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_52e3f3b96fcf48e5bfb0dca380ddd683 = $(`<div id="html_52e3f3b96fcf48e5bfb0dca380ddd683" style="width: 100.0%; height: 100.0%;"> - City: FLORIANOPOLIS<br> - OODC legislation?: 2014.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_f0f24868daaa42bc8cbf4aff5bd47434.setContent(html_52e3f3b96fcf48e5bfb0dca380ddd683);
        

        circle_marker_9b55a657cee54275b0f48dda4bfe8612.bindPopup(popup_f0f24868daaa42bc8cbf4aff5bd47434)
        ;

        
    
    
            var circle_marker_895a28d7bf08407a885086c35f5c8b80 = L.circleMarker(
                [-15.98, -49.86],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_5702961406fc4dbbb1469e710e3b9613 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_db5ea2a896ad4c6b97b29fd8403903cd = $(`<div id="html_db5ea2a896ad4c6b97b29fd8403903cd" style="width: 100.0%; height: 100.0%;"> - City: GOIANIA<br> - OODC legislation?: 2008.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_5702961406fc4dbbb1469e710e3b9613.setContent(html_db5ea2a896ad4c6b97b29fd8403903cd);
        

        circle_marker_895a28d7bf08407a885086c35f5c8b80.bindPopup(popup_5702961406fc4dbbb1469e710e3b9613)
        ;

        
    
    
            var circle_marker_27e64c61cd234eada88733664030fe83 = L.circleMarker(
                [-3.47, -65.1],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_a630ff92e8ae4d4a8311deeb99e5f753 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_e5eafc0312ca4abdbfa01babe422c78b = $(`<div id="html_e5eafc0312ca4abdbfa01babe422c78b" style="width: 100.0%; height: 100.0%;"> - City: MANAUS<br> - OODC legislation?: 2014.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_a630ff92e8ae4d4a8311deeb99e5f753.setContent(html_e5eafc0312ca4abdbfa01babe422c78b);
        

        circle_marker_27e64c61cd234eada88733664030fe83.bindPopup(popup_a630ff92e8ae4d4a8311deeb99e5f753)
        ;

        
    
    
            var circle_marker_1b31ae2106334a439103f971abff8c5c = L.circleMarker(
                [-9.46, -48.26],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_164b313398fe40e2a1983b93a3173cd3 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_e694b622e2f64d9dbffde03c68881cce = $(`<div id="html_e694b622e2f64d9dbffde03c68881cce" style="width: 100.0%; height: 100.0%;"> - City: PALMAS<br> - OODC legislation?: 2012.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_164b313398fe40e2a1983b93a3173cd3.setContent(html_e694b622e2f64d9dbffde03c68881cce);
        

        circle_marker_1b31ae2106334a439103f971abff8c5c.bindPopup(popup_164b313398fe40e2a1983b93a3173cd3)
        ;

        
    
    
            var circle_marker_dfb26ec50526476aafc245dcaf57e24d = L.circleMarker(
                [-30.17, -53.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_128b131281b84773a5886aa8e0f3b782 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_cba9ac11a8164dc287e84ab08d6478be = $(`<div id="html_cba9ac11a8164dc287e84ab08d6478be" style="width: 100.0%; height: 100.0%;"> - City: PORTO ALEGRE<br> - OODC legislation?: 1994.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_128b131281b84773a5886aa8e0f3b782.setContent(html_cba9ac11a8164dc287e84ab08d6478be);
        

        circle_marker_dfb26ec50526476aafc245dcaf57e24d.bindPopup(popup_128b131281b84773a5886aa8e0f3b782)
        ;

        
    
    
            var circle_marker_95d51d56109f4f7396680d13fa4e6948 = L.circleMarker(
                [-10.83, -63.34],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_37038e8378834af0b29ae5090ad4c181 = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_04137db7af3c43c3bd2adb4f022433f9 = $(`<div id="html_04137db7af3c43c3bd2adb4f022433f9" style="width: 100.0%; height: 100.0%;"> - City: PORTO VELHO<br> - OODC legislation?: 2010.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_37038e8378834af0b29ae5090ad4c181.setContent(html_04137db7af3c43c3bd2adb4f022433f9);
        

        circle_marker_95d51d56109f4f7396680d13fa4e6948.bindPopup(popup_37038e8378834af0b29ae5090ad4c181)
        ;

        
    
    
            var circle_marker_da2fe5fe668d4ac2a3d8d8c6c8cddf29 = L.circleMarker(
                [-22.19, -48.79],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_7b9002182da74dfa84a2c3e4259edad5);
        
    
        var popup_cdd38bd968ab4669a2512ee55d2a7b9b = L.popup({"maxWidth": 300, "minWidth": 100});

        
            var html_9be50f7badc34b56888f75051cb38195 = $(`<div id="html_9be50f7badc34b56888f75051cb38195" style="width: 100.0%; height: 100.0%;"> - City: SAO PAULO<br> - OODC legislation?: 2003.0<br> - OODC implemented?: Yes</div>`)[0];
            popup_cdd38bd968ab4669a2512ee55d2a7b9b.setContent(html_9be50f7badc34b56888f75051cb38195);
        

        circle_marker_da2fe5fe668d4ac2a3d8d8c6c8cddf29.bindPopup(popup_cdd38bd968ab4669a2512ee55d2a7b9b)
        ;

        
    
</script>

Source: [IBGE. (2018) “Pesquisa de  Informações  Básicas  Municipais”](https://www.ibge.gov.br/estatisticas/sociais/educacao/10586-pesquisa-de-informacoes-basicas-municipais.html?=&t=resultados)



<br>
### QUESTIONS AND METHODOLOGY
The OODC was established in São Paulo in 2002 by the city’s Strategic Master Plan. Since then the instrument have raised more than R$ 4.4 billion (around $0.9 billion), in about 3.5 thousand real estate projects. The anual amount generated by the OODC is considered modest, compared to other municipal revenue sources[^1]. Still, OODC is valued by the São Paulo municipality as a source of funding directly applicable to urban improvements (Friendly, 2017). In São Paulo, OODC revenues are allocated to the **Urban Development Fund (FUNDURB)** and earmarked to finance social housing, infrastructure, and other urban improvements of social interest to the community. 

[^1]: As a matter of comparison, São Paulo's budget in 2020 was R$69 billion, while the OODC revenue for that year was R$ 5.4 million.

_Revenues_
The two charts below show  OODC revenues and spending over the years. Due to limited data availability, the charts present figures only from 2013 to 2020. During this time period R$ 2.8 billion ($0.6 billion) were raised by the OODC. Between 2019 and 2020, lower interest rates impacted positively the real estate market, boosting OODC revenues. Also, changes made to São Paulo's master plan in 2014, altered the standardized formula used to calculate the charge levied on developers via the ODDC, increasing revenue generation.

_Spending_
Between 2013 and 2020, R$2.2billion ($0.44 billion) of OODC revenues were spent. Of that amount 40% was paid out in the last two years. 
As already mentioned, OODC funds are not a key municipal revenue source.  Still, this money can have important impacts depending on how they are allocated. For example, between 2013 and 2015, OODC revenues contributed to a 10% increase in the budget of the Subprefeituras Department, and a 7% growth in the Culture Department's budget,representing a significant revenue increase for this entities (Friendly, 2017).

![OODC_REV_SPEN_CHARTS](https://user-images.githubusercontent.com/97998623/166984385-92ad03bf-4a2d-42b0-b7d3-d1522bd4d79d.png)



In São Paulo, OODC revenues have a **redistributive purpose**; revenues collected in the most developed parts of the city should be spent on the most vulnerable areas. Given this redistributive objective, my project aims to answer the following set of questions: 
* Q1. Which parts of the city generated the highest amount of OODC revenue?
* Q2. Have OODC revenues been spent in areas with higher demand for infrastructure?
* Q3. What type of public projects were funded with OODC revenues? 

To answer these questions, I explore the following datasets:
* [SP’s Master Plan monitoring webpage](https://monitoramentopde.gestaourbana.prefeitura.sp.gov.br/) 
* [IBGE – Brazilian Census](https://www.ibge.gov.br/en/home-eng.html)

<img width="516" alt="image" src="https://user-images.githubusercontent.com/97998623/166829046-9132010d-3f93-41c9-af93-8c235a252d77.png">



### REVENUE AND SPENDING






### OODC SPENDING CATEGORY
Include analysis of the two graph below.
xxxxxxxxxxx

<img width="516" alt="image" src="https://user-images.githubusercontent.com/97998623/166984885-b9484888-e769-4eaf-9a57-f3c6ef0b3c61.png">

xxxxxx
xxxxxxxxxxxxxx

![pierchart_districts_cat_Types](https://user-images.githubusercontent.com/97998623/166984896-b086d91a-7efe-4ab9-b873-11ea74162425.png)




### A CLOSER LOOK AT THE INVESTMENT ON HOUSING
Include analysis of the two graph below.hbsfkjbskgbbglsdnglskng;n;kgen
dknfgnglrglberg

TO DO: INTERACTIVE MAP SP




### CONCLUSION











## Welcome CLASS

You can use the [editor on GitHub](https://github.com/flavia-leite/OODC_Sao_Paulo/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/flavia-leite/OODC_Sao_Paulo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
