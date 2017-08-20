# TV3 TV Guide Calendar

A calendar in iCalendar (ICS) format for the channels of Catalan TV network [TV3](http://www.ccma.cat/tv3/).

This project is just an excuse for me to play with [Puppeteer](https://github.com/GoogleChrome/puppeteer).

## Development

```bash
$ npm run watch
```

## TODO

- Add all available days.
- Add all network channels.
- Add episode missing details (URLs, description, language(s), ...)
- Link to a public calendar consuming from this service. I think Google Calendar offers this option. This calendar could work to showcase the service without having to subscribe to it.
- `$ ag ' TODO '`
- How to get notified of issues in production?
- Web crawler to warn about unexpected results (timeouts, missing content, ...)