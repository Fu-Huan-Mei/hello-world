# Quitng code
Use `git status` to list all new or modified files that haven't yet been committed.
Some basic Git commands are:
```
git status
git add
git commit
```
# Creating and highlighting code blocks
## Fenced code blocks
```
function test{
  console.log("notice the blank line before this function?");
}
```
````
```
Look! You can see my backticks.
```
````
## Syntax highlighting
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello Wolrd!")
puts markdown.to_html
```
