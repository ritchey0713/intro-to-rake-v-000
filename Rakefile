namespace :greeting do 
  desc 'outputs hola to the terminal'
  task :hola do 
    puts "hola de rake!"
  end 
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
end 

namespace :db do 
  desc 'migrate changes to your database'
  task :migrate => :enviroment do 
    Student.create_table 
  end 
end 
