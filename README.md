# Terms of service scanning AI Chrome extension

[inspiration](https://mymodernmet.com/social-media-policy-infographics-dima-yarovinsky/)

Planning:

popup.html shows on click, tells user to hightligh ToS and then click scan
on scan content.js fetches highlighted text (the ToS), checks if it's non-empty and then sends it to cloudflare AI
Cloudflare AI logs usage, sends back any suspicious content, along with an estimated percentage of your soul you give up when you agree
Display this information in the popup.html