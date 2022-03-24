# CRUD-beta
damn this

An attempt to create a full stack web application using ASP.NET combined with React with SQL database

## Breakdown

- Backend -> ASP.NET 6 Web API, initially I follow the tutorial and the guy was using .NET 5. I attempt to port it to .NET 6 with some changes and managed to make it work. Results were quite successful but there are issues with the CORS causing issue communicating between ports (frontend using different port). This issue is
- Frontend -> React (Thanks, I hate javascript more, also react) frontend was used. There are some differences with the tutorial version. React 5 vs 6, I don't know exacly, but some syntax changes causing major bug and issue such as infinite loops. Also the POST method to add users and department still not working
- Database -> Micsoft SQL server (sqllocaldb), issue with everytime you start the server the pipeline changing and you have to setup everything all over again in the backend

Good learning material overall, but a bit annoying due a minor differences in the version causing everything to go FUBAR

Source: 
