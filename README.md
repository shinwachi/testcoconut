# testcoconut
[Vagrant](https://www.vagrantup.com/) setup for [coconut](http://coconut-lang.org/) + [jupyter](http://jupyter.org/) combination.

Coconut is a functional programming language based on Python, recommended for Python users.

A simple vagrant setup so you can get started with the [coconut tutorial](http://coconut.readthedocs.io/en/master/HELP.html).

To run:
```
vagrant up
vagrant ssh
```

Then in vagrant's VM shell:
```
sudo coconut --jupyter notebook --port 8888 --ip=0.0.0.0 --no-browser
```


Then browse to: [`http://localhost:8890`](http://localhost:8890)
