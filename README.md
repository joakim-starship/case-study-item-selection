# Case study item selection

This repository includes a set of json documents with random products.
Each page can be found at `items/{page_number}.json`.

## Document format

```
{
    items: {
        id: number,
        name: string,
        price: number
    }[],
    next: boolean
}
```
