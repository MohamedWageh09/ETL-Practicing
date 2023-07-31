# Connected LKP & Unconnected LKP
- CONNECTED LKP WILL BE PART OF THE PIPELINE
  - UNCONNECTED LKP WILL NOT BE PART OF THE PIPELINE
- CONNECTED LKP RETURNS MULTIPLE PORTS
  - UNCONNECTED LKP RETURNS ONLY ONE PORT
- CONNECTED LKP SUPPORT DEFAULT VALUES (instead of nulls) 
  - UNCONNECTED LKP DOESN'T SUPPORT DEFAULT VALUES 
- CONNECTED LKP SUPPORTS DYNAMIC CACHE 
  - UNCONNECTED LKP DOESN'T SUPPORTS DYNAMIC CACHE 

LOOKUP VS JOIN TRANSFORMATIONS
- JOINS SUPPORTS ONLY EQUI (=) JOINS
  - LOOKUP SUPPORTS NON EQUI (all operators) JOINS
- LOOKUP SQL OVERRIDE IS SUPPORTED IN LOOKUP TRANSFORMATION
  - JOIN TRANSFORMATION DOESNT HAVE SQL OVERRIDE CONCEPT (write sql scripts)


## Source 1 (Employees Table):
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/f5397c0f-5300-4b70-885b-1b5147f7ef47)
## Source 2 (Departments Table)
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/8f47a11e-cbf6-4faa-9543-0c7fb12784cb)

# Connected Lookup
### Mapping:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/718f16d2-763b-434a-9b55-d559af7c7505)


### Workflow monitoring:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/8e7a4a35-601d-4604-886b-59b411752e7d)

### Target table:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/0157ab8f-95e4-4862-a113-695b07a05516)


# Unconnected Lookup
### Mapping:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/8c72a3fd-28bf-4b2e-93a5-049cbb05fd6a)

### Workflow monitoring:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/973561dc-e16f-4dec-b239-83244427724b)


### Target table:
![image](https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/22793c76-856b-47b6-b3cf-70e5b437b949)
