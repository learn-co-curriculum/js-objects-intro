# Object Oriented JavaScript

## Objectives
+ Explain what an object is in JavaScript
+ Explain the parts of a JS object
+ Create an object in JS


## Ruby Versus JavaScript
You've already worked with objects in JavaScript, but so far we've only treated them like hashes. Now it's time to change frame of mind and start to view them as objects with properties and values.

You're also already familiar with objects in Ruby. Both of these frames of reference are going to make dealing with objects in JavaScript that much easier. You already know what an object is, so now it's just about learning how JavaScript handles them.

 Let's create a user class and object in Ruby. The user will have a `name` and `email` attribute:

```ruby
class User
  attr_accessor :name, :email

  def initialize(name, email)
    @name = name
    @email = email
  end
end

kevin = User.new("kevin", "kevin@aol.com")
```

Now let's recreate the same thing in JS:

```js
var kevin = {
  name: "kevin",
  email: "kevin@aol.com"
}
```


talk about how the same thing - dealing with properties and data



## Resources
