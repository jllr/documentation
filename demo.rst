Demo Example 
**********************

Paragraphs
----------------------------------

CenturyLink, Inc. is an American worldwide communications company headquartered in Monroe, Louisiana. It provides communications and data services to residential, business, governmental and wholesale customers in 37 states

Inline text
----------------------------------

*some text* (italics)

**some other text** (bold)

``some more other text`` backquotes are for code samples

Lists
----------------------------------

Bulleted list
===========================

* One item
* Two items
* Three items

Numbered list
===========================

1. One item
2. Two items

#. One item
#. Two items

Nested list
===========================

* One item

  * One item
  * Two items

    * One item
    * Two items

Tables
----------------------------------

Grid tables
===========================
+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

Simple tables
===========================

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

Links
----------------------------------

External
===========================

`Github <https://github.com/ElasticBox/documentation>`_

Internal
===========================

`Configure a Hello World box`_

Headings
----------------------------------

This is a h1
**********************

This is a h2
----------------------------------

This is a h3
===========================

Raw code
----------------------------------

Html
===========================

.. raw:: html

	<div class="doc-image padding-1x">
      <img class="img-responsive" src="/../assets/img/docs/tutorials/helloworld-createnewbox.png" alt="Create a New Box Based on Linux Compute">
    </div>


.. raw:: html

  <pre>
  #!/bin/bash
  echo "${Greeting}" > /tmp/hello
  </pre>



