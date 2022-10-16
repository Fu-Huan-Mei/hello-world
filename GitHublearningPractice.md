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
# Using GeoJSON
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```
