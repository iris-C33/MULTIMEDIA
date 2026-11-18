# Anima-son

<?xml version='1.0' encoding='utf-8'?>
<mlt LC_NUMERIC="en_US.UTF-8" producer="main_bin" root="C:/Users/2496462/Videos" version="7.43.0">
 <profile colorspace="709" description="HD 1080p 29.97 fps" display_aspect_den="9" display_aspect_num="16" frame_rate_den="1001" frame_rate_num="30000" height="1080" progressive="1" sample_aspect_den="1" sample_aspect_num="1" width="1920"/>
 <producer id="producer0" in="00:00:00.000" out="00:09:51.718">
  <property name="length">2147483647</property>
  <property name="eof">continue</property>
  <property name="resource">black</property>
  <property name="aspect_ratio">1</property>
  <property name="mlt_service">color</property>
  <property name="kdenlive:playlistid">black_track</property>
  <property name="mlt_image_format">rgba</property>
  <property name="set.test_audio">0</property>
 </producer>
 <playlist id="playlist0">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <playlist id="playlist1">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor0" in="00:00:00.000">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist0"/>
  <track hide="video" producer="playlist1"/>
  <filter id="filter0">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter1">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter2">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <producer id="producer1" in="00:00:00.000" out="00:04:03.837">
  <property name="length">7308</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2496462/OneDrive - Collège Montmorency/Vidéos/Animation avec son.kdenlive</property>
  <property name="aspect_ratio">1</property>
  <property name="mlt_service">consumer</property>
  <property name="kdenlive:clip_type">0</property>
  <property name="xml">was here</property>
  <property name="seekable">1</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">4</property>
  <property name="kdenlive:control_uuid">{c9065a9a-7b7c-428a-b625-3c31ae1267a6}</property>
  <property name="kdenlive:file_size">171008</property>
  <property name="kdenlive:file_hash">58175df319883dc021906378e202e784</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
  <property name="audio_index">0</property>
  <property name="astream">0</property>
 </producer>
 <playlist id="playlist2">
  <property name="kdenlive:audio_track">1</property>
  <blank length="00:00:47.848"/>
  <entry in="00:00:00.000" out="00:04:03.837" producer="producer1">
   <property name="kdenlive:id">4</property>
  </entry>
 </playlist>
 <playlist id="playlist3">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor1" in="00:00:00.000" out="00:04:51.685">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist2"/>
  <track hide="video" producer="playlist3"/>
  <filter id="filter3">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter4">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter5">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <producer id="producer2" in="00:00:00.000" out="00:04:03.837">
  <property name="length">7308</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2496462/OneDrive - Collège Montmorency/Vidéos/Animation avec son.kdenlive</property>
  <property name="aspect_ratio">1</property>
  <property name="mlt_service">consumer</property>
  <property name="kdenlive:clip_type">0</property>
  <property name="xml">was here</property>
  <property name="seekable">1</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">4</property>
  <property name="kdenlive:control_uuid">{c9065a9a-7b7c-428a-b625-3c31ae1267a6}</property>
  <property name="kdenlive:file_size">171008</property>
  <property name="kdenlive:file_hash">58175df319883dc021906378e202e784</property>
  <property name="set.test_audio">1</property>
  <property name="set.test_image">0</property>
 </producer>
 <playlist id="playlist4">
  <blank length="00:00:47.848"/>
  <entry in="00:00:00.000" out="00:04:03.837" producer="producer2">
   <property name="kdenlive:id">4</property>
  </entry>
 </playlist>
 <playlist id="playlist5"/>
 <tractor id="tractor2" in="00:00:00.000" out="00:04:51.685">
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="audio" producer="playlist4"/>
  <track hide="audio" producer="playlist5"/>
 </tractor>
 <playlist id="playlist6"/>
 <playlist id="playlist7"/>
 <tractor id="tractor3" in="00:00:00.000">
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="audio" producer="playlist6"/>
  <track hide="audio" producer="playlist7"/>
 </tractor>
 <tractor id="{20f385d9-d57e-443f-b3b1-4425e4a0ad38}" in="00:00:00.000" out="00:04:51.685">
  <property name="kdenlive:uuid">{20f385d9-d57e-443f-b3b1-4425e4a0ad38}</property>
  <property name="kdenlive:clipname">Sequence 1</property>
  <property name="kdenlive:sequenceproperties.hasAudio">1</property>
  <property name="kdenlive:sequenceproperties.hasVideo">1</property>
  <property name="kdenlive:sequenceproperties.activeTrack">1</property>
  <property name="kdenlive:sequenceproperties.tracksCount">4</property>
  <property name="kdenlive:sequenceproperties.documentuuid">{20f385d9-d57e-443f-b3b1-4425e4a0ad38}</property>
  <property name="kdenlive:control_uuid">{20f385d9-d57e-443f-b3b1-4425e4a0ad38}</property>
  <property name="kdenlive:duration">00:04:51.718</property>
  <property name="kdenlive:maxduration">8742</property>
  <property name="kdenlive:producer_type">17</property>
  <property name="kdenlive:id">3</property>
  <property name="kdenlive:clip_type">0</property>
  <property name="kdenlive:file_size">0</property>
  <property name="kdenlive:folderid">2</property>
  <property name="kdenlive:sequenceproperties.audioTarget">1</property>
  <property name="kdenlive:sequenceproperties.disablepreview">0</property>
  <property name="kdenlive:sequenceproperties.position">8742</property>
  <property name="kdenlive:sequenceproperties.scrollPos">11210</property>
  <property name="kdenlive:sequenceproperties.tracks">4</property>
  <property name="kdenlive:sequenceproperties.verticalzoom">1</property>
  <property name="kdenlive:sequenceproperties.videoTarget">2</property>
  <property name="kdenlive:sequenceproperties.zonein">0</property>
  <property name="kdenlive:sequenceproperties.zoneout">75</property>
  <property name="kdenlive:sequenceproperties.zoom">8</property>
  <property name="kdenlive:sequenceproperties.groups">[
    {
        "children": [
            {
                "data": "1:1434:-1",
                "leaf": "clip",
                "type": "Leaf"
            },
            {
                "data": "2:1434:-1",
                "leaf": "clip",
                "type": "Leaf"
            }
        ],
        "type": "AVSplit"
    }
]
</property>
  <property name="kdenlive:sequenceproperties.guides">[
]
</property>
  <track producer="producer0"/>
  <track producer="tractor0"/>
  <track producer="tractor1"/>
  <track producer="tractor2"/>
  <track producer="tractor3"/>
  <transition id="transition0">
   <property name="a_track">0</property>
   <property name="b_track">1</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition1">
   <property name="a_track">0</property>
   <property name="b_track">2</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition2">
   <property name="a_track">0</property>
   <property name="b_track">3</property>
   <property name="compositing">0</property>
   <property name="distort">0</property>
   <property name="rotate_center">0</property>
   <property name="mlt_service">qtblend</property>
   <property name="kdenlive_id">qtblend</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
  </transition>
  <transition id="transition3">
   <property name="a_track">0</property>
   <property name="b_track">4</property>
   <property name="compositing">0</property>
   <property name="distort">0</property>
   <property name="rotate_center">0</property>
   <property name="mlt_service">qtblend</property>
   <property name="kdenlive_id">qtblend</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
  </transition>
  <filter id="filter6">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter7">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <producer id="producer3" in="00:00:00.000" out="00:04:03.837">
  <property name="length">7308</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2496462/OneDrive - Collège Montmorency/Vidéos/Animation avec son.kdenlive</property>
  <property name="aspect_ratio">1</property>
  <property name="mlt_service">consumer</property>
  <property name="kdenlive:clip_type">0</property>
  <property name="xml">was here</property>
  <property name="seekable">1</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">4</property>
  <property name="kdenlive:control_uuid">{c9065a9a-7b7c-428a-b625-3c31ae1267a6}</property>
  <property name="kdenlive:file_size">171008</property>
  <property name="kdenlive:file_hash">58175df319883dc021906378e202e784</property>
  <property name="kdenlive:monitorPosition">902</property>
  <property name="kdenlive:clipzones">[
    {
        "in": 0,
        "name": "Zone 1",
        "out": 7307
    }
]
</property>
 </producer>
 <playlist id="main_bin">
  <property name="kdenlive:folder.-1.2">Sequences</property>
  <property name="kdenlive:sequenceFolder">2</property>
  <property name="kdenlive:docproperties.audioChannels">2</property>
  <property name="kdenlive:docproperties.binsort">0</property>
  <property name="kdenlive:docproperties.browserurl">C:/Users/2496462/Documents/</property>
  <property name="kdenlive:docproperties.documentid">1795022716168</property>
  <property name="kdenlive:docproperties.enableTimelineZone">0</property>
  <property name="kdenlive:docproperties.enableexternalproxy">0</property>
  <property name="kdenlive:docproperties.enableproxy">0</property>
  <property name="kdenlive:docproperties.externalproxyparams"/>
  <property name="kdenlive:docproperties.generateimageproxy">0</property>
  <property name="kdenlive:docproperties.generateproxy">0</property>
  <property name="kdenlive:docproperties.guidesCategories">[
    {
        "color": "#9b59b6",
        "comment": "Category 1",
        "index": 0
    },
    {
        "color": "#3daee9",
        "comment": "Category 2",
        "index": 1
    },
    {
        "color": "#1abc9c",
        "comment": "Category 3",
        "index": 2
    },
    {
        "color": "#1cdc9a",
        "comment": "Category 4",
        "index": 3
    },
    {
        "color": "#c9ce3b",
        "comment": "Category 5",
        "index": 4
    },
    {
        "color": "#fdbc4b",
        "comment": "Category 6",
        "index": 5
    },
    {
        "color": "#f39c1f",
        "comment": "Category 7",
        "index": 6
    },
    {
        "color": "#f47750",
        "comment": "Category 8",
        "index": 7
    },
    {
        "color": "#da4453",
        "comment": "Category 9",
        "index": 8
    }
]
</property>
  <property name="kdenlive:docproperties.kdenliveversion">26.08.2</property>
  <property name="kdenlive:docproperties.patchversion">1</property>
  <property name="kdenlive:docproperties.previewextension"/>
  <property name="kdenlive:docproperties.previewparameters"/>
  <property name="kdenlive:docproperties.profile">atsc_1080p_2997</property>
  <property name="kdenlive:docproperties.proxyextension"/>
  <property name="kdenlive:docproperties.proxyimageminsize">2000</property>
  <property name="kdenlive:docproperties.proxyimagesize">800</property>
  <property name="kdenlive:docproperties.proxyminsize">1000</property>
  <property name="kdenlive:docproperties.proxyparams"/>
  <property name="kdenlive:docproperties.proxyresize">640</property>
  <property name="kdenlive:docproperties.seekOffset">30000</property>
  <property name="kdenlive:docproperties.sessionid">{66eb152f-86cf-4bad-b459-902f1bbcb2f7}</property>
  <property name="kdenlive:docproperties.uuid">{20f385d9-d57e-443f-b3b1-4425e4a0ad38}</property>
  <property name="kdenlive:docproperties.version">1.1</property>
  <property name="kdenlive:expandedFolders"/>
  <property name="kdenlive:binZoom">4</property>
  <property name="kdenlive:extraBins">project_bin:-1:0</property>
  <property name="kdenlive:documentnotes"/>
  <property name="kdenlive:documentnotesversion">2</property>
  <property name="kdenlive:docproperties.opensequences">{20f385d9-d57e-443f-b3b1-4425e4a0ad38}</property>
  <property name="kdenlive:docproperties.activetimeline">{20f385d9-d57e-443f-b3b1-4425e4a0ad38}</property>
  <property name="kdenlive:docproperties.layout">{
    "allDockWidgets": [
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 1078,
                    "width": 1757,
                    "x": 2070,
                    "y": 1086
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 11,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    },
                    {
                        "indexOfFloatingWindow": 0,
                        "isFloatingWindow": true,
                        "itemIndex": 0
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "timeline"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "project_bin"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 3,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 3,
                "wasFloating": false
            },
            "uniqueName": "library"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "subtitles"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "textedit"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "timeremap"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "markers"
        },
        {
            "lastCloseReason": 1,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 0,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "screengrab"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 1,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "audiospectrum"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 3,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "clipmonitor"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "projectmonitor"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "clip_properties"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 4,
                "wasFloating": false
            },
            "uniqueName": "notes_widget"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 9,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "media_browser"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 10,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "onlineresources"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "effect_stack"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "effect_list"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "transition_list"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 283,
                    "width": 226,
                    "x": 5,
                    "y": 48
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "undo_history"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "mixer"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 6,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "vectorscope"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 5,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "waveform"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 7,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "rgb_parade"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 8,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "histogram"
        }
    ],
    "closedDockWidgets": [
        "project_bin",
        "library",
        "subtitles",
        "textedit",
        "timeremap",
        "markers",
        "screengrab",
        "audiospectrum",
        "notes_widget",
        "media_browser",
        "onlineresources",
        "effect_stack",
        "effect_list",
        "transition_list",
        "undo_history",
        "vectorscope",
        "waveform",
        "rgb_parade",
        "histogram"
    ],
    "floatingWindows": [
        {
            "flags": 32,
            "geometry": {
                "height": 1078,
                "width": 1757,
                "x": 2147,
                "y": 1090
            },
            "isVisible": true,
            "multiSplitterLayout": {
                "frames": {
                    "4555": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "timeline"
                        ],
                        "geometry": {
                            "height": 1021,
                            "width": 1745,
                            "x": 0,
                            "y": 0
                        },
                        "id": "4555",
                        "isNull": false,
                        "mainWindowUniqueName": "",
                        "objectName": "timeline",
                        "options": 0
                    }
                },
                "layout": {
                    "children": [
                        {
                            "guestId": "4555",
                            "isContainer": false,
                            "isVisible": true,
                            "sizingInfo": {
                                "geometry": {
                                    "height": 1021,
                                    "width": 1745,
                                    "x": 0,
                                    "y": 0
                                },
                                "maxSizeHint": {
                                    "height": 524293,
                                    "width": 524293
                                },
                                "minSize": {
                                    "height": 99,
                                    "width": 88
                                },
                                "percentageWithinParent": 1.0
                            }
                        }
                    ],
                    "isContainer": true,
                    "isVisible": false,
                    "orientation": 2,
                    "sizingInfo": {
                        "geometry": {
                            "height": 1021,
                            "width": 1745,
                            "x": 0,
                            "y": 0
                        },
                        "maxSizeHint": {
                            "height": 16777215,
                            "width": 16777215
                        },
                        "minSize": {
                            "height": 90,
                            "width": 80
                        },
                        "percentageWithinParent": 0.0
                    }
                }
            },
            "normalGeometry": {
                "height": 1078,
                "width": 1757,
                "x": 2147,
                "y": 1090
            },
            "parentIndex": 0,
            "screenIndex": 0,
            "screenSize": {
                "height": 2160,
                "width": 3840
            },
            "windowState": 0
        }
    ],
    "mainWindows": [
        {
            "affinities": null,
            "geometry": {
                "height": 2041,
                "width": 2212,
                "x": 1928,
                "y": 164
            },
            "isVisible": true,
            "multiSplitterLayout": {
                "frames": {
                    "4081": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "projectmonitor",
                            "textedit",
                            "notes_widget"
                        ],
                        "geometry": {
                            "height": 830,
                            "width": 762,
                            "x": 1446,
                            "y": 0
                        },
                        "id": "4081",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "projectmonitor",
                        "options": 0
                    },
                    "4178": {
                        "currentTabIndex": 3,
                        "dockWidgets": [
                            "project_bin",
                            "transition_list",
                            "effect_list",
                            "clip_properties",
                            "undo_history"
                        ],
                        "geometry": {
                            "height": 830,
                            "width": 385,
                            "x": 0,
                            "y": 0
                        },
                        "id": "4178",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "clip_properties",
                        "options": 0
                    },
                    "4357": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "mixer",
                            "effect_stack",
                            "timeremap",
                            "subtitles"
                        ],
                        "geometry": {
                            "height": 1078,
                            "width": 2208,
                            "x": 0,
                            "y": 830
                        },
                        "id": "4357",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "mixer",
                        "options": 0
                    },
                    "4493": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "clipmonitor",
                            "library"
                        ],
                        "geometry": {
                            "height": 830,
                            "width": 1061,
                            "x": 385,
                            "y": 0
                        },
                        "id": "4493",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "clipmonitor",
                        "options": 0
                    }
                },
                "layout": {
                    "children": [
                        {
                            "children": [
                                {
                                    "children": [
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 95,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524279
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 103,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524265,
                                                    "width": 524270
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "guestId": "4178",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 830,
                                                    "width": 385,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 295,
                                                    "width": 298
                                                },
                                                "percentageWithinParent": 0.1743659420289855
                                            }
                                        },
                                        {
                                            "guestId": "4493",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 830,
                                                    "width": 1061,
                                                    "x": 385,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 238,
                                                    "width": 326
                                                },
                                                "percentageWithinParent": 0.4805253623188406
                                            }
                                        },
                                        {
                                            "guestId": "4081",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 830,
                                                    "width": 762,
                                                    "x": 1446,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 439,
                                                    "width": 502
                                                },
                                                "percentageWithinParent": 0.3451086956521739
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 82,
                                                    "x": 1832,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 167,
                                                    "x": 1747,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524251
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 92,
                                                    "x": 1822,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 81,
                                                    "x": 1833,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 508,
                                                    "width": 478,
                                                    "x": 1074,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 523905,
                                                    "width": 523960
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 508,
                                                    "width": 378,
                                                    "x": 1536,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524174,
                                                    "width": 524011
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        }
                                    ],
                                    "isContainer": true,
                                    "isVisible": false,
                                    "orientation": 1,
                                    "sizingInfo": {
                                        "geometry": {
                                            "height": 830,
                                            "width": 2208,
                                            "x": 0,
                                            "y": 0
                                        },
                                        "maxSizeHint": {
                                            "height": 524325,
                                            "width": 1572879
                                        },
                                        "minSize": {
                                            "height": 439,
                                            "width": 1126
                                        },
                                        "percentageWithinParent": 0.4350104821802935
                                    }
                                },
                                {
                                    "children": [
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 1078,
                                                    "width": 1757,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524338,
                                                    "width": 524300
                                                },
                                                "minSize": {
                                                    "height": 144,
                                                    "width": 95
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "guestId": "4357",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 1078,
                                                    "width": 2208,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 269,
                                                    "width": 336
                                                },
                                                "percentageWithinParent": 1.0
                                            }
                                        }
                                    ],
                                    "isContainer": true,
                                    "isVisible": false,
                                    "orientation": 1,
                                    "sizingInfo": {
                                        "geometry": {
                                            "height": 1078,
                                            "width": 2208,
                                            "x": 0,
                                            "y": 830
                                        },
                                        "maxSizeHint": {
                                            "height": 524325,
                                            "width": 1048593
                                        },
                                        "minSize": {
                                            "height": 269,
                                            "width": 431
                                        },
                                        "percentageWithinParent": 0.5649895178197065
                                    }
                                }
                            ],
                            "isContainer": true,
                            "isVisible": false,
                            "orientation": 2,
                            "sizingInfo": {
                                "geometry": {
                                    "height": 1908,
                                    "width": 2208,
                                    "x": 0,
                                    "y": 0
                                },
                                "maxSizeHint": {
                                    "height": 1048650,
                                    "width": 1048593
                                },
                                "minSize": {
                                    "height": 708,
                                    "width": 1126
                                },
                                "percentageWithinParent": 1.0
                            }
                        }
                    ],
                    "isContainer": true,
                    "isVisible": false,
                    "orientation": 1,
                    "sizingInfo": {
                        "geometry": {
                            "height": 1908,
                            "width": 2208,
                            "x": 0,
                            "y": 0
                        },
                        "maxSizeHint": {
                            "height": 16777215,
                            "width": 16777215
                        },
                        "minSize": {
                            "height": 90,
                            "width": 80
                        },
                        "percentageWithinParent": 0.0
                    }
                }
            },
            "normalGeometry": {
                "height": 0,
                "width": 0,
                "x": 0,
                "y": 0
            },
            "options": 0,
            "screenIndex": 0,
            "screenSize": {
                "height": 2160,
                "width": 3840
            },
            "uniqueName": "KdenliveKDDock",
            "windowState": 0
        }
    ],
    "screenInfo": [
        {
            "devicePixelRatio": 1.0,
            "geometry": {
                "height": 2160,
                "width": 3840,
                "x": 0,
                "y": 0
            },
            "index": 0,
            "name": "CB322QK"
        }
    ],
    "serializationVersion": 3
}</property>
  <property name="xml_retain">1</property>
  <entry in="00:00:00.000" out="00:00:00.000" producer="{20f385d9-d57e-443f-b3b1-4425e4a0ad38}"/>
  <entry in="00:00:00.000" out="00:04:03.837" producer="producer3"/>
 </playlist>
 <tractor id="tractor4" in="00:00:00.000" out="00:04:51.685">
  <property name="kdenlive:projectTractor">1</property>
  <track in="00:00:00.000" out="00:04:51.685" producer="{20f385d9-d57e-443f-b3b1-4425e4a0ad38}"/>
 </tractor>
</mlt>
