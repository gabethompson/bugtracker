# bugtracker
A Java GUI program to simulate a bug tracker. Uses a very similar database system to my helpdesk repository, but on port 3307 and using only the "users" table from helpdesk and the "bugs" table:
  idbugs int auto_increment not null
  bugname string
  bugdesc string
  bugrepro string
  bugnotes string
  bugstatus int
  butseverity int
  bugsubdate datetime
