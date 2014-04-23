#jekyll-recent-posts

Customize your jekyll blog to display your most recent posts.

    {% for post in site.posts limit:5 %}  
      <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  
    {% endfor %}  