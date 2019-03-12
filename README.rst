==========
py-meetups
==========

We are a group of volunteers who is trying to organize python meetups and workshops in Amsterdam.

This repository contains history of our events/taks/workshops currently organised via `Pyamsterdam@meetup.com <pyamsterdam-meetup>`_

So far we were able to present `these talks and workshops <History.rst>`_

.. |logo| image:: resources/images/pyAmsterdam.svg
   :scale: 40%
   :align: middle

|logo|


Contribution:
-------------

You can contribute to our cause by:

* Giving a talk on our meetups
* Creating a workshop
* Providing us with space where we can gather and talk about python
* Submitting a topic you'd like to hear about or try hands on


Our organisation structure is very simple

.. code-block:: text

    .
    ├── events  # anything event specific
    │   └── 2019-02-13
    │       └── Readme.rst
    ├── resources
    │   └── _org_examples
    │       ├── events
    │       │   └── 2019-01-01
    │       │       └── README.rst
    │       ├── talks
    │       │   └── example-talk.rst
    │       └── workshops
    │           └── example-workshop.rst
    ├── talks
    │   └── talk1.rst
    └── workshops
        └── Workshop-name
            └── Readme.rst



Talks
#####

Would you like a give a talk?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Do you have anything to you'd like to share and talk about?

#. Create branch ``talk/talk-title``

#. Add new file to ``talks/`` directory ``talks/awesome-python.rst``

#. Write a short description (see `example <resources/_org_examples/talks/example-talk.rst>`_

   * Talk title

   * Author

   * Abstract

#. Create a pull request from your branch/fork to the master


Events
######

To organise new event via this repository, please follow steps below.

You can view sample content of

#. Create new branch eg. `event/2019-01-01`

#. Create new directory in ``events`` with date prefix
   `YYYY-MM-DD` and more optional info eg. ``events/2019-01-01-meetup-location``.

#. Add a ``README.rst`` or ``README.md`` file inside eg. ``events/2019-01-01-meetup-location/README.rst``

#. Write a brief description about the event. See `example README.rst <resources/_org_examples/events/2019-01-01/README.rst>`

   * event name

   * links to talks stored in ``talks/`` directory

   * Links to workshops stored in ``workshops/directory``

#. Create a pull request from your branch/fork to the master


Workshops
#########

#. Create new branch eg. `workshop/2019-01-01`

#. Create new directory in ``workshops`` with date prefix
   `workshop-name`

#. Add a ``README.rst`` or ``README.md`` file inside eg. ``events/2019-01-01-meetup-location/README.rst``

   * Optionally add other necessary files (code, workshop steps)

#. Write a brief description about the workshop. See `example <resources/_org_examples/workshops/example-workshop.rst>`

   * Workshop name

   * Brief description

#. Create a pull request from your branch/fork to the master



Other suggestions and requests
##############################

Use this flow if your contribution do not fit in anything above.

Then create an issue with your suggestion.

Examples:

* Do you have an idea what would you like to learn and share?
* Is there any specific topic you'd like to propose for discussion?
* Interesting article/tutorial which can be presented live as a talk or workshop.


Topics we'd like to cover:
##########################

* Migration from `legacy python` to `python3`

* Virtual envs

* Dependency management

* Deployment as ‘single binary’ (PEX)

* Packaging

  * pyproject.toml

    * Flit - https://github.com/takluyver/flit

    * Poetry

  * Pipenv

  * setup tools

* Server Less python

  * AWS Lambda
  * Google Cloud Functions
  * Azure functions
