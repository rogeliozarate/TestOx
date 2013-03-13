# TestOx

## A Rails Proxy based in Rack::ReverseProxy

1.- Add Reverse Proxy gem to Gem file

```ruby
gem "rack-reverse-proxy", :require => "rack/reverse_proxy"

2.- Configure app in config/application.rb

Looks like magic, it is not.