
# Join Types Practicing
- Normal Join: Matched records from master and detail tables
- Master Outer Join: All records from detail table + matched records from master table
- Detail Outer Join: All records from master table + matched records from detail table
- Full Outer Join: the name describes enough :D

## Source Data Table 1 (Employees) (Detail Table):
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/9cf06e21-9985-4208-8aee-1bf27c67c84a)

## Source Data Table 2 (Departments) (Master Table):
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/a59d43c5-87fc-43f1-ad86-33f39f586a30)

## 1 ) Normal Join
### Mapping:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/cb811889-981e-4862-8052-76210573261b)

![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/6fe1134a-78c2-477c-84cb-9e099a90bf22)

![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/51eb5eaf-15db-4f88-ad0e-1696227d36c8)

### Target table:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/54e9f8dc-bfc0-4ee8-9cfd-7f6694739c55)


## 2) Master Outer Join
### Target table:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/400b2f50-7b9d-47ad-abbb-48a2addd533f)

## 3) Detail Outer Join (i added R&D department here and didn't assign it to any employee so the difference can be noticeable)
### Target table:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/2d4b577b-1386-4cc3-bd27-b1b12f834b10)


## 4) Full Outer Join:
### Target table:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/d4a29313-60cc-4adf-9c95-f999b38ae854)

