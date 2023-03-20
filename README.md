# ValueLinkList

ValueLinkList is a .NET source generator for generating a zero allocation link list to a member of an object.

### How to install
Add `ValueLinkList` as an analyzer project reference:
```xml
    <ItemGroup>
        <PackageReference Include="ModernUO.ValueLinkList.Annotations" Version="1.0.0" />
        <PackageReference Include="ModernUO.ValueLinkList.Generator" Version="1.0.0">
            <SetTargetFramework>TargetFramework=netstandard2.0</SetTargetFramework>
            <OutputItemType>Analyzer</OutputItemType>
            <ReferenceOutputAssembly>false</ReferenceOutputAssembly>
            <PrivateAssets>all</PrivateAssets>
        </PackageReference>
    </ItemGroup>
```

## Usage

### Basic Usage

