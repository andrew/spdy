!SLIDE 
# SPDY #

!SLIDE
# What it is?

  Experimental, open networking protocol from Google

!SLIDE bullets incremental
# Goals of SPDY

  * Reduce page load time, up to 50% speedup
  * Minimise rollout complexity 
  * Don't require changes to content or html
  * Engage the open source community

!SLIDE bullets incremental
# Technical features

  * Allows many concurrent http requests over a single TCP session
  * Compresses headers
  * Remove unecessary headers
  * Easy(ish) to implement and server efficient

!SLIDE bullets incremental
# Moar features

  * SSL for everything
  * Bi-directional 
  * Server push
  * Server hint
  * request prioritization 

!SLIDE bullets incremental
# Browser Implementations

  * Google chrome
  * Firefox (beta)
  * Kindle Fire
  * Chrome for Android

!SLIDE bullets
# Sites

  * Most of Google - search, gmail, adword
  * Joyent
  * Nodejitsu

!SLIDE bullets
# Server implementations

  * Apache (mod_spdy)
  * Node.js
  * Ruby
  * Python
  * Erlang
  * Go, Java, C...

!SLIDE bullets incremental
# Drawbacks
  
  * Content push ignores browser caches
  * Filtering software that inspects http requests may break (charles proxy)
  * Nginx, apache, varnish don't really work well with it

!SLIDE bullets incremental
# Other cool stuff

  * W3C considering it as a standard
  * Websockets over spdy
  * Using spdy between services and apis on servers
  * Spdy for iOS

!SLIDE bullets
# Links

  * Whitepaper - http://fwdtek.com/spdy
  * The SPDY Book - http://fwdtek.com/spdy-book
  * Code - https://gist.github.com/1994433

!SLIDE
# Fin.