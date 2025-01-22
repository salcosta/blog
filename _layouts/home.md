---
layout: none
---
{{ site.posts.first }}

<!-- 
<section id="recent-posts">
  <h2>Recent Posts</h2>
  <ul>
    {% for post in site.posts limit:5 %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>        
      </li>
    {% endfor %}
  </ul>
</section> -->

<style>
    #recent-posts {
  right: 0;
  position: fixed;
  margin: 2em 0;
  padding: 1em;
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 5px;
  top: 100px;
}

#recent-posts h2 {
  margin-bottom: 1em;
  font-size: 1.5em;
}
#recent-posts ul {
  list-style-type: none;
  padding: 0;
}
#recent-posts li {
  margin-bottom: 0.5em;
}
#recent-posts a {
  text-decoration: none;
  color: #007acc;
}
#recent-posts a:hover {
  text-decoration: underline;
}
</style>