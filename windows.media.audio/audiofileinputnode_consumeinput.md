---
-api-id: P:Windows.Media.Audio.AudioFileInputNode.ConsumeInput
-api-type: winrt property
---

<!-- Property syntax
public bool ConsumeInput { get;  set; }
-->

# Windows.Media.Audio.AudioFileInputNode.ConsumeInput

## -description
Gets or sets a value indicating if the audio file input node consumes input.

## -property-value
True if the audio file input node consumes input, and false otherwise.

## -remarks
You can stop all audio processing of a node by calling [Stop](audiofileinputnode_stop_1201535524.md). Set **ConsumeInput** to false to mute the input of the node instead. This can be useful in scenarios such as when the node has an effect with a decay applied, such as delay or reverb. Setting **ConsumeInput** to false will stop the node from consuming audio data while allowing effects to continue processing.

## -examples

## -see-also
