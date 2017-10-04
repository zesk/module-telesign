# TeleSign SMS Gateway for Zesk

This module provides integration with the TeleSign SMS Gateway and provides interfaces and class compatibility with `zesk\Module_SMS`.

TeleSign is a subscription service which provides APIs to SMS gateways for small transaction fees.

To configure the TeleSign module defaults, set the following values via your configuration:

- `zesk\TeleSign\Module::api_key` - The API Key configured in your TeleSign account
- `zesk\TeleSign\Module::rest_endpoint` - The API endpoint configured in your TeleSign account, by default `https://rest-api.telesign.com`
- `zesk\TeleSign\Module::customer_id` - Your customer ID in the form: "ABCDEF01-2345-6789-0ABC-DEF012345678"

The `zesk\Module_SMS` interfaces are a work-in-progress as additional SMS gateways are added.

Updated on **Wed Oct  4 15:12:20 EDT 2017**.