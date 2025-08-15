[spb_all_routes.html](https://github.com/user-attachments/files/21800856/spb_all_routes.html)
<!DOCTYPE html>
<html>
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
                #map_38096f242fd02d2a7f75f9e167acf6ea {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>
    
    
            <div class="folium-map" id="map_38096f242fd02d2a7f75f9e167acf6ea" ></div>
        
</body>
<script>
    
    
            var map_38096f242fd02d2a7f75f9e167acf6ea = L.map(
                "map_38096f242fd02d2a7f75f9e167acf6ea",
                {
                    center: [59.935, 30.325],
                    crs: L.CRS.EPSG3857,
                    zoom: 13,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_d2979c951a091ed57c6acd5ecc82d811 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_38096f242fd02d2a7f75f9e167acf6ea);
        
    
            var feature_group_e1c9942ce684522cce637faff1b9ea03 = L.featureGroup(
                {}
            ).addTo(map_38096f242fd02d2a7f75f9e167acf6ea);
        
    
            var poly_line_faa9c225fe8f4ea27111d1b467755acf = L.polyline(
                [[59.9326, 30.3462], [59.9398, 30.3146], [59.9553, 30.3067], [59.9622, 30.3008], [59.9316, 30.3552], [59.9666, 30.3115]],
                {"bubblingMouseEvents": true, "color": "blue", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "blue", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 0.7, "smoothFactor": 1.0, "stroke": true, "weight": 4}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var marker_f2975fe8ac151320ed837ce5f04cb430 = L.marker(
                [59.9326, 30.3462],
                {}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var icon_8836764b2c1552939aedd8dc1bbd886c = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_f2975fe8ac151320ed837ce5f04cb430.setIcon(icon_8836764b2c1552939aedd8dc1bbd886c);
        
    
        var popup_cc416a48b0c6b998b47ba28c07c58672 = L.popup({"maxWidth": "100%"});

        
            var html_e3bbeb5a826010eba3538795bbaf4a14 = $(`<div id="html_e3bbeb5a826010eba3538795bbaf4a14" style="width: 100.0%; height: 100.0%;">1. Coffe Roasters</div>`)[0];
            popup_cc416a48b0c6b998b47ba28c07c58672.setContent(html_e3bbeb5a826010eba3538795bbaf4a14);
        

        marker_f2975fe8ac151320ed837ce5f04cb430.bindPopup(popup_cc416a48b0c6b998b47ba28c07c58672)
        ;

        
    
    
            var marker_e4c41d925b7e6a111f3dec95cf169842 = L.marker(
                [59.9398, 30.3146],
                {}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var icon_19886ff333dc5cb7bf21f64cc66c5255 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_e4c41d925b7e6a111f3dec95cf169842.setIcon(icon_19886ff333dc5cb7bf21f64cc66c5255);
        
    
        var popup_6cda6d4d4a8caa300fb4e8b9a203bd04 = L.popup({"maxWidth": "100%"});

        
            var html_e17c477c3a99a81cea020f538fa5cb40 = $(`<div id="html_e17c477c3a99a81cea020f538fa5cb40" style="width: 100.0%; height: 100.0%;">2. Эрмитаж</div>`)[0];
            popup_6cda6d4d4a8caa300fb4e8b9a203bd04.setContent(html_e17c477c3a99a81cea020f538fa5cb40);
        

        marker_e4c41d925b7e6a111f3dec95cf169842.bindPopup(popup_6cda6d4d4a8caa300fb4e8b9a203bd04)
        ;

        
    
    
            var marker_c8d31ce726f8bbd5618c46b693d5db73 = L.marker(
                [59.9553, 30.3067],
                {}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var icon_d639c1fb2648210c46a741bb0cf91622 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_c8d31ce726f8bbd5618c46b693d5db73.setIcon(icon_d639c1fb2648210c46a741bb0cf91622);
        
    
        var popup_fa3775dce4f5881fe9aae1adf02842bd = L.popup({"maxWidth": "100%"});

        
            var html_75593c0c65ebf5304639d2af72dc8e53 = $(`<div id="html_75593c0c65ebf5304639d2af72dc8e53" style="width: 100.0%; height: 100.0%;">3. Артмуза</div>`)[0];
            popup_fa3775dce4f5881fe9aae1adf02842bd.setContent(html_75593c0c65ebf5304639d2af72dc8e53);
        

        marker_c8d31ce726f8bbd5618c46b693d5db73.bindPopup(popup_fa3775dce4f5881fe9aae1adf02842bd)
        ;

        
    
    
            var marker_cbc5fcb1fa08b8636534a99199a8d88d = L.marker(
                [59.9622, 30.3008],
                {}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var icon_9aa915b95b7285e5c068cdd9ae7303a2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_cbc5fcb1fa08b8636534a99199a8d88d.setIcon(icon_9aa915b95b7285e5c068cdd9ae7303a2);
        
    
        var popup_792299a1ae70f494c4c2b868a6fed6ae = L.popup({"maxWidth": "100%"});

        
            var html_8f5d26659d95f37582c9c90cef70a193 = $(`<div id="html_8f5d26659d95f37582c9c90cef70a193" style="width: 100.0%; height: 100.0%;">4. Скуратов Петроградка</div>`)[0];
            popup_792299a1ae70f494c4c2b868a6fed6ae.setContent(html_8f5d26659d95f37582c9c90cef70a193);
        

        marker_cbc5fcb1fa08b8636534a99199a8d88d.bindPopup(popup_792299a1ae70f494c4c2b868a6fed6ae)
        ;

        
    
    
            var marker_1803e0697eb4884bd4273f13dceea268 = L.marker(
                [59.9316, 30.3552],
                {}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var icon_f6335b0064a1cef4a91e7d81e8a3ab09 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_1803e0697eb4884bd4273f13dceea268.setIcon(icon_f6335b0064a1cef4a91e7d81e8a3ab09);
        
    
        var popup_694e2105580327132d19b4016fa89c9f = L.popup({"maxWidth": "100%"});

        
            var html_566a61977b38d24649cc442be5a6c294 = $(`<div id="html_566a61977b38d24649cc442be5a6c294" style="width: 100.0%; height: 100.0%;">5. Tetto</div>`)[0];
            popup_694e2105580327132d19b4016fa89c9f.setContent(html_566a61977b38d24649cc442be5a6c294);
        

        marker_1803e0697eb4884bd4273f13dceea268.bindPopup(popup_694e2105580327132d19b4016fa89c9f)
        ;

        
    
    
            var marker_4835aef4fa54a4397e0da8b3e6c44709 = L.marker(
                [59.9666, 30.3115],
                {}
            ).addTo(feature_group_e1c9942ce684522cce637faff1b9ea03);
        
    
            var icon_87c22cc3f2508d0179f0d9e7f7e31f01 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "blue", "prefix": "glyphicon"}
            );
            marker_4835aef4fa54a4397e0da8b3e6c44709.setIcon(icon_87c22cc3f2508d0179f0d9e7f7e31f01);
        
    
        var popup_ea584852399b91be47e23ed15e2640c0 = L.popup({"maxWidth": "100%"});

        
            var html_d15d9dc3829b8667ce892e7d8d592ea8 = $(`<div id="html_d15d9dc3829b8667ce892e7d8d592ea8" style="width: 100.0%; height: 100.0%;">6. Кино Мираж</div>`)[0];
            popup_ea584852399b91be47e23ed15e2640c0.setContent(html_d15d9dc3829b8667ce892e7d8d592ea8);
        

        marker_4835aef4fa54a4397e0da8b3e6c44709.bindPopup(popup_ea584852399b91be47e23ed15e2640c0)
        ;

        
    
    
            var feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd = L.featureGroup(
                {}
            ).addTo(map_38096f242fd02d2a7f75f9e167acf6ea);
        
    
            var poly_line_f3453c687635e0978abcf93948be535f = L.polyline(
                [[59.9303, 30.3229], [59.9235, 30.3494], [59.9278, 30.344], [59.9298, 30.3523], [59.9309, 30.3208], [59.9336, 30.3276]],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "green", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 0.7, "smoothFactor": 1.0, "stroke": true, "weight": 4}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var marker_464834b83fdad175503870e743ed58e6 = L.marker(
                [59.9303, 30.3229],
                {}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var icon_73a4bf0f45e0c394fb9a270ecf256f3f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_464834b83fdad175503870e743ed58e6.setIcon(icon_73a4bf0f45e0c394fb9a270ecf256f3f);
        
    
        var popup_336c867c3074413b5b2942518767d9e7 = L.popup({"maxWidth": "100%"});

        
            var html_f5791f7c3ed0fcba64238b413c72ff38 = $(`<div id="html_f5791f7c3ed0fcba64238b413c72ff38" style="width: 100.0%; height: 100.0%;">1. Bistrot Le Moujik</div>`)[0];
            popup_336c867c3074413b5b2942518767d9e7.setContent(html_f5791f7c3ed0fcba64238b413c72ff38);
        

        marker_464834b83fdad175503870e743ed58e6.bindPopup(popup_336c867c3074413b5b2942518767d9e7)
        ;

        
    
    
            var marker_ca15fe6be35720c2581fdc673c767700 = L.marker(
                [59.9235, 30.3494],
                {}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var icon_1325a4f7ed9e932522576a86662fd91f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_ca15fe6be35720c2581fdc673c767700.setIcon(icon_1325a4f7ed9e932522576a86662fd91f);
        
    
        var popup_878e1525a302da45c8a145dff5ca16de = L.popup({"maxWidth": "100%"});

        
            var html_e699d340676011d334b05c69138c0b7a = $(`<div id="html_e699d340676011d334b05c69138c0b7a" style="width: 100.0%; height: 100.0%;">2. Музей сновидений Фрейда</div>`)[0];
            popup_878e1525a302da45c8a145dff5ca16de.setContent(html_e699d340676011d334b05c69138c0b7a);
        

        marker_ca15fe6be35720c2581fdc673c767700.bindPopup(popup_878e1525a302da45c8a145dff5ca16de)
        ;

        
    
    
            var marker_fc44f2f29121fa40948079246f786f14 = L.marker(
                [59.9278, 30.344],
                {}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var icon_a4e17dcc6ecab9829d48759a07f03329 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_fc44f2f29121fa40948079246f786f14.setIcon(icon_a4e17dcc6ecab9829d48759a07f03329);
        
    
        var popup_95406ed4d15a0ca95c352a4ed8b90725 = L.popup({"maxWidth": "100%"});

        
            var html_c51cbce30fc8a23c4ae17562565b078e = $(`<div id="html_c51cbce30fc8a23c4ae17562565b078e" style="width: 100.0%; height: 100.0%;">3. Bolshe Coffee</div>`)[0];
            popup_95406ed4d15a0ca95c352a4ed8b90725.setContent(html_c51cbce30fc8a23c4ae17562565b078e);
        

        marker_fc44f2f29121fa40948079246f786f14.bindPopup(popup_95406ed4d15a0ca95c352a4ed8b90725)
        ;

        
    
    
            var marker_593b6114a024a1817005b2b1c4728b83 = L.marker(
                [59.9298, 30.3523],
                {}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var icon_c54bbd31b3ee382b323f363b82e7fc32 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_593b6114a024a1817005b2b1c4728b83.setIcon(icon_c54bbd31b3ee382b323f363b82e7fc32);
        
    
        var popup_6d68e36194a6f12eca6817f03b8628dc = L.popup({"maxWidth": "100%"});

        
            var html_320bb5fd8481cd0cac43638edf14f5a9 = $(`<div id="html_320bb5fd8481cd0cac43638edf14f5a9" style="width: 100.0%; height: 100.0%;">4. Музей звука</div>`)[0];
            popup_6d68e36194a6f12eca6817f03b8628dc.setContent(html_320bb5fd8481cd0cac43638edf14f5a9);
        

        marker_593b6114a024a1817005b2b1c4728b83.bindPopup(popup_6d68e36194a6f12eca6817f03b8628dc)
        ;

        
    
    
            var marker_94c0090dc5ebf4a432f6e75aa03f3459 = L.marker(
                [59.9309, 30.3208],
                {}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var icon_b5f121d00fb58f0ff5e8a3954b5fe5e2 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_94c0090dc5ebf4a432f6e75aa03f3459.setIcon(icon_b5f121d00fb58f0ff5e8a3954b5fe5e2);
        
    
        var popup_69af772a34d3c903e2857a2e7baefab1 = L.popup({"maxWidth": "100%"});

        
            var html_7df1514c84eaf0b420426990d0f43e89 = $(`<div id="html_7df1514c84eaf0b420426990d0f43e89" style="width: 100.0%; height: 100.0%;">5. Flori</div>`)[0];
            popup_69af772a34d3c903e2857a2e7baefab1.setContent(html_7df1514c84eaf0b420426990d0f43e89);
        

        marker_94c0090dc5ebf4a432f6e75aa03f3459.bindPopup(popup_69af772a34d3c903e2857a2e7baefab1)
        ;

        
    
    
            var marker_a9d9ebd827313ae1cd865386c2e6570e = L.marker(
                [59.9336, 30.3276],
                {}
            ).addTo(feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd);
        
    
            var icon_46ffd3d030e25ca8bedc96a73532b3df = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "green", "prefix": "glyphicon"}
            );
            marker_a9d9ebd827313ae1cd865386c2e6570e.setIcon(icon_46ffd3d030e25ca8bedc96a73532b3df);
        
    
        var popup_c1e7b3b8e8c131d36811d49b3f1ccb76 = L.popup({"maxWidth": "100%"});

        
            var html_4eebed929e74ad96d7f5060fcf8649e2 = $(`<div id="html_4eebed929e74ad96d7f5060fcf8649e2" style="width: 100.0%; height: 100.0%;">6. Бар Cabinet</div>`)[0];
            popup_c1e7b3b8e8c131d36811d49b3f1ccb76.setContent(html_4eebed929e74ad96d7f5060fcf8649e2);
        

        marker_a9d9ebd827313ae1cd865386c2e6570e.bindPopup(popup_c1e7b3b8e8c131d36811d49b3f1ccb76)
        ;

        
    
    
            var feature_group_1994124137961db67f4c5774604f0336 = L.featureGroup(
                {}
            ).addTo(map_38096f242fd02d2a7f75f9e167acf6ea);
        
    
            var poly_line_f7457ca23979a095ff33b49c6a9a16e6 = L.polyline(
                [[59.9292, 30.2902], [59.9292, 30.2902], [59.9339, 30.3063], [59.9554, 30.3036], [59.9663, 30.3114], [59.9718, 30.3004], [59.9602, 30.2926], [59.9558, 30.3188]],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "red", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 0.7, "smoothFactor": 1.0, "stroke": true, "weight": 4}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var marker_492b3c20f7e63405548b5c0aa80bcf92 = L.marker(
                [59.9292, 30.2902],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_90157fc192f3df7dd83d2053c9f66e18 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_492b3c20f7e63405548b5c0aa80bcf92.setIcon(icon_90157fc192f3df7dd83d2053c9f66e18);
        
    
        var popup_1cbac6341a7ae173e8c489f77418d6d1 = L.popup({"maxWidth": "100%"});

        
            var html_68138364c4f458de3ca7adc7872b171e = $(`<div id="html_68138364c4f458de3ca7adc7872b171e" style="width: 100.0%; height: 100.0%;">1. Скуратов Новая Голландия</div>`)[0];
            popup_1cbac6341a7ae173e8c489f77418d6d1.setContent(html_68138364c4f458de3ca7adc7872b171e);
        

        marker_492b3c20f7e63405548b5c0aa80bcf92.bindPopup(popup_1cbac6341a7ae173e8c489f77418d6d1)
        ;

        
    
    
            var marker_36fb2791b8915af39c8b8231bc99b2ba = L.marker(
                [59.9292, 30.2902],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_bd41c86691413f837055ace5f53aa799 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_36fb2791b8915af39c8b8231bc99b2ba.setIcon(icon_bd41c86691413f837055ace5f53aa799);
        
    
        var popup_17d548a7a3cfe0c06b183cdf69cb5e4a = L.popup({"maxWidth": "100%"});

        
            var html_ebca8ab020c43065bba28e8ff80b097a = $(`<div id="html_ebca8ab020c43065bba28e8ff80b097a" style="width: 100.0%; height: 100.0%;">2. Новая Голландия (прогулка)</div>`)[0];
            popup_17d548a7a3cfe0c06b183cdf69cb5e4a.setContent(html_ebca8ab020c43065bba28e8ff80b097a);
        

        marker_36fb2791b8915af39c8b8231bc99b2ba.bindPopup(popup_17d548a7a3cfe0c06b183cdf69cb5e4a)
        ;

        
    
    
            var marker_61bf1b2d491dea6b5b826db2605c02b2 = L.marker(
                [59.9339, 30.3063],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_0a6090f960799ce86201e506b5d93b0f = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_61bf1b2d491dea6b5b826db2605c02b2.setIcon(icon_0a6090f960799ce86201e506b5d93b0f);
        
    
        var popup_ef2091784eb8c01f1b45c262b2060d49 = L.popup({"maxWidth": "100%"});

        
            var html_72ec33cf10b80bec95ac48c0c35f9208 = $(`<div id="html_72ec33cf10b80bec95ac48c0c35f9208" style="width: 100.0%; height: 100.0%;">3. Исаакиевская площадь</div>`)[0];
            popup_ef2091784eb8c01f1b45c262b2060d49.setContent(html_72ec33cf10b80bec95ac48c0c35f9208);
        

        marker_61bf1b2d491dea6b5b826db2605c02b2.bindPopup(popup_ef2091784eb8c01f1b45c262b2060d49)
        ;

        
    
    
            var marker_c967355db535498ad38a2b61836509de = L.marker(
                [59.9554, 30.3036],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_56d41f6726d49bbe108f0cd29bad2613 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_c967355db535498ad38a2b61836509de.setIcon(icon_56d41f6726d49bbe108f0cd29bad2613);
        
    
        var popup_151e2ff03d954fca03031bcd03805313 = L.popup({"maxWidth": "100%"});

        
            var html_ecd835b6da4771d3521143eaa09f511b = $(`<div id="html_ecd835b6da4771d3521143eaa09f511b" style="width: 100.0%; height: 100.0%;">4. Кронверкский проток (набережная)</div>`)[0];
            popup_151e2ff03d954fca03031bcd03805313.setContent(html_ecd835b6da4771d3521143eaa09f511b);
        

        marker_c967355db535498ad38a2b61836509de.bindPopup(popup_151e2ff03d954fca03031bcd03805313)
        ;

        
    
    
            var marker_16a010a2a918d57832ee34121061b719 = L.marker(
                [59.9663, 30.3114],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_1517ad8adbb062690cd49e08eb4a3b42 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_16a010a2a918d57832ee34121061b719.setIcon(icon_1517ad8adbb062690cd49e08eb4a3b42);
        
    
        var popup_73bcf76e50c40db7bc19eec82844205e = L.popup({"maxWidth": "100%"});

        
            var html_0ea349b4040961697fd46b0b94b531ba = $(`<div id="html_0ea349b4040961697fd46b0b94b531ba" style="width: 100.0%; height: 100.0%;">5. Двор-колодец Каменоостровский 44Б</div>`)[0];
            popup_73bcf76e50c40db7bc19eec82844205e.setContent(html_0ea349b4040961697fd46b0b94b531ba);
        

        marker_16a010a2a918d57832ee34121061b719.bindPopup(popup_73bcf76e50c40db7bc19eec82844205e)
        ;

        
    
    
            var marker_95eb62649bb611f2114ef882a2e44db0 = L.marker(
                [59.9718, 30.3004],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_3fdab01fa8d5a0476331351064c98870 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_95eb62649bb611f2114ef882a2e44db0.setIcon(icon_3fdab01fa8d5a0476331351064c98870);
        
    
        var popup_fa4067b373f463f64e26c1990f76c6bc = L.popup({"maxWidth": "100%"});

        
            var html_55958530afc272a838056c55bc7a2ae7 = $(`<div id="html_55958530afc272a838056c55bc7a2ae7" style="width: 100.0%; height: 100.0%;">6. Набережная реки Карповки</div>`)[0];
            popup_fa4067b373f463f64e26c1990f76c6bc.setContent(html_55958530afc272a838056c55bc7a2ae7);
        

        marker_95eb62649bb611f2114ef882a2e44db0.bindPopup(popup_fa4067b373f463f64e26c1990f76c6bc)
        ;

        
    
    
            var marker_18e1c766761cb0b481c6aed01ae8cbf4 = L.marker(
                [59.9602, 30.2926],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_d8a54ca1b25f6995fb5a2acab547a53b = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_18e1c766761cb0b481c6aed01ae8cbf4.setIcon(icon_d8a54ca1b25f6995fb5a2acab547a53b);
        
    
        var popup_65c0909369560fd54bff7d4f2ba6b4d3 = L.popup({"maxWidth": "100%"});

        
            var html_31fe3554d710da36c4060d3204c05a27 = $(`<div id="html_31fe3554d710da36c4060d3204c05a27" style="width: 100.0%; height: 100.0%;">7. Двор-колодец Большой проспект ПС 160</div>`)[0];
            popup_65c0909369560fd54bff7d4f2ba6b4d3.setContent(html_31fe3554d710da36c4060d3204c05a27);
        

        marker_18e1c766761cb0b481c6aed01ae8cbf4.bindPopup(popup_65c0909369560fd54bff7d4f2ba6b4d3)
        ;

        
    
    
            var marker_ead7af3a6ca64bbfc94de04daa6a8369 = L.marker(
                [59.9558, 30.3188],
                {}
            ).addTo(feature_group_1994124137961db67f4c5774604f0336);
        
    
            var icon_b4723fe7f3d390a9d1779114f5d0d324 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "red", "prefix": "glyphicon"}
            );
            marker_ead7af3a6ca64bbfc94de04daa6a8369.setIcon(icon_b4723fe7f3d390a9d1779114f5d0d324);
        
    
        var popup_a28f7a3c841035dfbf7e09e09f0ccc80 = L.popup({"maxWidth": "100%"});

        
            var html_79331b7505f5023304e88b5efd88fafd = $(`<div id="html_79331b7505f5023304e88b5efd88fafd" style="width: 100.0%; height: 100.0%;">8. Ресторан Solids</div>`)[0];
            popup_a28f7a3c841035dfbf7e09e09f0ccc80.setContent(html_79331b7505f5023304e88b5efd88fafd);
        

        marker_ead7af3a6ca64bbfc94de04daa6a8369.bindPopup(popup_a28f7a3c841035dfbf7e09e09f0ccc80)
        ;

        
    
    
            var feature_group_cf523ec062ed8b0cc440e5533d43371c = L.featureGroup(
                {}
            ).addTo(map_38096f242fd02d2a7f75f9e167acf6ea);
        
    
            var poly_line_53bc62c7a0c03f329c1f329226a6cf02 = L.polyline(
                [[59.9303, 30.3229], [59.9448, 30.3701], [59.9713, 30.2593], [59.9692, 30.282], [59.96, 30.3208], [59.9309, 30.3208]],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": false, "fillColor": "orange", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 0.7, "smoothFactor": 1.0, "stroke": true, "weight": 4}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var marker_2fbcc0509868eec53fe4b8a2c90e0bb9 = L.marker(
                [59.9303, 30.3229],
                {}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var icon_feb3af4c78be20e9d1cbfc7f5bc27bc5 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_2fbcc0509868eec53fe4b8a2c90e0bb9.setIcon(icon_feb3af4c78be20e9d1cbfc7f5bc27bc5);
        
    
        var popup_b4a8c313ca82931a73aadcea0e4c0fee = L.popup({"maxWidth": "100%"});

        
            var html_2f4434f0ebbe1189e1bae272749ff813 = $(`<div id="html_2f4434f0ebbe1189e1bae272749ff813" style="width: 100.0%; height: 100.0%;">1. Bistrot Le Moujik</div>`)[0];
            popup_b4a8c313ca82931a73aadcea0e4c0fee.setContent(html_2f4434f0ebbe1189e1bae272749ff813);
        

        marker_2fbcc0509868eec53fe4b8a2c90e0bb9.bindPopup(popup_b4a8c313ca82931a73aadcea0e4c0fee)
        ;

        
    
    
            var marker_4de8e25a4c83189490ef263d9091db51 = L.marker(
                [59.9448, 30.3701],
                {}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var icon_d71bac0734e759df60a2c1c8eeafae5d = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_4de8e25a4c83189490ef263d9091db51.setIcon(icon_d71bac0734e759df60a2c1c8eeafae5d);
        
    
        var popup_68297c2839160318b71e4e5a0d2e3931 = L.popup({"maxWidth": "100%"});

        
            var html_fb9a3402c62d6822973bcccfd6a14762 = $(`<div id="html_fb9a3402c62d6822973bcccfd6a14762" style="width: 100.0%; height: 100.0%;">2. Таврический сад</div>`)[0];
            popup_68297c2839160318b71e4e5a0d2e3931.setContent(html_fb9a3402c62d6822973bcccfd6a14762);
        

        marker_4de8e25a4c83189490ef263d9091db51.bindPopup(popup_68297c2839160318b71e4e5a0d2e3931)
        ;

        
    
    
            var marker_c31365af375a7ec536bf61a2c07a65d0 = L.marker(
                [59.9713, 30.2593],
                {}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var icon_e114947c2f91e23573ee7b0d756fb5f3 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_c31365af375a7ec536bf61a2c07a65d0.setIcon(icon_e114947c2f91e23573ee7b0d756fb5f3);
        
    
        var popup_9edca93f0dbddefae60af8ef9ea36632 = L.popup({"maxWidth": "100%"});

        
            var html_9a1f53f7d80c547cb07d18c7a6bc0179 = $(`<div id="html_9a1f53f7d80c547cb07d18c7a6bc0179" style="width: 100.0%; height: 100.0%;">3. Елагин остров</div>`)[0];
            popup_9edca93f0dbddefae60af8ef9ea36632.setContent(html_9a1f53f7d80c547cb07d18c7a6bc0179);
        

        marker_c31365af375a7ec536bf61a2c07a65d0.bindPopup(popup_9edca93f0dbddefae60af8ef9ea36632)
        ;

        
    
    
            var marker_d2c57ef20e1a01e7baddde1a5d2f9b54 = L.marker(
                [59.9692, 30.282],
                {}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var icon_16f16a77be56b262f6ac7031ae04a9b0 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_d2c57ef20e1a01e7baddde1a5d2f9b54.setIcon(icon_16f16a77be56b262f6ac7031ae04a9b0);
        
    
        var popup_7a58bb5eef4af1a24dbc30df95379f3b = L.popup({"maxWidth": "100%"});

        
            var html_5569c2345d56b68203db275b81d1454f = $(`<div id="html_5569c2345d56b68203db275b81d1454f" style="width: 100.0%; height: 100.0%;">4. Кофейня (по пути с Елагина)</div>`)[0];
            popup_7a58bb5eef4af1a24dbc30df95379f3b.setContent(html_5569c2345d56b68203db275b81d1454f);
        

        marker_d2c57ef20e1a01e7baddde1a5d2f9b54.bindPopup(popup_7a58bb5eef4af1a24dbc30df95379f3b)
        ;

        
    
    
            var marker_f1ab2f6d6e2f4b05f7eb621d55d129d1 = L.marker(
                [59.96, 30.3208],
                {}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var icon_0ae09c2bd398454c3c25203782b41531 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_f1ab2f6d6e2f4b05f7eb621d55d129d1.setIcon(icon_0ae09c2bd398454c3c25203782b41531);
        
    
        var popup_be7012eb840f90d44d8e0ae883ab1d30 = L.popup({"maxWidth": "100%"});

        
            var html_5ae051dc5acc4ed614fef44e98671e3d = $(`<div id="html_5ae051dc5acc4ed614fef44e98671e3d" style="width: 100.0%; height: 100.0%;">5. Петроградская набережная</div>`)[0];
            popup_be7012eb840f90d44d8e0ae883ab1d30.setContent(html_5ae051dc5acc4ed614fef44e98671e3d);
        

        marker_f1ab2f6d6e2f4b05f7eb621d55d129d1.bindPopup(popup_be7012eb840f90d44d8e0ae883ab1d30)
        ;

        
    
    
            var marker_bd4000492ff53a096fd8fd17d6c520b8 = L.marker(
                [59.9309, 30.3208],
                {}
            ).addTo(feature_group_cf523ec062ed8b0cc440e5533d43371c);
        
    
            var icon_508eda13d7f62453a23fd6fb57528711 = L.AwesomeMarkers.icon(
                {"extraClasses": "fa-rotate-0", "icon": "info-sign", "iconColor": "white", "markerColor": "orange", "prefix": "glyphicon"}
            );
            marker_bd4000492ff53a096fd8fd17d6c520b8.setIcon(icon_508eda13d7f62453a23fd6fb57528711);
        
    
        var popup_f6512e53d9f337ab4386feca24bd7b79 = L.popup({"maxWidth": "100%"});

        
            var html_4212588b932f6d24b2ad4fa55f528e22 = $(`<div id="html_4212588b932f6d24b2ad4fa55f528e22" style="width: 100.0%; height: 100.0%;">6. Ресторан Flori</div>`)[0];
            popup_f6512e53d9f337ab4386feca24bd7b79.setContent(html_4212588b932f6d24b2ad4fa55f528e22);
        

        marker_bd4000492ff53a096fd8fd17d6c520b8.bindPopup(popup_f6512e53d9f337ab4386feca24bd7b79)
        ;

        
    
    
            var layer_control_2de5a6544ad9baf3c48f47fbe3a041ff = {
                base_layers : {
                    "openstreetmap" : tile_layer_d2979c951a091ed57c6acd5ecc82d811,
                },
                overlays :  {
                    "\u0414\u043e\u0436\u0434\u043b\u0438\u0432\u044b\u0439 \u0427\u0435\u0442\u0432\u0435\u0440\u0433" : feature_group_e1c9942ce684522cce637faff1b9ea03,
                    "\u0414\u043e\u0436\u0434\u043b\u0438\u0432\u0430\u044f \u041f\u044f\u0442\u043d\u0438\u0446\u0430" : feature_group_01e5cc0b0fc4c4f52db51c8e244ff3dd,
                    "\u0421\u043e\u043b\u043d\u0435\u0447\u043d\u044b\u0439 \u0427\u0435\u0442\u0432\u0435\u0440\u0433" : feature_group_1994124137961db67f4c5774604f0336,
                    "\u0421\u043e\u043b\u043d\u0435\u0447\u043d\u0430\u044f \u041f\u044f\u0442\u043d\u0438\u0446\u0430" : feature_group_cf523ec062ed8b0cc440e5533d43371c,
                },
            };
            L.control.layers(
                layer_control_2de5a6544ad9baf3c48f47fbe3a041ff.base_layers,
                layer_control_2de5a6544ad9baf3c48f47fbe3a041ff.overlays,
                {"autoZIndex": true, "collapsed": true, "position": "topright"}
            ).addTo(map_38096f242fd02d2a7f75f9e167acf6ea);
        
</script>
</html>
