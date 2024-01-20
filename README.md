# uBlockOrigin & uBlacklist Huge AI Blocklist
A huge blocklist of sites (~700) that contain AI generated content, for the purposes of cleaning Google Image Search.



## How to install the blocklist? (uBlock Origin)

1. Make sure that you have the uBlock Origin Extension, either for [firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) or [chrome](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) (also works on Android)

2. Click on the uBlock Origin Extension, and in the bottom right, there is a cog-wheel symbol--named the dashboard. Click it.

3. Once you are in the dashboard, look towards the top. Click on the tab that says "Filter lists"

4. Look towards the bottom, and expand the ```Import``` button.

5. Copy and paste this url ```https://raw.githubusercontent.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/main/list.txt``` into the dialogue box.

6. Apply changes, and your set!

A video guide on how to do this is available, as well:

https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/assets/128162304/7b8810dc-ce87-4cdc-8b5a-95dc5b0f56c3


uBlock Origin will automatically refresh the filter list once a day, so you'll always have up-to-date filters. 

If you want to force an update of the filter list, pressing the stopwatch next to the newly added list, then pressing ```Update now``` will achieve that.

## How to install the blocklist (uBlacklist)

1. Make sure that you have the uBlacklist extension, either for [firefox](https://addons.mozilla.org/en-US/firefox/addon/ublacklist/) or [chrome](https://chromewebstore.google.com/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe)

2. Click on your extensions list, select uBlacklist, then click on the "options" text, highlighted in blue.
> This will take you to the uBlacklist options panel, similar to the Dashboard in uBlock Origin

3. Scroll all the way down until you see the "Subscription" tab, and click on the blue "Add a subscription" button.

4. Give a name for the added blocklist. (eg. Main AI blocklist)
  
5. Copy and paste this url ```https://raw.githubusercontent.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/main/list_uBlacklist.txt``` into the "URL" part of the dialogue box, then press the blue "Add" button.

6. There you go! You're done!

7. (optional) Set the update interval to an hour for near-realtime list updates.


## Additional list(s)

As of right now, there are two lists. The main default list, and the nuclear list. 

The nuclear list has sites that contain a mix of authentic and AI generated imagery (eg. DeviantArt, Artstation, Stock Photography sites, etc), which make it tricky to outright block in the main filter list, so I've designated it to a separate list that you can toggle on and off if you so desire.

### uBlock Origin
In order to use the ```Nuclear``` list, do the same steps that you did in the section "How to install the blocklist (uBlock Origin)", but instead of using the other url, use ```https://raw.githubusercontent.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/main/additional_list_nuclear.txt```

### uBlacklist
In order to use the ```Nuclear``` list, do the same steps that you did in the section "How to install the blocklist (uBlacklist)", but instead of using the other url, use ```https://raw.githubusercontent.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/main/list_uBlacklist_nuclear```

## What is the difference between uBlock Origin and uBlacklist implementations?
uBlock Origin's implementation technically superior, as it allows you to continue scrolling even when tons of blocked websites are queried, since all it does is **set the offending sites' opacity to 0** instead of using traditional blocking methods. 

uBlacklist on the otherhand, **blocks the queries outright**--meaning if too many AI sites are in your Google Image Search results, you will not be able to scroll any father then the first 6 rows of images.

Although the latter is inferrior, it is a bit rare for that to happen, especially if you append operators such as ```-ai``` in your query. Just keep that in mind (it may also be a bug on uBlacklist's part).

## What if you want to go even further beyond?

I created a [repo that houses fantastic tips & tricks for Google Search's operators](https://github.com/laylavish/TipsTricksGoogleSearch/tree/main). Eradicate AI even more!!


## To Do
✅ Provide blocklist for uBlacklist compatibility


## Special thanks

Special thanks to this [pastebin](https://pastebin.com/B8kP4imQ) (since it added even more sites to my blocklist) and to u/AchernarB for the [awesome snip-bit of code.](https://www.reddit.com/r/uBlockOrigin/comments/13uyex5/how_to_block_results_from_a_specific_site_in_the/)
