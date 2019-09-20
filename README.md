fake REST API
http://fakerestapi.tk

REST API for developers to test and prototyping of sample applications.

Download csv files 
http://fakerestapi.tk/download_csv_files
Available CSV files

1. Products - 2000 records
2. Todo lists - 1000 records
3. Todo items - 2000 records

visit http://fakerestapi.tk  to know about total records and fields in csv datasets


Api endpoint link http://fakerestapi.tk/api/v1/todo_lists

Example

```
curl -X GET http://fakerestapi.tk/api/v1/todo_lists
[
  {
	  "id" : 1,
	  "title" : todo list title,
	  "description" : todo list description,
	  "due_date":"2020-01-19T22:48:47.998Z"
	  "created_at" : 2019-08-29T19:07:55.585Z,
	  "updated_at" : 2019-08-31T03:50:58.390Z
  }
  ......
  ......
]
```
        
