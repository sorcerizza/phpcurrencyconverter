Currency Converter in PHP


## Code Example

```

$amount = $_POST['amount'];
$cur1 = $_POST['cur1'];
$cur2 = $_POST['cur2'];


//Fetch all complted items
$completeItems     = mysqli_fetch_all($completeResult, MYSQLI_ASSOC);
 
//Free result set
mysqli_free_result($completeResult);
mysqli_free_result($result);
  
mysqli_close($conn);
```


## Usage

Use to add/edit/delete tasks without persistence (no backend).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

0.1.0 Finalized the example

## Tests

Basic non-automated manual browser test aka no test :P



## Contact
#### sorcererizza
* E-mail: izzaannsamax@gmail.com

