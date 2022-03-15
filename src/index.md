---
title: Hello World
layout: index.hbs
---

<ol>
    {{#each post}}
        <li>{{this.name}}</li>
    {{/each}}
</ol>