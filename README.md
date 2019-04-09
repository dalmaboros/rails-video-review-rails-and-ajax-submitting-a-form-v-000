# Rails and AJAX, Submitting a Form

## Summary

The previous video discussed sending data to a server using AJAX in Rails. This video covers the process of asynchronously submitting form data to a server using AJAX in a blog domain Rails application.

## Objectives

1. Use the `.on()` event handler function and `event.preventDefault()` to hijack the submit event of an HTML form element.
2. Use the .serialize() method to encode form elements into a string for submission.
3. Use the jQuery AJAX methods `.ajax()` or `.post()` within an event handler function to send serialized form data to a server.
4. Use .html.erb and .js.erb Action Views and Action View partials to render returned data from the server.
5. Use jQuery DOM manipulation methods to clear form input fields and append server response data to the DOM after successful form submission via AJAX.
6. Understand that adding the `:remote => true` Rails helper to a form automatically creates an event that fires an AJAX request to the server when the form is submitted.

## Video
<iframe width="100%" height="720" src="https://www.youtube.com/embed/XxzayZma5Ew?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

## Resources

- [jQuery docs: .serialize()](https://api.jquery.com/serialize/)
- [rails/jquery-ujs](https://github.com/rails/jquery-ujs)
- [A Tour of Rails’ jQuery UJS](https://thoughtbot.com/blog/a-tour-of-rails-jquery-ujs)
