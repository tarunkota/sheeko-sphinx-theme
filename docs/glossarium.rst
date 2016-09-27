.. _glossary:

Glossarium
==========

.. glossary::
   :sorted:

   
   Continuous Integration
    Continuous integration staat voor "Het dagelijks samenvoegen van alle, door verschillende ontwikkelaars, ontwikkelde code. Met als doel om zo snel mogelijk (integratie) problemen op te sporen en verhelpen."

   SKOS
    `Simple Knowledge Organization System <http://www.w3.org/2004/02/skos>`__. An
    general specification for Knowledge Organisation Systems (thesauri, word 
    lists, authority files, ...) that is commonly serialised as :term:`RDF`.

   RDF
    `Resource Description Framework <http://www.w3.org/RDF/>`__. A very flexible 
    model for data definition organised around `triples`. These triples forms a 
    directed, labeled graph, where the edges represent the named link between 
    two resources, represented by the graph nodes.

   Agavi
    `Agavi Framework <http://www.agavi.org>`_ is een ouder :term:`PHP` MVC 
    Framework dat als basis diende voor oudere toepassingen van het Agentschap.

   AGIV
    Het `Agentschap voor Geografische Informatie Vlaanderen <http://www.agiv.be>`_ 
    is een agentschap van de Vlaamse Overheid dat werkt rond GIS binnen de 
    Vlaamse Overheid. Zij beheren de :term:`CRAB` Webservice.

   CRAB
    Het `Centraal Referentie Adressen Bestand` van het :term:`AGIV` is de 
    authentieke bron voor adressen in Vlaanderen.

   CAPAKEY
    Een unieke sleutel voor een perceel. Wordt ook gebruikt als de naam van de
    webservice van het :term:`AGIV` die dergelijk info ontsluit.

   PostgreSQL
    `Postgresql <http://www.postgresql.org>`_ is de open source database 
    server waarop de meeste van onze toepassingen draaien.

   PostGIS
    `Postgis <http://postgis.refractions.net>`_ is een extensie voor 
    :term:`Postgresql` die Postgresql in staat stelt om spatial information op te slaan.

   Phing
    `Phing <http://phing.info>`_ is een :term:`PHP` tool waarmee build scripts 
    kunnen gemaakt worden. Wordt gebruikt bij oudere projecten.

   PHP
    `PHP <http://www.php.net>`_ is de programmeertaal die we vroeger in 
    de applicatielaag gebruikten.

   Python
    Python is de programmeertaal die nu de applicatielaag draagt.

   Java
    Een gekende statische programmeertaal.

   Javascript
    De typische script taal die gebruikt wordt in front-end applicaties. Niet 
    te verwarren met :term:`Java`. Op de naam na, hebben deze niets gemeen met 
    elkaar.

   Ubuntu
    Een Linux distributie die voortbouwt op de Debian distributie. Wordt 
    commercieel ontwikkeld door de firma Canonical.

   LTS
    `Long Term Stability`. Dit is een aanduiding van een :term:`Ubuntu` versie
    waarop een langere ondersteuningstermijn rust. De huidige LTS versie is
    Ubuntu 12.04. De volgende LTS versie zal Ubuntu 14.04 zijn.

   MySQL
    Een open source database server.

   SQLite
    Een open source database die bestaat uit een enkele file. Ideaal voor
    ontwikkeling en kleine toepassingen.

   departement LNE
    Het departement van het beleidsdomein Leefmilieu, Natuur en Energie.

   Drupal
    Een gekend open source CMS van Belgische oorsprong ontwikkeld in :term:`PHP`.

   Github
    Een online site waarop de ontwikkeling van veel open source software wordt
    bijgehouden. Bevat :term:`git` repositories en bijhorende issue trackers
    en wikis. 

   Git
    Een open source DVCS (Distributed Version Control System) dat bij voorkeur
    gebruikt wordt bij projecten van het Agentschap.

   Pull request
    Een algemene term voor een feature op :term:`Github`. Een developer vraagt
    om wijzigingen (die lokaal zijn aangebracht aan een bepaalde fork of branch van een 
    repository) te mergen met de master versie.

   Subversion
   Svn
    `Subversion <http://subversion.apache.org>`_ of `svn` is een ouder versie 
    controle systeem. In tegenstelling tot bv. :term:`git` is svn een 
    gecentraliseerd systeem. Dit werd vroeger veelvuldig gebruikt door het
    agentschap, maar wordt nu vervangen door :term:`git`. Wordt wel nog gebruikt
    door het :term:`departement LNE`.

   Trac
    Een open source issue tracker die veelvuldig door het agentschap gebruikt
    wordt. Wordt ook voor een aantal niet-technische projecten ingezet als
    algemeen projectopvolgingssysteem of klein workflow systeem.

   Semantic versioning
    `Semantic Versioning <http://semver.org>`_ beschrijft een manier voor het 
    toekennen van versienummers aan software. In grote lijnen wordt er gewerkt
    met `major.minor.patch` versies waarbij het major nummer verhoogd wordt
    bij een backwards incompatible API wijziging, het minor nummer verhoogd 
    wordt bij het toevoegen van backwards compatible nieuwe functionaliteit en
    waarbij het patch nummer verhoogd wordt bij het uitvoeren van backwards
    compatible bug fixes.

   Code coverage
    De mate waarin programmacode voorzien is van tests. De code coverage drukt
    uit hoeveel procent van de code geraakt wordt door geautomatiseerde testen.

   Travis CI
    Op het `Travis CI <https://travis-ci.org>`_ platform worden builds uitgevoerd
    voor toepassingen in verschillende talen. Momenteel is de service nog sterk
    gekoppeld aan :term:`Github`.

   Tox
    `Tox <https://testrun.org/tox>`_ is een :term:`python` tool die uitgebreid
    gebruik maakt van :term:`virtualenv` om aparte omgevingen voor unit tests
    aan te bieden. Zo kunnen py27 en py32 omgevingen naast elkaar getest worden
    zonder al te veel moeite.

   Virtualenv
    Met `www.virtualenv.org` kunnen meerdere geïsoleerde :term:`Python` 
    omgevingen aangemaakt worden. Dit zorgt er bijvoorbeeld voor dat meerdere
    toepassingen op een server dezelfde bibliotheek kunnen gebruiken, maar in
    met andere versies.

   REST
    REST of `REpresentational State Transfer` is een manier van 
    gegevensuitwisseling tussen toepassingen die nauw aansluit bij de werking van
    het HTTP protocol.

   Read The Docs
    `Read The Docs <https://readthedocs.org/>`_ bouwt :term:`Sphinx` 
    documentatie uit publieke repositories en maakt deze openbaar beschikbaar 
    als HTML en PDF versies. Voor elk project kunnen er verschillende versies
    aangeboden worden (bv. de laatste versie, alle major versies, ...). Zie
    bv. de `CRABpy documentatie <http://crabpy.readthedocs.org/en/latest/>`_.

   Sphinx
    `Sphinx <http://sphinx-doc.org>`_ is een documentatie tool op basis van 
    RST formaat. Dit verrijkte tekstformaat (analoog met Markdown en wiki 
    syntax) kan omgezet worden naar een hele reeks van formaten zoals HTML,
    PDF, Windows Help, Epub, ... De syntax is zeer rijk en bevat voorzieningen
    voor syntax highlighting, het werken met verwijzingen, het automatisch 
    aanmaken van indexen en glossaria, ...

   Open Source
    Software die beschikbaar gemaakt wordt onder een licentie die hergebruik
    door derden toelaat onder bepaalde voorwaarden. Gekende licenties zijn 
    GPL, BSD, Apache, MIT, ...

   PyPI
    `De Python Package Index <https://pypi.python.org/pypi>`_ is een online
    repository van :term:`Python` software. De meeste Python code wordt hier
    gepubliceerd als packages die vie easy install of setuptools makkelijk
    kunnen geïnstalleerd worden.

   ORM
    Een `Object Relational Mapper` is een bibliotheek of framework dat de 
    vertaling kan maken tussen objecten in een typische object-georiënteerde 
    omgeving naar een relationele databank en omgekeerde. Gekende voorbeelden
    zijn Hibernate voor :term:`Java`, :term:`SQLAlchemy` voor :term:`Python` en
    Doctrine voor :term:`PHP`.

   SQLAlchemy
    `SQLAlchemy <http://docs.sqlalchemy.org/>`_ is de meest gebruikte :term:`ORM` 
    onder :term:`Python`. Krachtig, maar met een vrij sterke leercurve. Wordt 
    samen gebruikt met :term:`Alembic` als migratie tool.

   Alembic
    Een tool van de makers van :term:`SQLALchemy` die het makkelijk maakt om
    revisies van schemas van een SQL databank bij te houden. Wordt gebruikt om
    de verschillende stadia in de evolutie van een databank te documenteren en
    bij te houden in :term:`Git`.

   Pyramid
    `Pyramid <http://www.pylonsproject.org/>`_ is een web framework voor 
    :term:`Python` dat zeer non-opinionated is. Het doet een aantal dingen zeer
    goed en laat voor de rest de ontwikkelaar vrij om zelf in te vullen welke 
    templating engine of :term:`ORM` gebruikt wordt.

   Jinja2
    `Jinja2 <http://jinja.pocoo.org>`_ is een framework onafhankelijke template
    taal voor :term:`python`. Qua syntax zijn er sterkge gelijkenissen met bv.
    de Django templating taal. Er bestaat een :term:`PHP` port genaamd 
    `Twig <http://twig.sensiolabs.org>`_.

   Foundation
    `Zurb Foundation <http://foundation.zurb.com>`_ is een :term:`Css` 
    framework dat zich eerder op de achtergrond houdt. Het maakt gebruik 
    van :term:`Sass` als css preprocessing taal.

   Sass
    Met Sass kan :term:`css` op een andere manier geschreven worden. Met behulp
    van mixins en andere herbruikbare functies worden er bronbestanden 
    aangemaakt die gecompileerd worden tot :term:`css`.

   HTML
    `HyperText Markup Language` is de standaardtaal waarmee het web gebouwd 
    werd. Het definieert semantische tags die op basis van :term:`css` verder 
    gestijld kunnen worden.

   Css
    `Cascading Stylesheets` zijn een manier om opmaak te definiëren voor 
    :term:`HTML` zodat het document en de presentatie ervan los van elkaar staan.

   SPA
    Een `Single Page Application` is een webtoepassing waarvan de client 
    volledig uit :term:`javascript` bestaat. Deze wordt geladen binnen op een
    enkele url en maakt bv. gebruik van de History API om aan state management 
    te doen.

   Dojo
    `Dojo <http://dojotoolkit.org>`_ is een :term:`javascript` framework 
    bestaande uit drie grote componenten: dojo (de kern), dijit (widgets) en 
    dojox (experimentelere code). Dojo zet heel sterk in op modulaire en 
    herbruikbare javascript code door middel van 
    `AMD modules <http://http://requirejs.org/docs/whyamd.html>`_.

   Authentieke bron
    Onder een authentieke bron verstaan we een bron die de eenduidig geldende
    voorstellingen van bepaalde zaken bevat. Dit kunnen documenten, gebouwen,
    premies, fotos of zelfs woorden zijn. Er bestaan externe authentieke bronnen
    zoals :term:`CRAB` voor adressen of het rijksregister voor personen. De
    meeste authentieke bronnen waarover we het hier hebben zijn authentieke
    bronnen van het agentschap. Waar mogelijk hebben deze ook wel banden met 
    externe authentieke bronnen. Zo kan de authentieke bron voor premies
    banden hebben met onze eigen authentieke bron voor beschermde objecten
    en met het rijksregister als authentieke bron voor de ontvangers van de premies. 

   FOSS
    `Free and Open-Source Software` is een verzamelnaam voor software die ook
    wel gekend is als `Free Software` en `Open Source Software`. Meestal komt
    dit er op neer dat de broncode van deze software mag bekeken, gebruikt, 
    gewijzigd en gekopieerd worden. De bedoeling is om deling van code maximaal
    mogelijk te maken. Dit wil niet noodzakelijk zeggen dat er geen commerciële
    rechten kunnen aan ontleend worden. Er zijn vandaag de dag meer en meer
    bedrijven die hun business-model hebben opgebouwd rond de ondersteuning en
    customisatie van FOSS.

   URI
    Een `Uniform Resource Identifier` is een uniek identifier voor een bepaalde
    resource op het internet. De meest gekende vorm van URIs is een URL zoals
    https://www.onroerenderfgoed.be.

   HTTP
    Het `HyperText Transfer Protocol` is het onderliggende protocol waarop het
    wereld wijde web draait.
