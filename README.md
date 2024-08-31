# Holodex & Hyperchat Tweaks

## Description
Improved dark mode, adjustable chat and menu width, hiding scrollbars/buttons and many more tweaks.

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/Himither/Holodex-Hyperchat-Tweaks/master/holodex.user.css)

## Preview
![Main preview image](/previews/1.png)

## Details
### Notice
Rarely, **when Hyperchat has an update waiting for you to accept**, the styling will temporarily not affect it until you **confirm the update**.

### [Holodex](https://holodex.net/)
**Turn on Holodex own dark mode** for the the two extended dark modes to display properly.

Unless you're using fullscreen mode anyway I would recommend Firefox over Chrome, because there's no ugly border on the top. Of course you need to install a nice pure black theme to make it fit.

### [Hyperchat](https://livetl.app/hyperchat)
If you want to **always see Live Chat** activate the hyperchat setting:

*HyperChat Settings -> Additional Options -> "Automatically switch to Live Chat"*

Alternatively you could set the dropdown menu to show again and **increase the chat width** enough for it to display properly

### Custom Avatar
You can simply insert a link or [convert a Image to Base64](https://codebeautify.org/image-to-base64-converter) and use it in a [Data URL](https://developer.mozilla.org/en-US/docs/Web/URI/Schemes/data). 

**In both cases you must _wrap your input in single quotes_.** 

> Link: ```'https://example.link'```

> Data URL : ```'data:image/webp;base64,<Base64 String>'``` (for a converted .webp)

In my experience it seems to be fine to omit the MIME type in this particular use-case. So ```'data:;base64,<Base64 String>'``` does also suffice.

**Full example**:

```'data:image/webp;base64,UklGRlQEAABXRUJQVlA4WAoAAAAQAAAAHwAAHwAAQUxQSBICAAABkCzJtmlb8+LZtm3btm3bttG0bdu2bfsd7mNjazS21vuDiJgA0p+iWIMGRZKJfaGVb2y2V0vyMyt4RgYA6Vg+RsnLJIj/TCLEBYlsCr6BuLtylQMSnuVlU4uDqQpRLRusVZlZahDV42Cpwib/S0hH6tY/KeNxbjYJC0RInEMGP4NYpmpSJPdBHgD4PdmLNU5pKMVY2+WyRZZzgHVxofLXLSOStZKSiSjlGCfkV8fPcoDlzIk3ADciBRElJxK1XVU9kXq4YJjrREm1VzWnFJvxfUaONv+M/WqWc84vrEnKfguIn63X5y+EO3sPmYDfB/c+kPCza8OLPHAlS7lvAPBl0KBvBwulyHoROJYpRbHjn3oP+wEAH0u2dCrgWtAwJ1G688CR1ES5GyzxQGlv1D+ogujcIpkpjSIlZSq6KA5Vf89JMUX08foJ96/ObXEdONN4zuWH0zY8jSnCI+byClcHqumExPkBl02CqzZ18ypiU+eJfhOAAxlqO6HTWSfzcUA2BcTZk18N6eMCInMa2PRwTRbFAK77iFej85agNFsAeHf8iXp5Be+Nmg74AHldqoSSuYmISj0EIHi2rw8qQpt2eUUAd4qRdr3XAGSzBapWqwzgRS3SW+8BjMp3apH+Ehtd+hxri5LRNO0uRLQi51qnJobZR79Tkd+MzEaMy210A851ZYh9ms63b3ZMTf+1QH4yClZQOCAcAgAAcAsAnQEqIAAgAD6ROplIpaMiITAYCACwEglsALElQX4BoAOKpcDgAbZO7Rt5drj75X0BCK6wFeLZAhhPj9+oPYJ/VXq6eRmtrnQSuH3ChFE4opckVa3JtNmgrMpnoyY2Qqa/AAD+/1bByQ5X7f0FTbi9///oM9b4f0UKG5y0ZhjoB/F7d+1RfznoN9iPabRgW1getuHgD2DWz6uPj/qi5/3xYQGFe5tvdt1DnN/n+f87rh3rajElPRgjpj/UNhp5SXw+fXe/kVgQTCs6yRzefU0NTyPZdFkfqZQQ3FzLCM+efETin6icjy1f29m33qq7ettIJTOaeddxZAvVkj3Aga8u/7YiHGmiX/HQKN9ZHVgMHzbUD4lyP6we+QPSqOOUyLexvYaByClWPrTsmSdquMyf6dxsv7UQteanXgr6VDL6d/6+7bwWR41XQ8TT/pYs9Oz/5Wkw1dufjWKEK1daMzPiZ8D8GZvSc+OzSKD520BH+WZdbVjqzUxplzwOtDApjr06+La0Fb4XdP8OhH1PvPnwM3cSjWojaZbWuyx5/n54WqjevlxBh38so/VYGAYUHaGHcvmX58rdxbTbwTYaCD791QbZ++nS00qtH7iffOGjtAT+v0rzWF4/L1llWUuQ55bKYt7/rEf3cwfTBVAb/dTFRYmD6tH5JjFEgkGINv2LXVUCeBLlyxnDmrNrbaex7GrVSmaxwF3HB+AA'```
