+++
date = '2025-08-04T17:22:16+02:00'
draft = false
title = 'Goodbye Wordpress'
+++

After years of running WordPress, I've finally bit the bullet and moved to a
Static Site Generator, in my case: Hugo. After long deliberation, I decided not
to move most of the old content over. 

I registered palstra.com in 2000, and at that time, still built it by hand in
plain HTML, sometimes with help of some tooling. In 2004, I moved over to
Movable Type, and after some time, migrated to WordPress.

That old blog was a mix of lifeblogs, linkdumps, technobabble and pictures and
most of the links no longer work, pictures were taken offline and subjects are
no longer relevant. Also, my life looks a lot different now than it did 20
years ago.

This website travelled around a lot, from an old PC running Linux at home in
Hellevoetsluis, to an old UltraSPARC next to my desk at the Herengracht running
Solaris, an old 4U server running FreeBSD at Redbus, moved to SchubergPhilis,
after which it finally migrated to an Ubuntu VM at TransIP, while at the same
time Apache and mod_php were finally replaced by nginx and php-fpm.

Now a lot of the PHP and WordPress headaches are gone, with this site being
built by a GitHub Deployment or Netlify Deploy. I've been moving around some
static sites between GitHub Pages, AWS S3 with Clouddflare and Netlify and for
now am staying at that last one. Moving around a static website and changing
the pipeline output to a new destination seems a lot easier than any WordPress
I've ever migrated.

For now, I'm keeping the stack as is, but I'll always keep tinkering in the
background, so don't be surprised if you see Astro, Eleventy or any other new
shiny tool fly by in the future.
