# How to set width for segment item
This section explains how to set width for segment item in segmented control.

## Getting Started with Xamarin Segmented Control (SfSegmentedControl)

This section provides an overview for working with the segmented control for Xamarin.Forms. Walk through the entire process of creating a real-world application with the SfSegmentedControl.

### Adding SfSegmentedControl reference
You can add SfSegmentedControl reference using one of the following methods:

#### Method 1: Adding SfSegmentedControl reference from nuget.org

Syncfusion Xamarin components are available in nuget.org. To add SfSegmentedControl to your project, open the NuGet package manager in Visual Studio, search for Syncfusion.Xamarin.Buttons, and then install it.

#### Method 2: Adding SfSegmentedControl reference from toolbox

Syncfusion also provides Xamarin Toolbox. Using this toolbox, you can drag the SfSegmentedControl control to the XAML page. It will automatically install the required NuGet packages and add the namespace to the page. To install Syncfusion Xamarin Toolbox, refer to Toolbox.

#### Method 3: Adding SfSegmentedControl assemblies manually from the installed location

If you prefer to manually reference the assemblies instead referencing from NuGet, add the following assemblies in respective projects.

Location: {Installed location}/{version}/Xamarin/lib

## Creating a project
Create a new BlankApp (Xamarin.Forms.Portable) application in Visual Studio for Xamarin.Forms.

### Adding SfSegmentedControl in Xamarin.Forms
Add the required assembly references to the PCL and renderer projects as discussed in the Assembly deployment  section.

Import the control namespace as shown in the following code.

**[XAML]**

```
xmlns:buttons="clr-namespace:Syncfusion.XForms.Buttons;assembly=Syncfusion.Buttons.XForms"
```
Set the control to content in ContentPage.

**[XAML]**
```
<ContentPage.Content>
    <buttons:SfSegmentedControl  />
</ContentPage.Content>
```
## Sample for Set width for segment item in segmented control

**[XAML]**
```
<StackLayout  VerticalOptions="CenterAndExpand">
        <buttons:SfSegmentedControl HorizontalOptions="CenterAndExpand" VisibleSegmentsCount="3" SegmentWidth="130" BorderThickness="2"
        SelectedIndex="2"
        BorderColor="#3F3F3F"
        FontColor="Black"
        Color="Transparent"
       CornerRadius="140"
        SelectionTextColor="AliceBlue">
            <sys:List x:TypeArguments="x:String">
                <x:String>Formals</x:String>
                <x:String>Casuals</x:String>
                <x:String>Trendy</x:String>
            </sys:List>
        </buttons:SfSegmentedControl>
        <buttons:SfSegmentedControl HorizontalOptions="CenterAndExpand"  SegmentWidth="100" BorderThickness="2"
        VisibleSegmentsCount="3"
        SelectedIndex="2"
        BorderColor="#3F3F3F"
        FontColor="Black"
        Color="Transparent"
        CornerRadius="100"                      
        SelectionTextColor="AliceBlue">
            <sys:List x:TypeArguments="x:String">
                <x:String>Formals</x:String>
                <x:String>Casuals</x:String>
                <x:String>Trendy</x:String>
            </sys:List>
        </buttons:SfSegmentedControl>
        <buttons:SfSegmentedControl  HorizontalOptions="CenterAndExpand" SegmentWidth="80" BorderThickness="2"
        VisibleSegmentsCount="3"
        SelectedIndex="2"
        BorderColor="#3F3F3F"
        FontColor="Black"
         CornerRadius="80"
        Color="Transparent"
        SelectionTextColor="AliceBlue">
            <sys:List x:TypeArguments="x:String">
                <x:String>Formals</x:String>
                <x:String>Casuals</x:String>
                <x:String>Trendy</x:String>
            </sys:List>
        </buttons:SfSegmentedControl>
        <buttons:SfSegmentedControl  HorizontalOptions="CenterAndExpand" SegmentWidth="60" BorderThickness="2"
        VisibleSegmentsCount="3"
        SelectedIndex="2"
        BorderColor="#3F3F3F"
        FontColor="Black"
        Color="Transparent"
        CornerRadius="60"
        SelectionTextColor="AliceBlue">
            <sys:List x:TypeArguments="x:String">
                <x:String>Formals</x:String>
                <x:String>Casuals</x:String>
                <x:String>Trendy</x:String>
            </sys:List>
        </buttons:SfSegmentedControl>
       
    </StackLayout>
```
## How to run this application?

To run this application, you need to first clone the how-to-set-width-for-segment-item repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.