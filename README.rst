priceline-python
===================

Priceline Python API

Disclaimer
----------

This is a unofficial python API wrapper for priceline.com

Using this software might contradict priceline.com terms of service

Currently this is just a proof of concept

Requirements
------------

* requests

Usage:
------

* Perform a basic one-way flight itinerary search::

	from priceline import Api
	s = Api.air_search(origin="SFO", destination="LAX", departure_date="2015-09-14")

	
.. image:: https://travis-ci.org/nderkach/priceline-python.png
    :target: https://travis-ci.org/nderkach/priceline-python
