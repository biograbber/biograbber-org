---
title: Requirements
weight: 10
disableToc: true
---

Thanks to the simplicity of Hugo, this page is as empty as this theme needs requirements.

Just download latest version of [Hugo binary (> 0.25)](https://gohugo.io/getting-started/installing/) for your OS (Windows, Linux, Mac) : it's that simple.

![Magic](/basics/requirements/images/magic.gif?classes=shadow)

![Capture](/images/capture.jpg)

Biograbber is a free professional video capture software for standards sources of V4L2 (Video for Linux) and UVC (USB Video Class).

There are many free software projects supporting the development of applications capable of capturing video following the standard V4L2. However, the functional development of these projects is very limited and does not meet professional requirements.

Any video device compatible with UVC standard will work with Biograbber, including webcams, but also many other professional capture devices capable of transforming signals HDMI, SDI, VGA, DVI, VHS, S-VHS, etc. to a USB signal compatible with UVC.

[Hugo-theme-learn](http://github.com/matcornic/hugo-theme-learn) is a theme for [Hugo](https://gohugo.io/), a fast and modern static website engine written in Go. Where Hugo is often used for blogs, this multilingual-ready theme is **fully designed for documentation**.

This theme is a partial porting of the [Learn theme](http://learn.getgrav.org/) of [Grav](https://getgrav.org/), a modern flat-file CMS written in PHP.

{{% notice tip %}}Learn theme works with a _page tree structure_ to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "docs/pages/_index.md"%}}) 
{{% /notice %}}

## Main features

## Main features

* [Automatic Search]({{%relref "/basics/configuration/_index.md#activate-search" %}})
* [Multilingual mode]({{%relref "/docs/i18n/_index.md" %}})
* **Unlimited menu levels**
* **Automatic next/prev buttons to navigate through menu entries**
* [Image resizing, shadow...]({{%relref "/docs/markdown.en.md#images" %}})
* [Attachments files]({{%relref "/docs/shortcodes/attachments.en.md" %}})
* [List child pages]({{%relref "/docs/shortcodes/children/_index.md" %}})
* [Mermaid diagram]({{%relref "/docs/shortcodes/mermaid.en.md" %}}) (flowchart, sequence, gantt)
* [Customizable look and feel and themes variants]({{%relref "/basics/style-customization/_index.md"%}})
* [Buttons]({{%relref "/docs/shortcodes/button.en.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "/docs/shortcodes/notice.en.md" %}}), [Expand]({{%relref "/docs/shortcodes/expand.en.md" %}})

![Capture](/images/capture.jpg)
## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it

{{% notice info %}}
Your modification will be deployed automatically when merged.
{{% /notice %}}

## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t hugo-theme-learn` -- source code is [available here at GitHub](https://github.com/matcornic/hugo-theme-learn)

{{% notice note %}}
Automatically published and hosted thanks to [Netlify](https://www.netlify.com/). Read more about [Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)
{{% /notice %}}
