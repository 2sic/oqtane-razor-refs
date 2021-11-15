# oqtane-razor-refs
Oqtane `refs` Folder for Razor to have Runtime Compile

[2sxc oqtane module](https://github.com/2sic/2sxc) require `refs` folder for run-time compilation of cshtml (razor pages) and cs files. 
Because `refs` are currently not distributed or deployed as part of [Oqtane install zip](https://github.com/oqtane/oqtane.framework/releases) or [ToSic.Sxc.X.X.X.nupkg](https://github.com/2sic/2sxc/releases) end user has to manually provide `refs` in Oqtane installation. 

## Oqtane 3.0.0 installation on .NET6.0
Unzip *net6.0-refs.zip* as `<root>/refs/`.

## Oqtane 2.0.0 installation on .NET5.0
Unzip *net5.0-refs.zip* as `<root>/refs/`.

## More info
- `refs` folder is generated as part of publish step of ASP.NET Core application that support razor run-time compilation and contians reference assemblies 
for all app references and its dependecies (aka compilation context)
- [Reference assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/reference-assemblies)
