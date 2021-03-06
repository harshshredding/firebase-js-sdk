<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [lite](./firestore_lite.md) &gt; [orderBy](./firestore_lite.orderby.md)

## orderBy() function

Creates a `QueryConstraint` that sorts the query result by the specified field, optionally in descending order instead of ascending.

<b>Signature:</b>

```typescript
export declare function orderBy(fieldPath: string | FieldPath, directionStr?: OrderByDirection): QueryConstraint;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fieldPath | string \| [FieldPath](./firestore_lite.fieldpath.md) | The field to sort by. |
|  directionStr | [OrderByDirection](./firestore_lite.orderbydirection.md) | Optional direction to sort by ('asc' or 'desc'). If not specified, order will be ascending. |

<b>Returns:</b>

[QueryConstraint](./firestore_lite.queryconstraint.md)

The created `Query`<!-- -->.

