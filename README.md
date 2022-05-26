# dotnet-restore

```YAML
    - name: donet publish
      uses : snsinahub-org/dotnet-publish@main
      with:
        path: 'C:\Users\user\'
        file_extenstion: "*.csproj"
        build_configuration: "release"
        newTag: "newTag"
```