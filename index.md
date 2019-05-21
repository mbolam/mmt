---
title: Home
---

# Metadata Management Tools

{% include figure.html img="tool-box.jpg" alt="toolbox" caption="Tool Box - CC0 - https://www.publicdomainpictures.net/en/view-image.php?image=100369" width="75%" %}

*Participants will use hands-on activities to learn how to incorporate different metadata management tools into their workflows, discuss example use cases for each tool, and have the opportunity to collaborate on problem-solving metadata workflow issues.*

Learn how to create a super quick easy website for a workshop by writing a few markdown files!
Host it for free on GitHub with gh-pages, and share!
Fun!

*See also:* [workshop-template-b](https://evanwill.github.io/workshop-template-b/), Bootstrap version.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})) Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> based on content created by Kelsey George
>
>workshop template: cc-by-sa <a href="https://github.com/evanwill">evan will</a> 2016. (get <a href="https://github.com/evanwill/workshop-template">source code</a>)
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
