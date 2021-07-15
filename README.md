# Migrate-Contract
A simple contract to migrate token from old version to new one  

How to Deploy:  
1) deploy and set V1, V2 and rate  
2) send the amount of V2 tokens needed to the contract  
3) click startMigration  

How to migrate:  
1) Go on V1 token contract and on "approve" function input the migration contract address and as amount set total supply  
2) Go on migration contract, on migrateToV2 and set the amount of V1 tokens to migrate.  
3) DONE
