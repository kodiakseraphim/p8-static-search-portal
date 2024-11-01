[**@globus/static-search-portal**](../../README.md) • **Docs**

***

# Type alias: ResultListingComponentOptions

> **ResultListingComponentOptions**: `object`

## Type declaration

### fields?

> `optional` **fields**: [`FieldDefinition`](FieldDefinition.md)[]

The fields to display in the result.
A field can be a string, an object with a `label` and `property`, or an object with a `label` and `value`.

#### Examples

```ts
["entries[0].content.purpose", "entries[0].content.tags"]
```

```ts
[
   "entries[0].content.tags",
   { label: "Purpose", "property": "entries[0].content.purpose" },
   { label: "Note", value: "Lorem ipsum dolor sit amet."}
]
```

### heading?

> `optional` **heading**: `string`

The field to use as the title for the result.

#### Default

```ts
"subject"
```

#### Example

```ts
"entries[0].content.title"
```

#### See

https://docs.globus.org/api/search/reference/get_subject/#gmetaresult

### image?

> `optional` **image**: `string` \| `object`

An image to display in the result.

#### Example

```ts
"entries[0].content.image"
```

### summary?

> `optional` **summary**: `string`

The field to use as the summary for the result.

#### Example

```ts
"entries[0].content.summary"
```

#### See

https://docs.globus.org/api/search/reference/get_subject/#gmetaresult

## Source

[src/components/ResultListing.tsx:31](https://github.com/globus/static-search-portal/blob/427d9e768bedde4f5dc3d367aa2f475355b36dde/src/components/ResultListing.tsx#L31)