TiaC Systems Network (TSN) GitHub Workflows
===========================================

This repository contains a lot of reusable GitHub workflows for TiaC Systems
Network (TSN). This means that standard procedures in the CI pipelines can be
used again and again and maintained here at a central location.

Documentation
-------------

The documentation overview is in this `readme in the project root directory
<README.rst>`_.

.. rubric:: Further readings:

- https://docs.github.com/en/actions/sharing-automations/reusing-workflows
- https://docs.github.com/en/actions/learn-github-actions/variables
- https://docs.github.com/en/actions/learn-github-actions/contexts#env-context
- https://docs.github.com/en/actions/learn-github-actions/expressions#fromjson
- https://docs.docker.com/build/ci/github-actions/multi-platform
- https://docs.docker.com/build/ci/github-actions/cache

.. rubric:: Examples for inspirations:

- https://www.jitsejan.com/use-github-actions-with-json-file-as-matrix
- https://github.com/orgs/community/discussions/68732

- https://medium.com/@aarne.laur/retry-failed-github-actions-8661e7601c66
- https://stackoverflow.com/a/78314483

Content
-------

Currently supported:

- `Docker`_: for multi-platform images with multi-stage Dockerfiles

References
----------

.. target-notes::

.. _`Docker`: https://docker.com/
