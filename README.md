# How-to-Add-a-Separator-in-the-.NET-MAUI-OTP-Input-Control
This repository contains a sample explaining how to add a separator in the .NET MAUI OTP Input Control. Separators are crucial for improving the readability of OTPs (One-Time Passwords), making it easier for users to enter and verify the code. This guide will show you how to implement this feature using the .NET MAUI toolkit, focusing on the `SfOtpInput` control which provides an easy way to add custom characters between OTP fields.

### Separator customization support in .NET MAUI OtpInput

Customizing the separator involves using the [Separator]( https://help.syncfusion.com/cr/maui-toolkit/Syncfusion.Maui.Toolkit.OtpInput.SfOtpInput.html#Syncfusion_Maui_Toolkit_OtpInput_SfOtpInput_Separator) property available in the SfOtpInput control. You can specify any character as the separator, allowing you to enhance the OTP's presentation according to your application's design requirements.

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
