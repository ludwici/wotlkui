.. meta::
   :keywords: wotklui, layout, layoutframe, layoutframetype, lua, xml, trinitycore, trinity, mangos, cmangos, azerothcore, script, scripting, doc, docs, documentation, ui, addons, wotlk

.. _xml_LayoutFrame:

LayoutFrame
===========
**<LayoutFrame>** - base tag for many UI elements.

.. code-block:: xml

    <LayoutFrame>
        <Size />
        <Anchors />
        <Animations />
    </LayoutFrame>

Inheritance
-----------
Inherited by: :ref:`Frame<xml_Frame>`, :ref:`FontString<xml_FontString>`, :ref:`Texture<xml_Texture>`

Attributes
----------
* **name** (string :abbr:`? (optional)`) - Set unique global name of element
* **inherits** (string :abbr:`? (optional)`) - Name of the base frame whose parameters will be borrowed
* **virtual** (boolean :abbr:`? (optional)`) - Make this frame virtual. The frame itself will not exist and can only be as a base frame for other interface elements. **name** required in this case
* **setAllPoints** (boolean :abbr:`? (optional)`) - Set anchors to *TOPLEFT* and *BOTTOMRIGHT* of parent frame
* **hidden** (boolean :abbr:`? (optional)`) - If true frame will not showed by default
* **parentKey** (string :abbr:`? (optional)`) - Create frame identifier and added it to parent

Elements
--------
* **Size**
* **Anchors**
* **Animations**