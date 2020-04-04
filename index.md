---
layout: default
title: Introduction 
nav_order: 1
description: "Instructions to use the MindBody software at Academie Duello"
permalink: /
---

# MindBody 
{: .fs-9 }

MindBody software 
{: .fs-6 .fw-300 }

[Get started now](https://mindbody.io){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } <br> 
[<img src="http://github.com/clintonbf/Lynns-and-Clints-doc-project/blob/gh-pages/assets/images/apple-logo.jpg?raw=true" width="20" height="20" />](https://apps.apple.com/us/app/mindbody-gym-spa-wellness/id689501356?_branch_match_id=774734447297851430){: .btn .fs-5 .mb-4 .mb-md-0 }
[<img src="http://github.com/clintonbf/Lynns-and-Clints-doc-project/blob/gh-pages/assets/images/android.jpg?raw=true" width="20" height="20" />](https://play.google.com/store/apps/details?id=com.mindbodyonline.connect&hl=en_US&_branch_match_id=774734447297851430){: .btn .fs-5 .mb-4 .mb-md-0 }
---

## About _MindBody_... 

This is a software that allows you to browse for "fitness membership, workout classes, wellness services, beauty appointments and more" - [_MindBody.io_](http://mindbody.io). 

### Things MindBody offers...


#### Quick start:

1. You can

1. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```yaml
remote_theme: pmarsceill/just-the-docs
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-2019 by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
