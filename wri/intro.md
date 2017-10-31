AORTA (Accessibility-Oriented Real-Time Applications) provides a unified API
for simple user interfaces.  Rather than maintaining separate UIs for the
blind, the deaf, the motion-impaired, and the fully-abled, vendors using the
AORTA API maintain only a single text-oriented UI, automatically adapted for
disabled users.  The unified API also supports integration with SaaS platforms
like Salesforce, Slack, and Facebook Messenger; low-bandwidth protocols like
SMS; and even audio devices like Amazon Alexa.

Accessible user interfaces are an increasingly important topic:

* [HuffPo: Silicon Valley Vows To Improve Tech For People With Disabilities]( http://www.huffingtonpost.com/entry/silicon-valley-accessibility-people-with-disabilities_us_55b23b15e4b0224d8831d789 )

  > At 19 percent of the U.S. population, people with disabilities represent
  > the largest minority group in the country, but basic technologies are often
  > inaccessible to them. 

* [Chris Pratt Apologizes to Hearing-Impaired Fans for ‘Insensitive’ Post]( http://variety.com/2017/film/news/chris-pratt-apology-hearing-impaired-facebook-1202409513/ )

  > In the post’s accompanying video, Pratt used American Sign Language to
  > articulate the apology onscreen — no volume necessary. He closed the
  > multi-paragraph reparation with a call to action for Instagram: “GET ON IT
  > INSTAGRAM!!!” He wrote. “Put closed captioning on your app.” Pratt also
  > suggested that Instagram implement technology that automatically adds
  > subtitles to its videos.

As consumer software companies prepare for IoT, non-graphical user interfaces
gain relevance.  For example, Spotify [recently announced][spotify] a
self-serve audio ad campaign management tool: "Give us a script, we'll give
your ad a voice."  The New York Times has reported that [As Amazon’s Influence
Grows, Marketers Scramble to Tailor Strategies][nyt], "plotting how companies
can best connect with people who are using devices like the voice-activated
Echo."

API unification is not a new idea, but it has been a successful one.  Companies
like [IFTTT][] have received extensive media coverage.  [mParticle][] offers to
"Collect and control all your customer data through a single API." Bidders as a
Service (BaaS) like [Beeswax][] and [Gamoshi][] offer buyers a single interface
to dozens of ad exchanges.  [Stripe][] adapts financial payment APIs, and
[Orchard Platform][] lets investors apply a single risk model to real-time
bidding across multiple loan origination platforms.  [Xamarin][] abstracts
mobile development platforms, [Socrata][] and [Enigma][] offer normalized APIs
to government data, etc.

No unified API specifically focused on accessible user interfaces seems to
exist yet, either commercial or free/open source.  The most likely explanation
is that until recently, a platform like AORTA would have seemed prohibitively
expensive.  The rise of inexpensive cloud computing (especially serverless
architecture) and web services like Amazon [Polly][] and [Lex][], however, has
reduced the cost, just as mobile computing, SaaS applications, and the social
justice movement have increased demand.

The implementation of AORTA is not complicated, but does require broad,
sustained engineering effort.  The product is exceptionally sticky, since
moving away from it requires manually re-implementing the myriad user
interfaces it supports (or losing the corresponding user base).  Moreover,
whereas adption of the AORTA API demonstrates a company's commitment to
accessibility, dropping it has unfortunate optics.

[IFTTT]: https://ifttt.com/
[Orchard Platform]: https://www.orchardplatform.com/
[Stripe]: https://stripe.com/
[mParticle]: https://www.mparticle.com/?utm_source=adwords&utm_medium=paid-search&utm_campaign=homepage-us-key-cities&utm_term=mparticle&utm_content=homepage&gclid=Cj0KCQjwr53OBRCDARIsAL0vKrMVYo59a5R6zGmbDJI5YeyUaglk0CbKyI-RgptSC1eNApkHbcjvMiEaAjxMEALw_wcB
[Beeswax]: https://www.beeswax.com/
[Gamoshi]: http://www.gamoshi.com/
[Xamarin]: https://www.xamarin.com/platform
[Socrata]: https://socrata.com/?gclid=Cj0KCQjwgIPOBRDnARIsAHA1X3So3EjDQWKet_0B6PESqpTVFJvVnpAMUpJmSvYBv5LyQKwpGbhLk6UaAm5pEALw_wcB
[Enigma]: https://www.enigma.com/solutions
[Polly]: https://aws.amazon.com/polly/
[Lex]: https://aws.amazon.com/lex/

[spotify]: https://adstudio.spotify.com/?utm_source=us-en_brand_spotifyadvertising_text&utm_medium=paidsearch&utm_campaign=2017q3_us_us_productmarketing_adstudio&gclid=CIGEjOqLv9YCFYSGswodOHwBcQ&gclsrc=ds
[nyt]: https://www.nytimes.com/2017/07/31/business/media/amazon-advertising.html
