---
-api-id: P:Windows.Media.Core.VideoStreamDescriptor.IsSelected
-api-type: winrt property
---

<!-- Property syntax
public bool IsSelected { get; }
-->

# Windows.Media.Core.VideoStreamDescriptor.IsSelected

## -description
Gets a value indicating whether the stream is currently in use by a [MediaStreamSource](mediastreamsource.md).

## -property-value
**true** if the stream is currently in use by a [MediaStreamSource](mediastreamsource.md); otherwise, **false**.

## -remarks
IsSelected is **true** if the stream represented by the stream descriptor is currently selected by the media pipeline. For example, if it is currently in use by a [MediaStreamSource](mediastreamsource.md). Otherwise, the value is **false**.

[MediaStreamSource](mediastreamsource.md) only raises the [SampleRequested](mediastreamsource_samplerequested.md) event for streams which are selected.

## -examples

## -see-also
