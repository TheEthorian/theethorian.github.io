---
layout: default
---

<style>
    time {
        font-size: small;    
    }
</style>

## About

### Simplified

I can make applications and exploits in many forms.

### Canonical

I'm from Ethoria, transmitting signals from Standard Ethorithican with a transcoder that converts them to "English".
The Central Government of Ethoria (CGoE) also anonymizes any traffic signals sent to the Network of Earth (NoE).

## Accounts

Verify Ethorian accounts and signatures

Email
: [ethorian](mailto:ethorian@protonmail.com)(@protonmail.com)
				
GitHub
: [TheEthorian](https://github.com/TheEthorian)

## Blog

{% for post in site.posts %}
<h3>{{ post.title }} <time datetime="{{ post.date | date_to_xmlschema }}">({{ post.date | date_to_string }})</time></h3>

{{ post.content }}
{% endfor %}

