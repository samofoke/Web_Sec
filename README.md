# Web_Sec
learning about web penetration testing.

## SQL Injection

SQL injection is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. It generally allows an attacker to view data that they are not normally able to retrieve. This might include data belonging to other users, or any other data that the application itself is able to access. In many cases, an attacker can modify or delete this data, causing persistent changes to the application's content or behavior. 

```
UNION SELECT Username, passward FROM User--

                ->SELECT name, discription FROM products WHERE category

                        -> All passwards
                        -> All Usernames [The Database] 
```
