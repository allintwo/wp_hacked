# wp_hacked

Few days ago my wp site got hacked by http://kacottagexk.kenrei.top/ .
I found the shell file in my index.php and folders
It creating fake sitemap and generating fake html pages to google bot and storing user password into plugins/log.txt

## How to stop

First rename public_html to public_html_back
download WORDPRESS and replace all code.
delete all shell files.
rename public_html_back to public_html

## what they do ?
They hacked your website then show their china product to your website.
exmaple http://kacottagexk.kenrei.top/indexnew.php?web=localhost&zz=1&uri=%2Fhackershell%2Filn_hacked.php&urlshang=&http=http&lang=en-US%2Cen%3Bq%3D0.5
This url displaying girls makeup  image url https://static.mercdn.net/item/detail/orig/photos/m67276099516_1.jpg

When googlebot or other bot indexing your website it cloaking your page and showing this product to bot.
When user visit using bot indexed list thay will able to see their product.



### why site get hacked

I have installed plugin name wp-filemanager-pro. This plugin have backdoor.
My login limit was not limited so hacker was attact brute force and xmlrpc.php .
