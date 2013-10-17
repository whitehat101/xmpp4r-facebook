# XMPP4R Facebook SASL Mechanism

Adds a X-Facebook-Platform SASL Authentication Mechanism to xmpp4r.
This gems loads xmpp4r and the SASL XFacebookPlatform mechinism, nothing more.

See the [xmpp4r project page](https://github.com/xmpp4r/xmpp4r) for information about xmpp4r.

Credit to @ShogunPanda for the [initial PR](https://github.com/ln/xmpp4r/pull/25) that this gem is based.


## Installation

Add this line to your application's Gemfile:

    gem 'xmpp4r-facebook'
    # listing xmpp4r in your gemfile is not necessary

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install xmpp4r-facebook

## Usage

    client.auth_sasl(Jabber::SASL::XFacebookPlatform.new(client, {:id => APP_ID, :token => ACCESS_TOKEN}), nil)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
