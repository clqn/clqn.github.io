# quine.xyz

welcome to the internet home of colleen quine (she/her), an unapologetically communist lesbian witch. you can find me on the <a rel="me" href="https://witches.live/@colleen">fediverse!</a>

{% for post in site.posts %}
- [{{post.title}}]({{post.url}}) - {{post.date | date: "%Y-%m-%d"}}
{% endfor %}

## [colleen's cookbook](./recipes.md)
