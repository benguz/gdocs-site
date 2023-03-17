# Setup instructions

1. (You'll need a github account) clone this repo.
2. Go to nav.html, which will be at the top of every page on your site.
3. Change the all caps text to your desired content. Make sure to also change file names if you change href links (subhead1.html).

## To add your own google docs
1. In the Google doc you want to add to your blog go to File > Page Setup. Change your document color to match the background color you chose for your site (we use white by default) and change the margins to 0.3 on the top and bottom and 0 on each side. This will look odd in the doc, but much cleaner online.
2. Change your font to something that will look good in a browser: Roboto, Roboto Slab, Arial, and Georgia are some good options.
3. Hit File > Share > Publish to Web, shift to the Embed tab, and click Publish. You’ll see a little block of code: copy the quoted text in src=""
4. Go to the file you want to change, in the "iframe" line, find src="" and put your copied text between the quotation marks
5. Push changes
6. Make sure to try your site on mobile so the formatting looks good on both places. If not, you can serve a different google doc for the mobile version, for example.

## To publish your website

Github pages or vercel