# devprx - easy proxy integration for your sites

Front end proxy; made for beginners (don't use this if you're serious about making a proxy site)

why you might want to use this:
works with all front end hosts
easily integratable
since it can be hosted on a frontend you can put it on azure which is usually *never* blocked!

main way to use it:
iframe a game url or app/site in one of your sites (hopefully apps as you should just find source code for games but I'm assuming you're proxying multiplayer games to have multiplayer connectivity) with the url such as `mydevprxsite.com/?url=https://play.geforcenow.com` or something, or have it on a html file

when you shouldn't use this:
when you want to use this only for proxying sites, yes this means that proxying sites is 100x better (imo) but deploying your own clone becomes useless so if your devprx url gets blocked either you're gonna have to tell people how to make their own devprx url or incorporate simple-bare with your backend which makes frontend proxies useless

instructions:

1. deploy https://github.com/DoxrGitHub/simple-bare, host that on flow, hop.io, glitch, or even replit! (the filters doesn't care about this)
2. (I just made a repo for this lol) host https://github.com/DoxrGitHub/dev-prx (currently moving to github rn) anywhere (frontend hosts!!) or integrate this in a file like prx.html
3. iframe the site as `myproxysite.com/?url=https://example.com` or if you integrated it `proxy.html?url=https://example.com` where example.com is proxied!

yes this is for extreme beginners and anyone even a bit more experienced should be able to easily incorporate a uv backend with their project but if you can't do that just use devprx

an example hosted on cloudflare pages:
https://doxrcfuv.pages.dev
