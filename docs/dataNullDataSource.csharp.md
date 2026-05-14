# `dataNullDataSource` Submodule <a name="`dataNullDataSource` Submodule" id="@cdktn/provider-null.dataNullDataSource"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataNullDataSource <a name="DataNullDataSource" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source null_data_source}.

#### Initializers <a name="Initializers" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Null;

new DataNullDataSource(Construct Scope, string Id, DataNullDataSourceConfig Config = null);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.config">Config</a></code> | <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig">DataNullDataSourceConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Optional</sup> <a name="Config" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.config"></a>

- *Type:* <a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig">DataNullDataSourceConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.with">With</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toHclTerraform">ToHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetHasComputedDefault">ResetHasComputedDefault</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetInputs">ResetInputs</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `With` <a name="With" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.with"></a>

```csharp
private IConstruct With(params IMixin[] Mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `Mixins`<sup>Required</sup> <a name="Mixins" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.with.parameter.mixins"></a>

- *Type:* params Constructs.IMixin[]

The mixins to apply.

---

##### `AddOverride` <a name="AddOverride" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToHclTerraform` <a name="ToHclTerraform" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toHclTerraform"></a>

```csharp
private object ToHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `ToMetadata` <a name="ToMetadata" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ResetHasComputedDefault` <a name="ResetHasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetHasComputedDefault"></a>

```csharp
private void ResetHasComputedDefault()
```

##### `ResetInputs` <a name="ResetInputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetInputs"></a>

```csharp
private void ResetInputs()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport">GenerateConfigForImport</a></code> | Generates CDKTN code for importing a DataNullDataSource resource upon running "cdktn plan <stack-name>". |

---

##### `IsConstruct` <a name="IsConstruct" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isConstruct"></a>

```csharp
using Io.Cdktn.Providers.Null;

DataNullDataSource.IsConstruct(object X);
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformElement"></a>

```csharp
using Io.Cdktn.Providers.Null;

DataNullDataSource.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformDataSource"></a>

```csharp
using Io.Cdktn.Providers.Null;

DataNullDataSource.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

##### `GenerateConfigForImport` <a name="GenerateConfigForImport" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport"></a>

```csharp
using Io.Cdktn.Providers.Null;

DataNullDataSource.GenerateConfigForImport(Construct Scope, string ImportToId, string ImportFromId, TerraformProvider Provider = null);
```

Generates CDKTN code for importing a DataNullDataSource resource upon running "cdktn plan <stack-name>".

###### `Scope`<sup>Required</sup> <a name="Scope" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

###### `ImportToId`<sup>Required</sup> <a name="ImportToId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.importToId"></a>

- *Type:* string

The construct id used in the generated config for the DataNullDataSource to import.

---

###### `ImportFromId`<sup>Required</sup> <a name="ImportFromId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.importFromId"></a>

- *Type:* string

The id of the existing DataNullDataSource that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#import import section} in the documentation of this resource for the id to use

---

###### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.provider"></a>

- *Type:* Io.Cdktn.TerraformProvider

? Optional instance of the provider where the DataNullDataSource to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.cdktfStack">CdktfStack</a></code> | <code>Io.Cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>Io.Cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.outputs">Outputs</a></code> | <code>Io.Cdktn.StringMap</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.random">Random</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefaultInput">HasComputedDefaultInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputsInput">InputsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefault">HasComputedDefault</a></code> | <code>string</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputs">Inputs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* Io.Cdktn.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* Io.Cdktn.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.count"></a>

```csharp
public double|TerraformCount Count { get; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Id`<sup>Required</sup> <a name="Id" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Outputs`<sup>Required</sup> <a name="Outputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.outputs"></a>

```csharp
public StringMap Outputs { get; }
```

- *Type:* Io.Cdktn.StringMap

---

##### `Random`<sup>Required</sup> <a name="Random" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.random"></a>

```csharp
public string Random { get; }
```

- *Type:* string

---

##### `HasComputedDefaultInput`<sup>Optional</sup> <a name="HasComputedDefaultInput" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefaultInput"></a>

```csharp
public string HasComputedDefaultInput { get; }
```

- *Type:* string

---

##### `InputsInput`<sup>Optional</sup> <a name="InputsInput" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> InputsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `HasComputedDefault`<sup>Required</sup> <a name="HasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefault"></a>

```csharp
public string HasComputedDefault { get; }
```

- *Type:* string

---

##### `Inputs`<sup>Required</sup> <a name="Inputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Inputs { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataNullDataSourceConfig <a name="DataNullDataSourceConfig" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.Initializer"></a>

```csharp
using Io.Cdktn.Providers.Null;

new DataNullDataSourceConfig {
    SSHProvisionerConnection|WinrmProvisionerConnection Connection = null,
    double|TerraformCount Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners = null,
    string HasComputedDefault = null,
    System.Collections.Generic.IDictionary<string, string> Inputs = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.connection">Connection</a></code> | <code>Io.Cdktn.SSHProvisionerConnection\|Io.Cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.count">Count</a></code> | <code>double\|Io.Cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.dependsOn">DependsOn</a></code> | <code>Io.Cdktn.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.forEach">ForEach</a></code> | <code>Io.Cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.lifecycle">Lifecycle</a></code> | <code>Io.Cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provider">Provider</a></code> | <code>Io.Cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provisioners">Provisioners</a></code> | <code>Io.Cdktn.FileProvisioner\|Io.Cdktn.LocalExecProvisioner\|Io.Cdktn.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.hasComputedDefault">HasComputedDefault</a></code> | <code>string</code> | If set, its literal value will be stored and returned. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.inputs">Inputs</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.connection"></a>

```csharp
public SSHProvisionerConnection|WinrmProvisionerConnection Connection { get; set; }
```

- *Type:* Io.Cdktn.SSHProvisionerConnection|Io.Cdktn.WinrmProvisionerConnection

---

##### `Count`<sup>Optional</sup> <a name="Count" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.count"></a>

```csharp
public double|TerraformCount Count { get; set; }
```

- *Type:* double|Io.Cdktn.TerraformCount

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* Io.Cdktn.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* Io.Cdktn.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* Io.Cdktn.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* Io.Cdktn.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provisioners"></a>

```csharp
public (FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner)[] Provisioners { get; set; }
```

- *Type:* Io.Cdktn.FileProvisioner|Io.Cdktn.LocalExecProvisioner|Io.Cdktn.RemoteExecProvisioner[]

---

##### `HasComputedDefault`<sup>Optional</sup> <a name="HasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.hasComputedDefault"></a>

```csharp
public string HasComputedDefault { get; set; }
```

- *Type:* string

If set, its literal value will be stored and returned.

If not, its value defaults to `"default"`. This argument exists primarily for testing and has little practical use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#has_computed_default DataNullDataSource#has_computed_default}

---

##### `Inputs`<sup>Optional</sup> <a name="Inputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.inputs"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Inputs { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#inputs DataNullDataSource#inputs}

---



