---
-api-id: M:Windows.UI.Notifications.TileUpdateManager.CreateTileUpdaterForApplication(System.String)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public Windows.UI.Notifications.TileUpdater CreateTileUpdaterForApplication(System.String applicationId)
-->

# Windows.UI.Notifications.TileUpdateManager.CreateTileUpdaterForApplication

## -description
Creates and initializes a new instance of the [TileUpdater](tileupdater.md) for a tile that belongs to another app in the same package as the calling app. The [TileUpdater](tileupdater.md) lets a developer change the appearance of that tile.

## -parameters
### -param applicationId
The package-relative application identifier (PRAID) of the tile. The specified app must be in the same package as the calling app. For more info on the PRAID, see the **Id** attribute of the [Application](/uwp/schemas/appxpackage/appxmanifestschema/element-application#attributes-and-elements) element.

If you are hosting background task(s) in an out-of-process COM server, separate from your main application, then pass as the argument for `applicationId` the PRAID of the application that defines the `windows.backgroundTask` extension in its own package manifest.

## -returns
The object you will use to send changes to the tile identified by *applicationId*.

## -remarks
This method is used only in conjunction with multi-app packages. The app identified by *applicationId* must belong to the same package as the caller.

Although you can specify the calling application's tile in this method, [createTileUpdaterForApplication](tileupdatemanager_createtileupdaterforapplication_1541898748.md) is the preferred method to use with single-app packages.

## -examples

## -see-also
[CreateTileUpdaterForApplication](tileupdatemanager_createtileupdaterforapplication_1541898748.md), [App tiles and badges sample](https://go.microsoft.com/fwlink/p/?linkid=231469), [Quickstart: Sending a tile update](https://msdn.microsoft.com/library/d4b2cebf-9dec-4c8f-bc6d-23edca7aaf83), [Tile and tile notification overview](https://msdn.microsoft.com/library/10a05b52-42c4-4f85-9310-57663e378b9e), [The tile template catalog](https://msdn.microsoft.com/library/2d3dd627-9a34-493c-bda4-ff7b80817e4f), [Guidelines and checklist for tiles](https://msdn.microsoft.com/library/e825f754-97dd-41c2-aff4-4dfb60eda677), [How to schedule a tile notification](https://msdn.microsoft.com/library/56b0c3e3-be90-4461-a8b1-79e88072b37c), [How to set up periodic notifications for tiles](https://msdn.microsoft.com/library/96c67773-2e5b-4278-b16d-2f813b16580c), [Tiles XML schema](https://docs.microsoft.com/uwp/schemas/tiles/tilesschema/schema-root)
