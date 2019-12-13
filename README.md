# Simplemde

Add [SimpleMDE](https://simplemde.com/) markdown editor to your Rails application.

This gem is not maintained for a long time. Not sure if it still works.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'simplemde'
```

## Usage

In your app/assets/javascripts/application.js

```javascript
  //= require jquery
  //= require jquery_ujs
  //= require simplemde
```

In your app/assets/Stylesheets/application.css

```css
  /*
  *= require simplemde
  *= require_tree .
  *= require_self
  */
```

Add this to your [controller-name].coffe

```coffeescript
    $(document).on 'turbolinks:load', ->
    simplemde = new SimpleMDE()
```
See [configuration options](https://github.com/NextStepWebs/simplemde-markdown-editor#configuration)

After that each first textarea on each page of this controller will be transformed to SimpleMDE markdown editor

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/arsique/simplemde.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
