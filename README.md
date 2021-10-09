<br />
<div align="center">
  <p align="center">
    CRUD with Spring and Ionic for Tasks
    <br />

  </p>
</div>

### Built With

- [Ionic](https://ionicframework.com)
- [spring.io](https://spring.io)
- [MySQL](https://www.mysql.com)
- [Angular](https://angular.io/)

1.- Open your IDE for Spring and run spring boot app.
<br>
2.-To start ionic , open the terminal and write ionic serve.

This project is build with 2 tables on SQL

I build one table to save all the task
This have :
ID
ID OF THE SUBJECT (foreign key)
NAME OF THE TASK
DATE LIMIT FOR THE TASK
DESCRIPTION OF THE TASK

And I made one more table to save all the subjects linked to the tasks.
This have :
ID OF THE SUBJECT
NAME OF THE SUBJECT
NAME OF A TEACHER


This means that this project have a 1:N relation. In this particular case, due to the ID SUBJECT in the table TASK, I can extract the name of the subject and show it in the
frontend

The rest of the project has a CRUD totally functional. To test the backend properly, you can use Postman with this link:
https://documenter.getpostman.com/view/17847912/UUy7bjQc

<p align="right">(<a href="#top">back to top</a>)</p>
