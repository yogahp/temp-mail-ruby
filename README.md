[![Build Status](https://travis-ci.org/yogahp/temp-mail-ruby.svg?branch=master)](https://travis-ci.org/yogahp/temp-mail-ruby)

# temp-mail-ruby

Ruby client for [TempMail](https://temp-mail.org)
Original version : [temp-mail](https://github.com/maxd/temp-mail)

## Usage

### Get available domain names

```ruby
require 'temp/mail'

client = Temp::Mail::Client.new
p client.available_domains
```

### Get incoming e-mails

```ruby
require 'temp/mail'

client = Temp::Mail::Client.new
p client.incoming_emails('buburgoreng@vps30.com')
```

[Here](https://temp-mail.org/en/api/) is Temp Mail API specification. It describe all fields of e-mail objects in incoming list.

## Contributing

1. Fork it ( https://github.com/yogahp/temp-mail-ruby/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
