# gh

{% for todo in todo_list %}<br>
&nbsp;&nbsp;&nbsp;&nbsp;{% if todo.done %} <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<input type="checkbox" checked> <br>
&nbsp;&nbsp;&nbsp;&nbsp;{% else %} <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<input type="checkbox"> <br>
&nbsp;&nbsp;&nbsp;&nbsp;{% endif %} <br>
&nbsp;&nbsp;&nbsp;&nbsp;\<label>{{todo.text}}</label> <br>
&nbsp;&nbsp;&nbsp;&nbsp;\<br> <br>
{% endfor %}
