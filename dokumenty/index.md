<!--{{pl/Development/NewGRF/inne strony| pl = pl/m4nfo/Extrazi/database |en=ttdpatch.de/grfspecs/m4nfoManual/menu }}--><!--
--><!--{{other languages | pl = User:Extrazi/database  }}--><!--
--><!----><!--{{-}}--><!----><!--<H2>--><div style="text-align:center; font-size:1.5em; font-weight:bold; background-color: #E7EBFF"> <small>[http://docs.openttd.org/source/index.html docs.openttd.org/source]</small> </div><!--<H2></H2>-->
<!--== ==-->
: <p></p>
<!-- ---- -->
<!--<div style="text-align:<!--center-->; font-size:1.2em; background-color: #E7EBFF; border: 1px solid #c7c8fe">'''.GRF'''</div>-->
<!--== .GRF ==-->
** [[database/formatGRF | Format pliku GRF ]]
** [[database/GRFcodec | GRFcodec ]] 
** <span title=R&D> [http://www.ttdpatch.de/grfspecs/ grfspecs ] </span>
=== .NFX - Kodowanie m4NFO <span title="przewinięcie na spód strony">[[database#spod|<small><sub>▼</sub></small>]]</span> ===
#     [[database/m4NFOmanual  | '''m4NFO Manual''' ]]
<!-- . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . -->
##    [[database/installation |  '''Instalacja''' ]]
###   [[database/basic        | Basic software ]]
###   [[database/download     |  Pobieranie ]]
###   [[database/instal |   Instalowanie ]] 
###   -
<!-- . . . . . . . . . . . . . . . . . instruktaż . . . . . . . . . . . . . . . . . -->
##    [[database/instrukcja | '''Instruktaż obsługi''' ]]  
###   [[database/basiConcepts | Koncepcje ]]  
####  [[database/basiConcepts#grf-files | Pliki GRF ]] 
####  [[database/basiConcepts#newgrf-files | pliki newGRF ]] 
####  [[database/basiConcepts#m4nfo-language-structure | Struktura języka ]] 
####  [[database/basiConcepts#features | Cechy ]] 
####  [[database/basiConcepts#structuring | Strukturyzacja plików źródłowych ]] 
###   Słownictwo i notacja
####  [[database/dataTypes | Typy danych ]] 
####  [[database/functionBlocks |  Bloki funkcyjne ]] 
####  Pojęcie grafiki
##### [[database/realSprites | Real sprites ]] 
##### {{#ifexist: database/recolourSprites | [[database/recolourSprites | Recolour sprites ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/RecolourSprites.html Recolour sprites] }}
##### {{#ifexist: database/spriteGrouping/Pl | [[database/spriteGrouping  | Sprite grouping ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/SpriteGrouping.html Sprite grouping] }}
##### {{#ifexist: database/spriteLayout | [[database/spriteLayout | Sprite layout ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/SpriteLayout.html Sprite layout] }}
####  [[database/conceptFunctions | Pojęcie funkcji ]] 
##### [[database/conceptFunctions#propertyfunctions | Funkcje właściwości ]] 
##### [[database/conceptFunctions#layoutfunctions | Funkcje układu ]] 
##### [[database/conceptFunctions#performancefunctions | Funkcje wydajności ]] 
##### [[database/conceptFunctions#auxiliaryfunctions | Funkcje pomocnicze ]] 
##### [[database/conceptFunctions#globalfunctions |Funkcje globalne ]] <!-- [http://www.ttdpatch.de/grfspecs/m4nfoManual/ConceptFunctions.html#GlobalFunctions Global functions] -->
##### Funkcje ogólne
<!-- . . . . . . . . . . . . . . . . . Ogólne  . . . . . . . . . . . . . . . . . -->
##    '''Ogólnie''' 
###   [[database/initialisation | newGRF initialisation ]] <!-- [http://www.ttdpatch.de/grfspecs/m4nfoManual/Initialisation.html newGRF initialisation] --> 
###   [[database/flowOfControl | <span title="Flow of control">Przepływ sterowania</span> & <br /> obsługa parametrów ]]  
###   {{#ifexist: database/errorHandling | [[database/errorHandling | Error handling ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ErrorHandling.html Error handling] }}
###   [[database/handlingCallbacks | Obsługa callbacks ]] 
###   [[database/textHandling | Obsługa tekstu ]] 
###   [[database/soundHandling | Obsługa dźwięku ]] 
###   {{#ifexist: database/recolouringFunctions | [[database/recolouringFunctions | Recolouring ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/RecolouringFunctions.html Recolouring]  }}
###   {{#ifexist: database/templating | [[database/templating | Templating ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Templating.html Templating] }}
###   [[database/globalFunctions | Funkcje globalne ]] 
###   [[database/generalFunctions | Funkcje ogólne ]] 
###   [[database/auxFunctions | Funkcje pomocnicze ]]  
###   [[database/m4nfoInternalFunctions | Funkcje <span title=internal >'wewnętrzne'</span> m4nfo ]]  
###   {{#ifexist: database/m4nfoInternalErrors | [[database/m4nfoInternalErrors | m4nfo internal error messages ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/m4nfoInternalErrors.html m4nfo internal error messages] }} 
<!-- . . . . . . . . . . . . . . . . . . Koleje . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/trains | [[database/trains | '''Trains''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Trains.html '''Trains''' ] }}
###   {{#ifexist: database/trainProperties | [[database/trainProperties | Train properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TrainProperties.html Train properties ] }}
####  {{#ifexist: database/priceCost | [[database/priceCost | New price and cost scheme ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/PriceCost.html New price and cost scheme ] }} 
###   {{#ifexist: database/trainFunctions | [[database/trainFunctions | Train functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TrainFunctions.html Train functions ] }}
###   {{#ifexist: database/trainCallbacks | [[database/trainCallbacks | Train callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TrainCallbacks.html Train callbacks ] }} 
<!-- . . . . . . . . . . . . . . . . . . Pojazdy drogowe . . . . . . . . . . . . . . . . -->
##    [http://www.ttdpatch.de/grfspecs/m4nfoManual/rvs.html '''Road vehicles''' ] 
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/rvsProperties.html Road vehicle properties ] 
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/rvsFunctions.html Road vehicle functions ] 
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/rvsCallbacks.html Road vehicle callbacks ] 
<!-- . . . . . . . . . . . . . . . . . . Statki  . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/ships | [[database/ships | '''Ships''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Ships.html '''Ships''' ] }}
###   {{#ifexist: database/shipProperties | [[database/shipProperties | Ship properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ShipProperties.html Ship properties ] }} 
###   {{#ifexist: database/shipFunctions| [[database/shipFunctions | Ship functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ShipFunctions.html Ship functions ] }} 
###   {{#ifexist: database/shipCallbacks/Pl | [[database/shipCallbacks | Ship callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ShipCallbacks.html Ship callbacks ] }} 
<!-- . . . . . . . . . . . . . . . . . . Stacje  . . . . . . . . . . . . . . . . -->
##    [[database/stations | '''Stacje''' ]]
###   [[database/stationProperties | Właściwości stacji ]] 
###   [[database/stationFunctions | Funkcje stacji ]]
###   [[database/stationCallbacks | Callbacks stacji ]]  
<!-- . . . . . . . . . . . . . . . . . Kanały . . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/canalsl | [[database/canals | '''Canals/rivers''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Canals.html '''Canals/rivers''' ] }}
###   {{#ifexist: database/canalProperties | [[database/canalProperties | Canal/river properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/CanalProperties.html Canal/river properties ] }}
###   {{#ifexist: database/canalFunctions | [[database/canalFunctions | Canal/river functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/CanalFunctions.html Canal/river functions ] }} 
<!-- . . . . . . . . . . . . . . . . . Mosty . . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/bridges | [[database/bridges | '''Bridges''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Bridges.html '''Bridges''' ] }}
###   {{#ifexist: database/bridgeProperties | [[database/bridgeProperties | '''Bridges''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/BridgeProperties.html Bridge properties ] }}
###   {{#ifexist: database/bridgeFunctions | [[database/bridgeFunctions | Bridge functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/BridgeFunctions.html Bridge functions ] }} 
<!-- . . . . . . . . . . . . . . . . . Domy . . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/houses | [[database/houses | '''Houses''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Houses.html '''Houses''' ] }}
###   {{#ifexist: database/houseProperties | [[database/houseProperties | House properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/HouseProperties.html House properties ] }}
###   {{#ifexist: database/houseFunctions | [[database/houseFunctions | House functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/HouseFunctions.html House functions ] }}
###   {{#ifexist: database/houseCallbacks | [[database/houseCallbacks | House callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/HouseCallbacks.html House callbacks ] }} 
<!-- . . . . . . . . . . . . . . . . . . kafle btanży . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/industrytiles | [[database/industrytiles | '''Industry tiles''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Industrytiles.html '''Industry tiles''' ] }}
###   {{#ifexist: database/industrytileProperties | [[database/industrytileProperties | Industry tile properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustrytileProperties.html Industry tile properties ] }}
###   {{#ifexist: database/idustrytileFunctions | [[database/idustrytileFunctions | Industry tile functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustrytileFunctions.html Industry tile functions ] }}
###   {{#ifexist: database/industrytileCallbacks | [[database/industrytileCallbacks | Industry tile callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustrytileCallbacks.html Industry tile callbacks ] }} 
<!-- . . . . . . . . . . . . . . . . . branże . . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/industries | [[database/industries | '''Industries''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Industries.html '''Industries''' ] }}
###   {{#ifexist: database/industryProperties | [[database/industryProperties | Industry properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryProperties.html Industry properties ] }}
###   {{#ifexist: database/industryFunctions | [[database/industryFunctions | Industry functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryFunctions.html Industry functions ] }}
###   {{#ifexist: database/industryCallbacks | [[database/industryCallbacks | Industry callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryCallbacks.html Industry callbacks ] }}
###   {{#ifexist: database/industryTypes | [[database/industryTypes | Industry types ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryTypes.html Industry types ] }} 
<!-- . . . . . . . . . . . . . . . . . Ładunki. . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/cargoes/Pl | [[database/cargoes | '''Cargoes''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Cargoes.html '''Cargoes''' ] }}
###   {{#ifexist: database/cargoProperties | [[database/cargoProperties | Cargo properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoProperties.html Cargo properties ] }}
###   {{#ifexist: database/cargoFunctions | [[database/cargoFunctions | Cargo functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoFunctions.html Cargo functions ] }}
###   {{#ifexist: database/cargoCallbacks | [[database/cargoCallbacks | Cargo callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoCallbacks.html Cargo callbacks ] }}
###   {{#ifexist: database/cargoTypes | [[database/cargoTypes | Cargo types/classes ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoTypes.html Cargo types/classes ] }} 
<!-- . . . . . . . . . . . . . . . . . Obiekty . . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/objects | [[database/objects | '''Objects''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Objects.html '''Objects''' ] }}
###   {{#ifexist: database/objectProperties | [[database/objectProperties | Object properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ObjectProperties.html Object properties ] }}
###   {{#ifexist: database/objectFunctions | [[database/objectFunctions | Object functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ObjectFunctions.html Object functions ] }}
###   {{#ifexist: database/objectCallbacks | [[database/objectCallbacks | Object callbacks ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/ObjectCallbacks.html Object callbacks ] }} 
<!-- . . . . . . . . . . . . . . . . . Typy kolei. . . . . . . . . . . . . . . . . -->
##    [[database/railTypes | '''Railtypes''' ]]
###   {{#ifexist: database/railTypeProperties | [[database/railTypeProperties | Railtype properties ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/RailtypeProperties.html Railtype properties] }}
###   [[database/railTypeFunctions | Railtype functions ]]
###   {{#ifexist: database/railTypeScheme | [[database/railTypeScheme | Standardized railtype scheme ]] |  [http://www.ttdpatch.de/grfspecs/m4nfoManual/RailtypeScheme.html Standardized railtype scheme] }} 
<!-- . . . . . . . . . . . . . . . . Miejscowości . . . . . . . . . . . . . . . . . . -->
##    {{#ifexist: database/towns | [[database/towns | '''Towns''' ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/Towns.html '''Towns'''] }}
###   {{#ifexist: database/townFunctions | [[database/townFunctions | Town functions ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TownFunctions.html Town functions] }}
<!-- . . . . . . . . . . . . . . . . Indeks . . . . . . . . . . . . . . . . . . -->
##    '''Index'''
###   [[database/indexGeneral | Ogólne ]] 
###   {{#ifexist: database/indexTrains | [[database/indexTrains | Trains ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexTrains.html Trains ] }}
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/Indexrvs.html Road vehicles ] 
###   {{#ifexist: database/indexShips | [[database/indexShips | Ships ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexShips.html Ships ] }}
###   [[database/indexStations | Stacje ]] 
###   {{#ifexist: database/indexHouses | [[database/indexHouses | Houses ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexHouses.html Houses ] }}
###   {{#ifexist: database/indexCanals | [[database/indexCanals | Canals/rivers ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexCanals.html Canals/rivers ] }}
###   {{#ifexist: user:extrazi/database/indexObjects | [[database/indexObjects | Objects ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexObjects.html Objects ] }}
###   {{#ifexist: database/indexIndustryTiles | [[database/indexIndustryTiles | Industry tiles ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexIndustrytiles.html Industry tiles ] }}
###   {{#ifexist: database/indexIndustries | [[database/indexIndustries | Industries ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexIndustries.html Industries ] }}
###   {{#ifexist: database/indexCargoes | [[database/indexCargoes | Cargoes ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexCargoes.html Cargoes ] }}
###   [[database/indexRailTypes | Typy <span title=Rail>torów</span> ]]<!-- [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexRailtypes.html Rail types ]-->
###   {{#ifexist: database/indexTowns | [[database/indexTowns | Towns ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexTowns.html Towns ] }} <br><!--
--><!--#:-->     __________________________________________________<!--__________-->
##<!--***--->    '''Raport techniczny'''
###   [[database/tR general | Ogólny ]] 
###   {{#ifexist: database/tR_trains | [[database/tR trains | Trains ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_trains.html Trains] }}
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_rvs.html Road vehicles] 
###   {{#ifexist: database/tR_ships | [[database/tR ships | Ships ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_ships.html Ships] }}
###   [[database/tR stations | Stacje ]]
###   {{#ifexist: database/tR_objects | [[database/tR objects | Objects ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_objects.html Objects] }}
###   {{#ifexist: database/tR_cargoes | [[database/tR cargoes | Cargoes ]] | [http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_cargoes.html Cargoes] }} <br><!--
--><!--<hr>--><!--#:--> __________________________________________________<!--__________-->
##***    '''Tutorial'''
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/BridgeTut.html Bridge tutorial]
###   [[database/callbacksTut |  Callback tutorial ]]
###   [[database/infoVersion32Tut | Kompilowanie newgrfs z 32 bpp i/lub dodatkowym zoomem ]] 
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/stackTut.html Composing vehicles from multiple sprites ] 
###   [[database/animObjectsTut | Animacja obiektu ]]
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/ParamTut.html Parameter usage ] 
###   [[database/stationsTut | Tutorial stacji ]]
###   [http://www.ttdpatch.de/grfspecs/m4nfoManual/ASLTut.html Using advanced sprite layouts ] 

<span id='spod' title="przewinięcie na top strony" style=float:right>[[database#top|<big>▲</big>]]</span> <!--<font color=white> ♪ 	 ♫ </font>-->
<!-- __NEWSECTIONLINK__ -->
