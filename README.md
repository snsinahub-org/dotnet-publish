# dotnet-restore

```YAML
    - name: print 2
      uses : snsinahub-org/dotnet-build@main
      with:
        path: 'C:\Users\user\'
        file_extenstion: "*.csproj"
        build_configuration: "release"
        test_path: "test_path"
        temp_path: "temp_path"
        test_depth: "Integer"
```