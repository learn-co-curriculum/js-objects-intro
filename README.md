# Object Oriented JavaScript

## Objectives
+ Explain what an object is in JavaScript
+ Explain the parts of a JS object
+ Create an object in JS


## Ruby Versus JavaScript

You've already worked with objects in JavaScript, but so far we've only treated them like hashes. Now it's time to change frame of mind and start to view them as objects with properties and values, just like the objects we make in Ruby using classes.

This frame of reference from Ruby is going to make dealing with objects in JavaScript that much easier. You already know what an object is, so now it's time to about learning how JavaScript handles them.

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

## Properties and Data

But how come when we create our `kevin` JavaScript object, it looks just like a hash but our Ruby `kevin` object looks more like what we typically think of as an object?

Let's back up for two seconds and really think about what an object is. In Ruby, we build classes as a way to organize and group together pieces of data. We use properties to provide a frame of reference for a single piece of data, and an object as a way to relate that piece of data to a bigger picture. Suddenly our data (random strings and numbers) means something because of the context the object provides.

Objects in JavaScript conceptually work the exact same way. The provide context for data. We use properties to define what that piece of data means. And we link that property to an object to know even more specifically what that piece of data relates to.

