# Case Statements Quiz

## Objectives

1. Distinguish a case statement from other patterns
2. Identify when to use a case statement
3. Write a case statement


**Note:** If you see concepts in the quiz that you might not have seen before, then Google it. Knowing how to look for information is an important part of being a good programmer so we're not going to always give you everything you need to figure out a problem; some of it will be on you. 

???

# Quiz

?: Which of the following is a case statement?

( )
```ruby
name = "Steven"

if name == "Steven"
  "Hi, #{name}"
else
  puts "Hi, stranger!"
``` 
(X)
```ruby
name = "Steven"

case name
  when "Steven"
    puts "Hi, #{name}"
  when "Amanda"
    puts "Welcome back, #{name}"
  when "Admin"
    puts "You have all the power!"
  end
``` 
( )
```ruby
def case
  puts "Am I a case statement?"
end

case
```

?: Of the following two examples, which example uses the case statement the best?

( )
```ruby
name = "Steven"

case name
  when "Steven"
    puts "Hi, #{name}"
  when "Amanda"
    puts "Welcome back, #{name}"
  when "Admin"
    puts "You have all the power!"
  end
```
( )
```ruby
grade = 95

case grade
  when 90..100
    "A" 
  when 80..90
    "B"
  when 70..80
    "C"
  when 60..70
    "D"
  when 0..60
    "F"
end
```
(X) Both are good as case statements

?: Which operator does a case statement use to compare the value to the conditions?

(X) `===`
( ) `==`
( ) `=`

???

## Does this need an update?

Please open a [GitHub issue](https://github.com/learn-co-curriculum/phrg-case-statements-quiz/pulls) or [pull-request](https://github.com/learn-co-curriculum/phrg-case-statements-quiz/pulls). Provide a detailed description that explains the issue you have found or the change you are proposing. Then "@" mention your instructor on the issue or pull-request, and send them a link via Connect.

<p data-visibility='hidden'>PHRG Case Statements Quiz</p>
