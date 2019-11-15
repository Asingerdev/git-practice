This is a change




```
class Bootcamp
  
    def initialize (name, slogan, student_capacity)
    @name = name
    @slogan = slogan
    @student_capacity = student_capacity
    @teachers = Array.new()
    @students = Array.new()
    @grades = Hash.new{ |hash, key| hash[key] = [] }
    end

end
```