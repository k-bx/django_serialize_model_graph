Serialize Model Graph
============================

With `serialize_model_graph`, you can serialize your model (and
its relatives) into a data structure that can be stored somewhere,
and then re-stored later.

Installation:

    python setup.py install

And add to your installed apps like so:

INSTALLED_APPS = (
    ...
    'serialize_model_graph',
    ...
)

Documentation can be found at [ReadTheDocs](https://django_serialize_model_graph.readthedocs.org/en/latest/).

Works via full-serializers, based on wadofstuff-django-serializers for full serialization
Documentation can be found at [ReadTheDocs](http://code.google.com/p/wadofstuff/wiki/DjangoFullSerializers).