# Help Long Island City!

**CONTRIBUTIONS WELCOME**, both in terms of content and design/features. This is a fork of [prospectheightsbk.com](https://github.com/irace/prospectheightsbk.com) by [Bryan Irace](https://github.com/irace)

## Content

Content is all managed within `_data/places.yml`.

An (incomplete) list of businesses to potentially add can be found [on this wiki page](https://github.com/jasonseney/licsupport.nyc/wiki).

## Forking for your Neighborhood

The site is generated using the [Jekyll](https://jekyllrb.com) version 3. static site platfrom on Ruby. Quick setup requires `ruby` and `bundler`. Using `bundle install` will install all the required gems for Jekyll to run on github pages. To run the site locally, use the command `bundle exec jekyll serve`.

Most of the custom fields for the neighborhood are in the config file, front matter, and the includes html files. Note that Jekyll must be restarted to recognize any changes in the config file.

# License

Available for use under the MIT license: [http://bryan.mit-license.org](http://bryan.mit-license.org)
