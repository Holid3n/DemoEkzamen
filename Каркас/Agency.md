![image](https://github.com/Holid3n/DemoEkzamen/assets/97594334/095291fd-5d0b-4589-bfe7-79bf32a57410)
"git.enabled": false,
"git.path": null,
"git.autofetch": false
<Window x:Class="TurAgency.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:TurAgency"
        mc:Ignorable="d"
        Title="TurAgency" MinHeight="450" MinWidth="800" Background="CadetBlue">
    <Grid >
        <Grid.ColumnDefinitions>
           
        </Grid.ColumnDefinitions>
        <Grid.RowDefinitions>
            <RowDefinition Height="auto">   
            </RowDefinition>
            <RowDefinition Height="*"></RowDefinition>
        </Grid.RowDefinitions>

        <StackPanel Orientation="Horizontal" Background="Aqua">
            
            <Image Stretch ="Uniform" MaxHeight="112" MaxWidth="110" Source="/resorces/Logo.png"/>
            <TextBlock  FontSize="18" FontFamily="Palatino Linotype" Foreground="Black"  VerticalAlignment="Center" Margin="10,0,0,0" >Туристическое агенство</TextBlock>
            <Button x:Name="Authorize"  ClickMode="Press" Margin="30,0,0,0" HorizontalAlignment="Center" Background="blue"  VerticalAlignment="Center" Foreground="White" >
                Автризация
            </Button>
        </StackPanel>
        
    </Grid>
</Window>
