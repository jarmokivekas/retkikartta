

Kartan pohjana käytettään MML:n ainestoa "Maastotietokanta".


https://www.maanmittauslaitos.fi/geopackage


Ei ihan kovin yksikertainen tapa tehdä asiaa, mutta
geopackage tiedostoon upotetut tyylit on siirrettävissä toisiin geopackage tiedostoihin tämän ohjeem mukaisesti:

https://www.maanmittauslaitos.fi/geopackage/maastotietokannan-tyylitiedostojen-hyodyntaminen

Tämä on kovin käytännöllistä jos käytetään esim. kunta-tason geopackage tiedostoja koko suomen tiedoston sijaan.



MML:n karttaikoneita on saatavilla SVG vektoreina GitHubista:

https://github.com/nlsfi/geoserver-configurations/tree/master/styles/maastokartta


Koordinaatisto
--------------

MGRS perustuu UTM koordinaatistoon. Käytännössä suomessa ollaan "WGS84 / UTM zone 35N" tai ""WGS84 / UTM zone 34N" riippuen sijainnista itä-länsi suunnalla. Tässä N on vyöhyke north, eli pohjoinen pallonpuolisko. Esim turun alueen 35V tarkentaa aluetta pohjois-etelä suunnassa, mutta projektio on kuitenki yhä 35N, koska olennaista on pohjoinen pallonpuolisko.

EPSG-koodeina kyseiset projektiot ovat:

- EPSG:32635
- EPSG:32634


Hyviä ohjeita Maastotietokannan käyttöön

https://www.maanmittauslaitos.fi/kartat-ja-paikkatieto/aineistot-ja-rajapinnat/tuotekuvaukset/maastotietokanta
