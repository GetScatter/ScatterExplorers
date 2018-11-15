# ScatterExplorers
A repository of explorers for use within Scatter

### Adding new explorers

- Create a pull request adding your explorer to the correct blockchain in the "explorers.json" file. 
- **Fill out all of the fields, they are all required.**

```
{
  "name":"",            // The name of your explorer, this should be Title Case
  "account":"",         // A link to an account/address on your explorer
  "transaction":"",     // A link to a transaction on your explorer
  "block":"",           // A link to a block on your explorer
```

**A note about the links** - All links must be suffixed with `/{x}` in order to be parsed correctly inside of Scatter.

## Example Entry

```
{
  "name":"Bloks",
  "account":"https://bloks.io/account/{x}",
  "transaction":"https://bloks.io/transaction/{x}",
  "block":"https://bloks.io/block/{x}"
}
```
