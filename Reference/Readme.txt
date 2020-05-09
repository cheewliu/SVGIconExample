1. Get icons pack (from anywhere) in svg format
2. Use SvgToXaml.exe to convert the icons into .xaml format
3. Copy the generated .xaml file into your project
4. Note that you can change the color of the icons in .xaml, look for example:
	GeometryDrawing Brush="#FF000000"
   Change the Brush to desired color or reference it to your theme's glyph:
	GeometryDrawing  Brush="{DynamicResource Control.Static.Glyph}"
