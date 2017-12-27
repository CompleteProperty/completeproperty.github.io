---
layout: post
title:  "Jekyll Notes"
date:   2017-12-10 12:12:00 -0500
slug: "jekyll-notes"
tags: [milk, pumpkin pie, eggs, juice]
categories: jekyll
---

See the [Jekyll docs][jekyll-docs] for details on using Jekyll.

### Commands
`$ jekyll serve` runs the local web server at http://127.0.0.1:4000/

`$ jekyll serve --drafts` runs the local web server and includes posts in the _drafts folder

`$ jekyll build` to generate into ./_site

`$ jekyll build --destination {destination}` to generate into {destination}

`$ jekyll build --source {source} --destination {destination}` to generate {source} folder into {destination}

`$ jekyll build --watch` to generated into ./_site and regenerated when changes happen

### Front Matter

For more details see the [front matter documentation](https://jekyllrb.com/docs/frontmatter/)

```yaml
---
layout: post
title:  "Jekyll Notes"
date:   2017-12-10 12:12:00 -0500
slug: "jekyll-notes"
tags: [milk, pumpkin pie, eggs, juice]
categories: [milk, pumpkin pie, eggs, juice]
---
```

[jekyll-docs]: https://jekyllrb.com/docs/home
