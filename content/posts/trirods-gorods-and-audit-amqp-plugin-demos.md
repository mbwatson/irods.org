Title: TRiRODS: GoRODS and Audit (AMQP) Plugin Demos
Date: 2016-12-14 18:00
Author: Terrell Russell
Status: published

RENCI and the iRODS Consortium hosted the first Triangle iRODS User Group Meeting (TRiRODS) on Wednesday, December 7, 2016.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vjNt74bgKXY" frameborder="0" allowfullscreen></iframe>

### GoRODS Demo and 1.0 Release

We were pleased to have John Jacquay, scientific systems engineer at [BioTeam](http://www.bioteam.net/), present [GoRODS, his Go iRODS client library](https://github.com/jjacquay712/GoRODS).  He presented an overview of his library, performance numbers, and a demo of a lightweight GO REST web client built on top of GoRODS.  As a surprise, he released version 1.0 near the end of his presentation, pushing live to GitHub.

### iRODS Audit (AMQP) Rule Engine Plugin Demo

We were also pleased to have Terrell Russell and Justin James from the iRODS Consortium present on their [recently published work on auditing iRODS with the Audit (AMQP) Rule Engine Plugin](https://irods.org/2016/12/auditing-irods-with-the-audit-plugin-and-elastic-stack/).  They showed how the audit plugin works within the iRODS Rule Engine Framework. The AMQP messages generated by every operation in iRODS can be queued, pulled by Logstash into Elasticsearch, and then displayed by Kibana as realtime dashboards of live activity within an iRODS Zone.

