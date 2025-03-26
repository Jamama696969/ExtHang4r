# ExtHang3r

> [!Disclaimer]  
> It's possible to still do the exploit with this version.

## What is it?
ExtHang3r is an exploit created by <a href="https://github.com/Blobby-Boi/">Blobby Boi</a> that allows ChromeOS users to kill managed extensions after the LTMEAT patch. It remains unpatched in all new ChromeOS versions as of February 2025.

## How does it work?
This exploit works very similar to <b>Dextensify</b>. The main difference being that instead of creating iframes and slowly getting rid of them, a separate popup window is created that spams iframes and refreshes them. After a few seconds, the popup is closed achieving similar behavior to the <b>LTMEAT Flood</b> method. This worked great in paper, but for whatever reason this hang just woudn't let you disable the extension with the file URLs switch. It would instead just restart the extension. However, a solution was quickly found and it was as simple as just attempting to load any of the extension's pages prior to flipping the switch.

## How do I use it?
To use the exploit, paste the following url into your url bar. More detailed instructions are provided in the exploit's page.

> [!TIP]
> If the tab immediately closes after opening, try changing the beginning of the URL from `data:` to `data://`.

```
(removed for simplicitys sake. use https://blobby-boi.github.io/data-URL-Generator if you really need it.)
```
