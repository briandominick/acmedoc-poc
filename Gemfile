source 'https://rubygems.org'

gem 'asciidoctor'
gem 'json'
gem 'liquid'
gem 'logger'
gem 'crack'

group :asciidoctor_plugins do
  gem 'asciidoctor-pdf'
  gem 'asciidoctor-diagram'
end

group :jekyll_plugins do
  gem 'jekyll-asciidoc', path: "../jekyll-asciidoc"
  gem 'coderay', '~> 1.1.0'
  gem 'rake-jekyll', '~> 1.1.0'
  gem 'jekyll-sitemap'
  gem 'jekyll-gist'
  gem 'jekyll-feed'
end

# Be sure to comment out one of the liquidoc calls below

# For use with released liquidoc gem...
# gem 'liquidoc'

# For dev testing...
# gem 'liquidoc', path: "../liquidoc-gem"
gem 'liquidoc', git: 'git@github.com:briandominick/liquidoc-gem.git', branch: 'attrs-ingest'
