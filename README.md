# How-to-Add-a-Separator-in-the-.NET-MAUI-OTP-Input-Control
This repository contains a sample explaining how to add a separator in the .NET MAUI OTP Input Control.

### Separator customization support in .NET MAUI OtpInput

You can improve readability by adding a custom character between OTP fields using the [Separator]( https://help.syncfusion.com/cr/maui-toolkit/Syncfusion.Maui.Toolkit.OtpInput.SfOtpInput.html#Syncfusion_Maui_Toolkit_OtpInput_SfOtpInput_Separator) property.

The following code example illustrate how to Customize Separator in SfOtpInput.

### XAML
```
<syncfusion:SfOtpInput Separator="-" Value="9183"/>

```
### C#

```
var otpInput = new SfOtpInput
{
    Separator = "-",
    Value = "9183"
};

```
