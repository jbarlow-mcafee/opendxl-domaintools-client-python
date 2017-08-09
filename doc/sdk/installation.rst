Library Installation
====================

Prerequisites
*************

* OpenDXL Python Client library installed
   `<https://github.com/opendxl/opendxl-client-python>`_

* The OpenDXL Python Client prerequisites must be satisfied
   `<https://opendxl.github.io/opendxl-client-python/pydoc/installation.html>`_

* The DomainTools API DXL service is running and available on the DXL fabric
    `<https://github.com/opendxl/opendxl-domaintools-service-python>`_

Installation
************

Use ``pip`` to automatically install the library:

    .. parsed-literal::

        pip install dxldomaintoolsclient-\ |version|\-py2.7-none-any.whl

Or with:

    .. parsed-literal::

        pip install dxldomaintoolsclient-\ |version|\.zip

As an alternative (without PIP), unpack the dxldomaintoolsclient-\ |version|\.zip (located in the lib folder) and run the setup
script:

    .. parsed-literal::

        python setup.py install