# AdGuard custom filters

Here are some files providing filters for AdGuard (may be working with other adblockers like uBlock).

## Adding a filter via github

For AdGuard :
1. Click on the filter's file you want (the ones with .txt)
2. Click on "Raw"
3. Go to Adguard configuration, select 'Filters', then 'Custom'
4. Click 'Add', then copy-paste the github URL you got by clicking 'Raw' previously
5. Save and enjoy

## Customizing a filter

You can fork this repo for sure !

You can copy-paste these files in the 'User rules' of AdGuard too, then you can modify them as you want.

## Importing my personal config file

My personal config file 'Personal AdGuard configuration.json' allows me to avoid ads and social media tweaks.

Right now in April 2026, I've been using it for over 6 years without a problem.

You can still edit the config : once you imported it, nothing will prevent you from modifying the imported configuration via the admin page of Adguard.

## List of filters

- **annoying-html-blocks.txt**: My personal list for HTML blocks that annoys me while browsing some regular websites

- **not-supported-websites.txt**: Avoid blocking anything on specific sites since AdGuard is breaking the service

- **youtube-hide-shorts.txt**: Hide traces of Shorts on Youtube, configured just to hide the videos but can be uncommented to block any trace of Shorts ; works with PC web browser extension and iOS app

- **youtube-hide-watched.txt**: Hide watched videos, configured to hide videos that are watched 90% of the lenght and up from Home, Subscriptions Channels and Watch ; can be modified to change % ; works with PC web browser extension and iOS app

- Static files (no changes planned):
   - **local-ips.txt**: Avoid blocking anything on LAN, useful if you are hosting some service

## Special thanks

- gijsdev for his work on Youtube Shorts for uBlock Origin, big inspiration for my AdGuard list (see his work [here](https://github.com/gijsdev/ublock-hide-yt-shorts))

## License

See [LICENSE.md](https://github.com/Norsagir/adguard-custom-filters/blob/main/LICENSE.md)
