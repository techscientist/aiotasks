TODO
====

New features
------------

- [X] Add a `send_tasks(..)` function
- [X] Add `current_app` var, like Flask does.
- [ ] Add actor model for each consummer
- [ ] Add ack when a messages was processed ok in an task
- [ ] Add RabbitMQ as a broker
- [ ] Add ZeroMQ as a broker
- [X] Add plugin for aiohttp
- [ ] Next task to execute

Improvements
------------ 

- [ ] Fix the fixture `redis_instance` to fix the correct shutdown of Redis test service
- [X] Add a warning message when use `memory://` as a backend.
- [ ] Add unsubscribe method for AsyncTaskSubscribeBase base class
- [ ] Add Cython in critical parts


Testing
------- 

- [ ] Add cyclomatic complexity check
- [ ] Add Pylint test
- [X] Add flake8 test
- [ ] Add doctest
- [ ] Improve test for actions.*.console