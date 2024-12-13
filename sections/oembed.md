# Screencast OEmbed Endpoint

### URL Scheme
* `https://app.screencast.com/[public_media_id]`

### API Endpoint
* https://app.screencast.com/api/v1/oembed/.json (return as JSON)
* https://app.screencast.com/api/v1/oembed/.xml (return as XML)

### Params:
* `string` - `url` - The Screencast URL to retrieve embedding information for.
* `int` - `maxwidth` - The maximum width of the embedded resource returned.
* `int` - `maxheight` - The maximum height of the embedded resource returned.

For more information on what data will be returned, see the [oembed site](http://oembed.com). Data will be returned for `rich` and `video` types.
