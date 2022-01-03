GETTING STARTED
Gem Version Build Status SemVer

Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort:

# myapp.rb
require 'sinatra'

get '/' do
  'Hello world!'
end
Install the gem:

gem install sinatra
And run with:

ruby myapp.rb
View at: http://localhost:4567

The code you changed will not take effect until you restart the server. Please restart the server every time you change or use sinatra/reloader.

It is recommended to also run gem install thin, which Sinatra will pick up if available.