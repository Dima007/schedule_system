#Система автоматизации составления расписания аудиторных занятий
Дипломная работа Матвеева А.В. 08-608
<br><b><br>Деплой инструкция:</b>
  <br>bundle install
  <br>rake db:create
  <br>rake db:migrate
  <br>rake db:setup
  <br> cd app/model/cppga/algocpp/ && make Makefile
  <br> Change routes in app/mdel/schedule.rb to yours and start server:
  <br>  rails s
  
