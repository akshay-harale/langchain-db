# langchain-db
langchain-db using huggingface and openai api based on following example.<br>
https://python.langchain.com/docs/integrations/toolkits/sql_database

To test this example you can create simple student table with following schema
```
CREATE TABLE public.student (
	s_name varchar(20) NULL,
	age int4 NULL
);
```
Insert some values
```
insert into student(s_name,age) values('jai',27),('akshay',42),('dipesh',37),('akshay',32),('sukesh',27),('jai',28),('rahul',27);
```

Install dependencies from requirements.txt
```
pip install -r requirements.txt
```
then run example using python command
```
python db-llm.py
```