---
comments: true
---
As nCoV/COVID-19 spreads, so as the support from open source community. Here lists the projects supporting different areas all over the world.
See also [projects for China 中国相关项目](china)



{% assign projects = site.data.world %}

{% include projects.md %}

<!--
{% for country in projects %}
## {{ country.country }}
{% for repo in country.repos %}
* {% if repo.repo_name %} ![](https://img.shields.io/github/stars/{{ repo.repo_name }}?color=yellow&label=%E2%AD%90%EF%B8%8F&logoColor=blue&style=plastic) [{{ repo.repo_name }}](https://github.com/{{ repo.repo_name }}) {% endif %} {% if repo.repo2_name %} ![](https://img.shields.io/github/stars/{{ repo.repo2_name }}?color=yellow&label=%E2%AD%90%EF%B8%8F&logoColor=blue&style=plastic) [{{ repo.repo2_name }}](https://github.com/{{ repo.repo2_name }}) {% endif %} {% if repo.web_name %}[{{ repo.web_name }}]({{ repo.web_url }}){% endif %} {% if repo.web2_name %}[{{ repo.web2_name }}]({{ repo.web2_url }}){% endif %} {{ repo.content }} {% endfor %}
{% endfor %}
-->



### Site recommendation
[Open Source COVID-19](https://weileizeng.github.io/Open-Source-COVID-19/) collects all open source sites related to  nCoV/COVID-19. It is hosted on [GitHub](https://github.com/WeileiZeng/Open-Source-COVID-19). You are welcome to recommend a site by
* [openning issue at GitHub](https://github.com/WeileiZeng/Open-Source-COVID-19/issues/)
* or [contact me](https://weileizeng.com/news/1992/06/29/contact/)




{% include page_summary_world.md %}

{% include footer.md %}