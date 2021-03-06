---
-api-id: M:Windows.Devices.PointOfService.IReceiptOrSlipJob.DrawRuledLine(System.String,Windows.Devices.PointOfService.PosPrinterLineDirection,System.UInt32,Windows.Devices.PointOfService.PosPrinterLineStyle,System.UInt32)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public void DrawRuledLine(System.String positionList, Windows.Devices.PointOfService.PosPrinterLineDirection lineDirection, System.UInt32 lineWidth, Windows.Devices.PointOfService.PosPrinterLineStyle lineStyle, System.UInt32 lineColor)
-->

# Windows.Devices.PointOfService.IReceiptOrSlipJob.DrawRuledLine

## -description
Adds an instruction to the print job to print a drawn, ruled line on the paper of the receipt or slip printer station.

## -parameters
### -param positionList
The position parameters for the ruled line. The character string for *positionList* differs depending on whether *lineDirection* specifies a horizontal ruled line or a vertical ruled line.

### -param lineDirection
The direction in which to print the ruled line.

### -param lineWidth
The width of the ruled line that the printer station should print. The unit of width is dot. If an unsupported value is specified, the best fit value for the printer station is used.

### -param lineStyle
The appearance of the ruled line, such as whether it is solid or broken, or single or double.

### -param lineColor
The color of the ruled line, as an integer value that is equal to the value of the cartridge constant used in the [ICommonClaimedPosPrinterStation.ColorCartridge](claimedjournalprinter_colorcartridge.md) property. If an unsupported value is specified, the printing results may be unpredictable.

## -remarks

## -examples

## -see-also
[ReceiptPrintJob.DrawRuledLine](receiptprintjob_drawruledline.md), [SlipPrintJob.DrawRuledLine](slipprintjob_drawruledline.md), [ICommonClaimedPosPrinterStation.ColorCartridge](claimedjournalprinter_colorcartridge.md), [PosPrinterLineDirection](posprinterlinedirection.md), [PosPrinterLineStyle](posprinterlinestyle.md)