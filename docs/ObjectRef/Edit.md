# Edit

The EWC implementation of Edit has some degree of support for:

 |   Attach    |   FieldType  |   Posn     |  *Text    |
 |   Border    |   Font       |  *SelText  |  *Value   |
 |   Decimals  |   FontObj    |   Size     |   Visible |
 |   Event     |   MaxLength  |   Style    |           |
 |   FCol      |   Password   |   Styles   |           |

* indicates that the property can change after it has been set.

Supported events:

 |  Change  |  GotFocus  |  KeyPress  |         |

Known limitations of the Edit implementation:

There is limited support for FieldType, but Numeric and Date should work.

                                                    
