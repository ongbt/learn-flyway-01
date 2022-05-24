# Flyway

ref: https://www.baeldung.com/database-migrations-with-flyway

Run: `./gradlew flywayMigrate -Dflyway.configFiles=myFlywayConfig.conf`  


## Issues:
1. H2 version '2.1.212' cannot work: H2 console at http://localhost:8080/h2-console says `Database "/Users/ongbt/data/demo" not found, either pre-create it or allow remote database creation `
   - 'com.h2database:h2:1.4.196' works, can access the H2 web console