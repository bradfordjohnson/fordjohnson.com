```{=html}
<% for (const item of items) { %>
  <a href="<%= item.href %>" class="project-row">
    <h5><%= item.title %> <span>↗</span></h5>
    <small><%= item.subtitle %></small>
    <p><%= item.description %></p>
  </a>
<% } %>
```