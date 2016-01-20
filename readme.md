# Real Counter with redis on Flask

This is Flask extension which implements page view counter, page like counter based on Redis 

## Reqirements

* Redis server
* Python library
~~~
pip install flask-session
pip install redis
~~~
* Bootsrap
 
## How to use
Just put snippet on html page.

~~~

{{ count_path() }}

~~~

That's all.