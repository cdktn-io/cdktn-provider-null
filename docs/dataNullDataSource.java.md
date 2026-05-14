# `dataNullDataSource` Submodule <a name="`dataNullDataSource` Submodule" id="@cdktn/provider-null.dataNullDataSource"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataNullDataSource <a name="DataNullDataSource" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source null_data_source}.

#### Initializers <a name="Initializers" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer"></a>

```java
import io.cdktn.providers.null_provider.data_null_data_source.DataNullDataSource;

DataNullDataSource.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
//  .hasComputedDefault(java.lang.String)
//  .inputs(java.util.Map<java.lang.String, java.lang.String>)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.hasComputedDefault">hasComputedDefault</a></code> | <code>java.lang.String</code> | If set, its literal value will be stored and returned. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.inputs">inputs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `hasComputedDefault`<sup>Optional</sup> <a name="hasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.hasComputedDefault"></a>

- *Type:* java.lang.String

If set, its literal value will be stored and returned.

If not, its value defaults to `"default"`. This argument exists primarily for testing and has little practical use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#has_computed_default DataNullDataSource#has_computed_default}

---

##### `inputs`<sup>Optional</sup> <a name="inputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.Initializer.parameter.inputs"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#inputs DataNullDataSource#inputs}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toHclTerraform">toHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetHasComputedDefault">resetHasComputedDefault</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetInputs">resetInputs</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `resetHasComputedDefault` <a name="resetHasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetHasComputedDefault"></a>

```java
public void resetHasComputedDefault()
```

##### `resetInputs` <a name="resetInputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.resetInputs"></a>

```java
public void resetInputs()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a DataNullDataSource resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isConstruct"></a>

```java
import io.cdktn.providers.null_provider.data_null_data_source.DataNullDataSource;

DataNullDataSource.isConstruct(java.lang.Object x)
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

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isConstruct.parameter.x"></a>

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformElement"></a>

```java
import io.cdktn.providers.null_provider.data_null_data_source.DataNullDataSource;

DataNullDataSource.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformDataSource"></a>

```java
import io.cdktn.providers.null_provider.data_null_data_source.DataNullDataSource;

DataNullDataSource.isTerraformDataSource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.isTerraformDataSource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport"></a>

```java
import io.cdktn.providers.null_provider.data_null_data_source.DataNullDataSource;

DataNullDataSource.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),DataNullDataSource.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a DataNullDataSource resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the DataNullDataSource to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing DataNullDataSource that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the DataNullDataSource to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.outputs">outputs</a></code> | <code>io.cdktn.cdktn.StringMap</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.random">random</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefaultInput">hasComputedDefaultInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputsInput">inputsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefault">hasComputedDefault</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputs">inputs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `outputs`<sup>Required</sup> <a name="outputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.outputs"></a>

```java
public StringMap getOutputs();
```

- *Type:* io.cdktn.cdktn.StringMap

---

##### `random`<sup>Required</sup> <a name="random" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.random"></a>

```java
public java.lang.String getRandom();
```

- *Type:* java.lang.String

---

##### `hasComputedDefaultInput`<sup>Optional</sup> <a name="hasComputedDefaultInput" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefaultInput"></a>

```java
public java.lang.String getHasComputedDefaultInput();
```

- *Type:* java.lang.String

---

##### `inputsInput`<sup>Optional</sup> <a name="inputsInput" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getInputsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `hasComputedDefault`<sup>Required</sup> <a name="hasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.hasComputedDefault"></a>

```java
public java.lang.String getHasComputedDefault();
```

- *Type:* java.lang.String

---

##### `inputs`<sup>Required</sup> <a name="inputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.inputs"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getInputs();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSource.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### DataNullDataSourceConfig <a name="DataNullDataSourceConfig" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.Initializer"></a>

```java
import io.cdktn.providers.null_provider.data_null_data_source.DataNullDataSourceConfig;

DataNullDataSourceConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
//  .hasComputedDefault(java.lang.String)
//  .inputs(java.util.Map<java.lang.String, java.lang.String>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.hasComputedDefault">hasComputedDefault</a></code> | <code>java.lang.String</code> | If set, its literal value will be stored and returned. |
| <code><a href="#@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.inputs">inputs</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `hasComputedDefault`<sup>Optional</sup> <a name="hasComputedDefault" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.hasComputedDefault"></a>

```java
public java.lang.String getHasComputedDefault();
```

- *Type:* java.lang.String

If set, its literal value will be stored and returned.

If not, its value defaults to `"default"`. This argument exists primarily for testing and has little practical use.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#has_computed_default DataNullDataSource#has_computed_default}

---

##### `inputs`<sup>Optional</sup> <a name="inputs" id="@cdktn/provider-null.dataNullDataSource.DataNullDataSourceConfig.property.inputs"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getInputs();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of arbitrary strings that is copied into the `outputs` attribute, and accessible directly for interpolation.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/null/3.3.0/docs/data-sources/data_source#inputs DataNullDataSource#inputs}

---



