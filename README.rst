==========================================
Interactive Login to Liberta Casa Services
==========================================


Creating a Dev Env
==================

- Install ``conda`` and initialize
-  ``source anaconda3/bin/activate``
- ``conda install py38`` 
- ``cd path/to/dir``
- ``pip install rasa``


Rasa setup and command list
===========================

- ``rasa init`` to create a new project
- ``rasa train`` to train your model

Entity Extraction
=================

- Using duckling the easy way ``docker run -p 8000:8000 rasa/duckling``
- docs https://duckling.wit.ai/#getting-started