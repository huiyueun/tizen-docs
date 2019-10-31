# Flex Layout

[Overview](#overview)<br>
[FlexDirection](#flexDirection)<br>
[FlexJustification](#flexJustification)<br>
[AlignmentType](#alignmentType)<br>
[FlexWrapType](#flexWrapType)<br>


<a name="overview"></a>
## Overview

`FlexLayout` is a flexible box layout, providing a more efficient way to lay out, align and distribute space among items in the container, even when their size is unknown or dynamic.

A layout which provides features like wrapping so if items no long fit on an axis they can automatically be positioned on another row or column.

`FlexLayout` defines four properties that affect the size, orientation, and alignment of child views. These properties are described in more detail in the table below.
Please see each categories below.

`Justification` applies to the flex Direction axis whilst `Alignment` is the (other) cross axis. Changing the Direction will apply the `Justification` to the new direction.

Natural size of items are used which can be different for each item.

Setting the size of an item has no effect.

| Property               | Type            | Description |
| -----------------------| --------------- | ------------ |
| `Direction`            | FlexDirection   | The orientation the flex items are laid out in (Column/Row) |
| `Justification`        | FlexJustification | Alignment of items along the flex axis when free space available |
| `Alignment`            | AlignmentType     | Alignment of items along the cross axis when free space available |
| `WrapType`             | FlexWrapType    | Enable wrapping of items |

<a name="flexDirection"></a>
## FlexDirection

`Direction` property specifies the main axis direction along which flex items are placed.

Column, ColumnReverse, Row, and RowReverse

<a name="flexJustification"></a>
## FlexJustification

`Justification` property specifies the alignment for flex items, when they do not use all available space on the main axis.

FlexStart, Center, FlexEnd, SpaceBetween, and SpaceAround

<a name="alignmentType"></a>
## AlignmentType

`Alignment` property specifies the alignment for flex items when they do not use all the available space on the cross axis.

Auto, FlexStart, Center, FlexEnd, and Stretch

<a name="flexWrapType"></a>
## FlexWrapType

`WrapType` property specifies whether the flex items must wrap if there is not enough room for them on 1 flex line.

NoWrap, and Wrap

// https://developer.tizen.org/development/guides/.net-application/natural-user-interface/ui-components/flexcontainer  <- Refer to this page, especially images


## Related information

- Dependencies
  -  Tizen 5.5 and Higher
