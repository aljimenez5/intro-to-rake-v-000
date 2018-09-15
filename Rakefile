namespace :greeting
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
    
  task :hola
    puts "hola de Rake!"
end

task :environment do
  require_relative './config/environment'
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    Student.create_table
  end
end