# IP Geolocation API - [ipbase.com](https://ipbase.com)

ipbase.com provides a reliable & scalable IP geolocation API for software developers. It uses a database of IP addresses associated with cities and other relevant information like time zone, latitude & longitude.

## Official libraries

| Language              | Code                                                                                     | Repository                                                                                             |
| --------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Python                | [https://github.com/everapihq/ipbase-python](https://github.com/everapihq/ipbase-python) | [https://pypi.org/project/ipbase/](https://pypi.org/project/ipbase/)                                   |
| PHP                   | [https://github.com/everapihq/ipbase-php](https://github.com/everapihq/ipbase-php)       | [https://packagist.org/packages/everapi/ipbase-php](https://packagist.org/packages/everapi/ipbase-php) |
| JavaScript ES6 module | [https://github.com/everapihq/ipbase-js](https://github.com/everapihq/ipbase-js)         | [https://www.npmjs.com/package/@everapi/ipbase-js](https://www.npmjs.com/package/@everapi/ipbase-js)   |
| Ruby                  | [https://github.com/everapihq/ipbase-ruby](https://github.com/everapihq/ipbase-ruby)     | [https://rubygems.org/gems/ipbase](https://rubygems.org/gems/ipbase)                                   |
| C#                    | [https://github.com/everapihq/ipbase-dotnet](https://github.com/everapihq/ipbase-dotnet) | [https://www.nuget.org/packages/ipbase/](https://www.nuget.org/packages/ipbase/)                       |
| Rust                  | [https://github.com/everapihq/ipbase-rs](https://github.com/everapihq/ipbase-rs)         | [https://crates.io/crates/ipbase-rs](https://crates.io/crates/ipbase-rs)                               |
| Go                    | [https://github.com/everapihq/ipbase-go](https://github.com/everapihq/ipbase-go)         | [https://pkg.go.dev/github.com/everapihq/ipbase-go](https://pkg.go.dev/github.com/everapihq/ipbase-go) |

## Postman collection

You can check out our [Postman collection here](https://www.postman.com/dominikkukacka/workspace/everapi/collection/6448-2d679115-8ed7-4dce-afb2-600ccfe6cba5?ctx=documentation)

## Your first request

Get your free API key [here](https://app.ipbase.com/register) and simply query our /info endpoint:

```
# your own IP
curl "https://api.ipbase.com/v2/info?apikey=YOUR-APIKEY"

# query a specific IP

curl "https://api.ipbase.com/v2/info?ip=1.1.1.1&apikey=YOUR-APIKEY"

```

## Pricing

Our packages start at 9.99$/month for 64,000 requests, you can find more here: [Pricing](https://ipbase.com/pricing/)

## Endpoints

Check out all the available endpoints here: [https://ipbase.com/docs/status](https://ipbase.com/docs/status)

## Support And Contact

Please send us an email at [support@ipbase.com](mailto:support@ipbase.com)
