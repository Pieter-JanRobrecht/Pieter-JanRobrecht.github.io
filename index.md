## Hi

It's me!
You probably don't know me and that's just fine.
If it's your first time here 'Welcome!'.
You might wonder what this place is?
And to be honest you are not the only one...
It's mainly a place for me to put some thoughts down really.
In an informal way.
Anyways, there should be a button or a list here somewhere that might lead you to one of my thoughts, experiments, ... .
Have a lovely day and see you later!

## Posts

<br />
{%- if site.posts.size > 0 -%}
  {%- for post in site.posts -%}
    {%- assign date_format = "%Y-%m-%d" -%}
    [{{ post.date | date: date_format }}] [{{ post.title | escape }}]({{ post.url | relative_url }})  
  {%- endfor -%}
{%- endif -%}
