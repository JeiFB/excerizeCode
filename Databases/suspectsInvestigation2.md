# #12 suspectsInvestigation


Solution

```sql
CREATE PROCEDURE solution()
BEGIN
	SELECT id, name, surname FROM Suspect WHERE height <= 170  OR			SUBSTRING(name, 1,1)<> 'B' OR surname NOT LIKE 'Gre_n' ORDER BY id;
END
```