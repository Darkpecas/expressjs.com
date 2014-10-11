# Third-party middleware

Here are some Express middleware modules:

  - [body-parser](https://github.com/expressjs/body-parser): previously `bodyParser`, `json`, and `urlencoded`. 
  See also:
    - [body](https://github.com/raynos/body)
    - [co-body](https://github.com/visionmedia/co-body)
    - [raw-body](https://github.com/stream-utils/raw-body)
  - [compression](https://github.com/expressjs/compression) - previously `compress`
  - [connect-image-optimus] (https://github.com/msemenistyi/connect-image-optimus):  Connect/Express middleware for optimal image serving. Switches to webp/jpegxr if possible.
  - [connect-timeout](https://github.com/expressjs/timeout): previously `timeout`
  - [cookie-parser](https://github.com/expressjs/cookie-parser): previously `cookieParser`
  - [cookie-session](https://github.com/expressjs/cookie-session): previously `cookieSession`
  - [csurf](https://github.com/expressjs/csurf): previousy `csrf`
  - [errorhandler](https://github.com/expressjs/errorhandler): previously `error-handler`
  - [express-debug](https://github.com/devoidfury/express-debug):  unobtrusive development tool that adds a tab with information about req, session, locals, and more to your application.
  - [express-partial-response](https://github.com/nemtsov/express-partial-response):  Express middleware for filtering-out parts of JSON responses based on the `fields` query-string; using Google API's Partial Response.
  - [express-session](https://github.com/expressjs/session): previously `session`
  - [express-simple-cdn](https://github.com/jamiesteven/express-simple-cdn):  easily use a CDN for your static assets, with multiple host support (ex. cdn1.host.com, cdn2.host.com).
  - [express-slash](https://github.com/ericf/express-slash):  Express middleware for people who are anal about trailing slashes.
  - [express-uncapitalize](https://github.com/jamiesteven/express-uncapitalize):  redirect HTTP requests containing uppercase to a canonical lowercase form.
  - [Flashify](https://github.com/tehlulz/flashify):  for rails type notifications
  - [method-override](https://github.com/expressjs/method-override): previously `method-override`
  - [morgan](https://github.com/expressjs/morgan): previously `logger`
  - [response-time](https://github.com/expressjs/response-time): previously `response-time`
  - [serve-favicon](https://github.com/expressjs/serve-favicon): previously `favicon`
  - [serve-index](https://github.com/expressjs/serve-index): previousy `directory`
  - [serve-static](https://github.com/expressjs/serve-static): previously `static`
  - [static-expiry](https://github.com/paulwalker/connect-static-expiry):  fingerprinted URLs/Caching Headers for static assets including external domain(s) support.
  - [vhost](https://github.com/expressjs/vhost): previously `vhost`
  - [view-helpers](https://github.com/madhums/node-view-helpers):  An express middleware that provides common helper methods to the views.

Some middleware previously included with Connect are no longer supported by the Connect/Express team,
are replaced by an alternative module, or should be superseded by a better module. Use one of these alternatives instead:

  - `cookieParser`
    - [cookies](https://github.com/jed/cookies) and [keygrip](https://github.com/jed/keygrip)
  - `limit`
    - [raw-body](https://github.com/stream-utils/raw-body)
  - `multipart`
    - [connect-multiparty](https://github.com/superjoe30/connect-multiparty)
    - [connect-busboy](https://github.com/mscdex/connect-busboy)
  - `query`
    - [qs](https://github.com/visionmedia/node-querystring)
  - `staticCache`
    - [st](https://github.com/isaacs/st)
    - [connect-static](https://github.com/andrewrk/connect-static)

For more middleware, see also:
 - [http-framework](https://github.com/Raynos/http-framework/wiki/Modules).
 - [expressjs](https://github.com/expressjs)