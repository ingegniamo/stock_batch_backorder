Stock Batch Backorder
===============================
When you confirm a Batch if during validation you confirm backorder creation,
all picking (or their part) not in the originala batch will be placed inside a new batch

Configuration
=============
After installation inside warehouse operation type youll'find a boolean:
"auto_create_batch_backorder"
Check this boolean if you want that all the backorder picking of this type will'be auto posted inside the new batch

Note for developer
=====
Remembre to manage complex situation: like placing 3 picking inside a batch and confirm all of the first one, something of the second one and nothing about the last one
Also check the compability with this module:
https://github.com/OCA/stock-logistics-workflow/tree/14.0/stock_picking_backorder_strategy

Usage
=====
Descriprion usage


Credits
=======

Authors
~~~~~~~

* STeSI s.r.l

Contributors
~~~~~~~~~~~~

* Moccia Francesco <moccia.f@stesi.eu>
