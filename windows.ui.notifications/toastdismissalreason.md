---
-api-id: T:Windows.UI.Notifications.ToastDismissalReason
-api-type: winrt enum
-api-device-family-note: xbox
---

<!-- Enumeration syntax
public enum Windows.UI.Notifications.ToastDismissalReason : int
-->

# ToastDismissalReason

## -description
Specifies the reason that a toast notification is no longer being shown. Used with [ToastDismissedEventArgs.Reason](toastdismissedeventargs_reason.md).

## -enum-fields
### -field UserCanceled:0
The user dismissed the toast notification.

### -field ApplicationHidden:1
The app explicitly hid the toast notification by calling the [ToastNotifier.hide](toastnotifier_hide_1807990681.md) method.

### -field TimedOut:2
The toast notification had been shown for the maximum allowed time and was faded out. The maximum time to show a toast notification is 7 seconds except in the case of long-duration toasts, in which case it is 25 seconds.


## -remarks

## -examples

## -see-also
[ToastDismissedEventArgs.Reason](toastdismissedeventargs_reason.md), [Toast notifications sample](https://go.microsoft.com/fwlink/p/?linkid=231503), [Sending toast notifications from desktop apps sample](https://go.microsoft.com/fwlink/p/?linkid=231503), [Toast XML schema](https://docs.microsoft.com/uwp/schemas/tiles/toastschema/schema-root), [Toast notification overview](https://msdn.microsoft.com/library/14a07fce-d631-4bad-ab99-305b703713e6), [Quickstart: Sending a toast notification](https://msdn.microsoft.com/library/098df37c-4d40-4499-b809-ccb651da1cba), [Quickstart: Sending a toast push notification](https://msdn.microsoft.com/library/bb962e30-6c95-4186-8a0e-6683140e17c7), [Quickstart: Sending a toast notification from the desktop](https://msdn.microsoft.com/library/1d20ed75-e24a-4e60-91ab-cfcbe902a68e), [Guidelines and checklist for toast notifications](https://msdn.microsoft.com/library/002951e3-3d2d-454a-a0b7-daa5c1e7178a), [How to handle activation from a toast notification](https://msdn.microsoft.com/library/74ba3513-0a52-46a0-8769-ed58abe7c05a), [How to opt in for toast notifications](https://msdn.microsoft.com/library/809cdd36-6de1-4de0-88b2-62b46cafdb28), [How to schedule a toast notification](https://msdn.microsoft.com/library/18a09413-1679-4606-8175-346f4fe6a4f8), [How to enable desktop toast notifications through an AppUserModelID](https://msdn.microsoft.com/library/bb32cd0a-99e6-47dc-a913-39a7b3027314), [The toast template catalog](https://msdn.microsoft.com/library/1a437614-4259-426b-8e3f-ca57368b2e7a), [Toast audio options](https://msdn.microsoft.com/library/12185879-1f9b-4bdc-99e7-a6f2f62806cb)
