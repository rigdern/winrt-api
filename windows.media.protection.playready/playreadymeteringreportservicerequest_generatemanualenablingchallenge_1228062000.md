---
-api-id: M:Windows.Media.Protection.PlayReady.PlayReadyMeteringReportServiceRequest.GenerateManualEnablingChallenge
-api-type: winrt method
---

<!-- Method syntax
public Windows.Media.Protection.PlayReady.PlayReadySoapMessage GenerateManualEnablingChallenge()
-->

# Windows.Media.Protection.PlayReady.PlayReadyMeteringReportServiceRequest.GenerateManualEnablingChallenge

## -description
Begins the process of manually enabling.

## -returns
The SOAP message to be used in a manual license acquisition challenge request.

## -remarks
Provides the caller the raw HTTP challenge and headers that they must send up to the server. When the response is received, it should be processed by calling the [ProcessManualEnablingResponse](playreadymeteringreportservicerequest_processmanualenablingresponse.md) method.

Calling this method places the class in a read-only state even if the method does not succeed.

## -examples

## -see-also
