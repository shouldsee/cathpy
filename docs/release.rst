cathpy.core.release
===================

.. code:: python

    from cathpy.core.release import (
        CathDomainList, 
        CathNamesList,
        CathDomall, )

    domainlist = CathDomainList.from_file('/path/to/CathDomainList.list')

    domainlist[5].domain_id = '3b89A01'
    domainlist[5].cath_id = '1.10.8.10.2.1.1.2.1'

    sreps = domainlist.filter_reps(depth=5)
    sreps.to_file('/path/to/CathDomainList.S35.list')

.. automodule:: cathpy.core.release
    :members:

