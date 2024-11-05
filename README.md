# Welcome to Mondrian
Mondrian is an Online Analytical Processing (OLAP) server that enables business users to analyze large quantities of data in real-time.

## Sub modules
  * **mondrian** - the core mondrian java library
  * **workbench** - A desktop GUI for generating Mondrian schemas

## To run Mondrian tests
  * you need to be in the "mondrian" module subfolder
  * you need to be connected to the Pentaho VPN
  * you need to have docker installed
  * change `mondrian/pom.xml` line 505 to: `<mysql.url.base>jdbc:mysql://localhost:3306</mysql.url.base>`
  * run: `mvn clean verify -DrunITs`
