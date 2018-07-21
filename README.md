# Translation for the IPS Explorer
Here is the Translation form the IPS-Explorer as is in English.

## Howto Translate

As seen below you see a Json File We do not translate the keywords just the Variable.
In order to translate this into example German it would look like:

English Version
```
{
  "translate": {
    "toggle": "Toggle navigation",
    "explorer": "Explorer",
    "reward": "Reward",
    "movement": "Movement",
    .....
```
Translated German Version (example)
```
{
  "translate": {
    "toggle": "Navigation umschalten",
    "explorer": "Explorer",
    "reward": "Belohnung",
    "movement": "Bewegung",
    .....
```
As you see we kept all the Keywords on the left side and just translated the Variabels on the right side.
Do not translate {{Variabel}} these are Variabels passed into the Translation Example:
English Version
```
    "balance_coin" : "Balance {{coin, uppercase}}",
    "received_coin" : "Received {{coin, uppercase}}",
````
German Version
```
    "balance_coin" : "Guthaben {{coin, uppercase}}",
    "received_coin" : "Erhalten {{coin, uppercase}}",
````

 You can either make a pull request or upload it to  https://hastebin.com/about.md