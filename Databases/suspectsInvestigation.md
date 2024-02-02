# #11 suspectsInvestigation


Solution

```sql
SELECT id, name, surname FROM Suspect WHERE height <= 170 
AND SUBSTRING(name, 1,1)= 'B' 
AND surname LIKE 'Gre_n' ORDER BY id;
```