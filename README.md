This fork gives up original full binding approach, it only wraps gde apis.

Make sure putting this at `addons/csharp_gdextension_bindgen` as I put the generated cs files into the subfold `Generated` (and ignored them by `.gdignore` as they are actually not godot csharp scripts.)

`GDExtension.csproj` may be useful if you want to split the generated files into another csproj (make sure to edit and match your godot and .net version here, and also exclude generated cs files in your main csproj), otherwise you can just ignore it.
