---
title: API Reference

language_tabs:
  - shell
  - ruby

toc_footers:
  - <a href='developer.dnsvalt.net/sign_in'>Sign Up for a Developer Key</a>
  - <a href='https://dnsvault.github.op'>Visit Site</a>

includes:
  - nodes
  - views
  - zones
  - records
  - acls
  - errors

search: true
---

# Introduction

Welcome to the DNSVault API! You can use our API to access DNSVault API endpoints, which can get information on various cats, kittens, and breeds in our database.

We have language bindings in Shell, Ruby, and Python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.


# Authentication

> To authorize, use this code:


```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```


```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

> Make sure to replace `meowmeowmeow` with your API key.

DNSVaultuses API keys to allow access to the API. You can register a new DNSVault API key at our [developer portal](http://example.com/developers).

DNSVaultexpects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>



