# Realtime Counter with redis on Flask

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

{{ count_this_path() }}

~~~

![alt text](https://github.com/brenden17/Realtime-Counter-with-Flask-on-Redis/blob/master/img/like.png "image")

That's all.