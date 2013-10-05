====================
Section Title 1
====================

--------------------------------------------------
Section Title 2
--------------------------------------------------

Section title 3
====================

Section title 4
------------------------------

Section title 5
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^



Inline Markup:
--------------------
*italic*

**strong emphasis**
`interpreted *text*`

``hello *italic*``

Escaping with Backslashes:
--------------------------------------------------
*escape* ``with`` "\"
\*escape* \``with`` "\\"

Paragraphs
----------
This is a paragraph.

Paragraphs line up at their left edges, and are normally separated by blank lines.

Bullet lists:
-------------
- this is item 1
- this is item 2

- Bullets are "-", "*" or "+". Continuing text must be aligned after the bullet and whitespace.

Note that a blank line is required before the first item and after the last, but is optional between items.


mynew list :

- item 1
- item2

- item3


Enumerated lists:
--------------------
1. this is the first item
2. this is the second
3. this is the fifth
#. This item is auto-enumerated
#. This is the last

Definition Lists:
--------------------
what
 Definition lists associate a term with a definition. (one/two/TAB or more space char is allowed)

How
	The term is a one-line phrase, and the definition is one or more paragraphs or body elements, intented relative to the term. Blank lines are not allowed between term and definition

	This is the second para

	This is the third paragraph

		
Field Lists:
--------------------

:Autors:
		Zhang Kang,
		David Goodger
		
		(and sundry other good-natured folks)
:Version: 1.0
:Dedication: To my father

Option Lists:(where is the difference with the source code ??)
-----------------------------------------------------------------
-a				command-line option "a"
-b file			options can have arguments and long descriptions
--long			options can be long also
--input=file	long options can also have arguments

LiteralBlocks:
--------------------
A paragraph containing only two colons indicated that the following indented or quoted text is a literal block.
::

 Whitespace, newlines, blank lines, and all kinds of markup (like *this* or \this) is preserved by literal blocks.
 The paragraph containing only '::' will be omitted from the result.

The ``::`` may be tacked onto the very end of any paragraph. The ``::`` will be omitted if it is preceded by whitespace.
The ``::`` will be converted to a single colon if preceded by text, like this::

 It's very convenient to use this form.

Per-line quoting can also be used on unindented literal blocks::

>Useful for quotes from email and
>for Haskell literate programming.

or this(not list)::

-first
-second


Line Blocks(what's it mean ?)
----------------------------------------
| Line blocks are useful for addresses,
| verse, and adornment-freee lists.
|
| Each new line begins with a vertical bar ("|").
|		Line breaks and initial indents are preserved.
| Continuation lines are wrapped
 portions of long lines; they begin
 with spaces in place of vertical bars.


Transitions:
--------------------

A transition marker is a horizontal line of 4 or more repeated punctuation characters.

--------------------

A transition should not begin or end a section or document, nor should two transitions be immediately adjacent.

Tables:
----------
Grid table:

+----------+----------+----------+
| header 1 | header2  | header 3 |
+==========+==========+==========+
|body row1 | column2  | column 3 |
+----------+----------+----------+


External Hyperlink:
--------------------
External hyperlinks, like Python_.

.. _Python: http://www.python.org/

Internal HyperLink Targets:
------------------------------
Internal crossrefernces, like example_

.. _example:

This is an example crossreference target

this is `a link contained space`_

.. _`a link contained space`: http://www.baidu.com



Directives:
-----------
For example, an image:

.. image:: ./star.png


Citation:
----------
Citation reference, like [CIT2002]_.
Note that citations may get rearranged, e.g., to the bottom of the "page".

.. [CIT2002] A citation
 (as often used in journals).


 syntax highlight with line number

.. sourcecode:: c
   :linenos:
   
   #include <stdio.h>
   int main()
   {
	 for(i=0;i<10;i++)
		printf("hello\n");
	 return 0;
	}

Contain an external source file( valid in sphnix):

.. .. literalinclude:: tmp.c
..    :language: c
..    :emphasize-lines: 12,15-18
..    :linenos:


控制光标在节标记间顺序移动的函数是
--------------------------------------------------
哈哈，`还不错吗`_, site_. 但是怎么支持中文？？

.. _`还不错吗`: http://www.google.com
.. _site: http://www.baidu.com

