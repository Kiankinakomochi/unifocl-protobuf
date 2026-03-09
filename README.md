# unifocl-protobuf

Source-of-truth Protocol Buffer contracts and generated .NET DTO assembly for unifocl CLI/Bridge communication.

## Layout
- `contracts/*.proto`: contract definitions
- `src/Unifocl.Shared`: .NET class library that auto-generates C# from `.proto`

## Build
```bash
dotnet build src/Unifocl.Shared/Unifocl.Shared.csproj --disable-build-servers -v minimal
```
