A Ruby gem designed to assist Ruby developers in working with Google Data APIs.

RDoc is available online for
  * [trunk](http://gdata-ruby-util.googlecode.com/svn/trunk/doc/index.html)
  * [Version 1.1.2](http://gdata-ruby-util.googlecode.com/hg/doc/index.html?r=1.1.2)
  * [Version 1.1.1](http://gdata-ruby-util.googlecode.com/hg/doc/index.html?r=1.1.1)
  * [Version 1.1.0](http://gdata-ruby-util.googlecode.com/hg/doc/index.html?r=1.1.0)
  * [Version 1.0.1](http://gdata-ruby-util.googlecode.com/hg/doc/index.html?r=1.0.1)

There is also a [RubyForge project](http://rubyforge.org/projects/gdata/) you can download the released gems from.

**NOTE:** Beginning in v1.1.2, `AuthSub` requests will default to HTTPS by default for security reasons, when possible. Please update any URLs you're using with this library to ensure they're using HTTPS before upgrading. You may receive a scope error when making `AuthAub` requests if you do not do this. (`ClientLogin` is not affected by this change, but we strongly recommend using HTTPS for all API requests regardless.)