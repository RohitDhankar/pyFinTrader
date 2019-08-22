# pyFinTrader
NASDAQ Symbols -- ROST[ROST(NASDAQ)_ROSS_STORES] and TJX[TJX_Companies_Inc] - data for trades from June 2019 till date here == https://github.com/RohitDhankar/pyFinTrader/tree/master/tempDataDir- pyFinTrader

Initial thoughts -- 

https://github.com/wilsonfreitas/awesome-quant
https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.QuadraticDiscriminantAnalysis.html

Initial Django + PSQL Config ---

```
postgres=# \c dbpsql_pyfinproj pyfinuser
psql (10.3 (Ubuntu 10.3-1.pgdg16.04+1), server 9.5.19)
You are now connected to database "dbpsql_pyfinproj" as user "pyfinuser".
dbpsql_pyfinproj=> 
dbpsql_pyfinproj=> \dt
                    List of relations
 Schema |            Name            | Type  |   Owner   
--------+----------------------------+-------+-----------
 public | auth_group                 | table | pyfinuser
 public | auth_group_permissions     | table | pyfinuser
 public | auth_permission            | table | pyfinuser
 public | auth_user                  | table | pyfinuser
 public | auth_user_groups           | table | pyfinuser
 public | auth_user_user_permissions | table | pyfinuser
 public | django_admin_log           | table | pyfinuser
 public | django_content_type        | table | pyfinuser
 public | django_migrations          | table | pyfinuser
 public | django_session             | table | pyfinuser
(10 rows)

dbpsql_pyfinproj=> \q

```
