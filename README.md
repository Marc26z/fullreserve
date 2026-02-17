# Fullreserve
I created a landing Page for my nostr blog. [Ghost](https://ghost.org/) is cool, but I got tired of fixing my mini PC evertime it overheats, the SSD harddrive dies or whatever. This is made with HTML, CSS,, and Javascript. I one shot vibe coded it using Claude Haiku 4.5. It totally screwed  the images so I needed to manually add them and I couldn't get the footer to center so I spaghetti coded the HTML, but it works.

## Features
The tip jar at the bottom currently has a link to zap me a coffee.

### Road Map
I plan to add a Support Page based on [Gigi's Support Page](https://dergigi.com/support/) 
#### Lightning Backend
I use [Albyhub](https://albyhub.com/). I tested it while it was in alpha mode and know how to run it on my own hardware, but I prefer to use the cloud to support the project and it still runs when my computer dies. If you're less technial, you can use alby hub to create your own lightning address.
##### Blog Posts
The blog posts are [nostr NIP-23, kind: 30023](https://nostrhub.io/23) posts. Habla.news is my favorite, but you can find other blogging clients at [Awesome Nostr](https://github.com/aljazceru/awesome-nostr). Just hit ctrl + f and search the term `blog`.
###### Tip Jar
The tip jar is based on [this repository](https://github.com/Marc26z/NostrTipJars) I made to help people who work at businesses that accept bitcoin to accept bitcoin tips. I use `lightning:fullreserve@getalby.com` for the QR code, but if you're not technical you can use any lightning address you have listed on Primal and take a screenshot of the lightning address QR code.
