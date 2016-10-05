This archetype generates a project with the JPA classes extracted from an Oracle Database model.

You can adapt it to other database, but it's not included out of the box.

You will need the Oracle Driver, in my case obtained from the Nexus repository: com.oracle:ojdbc:6

To execute the plugin:

mvn clean hibernate3:hbm2java