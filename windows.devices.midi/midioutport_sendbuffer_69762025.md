---
-api-id: M:Windows.Devices.Midi.MidiOutPort.SendBuffer(Windows.Storage.Streams.IBuffer)
-api-type: winrt method
---

<!-- Method syntax
public void SendBuffer(Windows.Storage.Streams.IBuffer midiData)
-->

# Windows.Devices.Midi.MidiOutPort.SendBuffer

## -description
Send the specified data buffer to the device associated with this [MidiOutPort](midioutport.md).

## -parameters
### -param midiData
The data to send to the device.

## -remarks
If this method fails with **RO_E_CLOSED**, it can be assumed that the [MidiOutPort](midioutport.md) has been disconnected from the device.

See [Obtaining pointers to data buffers (C++/CX)](https://msdn.microsoft.com/windows/apps/dn182761.aspx#) for more info.

## -examples

## -see-also
