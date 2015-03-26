# COMSODE pilots

Information about pilot installations in the [COMSODE](http://www.comsode.eu/) project. Purpose: provide quick links for those participating in the pilots.

## Who is participating?

There are **organizations in several countries** expected to participate in the pilots (Czech Republic, Italy, Netherlands, Slovakia). Since some organizations only confirmed their interest informally, their list is available on the [private project wiki](https://team.eea.sk/wiki/display/COMSODE/Pilot+Cases+-+work+area) at this time.

## Resources for participating organizations

Need more information? Look here:

- [COMSODE project website](http://www.comsode.eu/) -- general project information.
- [COMSODE blog](http://www.comsode.eu/index.php/blog/) -- reading about project updates, Open Data,...
- [COMSODE deliverables](http://www.comsode.eu/index.php/deliverables/) -- project deliverables. Methodologies will be probably of special interest.
- [demo.comsode.eu](http://demo.comsode.eu/) -- public server: demo of the publication platform (if you'd like to try it out, please contact us, contact below).
- [data.comsode.eu](http://data.comsode.eu/) -- data published by COMSODE.
- [Open Data Node roadmap & releases](https://utopia.sk/wiki/display/ODN/Roadmap+and+releases).
- [Open Data Node installation manual](https://utopia.sk/wiki/display/ODN/Open+Data+Node+v1.0.0).

The transformation component in Open Data Node is called "Unified Views" (technically speaking, it is an [ETL tool](https://en.wikipedia.org/wiki/Extract,_transform,_load) for [RDF data](https://en.wikipedia.org/wiki/Resource_Description_Framework)). The following information is related to Unified Views.

- [UnifiedViews GitHub repository](https://github.com/UnifiedViews).
- [UnifiedViews Documentation](https://grips.semantic-web.at/display/UDDOC/Introduction).

## Resources for pilot managers

- Resources for communication: [English](https://team.eea.sk/wiki/display/COMSODE/PILOT+materials+for+communication+-+ENG+version), [Slovak](https://team.eea.sk/wiki/display/COMSODE/PILOT+materials+for+communication+-+SK+version) (:no_entry_sign: not public, internal wiki).
- [Status of ODN documentation](https://team.eea.sk/wiki/display/COMSODE/Documentation+for+ODN+-+public) (:no_entry_sign: not public, internal wiki).
- [Google groups](https://groups.google.com/forum/#!forum/comsodepilots) -- when communicating about pilots, please send a copy to [comsodepilots@googlegroups.com](mailto:comsodepilots@googlegroups.com).

## Hardware and Software requirements

**Server hardware**: common x86_64 compatible CPU (2-4 cores recommended for heavier transformations), 4GB RAM (more for heavy transformations, e.g. 8GB), 40GB storage. ODN has been tested on modest VPS (and laptops) for testing and demonstration purposes. You should deploy it with real data, see the usage patterns and adjust the virtual machine parameters accordingly.

**Server software**: Linux (Debian 7.6 "wheezy"), OpenJDK 7, [Apache Tomcat 7+](http://tomcat.apache.org/), [Sesame 2.7.13+](http://sourceforge.net/projects/sesame/files/Sesame%202/) or Virtuoso 7.0+ (not yet fully supported as of March 2015) for intermediate data store for data processed on the pipeline, PostgreSQL.

**Client software** (for accessing ODN): reasonably recent web browser (Google Chrome 23+, Internet Explorer 8+, Mozilla Firefox 17+, Opera 12+, Safari 6+).

**Developer software** (only if you intend to develop your own plugins): Java IDE (Netbeans, Eclipse), [Apache Maven 3](http://maven.apache.org/), [Git](http://git-scm.com/downloads).

(Source: [internal wiki](https://utopia.sk/wiki/display/ODN/HW+and+SW+requirements+for+ODN).)

## Contact

For questions regarding the pilots, contact the COMSODE consortium member you have been in contact with. If you don't know whom to contact or you are a new organization interested in running a pilot, please contact [Jan Gondol](mailto:gondol@gondol.sk).
