# Jekyll-MDB-Cards-Colors
![Index](https://raw.githubusercontent.com/rogeriodeoliveira/Jekyll-MDB-Cards-Colors/master/IndexBlog.png)

      

Example: https://blog.rogeriodeoliveira.com/

**Includes**
* Share bar
* Author
* Read More
* Disqus
* Search (Title)

![Index](https://raw.githubusercontent.com/rogeriodeoliveira/Jekyll-MDB-Cards-Colors/master/PostHeader.png)

![Share bar AuthorRead More](https://raw.githubusercontent.com/rogeriodeoliveira/Jekyll-MDB-Cards-Colors/master/PostShareBarAutorReadmore.png)


**Style**
* MDBoostrap
* Fontawesome

**config.yml**

```

title: Template Jekyll Cards
email: email@gmail.com
description: You description here.
author: you name
about: You is.... 
copyright:  you copy
google-tag-id:  # e.g: XXX-XXXX00X
# Disqus Comments
disqus:
    # Leave shortname blank to disable comments site-wide.
    # Disable comments for any post by adding `comments: false` to that post's YAML Front Matter.
    shortname: #disqus-name-id

baseurl: "" # /blog
url: "" # url https://example.com

social_id:
  - facebook:
  - twitter:
  - google:
  - linkedin:
  - github:

social-share-bar: true

links: # Links navbar
  - title: Home
    url: https://youdomain.com/
  - title: Artigos
    url: https://blog.youdomain.com/
  #- title: Ferramentas
  #  url: https://youdomain.com/ferramentas
  - title: Sobre
    url: https://youdomain.com/sobre
  #- title: Contato
  #  url: https://youdomain.com/contato
  - title: Curso
    url: https://youdomain.com/curso
  - title: Livro
    url: https://youdomain.com/livro
  #- title: Contribua
  #  url: https://youdomain.com/contribuicao

# links
# termo-link: "https://youdomain.com/termo"
brand-link: "https://youdomain.com"
about-link: "https://youdomain.com/sobre/"
markdown: kramdown
highlighter: rouge

plugins:
  - jekyll-feed
  - jekyll-seo-tag
  - jekyll-paginate
  - jekyll-sitemap
  - jekyll-feed

paginate: 9

permalink: /:title/

lang: pt-BR

sass:
    style: :compressed

include: [_redirects]

# Exclude from processing.
# The following items will not be processed, by default. Create a custom list
# to override the default setting.
# exclude:
#   - Gemfile
#   - Gemfile.lock
#   - node_modules
#   - vendor/bundle/
#   - vendor/cache/
#   - vendor/gems/
#   - vendor/ruby/

```

Visit my blog to see real demo https://blog.rogeriodeoliveira.com/

# Setup and Run - Docker
1. Intall Docker - https://docs.docker.com/install/
1.2. Install Docker compose - https://docs.docker.com/compose/install/
2. Fork the template https://github.com/rogeriodeoliveira/Jekyll-MDB-Cards-Colors/fork
3. Clone the repo
4. Edit config.yml for personalize you blog
5. In root folder exec docker-compose up

For update jekyll-docker run script ./dockerUpdate.sh

For build run script ./dockerBuild.sh

# License
This theme is free and open source software, distributed under the The MIT License.

