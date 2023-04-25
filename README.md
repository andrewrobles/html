# gh

```html
{% for todo in todo_list %}
    {% if todo.done %} 
        <input type="checkbox" checked> 
    {% else %} 
        <input type="checkbox">
    {% endif %}
    <label>{{todo.text}}</label>
    <br>
{% endfor %}	
```