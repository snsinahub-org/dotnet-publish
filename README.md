# dotnet-restore

```YAML
    - name: donet restore-build-test
      uses : snsinahub-org/dotnet-all@main
      with:
        path: 'C:\Users\user\'
        file_extenstion: "*.csproj"
        build_configuration: "release"
        test_path: "test_path"
        temp_path: "temp_path"
        test_depth: "Integer"
```