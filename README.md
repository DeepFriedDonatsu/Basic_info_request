# Basic_info_request
Requests for Basic info in Ruby
#Original Code created in Codecademy:
##
print"What is your first name?"
first_name = gets.chomp
first_name2 = first_name.capitalize
first_name.capitalize!

print "What is your last name?"
last_name = gets.chomp
last_name2 = last_name.capitalize
last_name.capitalize!

print "What city are you from?"
city = gets.chomp
city2 = city.capitalize
city.capitalize!

print "What state are you from (abbreviated)?"
state = gets.chomp
state2 = state.upcase
state.upcase!

print "What about your age?"
age = gets.chomp
age2 = age.capitalize
age.capitalize!

##Phone number legnth verification:
print "For verification, what is your phone number? (No need for symbols!)"
phone_num = gets.chomp

if
  phone_num.length > 10
  puts "Sorry, but the number you've entered is too long. please try again."
  phone_num.length<10
  puts "Sorry, but the number you've entered is too short. Please try again."
end

puts "here are your details you provided to me:
Your first name is #{first_name}"
puts "Your last name is #{last_name}"
puts "you are #{age}" 
puts "and you are from #{city}" 
puts "in #{state}!"
puts "A good number to contact you at is: #{phone_num}"
##Verify correct info//
puts""
puts "is this correct?"
correct_answer = gets.chomp

if
  correct_answer == "no"
  puts "Whoops! Let's fix that!"
else
  puts "Thank you for your info!"
end
