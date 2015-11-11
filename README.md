Jekyll Roman Filter
===================

A liquid filter for Jekyll that converts numbers into Roman numerals.

## Installation

1. Add `gem 'jekyll-roman'` to your site's Gemfile and run bundle
2. Add the following to your site's _config.yml:

```yml
gems:
  - jekyll-roman
```

## Usage

This filter takes any given number, and converts it to roman numerals. For example, if you wish to display the year of your site's copyright, you would write the following:

```html
<h1>&copy; {{ site.time | date:"%Y" | roman }}</h1>
````

## Testing

1. `script/bootstrap`
2. `script/cibuild`

## Contributing

1. Fork the project
2. Create a descriptively named feature branch
3. Add your feature
4. Submit a pull request

## Acknowledgements

Code based on that found in [this discussion on Stack Overflow](http://stackoverflow.com/questions/26092510/roman-numerals-in-ruby). If you know of a better way of achieving the same result, please let me know!
