---
layout: post
title: Rail Views Django Templates
---

Rail Django

    <%= book.title %>  {{ book.title }}

    <% @books.each do |book| %>
        <tr>
        <td><%= book.title %></td>
        </tr>
    <% end %>
    
    
    {%  for book in book %}
        <tr>
        <td>{{ book.title }}</td>
        </tr>
    {% end %}
    
    
    <%= link_to 'Show', book %>
    
    <a href="{% url show book.id %}"</a>
    
    
    <%= render "shared/menu" %>
    
    {% include "shared/menu.html" %}

