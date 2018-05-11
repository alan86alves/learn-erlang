<p align="center">
  <img src="https://readtiger.com/img/wkp/en/Erlang_logo.png">
</p>

# Introduction

* Erlang, was developed by Ericson in 1986, the goal was to solve the telephony problem of the time. It has a VM called BEAM that is extraordinarily powerful. It was built to guarantee an availability of 99.9999999%. The name Erlang refers to "Ericsson Language".

* Joe Armstrong remarked in an interview with Rackspace in 2013: “If Java is 'write once, run anywhere', then Erlang is 'write once, run forever'.”[14]

* The Erlang view of the world, as Joe Armstrong, co-inventor of Erlang, summarized in his PhD thesis:

	* Everything is a process.

	* Processes are strongly isolated.

	* Process creation and destruction is a lightweight operation.

	* Message passing is the only way for processes to interact.

	* Processes have unique names.

	* If you know the name of a process you can send it a message.

	* Processes share no resources.

	* Error handling is non-local.

	* Processes do what they are supposed to do or fail.

- [x] https://en.wikipedia.org/wiki/Erlang_(programming_language)

# Install 

```bash
$ sudo /bin/su -c "echo 'deb http://binaries.erlang-solutions.com/debian raring contrib' >> /etc/apt/sources.list.d/erlang.list" 
```

```bash
$ wget -O - http://binaries.erlang-solutions.com/debian/erlang_solutions.asc | sudo apt-key add -
```

```bash
$ sudo apt-get update
```

```bash
$ sudo apt-get install esl-erlang
```

```bash
$ erl
Erlang R16B03-1 (erts-5.10.4) [source] [64-bit] [smp:4:4] [async-threads:10] [hipe] [kernel-poll:false]

Eshell V5.10.4  (abort with ^G)
1> 
```

Type `q().` to exit.

## The Free Lunch Is Over

- [x] http://www.gotw.ca/publications/concurrency-ddj.htm
- [x] https://en.wikipedia.org/wiki/Herb_Sutter
- [x] https://www.slideshare.net/Muhammad_Rizwan/the-free-lunch-is-over-43055538
- [x] https://softwareengineering.stackexchange.com/questions/212916/is-the-free-lunch-over

## The Actor Model

- [x] https://en.wikipedia.org/wiki/Actor_model
- [x] https://en.wikipedia.org/wiki/Carl_Hewitt
- [x] https://hal.archives-ouvertes.fr/hal-01163534v7/document
- [x] https://www.youtube.com/watch?time_continue=46&v=7erJ1DV_Tlo
- [x] https://www.brianstorti.com/the-actor-model/