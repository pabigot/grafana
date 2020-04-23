+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "StandardEditorProps"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
draft = true
+++

## StandardEditorProps interface

<b>Signature</b>

```typescript
export interface StandardEditorProps<TValue = any, TSettings = any> 
```
<b>Import</b>

```typescript
import { StandardEditorProps } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [item](#item-property) | <code>StandardEditorsRegistryItem&lt;TValue, TSettings&gt;</code> |  |
|  [onChange](#onchange-property) | <code>(value?: TValue) =&gt; void</code> |  |
|  [value](#value-property) | <code>TValue</code> |  |

### item property

<b>Signature</b>

```typescript
item: StandardEditorsRegistryItem<TValue, TSettings>;
```

### onChange property

<b>Signature</b>

```typescript
onChange: (value?: TValue) => void;
```

### value property

<b>Signature</b>

```typescript
value: TValue;
```