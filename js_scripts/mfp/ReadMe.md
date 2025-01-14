MFP - Produse și servicii pentru dezvoltarea soluției de arhivare electronică pentru îmbunătățirea interacțiunii cetățenilor și mediului de afaceri - [caiet de sarcini MFP pt arhivare electronica](https://mfinante.gov.ro/documents/35673/5542684/csac676660_12012022.pdf)

Cum sa obtii [programatic](https://rstforums.com/forum/topic/94371-cum-s%C4%83-ob%C8%9Bii-programatic-date-de-pe-mfinante/) date de pe MFP

Facturis - biblioteca cu informatii [oficiale](https://facturis-online.ro/e-factura/biblioteca-cu-informatii-oficiale-despre-formatul-xml-pentru-e-factura.html) pt eFactura

Pe contul LinkedIn al lui [Bogdan Ionescu](https://www.google.com/search?sca_esv=600253289&rlz=1C1JJTC_enRO1087RO1087&sxsrf=ACQVn09Ri6SbJeUDbhufpGF64syYGF8FTA:1705858760352&q=factura1234.xml&tbm=isch&source=lnms&sa=X&ved=2ahUKEwiQ-8mLg--DAxVWSfEDHcFuApkQ0pQJegQIDhAB&biw=1850&bih=875&dpr=1#imgrc=g7GxgzHF8CPy1M)(n.r. de urmarit articolele dansului) am gasit acest [post](https://www.linkedin.com/posts/bogdan-ionescu-657a785b_einvoice-efactura-anaf-activity-7126192250811789313-mjKp/?originalSubdomain=ro) in care vorbeste despe 2 module dezvoltate de colegii dumnealui de la  [MICS Software SRL](https://www.mics.ro/mcs/software)(poate fi util pt cei care utilizeaza Oracle, [SAP](https://e-factura-sap.ro/) dar am ales sa mentionez acest articol pt a vedea ce sarcini/etape sunt de implementat pe partea de ***transmitere*** facturi eletronice, gata generate in UBL/XML) - n.r. subiectul [factura1234.xml](https://www.agenciatributaria.es/static_files/AEAT/Contenidos_Comunes/La_Agencia_Tributaria/Modelos_y_formularios/Suministro_inmediato_informacion/FicherosSuministros/V_1_1/SII_Descripcion_ServicioWeb_v1.1.pdf) este destul de rar intalnit la [noi](https://www.fiscalitatea.ro/e-factura-2024-ghid-complet-23143/) dar [l-am intalnit](https://ecosio.com/en/blog/e-invoices-in-spain-facturae-and-faceb2b/) destul de [des](https://www.hispamer.es/factura-electronica-en-formato-ubl/16918) pe site-urile [spaniole](https://learn.microsoft.com/es-es/dynamics365/fin-ops-core/dev-itpro/analytics/er-quick-start3-customize-report)(.es); nici [factura123.xml](https://www.tdec.ro/ghid#4) nu este prea des intalnit la [noi](https://docplayer.ro/139202398-Metode-api-integrare-fgo-v-2-8-cuprins-istoric-versiuni-2-introducere-2-apelare-4-nomenclatoare-4-factura-4-emitere-4-print-6-s.html) in Romania. Ca sa va faceti o idee despre [factura UBL/XML](https://fliphtml5.com/mnzz/lxmw/basic/51-100), iata si o factura [italiana](https://tecnologiaacien.blogspot.com/2014/10/como-hacer-una-factura-electronica-iii.html); puteti sa va aruncati o privire si asupra [acestui](https://github.com/thejhorse/SUNAT-UBL-2.1-XML-Firmador/releases) github-repo(.NET);
Interesant de studiat este si experienta [peruana](https://www.contadoresyempresas.com.pe/principales-aspectos-de-la-xml-en-la-facturacion-electronica/) in aceasta speta.

Procesul de facturare/eInvoicing la nivel B2B ori B2C este prezentat in "draft will" pe un site [spaniol](https://www.invopop.com/blog/spain-draft-royal-decree-b2b-e-invoicing)

Studiul articolului "Despre eFactura pe intelesul tuturor" al celor de la [factureaza](https://blog.factureaza.ro/e-factura-este/) poate constitui un bun punct de plecare.

Apoi cei de la [WinMnetor](https://github.com/thejhorse/SUNAT-UBL-2.1-XML-Firmador/releases) prezinta pe docplayer prezinta eFactura implemntata de catre dansii.

Un articol interesant este si acesta "Cum se exporta factura in format .xml pentru importul in sistemul e-Factura?" editat de [Nicoleta Schifirnet](http://help.keyvision.eu/en/articles/6349012-cum-se-exporta-factura-in-format-xml-pentru-importul-in-sistemul-e-factura) pe site-ul [help.keyvision.eu](http://help.keyvision.eu) - solutia KeyVision este o solutie care se adreseaza avocatilor care doresc(contra-cost) sa aiba suport facil e-Factura

Daca sunteti interesati de "SmartCash ANAF Connector" pentru a intelege cum sunt integrate procesele eFactura si eTransport in acest ERP atunci puteti citi acest scurt [articol](https://www.magister.ro/implementarea-efactura-si-etransport-din-smartcash-rms-schimba-regulile-jocului-pentru-comercianti/).

Codurile [INS](https://insse.ro/cms/files/siruta/Metodologie.doc) [SIRUTA](https://siruta.nxm.ro/) ale [UAT](https://ro.wikipedia.org/wiki/SIRUTA)-urilor(zonelor, judetelor si capitalei precum si a oraselor/localitatilor cu/fara primarie) le gasiti in format excel(.xls) pe site-ul [DPFBL](http://www.dpfbl.mdrap.ro/cod_siruta_uat-uri.html); A se vedea si pagina aferenta SIRUTA pe site-ul [123coduri](https://www.123coduri.ro/cauta-in-baza-de-date-coduri-siruta.php?vcodg1=7); INS publica periodic, in vederea descarcarii,  acest [nomenclator](https://data.gov.ro/dataset/siruta-an-2023/resource/a43597c1-6af9-4ca9-adb7-0b5c7873d8fa) [SIRUTA](https://data.gov.ro/dataset/siruta-an-2023) in format [csv/xml](https://data.gov.ro/dataset/siruta-an-2023) pe [data.gov.ro](https://data.gov.ro/organization/institutul-national-de-statistica); Legat de SIRUTA si nu numai gasiti informatii utile si pe website-ul celor de la [ioisrl](https://ioisrl.ro/);
O serie de codificari/clasificari gasiti si pe site-ul[eCoduri](https://www.ecoduri.com/coduri-siruta.php);

[INS](https://data.gov.ro/dataset/siruta/resource/ed3f9ec6-8c12-4ba6-8688-74cadc69f14b) pune la toate versiunile si clasificarile pe care le utilizeza pe serverul lor [SENIN](http://80.96.186.4:81/senin/classifications.htm?selectedClassification=&action=&classificationName=SIRUTA); Exista si un serviciu web oferit de [INSSE](https://webgis.insse.ro/servicii/rest/services/Operational/Localitati/MapServer/0) ce poate fi accesat folosind protocolul ArcGIS REST or SOAP;
Pentru a putea livra un asemenea [serviciu de date spatiale](https://lege5.ro/gratuit/geztmojwg4zdc/normele-tehnice-pentru-realizarea-seturilor-de-date-spatiale-aferente-planurilor-de-amenajare-a-teritoriului-judetean-din-15052023) veti avea nevoie de un server ArcGIS; Interesant este si acest [manual INS](https://insse.ro/cms/files/site_podca/actualizari/manual_preview%208.pdf)(cautati dupa cuvantul ***SIRUTA*** pentru a descoperi legautura cu acest nomenclator); 

Iata si unde ne este necesar [SIRUTA](https://smartcash.community/cum-sa-ma-pregatesc-pentru-e-factura-si-e-transport/)

Pe site-ul european gasiti de asemena versiuni al [SIRUTA](https://data.europa.eu/data/datasets/9f38f6fe-66a0-4e93-ae24-4272b91c9849?locale=es)

Daca doriti date spatiale atunci puteti consulta variantele expuse pe site-ul [ANCPI ](https://geo-spatial.org/vechi/download/romania-seturi-vectoriale)

Aceasta analiza "Sectorul non-profit românesc: date existente, infrastructura de colectare, utilizarea datelor și posibile soluții de eficientizare " poate fi utila pentru [link-urile oferite](https://rafonline.org/wp-content/uploads/2023/01/Raport-infrastructuradate-sector-ONG_FDSC-2021-compressed.pdf).

Legat de SIRUTA mai gasiti si acest document(ceva mai vechi dar interesant)pe site-ul [MDLPA](https://www.mdlpa.ro/uploads/articole/attachments/64d0a28762583720581068.pdf)

Trebuie stiut si faptul ca **SIRUTA** este corelat cu [**NUTS**](https://www.europarl.europa.eu/factsheets/ro/sheet/99/nomenclatorul-comun-al-unitatilor-teritoriale-de-statistica-nuts-)

Daca vreti sa aflati CUI-ul unei firme(PJ) si nu stiti decat ca este inregistrata intr-un ***judet*** anume si desigur ii stiti ***denumirea*** atunci puteti apela la aplicatia online a [**MFP**](https://mfinante.gov.ro/info-pj-selectie-nume-si-judet)

