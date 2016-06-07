# Ruby Methods Code Challenge

## Objectives
1. Review mass assignment
2. Review `puts` method
3. Review explicit `return`

???

# Code Challenge I: Mass Assignment

Define a class, School, that initializes with a name and a location. The class should also have `attr_accessor`s for `name` and `location`. The initialize method should use keyword arguments for those attributes.

?: Which snippet correctly implements the above spec?

(x)

``` ruby
class School
  attr_accessor :name, :location

  def initialize(name:, location:)
    @name = name
    @location = location
  end
end
```

( )

``` ruby
class School
  attr_accessor :name, :location

  def initialize(*args)
    @name = args[0]
    @location = args[1]
  end
end
```

( )

``` ruby
class School
  attr_accessor :name, :location

  def initialize(name, location)
    @name = name
    @location = location
  end
end
```

???

???

# Code Challenge II: Puts Method

?: Which method `puts` `"ruby"` 3 times?

( )

``` ruby
def puts_ruby_three_times
  3.times do
    "ruby"
  end
end
```

(x)

``` ruby
def puts_ruby_three_times
  3.times do
    puts "ruby"
  end
end
```

( )

``` ruby
def puts_ruby_three_times
  3.do
    puts "ruby"
  end
end
```

???

???


# Code Challenge III: Explicit Return

?: Which method(s) return(s) `'ruby'`?

(x)

``` ruby
def return_ruby
  return "ruby"
end
```

(x)

``` ruby
def return_ruby
  "ruby"
end
```

( )

``` ruby
def return_ruby
  puts 'ruby'
end
```

???


<p data-visibility='hidden'>View <a href='https://learn.co/lessons/ruby-repl-assertion-test' title='Ruby Methods Code Challenge'>Ruby Methods Code Challenge</a> on Learn.co and start learning to code for free.</p>
