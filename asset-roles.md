
| Role Name | Source | Description                                                            |
| --------- | -------------|----------------------------------------------------------------------- |
| thumbnail | [Item Spec](item-spec/item-spec.md#asset-role-types) | An asset that represents a thumbnail of the item, typically a true color image (for items with assets in the visible wavelengths), lower-resolution (typically smaller 600x600 pixels), and typically a JPEG or PNG (suitable for display in a web browser). Multiple assets may have this purpose, but it recommended that the `type` and `roles` be unique tuples. For example, Sentinel-2 L2A provides thumbnail images in both JPEG and JPEG2000 formats, and would be distinguished by their media types. |
| metadata  | [Item Spec](item-spec/item-spec.md#asset-role-types) |  A metadata sidecar file describing the data in this item |
| overview  | Best Practice | An asset that represents a possibly larger view than the thumbnail of the Item, for example, a true color composite of multi-band data. |
| graphic | Best Practice | Supporting plot, illustration, or graph associated with the Item |
| data-mask | Best Practice | File indicating if corresponding pixels have Valid data and various types of invalid data |
| land-water | Best Practice | Points to a file that indicates whether a pixel is assessed as being land or water. |
| water-mask | Best Practice | Points to a file that indicates whether a pixel is assessed as being water (e.g. flooding map). | iso-19139 | Best Practice | Points to an [ISO 19139](https://www.iso.org/standard/67253.html) metadata xml file |
| iso-19115 | Best Practice | Points to an [ISO 19115](https://www.iso.org/standard/53798.html) metadata file |


Some of the particular asset roles also have some best practices: