---
∆. : database
--- 
# [docs.openttd.org/source](http://docs.openttd.org/source/index.html)
[![ottd]( /github-openttd.gif)](https://github.com/OpenTTD/OpenTTD/discussions)
## .GRF 
- **[Format pliku GRF ](https://github.com/extrazi/pl_m4nfo/wiki/formatGRF)** <br>
- **[GRFcodec](https://github.com/extrazi/pl_m4nfo/wiki/GRFcodec)** <br>
- **[grfspecs](http://www.ttdpatch.de/grfspecs/ )**

### .NFX - Kodowanie m4NFO <span title="przewinięcie na spód strony">[<small><sub>▼</sub></small>](index.md#spod)</span> 
A.		[**m4NFO Manual** ](database/m4NFOmanual) <br>
<!-- . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . -->
 1.	[**Instalacja**](database/installation) <br>
	I.		[Basic software](database/basic) <br>
	II.		[Pobieranie](database/download) <br>
	III.	[Instalowanie](database/instal) <br>
	IV.		• <br>
<!-- . . . . . . . . . . . . . . . . . instruktaż . . . . . . . . . . . . -->
 2.	[**Instruktaż obsługi**](database/instrukcja) <br>
	I.	[Koncepcje](database/basiConcepts ) <br>
		1.	[Pliki GRF](database/basiConcepts#grf-files) <br>
		2.	[pliki newGRF](database/basiConcepts#newgrf-files) <br>
		3.	[Struktura języka](database/basiConcepts#m4nfo-language-structure) <br>
		4.	[Cechy](database/basiConcepts#features) <br>
		5.	[Strukturyzacja plików źródłowych](database/basiConcepts#structuring) <br>
	II.	Słownictwo i notacja <br>
		1.	[Typy danych](database/dataTypes) <br>
		2.	[Bloki funkcyjne](database/functionBlocks) <br>
		3.	Pojęcie grafiki <br>
			I.		[Real sprites](database/realSprites) <br>
			II.		[Recolour sprites](http://www.ttdpatch.de/grfspecs/m4nfoManual/RecolourSprites.html) <br>
			III.	[Sprite grouping](http://www.ttdpatch.de/grfspecs/m4nfoManual/SpriteGrouping.html) <br>
			IV.		[Sprite layout](http://www.ttdpatch.de/grfspecs/m4nfoManual/SpriteLayout.html) <br>
		4.	[Pojęcie funkcji](database/conceptFunctions) <br>
			I.		[Funkcje właściwości](database/conceptFunctions#propertyfunctions) <br>
			II.		[Funkcje układu](database/conceptFunctions#layoutfunctions) <br>
			III.	[Funkcje wydajności](database/conceptFunctions#performancefunctions) <br>
			IV.		[Funkcje pomocnicze](database/conceptFunctions#auxiliaryfunctions) <br>
			V.		[Funkcje globalne](database/conceptFunctions#globalfunctions) <br>
			VI.		Funkcje ogólne <br>
<!-- . . . . . . . . . . . . . . . . . Ogólne  . . . . . . . . . . . . . -->
 3.	**Ogólnie** <br>
	I.		[newGRF initialisation](database/initialisation)  
	II.		[<span title="Flow of control">Przepływ sterowania</span> & <br /> obsługa parametrów](database/flowOfControl)  
	III.	[Error handling](http://www.ttdpatch.de/grfspecs/m4nfoManual/ErrorHandling.html) <br>
	IV.		[Obsługa callbacks](database/handlingCallbacks) <br>
	V.		[Obsługa tekstu](database/textHandling ) <br>
	VI.		[Obsługa dźwięku](database/soundHandling) <br>
	VII.	[Recolouring](http://www.ttdpatch.de/grfspecs/m4nfoManual/RecolouringFunctions.html) <br>
	VIII.	[Templating](http://www.ttdpatch.de/grfspecs/m4nfoManual/Templating.html) <br>
	IX.		[Funkcje globalne](database/globalFunctions) <br>
	X.		[Funkcje ogólne](database/generalFunctions) <br>
	XI.		[Funkcje pomocnicze](database/auxFunctions) <br>
	XII.	[Funkcje <span title=internal >'wewnętrzne'</span> m4nfo](database/m4nfoInternalFunctions) <br>
	XIII.	[m4nfo internal error messages](http://www.ttdpatch.de/grfspecs/m4nfoManual/m4nfoInternalErrors.html) <br>
<!-- . . . . . . . . . . . . . . . . . Koleje . . . . . . . . . . . . . . -->
 4.	[**Trains**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Trains.html) <br>
	I.		[Train properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/TrainProperties.html) <br>
		1.	[New price and cost scheme](http://www.ttdpatch.de/grfspecs/m4nfoManual/PriceCost.html) <br>
	II.		[Train functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/TrainFunctions.html) <br>
	III.	[Train callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/TrainCallbacks.html)  
<!-- . . . . . . . . . . . . . . . . . Pojazdy drogowe . . . . . . . . . -->
 5.	[**Road vehicles**](http://www.ttdpatch.de/grfspecs/m4nfoManual/rvs.html) <br>
	I.		[Road vehicle properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/rvsProperties.html) <br>
	II.		[Road vehicle functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/rvsFunctions.html) <br>
	III.	[Road vehicle callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/rvsCallbacks.html) <br>
<!-- . . . . . . . . . . . . . . . . . Statki  . . . . . . . . . . . . . -->
 6.	[**Ships**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Ships.html) <br>
	I.		[Ship properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/ShipProperties.html)  
	II.		[Ship functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/ShipFunctions.html) <br>
	III.	[Ship callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/ShipCallbacks.html) <br>
<!-- . . . . . . . . . . . . . . . . . Stacje  . . . . . . . . . . . . . -->
 7. [**Stacje**](database/stations) <br>
	I.		[Właściwości stacji](database/stationProperties) <br>
	II.		[Funkcje stacji](database/stationFunctions) <br>
	III.	[Callbacks stacji](database/stationCallbacks)  
<!-- . . . . . . . . . . . . . . . . . Kanały . . . . . . . . . . . . . . -->
 8.	[**Canals/rivers**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Canals.html) <br>
	I.	[Canal/river properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/CanalProperties.html) <br>
	II.	[Canal/river functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/CanalFunctions.html)  
<!-- . . . . . . . . . . . . . . . . . Mosty . . . . . . . . . . . . . . . -->
 9.	[**Bridges**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Bridges.html) <br>
	I.	[Bridge properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/BridgeProperties.html) <br>
	II.	[Bridge functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/BridgeFunctions.html)  
<!-- . . . . . . . . . . . . . . . . . Domy . . . . . . . . . . . . . . . . -->
 10.	[**Houses**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Houses.html) <br>
	I.		[House properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/HouseProperties.html) <br>
	II.		[House functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/HouseFunctions.html) <br>
	III.	[House callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/HouseCallbacks.html)  
<!-- . . . . . . . . . . . . . . . . . kafle btanży . . . . . . . . . . . . -->
 11.	[**Industry tiles**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Industrytiles.html) <br>
	I.		[Industry tile properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustrytileProperties.html) <br>
	II.		[Industry tile functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustrytileFunctions.html) <br>
	III.	[Industry tile callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustrytileCallbacks.html) <br>
<!-- . . . . . . . . . . . . . . . . . branże . . . . . . . . . . . . . . . -->
 12.	[**Industries**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Industries.html) <br>
	I.		[Industry properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryProperties.html) <br>
	II.		[Industry functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryFunctions.html) <br>
	III.	[Industry callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryCallbacks.html) <br>
	IV.		[Industry types](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndustryTypes.html)  
<!-- . . . . . . . . . . . . . . . . . Ładunki. . . . . . . . . . . . . . . -->
 13.	[**Cargoes**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Cargoes.html) <br>
	I.		[Cargo properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoProperties.html) <br>
	II.		[Cargo functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoFunctions.html) <br>
	III.	[Cargo callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoCallbacks.html) <br>
	IV.		[Cargo types/classes](http://www.ttdpatch.de/grfspecs/m4nfoManual/CargoTypes.html) <br>
<!-- . . . . . . . . . . . . . . . . . Obiekty . . . . . . . . . . . . . . . -->
 14.	[**Objects**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Objects.html) <br>
	I.		[Object properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/ObjectProperties.html) <br>
	II.		[Object functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/ObjectFunctions.html) <br>
	III.	[Object callbacks](http://www.ttdpatch.de/grfspecs/m4nfoManual/ObjectCallbacks.html) <br>
<!-- . . . . . . . . . . . . . . . . . Typy kolei. . . . . . . . . . . . . . -->
 15.	[**Railtypes**](database/railTypes) <br>
	I.		[Railtype properties](http://www.ttdpatch.de/grfspecs/m4nfoManual/RailtypeProperties.html) <br>
	II.		[Railtype functions](database/railTypeFunctions) <br>
	III.	[Standardized railtype scheme](http://www.ttdpatch.de/grfspecs/m4nfoManual/RailtypeScheme.html) <br>
<!-- . . . . . . . . . . . . . . . . Miejscowości . . . . . . . . . . . . . . -->
 16.	[**Towns**](http://www.ttdpatch.de/grfspecs/m4nfoManual/Towns.html) <br>
	I.		[Town functions](http://www.ttdpatch.de/grfspecs/m4nfoManual/TownFunctions.html) <br>
<!-- . . . . . . . . . . . . . . . . Indeks . . . . . . . . . . . . . . . . . -->
 17.	**Index** <br>
	I.		[Ogólne](database/indexGeneral) <br>
	II.		[Trains](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexTrains.html) <br>
	II.		[Road vehicles](http://www.ttdpatch.de/grfspecs/m4nfoManual/Indexrvs.html) <br>
	IV.		[Ships](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexShips.html) <br>
	V.		[Stacje](database/indexStations) <br>
	VI.		[Houses](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexHouses.html) <br>
	VII.	[Canals/rivers](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexCanals.html) <br>
	VIII.	[Objects](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexObjects.html) <br>
	IX.		[Industry tiles](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexIndustrytiles.html) <br>
	X.		[Industries](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexIndustries.html) <br>
	XI.		[Cargoes](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexCargoes.html) <br>
	XII.	[Typy <span title=Rail>torów</span>](database/indexRailTypes) <br>
	XIII.	[Towns](http://www.ttdpatch.de/grfspecs/m4nfoManual/IndexTowns.html) <br><!--
--><!--#:-->     __________________________________________________
 18.	**Raport techniczny** <br>
	I.		[Ogólny](database/tR_general) <br>
	II.		[Trains](http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_trains.html) <br>
	III.	[Road vehicles](http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_rvs.html) <br>
	IV.		[Ships](http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_ships.html) <br>
	V.		[Stacje](database/tR_stations) <br>
	VI.		[Objects](http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_objects.html) <br>
	VII.	[Cargoes](http://www.ttdpatch.de/grfspecs/m4nfoManual/TR_cargoes.html) <br><!--
--> __________________________________________________
 19.	<!--***-->**Tutorial** <br>
	I.		[Bridge tutorial](http://www.ttdpatch.de/grfspecs/m4nfoManual/BridgeTut.html) <br>
	II.		[Callback tutorial](database/callbacksTut) <br>
	III.	[Kompilowanie newgrfs z 32 bpp i/lub dodatkowym zoomem](database/infoVersion32Tut) <br>
	IV.		[Composing vehicles from multiple sprites](http://www.ttdpatch.de/grfspecs/m4nfoManual/stackTut.html) <br>
	V.		[Animacja obiektu](database/animObjectsTut) <br>
	VI.		[Parameter usage](http://www.ttdpatch.de/grfspecs/m4nfoManual/ParamTut.html) <br>
	VII.	[Tutorial stacji](database/stationsTut) <br>
	VIII.	[Using advanced sprite layouts](http://www.ttdpatch.de/grfspecs/m4nfoManual/ASLTut.html) 

#### [<span id="spod" title="przewinięcie na top strony" style="float:right"><big>▲</big></span>](index.md#top) <!--<font color=white> ♪ 	 ♫ </font>-->
<!--:--><!-- __NEWSECTIONLINK__ -->
