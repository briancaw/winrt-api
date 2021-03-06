---
-api-id: M:Windows.Phone.PersonalInformation.ContactStore.CreateOrOpenAsync
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Phone.PersonalInformation.ContactStore> CreateOrOpenAsync()
-->

# Windows.Phone.PersonalInformation.ContactStore.CreateOrOpenAsync

## -description
Opens the app's custom contact store, creating the store with the default options if it does not already exist.

## -returns
When this method completes, it returns a [ContactStore](contactstore.md) object representing the app's custom contact store. If you use [Asynchronous programming](https://msdn.microsoft.com/library/23fe28f1-89c5-4a17-a732-a722648f9c5e), the result type is [ContactStore](contactstore.md).

## -remarks
When this method is used to create the custom contact store, the default values of **ReadOnly** for [ContactStoreSystemAccessMode](contactstoresystemaccessmode.md) and **LimitedReadOnly** for [ContactStoreApplicationAccessMode](contactstoreapplicationaccessmode.md) are used.

## -examples

## -see-also
[CreateOrOpenAsync(ContactStoreSystemAccessMode, ContactStoreApplicationAccessMode)](contactstore_createoropenasync_214074668.md), [Asynchronous programming](https://msdn.microsoft.com/library/23fe28f1-89c5-4a17-a732-a722648f9c5e)

## -capabilities
ID_CAP_CONTACTS [Windows Phone]
